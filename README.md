# Convolutional LSTM Model For Speech Emotion Recognition

## -EN-

Speech emotion recognition (SER) is the task of recognizing emotions from speech signals. While people are capable of performing this task efficiently as a natural aspect of speech communication, it is still a work in progress to automate it using programmable devices. Speech emotion recognition plays an important role in the development of human-computer interaction since adding emotions to machines makes them appear and act in a human-like manner. Various SER techniques have been developed over the last few decades, but the problem has not yet been completely solved. This paper proposes a speech emotion recognition technique based on the hybrid of two deep learning architectures namely Convolutional Neural Network (CNN) and Long Short Term Memory (LSTM). Deep CNN has demonstrated its effectiveness in local feature selection, whereas LSTM has shown great success in the sequential processing of large texts. The proposed Convolutional LSTM (Co-LSTM) approach aims to create an efficient automatic method of emotion detection in human-machine communication. In the suggested method, Mel Frequency Cepstral Coefficient (MFCC) is used to extract a matrix of spectral features from the speech signal and afterward is converted to 1-dimensional (1D) array. Then, Co-LSTM is employed as a feature selection and classification method to learn the model for emotion recognition. The experimental analyses were carried out on the classification of all the eight emotions of the speech from RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) and TESS (Toronto Emotional Speech Set) databases. An accuracy of 86.7% was achieved with Co-LSTM using MFCC Spectrogram features. The obtained results convincingly prove the effectiveness of the proposed algorithm when compared to the previous works and other well-known classifiers.


## -TR-

Konuşmada duygu tanıma İngilizce adıyla Speech emotion recognition (SER), duyguların konuşma sinyalleri aracılığıyla tanınması işlemidir. İnsanlar, iletişiminin doğal bir parçası olarak bu işlemi verimli bir şekilde yerine getirebilse de programlanabilir cihazlar kullanarak duygu tanıma işlemi hali hazırda devam eden bir çalışma alanıdır. Makinelerin de duyguları algılaması, onların insan gibi görünmesini ve davranmasını sağlayacağından dolayı, konuşmada duygu tanıma, insan-bilgisayar etkileşiminin gelişmesinde önemli bir rol oynar. Geçtiğimiz on yıl içerisinde çeşitli SER teknikleri geliştirilmiştir, ancak sorun henüz tam olarak çözülmemiştir. Bu makale, Evrişimsel Sinir Ağı (Convolutional neural networks -CNN) ve Uzun-Kısa Süreli Bellek (Long Short Term Memory-LSTM) olmak üzere iki derin öğrenme mimarisinin birleşimine dayanan bir konuşmada duygu tanıma tekniği önermektedir. CNN lokal öznitelik seçiminde etkinliğini gösterirken, LSTM büyük metinlerin sıralı işlenmesinde büyük başarı göstermiştir. Önerilen Evrişimsel LSTM (Convolutional LSTM – Co-LSTM) yaklaşımı, insan-makine iletişiminde etkili bir otomatik duygu algılama yöntemi oluşturmayı amaçlamaktadır. İlk olarak, Mel Frekansı Kepstrum Katsayıları (Mel Frequency Cepstral Coefficient- MFCC) kullanılarak önerilen yöntemde konuşma sinyalinden bir görüntüsel öznitelikler matrisi çıkarılır ve ardından bu matris bir boyuta indigenir. Sonrasında modelin eğitimi için öznitelik seçme ve sınıflandırma yöntemi olarak Co-LSTM kullanılır. Deneysel analizler, konuşmanın sekiz duygusunun tamamının RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) ve TESS (Toronto Emotional Speech Set) veri tabanlarından sınıflandırılması üzerine yapılmıştır. MFCC Spektrogram öznitelikleri kullanılarak Co-LSTM ile %86,7 doğruluk oranı elde edilmiştir. Elde edilen sonuçlar, önceki çalışmalar ve diğer iyi bilinen sınıflandırıcılarla karşılaştırıldığında önerilen algoritmanın etkinliğini ikna edici bir şekilde kanıtlamaktadır.


## -Guide-

CreateModels.ipynb -> The file which I've created the models

Audio_Speech_Actors_01-24 -> The folder about the datasets

GUI -> I've made a GUI for this project with PyQT5 also, and that's the folder about GUI codes

Models -> The folder contains the deep learning models which I've created in this project

images -> Just for accuracy and loss images about my CoLSTM model 

## -GUI-

![1](https://user-images.githubusercontent.com/36486345/134703621-42cb61d3-7a48-4fca-8700-09b653f3c23c.png)

![2](https://user-images.githubusercontent.com/36486345/134703632-b9021d6a-0cc2-49de-8902-700036a6c0db.png)

![3](https://user-images.githubusercontent.com/36486345/134703645-ec15d05a-f852-477f-b634-427ee5d8c3b7.png)

