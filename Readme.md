# 🌐 Dash OnlineFoods Veri Seti Analizi
- Bu proje, OnlineFoods veri seti kullanarak bir Dash uygulaması geliştirmeyi amaçlamaktadır. Uygulama, kullanıcıların demografik verilerini ve yemek sipariş alışkanlıklarını analiz etmeye yönelik çeşitli görselleştirmeler sunar. 🍽️📊

# 🛠️ Kullanılan Teknolojiler
### Dash: Etkileşimli web tabanlı görselleştirme ve grafikler oluşturmak için kullanıldı.
### Plotly Express: Veri görselleştirmeleri için kullanıldı.
### Pandas: Veri manipülasyonu ve analiz için kullanıldı.
### pyngrok: Dash uygulamasını internet üzerinden erişilebilir hale getirmek için kullanıldı.

# 📋 Veri Seti
- Bu projede kullanılan veri seti OnlineFoods isimli bir CSV dosyasından alınmıştır. Veri seti, kullanıcıların demografik bilgilerini ve online yemek sipariş alışkanlıklarını içermektedir. 🧑‍💼🍔

### Veri seti şu sütunlardan oluşmaktadır:

### Age: Kullanıcının yaşı 👶👴
### Gender: Kullanıcının cinsiyeti 🚻
### Marital Status: Kullanıcının medeni durumu 💍
### Occupation: Kullanıcının mesleği 💼
### Monthly Income: Kullanıcının aylık geliri 💰
### Educational Qualifications: Kullanıcının eğitim durumu 🎓
### Family size: Kullanıcının aile büyüklüğü 👨‍👩‍👧‍👦
### Latitude: Kullanıcının coğrafi konumu (enlem) 🌍
### Longitude: Kullanıcının coğrafi konumu (boylam) 🌍
### Pin code: Kullanıcının posta kodu 🏠
### Output: Kullanıcının sipariş verdiği yemek türü 🍕🍔
### Feedback: Kullanıcının geri bildirimi 📝

# 📊 Kullanıcı Arayüzü
- Uygulama, kullanıcıların aşağıdaki grafikler arasında seçim yapmalarını sağlayan bir Dropdown menüsü içerir. Seçilen grafikle ilgili açıklamalar da eklenmiştir.

### Yaş Dağılımı: Kullanıcıların yaş dağılımını gösterir. 🎂
### Cinsiyet Dağılımı: Cinsiyet oranlarını pie chart şeklinde gösterir. ⚖️
### Medeni Durum Dağılımı: Medeni durum bilgilerini pie chart ile sunar. 💍
### Meslek Dağılımı: Kullanıcıların mesleklerine göre dağılımını bar chart olarak gösterir. 🧑‍💻
### Aylık Gelir Dağılımı: Kullanıcıların gelir seviyelerini gösterir. 💸
### Eğitim Durumu: Kullanıcıların eğitim seviyeleri dağılımını gösterir. 🎓
### Aile Büyüklüğü Dağılımı: Kullanıcıların aile büyüklükleriyle ilgili dağılımı sunar. 👨‍👩‍👧‍👦


# 🌍 Pyngrok ile Uzaktan Erişim
- Uygulamanızın internet üzerinden erişilebilir olması için pyngrok kullanılmıştır. Pyngrok, uygulamanızı internet üzerinden erişilebilir hale getirecek bir geçici URL sağlar.

- Not: Pyngrok kullanabilmek için ngrok sitesinden bir hesap oluşturup, kendi auth token'ınızı almanız gerekmektedir. Token'ınızı ngrok.set_auth_token("YOUR_TOKEN") satırına eklemeyi unutmayın.