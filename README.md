# MyQuote
MyQuotes adalah project sederhana yang menampilkan list data quotes. Bahasa yang digunakan yaitu kotlin dengan XML sebagai view nya. Pada project ini menerapkan konsep Networking dengan LoopJ dan Parsing JSON
## What I Learn
1. Project ini menggunakan library LoopJ dan menggunakan AsyncHttpClient untuk membuat koneksi ke server secara asynchronous. 
2. Project MyQuotes hanya mengambil data(READ) yaitu menggunakan client.get(). 
3. Terdapat 2 object yang dihasilkan oleh AsyncHttpResponseHandler yaitu onSuccess(koneksi berhasil) dan onFailure(koneksi gagal).
4. Menampilkan errorMessage berdasarkan statusCode, seperti 401 yang merupakan bad request
5. Parsing JSON dari <a href="https://quote-api.dicoding.dev/random" target="_blank">Quote Api Dicoding</a>
6. Format JSON pada API apabila { } = bertipe JSONObject dan [ ] = bertipe JSONArray
