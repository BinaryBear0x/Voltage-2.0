# Voltage-2.0

Voltage-2.0, Windows tarafından üretilen pil raporunu okuyup pil sağlığı ve temel batarya bilgilerini kullanıcıya gösteren masaüstü uygulamasıdır.

## Ne Yapar

- `powercfg /batteryreport` çıktısını üretir
- HTML raporu parse eder
- tasarım kapasitesi ve tam dolum kapasitesini karşılaştırır
- pil sağlığını yüzdesel olarak gösterir

## Teknolojiler

- C#
- Windows Forms
- HtmlAgilityPack

## Notlar

- Uygulama yönetici yetkisiyle çalıştırılmalıdır
- Özellikle bataryalı Windows cihazlar için anlamlıdır

