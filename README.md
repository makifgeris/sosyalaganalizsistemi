# Sosyal Ağ Analiz Sistemi

Bu proje, bir sosyal ağ grafiği üzerinde çeşitli analizler gerçekleştiren bir C programıdır. Kullanıcılar Red-Black Tree (kırmızı-siyah ağaç) yapısında tutulur ve kullanıcılar arasında arkadaşlık ilişkileri bir grafik yapısı olarak modellenir.

##  Özellikler

- 🔴 Red-Black Tree ile kullanıcıların verimli bir şekilde saklanması
- 👥 Arkadaşlık ilişkileri ile sosyal ağ grafiği oluşturma
- 🔍 DFS (Derinlik Öncelikli Arama) ile kullanıcıların etki alanlarını keşfetme
- 🤝 Ortak arkadaş analizi
- 🌐 Topluluk tespiti (bağlı bileşen analizi)
- 💾 `veriseti.txt` dosyasına kullanıcı ve arkadaşlık ilişkilerinin yazımı

##  Program Akışı

1. **Kullanıcı Ekleme:** Kullanıcılar Red-Black Tree yapısına eklenir.
2. **Arkadaşlık Tanımı:** Her kullanıcı için arkadaşları listelenir.
3. **Dosya Yazımı:** Kullanıcı ve arkadaşlık ilişkileri `veriseti.txt` dosyasına yazılır.
4. **DFS ile Etki Analizi:** Kullanıcının belirli derinliğe kadar olan bağlantıları bulunur.
5. **Ortak Arkadaş Analizi:** İki kullanıcı arasındaki ortak arkadaşlar listelenir.
6. **Topluluk (Connected Component) Tespiti:** Ağdaki tüm bağlantılı topluluklar listelenir.

## 📁 Örnek Çıktı (veriseti.txt)
![image](https://github.com/user-attachments/assets/174881ae-591a-4a99-8163-4af8694244dd)


