# Crop Foto Dari KTP Menggunakan OpenCV

- read image
- Convert Ke Graysclae
- Apply Threshold Otsu
- find Contour
- filter contour yang terlalu kecil atau besar
- cari 4 coordinate box pada contour terbaik
- lakukan perspective transform dari original image ke 4 coordinate yang didapatkan sebelumnya
- show image


### Hasil pengetesan

![](https://raw.githubusercontent.com/Muhammad-Yunus/OpenCV-Crop-Foto-KTP/master/resource/Capture.PNG)
