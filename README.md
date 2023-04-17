# Anggota Kelompok
- Angga Gamma Putra 01082200030@student.uph.edu
- Ferdynand Chandra 01082200014@student.uph.edu
- Gabriela Bianka Eva Ivanka Bimbin 01082200031@student.uph.edu

# PENDAHULUAN
Ini adalah sebuah Sistem Information Retrieval dengan Vector Space Model dan sebuah dataset dari ir_datasets : vaswani

# Dataset
https://ir-datasets.com/vaswani.html

"vaswani"
Sebuah korpus kecil yang terdiri dari sekitar 11.000 abstrak ilmiah.

Dokumen: Abstrak ilmiah
Pertanyaan: Kata kunci bahasa alami
Informasi Dataset = http://ir.dcs.gla.ac.uk/resources/test_collections/npl/
 
# Koleksi NPL
Koleksi NPL (juga dikenal sebagai VASWANI) adalah koleksi sekitar 10.000 judul dokumen. Koleksi ini memiliki sedikit reputasi "mengacaukan eksperimen orang".

# Mengacaukan eksperimen orang
Menurut situs web Glasgow IDOM, koleksi NPL memiliki reputasi merusak eksperimen seseorang karena memiliki rata-rata presisi dan recall yang sangat rendah dibandingkan dengan koleksi lainnya. Ini berarti bahwa sistem temu kembali informasi yang menggunakan koleksi ini sering gagal menemukan dokumen yang relevan atau mengembalikan terlalu banyak dokumen yang tidak relevan. Situs web tersebut juga menyarankan bahwa hal ini mungkin disebabkan oleh kualitas buruk dari kueri atau judul dokumen, yang terlalu pendek atau samar-samar untuk menangkap makna dari dokumen tersebut. 
Teknik NLP dapat digunakan untuk menganalisis teks dari kueri dan dokumen untuk mengekstrak informasi yang lebih bermakna yang dapat digunakan untuk meningkatkan akurasi hasil pencarian. Dengan demikian, teknik NLP dapat membantu meningkatkan kualitas dan relevansi hasil pencarian pada koleksi NPL.

*** Bit-bit***
- doc-text - document dalam bentuk teks
- query-text - query dalam bentuk teks
- doc-vecs - document yang diwakili oleh ID vocab
- query-vecs - query yang diwakili oleh ID vocab
- term-vocab - Tabel vocab  dengan ID yang sesuai
- rlv-ass - Penilaian relevansi
- term-vecs - Berkas berisi angka, tidak tahu apa fungsinya
- term-vocab - Berkas lain yang berisi angka-angka

# npl.tar.gz
http://ir.dcs.gla.ac.uk/resources/test_collections/npl/npl.tar.gz

# Repositori Github
https://github.com/Mingmong123/NLP-UAS

# Google Collab Main-Branch notebook
https://colab.research.google.com/drive/1AizUfUtzFvk0tgKrrBAT8iKhZ5oD8RzH?usp=sharing
