
# Api untuk pemesanan makanan menggunakan QR code


## Petunjuk penggunaan API ini

#### Get all Makanan


```http
  https://apis.salmanalfarizq.eu.org/api/v1/barang
```


#### Detai Makanan bedasarkan id


```http
  https://apis.salmanalfarizq.eu.org/api/v1/barang/${id}
```


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id dari data yang difetch di enpoint sebelumnya fetch |


#### Get semua meja


```http
  https://apis.salmanalfarizq.eu.org/api/v1/meja
```


#### Get Meja bedasarkan id meja


```http
  https://apis.salmanalfarizq.eu.org/api/v1/meja/{id}
```


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id dari data yang difetch di enpoint sebelumnya fetch |


#### Get keranjang


```http
  https://apis.salmanalfarizq.eu.org/api/v1/barang/${id}
```


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id_meja` | `int`    | **Required**. Id_meja dari data di endpoint meja |


#### Payment
##### ***beta***


```http
  https://payment.salmanalfarizq.eu.org/payments/intents?apiKey=ey-123648839988883922
```


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `amout`   | `int`    | **Required**. penulisan bilangan harus '1000000' artinya 10.000 dan minimal transaksi 10.000 |
| `apiKey`  | `string` | **Required**. anda bisa dm saya untuk mendapatkan apiKey nya|


## Untuk repositorynya bisa klik link di bawah ini
### [Repository Pemesanan makanan](#)
### [Payment](#)

## ***Jangan Lupa Follow Media Sosial Kreator dan berikan star untuk repositorinya***

