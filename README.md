# Debiasing-Facial-Detection-Systems
 
In this lab, we'll investigate one [recently published](http://introtodeeplearning.com/AAAI_MitigatingAlgorithmicBias.pdf "Paper") approach to addressing algorithmic bias. We'll build a facial detection model that learns the latent variables underlying face image datasets and uses this to adaptively re-sample the training data, thus mitigating any biases that may be present in order to train a debiased model.

The following picture compares the accuracy on each of "Dark Male", "Dark Female", "Light Male", and "Light Female" demographics being classified as a face using a standard CNN classifier and using our debiased model.

![bias](https://user-images.githubusercontent.com/54194162/158091889-cde11a99-683c-49bd-a4c4-26210af154d7.png)
