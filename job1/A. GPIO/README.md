# GPIO (General Purpose Input/Output)
## 1. GPIO - LED Blink
### A. Rangkaian
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/Rangkaian%20GPIO.png?raw=true)
## B. Source Code
Program LED Blink dapat dilihat pada link ini.
## C. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_program_Example_Blink/fc%20gpio%201.drawio.png?raw=true)
## D. Hasil dan Pembahasan
https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/8361ed71-04cc-45cd-a4dd-d005df0077e5 
Pada percobaan pertama digunakan 1 buah LED dan 1 buah Push Button. Push Button diinisialisasi sebagai Input melalui GPIO 4 pada ESP32 sedangkan pin LED diinisialisai sebagai Output melalui GPIO 5 pada ESP32. Setelah itu, program dibuat agar LED dapat melakukan blink dengan interval 1 detik sekali menggunakan timer milis(). 
## E. Kesimpulan
Dalam percobaan ini dapat disimpulkan bahwa kita dapat mengatur interval LED dalam melakukan blink menggunakan perintah delay().
