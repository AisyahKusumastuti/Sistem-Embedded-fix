# ADC (Analog to digital Converter) dan DAC (Digital to Analog Converter)
## Rangkaian
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/C.%20ADC%20dan%20DAC/ADC%20CDA.png?raw=true)

## 1. Membaca Nilai Yang Dihasilkan Potensiometer
### A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/C.%20ADC%20dan%20DAC/ADC___DAC_Program_langkah_2/ADC___DAC_Program_langkah_2.ino).
### B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/C.%20ADC%20dan%20DAC/ADC___DAC_Program_langkah_2/ADC%201.drawio.png?raw=true)
### C. Hasil
Percobaan ini bertujuan untuk membaca nilai analog dari potensiometer secara real time melalui serial monitor. Program menginisialisasi komunikasi serial menggunakan command "Serial.begin(115200)" dan memberikan jeda waktu 1 detik menggunakan "delay(1000)". Hasilnya nilai potensiometer bernilai antara 0 sampai 4095.

## 2. Mengatur Cahaya LED Menggunakan Potensiometer
### A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/C.%20ADC%20dan%20DAC/ADC___DAC_Program_langkah_4/ADC___DAC_Program_langkah_4.ino).
### B. Flowchart
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/C.%20ADC%20dan%20DAC/ADC___DAC_Program_langkah_4/ADC%202.drawio.png?raw=true)
### C. Hasil
Percobaan ini bertujuan untuk mengendalikan kecerahan LED dengan memanfaatkan nilai analog dari sebuah potensiometer. Program ini menggunakan modul PWM sebagai output yang terhubung ke LED. Setelah program membaca nilai analog dari potensiometer, nilai ini kemudian di mapping untuk rentang nilai analog (0 hingga 4095) menjadi rentang nilai PWM (0 hingga 255). Nilai inilah yang digunakan untuk mengatur kecerahan LED. Hasilnya semakin besar nilai potensiometer yang diputar maka LED akan semakin nyala terang.

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/7da227fe-132e-4d59-b33d-0ccde968f5d9
