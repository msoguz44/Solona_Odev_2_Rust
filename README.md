# Solona_Odev_2_Rust
**Örnek Kütüphane Programı:

Bir kütüphane yönetim sistemini temsil eden bir Rust programı yazın. Bu sistemde kitaplar ve dergiler farklı özelliklere sahip olacak şekilde tasarlanmalıdır. Sisteminiz, aşağıdaki gereksinimleri karşılamalıdır:

** Publication adında bir enum tanımlayın. Bu enum iki varyant içermelidir: /n
** Book ve Magazine. Her ikisi de farklı veri tipleri içermelidir:
** Book varyantı, title, author ve page_count alanlarına sahip bir struct içermelidir.
** Magazine varyantı, title, issue ve topic alanlarına sahip bir struct içermelidir.
** Kitap ve dergi örneklerini oluşturup, bu örnekleri içeren bir Vec<Publication> dizisi oluşturun.
** Dizideki her yayını, türüne (kitap veya dergi) göre farklı bir biçimde yazdıran bir fonksiyon yazın. 
Örneğin, kitaplar için "Kitap: [title] yazar: [author], [page_count] sayfa" ve dergiler için "Dergi: [title] - Sayı: [issue], Konu: [topic]" formatlarını kullanın.
