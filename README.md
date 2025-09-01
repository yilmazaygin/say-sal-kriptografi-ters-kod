# 📘 Sayısal Kriptografi ve Ters Kod Mühendisliği Notları

Bu depo, **Özgür Yazılım 2024 Yaz Kampı** süresince ve sonrasında oluşturduğum notları içermektedir.  
İçerik iki ana bölümden oluşmaktadır: **Sayısal Kriptografi** ve **Ters Kod Mühendisliğine Giriş**.

---

## 📑 İçindekiler

- [Bu Notlar Hakkında](#bu-notlar-hakkında)  
- [Özgür Yazılım Hakkında](#özgür-yazılım-hakkında)  
- [Özgür Yazılım Nedir?](#özgür-yazılım-nedir)  
- [Özgür Yazılım – Açık Kaynak Farkı](#özgür-yazılım--açık-kaynak-farkı)  

---

## I. KISIM: SAYISAL KRİPTOGRAFİ

1. [Kriptografi Nedir?](#kriptografi-nedir)  
2. [Sayı Kümeleri](#sayı-kümeleri)  
3. [Modüler Matematik](#modüler-matematik)  
4. [Cebirsel Yapılar](#cebirsel-yapılar)  
   - İkili İşlem  
   - Grup  
   - Ring  
   - Field  
5. [Golomb’un Rastgelelik Postulatları](#golombun-rastgelelik-postulatları)  
6. [LFSR](#lfsr)  
7. **Simetrik Anahtarlı Sistemler**  
   - Feistel Network  
   - DES  
   - DES için S-Box Yapısı  
   - AES  
   - ECB  
   - CBC  
   - OFB  
   - CTR  
8. **Asimetrik Anahtarlı Sistemler**  
   - Bölen Sembolü  
   - Eratosthenes Kalburu ile Asallık Kontrolü  
   - Aritmetiğin Temel Teoremi  
   - Öklid Algoritması  
   - Fermat’ın Küçük Teoremi  
   - Euler φ (Totient) Fonksiyonu  
   - Euler Teoremi  
   - RSA  
   - Ayrık Logaritma Problemi  
   - Diffie-Hellman Key Exchange  
   - DL, CDH, DDH Problemleri  
   - ElGamal Algoritması  
9. **Dijital İmzalar**  
   - RSA İmza  
   - ElGamal İmza  
   - DSA  
   - EtS / StE  
10. [Needham–Schroeder Key Exchange](#needham-schroeder-key-exchange)  
11. [Man-in-the-Middle Attack](#man-in-the-middle-attack)  
12. **Özet Fonksiyonları**  
   - Tek Yollu Özet Fonksiyonları  
   - Kriptografik Özellikler  
13. [ECDSA](#ecdsa)  
14. [Homomorfik Şifreleme](#homomorfik-şifreleme)  
15. [Zero-Knowledge Proofs](#zero-knowledge-proofs)  
16. [Differential Privacy](#differential-privacy)  
17. [Post-Kuantum Kriptografi](#post-kuantum-kriptografi)  

---

## II. KISIM: TERS KOD MÜHENDİSLİĞİNE GİRİŞ

1. [Ters Kod Mühendisliği Nedir?](#ters-kod-mühendisliği-nedir)  
2. [Sanal Makine ve Ubuntu Kurulumu](#sanal-makine-ve-ubuntu-kurulumu)  
   - VMware’a Ubuntu Kurulumu  
3. [Linux Terminali ve Temel Komutlar](#linux-terminali-ve-temel-komutlar)  
4. [Compiling / Linking Süreçleri](#compiling--linking-süreçleri)  
   - GCC Kullanımı  
   - NASM Kullanımı  
   - LD Kullanımı  
   - GCC ile C Dosyası Derleme Örneği  
   - NASM + LD ile Assembly Derleme  
5. [GDB (GNU Debugger)](#gdb-gnu-debugger)  
   - Temel GDB Komutları  
6. **Assembly’e Giriş**  
   - Assembly Kodunun Yapısı  
   - Registerlar  
   - Sistem Çağrıları  
   - Stack Yapısı  
   - Temel Talimatlar  
   - Örnek Kodlar  
   - Derleme ve GDB ile İnceleme  
7. [Crackme Çözümleri](#crackme-çözümleri)  
   - Örnek Çözümler  
8. [Analiz Teknikleri](#analiz-teknikleri)  
   - Statik ve Dinamik Analiz  
   - Malware Analizi  
   - Gelişmiş Debugging Teknikleri  
   - Anti-Reversing Teknikleri ve Çözümleri
