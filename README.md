# Blockchain-Ethereum

İÇİNDEKİLER

#### 1. GİRİŞ	6
2. TEMEL KAVRAMLAR	7 </br>
2.1 Veri Nedir?	7</br>
2.2 Veri Tabanları	7</br>
2.3 Merkezi Olmayan Sistemler	8</br>
2.4 Hash Nedir?	9</br>
2.5 Kriptoloji Nedir?	10</br>
2.6 Peer To Peer ( Eşten Eşe - P2P ) Kavramı	10</br>
2.7 Blockchain Teknolojisinin Felsefesi	11</br>
#### 3. BLOCKCHAIN’E GİRİŞ	12
3.1 Blockchain’in Tarihçesi	12</br>
3.2 Blockchain Nedir?	13</br>
3.2.1 İşlemler (Transactions) 	14</br>
3.2.1.1 Dijital İmza	15</br>
3.2.2 Dağıtılmış Defter Sistemi	16</br>
3.2.3 Merkezi Olmayan Yapısı	17</br>
3.2.4 Düğümler (Nodes) 	 17</br>
3.2.5 Ağdaki Fikir Birliği (Consensus) 	19</br>
3.2.5.1 İş Kanıtı (Proof of Work - PoW) 	20</br>
3.2.5.2 Hisse Kanıtı (Proof of Stake - PoS) 	21</br>
3.2.6 Değişmezlik (İmmulability) 	22</br>
3.3 Blockchain Ağlarında Gizlilik	22</br>
#### 4. BLOCKCHAIN ÇEŞİTLERİ	23
4.1 Genel Blockchain Ağları	23</br>
4.2 Özel Blockchain Ağları	23</br>
4.3 İzne Tabi Blockchain Ağları 	24</br>
4.4 Konsorsiyum Blockchain Ağları 	24</br>
#### 5. Blokchain Mimarisi ve Çalışma Prensipleri	25
5.1 Blockchain Nasıl Çalışır?	25</br>
5.2 Block Yapısı	26</br>
5.3 Blockchain Cüzdanları	28</br>
5.4 Blockchain Madenciliği ( Mining)	29</br>
5.5 Çatallaşma (Fork)	30</br>
5.6 En Uzun Blockchain Kaydı	32</br>
#### 6. BLOCKCHAIN AĞLARINDA ŞİFRELEME	32
6.1 Güvenli Şifreleme ( Secure Hash)	32</br>
6.2 Merkle Ağaç Yapısı ( Merkle Tree)	33</br>
6.3 Simetrik Şifreleme ( Symmetric Encryption)	34</br>
6.4 Asimetrik Şifreleme (Asymmetric Encryption)	34</br>
#### 7. BLOCKCHAIN UYGULAMALARINDA RİSKLER	34
7.1 Özel Anahtarların Saklanması	34</br>
7.2 Enerji Tüketimi	35</br>
7.3 Sınırlı Teşvik	36</br>
7.4 Yazılım Hataları, Açıklar ve Siber Saldırılar	36</br>
7.5 Şifreleme ve Kuantum Bilgisayarlar	36</br>
7.6 Çatallaşma (Fork) Problemi	37</br>
#### 8. BLOCKCHAIN PLATFORMLARI	37
8.1 Bitcoin Ağı	38</br>
8.2 Ethereum Ağı	38</br>
8.3 HyperLedger Ağı	39</br>
8.4 Ripple Ağı 	39</br>
#### 9. ETHEREUM GİRİŞ	39
9.1 Ethereum Tarihçesi	39</br>
9.2 Ethereum Nedir?	40</br>
9.3 Ethereum 2.0 Nedir?	43</br>
9.3.1 ETH 2.0 Staking Nedir? 	43</br>
9.4 Ethereum Sanal Makinesi (EVM) 	44</br>
9.4.1 EVM Nasıl İşler	 44</br>
9.4.2 Merkezi Olmayan Uygulamalar (DApps) 	 45</br>
9.4.3 Akıllı Sözleşmeler 	46</br>
9.4.4 ERC20 – ERC721 Protokolleri	48</br>
9.4.5 Ethereum Hesap Türleri	 49</br>
9.4.6 MetaMask Cüzdanı Nedir? 	51</br>
9.4.7 Solidity Nedir? 	51</br>
9.4.8 Ethereum İşlem Ücreti (GAS Fee) 	 52</br>
9.5 Ethereum ile Bitcoin Arasındaki Farklar	53</br>
9.6 Ethereum, Bitcoin’e Rakip Olabilir Mi?	55</br>
#### 10. SOLIDITY GİRİŞ	

## 1. GİRİŞ 
Blockchain teknolojisi paranın dijitalleşme süreciyle hayatımıza daha yoğun bir şekilde girmeye başlamıştır. Global düzeyde insanların kripto paralar hususunda farkındalık kazanmasında Bitcoin’in oldukça ayrıcalıklı bir yeri bulunmaktadır ki onun arkasında da Blockchain teknolojisi yer almaktadır.</br>
Önümüzdeki dönemde başta finans dünyası olmak üzere birçok alanda büyük yenilikler ve dönüşümler yaratması beklenen blok zinciri kavramı, 2008 yılında yayınlanan Bitcoin makalesiyle ortaya çıkmıştır. Makalenin yazarı olarak görünen Satoshi Nakamoto, 2009 yılında ilk Bitcoin yazılımını geliştirerek Bitcoin sisteminin kurulmasını sağlamıştır. Nakamoto, 2010 yılı ortalarına kadar Bitcoin ekosisteminin gelişmesini desteklemiş ve ardından projeden desteğini çekerek ortadan kaybolmuştur.</br>
Dünya çok yakın bir tarihte büyük bankaların battığı, ülkelerin finansal anlamda kötü duruma düştüğü bir kriz yaşamıştır. Küresel sistemde yaşanan son finans ve bankacılık krizlerinin toplumun güven duygusunu zedelemesi ile birlikte paranın temeli hakkında sorular gündeme gelmiştir. Bankacılık sektörüne olan güven duygusu sistemin işlemesi için gerekli olan temel yapı taşıdır. Günümüzde öznel bir değeri bulunmayan kağıt parayı kıymetli ve güvenli kılan unsur arkasındaki devlet otoritesi iken elektronik parayı güvenli kılan faktör ise finansal regülasyondur. Son yıllarda popülerliği artan kripto paraları da benzer şekilde Blockchain teknolojisi güvenli kılmaktadır.</br>
## 2. TEMEL KAVRAMLAR
### 2.1 Veri Nedir? 
 İngilizce dilinde karşımıza çıkan ve artık günlük yaşamda da dilimizde normalleşmeye başlayan “data” kelimesinin Türkçe karşılığıdır. İşlenmemiş, hem bilgi parçacığına verilen isimdir.</br>
Veriler; ölçüm, sayım, deney, gözlem ya da araştırma yolu ile elde edilmektedir. Ölçüm ya da sayım yolu ile toplanan ve sayısal bir değer bildiren veriler nicel veriler, sayısal bir değer bildirmeyen veriler de nitel olarak sınıflandırılmaktadır.</br>
Bir verinin tek başına bir anlamı ve işlevi bulunmaz. Veriler toplandıktan sonra gruplanarak, sıralanarak ve özetlenerek, elle ya da bilgisayarla işlenip enformasyona dönüştürüldüklerinde anlam kazanırlar. Böylece, ait oldukları unsuru açıklama gücüne kavuşur ve problem çözme ya da karar verme gibi bir amaca hizmet edebilecek duruma gelirler.</br>
### 2.2 Veri Tabanları  
 Veri tabanı, bilgisayar sisteminde depolanan yapılandırılmış bir kayıt ve veri koleksiyonudur. Bir veri tabanının gerçekten işlevsel olması için, yalnızca büyük miktarda kaydı iyi depolamakla kalmaz, aynı zamanda kolayca erişilebilir kılar. Buna ek olarak, yeni bilgi ve değişikliklerin girilmesi de oldukça kolay olmalıdır.</br>
Birçok veri tabanı çeşitleri bulunmaktadır. Bunlardan bazıları ilişkisel, Nesne Odaklı, Dağıtılmış, Bulut veri tabanları gibi daha sayabiliriz. Fakat son dönemde Bulut veri tabanları çok popüler olmuş ve çoğu küçük veya büyük firmalar tarafında da kullanımı revaçtadır. </br>
Bulut Depolama, dosyalarınızı internet üzerinde size verilen bir alanda saklamanıza verilen isimdir. Dosyalarınız internet üzerinde olduğu için internet bağlantısı olan her yerden onlara ulaşabiliyorsunuz.
![image](https://user-images.githubusercontent.com/82549640/147280288-3de829a7-f336-471b-b085-6fa35447f49b.png)











