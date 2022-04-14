## HowToTheHash(Hashleme nasıl yapılır?)

**Ls komutu ile önce uygulamalar listelenir.**<br/>
![ls-Komutu](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/LsCommend.png)

**Get-FileHash .\uygulamaadi.uzantisi /SHA256 türünde hashleme yapar.**<br/>
![Get-FileHashCommendDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/GetFileHashCommendDefault.png)

**Get-FileHash -A Sha1 .\uygulamaadi.uzantisi /-A dan sonra istenilen hashleme türü yazılır.**<br/>
![Get-FileHashCommendNotDefault](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/GetFileHashCommendNotDefault.png)

**Certutil -hashfile c:\uygulamaadi.uzantisi SHA256 /SHA256 türünde hash değerini verir.SHA256 değerini değiştirerek istediğimiz şifreleme yöntemindeki hash değerini alabiliriz.**<br/>
![CertutilCommend](https://github.com/AbdullahDemirkol/HowToTheHash/blob/main/Images/CertutilCommend.png)

## Şifreleme türleri<br/>
**SHA1**<br/>
**SHA256**<br/>
**SHA384**<br/>
**SHA512**<br/>
**MACTripleDES**<br/>
**MD5**<br/>
**RIPEMD160**<br/> 
