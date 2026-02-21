🔌 Serial Port Desktop Application

C# Windows Forms kullanılarak geliştirilmiş bir Serial Port (COM Port) haberleşme uygulamasıdır.

Bu uygulama sayesinde bilgisayar ile harici cihazlar (Arduino, sensör modülleri, mikrodenetleyiciler vb.) arasında seri port üzerinden veri gönderme ve alma işlemleri gerçekleştirilebilir.

🚀 Özellikler

Mevcut COM portları listeleme

Seçilen port ile bağlantı kurma / bağlantıyı kapatma

Seri porttan gelen verileri okuma

Seri port üzerinden veri gönderme

Baud Rate ve diğer port ayarlarını yapılandırma

Kullanıcı dostu Windows Forms arayüzü

🛠️ Kullanılan Teknolojiler

C#

.NET Framework 4.7.2

Windows Forms

System.IO.Ports


📌 Ana Bileşenler

Form1
Ana ekran – Port bağlantı ve veri işlemleri burada gerçekleştirilir.

NewForm
Ek işlem / yardımcı arayüz.

SettingsForm
Seri port ayarlarının yapılandırıldığı ekran.

Program.cs
Uygulamanın başlangıç noktası.

📂 Proje Yapısı
``` SerialPort.sln
│
└── SerialPort
    ├── Form1.cs
    ├── NewForm.cs
    ├── SettingsForm.cs
    ├── Program.cs
    └── App.config ```

⚙️ Kurulum ve Çalıştırma

1️⃣ Projeyi Klonlayın

``` git clone https://github.com/kullaniciadi/serialPort.git ```
