SniperCart
SniperCart, çevrimiçi mağazalarda stok durumu hızla tükenen ürünleri takip eden ve satışa sunulduğu anda sizin için otomatik olarak satın alma işlemini gerçekleştiren bir Selenium tabanlı alışveriş botudur. Hız ve güvenilirlik odaklı olarak tasarlanan bu bot, fırsatları kaçırmamanız için geliştirilmiştir.

Özellikler
Çevrimiçi mağazaları sürekli izler ve stok durumu değişikliklerini tespit eder.
Ürün satışa sunulduğunda hızlıca satın alma işlemini gerçekleştirir.
CAPTCHAları ve HTTP yönlendirmelerini etkili bir şekilde yönetir.
Esnek yapılandırma: İzlenecek ürünler ve mağazalar kolayca ayarlanabilir.
Kullanıcı dostu yapılandırma ve hata yönetimi.
Gereksinimler
Python (3.8 veya daha üstü)
Selenium
Tarayıcı sürücüsü (örn. ChromeDriver)
Gerekli Python Paketleri:
bash
Kodu kopyala
pip install -r requirements.txt
Kurulum
Depoyu klonlayın:

bash
Kodu kopyala
git clone https://github.com/kullanici_adiniz/SniperCart.git
cd SniperCart
Gereksinimleri yükleyin:

bash
Kodu kopyala
pip install -r requirements.txt
Tarayıcı sürücüsünü indirin ve sistem PATH'ine ekleyin.
Örneğin: ChromeDriver

Config dosyasını düzenleyin:
config.json dosyasında izleyeceğiniz ürünlerin URL'lerini ve kullanıcı bilgilerini ekleyin.

Kullanım
Botu başlatmak için aşağıdaki komutu çalıştırın:

bash
Kodu kopyala
python main.py
Bot, belirtilen ürünleri izlemeye başlayacak ve stok durumu değiştiğinde satın alma işlemini otomatik olarak gerçekleştirecektir.

Örnek Kullanım
json
Kodu kopyala
{
  "products": [
    "https://example.com/product1",
    "https://example.com/product2"
  ],
  "user_details": {
    "email": "kullanici@example.com",
    "password": "sifre"
  }
}
Uyarılar
Bu bot yalnızca kişisel kullanım içindir. Kullanımı sırasında mağazaların hizmet şartlarına dikkat edin.
Çok hızlı sorgulamalar yapmak bazı mağazaların IP adresinizi engellemesine yol açabilir. Bu nedenle botun hızını dikkatlice yapılandırın.
Katkıda Bulunmak
Eğer bu projeyi geliştirmek isterseniz, pull request'ler göndererek katkıda bulunabilirsiniz. Hatalar veya öneriler için bir issue oluşturabilirsiniz.

Lisans
Bu proje, MIT Lisansı kapsamında lisanslanmıştır.

