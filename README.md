# Blockchain-Ethereum
## ÖZET


   Son yıllarda kripto paralar için önemli gelişmeler yaşandı. Bu kripto paralar arasında Bitcoin piyasa büyüklüğü, ilk Blockchain ve ilk para birimi olarak bazı firmalar ve hatta ülkeler tarafından ödeme aracı olarak kabul edilmesi ile ön plana çıkmıştır.</br>
Bitcoin tamamen eşler arası çalışan bir elektronik ödeme sistemi olmuş ve ödemelerin bir finans kurumundan geçmeyerek doğrudan bir taraftan bir diğerine gönderilmesini olanak sağlamaktadır. İlk dönemde Bitcoin’in finansal özelliklerine duyulan ilgi, zaman içerisinde Bitcoin’e hayat veren Blockchain teknolojisine doğru kaymaya başlamıştır.</br>
Blockchain sayesinde insanlar artık ürün ve hizmet transferi işlemlerinde güvenlik ve doğrulamayı sağlaması için üçüncü taraf aracıya ihtiyaç duymamaktadır. Blockchain ile oluşturulan “güven protokolü” güvenilir, şeffaf ve hesap verebilir bir ortam sunmaktadır. Blockchain, kullanıcılar için merkezi olmayan dağıtık veri yapıları sayesinde güvenliğin temelini oluşturmaktadır. Bu proje kapsamında Bitcoin’in finansal kısmı değil de bir devrim niteliği olan Blockchain teknolojisi üzerinde durulacaktır.</br>
Blockchain teknolojisini daha iyi anlamamıza imkân sağlayacak kavramları ilk bölümde ele alacağız. Bu bölümün ilerleyen sayfalarında teknik detaylara girmeden Blockchain’in yapısını, çalışma mantığını, platformlarını, uygulama alanları, temelinde Blockchain teknolojisini barındıran yapıları gibi konulara değinip, ikinci bölümde ise Ethereum Blockchain ağında, Solidity programlama dili ile akıllı kontratlar yazarak, var olan bir düşünceyi kendi akıllı kontratlarımızı yazarak uygulamaya dönüştüreceğiz.</br>

İÇİNDEKİLER

1. GİRİŞ	6
2. TEMEL KAVRAMLAR	7 </br>
2.1 Veri Nedir?	7</br>
2.2 Veri Tabanları	7</br>
2.3 Merkezi Olmayan Sistemler	8</br>
2.4 Hash Nedir?	9</br>
2.5 Kriptoloji Nedir?	10</br>
2.6 Peer To Peer ( Eşten Eşe - P2P ) Kavramı	10</br>
2.7 Blockchain Teknolojisinin Felsefesi	11</br>
3. BLOCKCHAIN’E GİRİŞ	12</br>
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
4. BLOCKCHAIN ÇEŞİTLERİ	23</br>
4.1 Genel Blockchain Ağları	23</br>
4.2 Özel Blockchain Ağları	23</br>
4.3 İzne Tabi Blockchain Ağları 	24</br>
4.4 Konsorsiyum Blockchain Ağları 	24</br>
5. Blokchain Mimarisi ve Çalışma Prensipleri	25</br>
5.1 Blockchain Nasıl Çalışır?	25</br>
5.2 Block Yapısı	26</br>
5.3 Blockchain Cüzdanları	28</br>
5.4 Blockchain Madenciliği ( Mining)	29</br>
5.5 Çatallaşma (Fork)	30</br>
5.6 En Uzun Blockchain Kaydı	32</br>
6. BLOCKCHAIN AĞLARINDA ŞİFRELEME	32</br>
6.1 Güvenli Şifreleme ( Secure Hash)	32</br>
6.2 Merkle Ağaç Yapısı ( Merkle Tree)	33</br>
6.3 Simetrik Şifreleme ( Symmetric Encryption)	34</br>
6.4 Asimetrik Şifreleme (Asymmetric Encryption)	34</br>
7. BLOCKCHAIN UYGULAMALARINDA RİSKLER	34</br>
7.1 Özel Anahtarların Saklanması	34</br>
7.2 Enerji Tüketimi	35</br>
7.3 Sınırlı Teşvik	36</br>
7.4 Yazılım Hataları, Açıklar ve Siber Saldırılar	36</br>
7.5 Şifreleme ve Kuantum Bilgisayarlar	36</br>
7.6 Çatallaşma (Fork) Problemi	37</br>
8. BLOCKCHAIN PLATFORMLARI	37</br>
8.1 Bitcoin Ağı	38</br>
8.2 Ethereum Ağı	38</br>
8.3 HyperLedger Ağı	39</br>
8.4 Ripple Ağı 	39</br>
9. ETHEREUM GİRİŞ	39</br>
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
10. SOLIDITY GİRİŞ	-</br>













