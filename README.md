#   elasticsearch-kibana

Docker-compose dosyası aracılığı ile elasticsearch ve kibana kurulumları yapılıp başlatılır. 5601 portu ile kibana arayüzüne bağlantı sağlanabilir.
Docker-compose dosyası docker-compose up -d ile ayağa kaldırılır. Bu işlemden sonra elasticsearh ve kibana servislerimiz çalışır halde olacaktır.
### Filebeat
Filebeat kurulumu yapıldıktan sonra /etc/filebeat/ dizininde filebeat dosyasında path kısmına ilgili logun pathi atanır. filebeat setup -e komutu ile elastic konfigürasyonu yapılır.
Artık kibanadan filebeatle çektiğimiz log verilerini görüntüleyebiliriz.

