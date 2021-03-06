### API

API merupakan singkatan dari _application programming interface_, atau dalam bahasa manusia dapat diartikan sebagai penjembatan dalam sisi pemrograman aplikasi. Agar lebih jelas, kita dapat mengartikan API sebagai segala hal yang memberikan abstraksi pada suatu proses. 

Semisal kita ingin mendapatkan data sebuah pengguna pada Twitter kita dapat menggunakan API dari Twitter. Ketika kita menggunakan API kita tidak pernah tahu apa yang terjadi pada server Twitter. Kita hanya perlu mengetahui data apa yang harus kita kirim untuk mendapatkan data yang kita inginkan.

### OpenWeather API

OpenWeather API merupakan sebuah API yang diluncurkan oleh OpenWeather untuk memudahkan developer dalam mendapatkan data terkini mengenai cuaca. OpenWeather API merupakan API yang masuk ke dalam kategori **Restfull API** karena untuk mengaksesnya kita menggunakan request HTTP dan datanya dikirim dengan format JSON.

### Package Structure

Pada pembuatan proyek ini struktur package dibuat seperti berikut

```
|-- build.gradle
|-- README.md
|-- settings.gradle
|-- src
    |-- main
        |-- java
            |-- Controller
            |-- Model
            |-- Services
            |-- View
        |-- resources
    |-- test 
```

Struktur dasar dari proyek ini mengikuti guideline dari Maven sendiri, namun untuk struktur package dalam folder Java ada beberapa konsiderasi yang diperlukan. Konsiderasi pertama adalah saya tidak mengetahui seluas apa cakupan proyek ini.

Oleh karena itu file Java dikelompokkan ke dalam package Controller, Model, Services, View yang pasti ada pada proyek manapun. Dengan ini dalam proses pembuatan aplikasi, tidak akan ada package yang ditambah maupun dikurangi.

#### Implemented
NONE
#### Ongoing
* Search
* Current Weather
* Set default location
### Cancelled
NONE