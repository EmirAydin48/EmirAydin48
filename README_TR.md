**Mevcut Diller:** [English](README.md) | [Türkçe](README_TR.md)

# Merhaba 👋, Ben Emir Aydin

Marmara Üniversitesi Elektrik-Elektronik Mühendisliği 2. sınıf öğrencisiyim. Gömülü sistemler alanına odaklanıyorum.  
🔍 İstanbul–Bursa bölgesinde gömülü yazılım staj olanaklarına açığım.

---

## Seçili Projeler

### [Dual-MCU Endüstriyel IoT Gateway & FOTA (Staj Projesi)](https://github.com/EmirAydin48/dual-mcu-gateway-system) (Vaka Analizi)
Gerçek zamanlı kontrol döngülerini bozmadan legacy sistemleri modernleştirmek için geliştirilmiş, hata toleranslı telemetri ağ geçidi.

- **Amaç:** Gerçek zamanlı davranışı koruyarak legacy cihazlara güvenli bulut bağlantısı kazandırmak.
- **Mimari:** ESP32’nin ağ/güvenlik (gateway + firewall rolü), STM32’nin ise gerçek zamanlı kontrol ve telemetri mantığını yönettiği çift-MCU sistem mimarisi tasarladım.
- **Öne çıkan teknik çalışmalar:**
  - Ana kontrol döngüsünü duraksatmadan sensör verisi akışı ve uzaktan komut işleme için DMA tabanlı, non-blocking UART telemetri hattı geliştirdim.
  - Kısıtlı bellek koşullarında güvenilir veri aktarımı için özel Stop-and-Wait ARQ protokolü uyguladım.
  - <4 KB RAM kullanımıyla güncelleme yükleyebilen streaming AES-CTR çözme hattı geliştirdim.
- **Teknik altyapı:** C, FreeRTOS, TinyCrypt (AES-CMAC/CTR), STM32 HAL  

---

### [FPGA Tabanlı Donanım Kripto Motoru (Araştırma)](https://github.com/EmirAydin48/VHDL-Hardware-Cryptographic-Engine)
Doğrusal Olmayan Geri Beslemeli Kaydırma Yazmaçları (NLFSR) ve Dengesiz Feistel Ağları gibi teorik şifreleme mimarilerinin nasıl çalıştığını gösteren kripto motoru.

- **Proje:** Artix-7 FPGA üzerinde sentezlenen özel kriptografik çekirdek.
- **Öne çıkan teknik çalışmalar:** Feistel ağı ve NLFSR tabanlı bileşenleri tasarladım.
- **Teknik altyapı:** VHDL, Vivado, Logisim, Sayısal Mantık  

---

### [SunflowerBot: FPGA Güneş Takip Sistemi (Robotik)](https://github.com/EmirAydin48/VHDL-Solar-Tracking-System)
Paralel donanım mantığıyla çalışan otonom kontrol sistemi.

- **Proje:** Doğadaki heliotropik davranışı taklit ederek ışık kaynağına yönelen takip sistemi.
- **Öne çıkan teknik çalışmalar:**
  - Kontrol döngüsünü MCU olmadan tamamen donanımda çalıştırarak paralellik ve kesin zamanlama sağladım.
  - Sinyal işleme için özel IIR sayısal filtre ve mikro-saniye hassasiyetli zamanlamaları yöneten HD44780 LCD sürücüsü geliştirdim.
- **Teknik altyapı:** VHDL, XADC, PWM üretimi, Sayısal Filtreleme (IIR)  

---

## Teknik Yetkinlikler

- **Gömülü Yazılım:** C, FreeRTOS, STM32 HAL, ESP-IDF, (temel) Java  
- **Dijital Tasarım:** VHDL, Vivado, FPGA (Artix-7 / Basys 3), Logisim  
- **Arayüzler & Çevre Birimleri:** UART, SPI, I2C, DMA, ADC, Timer, PWM
- **Debug / Bring-up:** ST-LINK (SWD), UART loglama, osiloskop, kart üstü debug

---

## Güncel
TEKNOFEST Çip Tasarım Yarışması (Mikrodenetleyici Tasarım Kategorisi) kapsamında Team Marchip ile yarışmaya katılmak üzere hazırlık yapıyorum.

---

## 📫 **İletişim:** [LinkedIn](https://linkedin.com/in/emir-aydin-7b33f48) | [Email](mailto:emiraydin2448@gmail.com)
