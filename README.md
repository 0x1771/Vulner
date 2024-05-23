# Vulner

Vulner, web uygulamalarınızın güvenliğini sağlamak için tasarlanmış otomatik bir web güvenlik tarama aracıdır. Bu araç, potansiyel güvenlik açıklarını belirleyerek geliştiricilere ve güvenlik uzmanlarına yardımcı olur.

## Özellikler

- Otomatik Güvenlik Taraması: Web uygulamalarınızı düzenli aralıklarla otomatik olarak tarar.
- Çoklu Güvenlik Açığı Desteği: SQL Injection, XSS, CSRF, ve daha birçok yaygın web güvenlik açığını tespit eder.
- Kullanıcı Dostu Arayüz: Basit ve anlaşılır bir komut satırı arayüzü ile kullanım kolaylığı sağlar.
- Raporlama: Detaylı raporlar oluşturarak bulunan güvenlik açıklarını listeler ve bunları düzeltmek için öneriler sunar.
- Özelleştirilebilirlik: Tarama parametreleri ve yöntemleri kolayca yapılandırılabilir.

## Kurulum

Vulner'ı kullanmaya başlamak için aşağıdaki adımları izleyin:

### Gereksinimler

- Python 3.x
- Gerekli Python paketleri (requirements.txt dosyasına bakınız)

### Adımlar

1. **Depoyu klonlayın:**

    ```bash
    git clone https://github.com/yourusername/vulner.git
    cd vulner
    ```

2. **Gerekli paketleri yükleyin:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Aracı çalıştırın:**

    ```bash
    python vulner.py
    ```

## Kullanım

Vulner'ı kullanarak bir web uygulamasını taramak oldukça basittir. Aşağıdaki komutu kullanarak taramayı başlatabilirsiniz:

```bash
python vulner.py -u http://hedefwebsiteniz.com
Katkıda Bulunma

Katkıda bulunmak istiyorsanız, lütfen aşağıdaki adımları izleyin:

    Bu depoyu fork edin.
    Yeni bir dal (branch) oluşturun: git checkout -b ozellik-adi
    Yaptığınız değişiklikleri commit edin: git commit -m 'Yeni bir özellik ekledim'
    Değişiklikleri dalınıza push edin: git push origin ozellik-adi
    Bir Pull Request açın.

Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.
İletişim

Sorularınız veya önerileriniz için lütfen bizimle iletişime geçin:

    E-posta: fakesmileux@gmail.com
    GitHub Issues: https://github.com/0x1771/Vulner/issues
