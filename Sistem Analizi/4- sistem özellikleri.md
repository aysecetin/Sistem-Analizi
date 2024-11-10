# SİSTEM ÖZELLİKLERİ NELERDİR?🤓

## Sistem Özellikleri 
- Her sistem bir amaca hizmet eder. Bir fonksiyon gerçekleştirir.
- Her sistemin bir sınırı vardır.
- Sistemler bileşenlerden oluşur.
- Bileşenler arasında ilişkiler vardır.
- Her sistem çevresi ile etkileşim halindedir.
- Çevresi ile etkileşim sağlamak üzere giriş, çıkış olanakları ve gerekirse kullanıcı arabirimi bulunur.
- Her sistemin kısıtları vardır.
- 
 ```mermaid
graph TD
    Cevre["Çevre (Environment)"] -->|Geri Besleme| Surec["Süreç (Process)"]
    Giris["Girdi (Input)"] --> Surec
    Surec -->|Çıktı (Output)| Sinir["Sınır (Boundary)"]
    Surec -->|Geri Besleme| Cevre
    
    subgraph Sistem
        Surec
    end
