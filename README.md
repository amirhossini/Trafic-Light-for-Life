# Trafic-Light-for-Life (SAS Hackathon 2021)

A data for good project accepted for participation in Global HackinSAS 2021. Below are the highlights of the project, followed by technical details and model execution instructions:
- __The central idea:__ intersection management through audio sensing to prioritize emergency vehicles (please see the submission here: https://communities.sas.com/t5/Hacker-s-Hub-library/Traffic-Lights-for-Life-audio-based-intersection-management-for/ta-p/716595)
- __Raspberry Pi Project:__ Bi-directional set-up hosted by Azure IoT Hub
- __Artificial Intelligence:__ Application of CNN & LSTM (with 5 sec Audio Chunks) & CNN (with Spectrograms) for binary classification of emergency vs. non-emergency vehicles
- __Validation Dataset:__ 4:00 minutes of audio data including both emeregncy and non-emergency vehicles, as shown below: <br> 
     Audio: https://github.com/amirhossini/Trafic-Light-for-Life/blob/main/data/validation.wav <br>
     Time-series: <br> ![image](https://user-images.githubusercontent.com/63076229/109926219-f222f480-7c7f-11eb-8c2b-96154b5de0d8.png) <br>
     Spectrogram: <br> ![image](https://user-images.githubusercontent.com/63076229/112779376-dbb05480-9003-11eb-91ea-61ae9486e4f7.png) <br>





