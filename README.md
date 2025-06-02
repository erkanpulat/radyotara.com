# 🔗 [radyotara.com](https://radyotara.com/) 

### 🎯 Proje Amacı ve Hikayesi

Radyotara.com, Türkiye'deki radyo frekanslarına şehir ve ilçe bazlı olarak kolayca ulaşılabilmesini sağlamak amacıyla geliştirildi. Projenin çıkış noktası ise askerlik dönemimde yaşadığım basit ama tam çözülememiş bir sorun oldu. Görev yaptığım şehirde radyo dinlemek istediğimde, “Bu bölgede hangi radyo hangi frekansta yayın yapıyor?” sorusuna net bir cevap bulmak oldukça zordu.

Görev sürem tamamlandıktan sonra bu problemi başkalarının da yaşamaması için kalıcı bir çözüme kavuşturmak istedim. Yaptığım araştırmalar sonucunda mevcut kaynakların çoğunun ya kullanıcıya pratik bilgi sunamadığını, ya ulaşım açısından yetersiz kaldığını ya da güncel olmadığını fark ettim.

Bu nedenle herkesin kolayca kullanabileceği, sade, hızlı ve mobil uyumlu bir sistem oluşturma fikriyle yola çıktım. İşte Radyotara.com’un kısa serüveni bu şekilde. 🙂

---

### ⚙️ Teknik Detaylar

- Proje **Angular 19** ile geliştirilmiştir. **Static Site Generation (SSG)** yapısı kullanılmıştır.  
  Sayfalar önceden oluşturulduğu için site hızlı açılır ve SEO açısından yüksek performans sağlar.  
  Şu anda yaklaşık **1.600 sayfa**, arama motorları tarafından indekslenmiştir.

- Veri seti, özel olarak hazırlanan bir script aracılığıyla oluşturulmuştur.  
  Tüm radyo kanalları, şehirler ve frekanslar önce **ilişkisel JSON yapısı**yla ayrı ayrı kaydedilmiştir.

- Bu ana kaynaklar kullanılarak, **her şehir, ilçe ve radyo sayfası** için özelleştirilmiş JSON dosyaları üretilmiştir.  
  Build sürecinde bu dosyalar kullanılarak statik sayfalar oluşturulmuştur.

---

### 📸 Ekran Görüntüleri
<p align="center"> <img src="https://github.com/user-attachments/assets/5018d7d1-fa01-4f5c-9caa-271742f01a76" alt="radyotara.com – Ana Sayfa" /> <br /> <em>(Ana Sayfa)</em> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/63ea00e6-e59f-4950-91d0-97297061013a" alt="radyotara.com – Şehir Sayfası" /> <br /> <em>(Şehir Sayfası)</em> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/665d26c4-78a2-484c-a502-a9f0f7c5d2a2" alt="radyotara.com – Radyo Sayfası" /> <br /> <em>(Radyo Sayfası)</em> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/b72187db-03a8-4f2d-981f-b43377eba872" alt="radyotara.com – Radyo Sayfası" /> <br /> <em>(Aşkın Frekansı Sayfası)</em> </p>

