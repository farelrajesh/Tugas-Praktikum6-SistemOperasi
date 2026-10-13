# Tugas-Praktikum6-SistemOperasi
Praktikum Sistem Operasi 10/13/2026
1. Eksekusi seluruh profile yang ada :

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :

<img width="662" height="492" alt="image" src="https://github.com/user-attachments/assets/6fe6b09b-1def-401f-87b0-13b5ea3a8a58" />

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu 

<img width="936" height="753" alt="image" src="https://github.com/user-attachments/assets/8f91cc46-8441-4f7c-b6dc-f012998f8678" />

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut

<img width="807" height="628" alt="image" src="https://github.com/user-attachments/assets/6ee1545f-4d85-4e32-ae5e-14a48be1c045" />

2. Prompt String (PS)


a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal
oleh semua shell

<img width="682" height="517" alt="image" src="https://github.com/user-attachments/assets/78cffbef-100e-49b0-a84c-c9fab2538a8d" />

b. Eksperimen hasil PS1 :

<img width="663" height="512" alt="image" src="https://github.com/user-attachments/assets/9efd4f97-78ca-4815-b7d4-6bd6fffc3585" />


3.Logout Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout

<img width="820" height="700" alt="image" src="https://github.com/user-attachments/assets/a5462397-148f-4eb5-95d6-ef26c4864670" />

4. Bash script

a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing:

<img width="638" height="497" alt="image" src="https://github.com/user-attachments/assets/a40d91b5-675e-48ba-8249-bdd625c757f4" />

b. Jalankan script tersebut sebagai berikut:

<img width="651" height="491" alt="image" src="https://github.com/user-attachments/assets/ab560253-2a22-422f-a2a9-9b2e47518c5d" />

5. Jobs

a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.

<img width="652" height="506" alt="image" src="https://github.com/user-attachments/assets/a675c45e-fb0d-4082-a0a0-f4135aa02023" />

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) dibackground sebagai berikut :

<img width="652" height="497" alt="image" src="https://github.com/user-attachments/assets/aa4c4c3b-9dee-493c-af1a-7cbc358bc75d" />

c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background


<img width="652" height="493" alt="image" src="https://github.com/user-attachments/assets/cec13d05-fdc8-499f-9140-ded1f1e92944" />


d. Menghentikan program menggunakan kill

<img width="526" height="397" alt="image" src="https://github.com/user-attachments/assets/6897786d-2a95-41e9-907c-5f24c4569d5f" />


6. HISTORY

a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="720" height="517" alt="image" src="https://github.com/user-attachments/assets/57bb7303-38bb-417c-b172-d37ea4609dba" />

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan

<img width="646" height="495" alt="image" src="https://github.com/user-attachments/assets/15378769-633c-458d-8355-053b9bea883f" />


c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer

<img width="640" height="497" alt="image" src="https://github.com/user-attachments/assets/7dc29d2e-4838-4069-bde3-409ba680246f" />


d. Ulangi instruksi pada history bufer nomor 150

<img width="652" height="491" alt="image" src="https://github.com/user-attachments/assets/8ff219dd-9211-4aa0-9d8f-35b54cf71065" />

e. Ulangi instruksi dengan prefix “ls”

<img width="671" height="497" alt="image" src="https://github.com/user-attachments/assets/5178eb35-8e27-4d35-80d4-355eb53a8c6b" />
