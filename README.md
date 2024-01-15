Taiko Alpha-6 (A6) Katla Testnet’ine Giriş : https://medium.com/@TraderOzy/taiko-alpha-6-a6-katla-testnetine-giri%C5%9F-d9e7cbc1e2d6

Taiko’ya göre Katla şu ana kadar sahip olduğu en önemli test ağıdır.

Ne var ne yok?
İşte Katla’daki yenilikler:

Implemented Based Contestable Rollup (BCR), multi-proofs and SGX ile birlikte tasarımı.
Güncellenmiş köprü uygulaması, iyileştirilmiş köprü kullanıcı arayüzü ve yeni bir özellik: NFT köprüleme!
Blok gezgini ve durum sayfasında testnet istatistikleri güncellendi.
BCR uygulaması
Katla, Eylül 2023'te Singapur’daki TOKEN2049'da tanıttığı bir toplama tasarımı olan Based Contestable Rollup (BCR)’ yi uyguluyor. Katla ile dört katmanlı çoklu prova yapılandırmasını etkinleştiriyoruz: Aşağıda gösterildiği gibi iyimser provalar, SGX provaları, SGX+zkEVM provaları ve koruyucu provalar.


BCR ve Taiko’nun çoklu prova tasarımı hakkında daha fazla bilgi edinmek için lütfen bu blog yazısını okuyun .

Üstelik Katla’nın kodu EIP-4844'ü (proto-danksharding) destekliyor ancak bu özellik kapalı. Temel katman (Holesky) EIP-4844 ile sert çatallandığında, işlem maliyetlerini azaltmak amacıyla veri kullanılabilirliği için blobların kullanımını etkinleştirmek üzere muhtemelen bir yükseltme gerçekleştirecekler.

Sonuç olarak, Katla hâlâ tabanlı bir toplama ve Jólnir (Alpha-5) test ağında olduğu gibi tamamen aynı tokenomik tasarıma sahip bir tip-1 ZK-EVM’dir. Başka bir deyişle, uygulamanız herhangi bir değişiklik yapılmadan kutudan çıktığı gibi çalışmalıdır.

Güncellenmiş köprü
Ayrıca köprü kontratındaki birkaç hatayı da düzelttiler. Köprü uygulaması da yeniden uygulandı ve NFT token köprüleme artık etkinleştirildi. Hedef zincirdeki köprülü operasyonunuz başarısız olursa artık kaynak zincirindeki köprülü varlığınızı geri talep edebilirsiniz. Tam bir değişiklik günlüğünü burada bulabilirsiniz ve köprüye buradan ulaşılabilirsiniz.

Yukarıda ayrıntıları verilen büyük güncellemelerin yanı sıra, kullanıcılar, her zaman olduğu gibi, Taiko’da dağıtılan çeşitli dapp’leri kullanabilecek , sözleşmeleri dağıtabilecek, bir düğüm çalıştırabilecek, blok önerebilecek ve blokları kanıtlayabilecek; üstelik bunların tümünü izinsiz olarak yapabilecekler.

Güncellenmiş blok gezgini
Katla ayrıca yeni test ağı istatistiklerine sahip güncellenmiş bir blok gezginine de sahiptir.

Örneğin, artık en son canlılık bağının ne olduğunu, hangi kanıt katmanıyla kaç geçişin kanıtlandığını ve diğer istatistikleri görebilirsiniz.


Katla blok gezginini burada bulabilirsiniz.

Peki ya Jólnir (A5)?
Jólnir 31 Ocak 2024'te kullanımdan kaldırılacak.

Sıradaki ne?
Yaklaşan ana ağ lansmanımızın temelini oluşturduğu için Katla’nın şu ana kadar sahip olduğumuz en önemli test ağı olduğunu vurgulamak istiyoruz . Bu nedenle, yarışma ve SGX kanıtı oluşturma gibi yeni özellikleri kapsamlı bir şekilde test ettiğimizden emin olmamız gerekiyor.

İşte burada siz, yani topluluk devreye giriyor. Yarışma oyununa katılmaktan, node çalıştırmaya ve takas yapmaya kadar, Katla ile ne şekilde etkileşimde olursanız olun, ana ağa girdiğimizde hiçbir sürprizle karşılaşmamamızı ve her şeyin amaçlandığı gibi çalışmasını sağlamamıza yardımcı oluyor.

Yeni gelecekleri test etmemize yardımcı olduğunuz ve böylece Taiko’nun geleceğinde büyük rol oynadığınız için şimdiden teşekkür etmek istiyoruz. Taiko ≡ Topluluk . 🫶

Şimdi Testnet İçin Neler Yapabiliriz Gelin Başlayalım.
Öncelikle şuraya gidelim ve sağ üstten cüzdanımızı bağlayıp Holesky ve Katla ağlarını cüzdanımıza ekleyelim: https://bridge.katla.taiko.xyz/
Manuel olarak eklemek için: https://docs.taiko.xyz/guides/set-up-your-wallet

Şimdi sol taraftan “Faucet” kısmını seçip Holesky ağı üzerinde $HORSE tokenını mintleyelim.

Holesky ağında tokena sahip değilseniz işte sizin için “Faucet”:
holesky-faucet.pk910.de

https://bwarelabs.com/faucets/ethereum-holesky

Ardından ana sitemizde “Bridge” kısmına geri dönüp elimizde bulunan tokenları Katla ağına köprüleyelim.

Şimdi NFT köprülemesi gerçekleştireceğiz ama öncelikle bir NFT’ye sahip olmalıyız. Şuraya gidelim ve 1 tane NFT mitleyelim: https://taiko-katla-alpha-6-testnet-nft.testnet.nfts2.me/

Ardından mintlediğimiz NFT’nin üzerine tıklayalım EVM cüzdanımıza ekleyelim.

Artık cüzdanımızda gözüküyor.

NFT’imizin üzerine tıklayıp sözleşme adresini kopyalayalım.

Ana sitemize geri dönüp NFT kısmına girip sözleşmeyi yapıştıralım.



Şimdi Katla ağına geçelim ve bu gerçekleştirdiğimiz işlemlerin hepsini Katla ağı üzerinde de yapalım.
Ayrıca “Transactions” kısmında “Claim” yapmayı unutmayalım.

Okuduğunuz için teşekkürler. Şimdilik yapacaklarımız bu kadardı. Bana ufakta olsa destek sağladığınız için teşekkür ederim. Sağladığınız en ufak destek ile beraber içerik üretmeye yönelik motivasyonum artacaktır. Böylece kendi gelişimime de yardımcı olacağım. Kendinize iyi bakın. Sağlıcakla kalın.
Benimle Twitter üzerinden iletişime geçmek isterseniz: https://twitter.com/TraderOzy

Lens Protocol üzerinden iletişime geçmek isterseniz: https://hey.xyz/u/ozymandias

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Projeye ait;

Resmi Sitesi: https://taiko.xyz.

Twitter: https://twitter.com/taikoxyz.

Docs: https://docs.taiko.xyz.

GitHub: https://github.com/taikoxyz.

Discord: https://discord.gg/taikoxyz.

Community forum: https://community.taiko.xyz.

Youtube: https://www.youtube.com/@taikoxyz.
