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

  KULLANDIĞIM KOMUTLAR

-Git init; Proje oluşumunda kullandım.
-Git add; Staging sürecine eklemek için kullandım.
-Git commit; Yerel repo'ya kesin olduğum updateler için kullandım.
-Git push; Remote repo'ya yerelde yaptığım değişiklikleri gönderirken kullandım.
-Git remote; İstediğim remote repo ile yerel repomu bağdaştırırken kullandım.
-Git checkout; Branchler arasında geçiş yapabilmek için kullandım.
-Gİt branch; Yeni branch oluşturmak ve eski branchlerimi silmek için kullandım.
-Git merge; Bir branch'te yaptığım değişiklikleri ana branch ile birleştirirken kullandım.
-Git rebase; Kullanmadım ama öğrendiğime göre;

MASTER BRANCH------------------------------->Feature branch----> FINAL PRODUCT
                                             |           |
                                             |           |
                                             |           |
                                             |           |
                                             |           |
                                             |           |
                                          FEATURE    FEATURE

Yani tekrardan MASTER branch'e geçmek yerine Feature branch üzerinden devam edip onu temel almak.


Bu branch ve diğer branch'teki her şey git komutları ile yüklendi. Sadece son güncellemeler (readme'ye) Github üzerinden yapılmakta.

gitignore: normal github desktop app kullandığım da öğrendim; gitignore ile olan dosyaları umursama diğerlerini yükle demektir. Gitignore'lu dosyalar git tarafından umursanmaz iken diğer dosyalar git tarafından farkedilir.


MARKDOWN ÖĞRENDİM AMA BUNU NORMAL OLARAK YAZDIM MARKDOWN (extension) KULLANMADIM.


--BRANCHLER--

Feature kullandım sonra sildim local içerisinde.
Development, master/main/production olaylarını öğrendim.

Branchler biz (developerlar) ve müşterilere sunulan kısımların farkı gibi büyük işleri üstlenir

**TÜRKÇE**

Misal: Ben bir site yapıyorum

Anasayfam var, değiştirmek istediğim kısmım anasayfamda slider kısmı

slider'a erişir. Değişikliğimi yapar, Ardından Anasayfama bu güncellemeyi atarım.

Ben bunu development'ta yaptım bir site yapıyorum neticede. Tabi genelde production'a direct push atmak kötüdür ilk development'a copy oluşturulur oradan her şey ayarlanır sonra merge yapılır. BÖylece müşteri fix'te sorun çıksa bile tanık olmaz son ürüne tanık olur.

-------------------

Ama sitem çoktan yayında olsaydı. Bunu production'da yapmam gerekebilirdi.

**BRANCH'ÇE**

Development branch ---> Anasayfa branch --> Feature branch

Feature branch and Anasayfa branch merged.

$ -d feature branch

$ git push --all

--------------------

$ git merge production development


Pull ise basitçe benim başka branch'ten başka branch'e işlem yapmam, entegre etme.

burada yaptığım değişikliği local'de buradan local'e çekmiştim.
