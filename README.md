[![Build Status](https://travis-ci.org/Yara-Rules/rules.svg?branch=master)](https://travis-ci.org/Yara-Rules/rules) <img src="http://img.shields.io/liberapay/patrons/yararules.svg?logo=liberapay">


# Proje

Bu proje, bir grup BT Güvenliği Araştırmacısının, farklı Yara imzalarının derlendiği, sınıflandırıldığı ve mümkün olduğunca güncel tutulduğu tek bir depoya sahip olma ihtiyacını kapsar ve Yara kurallarını toplamak için açık kaynaklı bir topluluk olarak başlar. Yara kural setimiz GNU-GPLv2 lisansı altındadır ve bu lisans altında kullandığınız sürece herhangi bir kullanıcıya veya kuruluşa açıktır.

Yara giderek daha fazla kullanılıyor, ancak alet ve kullanımı hakkındaki bilgiler birçok farklı yere dağılmış durumda. Yara Kuralları projesi, mümkün olduğunca eksiksiz bir kural kümesini bir araya getirerek Yara kullanıcıları için buluşma noktası olmayı ve böylece kullanıcılara Yara'yı kullanıma hazır hale getirmenin hızlı bir yolunu sunmayı amaçlamaktadır.

Bu projenin Güvenlik Topluluğu ve tüm Yara Kullanıcıları için yararlı olacağını umuyoruz ve geri bildirimlerinizi bekliyoruz. E-posta listemize abone olarak bu topluluğa katılın.

# Katkı

Yara kurallarınızı bizimle ve Güvenlik Topluluğuyla paylaşmak istiyorsanız, posta listemize katılabilir, Twitter hesabımıza mesaj gönderebilir veya buradan çekme isteği gönderebilirsiniz.

Twitter hesabı: https://twitter.com/yararules

# Gereklilikler

Kurallarımızın çoğunun çalışması için Yara ** sürüm 3.0 ** veya üstü gereklidir. Bu, esas olarak bu sürümde tanıtılan "pe" modülünün kullanılmasından kaynaklanmaktadır.

Yüklü sürümünüzü 'yara -v' ile kontrol edebilirsiniz

Ubuntu 14.04 LTS varsayılan depolarında bulunan paketler çok eski.  Alternatif olarak kaynaktan yükleyebilir veya [Remnux deposunda](https://launchpad.net/~remnux/+archive/ubuntu/stable) bulunan paketleri kullanabilirsiniz.

~~Ayrıca, 'https://github.com/Koodous/androguard' kategorisindeki kuralları kullanmak istiyorsanız [Androguard Modülü] (mobile_malware-yara) ihtiyacınız olacak.~~

Androguard Modülüne bağlı mobile_malware kurallarını kullanımdan kaldırdık çünkü terk edilmiş bir proje gibi görünüyor.

# Kategoriler

## Anti-debug/Anti-VM

Bu bölümde, kötü amaçlı yazılımlar tarafından otomatik analizden kaçınmak için kullanılan hata ayıklama önleme ve sanallaştırma önleme tekniklerinin tespitine yönelik Yara Kurallarını bulacaksınız.

## Capabilities

Bu bölümde, diğer kategorilerin hiçbirine uymayan yetenekleri tespit etmek için Yara kurallarını bulacaksınız.  Analiz için bilinmesi yararlıdır, ancak kendi başlarına kötü amaçlı göstergeler olmayabilirler.

## CVE Kuralları

Bu bölümde, belirli Ortak Güvenlik Açıklarının ve Etkilenmelerin (CVE'ler) tanımlanmasına yönelik Yara Kurallarını bulacaksınız.

## Crypto

Bu bölümde, kriptografik algoritmaların tespitine ve varlığına yönelik Yara kurallarını bulacaksınız.

## Exploit Kitleri

In this section you will find Yara rules aimed toward the detection and existence of Exploit Kits.

## Zararlı Dökümanlar

Bu bölümde, Exploit Kitlerinin tespitine ve varlığına yönelik Yara kurallarını bulacaksınız.

## Zararlı Yazılımlar

Bu bölümde, iyi bilinen kötü amaçlı yazılımların tanımlanmasına yönelik Yara kurallarını bulacaksınız.

## Paketleyiciler

Bu bölümde, kötü amaçlı yazılımlar tarafından kendini gizlemek için kullanılabilecek iyi bilinen yazılım paketleyicilerini tespit etmeyi amaçlayan Yara Kurallarını bulacaksınız.

## WebShells

Bu bölümde, iyi bilinen web kabuklarının tanımlanmasına yönelik uzmanlaşmış Yara kurallarını bulacaksınız.

## Email

Bu bölümde, kötü amaçlı e-postaların tanımlanmasına yönelik Yara kurallarını bulacaksınız.

## Mobil Malware'lar

Bu bölümde, iyi bilinen mobil kötü amaçlı yazılımların tanımlanmasına yönelik Yara kurallarını bulacaksınız.

## Deprecated

Bu bölümde Yara kurallarının kullanımdan kaldırıldığını göreceksiniz.

# İletişim

Webpage: https://yara-rules.github.io/blog/

Twitter account: https://twitter.com/yararules

Yazının Orijinali: https://github.com/Yara-Rules/rules

