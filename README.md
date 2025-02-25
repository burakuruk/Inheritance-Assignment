Aşağıda README.md dosyanı daha düzenli ve profesyonel bir hale getirdim. Bunu GitHub’daki dosyan ile değiştirebilirsin.

Inheritance-Assignment

Bu repo, Inheritance (Kalıtım) ve Nesne Yönelimli Programlama (OOP) kavramlarını içeren bir ödev kapsamında oluşturulmuştur.

📌 Ödev 1: Inheritance Kullanarak Araç Sınıfları Oluşturma

Bu bölümde, Car (Araba) adlı bir temel sınıf oluşturulmuş ve bu sınıftan türeyen farklı araç sınıfları miras alınarak geliştirilmiştir. Araçların özellikleri belirlenerek ekrana yazdırılmıştır.

🚗 Oluşturulan Araç Sınıfları:

	•	BMW
	•	Porsche
	•	Mercedes
	•	Togg
	•	Audi
	•	Toyota

Ek olarak, manuel ve otomatik vites türlerini belirlemek için iki ayrı sınıf kullanılmıştır.

📌 Ödev 2: OOP Kavramları Açıklamaları

Bu bölümde, Nesne Yönelimli Programlama’nın temel kavramları açıklanmıştır:

	•	Abstract Class (Soyut Sınıf)
	•	Abstraction (Soyutlama)
	•	Polymorphism (Çok Biçimlilik)

Bu dosya OOP kavramlarını anlamak için temel bilgiler içermektedir.

📁 Dosya Yapısı

Ödev1/
│── Program.cs        → Ana kod dosyası
│── Ödev1.csproj      → Proje yapılandırma dosyası
│── bin/              → Derleme sonrası oluşturulan dosyalar
│── obj/              → Geçici proje dosyaları
│── Classes/
│   ├── Car.cs        → Temel sınıf (Base Class)
│   ├── Bmw.cs        → BMW sınıfı
│   ├── Porsche.cs    → Porsche sınıfı
│   ├── Mercedes.cs   → Mercedes sınıfı
│   ├── Togg.cs       → Togg sınıfı
│   ├── Audi.cs       → Audi sınıfı
│   ├── Toyota.cs     → Toyota sınıfı
│   ├── OtomatikV.cs  → Otomatik vites sınıfı
│   ├── ManuelV.cs    → Manuel vites sınıfı
│
│── ÖDEV2-OOP_Concepts.txt → OOP kavramlarının açıklamaları
│── README.md         → Ödev hakkında genel bilgiler

💻 Nasıl Çalıştırılır?

	1.	Visual Studio 2022 veya .NET destekleyen bir IDE açın.
	2.	Proje klasörünü açın ve Program.cs dosyasını çalıştırın.
	3.	Konsolda araç bilgileri ve vites türleri görüntülenecektir.

📜 Lisans

Bu proje eğitim amaçlıdır ve herhangi bir lisans kısıtlaması olmadan kullanılabilir.

✅ README.md’yi düzenledikten sonra GitHub’a yüklemeyi unutma!
Git Bash’te şu komutları kullanarak güncelleme yapabilirsin:

	1.	git add README.md
	2.	git commit -m "README.md güncellendi"
	3.	git push origin main
