#!/bin/bash

# Menulis header ke README.md
echo "# Daftar Folder dan File" > README.md

# Menulis daftar folder dan file dalam format markdown ke README.md
echo "\n## Struktur Direktori\n" >> README.md
echo '```' >> README.md
tree -L 2 >> README.md
echo '```' >> README.md


# My Project

Ini adalah deskripsi proyek saya.

![Hero Image](https://github.com/siegrin/MyWebsite/blob/main/website.png)

Informasi tambahan tentang proyek.
