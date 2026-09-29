Nathalie Tampubolon
D4 Teknologi Rekayasa Perangkat Lunak
41426015

EKSPERIMEN TERARAH
1.Hapus tag penutup article, muat ulang, dan periksa DOM.
   gejala   : artikel tidak muncul
   penyebab : </article> tidak ada
   perbaikan: menambahkan </artikel>
   hasil    : berhasil

2 Ubah salah satu id section sehingga tautan navigasi tidak menemukan tujuan.
   gejala   : tidak bisa membuka tautan section
   penyebab : penamaan section id salah
   perbaikan: menyesuaikan id section dengan id tautan di nav
   hasil    : berhasil


3 Tambahkan h4 langsung setelah h2 tanpa h3, lalu evaluasi hierarkinya.
   gejala   : struktur tidak sesuai yang menyebabkan error di validator
   penyebab : h4 dibawah h2 tapi tidak sesuai struktur heading
   perbaikan: membuat h3 diatas h4 agar bisa sesuai struktur heading.
   hasil    : berhasil

    
4 Letakkan main di dalam header, jalankan validator, kemudian perbaiki.
   gejala   : main berada di header
   penyebab : <main> diletakkan dalam header yang tidak sesuai struktur html yang benar
   perbaikan: <main> memindahkan main dibawah header
   hasil    : berhasil