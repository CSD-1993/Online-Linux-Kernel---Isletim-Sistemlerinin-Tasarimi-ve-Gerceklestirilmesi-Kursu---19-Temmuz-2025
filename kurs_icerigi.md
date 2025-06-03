# Online Linux Kernel - İşletim Sistemlerinin Tasarımı ve Gerçekleştirilmesi (360 Saat)


## Giriş
+ İşletim Sistemlerinin Tarihsel Gelişimi
+ Kaynak Yöneticisi Olarak İşletim Sistemleri
+ İşletim Sistemlerinin Alt Sistemleri
+ Linux İşletim Sisteminin ve Çekirdeğinin Tarihsel Gelişimi
+ Linux'ta Dosya Sistemindeki Temel Dizinler 
+ Linux Çekirdeğinin Genel Yapısı

## Çekirdek Kodlaması İçin Hazırlık Bilgileri
+ İşlemci Ailelerine Genel Bakış
+ Intel x86-64 İşlemcilerinin Yazılım Mşimarisine İlişkin Temel Özellikler
+ 32 ve 64 Bit ARM İşlemcilerinin (AArch32 ve AArch64) Yazılım Mimarisine İlişkin Temel Özellikler
+ Intel ve ARM Sembolik Makine Dilleri (Assembly Languages) Hakkında Temel Bilgiler
+ GCC Derleyicilerinin Temel Özellikleri ve Linux Çekirdek Kodlarında Kullanılan Eklentileri
+ Flat Binary Dosyaların Oluşturulması ve objcopy Programının Kullanımı
+ Bağlayıcıların (Linker) Kullanımı 
+ İşlemcilerde Koruma Mekanizması
+ İşlemcilerin Sayfalama Mekanizması
+ Intel x86-x64 İşlemcilerinde Sayfalama Mekanizması
+ ARM İşlemcilerinde Sayfalama Mekanizması

## Çekirdek Kodlamasında Kullanılan Önemli Veri Yapıları
+ Bağlı Listeler ve Linux Çekirdeklerinde Bağlı Listelerin Gerçekleştirimi
+ Hash Tabloları ve Linux Çekirdeklerinde hash tablolarının Gerçekleştirimi
+ İkili Arama Ağaçları, AVL ve Kırmızı-Siyah Dengelemesi ve Linux Çekirdeklerindeki Gerçekleştirimleri
+ Cache Sistemlerinin Oluşturulması ve Linux Çekirdeklerinde Tabanlı Cache Sistemlerinin Gerçekleştirimi
  
## Linux Çekirdeğinde Proses Yönetimi
+ Proses Kavramı, Proses İlişkin Bilgiler, Proses Kontrol Bloğu
+ Proses Kontrol Bloklarının İçerdiği Bilgiler
+ Linuz'un task_struct Yapısının İncelenmesi
+ Linux Sistemlerinde Pross'lerin Id Değerlerinin Anlamı ve Id Değerlerinin Oluşturulması
+ Linux Çekirdeğinde Proses Id Değerlrinin Üretilmesi
+ Proses Id Değerinden Proses Kontrol Bloğuna Erişilmesi
+ Prosesler Arasındaki İlişkilerin Oluşturulduğu Veri Yapıları
+ Linux Sistemlerinde task_struct Yapılarının Arasındaki Bağlantılar
+ Linux'ta Prooses Ağacının Dolaşılması
+ Linux Çekirdeğinde Prosslerin Durumları (Prcsess State)
+ Proseslerin Kaynak Limitleri
+ Linux Sistemlerinde Proseslerin Kaynak Limitlerine İlişkin Belirlemeler
+ Linux Çekirdeğinde Proses Yaratımına İlişkin Sistem Fonksiyonlarının ve Çekirdek Kodlarının Gözden Geçirilmesi
+ Linux Çekirdeklerinde Proseslerin Sonladırılması

+ 
## İşletim Sistemlerinde Thread Mekanizmaları
+ Thread Nedir?
+ Prosese ve Thread'e Özgü Bilgiler ve Veri Yapıları
+ Linux Çekirdeklerinde Thread'lerin task_struct Yapısındaki Temsili
+ Linux Çekirdeklerinde Prosesin Thread'lerinin Tutulduğu Veri Yapıları
+ Thread'lerin Çizelgeleme Politikaları ve Thread'lerin Öncelikleri
+ Linux Çekirdeklerinde Thread'lerin Yaratılması
+ POSIX pthread Kütüphanesinin Genel Yapısı

  
## İşletim Sistemlerinde Bekleme Kuyruklarının Tasarımı ve Gerçekleştirimi
+ Thread'lerin Bloke Olması
+ Bekleme Kuyruklarının Genel Yapısı
+ Bekleme Kuyruklarının Yaratılması
+ Bekleme Kuyruklarına Thread'lerin yerleştirilmesi ve Geri Alınması
+ Linux Çekirdeklerinde Bekleme Kuyrukları İle İşlem Yapan Çekirdek Kodlarının İncelenmesi
+ 

## İşletim Sistemlerinde Bağlamsal Geçiş (Context Switch) Mekanizması 
+ İşletim sistemlerinde Zaman Paylaşımlı Çalışma
+ Preemtive İşletim Sistemlerine Genel Bakış
+ Preemptive Çekirdekler 
+ İşletim Sistemlerinde Bağlamsal Geçiş Nasıl gerçekleştirilmektedir?
+ Linux Sistemlerinde Bağlamsal Geçiş İçin Oluşturulan Veri Yapıları
+ Linux Sistemlerinde Bağlamsal Geçişe İlişkin Kodların İncelenmesi
+ Linux Sistemlerinde Bağlamsal Geçişin Yapıldığı Yerler

## İşletim Sistemlerinde Çizelgeleme 
+ Thread Çizelgelmesi Nedir?
+ Thread Çizelgelemesinde Hangi Yöntemler Uygulanmaktadır?
+ Linux Sistemlerindeki Thread Çizelgelemerinde Zaman İçerisinde Hangi Değişiklikler Yapılmıştır?
+ Linux'un CFS (Completely Fair Scheduling) Algoritması
+ Birden Çok İşlemciya da Çekirdek Söz Konusu Olduğunda Çizelgeleme Aldoritmasının İşltilmesi
+ 

## İşletim Sistemlerinde Kesme Mekanizmaları
+ Kesme Kavramı ve Kesmelerin Ele Alınması, Kesme Çeşitleri
+ IRQ Kavramı ve PC Mimarisindeki IRQ Mekanizması
+ ARM Mimarilerindeki IRQ Mekanizmaları
+ Donanım Kesmeleri (Hardware Interrupts) ve İçsel Kesmeler (Exceptions)
+ Linux ÇekirdeklerindeKesme Betimleyici Tabloları (Interrupt Descriptor Tables)
+ Linux Çekirdeklerinde Kesmelerin Ele Alınması
+ Linux Çekirdeklerinde Kesme Oluştuğunda Thread'lerin Çekirdek Moduna Geçmesi ve Kullanıcı Moduna Geri Dönmesi
+ Linux Çekirdeklerinde SoftIRQ ve Tasklet Mekanizmaları
+ 



 
# Kursa Kayıt
[Kursumuza ön kayıt yaptırmak için bu bağlantıyı kullanabilirsiniz.](https://us02web.zoom.us/meeting/register/tZUucuytrTopEtJEi5_RgJJMCHp7BrlLUtTf#/registration)
