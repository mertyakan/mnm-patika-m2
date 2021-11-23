### MNM - PATIKA Magento2 - Ubuntu Server 

> Mac ve linux işletim sistemi kullanıcıları bu adımı atlayarak Magento Deploy adımına geçebilirler,

Windows kullanıcıları için oluşturulan ubuntu server imajını indiriniz, testler virtualbox üzerinde gerçekleşmiştir, 

https://link.link


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

# Run this automated one-liner from the directory you want to install your project.
curl -s https://raw.githubusercontent.com/markshust/docker-magento/master/lib/onelinesetup | bash -s -- magento.test 2.4.3-p1
```


