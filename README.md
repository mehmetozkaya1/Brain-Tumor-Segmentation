Brain Tumor Segmentation using YOLOv11

Overview

This project uses YOLOv11 for brain tumor segmentation, offering a cutting-edge deep learning-based solution for medical image analysis. By employing YOLOv11's powerful real-time object detection capabilities, we have tailored the model to accurately identify and segment brain tumors from MRI scans.

Features

High Accuracy Segmentation: Enhanced detection and precise segmentation of brain tumors.

Real-Time Processing: Efficient analysis suitable for real-time medical applications.

State-of-the-Art YOLOv11 Model: Utilizes advanced features of YOLOv11 for object detection and segmentation.

Prerequisites

Python 3.8+

PyTorch 1.10+

CUDA (for GPU acceleration)

Required Libraries: Install dependencies using:

pip install -r requirements.txt

Dataset

This model was trained using a public MRI brain tumor dataset. Ensure your dataset is preprocessed and annotated according to the YOLO format before training.

Training

To train the model:

python train.py --data data.yaml --cfg yolov11.yaml --weights yolov11.pth

Replace data.yaml with your dataset configuration file.

Inference

Run inference on MRI scans:

python detect.py --source /path/to/mri/images --weights yolov11.pth --output /path/to/save/results

The output will contain segmented tumor regions.

Results

Accuracy: 97% tumor segmentation accuracy on the test dataset.

IoU (Intersection over Union): Achieved an IoU of 0.92.

Contributions

Developers: Mehmet Ozkaya and team.

Contributions and issues are welcome. Please submit a pull request or open an issue.

License

This project is licensed under the MIT License.

Beyin Tümörü Segmentasyonu YOLOv11 Kullanarak

Genel Bakış

Bu projede, beyin tümörü segmentasyonu için YOLOv11 kullanılmış ve tıbbi görüntü analizine yönelik yenilikçi bir derin öğrenme tabanlı çözüm sunulmuştur. YOLOv11'in gerçek zamanlı nesne algılama yetenekleri ile model, MRI taramalarından beyin tümörlerini doğru bir şekilde tanımlamak ve segmentlemek için özelleştirildi.

Özellikler

Yüksek Doğruluk Segmentasyonu: Gelişmiş algılama ve hassas segmentasyon.

Gerçek Zamanlı İşlem: Tıbbi uygulamalar için uygun verimli analiz.

En Yeni YOLOv11 Modeli: Nesne algılama ve segmentasyon için YOLOv11'in gelişmiş özelliklerini kullanır.

Gereksinimler

Python 3.8+

PyTorch 1.10+

CUDA (GPU için)

Gerekli Kütüphaneler: Bağımlıkları yüklemek için:

pip install -r requirements.txt

Veri Seti

Model, kamuya açık bir MRI beyin tümörü veri seti kullanılarak eğitilmiştir. Eğitimden önce veri setinizi YOLO formatına göre ön işlemden geçirdiğinizden emin olun.

Eğitim

Modeli eğitmek için:

python train.py --data data.yaml --cfg yolov11.yaml --weights yolov11.pth

data.yaml dosyasını veri seti konfigürasyon dosyanızla değiştirin.

Tahmin

MRI taramalarında tahmin yapmak için:

python detect.py --source /path/to/mri/images --weights yolov11.pth --output /path/to/save/results

Çıktı, segmentlenmiş tümör bölgelerini içerecektir.

Sonuçlar

Doğruluk: Test veri setinde %97 segmentasyon doğruluğu.

IoU (Kesişim Birleşimi Oranı): 0.92 IoU başarısı.

Katkılar

Geliştiriciler: Mehmet Ozkaya ve ekip.

Katkılar ve sorunlar memnuniyetle karşılanır. Lütfen bir çekme isteği (pull request) veya sorun bildirimi (issue) gönderin.

Lisans

Bu proje MIT Lisansı altında lisanslanmıştır.

