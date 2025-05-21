# Advprog Tutorial 10 - Timer
## Priscilla Natanael Surjanto - 2306152153

### 2.1 Original code of the broadcast chat
![image1](images/image1.png)
Cara menjalankan:
1. Buka 4 terminal, semua terminal harus ada pada direktori proyek
2. Jangan lupa masukkan direktori bin ke `Cargo.toml`
3. Jalankan `cargo run --bin server` pada satu terminal
4. Jalankan `cargo run --bin client` pada 3 terminal lainnya
5. Mulai coba kirimkan pesan melalui terminal client

Ketika satu terminal client mengetik sebuah pesan lalu menekan enter, pesan ini akan dikirimkan ke server lalu dicetak pada terminal server. Server kemudian akan mengirimkan pesan tersebut ke semua client, dan pesan akan dicetak di semua terminal client. Ini berlaku pada terminal client manapun.