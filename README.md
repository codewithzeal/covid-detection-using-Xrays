# covid-detection-using-Xrays
### Introduction
This project aims at finiding x-ray image enhancement mehtods for detection of covid using CNN method. In this project I have used methods like CLAHE, Fourier smoothing, Bilateral noise reduction, CLAHE+Fourier smoothing, CLAHE+Denoised and highboost filtering
#### To run the project
Clone the repository and create folders like CovidDataset2, CovidDataset3, CovidDataset4,...,CovidDataset7. You can create more folders if you want based upon combination of image filters you aplly. So for this project I have Orignal dataset, CLAHE(Read images from covidDatset and store them in CovidDataset2), Orignal+Fourier_Smoothing(Read images from covidDatset and store them in CovidDataset3), CLAHE+Fourier smoothing (Read images from covidDatset2 and store them in CovidDataset4) and so one for filters like CLAHE+Bilateral noise reduction, Orignal+Bilateral noise reduction and highboost filtering. Run the models notebook to see the results
#### Image ouputs:
![image](https://user-images.githubusercontent.com/65071320/149150269-6c5a14c0-a622-4e6b-8ac3-f3b100c164d0.png)
![image](https://user-images.githubusercontent.com/65071320/149150327-a3433007-e639-4bf7-b18e-ed8f950a5312.png)
### Result
![image](https://user-images.githubusercontent.com/65071320/149150440-3cb281b9-e206-4668-9fbb-d834c5c18571.png)
### Conclusion 
#### It was found that CLAHE+Bilateral noise reduction worked the best
