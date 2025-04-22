# Module 10 - Software Architecture

## Refleksi 10 - Subscriber

> What is **_amqp?_**

**AMQP** (Advanced Message Queuing Protocol) adalah protokol standar terbuka untuk pertukaran pesan antar aplikasi atau komponen sistem. Protokol ini dirancang untuk mendukung komunikasi message-oriented yang handal, dengan fitur seperti message queuing, routing, reliability, dan security. AMQP memungkinkan aplikasi mengirim pesan secara asynchronous dan memastikan pesan terkirim bahkan saat penerima tidak online, sehingga cocok untuk sistem terdistribusi.

> What it means? `guest:guest@localhost:5672`, what is the first **_guest_**, and what is
the second **_guest_**, and what is **_localhost:5672_** is for?

String `guest:guest@localhost:5672` adalah format URL koneksi untuk RabbitMQ. Format ini terdiri dari beberapa bagian: bagian pertama **_guest_** adalah username untuk autentikasi ke server RabbitMQ, bagian kedua **_guest_** adalah password untuk autentikasi, dan **_localhost:5672_** menunjukkan alamat server (localhost, yaitu komputer lokal) dan port (5672) dimana server RabbitMQ berjalan. Port 5672 adalah port default yang digunakan oleh protokol AMQP.