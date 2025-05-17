# Langkah-Langkah Upload Project ke GitHub Lewat Terminal (Bahasa Manusia)

1. *Masuk ke folder project*  
   Aku pindah ke folder project yang namanya kuliah_pbo.

   ```bash
   cd /root/perkuliahan/kuliah_pbo
   ```

2. *Aktifkan Git*
   ```bash
   git init
   ```

3. *Tambahkan semua file*
   ```bash
   git add .
   ```

4. *Commit perubahan*
   ```bash
   git commit -m "pbo"
   ```

5. *Ganti nama branch ke main*
   ```bash
   git branch -M main
   ```

6. *Hubungkan ke GitHub*
   ```bash
   git remote add origin git@github.com:UltramanDana/kuliah_pbo.git
   ```

7. *Kirim ke GitHub*
   ```bash
   git push -u origin main
   ```

8. *Bikin file & folder tambahan*
   ```bash
   mkdir perti
   touch Catatan.md
   ```

9. *Buka di VS Code*
   ```bash
   code .
   ```