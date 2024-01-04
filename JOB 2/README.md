# JOBSHEET 2 -  PROTOKOL KOMUNIKASI DAN SENSOR
# Abstrak
Pada praktikum ini memberikan wawasan tentang cara kerja protokol komunikasi terutama yang terdapat pada ESP32, seperti UART, I2C, OneWire, SPI, serta dapat menggunakannya untuk mengakses sensor. UART (Universal Asynchronous Receiver Transmitter) adalah protokol komunikasi yang umum digunakan dalam pengiriman data  serial antara device satu dengan yang lainnya. Sebagai contoh komunikasi antara sesama mikrokontroler atau mikrokontroler ke PC. Dalam pengiriman data, clock antara pengirim dan penerima harus sama karena paket data dikirim tiap bit mengandalkan clock tersebut. SPI (Serial Peripheral Interface) adalah protokol data serial sinkron digunakan oleh mikrokontroler untuk berkomunikasi dengan satu atau lebih perangkat periferal cepat jarak pendek. Hal ini juga dapat digunakan untuk komunikasi antara dua mikrokontroler. Dengan koneksi SPI selalu ada perangkat satu master (biasanya mikrokontroler) yang mengontrol perangkat periferal. Sedangkan I2C (Inter Integrated Circuit) adalah sebuah protokol untuk komunikasi serial antar IC, dan sering disebut juga Two Wire Interface (TWI). Dalam praktikum ini juga memanfaatkan transducer sensor dan actuator untuk membuat sebuah perangkat IoT.
# Alat dan Bahan
  1. ESP32
  2. Breadboard
  3. Kabel jumper
  4. Sensor DHT 11, RFID
  5. LED (5) dan Push Button (3)
  6. Servo
  7. Resistor 330,1K, 10K Ohm (@ 3)
