**a. How many data your publisher program will send to the message broker in one run?**  
Publisher akan mengirimkan 5 data ke *message broker* dalam satu jalan. Kelima pesan tersebut memiliki informasi berbeda mengenai user_id dan user_name.

**b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?**  
Karena URL pada publisher dan subscriber sama, maka keduanya akan terhubung ke *message broker* RabbitMQ yang sama. Dimana keduanya akan berkomunikasi melalui server RabbitMQ yang berjalan di localhost pada port 5672 dengan *username* 'guest' dan *password* 'guest'. Koneksi ini memungkinkan publisher untuk mengirim *message* ke broker, dan subscriber untuk menerima *message* yang dikirimkan oleh publisher.

<br>

![Initial RabbitMQ](<image/Initial RabbitMQ.png>)