#  Java Spring Boot Introduction

### Proje Kurulumu

Projeyi öncelikle forklayın ve clone edin.
Daha sonra projeyi IntellijIDEA kullanarak açınız. README.md dosyasını dikkatli bir şekilde okuyarak istenenleri yapmaya çalışın.
Proje sayımız ilerledikçe proje yönetimimizi kolaylaştırmak adına projelerimizi belli klasör kalıplarında saklamak işimizi kolaylaştırmak adına iyi bir alışkanlıktır.
Örnek bir Lokasyon: Workintech/Sprint_1/Etud.

### Hedeflerimiz:

### Spring Boot Projesi oluşturma

 * Spring Initializr kullanarak bir Spring Boot projesi oluşturun.
 * İçerisinde ```Spring Web``` dependency eklenmeli.
 * Maven dependency management sistemini kullanarak tüm dependencyleri install edin.
 * Uygulamanızı  ```8585``` portundan ayağa kaldırın.
 * Spring devtools kullanarak uygulamanızın her değişim sonrasında kendisini restart etmesini sağlayınız.
 * Uygulamanızda ```application.properties``` dosyasına birkaç tane değer tanımlayıp, bunları ```Value``` annotation kullanarak çağırın.
 * ```AnimalController``` isimli bir sınıf oluşturunuz. Controller olarak görev yapacağından dolayı gerekli annotation ile işaretleyin.
 * Controller sınıfı içerisinde bir adet ```animals``` adında Map tanımlayın. ```Map<Integer, Animal>``` şeklinde değer almalı.
 * Amacımız CRUD işlemlerini tanımlayan endpointler yazarak bir Rest Api tanımlamak. 
 * [GET]/workintech/animal => tüm animal mapinin value değerlerini ```List``` olarak döner.
 * [GET]/workintech/animal/{id} => ilgili id deki animal mapte varsa value değerini döner.
 * [POST]/workintech/animal => ```integer id``` ve ```String name``` değerlerini alır ve animals mapine ekler.
 * [PUT]/workintech/animal/{id} => İlgili id deki map değerini ```Request Body``` içerisinden aldığı id değeri ile günceller.
 * [DELETE]/workintech/animal/{id} => İlgili id değerini mapten siler.
