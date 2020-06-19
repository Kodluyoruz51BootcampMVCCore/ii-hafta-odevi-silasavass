## Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)

### GitHub Nedir?

Github.com adresinden ulaşabileceğiniz github yazılımcılar için bir sosyal medya ortamıdır. Aynı zamanda yazılımcılar için bir kod kütüphanesidir. Burada yazılımcılar kendi projelerini halka açık ya da özel olarak saklayabilirler. En büyük özelliği çok sayıda open-source projeyi barındırıyor olmasıdır. Burada bulunan open-source projelere katkı sağlayıp geliştirilmesini sağlayabilirsiniz ya da kendi ihtiyacınız için değiştirip kullanabilirsiniz. Ücretli ya da ücretsiz olarak faydalanabileceğiniz seçenekler mevcut olmakla birlikte eskiden ücretli olan private(özel) proje geliştirme özelliğine artık ücret ödemenize gerek yok.

### GitFlow Nedir?

Git versiyon kontrol sistemlerinden bir tanesidir. Git Flow ise bir Git eklentisidir. Git Akış ile projelerinizi geliştirirken daha Düzenli Bir **Şube** mantığıyla geliştirebilirsiniz.

### GitLab Nedir?

GitLab, github ve bitbucket gibi bir git servisidir. Open-soure projelerin barındırılmasını sağlar ancak genelde firmalar tarafından kullanılır. Çünkü firmaların gitlab’ı kendi sunucularına kurmalarına imkan tanır ve kurum içi olarak git hizmetlerinden faydalanılmasını sağlar. Kişisel kullanım için ücret ödemeye gerek yoktur.

### Bitbucket Nedir?

Bitbucket.org adresinden ulaşabilirsiniz. Bitbucket size halka açık ve özel projelerinizi saklamanız için imkan sağlıyor ancak Github’dan farkıysa burası bir sosyal medya ortamı yada open-source projeler için bir kütüphane şeklinde kullanılmamaktadır. Kişisel kullanım için ücret ödemeye gerek yoktur.

### GitKraken Nedir?

Axosoft’un ürünü olan git projelerin yönetilmesinin kolaylaştıran ve branch’ların görsel olarak görünmesini sağlayan masaüstü uygulamasıdır. [www.gitkraken.com](http://www.gitkraken.com/) adresinden yazılıma ulaşılabilir. Yazılımı kişisel projelerde ve open-source projelerde kullanmak ücretsizdir.

### SourceTree Nedir?

Git projelerinin yönetilmesini sağlayan masaüstü uygulamasıdır. GitKrakenden farkı ücretsizdir. [www.sourcetreeapp.com](http://www.sourcetreeapp.com/) adresinden indirip kullanmaya başlayabilirsiniz.

GitHub, Git Flow gibi alternatif bir iş akışı önerir. Git Flow ile bazı öğelere sahiptir. GitHub, ana hattı ve sürüm dallarını bir master olarak birleştirir ve düzeltmeleri tıpkı özelliklerinde gibi ele alır.

Bu basitleştirilmiş model, bazılarının hızlı bir şekilde ayarlanabilir ve bazen günde birkaç kez kolayca dağıtabileceği sürekli dağıtım modellerine daha uygundur.

## Merge pull request, Create a merge commit, Squash and merge,Rebase and merge altında ne fark var?

### Merge commits

Will keep all commits history of the feature branch and move them into the master branch Will add extra dummy commit.

### Rebase and merge

Will append all commits history of the feature branch in the front of the master branch Will NOT add extra dummy commit.

### Squash and merge

Will group all feature branch commits into one commit then append it in the front of the master branch Will add extra dummy commit. src: https://stackoverflow.com/a/58608571



## issue ve #pull request de id ler neden artıyor farklı sekmeler olmasına rağmen?

#### Aspnetboilerplate ve yan ürünler araştırması. [AspNet Boilerplate - Web Application Framework](https://aspnetboilerplate.com/)



### Razor Pages Nedir ?

https://www.minepla.net/2017/09/asp-net-core-razor-pages-nedir/

https://www.yusufsezer.com.tr/asp-net-core-razor-pages/



### C # Json Seri / Deserialize

Serileştirme: Bir nesnenin saklanacak / transfer edilecek forma dönüştürülme işlemidir. Serileşmenin tersi olarak Deserialization ifadeleri kullanılır ve bu da Stream'in (Akış) nesne modeline dönüştürülme işlemidir.

 İki  metot sunar;

#### 1)

XML "Birden Fazla İşaretleme Dili" ve SOAP "Basit Nesne Erişimi Protokolü" Serileştirme altında Binary (ikili) Serialization Binar Serialization: Tür bağımlılığı gerekli. İkili serileştirme işlemi, daha çok bir birinden bağımsız iki uygulama arasında, nesne modellerini taşımak için kullanılır. İkili serileştirme işlemi; bir nesnenin durumunun saklama ortamına uygun hale getirilip yazım süreci olarak tanımlanabilir. İşlem düzenlemesi, nesnenin “kamu” ve “özel” adresleri, sınıfın adı, sınıf barındıran Meclis 'nin adı saklama ortamına yazılmak üzere “bayt” lar akışına çevirilir. Nesne, Deserialize edildiğinde ise nesnenin tam bir şekilde burada ve çalışır. Binary serileştirme ile .İkili Serileştirme ile bir nesneyi serileştirmek, sürücüde gereğinden çok fazla yer çalışmasına neden olabilir, çünkü nesneleştirme ve nesne bulunan her yapı ve nesne için sürücüde. Bir dizi veya koleksiyon (IList, ObservableCollection vb…) varsa bunun içinde bulunan her nesne başlığında (foreach) bir ikili başlık (o class'ın yapısı) şişirebilir.

#### 2)

XML ve SABUN Serileştirme: Tür esnekliği ile ön plana çıkan bu yapı, çok sık tercih ediliyor. XML Serileştirme işleminde sadece ortak tipler ve metotlar serileştirilebilir. Bu yapıda kullanılırimnizi kullanacak olan koşullar kısıtlamadan saklanabiliriz. XML ve SABUN açık bir standart yapıda, aynı zaman da her türlü uygulama ile rahatlıkla okunabildiğinden veri paylaşımı oldukça hızlıdır.

## MVC vs MVP vs MVVM vs MVW vs MVU 

### MVC

MVC'nin en büyük avantajı sorumlulukları Model,View ve Controller’a temiz bir şekilde dağıtmasıdır. Controller’lar uygulamanın akışını kontrol ederler, nerede neyin nasıl yapılmasına gerektiğine karar verirler. View sadece kendisinin nasıl update olacağına ilişkin business’ı içerir, Model’i oluşturur ve kullanıcıya gösterir. View uygulamayla ilgili hiç bir logic içermediğinden dolayı farklı platformlar (Windows, Web) için aynı controller’ı kullanan birden fazla View olabilir (Daha öncede dediğim gibi her zaman okadar kolay olmayabiliyor). Ama dezavantajlarıda yok değil. View ile Model arasındaki observer ilişkisi ilk bakışta karışık gelebilir, View’in güncellenmesi için, Controller’ın Model’i güncellemesi gerek ki Model’de değiştiğini View’e bildirebilsin. Ayrıca .Net gibi modern programlama ortamları User Inputlar’ın eventlerini zaten kendileri handle ediyorlar, mesela buton’a tıklandığıda veya textbox’ın text’i değiştiğindeki eventler gibi.yapabiliyor vs.

### MVP (Model-View-Presenter)

MVP Pattern’i aslında MVC’den evrilmiş bir pattern, sadece bağımlılıklar değişiyor ve Controller’ın yerine Prenseter (ki bu durumda kendisine hala Controller denebiliyor) geliyor. MVVM Pattern’i hakkında bilgi vermeden önce Presentation Model hakkında bilgi vermek istiyorum. Çünkü MVVM dediğimiz şeye; WPF ve Silverlight için Prensentation Model diyebiliriz. src: https://denizirgin.com/mvc-mvp-ve-mvvm-patternleri-aa7d1011daff

### MVVM (Model-View-ViewModel)

MVVM Pattern'i hakkında bilgi vermeden önce Sunum Modeli hakkında bilgi vermek istiyorum. Çünkü MVVM dediğimiz şeye; WPF ve Silverlight için Prensentation Modeli diyebiliriz fakat buradaki fark, Sunum Modeli hem View ile ilgili stateleri tutuyor hemde Görünüm hakkında hiç birşey bilmiyor. Gerçekten PM View'ın İş Katmanı ve İş Katmanı ile ilgili kordinasyonu sağlar ve View'a karar vermeyle ilgili çok az şey bırakıyor. Görünüm yine stateleri tutuyor gereklidir. Fakat MVP'nin aksine Sunum Modeli Görüntüle MVP'nin benzC, benziyor, fakat MVC'nin 1-n bir ilişki var, bir PM birden fazla Görünüm'de görüntüleniyor aksine Görünüm üzerinde ki manipulasyonlar PM üzerinden gerçekleşiyor. İnternette kullanım şekillerinden biride INotifyPropertyChanged interface'inden türeyip,. Net'in bağlayıcı alt yapısını kullanması. Zaten özünde yapılır iş DataBinding. Kendi propertylerini View'in property'leriyle senkronize ediyor, aynı zamanda devletlerinede karar veriyor, şu anda TextBox dolduğunda şu Buton etkin olsun gibi. Tabi herzaman, PM'de tutmak anlamsız olucak bir kontrol'un devlet'ini etkinleştirdi.

PM'in en büyük avantajı, herhangi bir View'e ihtiyaç duymadan bir View'in davranışlarını ve Data'sını barındarabilmesi, TDD'ye (Test Odaklı Geliştirme) çok uygun.

### MVU

MVU kendisiniN kökenleri fonksiyonel programlama dili Elm topluluğuna sahiptir.

Karaağaç Mimarisi, webapps ve oyunlar gibi etkileşimli programlar tasarlamak için bir modeldir. Bu mimari Elm'de doğal olarak ortaya çıkmaktadır. İlk Elm programları, icat eden birinden ziyade, kodlarında aynı temel kalıpları keşfetmeye devam ettiler. Önceden planlama yapmadan iyi tasarlanmış bir kodla biten insanlar görmek biraz ürkütücü!

Ama yeterli tarih, bu yazı bunun yerine mevcut favori programlama dilimden birine dayanan hızlı bir girişe odaklanıyor F #. 