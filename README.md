# SiNAMO
Single Integrated Network Architecture for Multiple Operating Environments

S = Single: Only one desktop environment will be allowed on the system. 
i = Integrated: All settings, configurations, and personalizations related to desktop environments will be backed up and removed in an integrated manner. 
N = Network: Relationships between desktop environment components, dm (gdm, lightdm, etc.) and other integrated packages will be considered. 
A = Architecture: The desktop environment change process will be built on a specific architecture and structure. 
M O = Multiple Operating environments: Installation of more than one desktop environment will not be allowed.

SiNAMO is Single Integration Network Architecture for Multiple Operating Environments. 

SiNAMO is Not a Multi-Desktop Manager.



TR,tr : Türkçe Çevirisi:

Birden fazla İşletim Ortamı için Tek Entegre Ağ Mimarisi
S = Single: Sistemde sadece bir masaüstü ortamına izin verilecek.
i = Integrated: Masaüstü ortamlarıyla ilgili tüm ayarlar, yapılandırmalar ve kişiselleştirmeler entegre bir şekilde yedeklenecek ve kaldırılacak.
N = Network: Masaüstü ortamı bileşenleri, dm (gdm, lightdm vb.) ve diğer entegre paketler arası ilişkiler dikkate alınacak.
A = Architecture: Masaüstü ortamı değişim süreci belirli bir mimari ve yapı üzerine inşa edilecek.
M O = Multiple Operating environments: Birden fazla masaüstü ortamının kurulmasına izin verilmeyecek.

SiNAMO, Çoklu İşletim Ortamları için Tek Entegrasyonlu Ağ Mimarisidir.

SiNAMO bir Çoklu Masaüstü Yöneticisi değildir.





# SiNAMO
Türkçe İsimlendirme:

Sade İç içe Nitelikli A***************************

SiNAMO:
S = Sistemi: Sistemde sadece bir masaüstü ortamına izin verilecek.
I = istikrarsızlaştıran: İstikrarsızlığa sebep olan mevcut yapılandırmaları ve bağımlılıkları entegre bir şekilde yedekleyip kaldıracak.
N = Nefret: Nefret ettiren şeylerden; Nefrete sebep olan, işletim sisteminden nefret etmenizi sağlayan (son kullanıcılara göre) çakışan paketler, yapılandırmalar, kişiselleştirmeler ve ayarlar arasındaki ilişkileri net bir şekilde yönetecek.
A = Arındırılan: Değişim sürecini belirli bir yapı ve mimari üzerine inşa edecek.
M = Masaüstü: Kullanıcı deneyimini artıracak şekilde optimize edilecek.
O = Ortamı: Birden fazla masaüstü ortamının sistemde bulunmasını engelleyecek. Ortamı tekleyicisi; Masaüstü Ortamını tekler, sadece tek bir masaüstü ortamına izin verir.

SiNAMO, Sistemi İstikrarsızlaştıran Nefret ettiren şeylerden Arındırılan Masaüstü Ortamı tekleyicisi

SiNAMO   *********************************** değildir.



SiNAMO Proje Açıklaması
SiNAMO projesi, GNU/Linux ve GNU/Linux Libre dağıtımlarında masaüstü ortamlarını yönetmeyi hedefleyen bir sistemdir.

Sistemi: Kullanıcıların sistemlerinde yalnızca bir masaüstü ortamı bulunmasına izin vererek, yapılandırma ve bağımlılık sorunlarını en aza indirir.
İstikrarsızlaştıran: Tüm ayarları ve yapılandırmaları entegre bir şekilde yedekleyerek, kullanıcıların mevcut ayarlarını kaybetmeden yeni bir masaüstü ortamına geçiş yapmasını sağlar.
Nefret: Masaüstü bileşenleri ve uygulamaları arasındaki ilişkiler, potansiyel çakışmaları önlemek için net bir şekilde tanımlanacak ve yönetilecektir.
Arındırılan: Değişim süreci, belirli bir yapı üzerinde gerçekleştirileceği için daha düzenli ve öngörülebilir bir geçiş sağlanacaktır.
Masaüstü: Kullanıcı deneyimini artırmak amacıyla, çalışma alanlarıyla ilgili yapılandırmalar optimize edilecektir.
Ortamı: Sistemde birden fazla masaüstü ortamının bulunmasına izin vermeyerek, karışıklıkları ortadan kaldırır.





Proje Açıklaması
SiNaMo, GNU/Linux ve GNU/Linux Libre dağıtımlarında masaüstü ortamlarının yönetimini merkezi bir sistem haline getirmeyi amaçlayan bir projedir. Bu proje, bir masaüstü ortamını kurup diğerini kaldırarak, masaüstü ortamları arasında oluşabilecek bağımlılık, çakışma ve yapılandırma problemlerini ortadan kaldırmayı hedefler.

Projenin Özellikleri:
Sistemde aynı anda sadece bir masaüstü ortamı bulunmasına izin verir.
Mevcut masaüstü ortamına ait tüm ayarları, yapılandırmaları, kişiselleştirmeleri ve ilgili paketleri yedekler.
Masaüstü ortamına bağlı tüm dm (gdm, sddm, lightdm vb.) yapılandırmalarını ve sistemdeki entegre uygulamaları yönetir.
Kaldırılamaz olarak işaretlenmiş paketleri bile kaldırarak, yeni masaüstü ortamı için temiz bir kurulum sağlar.
Masaüstü ortamları arasında oluşabilecek çakışmaları ortadan kaldırarak daha stabil bir kullanıcı deneyimi sunar.
Kullanım:
Mevcut masaüstü ortamını değiştirmek için SiNaMo komutlarıyla yeni masaüstü ortamını kurun.
Eski masaüstü ortamına dönmek isterseniz, yedeklenen ayarlar ve yapılandırmalarla sistemi eski haline döndürebilirsiniz.




github'da GNU/linux ve GNU/linux libre için yeni bir depo oluşturacğım. yapacağımız paket; dağıtımların masaüstü ortamını  (masaüstü ortamları [örneğin: lxde, xfce,enlightment,lxqt vb.] , çalışma alanları [örneğin: KDE çalışma alanı]- iş istasyonları [örneğin: Fedora İş İstasyonu]- workspaces ) , ana paket grubu olarak sadece bir grubu kuracak, sadece bir masaüstü ortamıdiğer grubu silecek şekilde sistemde sadece bir masaüstü ortamına izin verecek şekilde kurmayı sağlayacak bir paket olacak. mevcut masaüstü ortamını değiştirmek istediğinde mevcut masaüstü ortamına ait ayarlar , yapılandırmalar, kişiselleştrimeler, wayland veya x11 paketleri ve yapılandırmaları, masaüstü ortamını başlatan dm (gdm,lightdm,sddm vb) paketleri ve yapılandırmaları, masaüstü ortamıyla entegre edilmiş sistem paketleri ayarları yapılandırmaları, masaüstü ortamıyla entegre çalışan uygulamaların paketleri ayarları yapılandırmalarının tamamını yedekleyecek, ardından bu saydıklarımın tamamını , hatta kaldırılamaz paketleri (örneğin fedora için gnome-shell gibi kaldırılamaz paketleri) de kaldıracak. Ardından yeni masaüstü ortamına ait paketlerin tamamını kuracak. böylece masaüstü ortamlarının birbirleriyle olan yapılandırma, ayar, çakışan bağımlılıklar, çakışan paketlerin diğer masaüstü ortamını bozmamasını sağlayacağız. sistemde sadece bir masaüstü ortamı kurulacak, diğerine izin verilmeyecek. silinen-kaldırılan masaüstü grubunun ayarları yapılandırmaları kişiselleştirmeleri vb yedeklenecek. ki pc kullanıcısı tekrar eski masaüstü ortamına geçmek isterse herşeyi olduğu gibi eski haline geri dönülebilsin. 
