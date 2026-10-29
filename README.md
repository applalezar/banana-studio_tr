<p align="center">
  <img src="docs/assets/brand.svg" width="680" alt="Banana Studio" />
</p>

<p align="center"><strong>Bir fikirden görsele, YouTube kapağına ve videoya.</strong><br />Kendi API anahtarlarınla çalışan açık kaynak yaratıcı çalışma alanı.</p>

<p align="center">
  <a href="README_en.md">English</a> · <strong>Türkçe</strong> ·
  <a href="https://github.com/orkunisitmak/banana-studio/releases/latest">Mac / Windows indir</a> ·
  <a href="#özellikler">Özellikler</a> · <a href="#web-kurulumu">Web kurulumu</a>
</p>

<p align="center"><img src="docs/assets/gallery-real.jpg" width="1200" alt="Proje sahibinin gerçek iPhone kapak üretimleri, kişi referansları, prompt ve üretim kontrolleriyle web galerisinde" /></p>

<p align="center"><sub>Proje sahibinin hesabındaki gerçek üretimler ve arayüz görüntüleri, izniyle paylaşılmıştır. <a href="docs/assets/README.md">Demolar hakkında</a></sub></p>

**Banana Studio; görsel üretimi, seçili alan düzenleme, kapak planlama ve video üretimini aynı galeride toplar.** Bir cümleyle, referans görsellerle veya YouTube videosuyla başla. Brainstorm ile fikirleri keşfet, Enhance ile promptu geliştir, seçili alanı düzenle ve tek galeride video üret.

Uygulama [MIT lisansıyla](LICENSE) ücretsizdir. Yapay zekâ servisleri API kullanımını ayrıca ücretlendirir; model kredisi dahil değildir. Üretim için internet bağlantısı gerekir.

<a id="özellikler"></a>

## Brainstorm ile fikirler keşfet

Tek brief'ten **birbirinden farklı fikirler**, her fikir için de birden fazla görsel oluştur. Genel fikirler için **Simple**, kapak konseptleri için **YouTube** modunu seç. Fikir sayısı ve fikir başına görsel sayısı değiştirilebilir.

Brainstorm; brief'ini, seçtiğin People kayıtlarını ve referansların rollerini kullanır. YouTube kapaklarında okunabilir kompozisyon, kameraya bakan kişiler ve brief'te sabit kıyafet istenmediğinde farklı kıyafet planları üretir.

<p align="center"><img src="docs/assets/brainstorm-real.jpg" width="1000" alt="Gerçek kapakların üzerinde Brainstorm paneli: YouTube modu, beş fikir, aynı kişiye ait fotoğraf grubu ve üretilebilecek görsel sayısı" /></p>

## Enhance ile promptunu geliştir

Kısa fikrini kendi cümlelerinle yaz. **Enhance**, seçili görsel veya video modeline uygun daha açık talimatlar hazırlar: kişi/nesne, kompozisyon, ışık, referans rolleri; videoda hareket ve sahne planı.

Türkçe taslaklardan da üretim açıklamaları İngilizce hazırlanır; görselde görünmesini istediğin yazılar, özel isimler ve alıntılanan diyaloglar istenen dilde kalır. **AI settings** üzerinden model, düşünme seviyesi ve sağlayıcı seçeneklerini seç.

## Bir alanı düzenle, geri kalanını koru

**Edit image** aç, içi dolan serbest çizim **Mask** veya **Rectangle** ile alan seç, değişikliği anlat. Her seçim bir katmandır: **Shift + çizim** yeni katman ekler; yatay şeritten katmanı seçip yeniden çizebilirsin. Edit promptu için referans yükleyebilir, modeli ve kaliteyi seçebilirsin.

**Son seçimin dışındaki pikseller kaynak görselden korunur.** Referans eklemek normal üretim akışında kalır; korumalı edit yalnızca açıkça alan seçtiğinde başlar. Yeni siluet gerektiğinde ayrı katmanlar oluşturulur.

<p align="center"><img src="docs/assets/area-edit-real.jpg" width="1000" alt="Gerçek üretilmiş kapakta alan düzenleme: başlık ve fiyat dikdörtgen katmanda seçili; kişinin yüzü seçimin dışında korunuyor" /></p>

Editler iş olarak arka planda ilerler; ilerlemeyi ve yeni galeri sonuçlarını takip edebilirsin. Önceki sonucu beklemeden başka deneme gönder. **Kaynak/sonuç sliderı** ile karşılaştır, kaynağa dön veya sonucu seç.

<details>
<summary>Edit kontrollerini ve önce/sonra karşılaştırmasını gör</summary>

<p><img src="docs/assets/edit-controls-real.jpg" width="1000" alt="Gerçek edit prompt kutusu: referans yükleme, model, kalite, artı/eksi görsel sayısı ve Enhance" /></p>
<p><img src="docs/assets/comparison-real.jpg" width="1000" alt="Kaynak ve editlenen kapağın slider ile karşılaştırması: portre korunurken başlık değişiyor" /></p>

Yukarıdaki dikdörtgen ve taslak, edit kontrollerini göstermek için hazırlanmıştır; bu ekran görüntüleri için yeni üretim gönderilmemiştir. Karşılaştırma aynı hesaptaki daha önce tamamlanmış bir editi gösterir.

</details>

## YouTube videosundan kapak üretimine

**YT** ile kanal veya video bul, videoyu analiz et, bölümün ana vaadini kontrol et, gösterilecek kişileri seç. Brief'i Brainstorm'a gönder veya üretim öncesinde düzenle. Kanalın önceki kapaklarını ve referansları normal üretim akışında kullan.

Videoyu okuma ve yaratıcı brief ayrı sağlayıcı akışları kullanır. Gerekli kombinasyonu [anahtar rehberi](docs/tr/models.md) açıklar. [Kapak üretim adımlarını izle →](docs/tr/guide.md#youtube-kapagi-uretim-adimi)

## Metin, görsel ve referanslarla video üret

Süre, en-boy oranı, kalite ve girdiler için modele uygun kontrolleri kullan. **Seedance 2.0 / 2.5 Relaxed** ve **MiniMax H3 Max** farklı akışlar sunar; arayüz seçili moda uygun ayarları gösterir.

MiniMax H3 Max modları: **Text to Video Max · Image to Video Max · Reference to Video Max · Extend Video Max · Lip Sync Max · Recast**. Desteklenen modlarda görsel, video veya ses referansı ekle; Enhance ile hazırlanan kısa hedefi kullan, sonuç için gerekli tüm ayarları belirle.

<p align="center"><a href="https://github.com/orkunisitmak/banana-studio/raw/refs/heads/main/docs/assets/video-demo.mp4"><img src="docs/assets/video-preview.gif" width="640" alt="Gerçek üretilmiş video klibi" /></a></p>

<p align="center"><strong><a href="https://github.com/orkunisitmak/banana-studio/raw/refs/heads/main/docs/assets/video-demo.mp4">15 saniyelik gerçek klibi indir (MP4) →</a></strong><br /><sub>Sahibin hesabından alınmış gerçek üretim örneği; yalnızca belge amaçlı yayına uygun şekilde küçültülmüş ve ses/üretim meta verileri kaldırılmıştır.</sub></p>

<details>
<summary>Gerçek video oynatıcısını ve kayıtlı üretim bilgilerini gör</summary>

<p><img src="docs/assets/video-real.jpg" width="1000" alt="Gerçek galeri video oynatıcısı: seçili klip, prompt, kayıtlı model, süre ve kalite" /></p>

</details>

## Tüm projeni bir arada tut

| Özellik | Ne işe yarar? |
| --- | --- |
| **Görsel üretimi** | GPT Image 2.5, Nano Banana Pro ve Nano Banana 2.1; desteklenen modellerde oran, boyut/özel ölçü, kalite ve görsel sayısı. |
| **Referanslar ve `@` etiketleri** | Görsel yükle veya yeniden kullan; kimlik, nesne, stil veya sahne rolü ver. Referans eklemek alan editini zorlamaz. |
| **People** | Aynı kişinin kimlik fotoğraflarını grupla; birden fazla fotoğraf hâlâ tek kişiyi temsil eder. |
| **Referans kütüphanesi ve şablonlar** | Kaynakları, kayıtlı prompt ve ayar kombinasyonlarını farklı projelerde yeniden kullan. |
| **Re-create ve Variation** | Bir sonucun prompt ve ayarlarını geri yükle veya yeni varyasyon keşfet. |
| **Galeri düzeni** | İç içe klasör, favori, arama, görsel/video filtresi, grid yoğunluğu, çoklu seçim ve klasörler arası taşıma. |
| **Görüntüleyici ve karşılaştırma** | Doğal görsel oranı, zoom/kaydırma, yan yana görsel karşılaştırması ve kaynak/edit sliderı. Oklarla gezinme, **Shift+B** ile Details açma/kapatma ve mobil kaydırma. |
| **İşler ve geçmiş** | İlerleme, bildirimler, tamamlanan sonuçlar ve kurtarılabilen iş bilgileri; webde OpenAI görsel işleri kalıcı kuyruk kullanır. |
| **Üretim detayları** | Mevcut prompt, referans, boyut, model, kalite, maliyet, süre, hazırlama modeli/düşünme seviyesi ve kayıtlı edit katmanları/kaynağı. Eski kayıtlarda bazı alanlar eksik olabilir. |
| **İndirme ve paylaşım** | Görsel/video indir. Web alanında tamamlanmış görselleri görmek ve indirmek için süreli herkese açık klasör bağlantıları da oluşturulabilir. |
| **Çalışma alanı yönetimi** | Webde hesap erişimi ve sahip/yönetici kontrolleri; bağımsız masaüstü uygulamasında yerel çalışma alanı. |

[Görselli kullanım rehberini aç →](docs/tr/guide.md)

## Başlangıç

| Cihazın | Bugün sunulan sürüm | Buradan başla |
| --- | --- | --- |
| Apple Silicon işlemcili Mac | Bağımsız uygulama, macOS 13.5+ | [İndir](https://github.com/orkunisitmak/banana-studio/releases/download/v0.1.2/Banana-Studio-0.1.2-macos-arm64.zip) · [Kurulum rehberi](docs/tr/desktop.md) |
| Intel işlemcili Mac | Bağımsız uygulama, macOS 13.5+ | [İndir](https://github.com/orkunisitmak/banana-studio/releases/download/v0.1.2/Banana-Studio-0.1.2-macos-x64.zip) · [Kurulum rehberi](docs/tr/desktop.md) |
| Windows 10/11, 64-bit Intel/AMD | Bağımsız taşınabilir uygulama | [İndir](https://github.com/orkunisitmak/banana-studio/releases/download/v0.1.2/Banana-Studio-0.1.2-windows-x64.zip) · [Kurulum rehberi](docs/tr/desktop.md) |
| Diğer bilgisayarlar, telefon ve tablet | Tarayıcı üzerinden web sürümü | Kurulmuş web adresini aç; erişimi ve servis anahtarlarını web alanının sahibi yönetir. |

**Masaüstünde hızlı başlangıç:** indir → zip'i ayıkla → aç (Mac'te önce Uygulamalar'a taşı) → **Provider keys** → modelin anahtarını gir → üret. Bağımsız uygulamada **Supabase, Vercel, Google veya özel sunucu gerektirmez**.

## Modeller ve API anahtarları

API anahtarı, uygulamanın ilgili yapay zekâ servisindeki hesabını kullanmasını sağlayan özel bir erişim bilgisidir. Yalnızca kullanacağın servisleri ekle. Tablo **bu uygulamanın kullandığı yönleri** gösterir; model listesi değil.

| Model veya özellik | Sağlayıcılar (Auto önceliği) | Uygun anahtarlardan biri yeterli |
| --- | --- | --- |
| GPT Image 2.5 — yeni görsel ve korumalı alan editi | OpenAI → OpenRouter → fal.ai | `OPENAI_API_KEY` / `OPENROUTER_API_KEY` / `FAL_KEY` |
| Nano Banana Pro / Nano Banana 2.1 | fal.ai → Google Gemini → OpenRouter | `FAL_KEY` / `GEMINI_API_KEY` / `OPENROUTER_API_KEY` |
| Claude Opus 5.5 — Enhance, Brainstorm, varyasyon ve yaratıcı brief | OpenRouter | `OPENROUTER_API_KEY` |
| GPT-6.1 Sol — metin özellikleri | OpenAI → OpenRouter | `OPENAI_API_KEY` / `OPENROUTER_API_KEY` |
| Gemini 3.8 Flash — metin ve YouTube videosu analizi | Google Gemini → OpenRouter | `GEMINI_API_KEY` / `OPENROUTER_API_KEY` |
| Seedance 2.0 / 2.5 | EvoLink → fal.ai → OpenRouter (desteklenen işlemler) | `EVOLINK_API_KEY` / `FAL_KEY` / `OPENROUTER_API_KEY` |
| MiniMax H3 Max — metin/görsel/referanstan video, uzatma, lip sync ve recast | fal.ai | `FAL_KEY` |
| YouTube kanal/video araması | Google YouTube Data API v3 | `YOUTUBE_API_KEY` |

**Tek sağlayıcıyla başlayabilirsin:** **OpenRouter anahtarı** GPT/Nano görselleri, Opus/GPT/Gemini metin özellikleri, video analizi ve desteklenen Seedance işlemlerini açabilir. **fal.ai anahtarı** GPT/Nano görselleri, Seedance ve H3 Max videoyu açabilir; Enhance/Brainstorm için ayrı metin sağlayıcı gerektiğinde OpenRouter eklenir.

Varsayılan yaratıcı model **Opus 5.5 / Medium** olarak kalır. Modeli, düşünme seviyesini ve **Auto / belirli sağlayıcı** seçimini **AI settings** üzerinden yap. Sağlayıcı üretim başlatma öncesinde seçilir ve kaydedilen işlerle birlikte saklanır.

OpenRouter Seedance bu uygulamada metin, first/last frame ve görsel referanslarını destekler; sabit süre ve görüntü oranı gerekir, Seedance 2.5 için 480p/720p sunar. Video/ses referansı, Extend/Auto ve 1080p için fal.ai/EvoLink gerekir.

## Hangi sistemlerle çalışıyor?

Ortak arayüz **React + TypeScript + Vite** ile hazırlanır. Mac kabuğu **AppKit + WKWebView** kullanır; kendi **Node.js** sunucusunu taşır, verileri **SQLite + yerel dosyalara**, anahtarları **macOS Keychain / Windows Credential Manager** içinde tutar.

İşlemde kullanılan prompt ve referanslar ilgili sağlayıcıya gönderilir. Masaüstü ve web galerileri ayrıdır; Masaüstü uygulamaları otomatik bulut senkronizasyonu yapmaz. [Veri sınırları](SECURITY.md) · [Mimari](docs/tr/development.md)

<a id="web-kurulumu"></a>

## Kendi web alanını kur

Windows, Mac, mobil ve ekibin için tarayıcıdan açılan bir alan mı istiyorsun? Repoyu kendi GitHub hesabına kopyala, kendi Supabase projeni oluştur, Vercel'e deploy et. Supabase bilgilerini ve servis anahtarlarını güvenli şekilde yönetin; kullanıcı medya, yerel veritabanı veya özel hesap ayarlarını asla repoya eklemeyin.

Rehberde terminal gerektirmeyen SQL Editor yolu, değişken tablosu, kontrol adımları ve hata çözümleri bulunur. Hazır bir Banana Studio veritabanı veya kişisel hesap dahil değildir.

**[Adım adım web kurulum rehberini aç →](docs/tr/deploy.md)**

<p align="center"><sub><a href="LICENSE">MIT</a> · <a href="SECURITY.md">Güvenlik</a> · <a href="docs/tr/development.md">Katkıda bulun</a> · <a href="docs/THIRD_PARTY_NOTICES.md">Üçüncü taraf bildirimleri</a></sub></p>
