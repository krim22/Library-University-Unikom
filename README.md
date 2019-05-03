# Aplikasi perpustakaan

## fitur
* tambah anggota
* pinjam buku untk anggota (yang bukan anggota gak boleh pinjam)
* anggota hanya bisa meminjaman  buku kemudian baru bisa pinjam lagi ketika buku taleh dikembalian.
* hitung denda
* lihate daftar anggota yang pinjam buku terbanyak

## perancangan Data
Anggota (id , nama, universitas, jurusan, member Sejak ,masa beriaku,jumlah Buku)
buku ( id , isbn , judul , pengarang , penerbit )
penerbit(id ,nama, website , alamat)
transaksi ( id , tangal pinjam , tangal kembali , buku , anggota , kembali )

![perancangan Data](/exports/Library-D-Class.png)


# Application de la bibliothèque

## caractéristiques
* ajouter des membres
* emprunter des livres pour les membres (ceux qui ne sont pas membres ne peuvent pas emprunter)
* Les membres peuvent uniquement emprunter des livres et peuvent ensuite les emprunter à leur retour.
* calculer l'amende
* Regardez la liste des membres qui empruntent le plus de livres

## Conception des données
Membres (identifiant, nom, université, département, membre depuis, donnez-moi du temps,nombre de livres)
livre (id, isbn, titre, auteur, éditeur)
éditeur (identifiant, nom, site web, adresse)
transactions (identifiant, prêt, retour, livre, membre, retour)


# Data design
Members (id, name, university, department, member Since, period of giving, number of Books)
book (id, isbn, title, author, publisher)
publisher (id, name, website, address)
transactions (ID, loan, return, book, member, return)