> What is **AMQP**?

AMQP atau Advanced Message Queuing Protocol merupakan sebuah standar protokol untuk mentransfer pesan antar aplikasi atau servis. Agar seperti HTML, namun dengan sistem dan kegunaan yang berbeda. Sebuah producer (client yang ingin mengirim pesan) akan terhubung dengan broker (sebuah server), dan consumer (client lain yang ingin menerima pesan) juga akan terhubung dengan broker yang sama untuk menerima pesannya.

> What does it mean? *guest:guest@localhost:5672* , what is the first **guest**, and what
is the second **guest**, and what is **localhost:5672** is for?

- `guest` pertama merupakan username untuk autentikasi.
- `guest` kedua merupakan password untuk autentikasi.
- `localhost:5672` merupakan lokasi url broker, dimana `localhost` merupakan hostname atau IP address dan `5672` merupakan port pada hostname atau IP tersebut.

### Simulating Slow Subscriber
![slow_sub](image/Simulating%20slow.png)

Pada queue, terdapat 11 message yang belum dikirim karena subscriber yang sedang (disimulasikan) pelan.