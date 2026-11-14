# ÇağrıKalite AI

Tarayıcı üzerinden çağrı dinleme ve kalite değerlendirme için ücretsiz statik MVP.

## Yayına alma (GitHub Pages)
1. Repository → **Settings** → **Pages**.
2. **Build and deployment** altında Source: **Deploy from a branch** seçin.
3. Branch: **main**, Folder: **/(root)** seçip **Save**'e basın.
4. Birkaç dakika sonra uygulama şu adreste açılır: https://tugaycoskun5004-cmyk.github.io/CagriKaliteAI/

## Kullanım
- `index.html` dosyası uygulamanın giriş sayfasıdır.
- WAV/MP3 kaydını tarayıcıda oynatabilir, transkript/not ekleyebilir ve kalite kriterlerini işaretleyebilirsiniz.
- Kesin ihlal, ilgili bölümün puanını yalnızca bir kez düşürür.
- İnceleme gerekli seçeneği otomatik puan kesmez.
- Kritik sıfırlama kriterlerinden biri seçilirse toplam puan 0 olur.
- Değerlendirme geçmişi tarayıcının yerel depolamasında tutulur; cihazlar arasında senkronize olmaz.
- CSV dışa aktarımı bulunur.

## Sınırlamalar ve gizlilik
Bu MVP otomatik konuşma tanıma veya otomatik yapay zekâ değerlendirmesi yapmaz; sesin dinlenmesi ve kriterlerin işaretlenmesi kullanıcı tarafından yapılır. Gerçek vatandaş/sağlık verisi veya kişisel bilgi içeren çağrı kayıtlarını herkese açık depoya yüklemeyin. Bu prototipte kayıt ve değerlendirme verileri sunucuya gönderilmez.
