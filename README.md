# Keycloak_AutoStart_Setup

AWS Ec2 sunucularında kurulu olan keycloak lar reboot tan sonra otomatik olarak başlamıyordu. Manuel başlatılmaya ihtiyacı vardı. Bunun için aşağıdaki komutu çalıştırdık :

"chkconfig nginx on"

sudo chkconfig nginx on

**sudo su yaparsan root user a geçiş yaparsın.

Bu komutun ne yaptığını boş zamanında çalış öğren. Aşağıdakileri de boş zamanında oku öğren !!!


https://subscription.packtpub.com/book/cloud-and-networking/9781788623551/1/ch01lvl1sec15/adding-nginx-as-a-system-service

http://www.freekb.net/Article?id=1226

https://stackoverflow.com/questions/17287418/nginx-not-starting-after-server-reboot
