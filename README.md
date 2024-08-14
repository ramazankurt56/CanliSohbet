# Canlı Sohbet Projesi

Bu proje, ASP.NET Core ve Angular kullanarak geliştirilen bir canlı sohbet uygulamasıdır. Proje, SignalR teknolojisiyle gerçek zamanlı iletişim sağlamak amacıyla oluşturulmuştur.

## Proje Yapısı

### CanliSohbetServer
- **ASP.NET Core WebAPI** kullanılarak geliştirilen sunucu tarafı uygulamasıdır.
- **SignalR** kullanarak istemciler arasında gerçek zamanlı mesajlaşmayı sağlar.
- **Controllers** klasörü, API uç noktalarını barındırır.
- **Hubs** klasörü, SignalR hub'larını içerir.

### CanliSohbetClient
- **Angular** ile geliştirilmiş istemci tarafı uygulamasıdır.
- Gerçek zamanlı mesajlaşma için **@microsoft/signalr** kütüphanesi kullanılır.
- Kullanıcı arayüzü Angular bileşenleri ile oluşturulmuştur.
