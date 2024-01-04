# GPIO (General Purpose Input/Output)
## 1. GPIO - LED Blink 1 detik
### Rangkaian
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/Rangkaian%20GPIO.png?raw=true)
### A. Source Code
Program LED Blink dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_program_Example_Blink/GPIO_program_Example_Blink.ino).
### B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_program_Example_Blink/fc%20gpio%201.drawio.png?raw=true)
### C. Hasil
Percobaan pertama ini membuat program agar LED dapat melakukan blink dengan interval 1 detik sekali. Fungsi "void setup" digunakan untuk mengatur perangkat agar menjadi input atau output. Sedangkan fungsi "void loop" digunakan untuk menjalankan blink secara terus menerus. Untuk mengatur interval waktu digunakan perintah delay().

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/8361ed71-04cc-45cd-a4dd-d005df0077e5 

## 2. GPIO - Mengendalikan LED Menggunakan Push Button
## A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_Program_langkah_3/GPIO_Program_langkah_3.ino).
## B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_Program_langkah_3/flowchart%20GPIO%202.drawio.png?raw=true)
## C. Hasil
Percobaan ini memanfaatkan push button untuk mengendalikan LED agar menyala ataupun mati. Nilai digital dari push button dapat dibaca dan disimpan dalam variabel buttonState menggunakan digitalRead(buttonPin). Jika nilai buttonState HIGH, maka LED akan menyala. Namun, jika push button bernilai LOW, maka LED akan mati.

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/cf547f57-35aa-4350-abaa-6ba3ed157272

## 3. GPIO - LED Blink Setiap 500ms Sekali
## A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_Program_langkah_4/GPIO_Program_langkah_4.ino).
## B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_Program_langkah_4/flowchart%20gpio%203.drawio.png?raw=true)
## C. Hasil

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/58bc0ca8-c7d1-4103-b67b-797f00a357c2

## 4. GPIO - Running LED
## A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_program_langkah_5_Rled/GPIO_program_langkah_5_Rled.ino).
## B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/A.%20GPIO/GPIO_program_langkah_5_Rled/flowchart%20gpio%204.drawio.png?raw=true)
## C. Hasil
https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/9b56adfe-8108-4625-a1f7-b513969c6d1d

## ANALISA
