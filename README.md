## Simple Time Sharing System Using C Programming
# Project Description
Program ini merupakan simulasi sederhana dari sistem time-sharing pada sistem operasi. Program ini dibuat menggunakan bahasa C dan dijalankan pada lingkungan Linux. Melalui program ini, beberapa proses dapat berjalan secara bergantian dengan pembagian waktu CPU menggunakan mekanisme process scheduling. 

# Objectives
- Mensimulasikan mekanisme time-sharing pada sistem operasi

- Memahami konsep process scheduling dan multitasking

- Mengimplementasikan algoritma Round Robin secara sederhana

- Menggunakan fork, signal, dan timer pada sistem Linux

# Concept
Program ini mengimplementasikan beberapa konsep utama dalam sistem operasi, yaitu:

- Process Creation menggunakan fork()

- Process Control menggunakan SIGSTOP dan SIGCONT

- Timer Interrupt menggunakan SIGALRM

- CPU Scheduling dengan algoritma Round Robin

- Time-Sharing System

# Tools & Environment
- Operating System: Ubuntu Linux (Virtual Machine)

- Virtualization: Oracle VirtualBox

- Programming Language: C

- Compiler: GCC

# Program Flow
1. Parent process membuat beberapa child process menggunakan fork()

2. Semua child process dihentikan sementara

3. Timer diatur untuk aktif setiap 1 detik

4. Scheduler akan menghentikan proses yang sedang berjalan

5. Scheduler melanjutkan proses berikutnya secara bergantian

6. Proses berjalan terus dengan konsep time-sharing

# How to Compile & Run
1. Gunakan perintah "gcc -o timeshare timeshare.c" di terminal Linux

2. Setelah dikompilasi, jalankan program dengan perintah "./timeshare"

3. Untuk menghentikan program, tekan CTRL + C

# Conclusion
Program ini berhasil mensimulasikan sistem time-sharing menggunakan bahasa C pada lingkungan Linux. Dengan penerapan fork, signal, dan timer, konsep CPU scheduling dan multitasking pada sistem operasi dapat dipahami dengan baik. 

# Group 7 Operating Systems BINUS UNIVERSITY
- Meghan Hillary Mardjohan - 2702223443

- Jason Emanuel Halim - 2702242410

- Kayla Aurelia Susanto - 2702241074