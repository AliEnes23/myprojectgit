# öğrendiklerim

Git bir dosya ağıdır.


Nasıl çalışmasına gelince, yerelde proje(ler) oluşturulur, staging area denilen commit edilmeden önceki yerde tutulur, ardından local repo ardından remote repo'ya gönderilir.

Çalışma mantığı ise git bash ile biz kendi bilgisayarımızda istediğimiz gibi değişiklikler yapabiliriz ardından staging area'ya göndeririz (atlanabiliyor ama atlanmamalı). Sonrasında yerel repomuza gönderir oradan da remote repo'ya. 

Git bir kişinin istediği yerden projesine erişebilmesini yada birden fazla kişinin aynanda bir proje üzerinde eş zamanlı çalışabilmesine olanak sunan, dosya ağ programıdır. Branchler ile çalışan bu program

ANA DAL --> YAN DAL -------------------------------------
   |---> YAN DAL                                         |
   |--> BUG YAŞANMA DURUMUNDA ACİL FİX BRANCH'I           | --------------> ANA DAL
   \/                                                    |
  YAN DAL -----------------------------------------------


  BASİTÇE BU ŞEKİLDE ÇALIŞIR 
  
  SUNDUĞU FIRSATLARDA;

  Ana proje ister kocaman ister küçük bir şey olsun, değiştirmek istediğimiz parçayı istediğimiz gibi değiştirmemize fırsat tanır ve bunu hızlı yapar. Ben index.html dosyasını değiştirmek istiyorsam sadece onun için branch açıp orada değişikliklerimi yapabilirim, ardından merge atıp ana projeme ekleyebilirim. Bu şekilde her projede her şey yeniden yüklenmez, değiştirilmez. Zaman kazanılır.

  
