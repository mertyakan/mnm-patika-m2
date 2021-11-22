# MNM - PATIKA Magento2 - Ubuntu Server 

magento2 için oluşturulan ..... linki üzerinden ova formatında oluşturulan ubuntu server imajını indiriniz,

https://link.link


# Ubuntu server credential

username: mnm

password: 1123

İmport işlemi için virtualbox üzerinde denenmiştir,

Windows üzerinden erişim sağlanılacak ise, 

Windows Terminal uygulamasının indirilmesi önerilmektedir,


NOT: Ova formatındaki sanal sunucuyu import ettikten sonra, network ayarlarının yapılması gerekmektedir,

```
sudo vim /etc/netplan/00-installer-config.yaml
```

Aşağıdaki gibi netplan dosyasını düzenleyiniz,

```
network:
  ethernetes:
    enp0s3:
      dhcp4: true
  version: 2
```

Sanal sunucuyu çalıştırdıktan sonra

