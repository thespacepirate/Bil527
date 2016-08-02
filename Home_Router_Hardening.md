**TOBB EKONOMİ VE TEKNOLOJİ ÜNİVERSİTESİ**

**BİLGİ GÜVENLİĞİ**

**BİL 527 – AĞ SAVUNMA SİSTEMLERİ**

**HOME ROUTER/ADSL SIKILAŞTIRMA KILAVUZU**

(Huawei HG253s Modeli Alınarak Hazırlanmıştır)

Muhammet Şakir ŞAHKULUBEY

151111050

**İÇİNDEKİLER** 2

**GİRİŞ** 3

**BÖLÜM 1 **

**YÖNLENDİRİCİ SIKILAŞTIRMA**

Adım 1: Varsayılan Olarak Gelen Şifreleri Değiştirin 4

Adım 2: Firewall Ayarlarını Etkinleştirin 5

Adım 3: UPnP'yi Devredışı Bırakın 5

Adım 4: Cihazınızın Firmware Versiyonunun Güncel olduğundan Emin olun 6

Adım 5: DHCP Havuzunu Daraltın 7

Adım 6: Mümkün İse Log Kayıtlarını Tutun 7

**BÖLÜM 2**

**KABLOSUZ AĞ SIKILAŞTIRMA**

Adım 1: Varsayılan Olarak Gelen SSID'nizi Değiştirin 9

Adım 2: Güçlü Bir Kablosuz Ağ Şifresi Seçin 9

Adım 3: SSID'nizi Gizleyin 9

Adım 4: Şifreleme için WPA2'yi Seçin 10

Adım 5: Misafir Ağını Devre Dışı Bırakın 11

Adım 6: Mac Adres Filtrelemeyi Aktif Edin 11

Adım 7: WPS'i Devre Dışı Bırakın. Şayet Zorundaysanız, Dikkatli Kullanın
12

**KAYNAKLAR** 13

**GİRİŞ**

Günümüzde internet kullanımı oldukça yaygınlaşmış durumda. Teknoloji
ilerliyor ve gün geçtikçe ucuzlayarak yaygın hale geliyor. Çoğumuz, ADSL
teknolojisinin evlerimize kadar girmesi ile interneti rahat bir şekilde
kullanmaya başladık ve hayatımızda birçok şey değişip kolaylaşmaya
başladı.

Tabi bu kolaylıklar beraberinde güvenlik risklerini de getirdi.
Özellikle evlerimizde kullandığımız internet son kullanıcıya hizmet
verdiği için burada risk daha da yüksek. Internete bağlandığımız anda
tehdit altındayız. Ancak bu yüzden internetin nimetlerinden
faydalanmamak da mantıklı olmayacaktır.

Sanırım artık hepimiz herhangi bir cihazın veya bir bilgisayar ağının
tamamıyla güvenli olduğunu söyleyemeyeceğimizi biliyoruz. Ancak mümkün
olan en güvenli hale getirbilmek bizim elimizde. Evimizdeki yönlendirici
cihazımızda yapacağımız bir dizi değişiklik, ağımızı daha güvenli hale
getirecektir.

**BÖLÜM 1**

**YÖNLENDİRİCİ SIKILAŞTIRMA**

**Adım 1: Varsayılan Olarak Gelen Şifreleri Değiştirin**

![](media/image1.jpeg){width="6.3in" height="2.6479166666666667in"}

Yeni kurulan bir cihazda, cihazın arayüzüne bağlanmanızı sağlayacak
kullanıcı adı/şifre’yi asla varsayılan olarak bırakmamalısınız. İlk
yapmanız gereken de bu bilgileri değiştirmek olmalıdır.

Kimi cihazda “Misafir Hesabı” seçeneği de bulunuyor ki bunun da devre
dışı bırakılması tavsiye edilir.

Oluşturacağınız yönetim şifresi tabii ki kolay tahmin edilebilir
olmamalıdır. Tercihen büyük-küçük harf, rakam ve işaretlerden oluşan en
az 8 karakterli bir kombinasyon olmalıdır.

![](media/image2.jpeg){width="6.3in" height="1.5340277777777778in"}

**Adım 2: Firewall Ayarlarını Etkinleştirin**

Güvenlik duvarı fonksiyonu altı alt işleve ayrılabilir: MAC filtreleme,
IP filtreleme, URL filtreleme, Uygulama filtreleme, DOS saldırısı ve
ACL. Güvenlik duvarı seviyesi, bu altı alt işlevin ortak bir
özelliğidir. Güvenlik duvarı seviyesi ayarını değiştirirseniz, ayar altı
alt işlevin tümü için geçerli olur.

![](media/image3.jpeg){width="6.293055555555555in" height="1.975in"}

Güvenlik duvarının yedi seçeneği vardır: Devre dışı bırak, “Tümünü Bloke
et, Yüksek, Orta, Düşük, Standart ve Özel”. Güvenlik duvarı fonksiyonunu
devre dışı bırakmak için, Devre dışı bırak’ı seçebilirsiniz. Güvenlik
duvarının filtreleme derecesi Tümünü Bloke et, Yüksek, Orta ve Düşük
sırasıyla azalır. Varsayılan olarak, güvenlik duvarı seviyesi Standart
olarak ayarlanmıştır. Diğer seviye, kişiye özel bir seviyedir. Başka bir
deyişle, güvenlik duvarını gerektiği şekilde özelleştirebilirsiniz.

Size tavsiyemiz, bu ayarları kullanım şeklinize göre özelleştirmenizdir.

**Adım 3: UPnP'yi Devredışı Bırakın**

Günümüzdeki “ev tipi yönlendiriciler” artık yalnızca bir kablosuz ağ
yayını yapıp, kendisine bağlanan cihazları internete eriştirmenin
dışında, akıllı cihazları otomatik bir şekilde ağa dahil edebilmeye
yarayan çeşitli protokolleri de desteklemektedirler.

Yönlendiriciniz tarafından desteklenen UPnP (Universal Plug and Play),
DLNA (Digital Living Network Alliance) gibi protokoller genellikle
kullanılmamalarına rağmen varsayılan olarak aktif durumda olabiliyorlar.

Önerimiz, kullanmadığınız her özelliği devre dışı bırakmanız.

Bu çerçevede riskleri minimize etmek adına UPnP özelliğini devre dışı
bırakıyoruz. İhtiyacımız olduğunda aktif hale getirmek zor bir işlem
olmayacaktır.

![](media/image5.jpeg){width="6.3in" height="1.9694444444444446in"}

**Adım 4: Cihazınızın Firmware Versiyonunun Güncel Olduğundan Emin
Olun**

Bize göre birçok kullanıcı bu noktayı gözardı ediyor. Yönlendirici
üreticileri, ürünleri için periyodik aralıklarla geliştirdikleri en son
firmware versiyonunu kendi web sitelerine yüklerler. Bazen bu
güncellemeler, önemli güvenlik açıkları için yamalar içerirler. Bu
sebeple güncel firmware kullanmak hayati öneme sahip olabiliyor.

![](media/image6.jpeg){width="6.3in" height="1.573611111111111in"}

Gün geçtikçe yenilenen cihazlarda güncelleme işlemi daha da kolay hale
geliyor.

Öyle ki kimi cihazda yeni bir firmware versiyonu yayınlanmışsa size
bilgi veriyor. Hatta kimisinde işlemi yapmak için yönetim arayüzünden
ayrılmanıza dahi gerek kalmıyor.

Aynı sebeple kullanıcılardaki ağ adaptörlerinin (wireless veya ethernet)
de driver'lerının güncel tutulmasında büyük fayda var.

**Adım 5: DHCP Havuzunu Daraltın**

DHCP (Dynamic Host Configuration Protocol), yönlendiriciye
bağlandığınızda otomatik IP almanıza yarayan protokoldür. Genellikle
cihazınızda varsayılan olarak aktif haldedir.

Cihaz tarafından IP dağıtılırken, önceden belirlenmiş bir havuzdan
sırası ile IP adresleri kiralanır.

Evinizde yönlendiriciye bağlanan beş adet cihaz varsa, bu havuzda 150
adet ip olması gereksizdir. Örnek olarak da kablosuz ağ şifreniz
istemediğiniz kişilerin eline geçerse, birçok kişi aynı anda otomatik ip
alarak ağınıza dahil olma şansına sahip olacaktır.

Bu gibi sebeplerden ötürü havuzu ihtiyaca uygun genişlikte tutmak, sizin
için faydalı olacaktır.

![](media/image7.jpeg){width="6.3in" height="3.376388888888889in"}

**Adım 6: Mümkün İse Logları Biryerde Tutun**

Ev kullanıcılarının yapacağı birşey gibi gözükmese de kayıtları biryerde
saklamak işinize yarayabilir. Bu kayıtlar çeşitli bilgiler içerebilir.

Birilerinin ağınıza sızmaya çalışıp çalışmadığını veya bilginiz
haricinde birilerinin yönlendiriciye erişip erişmediğini anlamanıza
yardımcı olabilir.

![](media/image8.jpeg){width="6.3in" height="1.636111111111111in"}

Eğer kablosuz ağ kullanıyorsanız işimiz bitmedi. Kablosuz ağınızı daha
güvenli hale getirmek için bir takım ekstra sıkılaştırmalar
yapmalısınız. Birkaç adımda anlatalım:

**BÖLÜM 2**

**KABLOSUZ AĞ SIKILAŞTIRMA**

**Adım 1: Varsayılan Olarak Gelen SSID'nizi Değiştirin**

Herhangi biryerdeki kablosuz ağların isimlerine dikkat ettiğinizde, bazı
yayınlarının isminin “NETGEAR095” veya “Superonline-Huawei-HG253” gibi
isimler onduğunu göreceksiniz.

Bu sizin için pek birşey ifade etmeyebilir. Ancak kötü niyetli biri için
bu böyle olmayabilir.

Bu tarz kablosuz ağ isimleri, bu ağların henüz ayarlamalarının tam
yapılmadığı ve birçok ayarın fabrika ayarları ile aynı olduğu anlamına
gelebilir. Bu durumda internetten yapılacak küçük bir arama sonrası
yönlendiricinin varsayılan olarak gelen bilgilerini elde etmek hiç de
zor değildir. Bu da sizi daha çok risk altında bırakacaktır.

Sonuç olarak SSID'nizi cihazın modelini içermeyecek şekilde seçmeniz
yararınıza olacaktır.

**Adım 2: Güçlü Bir Kablosuz Ağ Şifresi Seçin**

Kablosuz ağınızın birçok delme girişimine mağruz kalabileceğini
unutmayın.

Verecğiniz şifre kolay tahmin edilebilir olmamalıdır. Tercihen
büyük-küçük harf, rakam ve işaretlerden oluşan en az 8 karakterli bir
kombinasyon olması tavsiye edilir.

**Adım 3: SSID'nizi Gizleyin**

SSID gizlemek, kablosuz ağ adınızın yayınlanmaması olarak da ifade
edilebilir. Aslında bakılırsa SSID'nizi gizlemenin kendisi, bir güvenlik
önlemi sayılmaz.

Ağ yayını yapılan bölgede, belli araçlar ile SSID'niz siz yayın
yapmasanız da tespit edilebilir.

Ancak bununla birlikte, ağ adınızı tespit edemeyecek diğer parazitlerin
ağınıza sızmaya çalışmasını engellemek için faydalı bir yol olabilir.

Bu işlemin sıkıcı tarafı ise kablosuz ağa ilk bağlandığınızda SSID'nizi
elle girmenizin gerekmesi.

![](media/image9.jpeg){width="6.3in" height="2.741337489063867in"}

**Adım 4: Şifreleme İçin WPA2'yi Seçin**

Şifreleme metodu olarak WPA2 harici bir şifreleme metodu seçmek,
kablosuz ağınızın güvenliği açısından yapabileceğiniz en büyük hata
olabilir. Bu seçim hayati anlam taşır.

WPA2 şifrelemesi ağınıza izinsiz girilmesini çok zor hale getirir.

Tüm modern kablosuz yönlendiricilerr ve kablosuz kullanıcıların tamamı
bu metodu destekler.

Tavsiyemiz, şifreleme metodu olarak kesinlikle WPA2 kullanılmasıdır.

![](media/image10.jpeg){width="6.3in" height="2.741337489063867in"}

**Adım 5: Misafir Ağını Devre Dışı Bırakın**

Yönlendiricimizde bu özellik mevcut değil, ancak farklı modellerde bu
özellik bulunmaktadır.

Misafir ağı, genel olarak başkalarının yönlendiricinize (genellikle)
güvensiz bir şekilde erişimini sağlar. Belli başlı birtakım ayarlamalar
ile daha güvenli hale de getirilebilir.

Ancak ağınızın güvenliğe önem veriyorsanız, tavsiyemiz misafir ağının
kullanılmaması yönünde.

![](media/image11.jpeg){width="4.59375in" height="3.099971566054243in"}

**Adım 6: Mac Adres Filtrelemeyi Aktif Edin**

Mac adres filtresi oluşturmak, hangi cihazların ağa alınacağına veya
hangi cihazların erişiminin reddedileceğine karar verebilmenize olanak
sağlar.

İki yöntemle filtre oluşturulabilir: Birincisi “Kara Liste” yöntemidir.
Bu yöntem ile hangi mac adreslerine sahip cihazların erişiminin
engelleneceğini gösteren bir liste oluşturulur.

İkinci Yöntem ise “Beyaz Liste” yöntemidir. Bu yöntem ile de hangi mac
adreslerine sahip cihazların erişimine izin verileceğini belirten bir
liste oluşturulur.

Daha güvenli olan ve önerilen yöntem “Beyaz Liste” yöntemidir.
Engellemek istediğiniz tüm cihazları bilemeyebilirsiniz ancak erişim
yetkisine sahip olmasını isteyeceğiniz cihazların sayısı engellemek
istediklerinize oranla çok daha az olacaktır.

Filtre oluşturmak için öncelikle filtreye dahil edeceğiniz cihazların
MAC adreslerine sahip olmanız gerekecektir. Tabi DHCP listesinden de bu
bilgiye ulaşmanız mümkün.

![](media/image12.jpeg){width="6.3in" height="1.6236111111111111in"}

**Adım 7: WPS'i Devre Dışı Bırakın. Şayet Zorundaysanız Dikkatli
Kullanın**

WPS (Wi-Fi Protected Setup) şifre girmeden kablosuz ağa dahil olabilmek
için kullanılabilen bir özelliktir. Ancak beraberinde bazı güvenlik
açıklarını da getirebilmektedir.

Bazı kablosuz güçlendiriciler wps olmadan birbirleriyle bağlantı
kuramayabiliyorlar. Bunun dışındaki durumlarda wps kullanılmasını
tavsiye etmiyoruz.

![](media/image13.jpeg){width="6.3in" height="2.741337489063867in"}

**KAYNAKLAR**

www.huawei.com

support.cisco.com

[blog.kaspersky.com](https://blog.kaspersky.com)

[securitygladiators.com](https://securitygladiators.com)
