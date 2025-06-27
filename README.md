# GPT Weather Stylist 👗🌦️

Bu proje, güncel hava durumu verilerine göre kullanıcıya uygun kıyafet önerileri sunan bir yapay zeka asistanıdır. LangChain, Streamlit ve OpenAI API kullanılarak geliştirilmiştir.

## 🧠 Proje Özellikleri

- 📍 Lokasyon bazlı hava durumu verisi çeker (WeatherAPI kullanılarak)
- 🧥 Sıcaklık, rüzgar, yağış gibi bilgilere göre kıyafet tavsiyesi verir
- 💬 Tüm çıktılar Türkçe ve kullanıcı dostu dilde sunulur
- 🔗 LangChain ile araç destekli düşünme modeli (ReAct) uygulanır
- 🎨 Streamlit ile sade ve etkileşimli web arayüzü

## 🔧 Kullanılan Teknolojiler

- Python
- Streamlit
- LangChain
- OpenAI API (GPT-3.5/GPT-4 destekli)
- WeatherAPI
- dotenv (çevresel değişkenler için)

## ⚙️ Kurulum

# 1. Bu projeyi klonlayın
git clone https://github.com/SezinKorogluu/gpt-weather-stylist.git
cd gpt-weather-stylist

# 2. Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

# 3. .env dosyasını oluşturun ve içine API anahtarlarınızı girin
echo OPENAI_API_KEY=your_openai_api_key >> .env
echo WEATHERAPI_KEY=your_weatherapi_key >> .env

# 4. Uygulamayı başlatın
streamlit run app.py

##🧪 Örnek Kullanım
Kullanıcıdan gelen soru:
Ankara'da bugün ne giysem?

Yanıt:
Ankara’da hava güneşli ve 24°C. Bugün hafif bir kazak veya uzun kollu tişört tercih edebilirsiniz. Üzerinize ince bir ceket almak faydalı olabilir. Spor ayakkabı ve güneş gözlüğü de iyi bir seçim olur.

##🛠️ Kullanılan Araçlar (Tools)
get_weather
Belirtilen konum için güncel hava durumu bilgisini çeker.

recommend_clothing
Hava durumu bilgisine göre uygun kıyafet önerileri sunar:

Sıcaklık aralığına göre öneriler

Hava koşullarına göre özel öneriler (yağmurlu, karlı, rüzgarlı, güneşli)

Mevsimsel uygunluk

##📌 Notlar
.env dosyası .gitignore içerisine eklenmiştir ve GitHub’a yüklenmez.

Bu proje sadece eğitim ve demo amaçlıdır.

##🧑‍💻 Geliştirici
Sezin Köroğlu
📍 Türkiye

⭐ Geliştirme önerileri ve katkılar için PR’lar (pull request) açıktır.

