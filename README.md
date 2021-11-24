### MNM - PATIKA Magento2 - Ubuntu Server 

> Mac ve linux işletim sistemi kullanıcıları bu adımı atlayarak Magento Deploy adımına geçebilirler,

Windows kullanıcıları için oluşturulan ubuntu server imajını indiriniz, testler virtualbox üzerinde gerçekleşmiştir, ubuntu imajı içerisindeki vm network tanımı (netpplan) enp0s3 olarak ayarlıdır, bağlantı problemi yaşanır ise bu ayar kontrol edilmelidir

https://sendgb.com/hJcjLp07x19


# Virtualbox import ova

Virtualbox üzerinde Sanal cihazı içe aktar seçeneği ile indirdiğiniz ova imajını gösterin.

İmport sonrası sanal makinanın ayarlar sekmesinde network seçeneğini NAT olarak değşitirin,

Gelişmişe tıklayarak Bağlantı Noktası Yönlendirme seçeğine girin,

![This is an image](https://i.ibb.co/bHMGkQ0/Screen-Shot-2021-11-24-at-15-43-10.png)

Yukarıdaki gibi tanımlamaları gerçekleştirin,

Sanal sunucuyu çalıştırın, sunucu 


# Ubuntu server credential

username: mnm

password: 1123


> NOT: Windows Terminal, Php storm uygulamalarının indirilmesi önerilmektedir,

# Magento Deploy

> https://github.com/markshust/docker-magento

```
# Create your project directory then go into it:
mkdir ~/Sites/magento
cd $_


https://meet.google.com/abv-qkde-jsj

# Run this automated one-liner from the directory you want to install your project.
curl -s https://raw.githubusercontent.com/markshust/docker-magento/master/lib/onelinesetup | bash -s -- magento.test 2.4.3-p1
```


