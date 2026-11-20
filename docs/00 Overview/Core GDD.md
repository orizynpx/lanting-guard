---
version: 1.0.0
last_updated: 2026-11-20
revision_note: First creation
---

## Judul/Nama Aplikasi Permainan

Judul permainan ini adalah Lanting Guard: Rush the River. Judul utama (main title) dipilih untuk mewakili kegiatan inti yang dilakukan pemain, yaitu melindungi (guarding) rumah lanting. Sementara itu, subtitle ditambahkan sebagai hal yang menyerupai tagline, layaknya pada permainan HoloCure: Save the Fans!.

## Latar Belakang dan Motivasi

Permainan ini dikembangkan dengan tujuan memperkenalkan [rumah lanting](https://www.indonesia.travel/id/id/travel-ideas/culture/rumah-lanting) kepada masyarakat Indonesia atau bahkan masyarakat dunia. Rumah lanting sendiri sederhananya merupakan rumah dengan fondasi terapung dan diapungkan di pinggir sungai.

Walaupun begitu, rumah lanting memiliki risiko seperti hanyut terbawa arus atau rusak karena dihantam oleh objek yang mengapung di sungai, terutama sampah yang dibuang sembarangan. Hal tersebut mengakibatkan rumah lanting agak kurang aman untuk ditinggali. Sebagian hal yang dapat dilakukan untuk mengurangi risiko tersebut adalah membersihkan sungai dari sampah dan mencegah sampah masuk ke sungai. Sungai yang bersih dari polusi juga merupakan perwujudan dari Sustainable Development Goal (SDG) ke-6, yaitu air bersih dan sanitasi (clean water and sanitation), terutama target 6.3, sebagaimana berikut:

By 2030, improve water quality by reducing pollution, eliminating dumping and minimizing release of hazardous chemicals and materials, halving the proportion of untreated wastewater and substantially increasing recycling and safe reuse globally.

Genre tower defense adalah pilihan yang muncul pertama kali ketika membayangkan aksi apa saja yang dapat dilakukan kepada sebuah rumah, yakni mempertahankannya. Lebih tepatnya, mempertahankan rumah lanting dari hantaman sampah yang menjelma menjadi monster hidup sembari membawanya menyusuri sungai di pulau Kalimantan untuk menemukan sumber polusi tersebut. Melihat antusiasme pemain akan game bergenre roguelike deckbuilder (contohnya, Slay the Spire dan sekuelnya, Slay the Spire 2, beserta Balatro), genre roguelike deckbuilder dikombinasikan dengan tower defense berpotensi memikat target audience berupa anak muda berusia 10 tahun hingga orang dewasa berusia 40 tahun.

Untuk menjangkau pasar yang lebih luas lagi, game ini dikembangkan untuk didistribusikan pada perangkat seluler berupa ponsel Android. Clash Royale merupakan contoh game pada perangkat seluler yang sangat sukses dan merupakan salah satu game yang cukup menyerupai ide game ini secara konsep.

## Deskripsi Aplikasi Permainan

### High Concept Statement
Lanting Guard: Rush the River adalah sebuah aplikasi permainan berdasarkan budaya masyarakat Kalimantan berupa rumah lanting yang dipertahankan dari serangan monster berwujud limbah menggunakan perahu tradisional Kalimantan (disebut jukung) dengan tujuan menemukan sumber limbah sungai.

### Story

Rumah lanting dinavigasikan oleh seorang pemuda Kalimantan Selatan yang bernama Galih. Dia merasakan dampak dari perubahan iklim yang menyebabkan air sungai meninggi sekaligus perusahaan yang tak bertanggung jawab yang membuang limbah industri di sekitaran hulu sungai sehingga mengalir ke hilir tempat dia tinggal. Dia memanfaatkan teknologi rumah lanting untuk menyusuri sungai dan menempatkan perahu (jukung) yang melindungi rumah tersebut dari serangan monster sampah. Sampah tersebut dia daur ulang untuk membuat perahu baru atau memperbaiki perahu yang ada. Tujuannya adalah menemukan sumber penyebab limbah tersebut berasal.

### Mechanics and Players’ Role

Tujuan pemain adalah menyusuri map dari satu titik ke titik lain hingga sampai ke titik bos akhir. Titik tersebut umumnya berupa sebuah pertarungan (battle). Battle terdiri dari satu atau lebih gelombang (wave). Gelombang berisi sejumlah monster sampah yang akan menyerang. Sebelum tiap gelombang, pemain diminta menempatkan perahu (jukung) di hadapan rumah lantingnya dengan cara memainkan kartu jukung (“tower”). Ketika gelombang berlangsung, perahu-perahu akan dengan sendirinya menyerang monster yang bergerak menuju rumah lanting. Kartu barang mencakup kegunaan seperti memperlambat progres monster, memperbaiki perahu, bahkan mengenakan damage yang cukup besar kepada monster. Setelah seluruh wave dalam sebuah battle berhasil dilalui, pemain akan dihadiahi sejumlah uang dan kartu-kartu baru untuk ditambahkan ke dalam dek.

Player sendiri memainkan peran sebagai Galih, yang mengendalikan rumah lanting dan membawanya menyusuri aliran sungai. Di dalam permainan, pemain mendapati peta (graph bercabang) yang menggambarkan aliran sungai, dari hilir (node terbawah) ke hulu (node teratas). Node dapat berupa Pertarungan (Combat), Pertarungan Bos (Boss Combat), Pasar Terapung (Shop), Dermaga (Port), Harta Karun (Treasure), atau Peristiwa (Event).

Angka baseline untuk permainan ini adalah 5 dan kelipatannya.
Player memulai permainan dengan 5 Slot Jukung dan 5 Energi. Slot Jukung dan Energi dapat ditingkatkan melalui opsi upgrade di Dermaga.

HP (health points) rumah lanting adalah 100.
HP baseline jukung 30.
HP baseline musuh adalah 20.
Damage baseline jukung dan musuh adalah 5.
Player memulai game dengan 100 rongsokan (scrap).

Terdapat dua jenis kartu: kartu jukung (unit card) dan kartu barang (item card).

Kartu jukung berfungsi seperti plant seed di Plants vs Zombies, dalam artian kita hanya memiliki 1 kartu jukung, tetapi kita bisa menaruh banyak kartu jukung (1:N dalam notasi perancangan basis data). Kartu jukung dapat diibaratkan sebagai relic di Slay the Spire. Kita tidak bisa memiliki relic duplikat di Slay the Spire, alias relic bersifat unique, seperti primary key dalam basis data. Kartu jukung di dalam story digambarkan sebagai cetak biru (blueprint), sehingga menjelaskan mengapa kita bisa mendapatkan jukung di dalam peti harta karun atau membelinya dari pedagang di pasar terapung.

Kartu barang berfungsi seperti troop di Clash Royale, dalam artian kita memiliki jumlah kartu yang tak dapat diubah (8 kartu jika menyesuaikan Clash Royale). Ketika kita memulai Fase Bertarung, kita diberikan 4 kartu acak dari dek. Jika suatu kartu dimainkan, kartu baru akan menempati posisinya. Kartu kemudian berotasi (cycle). Tidak ada Draw dan Discard Pile layaknya Slay the Spire untuk meminimalisir cognitive load di tengah pertarungan, yang merupakan high-action sequence. Kartu barang dapat diibaratkan sebagai card di Slay the Spire. Walaupun kita hanya memiliki 8 slot kartu di dalam dek, kita dapat memiliki kartu yang sama (duplikat). Kartu barang di dalam story digambarkan sebagai barang nyata. Energi digambarkan sebagai tenaga yang diperlukan untuk memanfaatkan barang tersebut (melempar parang, menjatuhkan jaring, atau melakukan perbaikan jukung).

Statistik yang ada di dalam permainan:

Health Points (HP): Melambangkan seberapa “sehat” rumah lanting milik player. Player memulai game dengan 100 HP. HP dapat ditingkatkan dari Peristiwa (Event) tertentu.
Slot Jukung: Melambangkan berapa banyak jukung yang dapat dikerahkan oleh player pada suatu waktu. Player memulai game dengan 5 slot. Slot ini dapat ditingkatkan dengan memilih opsi upgrade slot di Dermaga (Port) atau Peristiwa tertentu atau membelinya di Pasar Terapung (Shop).
Misalnya, Jukung A menempati 1 slot, Jukung B menempati 2 slot, dan Jukung C menempati 3 slot. Player bisa memilih untuk menaruh 5 buah Jukung A; 2 buah Jukung B dan 1 buah jukung A; atau 1 buah Jukung B dan 1 buah Jukung C. Slot ini BUKAN merupakan posisi pada sungai, melainkan batasan numerik.
Energi: Melambangkan banyak tenaga yang perlu dikeluarkan untuk menggunakan kartu barang. Player memulai game dengan 5 energi. Jumlah energi dapat ditingkatkan dengan memilih opsi upgrade energi di Dermaga atau Peristiwa tertentu atau membelinya di Pasar Terapung.
Slot Kartu: Seberapa banyak kartu barang yang dapat dimiliki player. Jumlah kartu jukung tidak dibatasi. Player hanya dapat memiliki 8 kartu barang, dan ketika memperoleh kartu barang baru, player diharuskan mengganti kartu yang sudah ada.
Rongsokan (Scrap): Mata uang di dalam game. Diperoleh sebagai reward memenangkan Pertarungan atau dari Peristiwa tertentu. Player memulai game dengan 100 rongsokan. Player dapat menghabiskan rongsokan di Pasar Terapung untuk membeli kartu atau upgrade stat.

Sketsa dari permainan:

### Genre

Genre permainan ini secara luas adalah strategi. Lebih spesifiknya, genrenya adalah penggabungan antara tower defense dan roguelike deckbuilder.

### Competition Modes

Permainan ini bersifat single player. Pemain hanya akan melawan musuh yang ada di dalam permainan (PvE), tidak melawan pemain lainnya (PvP).
General Summary of Progression
Dari hilir, ke hulu. Permainan dimulai dari muara sungai yang kemudian bercabang sehingga memungkinkan pemain untuk memilih level untuk dituju. Selain “ruangan” battle (pertarungan), juga terdapat ruangan shop (pasar terapung), rest site (dermaga), dan treasure. Dari sana, pemain bisa mendapatkan perlengkapan dan memulihkan rumahnya. Permainan berakhir pada hulu sungai tempat bos terakhir (final boss) berada.

### Progression

Player harus melalui TEPAT 10 node (tidak lebih dan tidak kurang) untuk memenangkan game.
Rute yang dipilih player memiliki tepat 1 Harta Karun, 1-2 Pasar Terapung, 2-3 Dermaga, 0-2 Peristiwa, 2-4 Pertarungan, dan tepat 1 Pertarungan Bos.
Urutan pencapaian node dapat berubah, kecuali sebagai berikut:
Salah satu Pertarungan selalu berada pada barisan node 1.
Harta Karun selalu berada pada barisan node 6.
Salah satu Dermaga selalu berada pada barisan node 9 untuk mengizinkan player heal/upgrade sebelum Pertarungan Bos.
Pertarungan Bos selalu berada pada node 10.

Contoh progression sederhana:

Node diberi ikon saja, tetapi terdapat legenda peta yang menjelaskan maksud dari ikon.

Pertarungan (Combat): Berisi Gelombang (Wave) yang harus dilewati oleh player. Memenangkan Pertarungan akan memberikan player sejumlah rongsokan dan opsi kartu barang (kartu jukung tidak bisa didapatkan dari sini).
Dermaga (Port): Berisi 3 opsi, yaitu Perbaiki Rumah (Heal) yang mengembalikan 30% HP; Tingkatkan Slot Jukung yang menambahkan 1 slot; dan Tingkatkan Energi yang menambahkan 1 energi. Gratis.
Pasar Terapung (Shop): Berisi sekumpulan opsi kartu yang dapat dibeli (anggaplah 4 kartu barang dan 2 kartu jukung) dan upgrade slot jukung atau energi.
Harta Karun (Treasure): Berisi opsi 1 dari 3 kartu jukung. Gratis.
Peristiwa (Event): Berisi skenario singkat yang menjelaskan apa yang terjadi dan apa opsi yang dapat dilakukan pemain. Umumnya berupa tradeoff (contoh: meningkatkan HP tapi mengurangi energi).
Pertarungan Bos (Boss Combat): Juga berisi Gelombang layaknya Pertarungan biasa, tetapi Gelombang juga berfungsi sebagai “boss phases”.

Pertarungan terdiri dari 1 atau lebih Gelombang (Wave). Suatu Gelombang terdiri dari 2 Fase, yaitu Fase Bersiap dan Fase Bertarung.

Fase Bersiap (Pre-Wave):
Player diberikan SELURUH kartu jukung yang mereka miliki.
Player dapat menaruh jukung di sungai dengan cara drag-and-drop ATAU klik kartu kemudian klik lokasi untuk menaruh jukung (untuk mempersingkat penjelasan, cara ini akan disebut point-and-click).
Player dapat menaruh jukung di area yang ditentukan (area akan di-highlight ketika drag-and-drop atau mengeklik kartu).
Batas area tersebut adalah di depan rumah lanting (yang terletak di bagian bawah layar) hingga bagian atas layar.
Player dapat memindahkan jukung yang sudah ditaruh dengan cara yang sama dengan menaruhnya (drag-and-drop atau point-and-click).
Player dapat menarik kembali jukung dari sungai dengan cara drag-and-drop atau point-and-click menjauh dari sungai dan menjatuhkannya di hand.
Jika merupakan Fase Bersiap untuk Gelombang 2 dst., HP jukung akan kembali seperti semula (full).
Tiap jukung akan menempati sejumlah slot tertentu.
Player dapat menggeser (scroll) layar ke atas untuk melihat seluruh musuh yang akan menyerang pada fase berikutnya.

Fase Bertarung (Mid-Wave)
Musuh muncul (spawn) off-screen pada bagian atas layar dan bergerak ke bawah secara real-time.
Penempatan jukung tidak dapat diubah. Jukung juga tidak bisa ditarik.
Pada fase ini, player diberikan 4 kartu barang secara acak dari dek mereka. Memainkan kartu akan memakan Energi sesuai dengan yang tertera pada informasi kartu.
Energi hampir sama dengan Elixir di Clash Royale.
Artinya, energi beregenerasi tiap beberapa detik dan memiliki batas maksimal energi.
Player memulai game dengan maksimal 5 energi.
Tiap kali fase ini dimulai, energi dihitung dari 0. Tiap beberapa detik, player akan mendapat 1 energi.
Jika ada jukung yang hancur (HP-nya menjadi 0 akibat serangan musuh) pada fase ini, Slot Jukung player akan berkurang sesuai jumlah slot yang digunakan jukung UNTUK SEMENTARA WAKTU (temporarily) hingga Pertarungan selesai (player menang).

### Target Audience

Anak muda 10 tahun ke atas hingga orang dewasa berusia 40 tahun yang menggemari permainan tower defense dan/atau roguelike.

## Teknologi dan Sumber Daya yang Dipergunakan

Game engine yang digunakan untuk mengembangkan aplikasi permainan ini adalah Godot Engine dengan kode yang ditulis dalam bahasa pemrograman bawaannya, yaitu GDScript.

Untuk pembuatan aset visual, aplikasi yang digunakan adalah Aseprite, karena gaya visual yang digunakan adalah pixel art.

Untuk pembuatan soundtrack, aplikasi yang digunakan adalah Audacity. Soundtrack permainan sendiri didapat dengan melakukan outsourcing kepada rekan salah seorang anggota. Tautan menuju profil rekan tersebut: https://www.youtube.com/@Medlek.

Selama pengembangan, perangkat keras yang digunakan adalah laptop masing-masing anggota yang menjalankan sistem operasi Windows 11. Pengetesan dapat dilakukan langsung di laptop atau di ponsel anggota yang menjalankan Android.
