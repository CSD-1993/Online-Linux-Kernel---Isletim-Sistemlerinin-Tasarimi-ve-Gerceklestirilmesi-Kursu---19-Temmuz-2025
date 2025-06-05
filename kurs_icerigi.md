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
+ Intel x86-64 İşlemcilerinin Yazılım Miimarisine İlişkin Temel Özellikler
+ 32 ve 64 Bit ARM İşlemcilerinin (AArch32 ve AArch64) Yazılım Mimarisine İlişkin Temel Özellikler
+ Intel ve ARM Sembolik Makine Dilleri (Assembly Languages) Hakkında Temel Bilgiler
+ GCC Derleyicilerinin Linux Çekirdek Kodlarını İlgilendiren Eklentileri
+ Flat Binary Dosyaların Oluşturulması ve objcopy Programının Kullanımı
+ Bağlayıcıların (Linkers) Kullanımı 
+ İşlemcilerde Koruma Mekanizması
+ Intel x86-x64 İşlemcilerinde Sayfalama Mekanizması
+ ARM İşlemcilerinde Sayfalama Mekanizması
+ Linux Çekirdek Kodlarına İlişkin Dizin Ağacı
+ Çekirdek Kaynak Kodlarında Ne Nerededir?

## Linux Sistemlerinin Boot Süreci 
+ Boot İşleminin Genel İşleyişi
+ asaüstü Sistemlerde ve Gömülü Sistemlerde Boot Süreci
+ Boot Loader Programları
+ Çekirdek Parametreleri
+ Çekirdek Parametrelerinin Çekirdek Kodları Tarafından Elde Edilmesi ve Kullanılması
+ Geçici Kök Dosya Sistemi
+ Kök Dosya Sisteminin Mount Edilmesi
  
+ ## Çekirdeğin Derlenmesi
+ Çekirdek Derleme İşlemlerinin Adımları
+ Kaynak Kodların İndirilmesi
+ Çekirdek Build Sisteminin Gözden Geçirilmesi
+ Çekirdek Üzerinde yapılan Değişikliklerin Build İşlemine Dahil Edilmesi
+ Sistemin Yeni Çekirdekle Yeniden Başlatılmasının Sağlanması

## Çekirdek Kodlamasında Kullanılan Önemli Veri Yapıları
+ Bağlı Listeler ve Linux Çekirdeklerinde Bağlı Listelerin Gerçekleştirimi
+ Kuyruk Sistemleri ve Linux Çekirdeklerinde Kuyruk Sistemlerinin Gerçekleştirimi
+ Hash Tabloları ve Linux Çekirdeklerinde hash tablolarının Gerçekleştirimi
+ İkili Arama Ağaçları, AVL ve Kırmızı-Siyah Dengelemesi ve Linux Çekirdeklerindeki Gerçekleştirimleri
+ Cache Sistemlerinin Oluşturulması ve Linux Çekirdeklerinde LRU Tabanlı Cache Sistemlerinin Gerçekleştirimi
  
## Proses Yönetimi
+ Proses Kavramı, Proseslere İlişkin Bilgiler, Proses Kontrol Bloğu
+ Proses Kontrol Bloklarının İçerdiği Bilgiler
+ Linux'un task_struct Yapısının İncelenmesi
+ Linux Sistemlerinde Pross'lerin Id Değerlerinin Anlamı ve Proses Id Değerlerinin Oluşturulması
+ Linux Çekirdeğinde Proses Id Değerlrinin Üretilmesi
+ Proses Id Değerinden Proses Kontrol Bloğuna Erişilmesi
+ Prosesler Arasındaki İlişkilerin Oluşturulduğu Veri Yapıları
+ Linux Sistemlerinde task_struct Yapılarının Arasındaki Bağlantılar
+ Linux Çekirdeğinde Prooses Ağacının Dolaşılması
+ Linux Çekirdeğinde Prosslerin Durumları (Prcsess State)
+ Proseslerin Kaynak Limitleri
+ Linux Sistemlerinde Proseslerin Kaynak Limitlerine İlişkin Belirlemeler
+ Linux Çekirdeğinde Proses Yaratımına İlişkin Sistem Fonksiyonlarının ve Çekirdek Kodlarının Gözden Geçirilmesi
+ Linux Çekirdeklerinde Proseslerin Sonladırılması
+ Linux Çekirdeğinde Prseslere İlişkin Sistem Fonksiyonlarının Gözden Geçirilmesi
  
## Thread Yönetimi
+ Thread Kavramı ve Thread'lere Olan Gereksinim
+ Prosese ve Thread'e Özgü Bilgiler ve Veri Yapıları
+ Linux Çekirdeklerinde Thread'lerin task_struct Yapısıyla Temsili
+ Linux Çekirdeklerinde Prosesin Thread'lerinin Tutulduğu Veri Yapıları
+ Thread'lerin Çizelgeleme Politikaları ve Thread'lerin Öncelikleri
+ Linux Çekirdeklerinde Thread'lerin Yaratılması
+ POSIX pthread Kütüphanesinin Genel Yapısı ve Gerçekleştirimine İlişkin Bilgiler

## Linux Çekirdek Kodlarında Senktronizasyon
+ CPU'ya Özgü Değişkenler
+ Atomik İşlemler
+ Bellek Bariyerleri
+ Spinlock Mekanizaması ve Spinlock Nesneleri
+ Rad/Write Spinlock NEsneleri
+ Semaphore Nesneleri
+ Seqloc'lar
+ Read Copy Update Mekanizması
+ Read/Write Semaphore Nesneleri
+ Bitiş (Completion) Nesneleri
+ Kesmelerin Kapatılması ve Açılması

## Bekleme Kuyruklarının Tasarımı ve Gerçekleştirimi
+ Thread'lerin Bloke Olması
+ Bekleme Kuyruklarının Genel Yapısı
+ Bekleme Kuyruklarının Yaratılması
+ Bekleme Kuyruklarına Thread'lerin yerleştirilmesi ve Oradan Geri Alınması
+ Linux Çekirdeklerinde Bekleme Kuyrukları İle İşlem Yapan Çekirdek Kodlarının İncelenmesi

## Linux Çekirdeğinin Dosya Sistemi 
+ Sanal Dosya Sistemi (Virtual File System) Kavramı
+ Dosya Sistemine İlişkin Veri Yapıları
+ Proseslerin Dosya Betimleyici Tabloları
+ Dosya Nesneleri ve file Yapısının İncelenmesi
+ inode Yapısı ve inode Nesneleri
+ dentry Yapısı ve dentry Nesneleri
+ Süper Blok Nesneleri
+ INode Cache Sistemi
+ Dentry Cache Sistemi
+ Dosya Sistemi Türleri 
+ Dosya Sistemlerinin Register Ettirilmesi
+ İsim Alanları (Namespaces)
+ Dosya Sistemlerinin Mount Edilmesi
+ Kök Dosya Sisteminin Mount Edilmesi
+ Geçici Kök Dosya Sistemleri ve Gerçek Dosya Sistemine Geçiş
+ Dosya Sistemlerinin Unmount Edilmesi
+ Yol İfadelerinin Çözümlenmesi (Pathname Resolution)
+ Sembolik Bağlantı Dosyalarının İzlenmesi
+ Dosya Sistemine İlişkin Sistem Fonksiyonlarının Gerçekleştirimi
+ Dosya Kilitlemeye Yönelik Veri Yapıları
  
## Linux Aygıt Sürücü Mimarisi
+ Donanımsal IO İşlemlerine ve IO Portlarına Genel Bakış
+ Linux Çekirdeğinde Aygıt Sürücü Mimarisi
+ Linux Çekirdeğinde Aygıt Sürücü Mimarisine İlişkin Veri Yapıları)
+ KObject Nesneleri
+ Aygıt Dosyaları (Device Files)
+ Aygıt Sürücülerinin Yüklenme Süreci
+ Aygıt Sürücülere Erişim
+ DMA İşlemleri
+ Karakter Aygıt Sürücülerinin Temel Yapısı ve Çalışma Biçimi
+ Blok Aygıt Sürüclerinin Temel Yapısı ve Çalışma Biçimi
+ Çekirdeğin IO Çizelgeleyicisi
   
## Linux Çekirdeklerinde Zaman Ölçümleri
+ Donanımların Sunduğu Zamanlama Mekanizmaları
+ Gerçek Zaman Saatleri, İşlemcilerin TSC Mekanizmaları, Zamanlayıcı Devreleri (PIT)
+ İşlemcilerin Yerel Zamanlayıcıları (Local Timers)
+ Linux Sistemlerinde Zamanlama İşlemleri
+ Zamanlama Mekanizmasında Kullanılan Veri Yapıları
+ jiffies Değişkeni
+ Timer Kesme Kodunun İncelenmesi
+ Global ve Yerel Timer Kesme Kodları
+ Çekirek Zamanının ve Tarihinin Güncellenmesi
+ Sistem İstatistiklerinin Güncellenmesi
+ Dinamik Zamanlayıcılar
+ Delay Fonksiyonları
+ Zamanlamaya Yönelik Sistem Fonksiyonlarının Gözden Geçirilmesi

## Bağlamsal Geçiş (Context Switch) Mekanizması 
+ İşletim sistemlerinde Zaman Paylaşımlı Çalışma
+ Preemtive İşletim Sistemlerine Genel Bakış
+ Preemptive Çekirdekler 
+ İşletim Sistemlerinde Bağlamsal Geçiş Nasıl gerçekleştirilmektedir?
+ Linux Sistemlerinde Bağlamsal Geçiş İçin Oluşturulan Veri Yapıları
+ Linux Sistemlerinde Bağlamsal Geçişe İlişkin Kodların İncelenmesi
+ Linux Sistemlerinde Bağlamsal Geçişin Yapıldığı Yerler

## Çizelgeleme İşlemleri
+ Thread Çizelgelmesi Nedir?
+ Thread Çizelgelemesinde Hangi Veri Yapıları ve Algoritmalar Kullanılmaktadır?
+ Linux Sistemlerindeki Thread Çizelgelemelerinde Zaman İçerisinde Hangi Değişiklikler Yapılmıştır?
+ Çizelgeleyici Sisteme İlişkin Veri Yapılarının Tanıtılması
+ Linux'un CFS (Completely Fair Scheduling) Algoritması
+ CFS Algortimasına İlşkin Çekirdek Kodlarının Gözden Geçirilmesi
+ Çok İşlemcili ya da Çok Çekirdekli Sistemlerde Çalışma Kuyruklarlarının Dengelenmesi
+ Çizelgeleme İşlemlerine Yönelik Sistem Fonksiyonlarının Gözden Geçirilmesi

## Çekirdeğin Bellek Yönetimi
+ İşlemcilerin Sayfalama Mekanizması
+ İşlemcilerin Koruma Mekanizması
+ SMP ve NUMA Mimarileri
+ Fiziksel Sayfalara İlişkin Çekirdek Veri Yapıları
+ Sayfa Betimleyicileri
+ Sayfaların Tahsis Edilmesi
+ 32 Bit Sistemlerde Yüksek Bellek Alanının Yönetimi
+ İkiz Blok Sisteminin Tasarım ve Gerçekleştirimi
+ Dilimli Tahsisat Sisteminin (Slab Allocator) Tasarım ve Gerçekleştirimi
+ CPU'ya Özgü Sayfalama Cache'leri
+ Ardışıl Olmayan Bellek Tahsisatları
+ Proseslerin Bellek Alanları
+ Bellek Betimleyicileri
+ Belleğin Bölgelere Ayrılması
+ Prosesler İçin Doğrusal Bellek Alanının Yaratılması ve Yok Edilmesi
+ Copy On Write Mekanizması
+ Bellek Yönetimine İlişkin Sistem Fonksiyonları

## Page Cache Sistemi
+ Page Cache Sisteminin Amacı 
+ Page Cache Sisteminin Kullandığı Veri Yapıları
+ Kirlenmiş Sayfaların Aygıta Yazılması
+ pdflush Kernel Thread'inin Çalışma Sistemi
+ Page Cache Sistemine Yönelik Sistem Fonksiyonları

## Dosya Sisteminde Okuma ve Yazma İşlemleri
+ Disk Tbanlı Dosyalardan (Blok Aygıtlarından) Okuma ve Yazma İşlemlerinin Ayrıntıları
+ Bellek Tabanlı Dosyaların Organizasyonu
+ Asenkron IO İşlemleri

## Kesme Mekanizmaları ve Kesmelerin Çekirdek Tarafından Ele Alınması
+ Kesme Kavramı ve Kesmelerin Ele Alınması, Kesme Çeşitleri
+ IRQ Kavramı ve PC Mimarisindeki IRQ Mekanizması
+ Kesme Denetleyicileri ve APIC'ler
+ ARM Mimarilerindeki IRQ Mekanizmaları
+ Donanım Kesmeleri (Hardware Interrupts) ve İçsel Kesmeler (Exceptions)
+ Linux ÇekirdeklerindeKesme Betimleyici Tabloları (Interrupt Descriptor Tables)
+ Linux Çekirdeklerinde Kesmelerin Ele Alınması
+ Linux Çekirdeklerinde Kesme Oluştuğunda Thread'lerin Çekirdek Moduna Geçmesi ve Kullanıcı Moduna Geri Dönmesi
+ Linux Çekirdeklerinde SoftIRQ ve Tasklet Mekanizmaları
+ Çalışma Kuyrukları (Work Queues)
  
## Sistem Fonksiyonları (System Calls)
+ Sistem Fonksiyonlarının Çekirdek Kodlarındaki Organizasyonu
+ Sistem Fonksiyonlarının Çağrılma Mekanizması
+ Kullanıcı Modundan Sistem Fonksiyonarının Çağrılması
+ POSIX Kütüphanesi Tarafından Sistem Fonksiyonlarının Çağrılması
+ Sistem Fonksiyonlstıns Parametre Aktarımı
+ Sistem Fonksiyonlarına Aktarılan Parametrelerin Geçerliliğinin Sınanması
+ Sistem fonksiyonlarından Kullanıcı Alanına Erişim
+ Sistem Fonksiyonundan Geriye Dönüş
+ Sistem Fonksiyonlarına İlişkin Makrolar

## Sinyal (Signal) Mekamizması
+ Sinyal Kavramı
+ Linux Sistemlerinin Desteklediği Sinyaller
+ Siyallere İlişkin Çekirdek Veri Yapıları
+ Çekirdekte Sinyallerin Oluşturulması
+ Sinyallerin Proseslere Teslim Edilmesi
+ Sinyaller İçin Default Davranışların Oluşturulması
+ Sinyallerin Çekirdek Tarafından Yakalanması ve Ele Alınması
+ Sinyallerin Askıda Kalması ve Bloke Edilmesi
+ Sinyal Fonkisyonlarından Geriye Dönüş
+ Sinyallerin Yeniden Başlatılması Süreci
+ Sinyallerle İlgili Sistem Fonksiyonları

## Ext ve FAT Dosya Sistemlerinin Gerçekleştirimi (Signal) Mekamizması
+ Ext Dosya Sistemlerinin Disk Organizasyonu
+ Ext Dosya Sistemine İlişkin Çekirdek Kodlarının Gözden Geçirilmesi
+ FAT Dosya Sisteminin Disk Organizasyonu
+ FAT Dosya Sistemine İlişkin Çekirdek Kodlarının Gözden Geçirilmesi

# Kursa Kayıt
[Kursumuza ön kayıt yaptırmak için bu bağlantıyı kullanabilirsiniz.](https://us02web.zoom.us/meeting/register/tZUucuytrTopEtJEi5_RgJJMCHp7BrlLUtTf#/registration)
