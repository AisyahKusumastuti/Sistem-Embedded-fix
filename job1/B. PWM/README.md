# PWM (Pulse Width Modulation)
## Rangkaian
![alt text](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/B.%20PWM/PWM.png?raw=true)

## 1. Mengendalikan Kecerahan Sebuah LED
### A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/B.%20PWM/PWM_program_langkah_2/PWM_program_langkah_2.ino).
### B. Flowchart
![alt text](?raw=true)
### C. Hasil
Percobaan ini bertujuan untuk mengendalikan kecerahan sebuah LED menggunakan teknik PWM, yang mana merupakan sebuah teknik mengontrol tingkat daya yang disampaikan ke suatu perangkat atau komponen dengan cara mengubah persentase waktu di mana sinyal tersebut dalam keadaan aktif (tinggi) dalam suatu periode tertentu. Terdapat beberapa variabel penting pada percobaan ini, diantaranya yaitu "ledPin" atau nomor pin GPIO untuk LED, "freq" yang merupakan frekuensi dari PWM, "ledChannel" yaitu nomor saluran PWM, dan "resolution" yaitu resolusi bit PWM. Untuk meningkatkan kecerahan LED secara bertahap, digunakan "dutyCycle" dengan nilai dari 0 ke 255, sehingga memberikan efek peningkatan kecerahan dari mati,redup, hingga terang. Begitu pula sebaliknya, untuk mengurangi tingkat kecerahan LED, digunakan "dutyCycle" dengan nilai dari 255 ke 0, sehingga memberikan efek pengurangan kecerahan dari terang, redup, hingga LED mati. Duty cycle merupakan perbandingan antara durasi sinyal tinggi dan durasi total satu siklus, menentukan seberapa lama sinyal tinggi dibandingkan dengan total waktu siklus.

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/12a2a531-3836-4765-89d7-7f9d711f44cb

## 2. Mengendalikan Kecerahan 3 Buah LED
### A. Source Code
Program dapat dilihat [disini](https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/blob/main/job1/B.%20PWM/PWM_program_langkah_4/PWM_program_langkah_4.ino).
### B. Flowchart
![alt text](?raw=true)
### C. Hasil
Percobaan ini hampir sama dengan percobaan sebelumnya. Kali ini mengendalikan kecerahan dari 3 buah LED sekaligus. Variabel "ledPin" (nomor pin GPIO untuk LED), "freq" (frekuensi dari PWM), "ledChannel" (nomor saluran PWM), dan "resolution" (resolusi bit PWM) diatur sedemikian rupa sesuai dengan perintah jobsheet. Untuk meningkatkan kecerahan LED secara bertahap, digunakan "dutyCycle" dengan nilai dari 0 ke 255, sehingga memberikan efek peningkatan kecerahan dari mati,redup, hingga terang. Begitu pula sebaliknya, untuk mengurangi tingkat kecerahan LED, digunakan "dutyCycle" dengan nilai dari 255 ke 0, sehingga memberikan efek pengurangan kecerahan dari terang, redup, hingga LED mati. Percobaan ini menghasilkan kondisi LED yang menyala perlahan lalu meredup perlahan.

https://github.com/AisyahKusumastuti/Sistem-Embedded-fix/assets/154494434/75a7030e-6d90-4318-b132-25c72c9ce140
