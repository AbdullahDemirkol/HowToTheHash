# HowToTheHash
Hashleme nasıl yapılır?

ls komutu ile önce uygulamalar listelenir.<br/>
![ls-Komutu](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/LsCommend.png)

get-Filehash .\uygulamaadi.uzantisi /SHA256 türünde hashleme yapar.<br/>
![Get-FileHashCommendDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/GetFileHashCommendDefault.png)

get-Filehash -A Sha1 .\uygulamaadi.uzantisi /-A dan sonra istenilen hashleme türü yazılır.<br/>
![Get-FileHashCommendNotDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/GetFileHashCommendNotDefault.png)

certutil -hashfile c:\uygulamaadi.uzantisi SHA256 /SHA256 türünde hash değerini verir.SHA256 değerini değiştirerek istediğimiz şifreleme yöntemindeki hash değerini alabiliriz.<br/>
![CertutilCommend](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/CertutilCommend.png)

SHA1,SHA256,SHA384,SHA512,MACTripleDES,MD5,RIPEMD160 Şifreleme türleri.
