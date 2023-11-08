# Person-Detection-using-YOLOV3
Person Detection
**Background** 
- Deteksi manusia merupakan salah hal kemampuan unik dalam bidang Visi Komputer untuk menemukan lokasi objek(manusia) baik dalam gambar maupun video.
- Tujuan dari deteksi manusia adalah untuk mengenali dan memahami keberadaan manusia dalam data visual dan membuat keputusan berdasarkan informasi tersebut.
- Manfaat deteksi manusia diantaranya: penarian criminal, pencarian orang hilang, penelitian biometix,dll
  
**Problem Statement** 
- Masalah yang terjadi adalah bagaimana computer mampu melakukan deteksi manusia dengan akurasi yang paling baik.
- Oleh karena itu diperlukan metode Deep Learning dengan tujuan deteksi orang dengan akurasi yang baik.
  
**Deep Learning Techniques** 
  Algoritma Deep Learning yang digunakan dalam tugas in, yaitu: YOLO dan Faster R-CNN
  
**Dataset** 
- COCO dataset berisi berbagai macam gambar dengan berbagai objek dalam konteks sehari-hari. Dataset ini dikembangkan oleh Microsoft dan berisi lebih dari 200.000 gambar dengan lebih dari 80 kategori objek yang berbeda.
- Data yang digunakan dalam pengujian ini adalah: Coco dataset dengan kelas Person
- Jumlah data yang digunakan 3000 data train dan 500 data Testing 
- Setiap gambar dalam dataset diberikan beberapa anotasi berbentuk bounding box (kotak pembatas) yang menunjukkan lokasi dan ukuran objek-objek yang ada dalam gambar. - 
  Anotasi ini mencakup empat nilai, yaitu koordinat x dan y dari sudut kiri atas kotak pembatas, serta lebar dan tinggi kotak pembatas.
  
**Dataset & Annotation** 
![image](https://github.com/fenchi-riti/Person-Detection-using-YOLOV3/assets/72839436/748c1e00-02e6-45b5-9119-5a30bc3bd8d8)

**YOLOV3** 
- Kecepatan dalam deteksi objek
- Melakukan deteksi objek secara real time
- Single-shoot-detection:  memprediksi bounding box dan class  probabilitas dari sleuruh gambar secara keseluruhan
- Memiliki akurasi prediksi yang baik dengan menggunakan arsitektur Darknet-53  sebagai jaringan backbone untuk ekstraksi fitur

**Training YOLOV3** 
- Ekstraksi Fitur: Arsitektur YOLOv3 menggunakan Darknet-53 sebagai bagian ekstraksi fitur. 
- Prediksi Bounding Box dan probabilitas kelas
- Hasil akhirnya daftar bounding box  dengan label kelas dan skor kepercayaan yang sesuai
**Download YOLOV3** 
Download Weight file: !wget https://pjreddie.com/media/files/yolov3.weights
Download cgf file ![image](https://github.com/fenchi-riti/Person-Detection-using-YOLOV3/assets/72839436/41de9ade-ac60-4b6e-8162-319b8dd9279d)
![image](https://github.com/fenchi-riti/Person-Detection-using-YOLOV3/assets/72839436/d44a528c-e20b-4e1d-8373-851698b49290)
**Result YOLOV3** 
![image](https://github.com/fenchi-riti/Person-Detection-using-YOLOV3/assets/72839436/72ee8fc3-53f7-4daf-94d2-c570c1e276de)
**Performance YOLOV3**
  mAP: 
Inference Latency: 6.0535 seconds
![image](https://github.com/fenchi-riti/Person-Detection-using-YOLOV3/assets/72839436/92f0a1a0-c0fa-4a13-9b3f-65b5bc6fe23a)








  

