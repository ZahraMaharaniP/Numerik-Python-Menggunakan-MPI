# Numerik-Python-Menggunakan-MPI
Menjelaskan bagaimana eksekusi numerik python pada MPI Cluster melalui Ubuntu Desktop.

# Topologi MPI Cluster
![topologi](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/65d57d2b-a68b-4418-9769-2f960c071e97)

# 1. New User
## 1.1 Buat User
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/9f05683e-3901-4a60-a1ea-8feb955cac66)

## 1.2 Berik Akses Root
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/c3df99b5-a844-4967-9ad5-4f014fc847d3)

## 1.2 Login ke User yang Dibuat
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/b32d2dd8-9864-4200-9011-4c85a3433c09)

# 2. Buat File 
## 2.1 Buat File pada User Menggunakan Perintah
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/bffc3427-755d-42df-bd6e-0ca2982aee2b)

## 2.2 Edit File
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/a339cdc1-77fd-4ea2-882c-986fc7cf6727)

## 2.3 Masukkan Program numerik.py kedalam File yang Sudah Dibuat
![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/65c09fe8-9101-4a63-86d0-6847726690d0)

# 3. Perbedaan Waktu Eksekusi pada Multinode dan SingleNode
## 3.1 MultiNode
`mpiexec -n 1 -host master,worker1,worker2 python3 numerik.py`

![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/b44fc586-04e2-4bb7-ae75-f2c5400e9754)

## 3.2 SingleNode
python3 numerik.py

![image](https://github.com/ZahraMaharaniP/Numerik-Python-Menggunakan-MPI/assets/149281915/7d44bae3-4bb3-4a2e-9f3e-9a0cb080a261)
