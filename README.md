 		 
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147292359-46690a5b-7f0f-4095-a7d0-10bda82b7af7.png">
</p>

<p align="center"> 
SELÇUK ÜNİVERSİTESİ</br>
TEKNOLOJİ FAKÜLTESİ</br>
BİLGİSAYAR MÜHENDİSLİĞİ BÖLÜMÜ</br>
BİTİRME PROJESİ</br>
</p>
<p align="center"> 
BLOCKCHAIN TEKNOLOJİSİ & </br>
ETHEREUM AĞINDA SOLİDİTY PROGRAMLAMA</br></br>
Mustafa ERDOĞAN
</p>

İÇİNDEKİLER

1. GİRİŞ</br>
2. TEMEL KAVRAMLAR</br>
2.1 Veri Nedir?</br>
2.2 Veri Tabanları</br>
2.3 Merkezi Olmayan Sistemler</br>
2.4 Hash Nedir?</br>
2.5 Kriptoloji Nedir?</br>
2.6 Peer To Peer ( Eşten Eşe - P2P ) Kavramı</br>
2.7 Blockchain Teknolojisinin Felsefesi</br>
3. BLOCKCHAIN’E GİRİŞ</br>
3.1 Blockchain’in Tarihçesi</br>
3.2 Blockchain Nedir?</br>
3.2.1 İşlemler (Transactions)</br>
3.2.1.1 Dijital İmza</br>
3.2.2 Dağıtılmış Defter Sistemi</br>
3.2.3 Merkezi Olmayan Yapısı</br>
3.2.4 Düğümler (Nodes)</br>
3.2.5 Ağdaki Fikir Birliği (Consensus)</br>
3.2.5.1 İş Kanıtı (Proof of Work - PoW) </br>
3.2.5.2 Hisse Kanıtı (Proof of Stake - PoS) </br>
3.2.6 Değişmezlik (İmmulability) </br>
3.3 Blockchain Ağlarında Gizlilik</br>
4. BLOCKCHAIN ÇEŞİTLERİ</br>
4.1 Genel Blockchain Ağları</br>
4.2 Özel Blockchain Ağları</br>
4.3 İzne Tabi Blockchain Ağları </br>
4.4 Konsorsiyum Blockchain Ağları </br>
5. Blokchain Mimarisi ve Çalışma Prensipleri</br>
5.1 Blockchain Nasıl Çalışır?</br>
5.2 Block Yapısı</br>
5.3 Blockchain Cüzdanları</br>
5.4 Blockchain Madenciliği ( Mining)</br>
5.5 Çatallaşma (Fork)</br>
5.6 En Uzun Blockchain Kaydı</br>
6. BLOCKCHAIN AĞLARINDA ŞİFRELEME</br>
6.1 Güvenli Şifreleme ( Secure Hash)</br>
6.2 Merkle Ağaç Yapısı ( Merkle Tree)</br>
6.3 Simetrik Şifreleme ( Symmetric Encryption)</br>
6.4 Asimetrik Şifreleme (Asymmetric Encryption)</br>
7. BLOCKCHAIN UYGULAMALARINDA RİSKLER</br>
7.1 Özel Anahtarların Saklanması</br>
7.2 Enerji Tüketimi</br>
7.3 Sınırlı Teşvik</br>
7.4 Yazılım Hataları, Açıklar ve Siber Saldırılar</br>
7.5 Şifreleme ve Kuantum Bilgisayarlar</br>
7.6 Çatallaşma (Fork) Problemi</br>
8. BLOCKCHAIN PLATFORMLARI</br>
8.1 Bitcoin Ağı</br>
8.2 Ethereum Ağı</br>
8.3 HyperLedger Ağı</br>
8.4 Ripple Ağı</br>
9. ETHEREUM GİRİŞ</br>
9.1 Ethereum Tarihçesi</br>
9.2 Ethereum Nedir?</br>
9.3 Ethereum 2.0 Nedir?</br>
9.3.1 ETH 2.0 Staking Nedir?</br>
9.4 Ethereum Sanal Makinesi (EVM) </br>
9.4.1 EVM Nasıl İşler</br>
9.4.2 Merkezi Olmayan Uygulamalar (DApps)</br>
9.4.3 Akıllı Sözleşmeler </br>
9.4.4 ERC20 – ERC721 Protokolleri</br>
9.4.5 Ethereum Hesap Türleri</br>
9.4.6 MetaMask Cüzdanı Nedir?</br>
9.4.7 Solidity Nedir?</br>
9.4.8 Ethereum İşlem Ücreti (GAS Fee)</br>
9.5 Ethereum ile Bitcoin Arasındaki Farklar</br>
9.6 Ethereum, Bitcoin’e Rakip Olabilir Mi?</br>
10. SOLIDITY GİRİŞ</br>


## 1. GİRİŞ 
<p> Blockchain teknolojisi paranın dijitalleşme süreciyle hayatımıza daha yoğun bir şekilde girmeye başlamıştır. Global düzeyde insanların kripto paralar hususunda farkındalık kazanmasında Bitcoin’in oldukça ayrıcalıklı bir yeri bulunmaktadır ki onun arkasında da Blockchain teknolojisi yer almaktadır.</p>
<p> Önümüzdeki dönemde başta finans dünyası olmak üzere birçok alanda büyük yenilikler ve dönüşümler yaratması beklenen blok zinciri kavramı, 2008 yılında yayınlanan Bitcoin makalesiyle ortaya çıkmıştır. Makalenin yazarı olarak görünen Satoshi Nakamoto, 2009 yılında ilk Bitcoin yazılımını geliştirerek Bitcoin sisteminin kurulmasını sağlamıştır. Nakamoto, 2010 yılı ortalarına kadar Bitcoin ekosisteminin gelişmesini desteklemiş ve ardından projeden desteğini çekerek ortadan kaybolmuştur.</p>
<p> Dünya çok yakın bir tarihte büyük bankaların battığı, ülkelerin finansal anlamda kötü duruma düştüğü bir kriz yaşamıştır. Küresel sistemde yaşanan son finans ve bankacılık krizlerinin toplumun güven duygusunu zedelemesi ile birlikte paranın temeli hakkında sorular gündeme gelmiştir. Bankacılık sektörüne olan güven duygusu sistemin işlemesi için gerekli olan temel yapı taşıdır. Günümüzde öznel bir değeri bulunmayan kağıt parayı kıymetli ve güvenli kılan unsur arkasındaki devlet otoritesi iken elektronik parayı güvenli kılan faktör ise finansal regülasyondur. Son yıllarda popülerliği artan kripto paraları da benzer şekilde Blockchain teknolojisi güvenli kılmaktadır.</p>
<p> Anahtar kelimeler: Blockchain, Kriptoloji, Bitcoin, Ethereum, Akıllı kontrat (Smart Contract), Madenci, Eşten eşe(P2P), Solidity, Ethereum Sanal Makine, Hash, ERC-20, ERC-721, Merkezi olmayan uygulamalar (DApps)</p>

## 2. TEMEL KAVRAMLAR
### 2.1 Veri Nedir? 
<p> İngilizce dilinde karşımıza çıkan ve artık günlük yaşamda da dilimizde normalleşmeye başlayan “data” kelimesinin Türkçe karşılığıdır. İşlenmemiş, hem bilgi parçacığına verilen isimdir.</p>
<p> Veriler; ölçüm, sayım, deney, gözlem ya da araştırma yolu ile elde edilmektedir. Ölçüm ya da sayım yolu ile toplanan ve sayısal bir değer bildiren veriler nicel veriler, sayısal bir değer bildirmeyen veriler de nitel olarak sınıflandırılmaktadır.</p>
<p> Bir verinin tek başına bir anlamı ve işlevi bulunmaz. Veriler toplandıktan sonra gruplanarak, sıralanarak ve özetlenerek, elle ya da bilgisayarla işlenip enformasyona dönüştürüldüklerinde anlam kazanırlar. Böylece, ait oldukları unsuru açıklama gücüne kavuşur ve problem çözme ya da karar verme gibi bir amaca hizmet edebilecek duruma gelirler.</p>

### 2.2 Veri Tabanları  
<p> Veri tabanı, bilgisayar sisteminde depolanan yapılandırılmış bir kayıt ve veri koleksiyonudur. Bir veri tabanının gerçekten işlevsel olması için, yalnızca büyük miktarda kaydı iyi depolamakla kalmaz, aynı zamanda kolayca erişilebilir kılar. Buna ek olarak, yeni bilgi ve değişikliklerin girilmesi de oldukça kolay olmalıdır.</p>
<p> Birçok veri tabanı çeşitleri bulunmaktadır. Bunlardan bazıları ilişkisel, Nesne Odaklı, Dağıtılmış, Bulut veri tabanları gibi daha sayabiliriz. Fakat son dönemde Bulut veri tabanları çok popüler olmuş ve çoğu küçük veya büyük firmalar tarafında da kullanımı revaçtadır.</p>
<p> Bulut Depolama, dosyalarınızı internet üzerinde size verilen bir alanda saklamanıza verilen isimdir. Dosyalarınız internet üzerinde olduğu için internet bağlantısı olan her yerden onlara ulaşabiliyorsunuz.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147280288-3de829a7-f336-471b-b085-6fa35447f49b.png"></br> Şekil 1 - Bulut Depolama
</p>
<p >Artık, donanımın uygulamalara ve uygulamaların servislere dönüştüğü bir dönemden geçiyoruz. Bu sebeple bulut çözümleri eşsiz bir maliyet avantajı ile ihtiyaç duyduğumuz altyapıları bize sağlıyor. Ancak bu, teknolojik gelişmenin son noktası değil. Daha ötesi de var…</p>

### 2.3 Merkezi Olmayan Sistemler (Decentralized Systems)
<p> Bir merkezi olmayan sistem,	tek bir varlığın tek yetkili olmadığı birbirine bağlı bir bilgi sistemidir. Bilgi işlem ve bilgi teknolojisi bağlamında, merkezi olmayan sistemler genellikle ağa bağlı bilgisayarlar şeklindedir. Örneğin, internet merkezi olmayan bir sistemdir, ancak zamanla giderek merkezileşmiştir.</p>
<p>Merkezi olmayan bir sistem, dağıtılmış bir sistemden farklıdır. Merkezi olmayan bir sistem genellikle, her biri toplam son kullanıcıların bir alt kümesine hizmet eden çok sayıda yetkili düğüme (node) sahiptir. Bununla birlikte, dağıtılmış bir sistemde, son kullanıcı yoktur, çünkü ağdaki her düğüm tek bir birim olarak davranmak için birbirleriyle iletişim kurar.</p>
 <p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282089-ddf9e5b5-5dde-42ba-a8b0-b1941f4e8b2a.png"></br> Şekil 2 - Merkezi, Dağıtık ve Merkezi Olmayan Sistemler
</p>


### 2.4 Hash Nedir?
<p> Girilen veriyi, sabit uzunlukta çıktıya dönüştüren matematiksel işleme hash denir. Bu işlemin amaçlarından biri, verinin gizlenmesidir. Örneğin, web sitelerine üye olurken yazılan şifreler hash’e dönüştürülerek veri tabanına yazılır. Bu sayede veri tabanını inceleyen kötü niyetli kişi kullanıcıların şifrelerini bilemez.</p>
<p>Bir diğer kullanım amacı ise verinin güvenli oluşturulmasıdır. Girdi verisi ne kadar uzun olursa olsun çıktı daima aynı uzunlukta olacağından, hash kodu özet amaçlı saklanabilir. Farklı hash fonksiyonları farklı büyüklüklerde çıktı yaratır fakat her bir hashing algoritması için olası çıktı büyüklüğü her zaman sabittir. Örneğin, SHA-256 algoritması yalnızca 256 bit çıktılar üretebilirken SHA-1 her zaman 160 bitlik bir özet yaratır.</p>
<p> Örnek olarak, Bitcoin Blockchain ağında kullanılan “SHA-256” hashing algoritmasından “Binance” ve “binance” kelimelerini geçirelim.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282212-176dd5fd-a541-423d-b0e7-9f98caa5a558.png"></br> Şekil 3 - SHA-256 Hashing Algoritması
</p>
<p> Çok küçük bir farkın (ilk harfin büyük ya da küçük olması) nasıl tamamen farklı bir hash değeri yarattığına dikkat edin. Fakat biz SHA-256 kullandığımız için, çıktılar her zaman sabit 256 bit (ya da 64 karakter) boyutunda olur. Ayrıca, bu iki kelimeyi algoritmadan kaç kere geçirirsek geçirelim, iki çıktı her zaman aynı kalacaktır.</p>

### 2.5 Kriptoloji Nedir?
<p> Binlerce yıldır, üretilen veri kayıt altına alınırken ortaya çıkan en önemli ihtiyaçlardan bir tanesi, veriyi istenmeyen gözlerden saklamak olmuştur. Kriptoloji her ne kadar kulağımıza modern bir kelime gibi gelse de aslında eski bir Yunanca kelime olan “Kryptos” kelimesinden türetilmiştir. Kryptos gizlilik anlamına gelirken, kriptoloji gizlilik bilimi anlamına gelmektedir.</p>
<p> Şifreleme, herhangi bir veri kümesini bir kural yapısı kullanarak rastgele görünen bir veri kümesine dönüştürür. Bu rastgele gibi görünen veri kümesi, ancak şifreleme yapılırken kullanılan anahtara sahip olanlar tarafından orijinal ve anlamlı haline geri dönüştürülebilir. Bu anahtara sahip olmayanlar için ise bir anlam ifade etmez. Böylece şifrelenmiş veri nerede ne şekilde depolanırsa depolansın sadece anahtar sahibi tarafından anlamlı kalmaya devam eder.</p>

### 2.6 Peer To Peer (Eşten Eşe- P2P) Kavramı
<p> Herhangi bir otoriteye ya da merkeze ihtiyaç duymadan çalışan Bitcoin’in yapısını anlayabilmek için, internet teknolojilerinin kilometre taşlarından biri olan P2P ağ protokolünü bilmek önemlidir.</p>
<p> Merkezi bir otoritenin katılımı olmadan taraflar arasında bilgi, veri veya varlık alışverişi veya paylaşımı tarif etmek için kullanılır. Eşler arası veya P2P, bireyler ve gruplar arasındaki etkileşimlere dağıtılmış bir yaklaşım benimser. Bu yaklaşım, bilgisayarlarda ve ağlarda eşler arası dosya paylaşımı ve kripto para birimi ticaretinde kullanılmaktadır.</p>
<p> Bu protokolde, ağa bağlı bilgisayarlara veri paylaşabildiği gibi, onların cihazlarındaki verilere de erişmek mümkündür. Yani; P2P ağlarında merkezi sunucu yapısına ihtiyaç yoktur. Eşler hem istemci hem de sunucu görevini üstelenmektedir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282457-02b86452-f1c3-4b46-a68c-21fa63d8c7cd.png"></br> Şekil 4 - Peer To Peer (P2P)
</p>


### 2.7 Blockchain Teknolojisinin Felsefesi
<p> Tarih boyunca veri kayıtlarının hizmet ettiği önemli ihtiyaçlardan birisi büyümekte olan topluluklar içinde düzenin sağlanması olmuştur. Büyümekte olan toplumlarda, birbirini tanımayan kişi ve yapılar arasındaki ilişkilerin kurallara bağlı hale getirilmesi ve bu kuralların kayıtlara geçirilmesi her zaman büyük önem taşımıştır.</p>
<p> 2008-2009 yılında Satoshi Nakamoto tarafından yayınlanan Bitcoin’in Whitepaper’ın da her ne kadar bir dizi matematiksel ve teknolojik uygulamayı bizlere sunsa da aslında makalede verilen temel mesaj, mealen şöyledir: “Ey insanlar! Birbirinizi tanıyın veya tanımayın, artık merkezi yapılara ihtiyaç duymadan güvenli bir veri kayıt sistemi kurmak mümkün. Bu sistem, matematik ve teknolojinin imkanlarını kullandığı için manipüle edilemez ve bozulamaz”.</p>
<p> Blockchain felsefesinin verdiği mesajı artık biliyoruz. Merkezi olmayan ama güvenli veri kayıt sistemlerini nasıl hayata geçirildiğini anlamak için temel kavramlar hakkında artık bir bilgiye sahibiz. Şimdi Blockchain’in çalışma süreçlerine geçiş yapabiliriz.</p>

## 3. BLOCKCHAIN’E GİRİŞ
## 3.1 Blockchain’in Tarihçesi 
•	İlk günlerde;
<p> Blockchain teknolojisinin ardındaki fikir, bilim adamları Stuart Haber ve W.Scott Stornetta’nın hesaplama açısından kullanışlı bir çözüm ile dijital belgelerin zaman damgası ile kurcalanamaz veya geriye dönük olarak değiştirilememesi şeklinde 1991 yılında tanımlanmıştır.</p>
<p> Sistem, zaman damgalı belgelerin saklanması için kriptolanmış güvenli bir Blockchain’i kullanmış ve 1992 yılında Merkle ağaçları tasarıma dahil edilmesiyle birlikte birkaç belgenin bir blok halinde toplanması sağlanmış. Fakat bu teknoloji kullanılmamış ve patenti Bitcoin’in başlangıcından dört yıl önce, 2004 yılında sona ermiştir.</p>

•	Modern günümüzde;

<p> Bu fikir 2008 yılında tekrardan Satoshi Nakamoto isminde kimsenin tanımadığı, kimliği bilinmediği bir kişi tarafından ortaya atıldı.</p>
<p> 2008’in ortasında bir email grubuna (CyperPunk) sekiz sayfalık bir “White Paper” gönderiyor ve bu yazısında mevcut bankacılık sisteminde bazı hataların olduğunu söylüyor. Bu problemleri ben şu şekilde çözerim diyerek bazı teşhisler koyarak çözüm önerilerini belirtiyor.</p>
<p> Bunun sonrasından Satoshi, 2009’un başında ilk Bitcoin’i canlıya alıyor. Bitcoin canlıya alınması ile beraber insanlar sisteme kodlar yazarak, forumlarda veya mail gruplarında tartışmaya başlıyorlar. Bu tartışmalar günümüzde halen devam eden “Bitcoin balon mu?” sorusu üzerinden ilerliyor. O dönemde projeye inanmayan insanlara günümüzde Bitcoin fiyatını gösterirsek, dönemin “balon?” diyenlerine bir cevap niteliği taşıyor.</p>

### 3.2 Blockchain (Blok Zinciri) Nedir?
<p> Herhangi bir merkez ya da otoriteye ihtiyaç duymadan, verilerin dağıtık ağ üzerinde saklandığı kayıt teknolojisine Blockchain ya da Blok Zinciri denir. İlk kripto para birimi olan Bitcoin ile hayatımıza giren Blockchain, eski verilerde düzenleme olanağı sunmaz. Dolayısıyla geleneksel veri tabanları gibi değil, işlemlerin ardı sıra listelendiği dijital bir kayıt defteri şeklinde çalışır.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282686-8025a75b-0c4f-4c1a-997f-a8f23c8a0e3f.png"></br> Şekil 5 - Blok Zinciri
</p>
<p> Blockchain de veriler bloklara giriş tarihine göre art arda sıralanır. Her blok içinde işlem bilgileri ve önceki blokun şifrelenmiş özet kodu (Hash) bulunur. Her blok, kendilerinden önceki bloğa şifreli biçimde bağlı olduğundan, herhangi birinde değişiklik yapılması, sonraki tüm bloklarda değişiklik meydana getirir. Bu sayede verilerin asla değiştirilmediğinden emin olunur. </p>
<p> Burada Blockchain’i bir altyapı şeklinde düşünebiliriz. Sadece bahsetmek istediğim bir nokta da Bitcoin ve Blockchain’in tamamen farklı şeyler olmasıdır. Blockchain bir altyapı teknolojisi iken, Bitcoin bu altyapı üzerine uygulanmış bir finansal üründür. Yani Bitcoin bir üründür, Ethereum bir üründür ama bunların hepsi bir Blockchain sistemleri olup içlerinde farklılıklar göstermektedir. Blockchain, dağıtılmış defter teknolojisi (Distributed Ledger) ve şifreleme (Kriptoloji) ‘nin toplamı olarak düşünebiliriz.</p>

### 3.2.1 Transactions (İşlemler)
<p> Transaction(işlem), kripto para biriminin değerinin, blok zincir ağında bir varlıktan diğerine taşınması işlemine verilen isimdir. </p>
<p>Transaction’lar normal bankacılık sistemlerinde bir kişiden başka bir kişiye para gönderdiğin zaman örneğin, A kişisinin B kişisine 10 TL göndermesi bir Transaction ‘dır ve bu işlemleri bankalar kendi sistemlerinde tutarlar. Blockchain de aynı şekilde Transaction ‘lar Ledger(defter) adını verdiğimiz bu yerde tutulmaktadır.</p>
<p>Bir Bitcoin’i bir başkasına gönderdiğinizde, cüzdanınızdan parayı gönderdiğiniz kişinin adresi olan bir işlem çıktısı oluşturur. Bu işlem daha sonra Bitcoin ağına işlem girişi olarak Bitcoin adresinizle kaydedilecektir. Bu kişi söz konusu Bitcoin’leri başka birine gönderdiğinde, adresi de işlem girdisi olur. Diğer kişinin Bitcoin adresi ise işlem çıktısı olur. Süreç bu şekilde devam eder. </p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282795-9d5bb2ab-37ef-439b-8de7-64919008e3b4.png"></br> Şekil 6 - Transaction süreci
</p>
<p> Bu sistemi kullanarak, insanlar Bitcoin işlemlerini Bitcoin oluşturulduğu zamana kadar izleyebilir ve kimin herhangi bir zamanda kime ne gönderdiğini anlayabilir. Bu ise, tüm işlemlerin şeffaf bir sistem içerisinde gerçekleştiğini gösterir.</p>

### 3.2.1.1 Dijital İmza
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147282872-11b8c37c-78e0-403b-bd57-1e7d314064c5.png"></br> Şekil 7 - Transaction İmza
</p>
<p> Şekil 7 ‘deki örnekte Onur, Mert kişisine 5 Bitcoin gönderiyor. Bu Onur tarafından imzalanmış veri ile gönderiliyor. Bu imzalar Asimetrik şifreleme yöntemi ile yapılmaktadır. Onur veriyi Private Key ile imzalayarak Mert’e gönderiyor. Mert ve düğümdeki (Nodes) tüm cihazlar ise Onur’un Public Key’ine sahiptirler. Onur’un gönderdiği işlemin Public Key’i ile gerçekten Onur tarafından mı imzalanmış diye Onur’un Private Key’i ile sorgulanıyor. Eşleşme başarılı ise sistem buna doğruluğu veriyor.</p>

•	21 Milyon Bitcoin üretildiğinde madenciler nasıl ödül alacak?

<p> Bildiğimiz gibi Bitcoin’in arzı 21 milyon adet ile sınırlıdır. Bu sistem ilk çıktığında Satoshi diyor ki, “Arkadaş biz her Transaction ’u alıp bloğa ekleyemeyiz. Neden? Çünkü her Transaction’u bloğa eklersem milyarlarca blok olur.” 5-10 yıl sonra madenciler geriye dönük 0’dan itibaren Transaction geldiğinde yarışmaya başlamadan önce bütün bloklardaki veriler doğruluğunu kontrol etmesi milyarlarca blok olduğundan devasa bir iş yükü oluşturacaktır. Zaman ilerledikçe madencilerin çalışma kapasitesi artacağı için madenciler yavaşlamaya başlayacaktır.</p>
<p>Buna çözüm olarak Satoshi, her 10 dakika da bir mevcut Transaction’ları bir bloğa eklersek X zamandan sonra bizim blok sayımız şu adete ulaşır ve sistem ağırlaşmadan devam edebilir gibi fikir atıp hesaplaması yapılıyor. Bu 10 dakika da bir tane Transaction ya da bin tane Transaction gelebilir. Bunu optimize etmek için sistem kendi içinde otomatik olarak difficulty(zorluk) seviyesini ayarlar. Zorluk, global olarak gün geçtikçe artan madenci ve işlemci gücü yatırımlarından da etkilenir.</p>
<p>Zorluğun derecesinin artması belli oranda Bitcoin üretimini azaltacağından dolayı Bitcoin değerinin de sürekli olarak artmasında etki eder. 21 Milyon Bitcoin üretildikten sonra zorluk derecesi bitecek ve ortada madencilerin çözeceği problem kalmayacak. Bu aşamadan sonra veya bu son aşamaya gelmeden önce elbette bir Hard Fork çıkacaktır. Madenci ve Hard Fork kavramlarını ilerde detaylı bir şekilde göreceğiz.</p>

### 3.2.2 Dağıtılmış Defter Sistemi (Distributed Ledger)
<p> Dağıtık defter teknolojisi (DLT); şifrelenip parçalara ayrılmış verilerin merkeziyetsiz biçimde saklandığı altyapıya denir.</p>
<p> Ağ katılımcıları yetkileri dahilinde verilere erişebilir, güncelleme yapabilir, veri doğrulama işlemlerine destek verebilirler. Verinin birden fazla noktada bulunması ve sistemin ağ katılımcıları arasında kurulan Consensus (Fikir birliği) ile işlemesi sayesinde otorite veya yöneticiye ihtiyaç duymaz.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283219-8e072e6e-ac29-4738-8705-113d3dcfa3fc.png"></br> Şekil 8 - Distributed Ledger Teknolojisi
</p>
<p> Eşler arası (P2P) ağ sistemi üzerine kurulan dağıtık defter teknolojisi, ağın kurallarına bağlı olarak herkes tarafından erişilebilen açık (Public) ya da yetki sahibi kullanıcıların erişebildiği (Private) yapıda geliştirilebilir.</p>
<p> Normalde bankacılık sistemlerinde Bir A kişisinin hesabına nereden para gelmiş veya kime ne göndermiş gibi bilgileri bilemiyoruz. Fakat Satoshi’nin ortaya koyduğu Blockchain sistemindeki çözümde bu bilgiler herkes tarafından görülebilmektedir. Bütün dünya üzerindeki kullanıcılar (nodes) tarafından tutulun bu defterlerde bu dataları siz gözlemleyebiliyorsunuz. Bu ne demek, yani ben size Blockchain üzerindeki adresimi verirsem siz benim işlem akışımı görebilirsiniz.</p>

### 3.2.3 Merkezi Olmayan Yapısı
<p> Kritik bir bilgi olarak, defterdeki bu Transaction ‘lar merkeziyetsiz olarak tutulmasıdır. Hatırlarsak Satoshi Bankacılık sistemlerindeki problemlerden bahsediyordu. Bunlardan bir tanesi de merkezi bir yapıda olmasıydı. Merkezi yapı nedir? Ben bir işlem yapacağım zaman örneğin, A kişisine para göndereceğim zaman bir anda farklı kurumlar belirmektedir. Banka aradan çıkar “Bunu anca benim üzerimden gönderebilirsin” der. Başka bir yerden Mastercard, yurt dışına göndereceksem Swift gibi sistemler çıkar ve her biri bizden kesinti yaparlar.</p>
<p>	Örneğin, toplamda 100 TL göndereceksem belki 90 lira ulaştırabileceğim. Belki bu işlem 3-4 gün sonra gerçekleşebilecek. Satoshi burada “Hem para kesintisi var hem de vakit kaybı var ve biz bu aracı kurumlara neden güveniyoruz” sorusunu sormuş ve bu bilgi çağında bu işlemleri belirli algoritmaların üzerine konumlandırırsak bu kurumlara ihtiyacımızın kalmayacağını söylemiştir. Bu problem ise Blockchain ‘in “Merkeziyetsiz” olmasına götürmektedir.</p>
<p>	Eğer güvenilir bir merkezi kurum olmazsa bu sefer verinin doğruluğunu veya bakiyeleri kim kontrol edecek? Örneğin, ben A kişisine 100 TL göndermek istiyorum fakat bakiyemde 100 TL ‘nin olduğunu kim kontrol edecek? Burada devreye Nodes (düğümler) giriyor.</p>

### 3.2.4 Nodes (Düğümler)
<p>	Sadece tek bir bilgisayarda veya başka bir donanım aygıtında bulunan blok zincirinin bir kopyasıdır. Bu düğümler temelde, insanların blok zinciri üzerinde meydana gelen Transaction‘ları takip etmek için kullandıkları defterlerin bir nevi kopyasıdır. Blok zincirinin bütün işlem geçmişinin kopyasını elde edebilir. Fakat şöyle bir sorun var; bu düğümleri çalıştırabilmek için çok fazla alana ve belleğe ihtiyacınız var. </p>
	<p>Node’lar şu kontrolleri yapar:</p>
•	Kurallara uygun miktarda coin üretildi mi?</br>
•	Transferler uygun biçimde imzalandı mı?</br>
•	Bloklar doğru veri formatında mı?</br>
•	Çifte harcama (double spend) yapıldı mı?</br>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283573-5c38fe2c-9422-4896-8fc3-dbaecd8abd7d.png"></br> Şekil 9 – Nodes (Düğümler)
</p>
<p> Merkezi bir yapının olmadığı ama birilerinin bunu kontrol etmesi gerektiğini konuştuk. Satoshi soruna şöyle çözüm üretiyor, “Sistemdeki bütün kullanıcılar yani sistemde 50 kişi varsa bu 50 kişinin hepsi birer düğüm(node) dür” demiştir. Herkesin bilgisayarında çalışan bir uygulama ve herkesi birer oy hakkı olduğunu söylüyor. Burada Consensus tanımına getiriyor bizi. Yetkili Node’lar. Consensus kurallarına uymayan işlemleri geçersiz kılma yetkisine sahiptir.</p>

### 3.2.5 Ağdaki Fikir Birliği (Consensus)
<p> Satoshi sistemi ilk canlıya aldığında sisteme 50 Bitcoin konuluyor. Bu 50 Bitcoin’in 10 tanesini A kişisine, 40 tanesini B kişisine olmak üzere toplam iki adet Transaction gerçekleştiriliyor. Sistemde birileri Satoshi’nin 50 Bitcoin var mı? diye kontrol etmesi gerekiyor ki ileride de bu şekilde çalışmaya devam etsin.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283661-ce5655a8-2c39-463b-bdaf-c0cf924177fc.png"></br> Şekil 10 – Fikir Birliği (Consensus)
</p>
<p> Bu sürdürebilirliği devam ettirmek için belirli kullanıcılara teşvik vermek gerekiyor ki bu insanlar bilgisayarlarını çalıştırsınlar, sistemdeki Transaction ‘ları kontrol etsinler. Bu teşvik verme ise bizi Mining (madencilik) kavramına götürüyor.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283721-a266b6d5-27b1-4b90-b47f-1712d84c525a.png"></br> Şekil 11 - Madenci Kavramı
</p>
<p>Çoğu kez karıştırılan bir olay ise Bitcoin, madenciler tarafından kazılarak bulunmamasıdır. Madenciler yani bu Transaction ‘ları, bakiyeleri, adreslerin doğruluğu vb. kontrol eden arkadaşlar doğrulama işlemlerini yaparlar. Bütün Transaction ‘lar doğru ise her node “evet doğru” oyunu verir ve en az %51 oy sonucu verildiğinde madenciler arasında yarış başlar. Madencilere bir “Artificial puzzle” verilerek en hızlı çözeni bulabilmek için yarışırlar. Puzzle’ı ilk çözen madenciye teşvik olarak ödül Bitcoin’i verilir. Tüm madencilere bu işlemi yaptığı için teşvik verilmemesinin sebebi vardır. Bunun sebebi her madenciye teşvik olarak Bitcoin verilirse her blok üretildiğinde piyasaya daha fazla Bitcoin girişi olacaktı. Bu devasa adet artışı ise Bitcoin’in değerini düşürecektir.</p> 
<p> Satoshi Bitcoin ağında fikir birliği (Consensus) anlamında İş Kanıtı (Proof Of Work-PoW) algoritmasını önerdi ve gerçekleştirdi. İlerleyen yıllarda ise bu PoW’un güç tüketimi konusundaki dezavantajı yüzünden diğer Blockchain tasarımcıları yeni protokol olarak Hisse Kanıtı Algoritması (Proof Of Stake-PoS) tasarlanmıştır.</p>

### 3.2.5.1 İş Kanıtı (Proof of Work-PoW)
<p> Proof of Work kripto paralardaki kullanımıyla bilinir. Bitcoin üretmek için madenciler yapbozları çözmede yarışırlar. Böylece bir bloğu tamamlayıp yeni çıkarılmış coin’lerle ödüllendirilirler. İşte burada bahsi geçen yapboz, Proof of Work’dür.</p>
<p> Bir Proof of Work fikir birliğinde yapbozu çözme şansınızı artırmanızın tek yolu daha çok bilgisayar gücü kullanmaktır. Temelde, bir bloğu doğrulama şansınız donanımınızın kaç tane bilgisayar döngüsünü kaldırabildiğine denk düşer.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283838-435651fc-a571-4a08-8605-54f8ecdd7085.png"></br> Şekil 12 - İş Kanıtı (PoW)
</p>
<p> Proof of Work, Bitcoin ve Ethereum dahil birçok kripto paranın kullandığı fikir birliği mekanizmasıdır. Bununla birlikte 2020’nin ilk çeyreğindeki bir zaman diliminde Ethereum network’ünü yükseltmeye ve Proof of Stake mekanizmasına geçmeye hazırlanmıştır.</p>
<p> Çünkü PoW (iş kanıtı), madencilerin donanımlarının gücüne göre daha çok işlem yapmaktaydı. Daha çok donanım gücü olan daha çok işlem yapar ve daha çok komisyon alır. Bu da çok fazla enerji tüketimi ve doğa ya zararı bulunuyordu. ETH 2.0 güncellemesi ile PoS (hisse kanıtı) yöntemine geçerek elinde Ether coini daha fazla olan daha fazla işlem yapma gücüne sahip olacaktır. Doğa için güzel haber fakat madenciler için kötü bir haber niteliğindedir.</p>

### 3.2.5.2 Hisse Kanıtı (Proof of Stake-PoS)
<p> Proof of Stake matematiksel bir yapboz kullanmaz. Aksine belirli bir zamanda desteklenen coin’lerin sayısından etkilenen belirleyici bir olasılığa dayanır. Bir başka deyişle, geçerli bir blok oluşturma şansınız ‘kilitlediğiniz’ coin sayısıyla orantılı olacaktır. Örneğin, 30 coin’i olan bir insanın bir sonraki blok onaylayıcısı olması ihtimali 10 coin’i olan bir insanınkinden fazladır.</p>
<p> PoS ile yaratılan yeni coin’ler yoktur; tüm coin’ler en başta yaratılır. Onaylayıcılar yeni çıkarılan coin’ler yerine işlem ücretleriyle ödüllendirilirler.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147283938-22b909ae-1993-4c4b-a1ee-68605c70f942.png"></br> Şekil 13 - PoW vs PoS
</p>

### 3.2.6 Değişmezlik (İmmulability)
<p>Değişmezlik Blockchain’lerin, hali hazırda onaylanmış olan işlemlerin değiştirilmesini engellemedeki becerisine denir. Bu işlemler genellikle kripto para transferlerine ilişkin olsa da dijital verinin parayla ilişkin olmayan diğer türlerinin kayıtlarına yönelik de olabilir.</p>
<p> Fikir birliği, değişmezlikle birleşerek Blockchain ağlarındaki veri güvenliğinin genel çerçevesini sunar. Fikir birliği algoritmaları sistem kurallarına uyulduğunu ve dahil olan tüm partilerin ağın mevcut durumu hakkında fikir birliğine vardığını garantilerken, değişmezlik de geçerli olarak kabul edilen her bir bloğun ardından verinin ve işlem kayıtlarının bütünlüğünü garantiler.</p>
<p>Değişmezlik kavramına göre bir sisteme giriş yapıldıktan sonra Hash algoritmaları sayesinde sistem kesinlikle değişikliğe uğramaz.  A kişisi B kişisine 10 btc gönderdikten sonra ileriye dönük kesinlikle değiştirilemez. Örneğin 10 btc, daha sonradan 15 veya 6 btc yapılamaz.</p>

### 3.3 Blockchain Ağlarında Gizlilik
<p> Dünyadaki ilk ve en popüler Blockchain ağlarından birisi olan Bitcoin, Blockchain ağının tasarımı gereği, üzerinde oluşturulan kişilere ait cüzdan bilgileri için gerçek kimlik bilgileri talep edilemez. Farklı bir ifade ile Bitcoin Blockchain ağına giren bir kişinin gerçek hayatta kim olduğunu, sadece ağ yapısını inceleyerek pratik olarak bulmak neredeyse imkansızdır.</p>
<p> Bir Blockchain ağı üzerindeki gizli yani şifrelenmiş bilgilerin bir dış gözlemci için orijinal haline çevrilmesi mümkün olmasa da açık işlem bilgileri üzerinden çeşitli analiz çalışmaları yapılabilir ve bu işlemler üzerinde farklı veri modellemeleri gerçekleştirilebilir.</p>
<p> Kripto paraların alım ve satım işlemleri, tüm kimlik bilgilerinizi en detaylı şekilde sizden alan çeşitli borsalar üzerinde yapıldığı için, gizlilik veya anonimlik diye bir şey söz konusu değildir.</p>

## 4. BLOCKCHAIN ÇEŞİTLERİ 
### 4.1 Genel Blockchain Ağları (Public Blockchain)

<p> Public yani açık Blockchain türünde, yapılan her işlem ağdaki tüm kullanıcılar tarafından gözlemlenebilir. İşlemlerin hepsi gözüküyor olmasına rağmen kullanıcılar dilerse anonim profil kullanabilir ve gerçek kimliklerini gizleyebilirler. Bitcoin ve Ethereum bu ağ türlerinin örnekleridir.</p>

### 4.2 Özel Blockchain Ağları (Private Blockchain)
<p> Tamamen özel olan bu ağ modelinde işlemler tek bir kuruluş tarafından kontrol edilir. Verileri kimin erişebileceği, kimin işlem yapabileceği ve kimin düzenleme hakkında sahip olabileceğine ağın sahibi karar ver. Merkezi yönetime ihtiyaç duymama özelliğine ters olan bu ağ sistemi test ortamlarında tercih edilir. Uluslararası finans kuruluşları ve regülatörlerin ortaklığında geliştirilen R3, bu sisteme bir örnektedir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147284160-200bd984-42ed-48d7-9440-95288755d559.png"></br> Şekil 14 - Public vs Private Blockchain
</p>

### 4.3 Yarı Özel Blockchain Ağları (Semi-Private Blockchain)
<p> Semi-Private (Yarı özel) Blockchain ağları, belirlenmiş kriterleri karşılayan herhangi bir kullanıcıya erişim izni verir. Bir başka değişle, ağ sistemini belirleyen kurum bünyesindeki herkes ağa giriş yapabilir. Kurum tarafından tercih edilmesi durumunda ağ tamamen açık halede dönüştürülebilir. Yarı-özel Blockchain ağları kamusal uygulamalara olduğu kadar, firmalar arasındaki transferler, B2B içinde uygundur. Örnek: Ripple Ağı</p>

### 4.4 Konsorsiyum Blockchain Ağları
<p> Konsorsiyum Blockchain sisteminde ağa herkes erişiyor olsa da, işlemler sadece seçilmiş grup tarafından gözlemlenebilir. Bu tip Blockchain ağları, işlemlerin muhasebe ekibi ya da maili kurum tarafından takip edilmesi için kullanılabilir. Bu ağ türünde yetkililer dilerse işlemleri herkese açık hale getirebilirler ya da belirlenmiş katılımcılara giriş izni verirler. Örnek: Hyperledger Ağı</p>
<p> Örnek Şablon: Aşağıdaki şablon ağ çeşitlerini daha iyi kavramanıza yardımcı olacaktır.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147284271-49c31ed3-92cc-47a5-a557-c11f9223eac8.png"></br> Şekil 15 - Blockchain Çeşitleri
</p>

### 5. BLOCKCHAIN MİMARİSİ VE ÇALIŞMA PRENSİPLERİ
## 5.1 Blockchain Nasıl Çalışır?
<p> Blockchain teknolojisinin çalışma prensibinin altında yatan en önemli özellikler; anonim, dağıtık, merkezsiz ve kamusal olmasına karşın bozulamaz ve hacklenemez oluşudur.</p>
<p> Veriler bloklar halinde saklanır. Madenci ismi verilen ağa bağlı bilgisayarlar, işleme konan verileri bir araya getirerek şifreleme standartlarına uygun biçimde arşivler ve blok halinde getirir. İşlemlerin tamamına ait veriler, özet bir fonksiyona(hash) dönüştürülür. Bitcoin ağında örnek verecek olursak, hash fonksiyon oluşturmak için SHA-256 şifreleme algoritması kullanılır.</p>
<p> Blockchain ağına destek veren, node(düğüm) yani madenciler tarafından blokların ve şifreleme bilgilerinin kontrolü yapılır. Yeterli onay alması durumunda blok zincire eklenir. Birbirine özel şifrelerle bağlanan blokların sıralı biçimde listelenmesi sayesinde hayali bir zincir meydana gelir.</p>
<p> Gerçekleşen işlemin ardından madenci, kullanılan Consensus yapısına uygun biçimde ödül kazanır.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147284397-c2431d26-5497-4b03-9872-9af16c353ffc.png"></br> Şekil 16 - Blockchain Çalışma Döngüsü
</p>

### 5.2 Blok Yapısı
<p> Blockchain yaklaşımında veriler blok adı verilen yapılarda tutulur. Blok yapısı için “güvenlik” kavramı içerdiği bilgileri dış dünyadan saklaması olarak değil, oluşturduktan sonra içerdiği bilgilerin değiştirilmeyeceğini anlamında kullanılır. Bunu sağlamak için Hashing ve zaman bilgisi kullanılmaktadır.
<p> Blockchain olan bir sistemde işlemler (transactions) ağdaki tüm düğümler(kullanıcılar) tarafından denetlenir. Her kullanıcı tüm zincirin bir kopyasına sahiptir ve işlemleri bunun üzerinde yapar. Yeni Transaction ’ı ağdaki kullanıcıların en az yüzde 51’i geçerli kabul ederse bloğa yazılır ve Bitcoin ağında en geç 10 dakika da, Ethereum ’da ise 15 saniyede yeni blok zincire eklenir.
<p> Temel olarak blok iki parçadan oluşur;
1)	Blok içerisindeki veri bütünlüğünü kontrol etmek amaçlı başlık (Block header) bilgisi.</br>
2)	Blok içerisindeki veriler</br>

<p>Her blok kendi hash değerini, bir önceki bloğun hash değerini, oluşturulan zaman damgasını ve data değerlerini içerir.</p>

•	Timestamp: Bloğun oluşturulduğu zaman,</br>
•	Data: Bloğun içeriğindeki şifreli veri,</br>
•	Current Hash: Bloğun sadece kendisine ait olan tekil anahtar yani parmak izi.</br>
•	Previous Hash: Bloğun bağlı olduğu bir önceki bloğun Hash değeridir.</br>
•	Nonce: Sistemin zorluğuna göre rastgele oluşturulan değerdir. Madenciler bu değere ulaştığında ödül verilir.</br>
<p>Not: Hash değeri oluşturulurken Timestamp, Previous Hash ve Data kullanılır.</p>
<p>Genesis Blok: Zincirdeki ilk bloğa denir. Bağlı olduğu bir önceki blok olmadığı için Previous Hash değeri “0” dır. Aşağıdaki blok yapısında ilk blok yani Genesis blok olduğunu Previous Hash değerinin sıfır olmasından anlayabiliyoruz.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147284557-b8a15dff-861f-453b-b459-9de748b97192.png"></br> Şekil 17 - Genesis Blok
</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147284591-f438b636-f513-47a5-a64b-ef297c5e9f1c.png"></br> Şekil 18 - Blockchain Sıra Yapısı
</p>
<p>Bir bloktaki veriler değiştirilmeye kalkışılırsa tüm blokların düzenlenmesi gerekir. Çünkü her blok bir öncekinin ve kendi Hash'ini tutmaktadır. Eğer bir bloktaki verileri değiştirmeyi başarırsa o bloğun bağlı olduğu bloklarında hash değerlerini, onlarında bloklarının bağlı olduğu diğer blokların hash değerleri gibi tüm zinciri bu şekilde değiştirerek gitmesi gerekmektedir. Bunu anca tüm ağın üzerinde %51 söz hakkına sahip olması gerekir. Bunun gerçekleşmesine imkansız diyemiyoruz fakat şuan böyle bir teknoloji bulunmamaktadır. Şuan da bile Kuantum bilgisayarlar için algoritmalar geliştirilmektedir. Bu olayın gerçekleşmesi için devletler büyük örgütlerinde girmesi gerekebilir. Eğer bu saldırı gerçekleşirse interneti ele geçirdiler diyebiliriz.</p>
<p>Not: Bitcoin ağında yazılan ve işlenen tüm verileri, blokları ve bunların bilgilerini bu site üzerinden inceleyerek daha detaylı bilgi sahibi olabilirsiniz.(https://www.blockchain.com/tr/explorer)</p>

### 5.3 Blockchain Cüzdanları
<p> Blockchain cüzdanları, ödeme yapmak için gerekli olan özel anahtarları saklamanızı sağlarlar. Farklı tipteki cihazlar için farklı şekillerde olabilirler. Bilgisayarda tutmaktan sakınıyorsanız, bunları kağıt üzerinde bile saklayabilirsiniz. Bitcoin cüzdanınızı güvence altına almanız elbette çok önemlidir.</p>
<p> Bitcoin’ler bildiğimiz banknotların modern halleridir ve her geçen gün iş yerleri ödeme olarak Bitcoin’i kabul etmeye başlamaktadır. Bitcoin nasıl üretilir ve bir Bitcoin işlemi nasıl gerçekleşir artık biliyoruz, peki ama nerede tutuluyorlar? Günlük hayatta kullandığımız paraları elle tutulur, gözle görülür bir cüzdanda tutarız. Bitcoinler’de de durum buna benzer ama Bitcoin’ler veya kripto paralar normalde elle tutulur bir cüzdanda değil, dijital bir cüzdanda tutulur.</p>
<p> Aslında tam olarak doğru söylemek gerekirse, teknik olarak Bitcoin veya kripto paralar hiçbir yerde tutulmuyor. Bunun yerine sizin sakladığınız şey, halka açık Bitcoin adresinize erişmek ve işlemleri onaylamak için kullandığınız güvenli dijital anahtarlardır.</p>
	<p>Günümüzde 5 çeşit Blockchain cüzdanı bulunmaktadır;</p>
•	Masaüstü Cüzdanları</br>
•	Çevrimiçi Cüzdanlar</br>
•	Mobil Cüzdanlar</br>
•	Donanım Cüzdanları</br>
•	Kağıt Cüzdanlar</br>
<p>Günümüzde popüler olan www.blockchain.com/wallet adresinden Blockchain cüzdanı oluşturabilirsiniz. Örnek cüzdan görünümü ve adresi şekil 19’daki gibidir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285197-c2dd6503-2c14-45cc-80aa-921bc5fcef80.png"></br> Şekil 19 – Örnek Blockchain Cüzdanı
</p>

### 5.5 Blockchain Madenciliği (Mining)
<p> Madencilik kavramı diğer Blockchain platformlarına göre değişiklik göstermektedir. Genel çatı altında bakıldığında, bulunduğu platformun işlemlerini (transactions) onaylayan, bloklara yazan ve o Blockchain ağının kripto para birimini üretmesini sağlayan bir yapıdır.</p>
<p> Madenci, yapılan işlemleri biriktiren ve bunları bloklar halinde organize eden bir Node’dur. Yapılan her işlemde madenci Node’ları bu işlemi alıp doğruladıktan sonra hafıza havuzuna ekler ve bunları çoklu işlem blokları olarak birleştirmeye başlar. Bir bloğun kazım sürecindeki ilk aldım hafıza havuzundaki her bir işlemin hashlenmesidir.</p>
<p> Sürece başlamadan önce, madenci node, kendisine madencilik ödülünü göndereceği bir işlem ekler. Coinbase olarak adlandırılan bu işlem aynı zamanda coinlerin “yoktan var edildiği”, çoğu zaman da yeni blokta yapılan ilk işlemdir.</p>
<p> Her bir alım satım işlemi hashlendikten sonra, bu hashler Merkle ağacı ya da hash ağacı olarak organize edilir, yani hashler ikili eşler olarak düzenlenir ve kök hash ya da Merkle kökü olarak da bilinen “ağacın tepe noktasına” ulaşana kadar hash edilir. Kök hash, bir önceki bloğun hashi ve nonce olarak da bilinen rastgele bir sayıyla birlikte bloğun başlığına yerleştirilir. Daha sonra blok başlığı hash edilerek bloğun belirteci (Header) olarak kullanılacak bir çıktı oluşturulur.</p>
<p> Blok başlığı (Header) hashi belirli miktarda sıfır ile başlamalıdır. Hashleme zorluğu olarak da bilinen bu hedef değer bir denge unsuru olarak yeni blokların yaratılma hızının, ağdaki hashleme gücüne orantılı kalmasını sağlar.</p>
<p> Aralarından biri sonunda geçerli bir hash bulana kadar ağdaki madenciler başlığı nonce’dan yineleyerek tekrar tekrar hash ederler. Geçerli bir hash bulunduğunda, bunu ilk bulan node, ağa yayınlar. Diğer tüm Node’lar bu hashin geçerli olup olmadığını kontrol eder ve bloğu kendi Blockchain kopyasına ekleyerek bir sonraki bloğu kazmaya devam eder.</p>
•	Maden Havuzları
<p> Blok ödülü geçerli bir hashi bulan ilk madenciye verilse de, geçerli bir hash bulma olasılığını ağın toplam kazı gücüyle doğru orantılıdır. Düşük yüzdeli bir kazı gücüne sahip madencilerin kendi başlarına bir sonraki bloğu bulma şansları oldukça düşüktür. Bu sorunu çözmek için madencilik havuzları yaratılmıştır.</p>
<p> Havuzlarda işleme güçlerini bir ağda paylaşan madencilerin kaynakları bir araya getirilir ve ödüller bir blok bulma olasılığına yönelik yaptıkları katkı payıyla orantılı olarak havuzdaki herkesle eşit miktarda paylaşılır.</p>

### 5.5 Çatallaşma (Fork)
<p> Geçmişe sahip olan blok zincirinin, iki farklı düşünce yapısı sebebi ile yeni bir coin oluşmasına neden olan güncellemedir. Çatallaşmaya en iyi örnek Ethereum çatallaşması ile oluşan Ethereum Classic’tir. Çatallaşma 2 şekilde olmaktadır.1- Geçici olan çatallanma, 2- Kalıcı olan çatallaşmadır. Diğer tarihsel olarak yaşanacak olan en yakın çatallaşma ise 15 Kasım’da BCH (Bitcoin Cash) olacaktır.</p>

•	Çatallanma (Fork) neden olur?

<p> Kripto para birimlerinde çatallanma sebebi farklı olabilmektedir. Bazen dijital para birimi için güncelleme veya değişiklik yapılması gerektiğinde yapılmaktadır. Bazen de sistem içinde oluşan fikir ayrılıkları bu çatallaşmayı oluşturur.</p>
<p>Çatallaşma iki şekilde kendini gösterir;</p>
1)	Hard Fork: Sistem kullanıcıları, eski versiyondan yeni olan versiyona geçmek için iki ayrı yazılım oluştururlar. Ancak bu yazılımların farklı versiyonunu kullanmaktadırlar. Eski sürüm ile yeni olan sürüm arasında uyuşmazlıklar olduğu zaman Hard Fork yaratma kararı alınmaktadır.
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285634-57a0af8a-a2dd-423f-a833-a701a2e9e3d1.png"></br> Şekil 20 - Hard Fork Uygulanmış Zincir
</p>
2)	Soft Fork: Sadece önceden geçerli olan işlemlerin geçersiz hale getirilmiş olduğu yazılım programlarındaki değişikliklere “Soft Fork” denilmektedir. Bu sistem sayesinde tek bir zincir ile devam edilerek eskiden oluşturulan blokta bulunan veriler yeni kurallar çerçevesinde el değiştirmektedir.
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285703-44d6da3f-943e-4e76-87de-b67b683f8171.png"></br> Şekil 21 - Soft Fork Uygulanmış Zincir 
</p>

5.6 En Uzun Blockchain Kaydı
<p> Dağıtık merkezi olmayan büyük ölçekli bir mimariyle bağlı her bir makinedeki blok yapısının her zaman tutarlı olması beklenemez. Sistem içerisinde yakın zamanlı paralel blok üretimi, blokların ağ üzerindeki makinelere farklı zamanlarda iletilmesi gibi nedenlerden dolayı ağa bağlı makineler üzerinde Blockchain ağında farklı blok sıralamasına sahip düğümlerin (node) bulunması karşılaşılan bir durumdur. Bu durumu çözebilmek için makineler her zaman “en uzun Blockchain kaydı geçerlidir” mantığı ile hareket edip, bu Blockchain kaydını genişletmek amacı ile işlem yaparlar.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285756-198e3c75-3957-41cb-bb42-b19e57474579.png"></br> Şekil 22 - En Uzun Zincir Seçimi
</p>

## 6. BLOCKCHAIN AĞLARINDA ŞİFRELEME
### 6.1 Güvenli Şifreleme (Secure Hash) 
<p> Bu yaklaşım, matematiksel işlemler kullanarak büyük bir veriden kıyasla daha küçük bir özet bilgi (dijital bir parmak izi) üretilesine dayanır. Bu üretim yapısı:</p>
•	Aynı veri kümesi için her zaman aynı özet bilgiyi üretir.</br>
•	Tek yönlüdür; yani özet bilgiden kaynak veriye geri dönülmesi mümkün değildir. Özet bilgiden kaynağa ulaşmanın tek yolu, kaynak kümesindeki her olası veri yapısı için güvenli özetleme fonksiyonunu çalıştırıp, oluşan özet bilgi ile elimizdeki özet bilgiyi karşılaştırmaktır.</br>
•	Hızlı olarak gerçekleştirilen işlemlerdir.</br>
•	Küçük veri değişikliklerinde bile çok farklı özet bilgi üretir ve bu özelliğe “çığ etkisi” adı verilir.</br>
<p> Güvenli özetleme algoritmaları, özetledikleri veriden bağımsız olarak sabit uzunlukta özet değer üretirler, örneğin SHA-1 algoritmasının ürettiği özet değerler 160 bit uzunlukta iken, SHA-256 algoritmasında özet bilgi uzunluğu 256 bit’tir. Algoritma sonuçları sabit uzunlukta olduklarından teorik olarak farklı veri kümeleri için özet değerlerinin çakışması mümkündür. Bu olasılık göz ardı edilebilecek seviyede büyüktür.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285881-84618e28-1981-4b62-8d0e-8793c4b131ee.png"></br> Şekil 23 - SHA-256 Örnek
</p>

### 6.2 Merkle Ağaç Yapısı (Merkle Tree) 
<p> Merkle ağacı, büyük veri kümelerini güvenli ve hızlı bir şekilde doğrulamak için kullanılan, güvenli özetleme yapısı üzerinde geliştirilmiş bir yaklaşımdır. Merkle ağaç yapısında ikili (binary) bir ağaç yapısı oluşturulup, en alt seviyeye veri kümesindeki parçalar yerleştirilir. Sonrasında en alt seviyeden yukarıya doğru ikili bir şekilde özetleme değeri üretilerek ilerlenip, tüm ağaç yapısı için tekil bir özetleme değeri (Merkle kök değeri) üretilmiş olur.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147285959-526a8f9d-2c0f-4606-b600-9ad03285b2fb.png"></br> Şekil 24 - Merkle Ağaç Yapısı
</p>

## 6.3 Simetrik Şifreleme (Symmetric Encryption) 
<p> Bu yaklaşımda hem şifreleme hem çözümleme adımlarında aynı anahtar bilgisi kullanılmaktadır. Bundan dolayı anahtar bilgisinin sadece ilgili taraflar arasında paylaşması gerekmektedir, anahtarı ele geçiren herhangi bir taraf şifrelenmiş veriden orijinal veriye erişebilir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147286015-60eb9736-0fcb-4e91-9957-b53b8e83af87.png"></br> Şekil 25 - Simetrik Şifreleme
</p>

### 6.4 Asimetrik Şifreleme (Asymmetric Encryption) 
<p> Blockchain teknolojisinde en yaygın kullanılan şifreleme yöntemlerinden birisi “Asimetrik Şifreleme” dir. Asimetrik şifrelemede, kişilerin hem gizli anahtarı (private key) hem de herkese verdiği ortak anahtarı (public key) vardır. Kişi karşısındaki kişiye bir mesaj göndermek istediğinde karşısındaki kişinin ortak anahtarı ile metni şifreler. Bu mesajı sadece karşıdaki kişinin gizli anahtarı açabilir.</p>
 <p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147286090-38609242-6377-414a-8104-8c058d4228f7.png"></br> Şekil 26 - Asimetrik Şifreleme
</p>

## 7. BLOCKCHAIN UYGULAMALARINDA RİSKLER
## 7.1 Özel Anahtarın Saklanması (Private Key)
<p> Kripto para çözümlerinde ve Blockchain cüzdanlarındaki özel anahtarın saklanması, sahibinin sorumluluğundadır. Sahibinin bir özel anahtarı kaybetmesi durumunda, son kullanıcının elindeki şifrelenmiş işlemlerin sahipliği doğrulayacak hiçbir bilgi kalmaz.</p>
<p> Özel anahtarların başka bir kullanıcının eline geçmesi durumu, ilişkili varlıkların sahipliğini kaybetmek ile eş değer durumdur. Bu gibi problemlerin oluşmasını engellemek amacı ile kullanıcıların anahtar verilerini koruyacak yeni aracı kurum yapılarının oluşması muhtemel bir gelişmedir. Bu sebeple farklı alternatif çözümler sunan kripto para cüzdan uygulamaları, servisleri ve donanımlarının sayısı her geçen gün artmaktadır. Ancak bu yapılar da beraberinde farklı güvenlik sorunlarını getirmektedir.</p>
<p> Daha uzun vadede özel anahtarların biyometrik verilere bağlanması hedeflenmektedir.</p>

### 7.2 Enerji Tüketimi
<p> Proof of Work (PoW) fikir birliği algoritması kullanan Blockchain platformları, şu anda ciddi bir enerji tüketimi ve dolaylı olarak karbon ayak izi etkisi doğurmaktadır. Bitcoin Blockchain ağında yeni blokların eklenmesi için madenciler tarafından harcanan işlem gücünün tükettiği elektrik, dünya üzerindeki bazı küçük ülkelerin tükettiği elektrik miktarını geçmiş durumdadır. </p>
<p> Bu sebeple alternatif Fikir birliği (Consensus) algoritmaların geliştirilmesi ve enerji tüketiminin azaltılması için pek çok çalışma yürütülmektedir. Bunlardan birisi bir diğer Fikir birliği algoritması olan Proof Of Stake (PoS), elindeki hissenin değeri kadar söz sahibi olduğu için PoW’ da ki gibi yüksek kaynak tüketimi yapmamaktadır. Önümüzdeki yıllarda PoS gibi daha çevresel çözümlere gitmek için çeşitli uğraşlar sergilenmektedir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147286244-ee2ae925-cc60-4c19-a2a8-91996a6952cc.png"></br> Şekil 27 - Madencilerin Elektrik Tüketimi
</p>

### 7.3 Sınırlı Teşvik
<p> “Proof of Work” tipi mutabakat (fikir birliği) yaklaşımı kullanan Açık Blockchain ağlarında yeni blokların üretilmesi için gerçekleştirilen madencilik işlemi, genel olarak teşvik sistemi ile beslenmektedir. Kripto para üretim miktarı sınırlı olan durumlarda teşvik sisteminin sonlanması ile birlikte burada oluşacak madenci davranış şekli konusunda kesin bir sonuca varmamız şimdiden mümkün görülmemektedir.</p>

### 7.4 Yazılım Hataları, Açıklar ve Siber Saldırı Tehlikeleri
<p> Blockchain teknolojisi oldukça yeni bir teknolojidir, bundan dolayı şu anda kullanılan Blockchain platformları genel olarak “deney” olarak adlandırılmaktadır.</p> 
<p> Teknoloji çok yeni olduğu için öngörülemeyen yazılım hataları siber saldırganlara davetiye çıkartmakta ve özellikle Açık Blockchain platformlarındaki bu kusurlar tespit edildiği takdirde ciddi ekonomik kayıplar yaşanabilmektedir.</p> 
<p> Sahip oldukları açıkların giderilmesi ve yeniliklerin eklenmesi için platformlar üzerinde sürekli güncelleme çalışmaları yürütülmekte, ancak özellikle Açık Blockchain platformlarının merkezi olmayan, demokratik yapısı bu güncellemelerin gerçekleştirilmesinde her bir uç noktanın birlikte hareket etmesini gerektirmekte, bir anlaşmazlık durumunda ise çatallaşma adı verilen sonuçlar doğabilmektedir.</p>

### 7.5 Şifreleme ve Kuantum Bilgisayarlar
<p> Blockchain platformlarını en güçlü kılan özelliklerin başında kriptografi gelmektedir. Bu kapsamında kullanılan şifreleme yaklaşımları oldukça güçlü olsa da kuantum bilişim gibi alanlardaki gelişmelerle birlikte bu konuda ilerideki zamanlarda çeşitli zafiyetler görülebileceği düşünülmektedir.</p>
<p> Günümüzdeki bilgisayarların sadece 1 ve 0 ile işlem yapabildiği ikili(binary) sistemler kullanıyoruz. Ancak kuantum bilgisayarlarda 1 v 0 durumların birlikte ve aynı anda geçerli olduğu üçüncü bir durum daha bulunmaktadır. Her ne kadar bu bilgisayarlar günümüzde laboratuvarlarda kullanılıyor olsa da önümüzdeki 10 yıllar içerisinde daha erişebilir hale gelecektir.</p>
<p> Bu durum mevcut Blockchain platformları için bir risk oluşturmaktadır. Ancak bu sistem daha erişebilir olduğunda bu sefer kuantum bilgisayarlar ile şifreleme işlemleri gerçekleştirilecektir.</p>

### 7.6 Çatallaşma (Fork) Problemi
<p> Blockchain ağlarında yaşanabilen çatallaşma probleminin en büyük örneği “DAO Olayı” olarak adlandırılmaktadır ve 2016 yılında Ethereum Blockchain ağında gerçekleştir. Gelişmiş bir akıllı sözleşme olan DAO yaklaşımı (Merkeziyetsiz otonom organizasyonu), herhangi bir insan müdahalesi gerek kalmayacak şekilde, bir kurumun kurallarını ve karar verme mekanizmalarını bir akıllı sözleşme kapsamında tanımlayarak, çözüm sunmayı hedeflemiştir.</p>
<p> DAO projesi Nisan 2016 yılında Ethereum üzerinde çalışmak üzere tanımlanmış bir ICO gerçekleştirmiş ve 11.000 civarında kişinin katılımı ile beraber 170 milyon dolar değerinde Ether (ETH) toplamıştır. Ancak akıllı sözleşme yapısında bulunan açığı fark eden bir veya bir grup hacker, toplanan fonun 1/3 ‘ini kendi hesaplarına aktarmışlardır.</p>
<p> Bu durum sonrası, sadece bu olaya özgü işlemlerin iptali için mecburi Çatallaşma işlemi gerçekleştirilmiştir. Ancak Ethereum yapısı üzerindeki bazı kullanıcılar, “Kurallara uygun davranan her işlem geçerli bir işlemdir” düşüncesi ile bu değişikliği kabul etmemiştir. Eski kod yapısı ile devam eden grup Ethereum Classic (ETC) adını almış ve yeni kod yapısı ile devam edenler Ethereum (ETH) şeklinde yoluna devam etmiştir. Bu şekilde mecburi çatallaşma gerçekleşmiştir.</p>

## 8. BLOCKCHAIN PLATFORMLARI
<p> Birçok Blockchain platformları bulunmaktadır. Ancak Bitcoin, Ethereum, Hyperledger ve Ripple şu anda gerek açık kaynaklı grupların sahiplenmesi gerekse kurumsal yapıların sahiplenmesi ile birlikte en çok ilgi duyulan platformlara dönüşmüş durumdalar.</p>

### 8.1 Bitcoin Ağı
<p> Blockchain kavramının hayatımıza girmesinde en temel role sahip platform, şüphesiz Bitcoin platformudur. Bitcoin aynı zamanda en çok bilinen ve tanınan Blockchain platformudur. İlk olarak Kasım 2008’ de Satoshi Nakamoto adı ile yayınlanan bir makale kapsamında ortaya çıkmış, 2009 yılı başında açık bir ağ olarak faaliyete girmiştir.</p>
<p> Temel olarak P2P (uçtan uca) para transferi konusunda alternatif bir yaklaşım getirmektedir. Günümüz dünyasında para transferi yapabilmek için bankalar ya da konuda özelleşmiş ara kurumlar hizmet sunmaktadır. Ancak bu servisleri kullanarak gerçekleşen işlemler hem maliyetli olmakta hem de uzun sürelerde gerçekleşmektedir. Bitcoin platformu sayesinde bu aracılara gerek duymadan zaman ve maliyetten tasarruf ederek para transferlerini gerçekleştirebiliyoruz.</p>
<p> Bitcoin platformunda, kripto para birimi BTC ‘yi kullanılır. Toplam para arzı sınırlı olduğu için (21 milyon adet) piyasa da daha değerli durmaktadır. Fakat Bitcoin Blockchain ’de her 10 dakika da bir blok oluşmaktadır. Satoshi en başta blok oluşturma algoritmasını bu şekilde ayarlamıştır. Bu nedenle sınırlı sayıda üretilen 21.000.000 adet Bitcoin’in tahmini ne zaman üretimi duracağı hesaplanmaktadır. Bu yüzden Bitcoin para olarak değil, yatırım aracı (altın) gibi görülmesi daha doğru olur.</p>

### 8.2 Ethereum Ağı
<p> 2014 yılında Vitalik Buterin, Gavin Wood ve Jefrey Wilcke tarafından geliştirilmiş bir Blockchain platformudur. Yeni nesil Blockchain altyapısı olarak da bilinen Ethereum, akıllı sözleşme (Smart Contract) konusunda ilk tercihler arasındadır.</p>
<p> Herkesin kendi uygulamasını geliştirebildiği Ethereum platformunda Blockchain tabanlı açık kaynaklı projeler üretiliyor. Tıpkı Bitcoin platformunda olduğu gibi Ethereum’un da herhangi bir sahibi ya da bağlı bulunduğu kuruluş yoktur. Ayrıca Ethereum, Bitcoin altyapısına kıyasla esnekliği ve uyumluluğu ile ön plana çıkmaktadır. </p>
<p> Bu sunumun aslında ana konusu Ethereum Blockchain teknolojisidir. İlerleyen konularda Ethereum teknolojisini detaylı bir şekilde ele alacağız.</p>

### 8.3 HyperLedger Ağı
<p> Aralık 2015’te Linux Vakfı tarafından başlatılan açık kaynak kodlu bir Blockchain platformudur. Amaçları kısaca iş dünyasında şirket seviyesindeki işlemlerin idare edileceği Blockchain Framework’leri geliştirmek; bu işlemler için hem ticari hem de teknik yönetimler tarafından desteklenen tarafsız, açık ve tamamen topluluk odaklı altyapılar sağlamak; insanları Blockchain fırsatları konusunda eğitmek ve bu projeleri geliştirmek için teknik topluluklar kurmaktır. Yani HyperLedger adını verdiğimiz proje kesinlikle bir kripto para değildir. Hatta projenin bir yetkilisi olan Brian Behlendorf, kendisine kripto paralar hakkında sorulan bir soruya karşılık olarak gelecekte asla Hyperledger coin gibi bir proje olmayacağını açıklamıştır.</p>

### 8.4 Ripple Ağı 
<p> Özellikle uluslararası para transferi işlemlerinin gerçek zamanlı biçimde yapılmasına odaklanan Ripple platformu Swift sisteminin gerçek bir rakibi olarak görülüyor. Geleneksel metotlarla yapılan sınır ötesi para transfer işlemlerinin yavaşlığına alternatif olarak geliştirilen Ripple, Bitcoin ’de kullanılan Proof of Work (PoW) mekanizması yerine kendine ait bir mutabakat protokolü kullanıyor. Xrp token ismi ile kendi kripto para birimine sahip olmasına rağmen, farklı birimlerle transfer yapılmasına da izin veren bir altyapı sunuyor. Kurumsal projelere odaklanan Ripple platformu bankalar tarafından oldukça destek görüyor.</p>

## 9. ETHEREUM GİRİS
### 9.1 Ethereum Tarihçesi 
<p> Ethereum ilk olarak Vitalik Buterin tarafından 2013 yılının sonunda yayınlanan bir pazarlama aracı olan White Paper ile duyuruldu. Tarihler 2014 yılının Ocak ayını gösterdiğinde ise Kuzey Amerika ‘da gerçekleşen bir konferansta Vitalik tarafından Ethereum’un ne olduğu açıklandı. O zamana kadar büyür bir merakla beklenen dijital para, beklentileri karşılaşmış olacak ki kısa sürede Bitcoin ‘in rakibi olarak anılmaya başlandı.</p>
<p> Gavin Wood, 2014 Nisan ayında Yellow Paper ile teknik özellikleri ve çeşitli dokümanları yayınladı. Herkes bu süreçte Ethereum nedir diye fazlasıyla merak etmeye başladı. Daha sonra 2015 yılında Ethereum canlıya alındı.</p>
<p> “İnternetin enerji kaynağı” gibi iddialı bir çıkış yapan Ethereum, Bitcoin blok zinciri mantığından yola çıkılarak üretilmiştir. Kendine ait, özel bir yazılım dili kullanılmış ve işletim sistemi üzerinde merkezi olmayan yazılım protokolleri geliştirilmiştir.</p>
<p> Ethereum, şifreleme altyapısı olarak Bitcoin ‘den daha gelişmiş olduğu iddia ediliyor. En büyük farkı ise algoritma yapısı olarak gösteriliyor. Merkeze bağlı olmayan, şifreli ve güvenli işlemleri mümkün kılan blok zinciri teknolojisi ile geliştirilmiştir. Aynı zamanda bu ağa katılan kullanıcıların, bilgisayar donanımları sayesinde yeni Ethereum üretmesi de mümkün hale getirilmiştir.</p>

### 9.2 Ethereum Nedir? 
<p> Ethereum, açık kaynaklı (open source) merkeziyetsiz bir hesaplama platformudur. Ethereum ’u bir masaüstü ya da dizüstü bilgisayar gibi düşünebilirsiniz fakat tek bir cihaz üzerinde çalışmaz. Bunun yerine, dünyanın her yerinden binlerce makinede eş zamanlı olarak çalışır ve bu da Ethereum’un bir sahibi olmadığını gösterir.</p>
<p> Bitcoin ve diğer kripto paralar gibi Ethereum da dijital para transferi yapmanıza imkan tanır. Fakat, bundan çok daha fazlasını yapma kapasitesine sahiptir. Örneğin kendi kodunuzu yaratabilir ve diğer kullanıcıların yarattığı uygulamalarla etkileşim kurabilirsiniz. Çok esnek olduğu için her türden program Ethereum üzerinde kullanıma sunulabilir.</p>
<p> En basit haliyle Ethereum’un arkasındaki ana fikir geliştiricilerin, merkezi bir sunucu yerine dağıtılmış bir ağ üzerinde çalışan bir kod yaratabilmesi ve u kodu kullanıma sunabilmesidir. Yani teorik olarak bu uygulamalar kapatılamaz ya da sansürlenemez.</p>	
<p> Bitcoin Blockchain teknolojisinde dijital para (BTC) sahipliği izlemek için kullanılırken, Ethereum Blockchain dijital para (Ether) ağında merkeziyetsiz uygulamaların geliştirilmesi ve çalıştırılması odaklı kullanılır.</p>
<p> Ethereum Blockchain de madenciler ağı beslerler ve karşılığında Ether kazanırlar. Kullanışlı bir kripto para biriminin ötesinde Ethereum, uygulama geliştiricileri tarafından ağda işlem ücretleri ve hizmetler için ödeme yapma için de kullanılır. Madencilerin ücretlerini ödemek için kullanılan blokların ikinci bir türü vardır ve buna “Gas” adı verilir.</p>

•	Klasik İnternet Erişimi 
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147287305-cc0c5963-2182-4a9d-b928-c7dd147b08de.png"></br> Şekil 28 - Klasik internet erişimi
</p>
<p> Şuan da klasik bilgisayarları düşünün. Hepimizin elinde bilgisayar veya cep telefonu var. Çok güzeller, son modeller ve dünyanın parasını veriyoruz. Bu bilgisayarlar yine son moda olan süper güçlü bulutlara bağlanıyor.</p>
<p> Bildiğimiz gibi bulut teknolojisi sunan bazı sağlayıcılar var. (Microsoft, AWS vs.) Fakat bu bulut sistemleri aslında arka tarafta bizim en başından beri kullandığımız bilgisayarlardan oluşuyor.</p>
<p> Ben verimi gönderdiğim zaman karşı tarafa bu bulut sistemi üzerinden günün sonunda benim verilerim bu bilgisayarlarda “tırnak içinde güvenli bir şekilde” tutuluyor (Ama ne kadar güvenli?). Yani benim verilerim başka birisinin bilgisayarında ama bu büyük bir sorun değil ama nasıl bir güvenlikle saklanıyor bunu biz bilmiyoruz.</p>

•	Ethereum İnternet Erişimi 
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147287383-77fd10ae-75d6-4e44-8920-02fa36e7740c.png"></br> Şekil 29 - Ethereum internet erişimi
</p>
<p> Etheruem da yine aynı bilgisayarı kullanıyorum fakat farklı olarak ben tek bir bilgisayara bağlanmıyorum. Benim facebook.com gibi amazon.com gibi bir adresim yok. Benim aslında bir tane networküm var. Bunu ise şöyle yapıyorum bilgisayarıma bir yazılım indiriyorum. Bu yazılım open source bir ürün. Yani siz bu kodların içinde ne olduğunu biliyorsunuz. Yazılımın içinde bir arka kapı var mı buna ayrıca “Back Door” diyoruz, başka birisi bir halt karıştırıyor mu bu gibi durumları görebiliyorsunuz. Sizin bunları görmeniz için üst düzey bir bilgiye ihtiyacınız yok çünkü bunları araştıran bin bir çeşit topluluklar bulunmaktadır. Open source yazılımların artısı burada devreye giriyor. Yani Etheruem burada şeffaflık sağlıyor.</p>
<p> Bu yazılım şöyle çalışıyor. Yazılımı ilk çalıştırdığımız zaman network üzerindeki diğer bilgisayarları buluyor. Bulduğu bilgisayarda başka bilgisayarları bularak bu şekilde tüm ağa data aktarımı gerçekleşiyor. Bu ağ bu şekilde dünyanın dört bir yanına dağılmış oluyor. Ve ben online oluyorum.</p>
<p> Yani şuandaki interneti nasıl kullanıyoruz? Örneğin ben Türk Telekom üzerinden internete çıkıyorum. Daha sonra facebook.com a tıklayarak Facebook’a bağlanıyorum. Etheruem da facebook.com a bağlanmak yerine başka bir bilgisayara bağlanıyorum ve bu bilgisayarlar dünyanın her yerinde.</p>
<p> Etheruem ağında verilerimiz herkeste saklanıyor. Bilgisayarımıza bir uygulama kurduğumuz zaman bu uygulama dünyanın her yerine aynı anda kuruluyor. Ve ben bu uygulamayı çalıştırdığım zaman dünyadaki tüm bilgisayarlarda değil ama dünyadaki tüm bilgisayarların birinde çalışıyor. Ben uygulamamı kimin çalıştırdığını bilmiyorum, çalıştıran kişi de benim onu çalıştırdığımı bilmiyor. Aslında Etheruem böyle bir şey.</p>

### 9.3 Ethereum 2.0 Nedir? 
<p> Ethereum yeni finansal sistemin bel kemiği olmayı hedefliyorsa saniye başına işlem sayısı çok daha yüksek olmalıdır. Ağın dağıtılmış doğası göz önüne alındığında bu çözülmesi oldukça zor bir sorundur ve Ethereum geliştiricileri yıllardır çözüm üzerine kafa yormaktadır.</p>
<p> Öncelikle ağı yeterli seviyede merkeziyetsiz şekilde tutmak için limitlerin uygulanması gerekir. Bir node olarak çalışmanın gereklilikleri ne kadar yüksek olursa ağ da o kadar merkezi hale gelir. Yani Ethereum’un işlem kapasitesini artırması Node’ların üzerindeki yükü de artıracağından sistemin bütünlüğüne zarar verebilir. Ethereum 2.0 ile ağın hızı ve ölçeklenebilirliği daha üst seviyeye taşınacaktır.</p>
<p> Ethereum’a ve diğer Proof of Work (PoW) kripto paralara yönelik bir diğer eleştiri de son derece yüksek seviyelerde kaynak gerektiriyor olmalarıdır. Bir bloğun Blockchain‘e başarıyla eklenebilmesi için madencilik kullanılır. Fakat bloğun bu şekilde yaratılması için çok fazla elektrik tüketen hesaplamaların hızla yapılması gerekir.</p>
<p> Yukarıdaki bahsettiğimiz eksiklere yönelik genel olarak Ethereum 2.0 olarak bilinen bir grup önemli yükseltme önerilmiştir. Tam olarak uygulamaya konduğunda ETH 2.0 ile enerji tasarrufu, ağın performansını büyük oranda yükseltilmesi hedefleniyor.</p>

### 9.3.1 ETH 2.0 Staking Nedir? 
<p> Ethereum 2.0 ile gelecek en büyük yenilik, Proof of Work (İş İspatı) konsensüs algoritmasıyla çalışan ağın, Proof of Stake (Hisse İspatı) algoritmasına geçmesi olacaktır.</p>
•	Stake Etmek (Staking): Ağ katılımcısının sahip olduğu kripto parayı sisteme kilitlemesi karşılığında gelir elde ettiği modele denir.

<p> Proof of Stake Consensus algoritmasıyla çalışan Ethereum 2.0 ağına katılmak ve blok ödülü elde etmek için Ether (ETH) kilitleme işlemine “ETH 2.0 Staking” denir.
Ethereum tarafından yapılan resmi açıklamada, sisteme en az 32 ETH kilitleyen her kullanıcı Ethereum 2.0 ağında onaylayıcı (validator) olabileceğini açıkladı.</p>

### 9.4 Ethereum Sanal Makinesi (EVM)
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147287832-1e9edee8-bee4-4b97-aa8c-e2d93b9628bf.png"></br> Şekil 30 - Ethereum Sanal Makinesinin Görevi
</p>
<p> Ethereum’un oluşumundan önce, Blockchain uygulamaları çok sınırlı bir operasyonu dizayn etmek için tasarlandı. Örneğin Bitcoin ve diğer kripto para birimleri sadece eşler arası (P2P) olarak çalışmak üzere geliştirildi. Fakat geliştiriciler bir sorunla karşılaştı. Ya Bitcoin’in sunduğu işlevler dizisini ve diğer uygulama türlerini genişleteceklerdi ve bu çok karmaşık ve zaman alıcıydı, ya da yeni bir blok zincir uygulaması ve tamamen yeni bir platform geliştireceklerdi. Ethereum’un yaratıcısı Vitalik Buterin bu çıkmaza dikkat ederek, yeni bir yaklaşım geliştirdi. (EVM)</p>
<p> Ethereum’un temel yeniliği olan Ethereum Sanal Makinesi (EVM), Ethereum ağı üzerinde çalışan Turing komple bir yazılımdır. Programlama dili ne olursa olsun, yeterli zaman ve bellek verilen herkesin herhangi bir programı çalıştırmasına olanak tanır. Ethereum Sanal Makinesi, blok zinciri uygulamaları oluşturma işlemini her zamankinden çok daha kolay ve verimli hale getirir.</p>
<p> Ethereum, her yeni uygulama için tamamen orijinal bir blok zincir oluşturmak yerine, tek bir platformda binlerce farklı uygulamanın gelişimini mümkün kılar.</p>

### 9.4.1 EVM Nasıl İşler?

<p> Ağdaki her Ethereum düğümü kendi EVM uygulamasını çalıştırır ve aynı talimatları uygulayabilir.</p>
<p> Ethereum ağı programlama dili olan Solidity dili ile uygulamalı bir yaklaşım edinmek isteyen deneyimli kodlayıcılar için uygun akıllı sözleşmeler yapmak için bir geçit görevi görür. EVM kodlamak oldukça karmaşık olmakla birlikte, geliştiriciler Serpent ve Solidity’de akıllı sözleşmeler yazabilme sayesinde bunu okunabilir hale getirebilirler. Ayrıca EVM, Python, Ruby, C++ ve diğer birkaç kodlama dilinde de çalışabilir.</p>
<p> EVM, akıllı sözleşmelerin yürütülmesinde ve bakımından sorumludur. Akıllı sözleşmelerin yapıldığı yerdir. Akıllı sözleşmeleri ve algoritmayı yürüttüğü için, kullanıcıların çifte harcama yapmasını önler ve böylece işlemler yapıldıktan sonra, işlemlerin kopyaları ağdaki binlerce düğüme yayılır ve kaydedilir. Böylece çifte harcamanın esasen var olmadığından emin olur.</p>
<p> Ayrıca DDoS saldırılarından platformu korur, güvenlik duvarlarını korur, hataları ortadan kaldırır ve güvenlik önlemlerini güçlendirir.</p>

### 9.4.2 Merkezi Olmayan Uygulamalar (DApps)
<p> Merkezi olmayan uygulamaları basitçe tanımlamak gerekirse bir blok zincir ağında ya da P2P bilgisayar ağında çalışan programlardır. Başka bir söylem ile Blockchain teknolojisinden faydalanan açık kaynaklı yazılımlar, DApps olarak bilinir.</p>
<p> Dağılmış bir sistem üzerinde çalışan bir protokoldür. Merkezi platformların aksine yapılan işlemlerin hiç birisine üçüncü taraflar dahil olamamaktadır. Bu yüzden verilerinizi ele geçirerek ve internet üzerinden uygulamalara kimliksiz erişim sağlayarak veri sahipliği ve gizlilik sorunlarını çözer. Merkezi olmayan platformlarda bir aracı olmaması nedeniyle eşler arası (P2P) ağı olarak da adlandırılabilir.</p>
<p> Artık DApp’ın ne olduğunu bildiğinize göre, bir DApp’ı yargılayabileceğiniz kriterlere bakalım;</p>
1)	Açık Kaynak: Temel olarak, DApp’ler özerklik tarafından yönetilir ve tüm değişkenlere fikir birliği veya kullanıcıların çoğunluğu karar verir. Ayrıca, uygulamanın kaynak kodu herkes tarafından kullanılabilir.</br>
2)	Merkezi olmayan: Merkezileştirmenin tehlikelerinden kaçınmak için, uygulamanın operasyonunun tüm kayıtların halka açık ve merkezi olmayan bir blok zincirinde depolanması gerekir.</br>
3)	Teşvikler: Blok zinciri doğrulayıcılarının, onları kriptografi tokenlar ile ödüllendirerek teşvik etmesi gerekir.</br>
4)	Algoritma: Merkezi olmayan uygulama topluluğu, temelde değerin kanıtını göstermek için bir kriptografik algoritma üzerinde anlaşmalıdır.</br>

### 9.4.3 Akıllı Sözleşmeler (Smart Contract)
<p> Akıllı kontrat yalnızca bir koddu. Kod akıllı ya da bildiğimiz şekilde bir kontrat değildir. Fakat koda belli başlı koşullar altında kendi kendini uygulamaya koyduğu için akıllı denir ve partiler arasındaki anlaşmaların yerine getirilmesini sağladığı için de bir anlamda kontrattır.</p>
<p> Bilgisayar bilimcisi Nick Szabo bu fikri 1990’ların sonunda ortaya atmıştır. Kavramı açıklamak için bir otomat örneğini kullanmış ve otomatların modern akıllı kontratların öncülü olarak değerlendirebileceğini belirtmiştir. Otomat örneğinde uygulamakta olan basit bir kontrat söz konusudur. Kullanıcı makinaya bozuk para atar ve makine de kullanıcıya istediği ürünü verir. Bir akıllı kontrat da aynı mantığı dijital koşullarda uygular. Koda, “Bu kontrata iki Ether gönderildiğinde ‘Bitirme Projesi Ödevi’ yanıtını gönder” gibi basit bir şart girilebilir.</p>
<p> Ethereum ’da geliştirici bu girdiyi daha sonra EVM tarafından okunabilecek şekilde kodlar. Ardından bu kodu, kontratı uygulamaya koyan özel adrese göndererek yayınlar. Bu noktada kontrat herkes tarafından kullanılabilir hale gelir. Ayrıca geliştirici kodu yazarken özel bir koşul belirmediği sürece kontrat silinemez.</p>
<p> Artık sözleşmenin bir adresi vardır. Bu adresle etkileşim kurmak için kullanıcıların tek yapması gereken adrese 2 ETH göndermektir. Böylece kontratın kodu tetiklenir ve dünyanın herhangi bir yerinden bu ağa giriş yapan node üzerinden kodu çalıştırılır, kontratın ödemesinin yapıldığını görür ve çıktıyı kaydeder. (“Bitirme Projesi Ödevi”)</p>
<p> Yukarıda bahsettiğimiz işlem Ethereum ile yapabileceklerin en basit örneklerinden biridir. Birçok kontratı birbirine bağlayan daha kapsamlı uygulamalar yaratılabilir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147288508-3e68aa9a-650e-40e0-8ca3-88114f988adf.png"></br> Şekil 31 - Akıllı Sözleşmelerin bileşenleri
</p>
Akıllı Sözleşmelerin Bileşenleri;

•	Owner Address (Adres Sahibi)</br>
<p>Bir sözleşmenin sahibi dediğimiz bir kurucusu vardır. Bizim Ethereum networküne girebilmemiz için benim bir tane kendimize ait adresimizin olması gerekiyor. Bu adres tamamen bize özel. Bir banka hesabı gibi ama kendi kişisel adresimizdir.</p>

•	State (Durum)</br>
<p>Sözleşmelerin üzerinde State diye bir kavram vardır. Nedir bu State? Örneğin benim bir akıllı sözleşmem var. Diyelim ki ben bir ev sahibiyim. Ben ev sahibi olarak yani “Owner Address” bir tane ev sözleşmesi yaratıyorum. Sözleşmemi sisteme dahil ettiğim zaman o evimin adresi ayrıca sözleşmenin adresi de olmuş oluyor. Bu evime birileri kiracı olarak giriş yaptığı zaman, sözleşmemin durumunda (State) bir değişiklik yapıyorum ve evin yeni kiracısını X kişisi olacak güncelliyorum ve o X kişisinin adresini de duruma (state) yazıyorum. Çünkü o kişinin adresi üzerinden para alış verişi yapacağız. Bu şekilde her kira ödendiğinde veya yeni kiracılar geldiğinde yeni bir state oluşur.</p>
<p>Sadece ileriye dönük yeni State’ler oluşturuluyor. Geçmişe yönelik State’ler ise kesinlikle değiştirilemiyor. Eğer sözleşme yanlış hazırlanıp paylaşılmışsa bu sözleşme ağdan artık silemeyiz veya değiştiremeyiz. Bunu Ethereum sahibi bile değiştiremez. Fakat sözleşme içerisine belli bir koşul gerçekleşirse “Sözleşmeyi sil” fonksiyonunu ekleyerek sözleşmeyi silebiliriz.</p>

•	Nonce</br>
<p>Adres herhangi bir işlem gönderdiğinde artırılan bir tam sayıdır. Akıllı sözleşme yi deploy (dağıtmak) ettikten sonra nonce değeri “0” dır. Akıllı sözleşme ilk işlemi yaptıktan sonra değer 1’e yükselir. Yani sözleşmenin ne kadar işlem yaptığını bize yansıtır.</p>
<p>Sözleşmede eylemleri sırayla yapılmasın sağlar. Yani ben bir adresten başka bir adrese 2 Ether gönderiyorum ve daha onaylanmadan başka bir adrese 10 Ether gönderiyorum. Bu nonce değeri sayesinde işleme ilk dahil edilen eylemi gerçekleştirir. Bir nevi eylemleri sıraya sokmayı sağlamaktadır.</p>
•	Amount</br>
<p> Bir kontrat kendi içinde para tutabilir. Amount, sözleşmenin üzerinde sahip olunan paranın miktarını gösterir. Yani benim 100 Ether’im var diyelim. Ben bir kontrata 50 Ether gönderebiliyorum ve o kontratta güvenli bir şekilde durabiliyor kimse o parayı çalamıyor. Tabi eğer bunun için kontratın içerisine kod yazılmazsa.</p>

### 9.4.4 ERC20 – ERC721 Token Protokolleri
•	ERC20 Protokolü</br>
<p> Bitcoin (BTC), Cardano (ADA), Polkadot (DOT) gibi bağımsız kripto para birimlerinin kendi Blockchain ağları bulunurken, ERC-20 standardını benimseyen Token’ların kendilerine özel zincirleri yoktur; daima Ethereum Blockchain ağı üzerinden çalışırlar.</p>
<p> ERC-20 Token’larına ait transfer işlemleri, muhasebe defteri mantığı ile tutulmaz. Bu tokenlar, Ethereum Blockchain ağı üzerinde çalışan akıllı sözleşmelerde geçerler. Yani kullanıcılar, sahip oldukları ERC-20 standardına sahip Token’ları başka bir kullanıcıya göndermek istediklerinde, bu işlem talebini içeren kod satırı, akıllı sözleşmedeki diğer işlemlerin arasına eklenir.</p>
<p> Örneğin ERC20 protokolü ile yazılmış KSK adında bir token olsun. 1 KVK token ile başka bir 1 KVK token arasında hiçbir fark bulunmaktadır.</p>
•	ERC721 Protokolü</br>
<p> ERC-721, Ethereum Blockchain’i üzerinde eşsiz Token’ların nasıl yaratılacağını açıklayan bir standarttır. ERC-20 standardı ile oluşturulan Token’ların aksine ERC-721 ile oluşturulan Token’ların her biri eşsizdir.</p>
<p> Birbirinden farklı olan bu Token’lar aynı zamanda birbiri ile aynı değere de sahip değildir. Bu token tiplerini sanat eserleri olarak değerlendirebiliriz. Hiçbir sanat eseri, tablo ya da müzik tamamen birbiri ile aynı olamayacağı gibi bu Token’lar de birbirinden farklıdır. Bu sebeple takası ve değişimi ERC-20 Token’ları gibi gerçekleşmemektedir.</p>

### 9.4.5 Ethereum Hesap Türleri
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147288805-d01cc197-7abc-4670-b7d6-3f259e0e0c8b.png"></br> Şekil 32 - Ethereum Hesap Türleri-1
</p>
<p> Ethereum da iki tip hesap bulunmaktadır. Bitcoin de ve birçok kripto sistemlerinde ise bir tane hesap çeşidi vardır. Bu da sadece kullanıcı hesabıdır. Yani siz sistem içerisinde bir node olduğunuz zaman, cüzdan oluşturduğunuz zaman sizin için bir hesap (address) oluşturulur. Siz sadece sistem içerisinde, size benzeyen kişiler üzerinde işlemler yapabilirsiniz.</p>
<p> Ethereum da ise bu kişilere bağımlı olan hesaplar “Externally owned accounts (Dışarıdan sahip olunan hesaplar)” olarak geçmektedir. Buna ikinci olarak Ethereum‘un getirdiği çözüm ise kontratlardır. Kontratlar da bir hesap gibi davranırlar.</p>
<p> Bu ne anlama gelir?</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147288845-1acd2c43-1d2f-4880-ad7f-e7d86299c3da.png"></br> Şekil 33 - Ethereum Hesap Türleri-2
</p>
<p> Normalde Transaction’lar daha önce Bitcoin de gördüğümüz gibi neydi A kişisi B kişisine 10 BTC gönderebilmiştir. Burada ise bu Transaction işlemlerini biraz daha genişletebiliyoruz.</p>

•	Hesaptan hesaba Transaction gönderebiliyor.</br>
•	Hesaptan bir Kontrat adresine Transaction’u gönderebiliyor.</br>
•	Kontratlar kendi aralarında Transaction gerçekleştirebiliyorlar.</br>
•	Kontratlar kişilere para gönderebiliyorlar. Kontrat üzerinde birikmiş bir parayı siz bir kişiye gönderen farklı Transaction’lar yaratabiliyorsunuz.</br>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147288940-d605dea3-eba2-48f8-9cc5-6de754a5946f.png"></br> Şekil 34 - Hesaptan Hesaba Örnek
</p>
<p> Şekil 34’de Örnek uygulamada hesaptan hesaba Transaction bilgilerini görebiliyoruz. From: yazan yerde gönderen kişinin adresi, To yazan yerde ise gönderilen kişinin adres bilgisi yazmaktadır. Value: gönderilen (7.5) Ether bilgisini verir.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147289071-e39af18e-961b-49fb-8d75-ec66cae90a2c.png"></br> Şekil 35 - Hesaptan Kontrata Örnek
</p>
<p>Şekil 35’de ise hesaptan kontrata Transaction işleminin örnek dokümanını görebiliyoruz.</p>

### 9.4.6 MetaMask Cüzdanı Nedir?
<p> MetaMask, Ethereum tabanlı her tür token destekleyen (örneğin ERC-20 standartlarını kullananları ya da eşsiz tokenları) açık kaynaklı bir Ethereum cüzdanıdır. Buna ek olarak, başka kişilerden token alabilir ya da dahili Coinbase ve ShapeShift entegrasyonlarıyla token satın alabilir/takas edebilirsiniz.</p>
<p> MetaMask'ı bu kadar ilginç kılan unsur web siteleriyle ara yüz kurabilmesidir. Diğer cüzdanlarla ödeme adreslerini kopyalayıp yapıştırmanız ya da bir QR kodu farklı bir cihazda taratmanız gerekir. MetaMask uzantısıyla ise, web sitesi cüzdanınıza bir ping atar ve size işlemi kabul etme ya da etmeme seçeneği sunulur.</p>
<p> MetaMask, standart bir kripto cüzdanı olarak hizmet edebilir ama gerçek gücü akıllı kontratlarla ve merkeziyetsiz uygulamalarla sorunsuz bir şekilde ara yüz kurabilmesidir.</p>

### 9.4.7 Solidity Nedir?
<p>Solidity, EVM üzerinde çalışan akıllı sözleşmeler tasarlamak ve sözleşmeleri geliştirmeye yönelik statik (değişkenlerin önceden belli olduğu programlama dilleri. Java, c# vs) bir yapıya sahip nesne yönelimli programlama dilidir.</p>
<p>Çeşitli blok zinciri platformlarında kullanılır. Bu platformlardan en popülerinden birisi Ethereum blok zinciridir. Yazılış bakımından genelde JavaScript’e benzetilmektedir.</p>
<p>Tarihçesinden kısaca bahsetmek istersek, ilk kez 2014 yılında Gavin Wood tarafından önerilmiştir. Daha sonra Ethereum projesi bünyesindeki Christian Reitwiessner yönetimindeki Solidity ekibi tarafından tarafından yönetildi.</p>
<p>Solidity açık kaynaklı yazılım olup kaynak kodları Ethereum Solidity’nin GitHub adresinde bulunmaktadır. Solidity dokümanlarını inceleyebilirsiniz. Solidity geliştirmek için web üzerinden Remixi de veya EthFiddle platformlarından çalışabilirsiniz, onun dışında VisualCode, Atom, Intelliji gibi platformlar içinde Solidity eklentileri mevcuttur.</p>
<p>İlerleyen bölümlerde Solidity ile daha detaylı ilerleyip projeler yazacağız.</p>

### 9.4.8 Ethereum İşlem Ücreti (GAS Fee)
<p> EVM aracılığı ile Ethereum ağında yazdığımız program kişinin yalnızca kendi kişisel bilgisayarında çalıştırılmaz, Ethereum ekosistemindeki herkesten de programı çalıştırması istenir.</p>
<p> Bu durumda şu soru ortaya çıkar: on binlerce kişi sofistike kontratları çalıştırdığında ne olur? Eğer bir kişi kontratını aynı kodu tekrar edecek şekilde düzenlerse her bir Node 'un bunu sonsuz kez çalıştırması gerekir. Bu durum kaynaklar üzerinde büyük bir yük yaratır ve muhtemelen en nihayetinde sistem çöker.</p>
<p> Ethereum bu riski ortadan kaldırmak için GAS kavramını ortaya sürmüştür. Arabanızın benzin olmadan çalışamaması gibi kontratlar da GAS olmadan uygulamaya konamaz. Kullanıcıların kontratları başarıyla çalıştırabilmesi için belirli bir GAS ödemesi yapması gerekir. Eğer yeteri kadar GAS yoksa, kontrat çalışmayı bırakır.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147289462-899edc6b-a6b9-40bd-bf41-756766555197.png"></br> Şekil 36 - GAS Örneği -1
</p>
<p>Şekil 36’deki örnekte, registerToEvent() fonksiyonunda bir takım kodlar çalışmaktadır. Bu örnekteki Gas değerleri gerçeğini yansıtmamaktadır. EVM tarafından geliştirilen sistem size aslında şunu diyor; Çalıştırılmaya çalışılan bir kod içerisinde her yaptığınız bir işin bedeli vardır. Bu bedeli siz en baştan ortaya koymak zorundasınız.</p>
<p>Bu nedir? Diyor ki bir “for” döngüsü çalıştıracaksan bana 5 TL, “if” sorgusu çalıştıracaksan 3 TL, ya da “while” çalıştıracaksan ne yapacağın belli olmaz bunun fiyatı 10 TL gibi her iş belli bir ücrete tabi tutulmuştur. Bu ücretler daha önceden belirlenmiş değerler çerçevesinde uygulanır.</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/82549640/147289545-dab2becb-815d-470f-b4fd-cd9cb29a1ba3.png"></br> Şekil 37 - GAS Örneği -2
</p>
<p>Burada kırmızı alanda gördüğümüz değerler aslında siz daha Transaction yaratırken koyduğunuz paradır. Madenciler sizin bu kodunuz üzerinde çalışmaya başladığında yani kontratınızı deploy edip Etheruem ağına dağıttınız da bu Gas ücreti sizden çekilir.</p>

### 9.5 Ethereum ve Bitcoin Arasındaki Farklar
<p> Kripto para yatırımcıların en çok yatırım yaptığı ve teknolojileriyle finans dünyasını şekillendiren Bitcoin ve Ethereum arasındaki farklar nelerdir inceleyelim.</p>

•Konsept</br>
1) Bitcoin bir ödeme sistemi iken, Ethereum aslında bir bilgisayardır.</br>
2) Bitcoin, taraflar arası para (BTC) transferini Blockchain üzerinden güvenli bir şekilde gerçekleşmesini sağlar. Ethereum, taraflar arası para (ETH) ve veri transferini mümkün kılarken aynı zamanda geliştirdiği akıllı kontrat teknolojisi sayesinde iki taraf arasında öncesinden belirlenmiş şartlar sağlandığında transfer yapılmasını sağlar.</br>
3) İki kripto para arasında temek fark, Ethereum’un programlanabilir olmasıdır. Blockchain teknolojisi, üretilen paradan/bilgiden daha fazlasını gerektirir. Bitcoin’in yazılımsal tabanı değişikliklerin uygulanması için çok yavaş kalır. Birçok yatırımcı ilk kripto para birimi imajı yüzünden Bitcoin’e yönelmiştir.</br>

•	Madencilik</br>
1)	Bitcoin de yapıla transferler madenciler tarafından “Proof of Work” yani işlem kanıtı ile onaylanmaktadır.</br>
2)	Ethereum da aynı yöntemi kullanmaktadır fakat uzun süredir geliştirilen Ethereum 2.0 ile “Proof of Stake” yani hisse kanıtı sistemine geçecektir. Bu sayede bir taraf elinde bulundurduğu kripto para miktarı kadar işlemi onaylayabilecektir.</br>

•	Ödülleri</br>
1)	Bitcoin her bir blok sonunda madencileri 6.25 Bitcoin ile ödüllendirir. Bu ödül her 210.000 blokta bir, yaklaşık 4 senede bir yarılanmaktadır. Bu yarılanma işlemine “Halving” denilmektedir.</br>
2)	Ethereum da madenciler ya da Ethereum 2.0 ile işlemi onaylayanlar her blok için 3 Ether ödül alır. Bitcoin de olduğu gibi blok sonrasında ödül yarılanmaz.</br>

•	Arz Miktarları</br>
1)	Şu anda yaklaşık 18.5 Milyon adet Bitcoin dolaşımdadır. Toplam oluşturulabilecek Bitcoin miktarı ise 21 Milyon adet ile sınırlıdır.</br>
2)	Ethereum yaklaşık 111 Milyon adeti piyasadadır. Belirlenen arz sınırı yoktur.</br>

•	Transfer Ücretleri</br>
1)	Gönderim için ödenen ücret, Bitcoin için gönderen kişinin kararına bırakılmıştır. Bir işlemin çok daha hızlı gerçekleşmesini isteyen taraf gönderim ücretini artırarak işlemi onaylayacak olan madencilerin dikkatini kolaylıkla çekebilir.</br>
2)	Ethereum da “Gas” ücreti olarak da bilinen sabit ücretler ile gönderimler gerçekleşmektedir.</br>

•	Blok Oluşturma</br>
1)	Bitcoin de Blockchain’e bir blok eklemek 10 dakika sürmektedir.</br>
2)	Ethereum için blok oluşturma süresi 10-15 saniye arasında gerçekleşmektedir.</br>

### 9.6 Ethereum, Bitcoin ’e Rakip Olabilir mi?

<p> Bitcoin kripto piyasasında en çok işlem gören para birimidir. Kısa b,r süre içerisinde Ethereum’a gösterilen değerin ve ilginin artma sebebi, Bitcoin blok zincirinden daha yenilikçi olması olabilir. Bu durum Ethereum Bitcoin’e rakip olabilir mi? Sorusunu akıllara getirmiştir. Ethereum kurucusu Vitalik Buterin ise bu konuda şöyle ifadeler kullanmıştır:</p>
<p> “Eğer kripto paralar ile dünyada bulunan değerli kaynakları karşılaştırıyorsak ve Bitcoin’i Altın, Litecoin’i Gümüş olarak kabul ediyorsak, Ethereum Petrol’dür. Çünkü Ethereum’un altında yatan teknoloji dünyanın internet sistemindeki enerji kaynağı olacaktır. Dünyada petrol nasıl birçok sektör ve teknolojide kullanılıyorsa Ethereum teknolojisi için de aynı şey geçerlidir. Bu nedenle biz Ether’i “kripto yakıt” olarak adlandırıyoruz. Ethereum platformunun ihtiyaç duyduğu enerji Ether (ETH) ile sağlanacak”.</p>
<p> Vitalik’in açıklamalarına göre Ethereum’un Bitcoin ile rakip olmak gibi bir amacı olmadığını görmekteyiz. Ethereum kurucu ekibin Bitcoin çıktığı ilk dönemlerden itibaren Blockchain ve Bitcoin geliştiricileri arasında yer almaktadır.</p>
