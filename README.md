# Tugas6SistemOperasi_09011282328108
## 1. Eksekusi seluruh profile yang ada :
## a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”
![SOO1](https://github.com/user-attachments/assets/b3135da3-3916-4316-9270-67c333691255)
![SOO2](https://github.com/user-attachments/assets/0a7f528a-124b-4b2f-8ff6-538e9227fe38)
## b. Edit semua profile yang terkait dengan user, buat file dan edit file tersebut.  Pada setiap file tersebut, cantumkan instruksi echo
![SOO4](https://github.com/user-attachments/assets/be159570-2756-4415-952c-bf6a16bf458a)
![SOO3](https://github.com/user-attachments/assets/7fb6ccc0-6f26-4cf8-a57b-bba3eaefef00)
![SOO5](https://github.com/user-attachments/assets/64a4a51c-b8ed-4019-8f74-cf8c746f4533)
![SOO6](https://github.com/user-attachments/assets/f82364ce-2fc3-4068-b831-6c37da652bd8)
![SOO66](https://github.com/user-attachments/assets/c4b0c64c-e335-46a3-81d4-2ecd098fed15)
![SOO7](https://github.com/user-attachments/assets/10e93f8c-8c1d-48f7-a99c-2978f18afabc)
## c. Jalankan instruksi substitute user (su), keluar, lalu jalankan substitusi user dengan opsi -:, lalu keluar
![SOO8](https://github.com/user-attachments/assets/52287bd3-404d-4efe-b6a1-403e3d7305f1)
![SOO9](https://github.com/user-attachments/assets/5fc0e26d-c568-4770-9ea6-cde101f31d83)
## 2. Prompt String (PS)
## Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell PS1=‟> „ export PS1
![SOO10](https://github.com/user-attachments/assets/28af4dfd-ef57-4b23-aee7-2006d043246c)
![SOO11](https://github.com/user-attachments/assets/2ecf4eca-10a0-4913-b9a7-f966837ae973)
## 3. Logout Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout Echo “Terima kasih atas sesi yang diberikan” Sleep 5 clear
![SOO12](https://github.com/user-attachments/assets/f04a1854-65bc-494e-b207-857745548209)
![SOO13](https://github.com/user-attachments/assets/aec79535-fe03-4974-8db0-02d066fc7fa4)
## 4. Bash script
## a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : 
![SOO114](https://github.com/user-attachments/assets/77a220b6-266b-43c2-ae94-756db9ba723b)

![SOO14](https://github.com/user-attachments/assets/5e2f0ac0-4c5d-4a53-af27-6d46022c7bd8)

![SOO15](https://github.com/user-attachments/assets/371df70d-c002-4ba5-91e0-d8342b56da94)

![SOO16](https://github.com/user-attachments/assets/249f2c37-1654-498d-8e3f-28875f26c372)
## b. Jalankan script tersebut sebagai berikut :
![SOO17](https://github.com/user-attachments/assets/25d6ac94-8885-481f-ac6d-431247e4ecd7)
![SOO18](https://github.com/user-attachments/assets/0ceccd55-577c-400c-83b9-aa3a8e08baeb)
![SOO19](https://github.com/user-attachments/assets/ed36df7c-4eef-4d19-a01b-3d5703e0163d)
![SOO20](https://github.com/user-attachments/assets/cf7843c9-12ac-4b77-8e83-ef85c0dcfc52)
![SOO21](https://github.com/user-attachments/assets/82a2d568-43f8-48f2-9faf-58b4b3668e01)
![SOO22](https://github.com/user-attachments/assets/e704a6ce-34e8-4ef8-b9b0-ad5ba3c6cb9e)
## 5. Jobs
## a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil. 
![SOO23](https://github.com/user-attachments/assets/61429e85-5407-42ca-8e69-8af5c74ff514)
## b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut : $ jobs $ find / -print > files 2>/dev/null & $ jobs
![SOO24](https://github.com/user-attachments/assets/6763abbe-aacf-4a46-8ba9-deb6e82c64f2)
![SOO25](https://github.com/user-attachments/assets/e2b81bd8-a9ae-4826-8b96-46e9263eb13b)
![SOO26](https://github.com/user-attachments/assets/7882dae6-6be9-42cc-90b5-4090d96e331b)
## c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background $ fg %1 $ bg
![SOO27](https://github.com/user-attachments/assets/85657fa2-5a89-4879-91b5-25ddca555b7d)
![SOO28](https://github.com/user-attachments/assets/44ec60c5-8935-4841-bc97-1e67410489b1)
## d. Stop program background dengan utilitas kil 
![SOO29](https://github.com/user-attachments/assets/76650bbc-42e0-40a9-b36a-8e6e03c34b20)
![SOO30](https://github.com/user-attachments/assets/43bad944-54f6-4af1-a743-8a81812aa5e8)
## 6. History
## a. Ganti nilai HISTSIZE dari 1000 menjadi 20 
![SOO31](https://github.com/user-attachments/assets/6b9d4a4c-960d-4aef-936b-d636f1828482)
## b.Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan 
![SOO32](https://github.com/user-attachments/assets/77523300-eb3b-44c1-99a7-ca297afa98a4)
## c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer 
## d. Ulangi instruksi pada history bufer nomor 150 
![SOO33](https://github.com/user-attachments/assets/412d68ea-0a18-4fa2-a613-1de9e6827a0c)
## e. Ulangi instruksi dengan prefix “ls” 
![SOO34](https://github.com/user-attachments/assets/716519c4-8f6d-4081-a27e-7a63489129d0)





