# Penjelasan
***

## Penjelasan File
1. **naiveBayes.ipynb** 	: file coding
2. **dataTesting.csv**		: file data yang digunakan untuk testing metode
3. **MOCK_DATA.csv**	: file data yang akan di prediksi menggunakan naïve bayes

4. **Lulus.csv**		: referensi dataset sebagai indikator kelulusan yang digunakan untuk membuat data testing (dataTesting.csv)
***

## Langkah run program
1.	Pastikan perangkat sudah terinstall pip, lakukan pengecekan dengan cara membuka Command Prompt atau win + R, lalu jalankan:
```
pip -V
or
pip --version
```

2.	Jika muncul seperti gambar dibawah maka pip sudah terinstall
![Version pip](/version_pip.jpg)

3.	Jika belum terinstall, lakukan penginstallan dapat melihat [Cara Install pip](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/#:~:text=Step%201%3A%20Download%20the%20get,where%20the%20above%20file%20exists.&text=Step%204%3A%20Now%20wait%20through,Voila)

4.	Pastikan semua package yang dibutuhkan terinstall, package yang dibutuhkan:
    1)	Pandas
    2)	Numpy
    3)	Sklearn 
    
5.	Jika belum terinstall maka jalankan kode berikut secara satu persatu pada cmd atau Command Prompt
```
pip install pandas
```

```
pip install numpy
```

```
pip install -U scikit-learn
```

6.	Jalankan kode program pada file naiveBayes.ipynb satu persatu berurutan dari baris teratas
