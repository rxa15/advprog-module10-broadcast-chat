# Module 10: Asynchronous Programming
## Tutorial Advanced Programming 2023/2024 Genap

* Nama  : Tengku Laras Malahayati
* NPM   : 2206081641
* Kelas : A

## Reflection
### 2.1 Original Code of Broadcast Chat
![Original Code & How It Works](sources/2.1.png)
First, I execute the command `cargo run --bin server` to start the server. Following that, I launch the client using `cargo run --bin client`. This client automatically connects to the server. As shown in the above image, whenever I type a message on the client side, the server receives it and displays the output `From client 127.0.0.1: "message"`. Additionally, other clients are able to see the messages sent by other clients because the server relays them with the notation `From server: message`.