# Reflection

### commit 2.1
#### server side
![commit2.1-server](images/commit2.1-server.png)

#### client 1 side
![commit2.1-client1](images/commit2.1-client1.png)

#### client 2 side
![commit2.1-client2](images/commit2.1-client2.png)

#### client 3 side
![commit2.1-client3](images/commit2.1-client3.png)

Untuk menjalankannya simply buat terminal untuk masing-masing sisi dan run setidaknya 1 server dengan command `cargo run --bin server` dan setidaknya 1 client dengan command `cargo run --bin client`. Pada tutorial ini saya membuat 4 terminal total (1 server dan 3 client). Ketika kita mengirim text dari 1 client, server akan mengeprint text dari 1 client tersebut beserta detail dari port apa. Selain itu, client lain juga menerima pesan tersebut.