# Discord Hata Bildirim Botu

Bu proje, Discord sunucunuzdaki belirli bir kanala otomatik olarak hata mesajları göndermenizi sağlayan bir bot geliştirmek için oluşturulmuştur. Kodlarınızda bir hata oluştuğunda, bu bot hatayı yakalar ve Discord kanalınıza bildirir. Bu sayede hataları hızlı bir şekilde tespit edip çözebilirsiniz.

## Özellikler
- Kod bloglarında veya projelerde oluşan hataları otomatik olarak belirlenen bir Discord kanalına gönderir.
- Hata mesajlarını gerçek zamanlı olarak bildirir.
- Minimal kurulum ve kullanıcı dostu yapılandırma sunar.

## Gereksinimler
Projenin çalışması için aşağıdaki araçlara ve kütüphanelere ihtiyaç vardır:
1. Node.js (v14 veya üstü)
2. Aşağıdaki npm paketleri:
   - discord.js
   - chalk
   - wio.db
   - http
   - express

## Kurulum
Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:
1. Projeyi klonlayın:
   git clone (https://github.com/devshadow1/web2-discord-post.git)
   cd web2-discord-post
2. Bağımlılıkları yükleyin:
   npm install
3. Discord Bot Token'ı ve Kanal ID'sini yapılandırın:
   config.json dosyasını düzenleyin:
   {
     "token": "BOT_TOKENİNİZ", 
     "channelId": "KANAL_IDNİZ" // mesajın gönderileceği sunucu kanalı
   }
4. Botu çalıştırın:
   node index.js

## Kullanım
- Projeyi çalıştırdıktan sonra, gerekli gördüğünüz yere kodu yerleştirdiğinizde bot hata mesajlarını Discord kanalınıza göndermeye başlayacaktır.
- Gönderilen mesaj örneği:
  🔴 [HATA]: TypeError: Cannot read property 'x' of undefined
- Hata detayları ve oluştuğu zaman hakkında bilgiler mesajda yer alır.


## Destek
Herhangi bir sorunla karşılaşırsanız, aşağıdaki kanallardan benimle iletişime geçebilirsiniz:
Instagram: @c3n4p

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.


------------------------------------------------------------------------------------------


# Discord Error Reporting Bot

This project is designed to develop a bot that automatically sends error messages to a specific channel on your Discord server. When an error occurs in your code, this bot captures it and notifies your Discord channel. This helps you quickly identify and resolve issues.

## Features
- Automatically sends errors from code blocks or projects to a designated Discord channel.
- Real-time error reporting.
- Minimal setup with a user-friendly configuration.

## Requirements
The following tools and libraries are required for the project to work:
1. Node.js (v14 or higher)
2. The following npm packages:
   - discord.js
   - chalk
   - wio.db
   - http
   - express

## Installation
Follow the steps below to run the project:
1. Clone the project:
   git clone https://github.com/devshadow1/web2-discord-post.git
   cd web2-discord-post
2. Install dependencies:
   npm install
3. Configure your Discord Bot Token and Channel ID:
   Edit the config.json file:
   {
     "token": "YOUR_BOT_TOKEN",
     "channelId": "YOUR_CHANNEL_ID" // The server channel where the message will be sent
   }
4. Start the bot:
   node index.js

## Usage
- After running the project, place the necessary code snippet where required, and the bot will start sending error messages to your Discord channel.
- Example of a sent message:
  🔴 [ERROR]: TypeError: Cannot read property 'x' of undefined
- The message includes details about the error and when it occurred.

## Support
If you encounter any issues, feel free to contact me through the following channels:
Instagram: @c3n4p

## License
This project is licensed under the MIT License.





