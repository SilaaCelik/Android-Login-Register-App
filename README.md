<p>
  Android Kayıt ve Giriş Paneli Uygulaması (UyePaneliApp)
Bu proje, temel bir kullanıcı kayıt ve giriş sistemini içeren, verilerin kalıcı olarak saklanması için SharedPreferences teknolojisini kullanan bir Android mobil uygulamasıdır.

🚀 Proje Özellikleri
Kullanıcı Kaydı: Kullanıcıların bir kullanıcı adı ve şifre belirleyerek sisteme kaydolmasını sağlar.
Giriş Sistemi: Kayıtlı bilgilerin doğrulanmasıyla güvenli giriş imkanı sunar.
Veri Saklama: Kullanıcı bilgileri uygulamanın SharedPreferences alanında anahtar-değer (key-value) çiftleri olarak tutulur.
Dinamik Karşılama: Giriş yapan kullanıcıyı ismiyle karşılayan özel bir ana ekran barındırır.

🛠 Kullanılan Teknolojiler
Dil: Java
Arayüz (UI): XML (LinearLayout ve ConstraintLayout yapıları)
Depolama: SharedPreferences (Yerel veri saklama)
Araçlar: Android Studio SDK

📂 Uygulama Akışı
Giriş Ekranı (MainActivity): Uygulama açıldığında kullanıcıyı karşılar. Kayıtlı değilse "KAYDOL" seçeneğine yönlendirir.
Kayıt Ekranı (MainActivity2): Kullanıcı adı ve şifre bilgilerini alır, doğrular ve cihaza kaydeder.
Başarı Ekranı (MainActivity3): Bilgiler doğru girildiğinde kullanıcının ismini ekrana basarak hoş geldin mesajı gösterir.

💡 Kurulum ve Çalıştırma
Bu projeyi bilgisayarınıza indirin veya klonlayın.
Android Studio ile projeyi açın.
XML dosyalarındaki "Namespace" (android:) tanımlamalarının ve yerleşim kısıtlamalarının (layout_width/height) doğru yapılandırıldığından emin olun.
Bir emülatör veya gerçek bir Android cihaz üzerinde çalıştırın.
</p>
