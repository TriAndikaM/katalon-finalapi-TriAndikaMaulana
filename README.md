# API restful-booker.herokuapp.com/

## Get All Booking ID
Pada test case ini akan didapatkan semua Id booking yang ada dengan menggunakan metode request API GET ke https://restful-booker.herokuapp.com/booking. {idbooking} diambil dari global variabel idbooking. 

Endpoint: https://restful-booker.herokuapp.com/booking

## Get Detailed Booking Data based Id
Pada test case ini akan didapatkan detail informasi dari satu id booking menggunakan metode request API GET ke https://restful-booker.herokuapp.com/booking/${idbooking}. {idbooking} diambil dari global variabel idbooking

Endpoint: https://restful-booker.herokuapp.com/booking/${idbooking}

## Get Token
Pada test case ini akan didapatkan token autentikasi dari https://restful-booker.herokuapp.com/auth dan menyimpanya pada global variabel {token}.

Endpoint: https://restful-booker.herokuapp.com/auth

## Insert Data Booking Baru
Pada test case ini akan dibuat data booking baru dengan request API POST ke https://restful-booker.herokuapp.com/booking

Endpoint: https://restful-booker.herokuapp.com/booking

## Update Data 
Pada test case ini data booking diidentifikasi dengan {idbooking} yang disimpan global variabel kemudian data terkait id tersebut disunting dengan request API PUT ke https://restful-booker.herokuapp.com/booking/${idbooking}

Endpoint: https://restful-booker.herokuapp.com/booking/${idbooking}

## Delete Data
Pada test case ini data booking akan diidentifikasi{idbooking} yang disimpan global variabel kemudian data terkait tersebut akan dihapus dengan request DELETE ke https://restful-booker.herokuapp.com/booking/${idbooking}

Endpoint: https://restful-booker.herokuapp.com/booking/${idbooking}
