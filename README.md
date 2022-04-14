# HowToTheHash
Hashleme nasıl yapılır?

ls komutu ile önce uygulamalar listelenir.
![ls-Komutu](https://github.com/AbdullahDemirkol/HowToTheHash/blob/master/images/LsCommend.png)

get-Filehash .\uygulamaadi.uzantisi /SHA256 türünde hashleme yapar.
![Get-FileHashCommendDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/master/images/GetFileHashCommendDefault.png)

get-Filehash -A Sha1 .\uygulamaadi.uzantisi /-A dan sonra istenilen hashleme türü yazılır.
![Get-FileHashCommendNotDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/master/images/GetFileHashCommendNotDefault.png)

certutil -hashfile c:\uygulamaadi.uzantisi SHA256 /SHA256 türünde hash değerini verir.SHA256 değerini değiştirerek istediğimiz şifreleme yöntemindeki hash değerini alabiliriz.
![CertutilCommend](https://github.com/AbdullahDemirkol/HowToTheHash/blob/master/images/CertutilCommend.png)

SHA1,SHA256,SHA384,SHA512,MACTripleDES,MD5,RIPEMD160 Şifreleme türleri.