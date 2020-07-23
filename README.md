# ArticlePublisher
Örnek Asp.Net Core MVC Wep Uygulaması

Kullanılan Teknolojiler:
	Visual Studio 2019 Community Edition
	Microsoft.EntityFrameworkCore
	MSSQLLocalDB
	Bootstrap 4
	Summernote --> Makale içeriği hazırlayabilmek için
	Disqus --> Makalelere yorum ekleyebilmek için

Uygulamayı local'de çalıştırmak için yapılması gerekenler:
	1. EntityFrameworkCore'un son sürümünün yüklü olması gerekiyor.
	2. Migrations klasörünü silip, Package Manager Konsolu açın:
		2.1. Add-Migrations InitialMigration --> Komutunu çalıştırın.
		2.2. Update-Database --> Komutunu çalıştırın.
		2.3. Visual Studio'da View sekmesinden Sql Server Object Explorer'dan BlogPostsDB Database'ini görün.
	3. Yeni makaleler ekleyin, silin, update edin, filtereleyin.
	4. Disqus'ı kullanabilmek için google'a disqus yazın ve ilk linke tıklayın.
		4.1. google ile üye olabilirsiniz.
		4.2. I want to install on my WebSite seçeneğini seçin
		4.3. WebSite Name : ArticlePublisher olarak girin
		4.4. Category : Entertainment olarak girin
		4.5. Ödeme sayfası çıkacak aşağıda subscribe now butonuna tıklayın
		4.6. I dont see my platform seçeneğini seçin
		4.7. Details.cshtml içerisine kodu ben kopyaladım. Sizin localhost portunuza göre update etmeniz gerekiyor. Başka bir şeyi değiştirmeyin. Sadece localhost portu.

Sorular:
	1. MVC tasarım desenini kullandım. Bu desen ile çok güzel maintain edilebilir projeler implemente edilebiliyor.
	   Zaten bence mevzu kod yazabilmekte değil, onu maintain edebilmekte. MVC bunun için güzel bir tasarım deseni.
	   Ayrıca çalışma mantığı da çok hoş.
	2. EntityFrameworkCore kütüphanesini ilk defa kullandım. EntityFramework kullanmıştım daha evvel.
	   Bootstrap 4 --> Dökümantasyona girip sevdiğim component'leri copy paste alıp kullanırım. Deneme yanılma ile çoğu zaman ilerliyorum.
	3. Daha geniş vaktim olsaydı. Makaleleri kategorize etmek isterdim. Yazar bilgisini de tutmak isterdim.
	4. Bu benim ilk asp.net core mvc projem. Kendimi bu alanda geliştirmek istiyorum. Vue.js de öğrenip, front-end back-end hepsinde ustalaşmak istiyorum. 
	   Bu repoda bir projem daha var. O .Net Framework ile yazıldı. MVC'yi o proje ile öğrendim onu da inceleyebilirsiniz.
	  
	