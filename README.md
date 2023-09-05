# Dataset Klasörleri

Bu klasörde, farklı projeler için kullanılan veri setlerini bulabilirsiniz. Her proje klasörü kendi içinde, ilgili projenin ayrıntılarına, dataset özelliklerine ve diğer bilgilere dair bir `README.md` dosyasını içermektedir.


## Kullanım
Bir projenin datasetini ve detaylarını incelemek için ilgili proje klasörüne gidin ve `README.md` dosyasını okuyun. Bu dosya size projenin veri seti hakkında geniş bilgi verecektir.

### AWS S3 ile Dosya ve Klasör Yükleme
- Yeni Bir Klasör Ekleme: `aws s3 cp <yerel-klasör-yolu> s3://<bucket-ismi>/<hedef-klasör>/ --recursive`
- Dosya Yükleme: `aws s3 cp <yerel-dosya-yolu> s3://<bucket-ismi>/<hedef-dosya>`
