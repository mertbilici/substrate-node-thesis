# Substrate Düğümü

Bu yazılım "Yeşil Enerji Kanıtı" uzlaşma yöntemini kullanan bir substrate düğümüdür.

Yeşil Enerji Kanıtı, bilinen klasik uzlaşma algoritmalarına göre daha düşük enerji tüketimine sahip ve yenilenebilir enerji üretimini teşvik eden bir mekanizmadır. Özellikle eşler arası enerji ticareti için kullanılmak üzere Yüksek Lisans Tez çalışmam kapsamında geliştirilmiş ve açık kaynak kodlu olarak yayınlanmıştır.

## Kurulum

Düğümü bilgisayarınızda kullanmak için substrate'in resmi sitesindeki kurulum aşamalarını takip edebilir ve ardından bu düğümü indirerek çalıştırabilirsiniz.

### Derleme

Aşağıdaki komutu kullanarak bu programı derleyebilirsiniz.

"
cargo build --release
"

### Çalıştırma

Aşağıdaki komutu kullanarak bu programı çalıştırabilirsiniz.

"
./target/release/node-template -h
"
