# SwiftteNesneTabanliProgramlamaKonuAnlatimi

Swift, nesne tabanlı programlama (OOP - Object-Oriented Programming) paradigmasını destekleyen bir programlama dilidir. OOP, yazılım geliştirme
sürecinde verileri ve işlevleri bir araya getiren bir tasarım yaklaşımıdır.
Swift, bu yaklaşımı kullanarak kodunuzu daha düzenli, anlaşılır ve sürdürülebilir hale getirmenize yardımcı olur. İşte Swift'te 
nesne tabanlı programlamanın temel kavramları:

Sınıflar (Classes): OOP'de, verileri ve bu verileri işleyen işlevleri bir araya getiren bir veri yapısı olan sınıflar bulunur.
Swift'te sınıflar, özellikle nesne oluşturmak ve bu nesneler üzerinde işlemler yapmak için kullanılır. İşte bir sınıfın temel yapısı:

class Araba {
    var marka: String
    var model: String
    
    init(marka: String, model: String) {
        self.marka = marka
        self.model = model
    }
    
    func calistir() {
        print("\(marka) \(model) çalıştırıldı.")
    }
}

esneler (Objects): Sınıflardan türetilen örnekler nesneler olarak adlandırılır. Yukarıdaki örnekte, Araba sınıfından 
türetilen bir nesne şu şekilde oluşturulabilir:

let araba1 = Araba(marka: "Toyota", model: "Corolla")


Özellikler (Properties): Sınıflar, nesnelerin özelliklerini (veya niteliklerini) temsil etmek için değişkenler veya sabitler içerebilir.
Örneğin, yukarıdaki Araba sınıfında marka ve model özelliklerini gördük.
Metodlar (Methods): Sınıflar, nesneler üzerinde işlemler yapmak için fonksiyonlar veya metotlar içerebilir. 
Örneğin, Araba sınıfındaki calistir fonksiyonu bir metod örneğidir.
Kalıtım (Inheritance): OOP'de bir sınıf, başka bir sınıftan kalıtım (inheritance) alabilir, yani bir sınıfın özelliklerini 
ve metodlarını başka bir sınıf kullanabilir. Kalıtım, kodun yeniden kullanılabilirliğini artırır.

class SUV: Araba {
    var offRoadYetenegi: Bool = true
}

Polimorfizm (Polymorphism): Polimorfizm, aynı isme sahip ancak farklı davranışlara sahip metodların kullanılabilmesini sağlar. Bu, kodun daha esnek ve genişletilebilir olmasına yardımcı olur.
Soyut Sınıflar (Abstract Classes): Swift, soyut sınıfların (abstract classes) doğrudan desteklenmediği bir dil olsa da, soyut sınıf benzeri 
davranışlar elde etmek için protokoller (protocols) kullanılabilir.
Kapsülleme (Encapsulation): OOP, verileri ve metodları bir arada tutarak ve dışarıdan erişimini kontrol ederek kapsülleme 
prensibini uygular. Bu, programın daha güvenli ve bakımı kolay hale gelmesini sağlar.

Swift, nesne tabanlı programlamayı desteklerken aynı zamanda diğer programlama paradigmalarını da benimseyen çok yönlü bir dil olarak 
kullanılabilir. Bu, geliştiricilere projelerini farklı ihtiyaçlara göre tasarlamak için esneklik sağlar. OOP, büyük ve karmaşık projelerin 
daha iyi düzenlenmesine ve yönetilmesine yardımcı olabilir.



