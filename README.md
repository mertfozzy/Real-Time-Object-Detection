![photo](https://github.com/mertfozzy/Real-Time-Object-Detection/blob/main/webcam%20test%202.png?raw=true)
# Real-Time-Object-Detection

---------------------------------------------------T U R K I S H------------------------------------------------------------------

Proje Sahibi: Mert Altuntaş

Proje Tanımı: Bu projenin amacı, nesneleri gerçek zamanlı olarak iyi bir doğrulukla tespit etmektir. Nesneler, web kamerasında canlı olarak kare veya daire içine alınmış bir alanda görünecektir.

Tüm kodlar Mert Altuntaş tarafından yazılmıştır.

Araçlar ve Çerçeveler:
Bu proje için gerekli yazılımlar;
- Programlama dili olarak Python 3.7 (veya üstü)
- Python kütüphanelerini kullanmak için Anaconda Dağıtımları
- Geliştirme ortamı olarak Pycharm Pro veya Spyder
- Nesneleri algılamak için OpenCV kütüphanesi
- Matrisler oluşturmak ve hesaplamalar yapmak için Numpy kütüphanesi
- Proje dosyalarını saklamak ve proje sürümlerini izlemek için Github Öğrenci Geliştirici Paketi.


Gerekli Ekipman:
- Windows 10 veya Linux tabanlı bilgisayar
- Web Kamerası veya Ek Kamera


İşlevsel gereksinimler :
- Öncelikle program bir masaüstü uygulaması olacak.
- Program, bir web kamerasındaki nesneleri algılayacaktır. Kullanıcılar nesneleri kare veya daire içine alınmış bir alanda görebilir.
- Program ayrıca gerçek zamanlı olarak çalışmalıdır. Tüm tespitler canlı olmalı.
- Ayrıca program 80'e yakın farklı nesneyi algılayabilecektir. Veri setim YOLOv3'e dayalı olacaktır.


Eklemeler:
- Program, insan vücudunu, gözleri ve yüzleri içeren nesneleri algılayacaktır.
- Ayrıca program yüzdeki duyguları (gülümsemek gibi) gerçek zamanlı olarak algılayabilecektir.
- Proje bir Kullanıcı Arayüzüne sahip olabilir. (Geliştiriliyor..)


Nasıl Çalışır ?
- https://pjreddie.com/darknet/yolo/ adresinden yolov3-416 paketini indirin.
- Projemizi oluşturalım ; indirdiğimiz dosyayı ve kütüphaneleri dahil edin. (opencv-numpy)
- Anaconda dağıtımından yararlanacaksak conda konsolundan kütüphane indirebilirsiniz. Pycharm üzerinde kütüphaneler kurulabilir.
- Python Interpreter'inizi seçip kodu derleyin. Webcam penceresi açılacak ve deteksiyon başlayacaktır.
- Bu aşamada görüntü donanıma bağlı olarak yavaş olabilir. Programdan çıkış yapmak için "q" harfine basmanız yeterlidir.


-----------------------------------------------------E N G L I S H----------------------------------------------------------------

Project Owner : Mert Altuntaş

Project Description : The aim of this project is to detect the objects in real time with good accuracy. Objects will appear live on webcam in a squared or circled area.

All the datas and codes created by Mert Altuntaş.

Tools and Frameworks :
For this project required softwares are ;
-	Python 3.7 (or above) as programming language
-	Anaconda Distributions to use Python libraries
-	Pycharm Pro and Spyder as a developing environments
-	OpenCV Libraries to detect objects
-	Numpy Libraries to create matrices and making calculations
-	Github Student Developer Pack for keeping project files and tracking project versions.


Required Equipment :
-	Windows 10 or Linux based computer
-	Webcam or Additional Camera


Functional Requirements :
- First of all, the program is a desktop application. 
- The program will detect objects from a webcam. Users can see the objects in a squared or circled area.
- The program also should work in real time. All detections have to be live.
- Also, the program will be able to detect almost 80 different objects. My dataset will be based on YOLOv3.


Additions :
- The program will detect objects, that includes human bodies, eyes and faces.
- Also, the program will be able to detect facial emotions (like smiling) in real time.
- The Project might have a User Interface. (Under Development..)


How does it work ?
- Download yolov3-416 package from this address : https://pjreddie.com/darknet/yolo/.
- Let's create our project; Include the file and libraries we downloaded. (opencv-numpy)
- If you are going to use Anaconda distribution, you can download the library from the conda console. Libraries can be installed on PyCharm.
- Select your Python Interpreter and compile the code. The webcam window will open and the detection will start.
- At this stage, the image may be slow depending on the hardware. To exit the program, simply press the letter "q".
