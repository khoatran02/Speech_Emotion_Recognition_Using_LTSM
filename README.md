# Speech_Emotion_Recognition_Using_LTSM.ipynb
This is my project scientific research. I had used filter MFCC for extract featuer and used LSTM model for train data.<br>
What is MFCC?<br>
In sound processing, the mel-frequency cepstrum (MFC) is a representation of the short-term power spectrum of a sound, based on a linear cosine transform of a log power spectrum on a nonlinear mel scale of frequency.<br>

Mel-frequency cepstral coefficients (MFCCs) are coefficients that collectively make up an MFC.[1] They are derived from a type of cepstral representation of the audio clip (a nonlinear "spectrum-of-a-spectrum"). The difference between the cepstrum and the mel-frequency cepstrum is that in the MFC, the frequency bands are equally spaced on the mel scale, which approximates the human auditory system's response more closely than the linearly-spaced frequency bands used in the normal spectrum. This frequency warping can allow for better representation of sound, for example, in audio compression that might potentially reduce the transmission bandwidth and the storage requirements of audio signals.<br>

My model:<br>
![image](https://user-images.githubusercontent.com/86609606/191217118-38d7a007-f7aa-41a5-b963-b75b0bfb0a3b.png)<br>
My result:<br>
+ Accuracy:<br>
![image](https://user-images.githubusercontent.com/86609606/191216238-d0514f60-ccb5-4f8e-add7-094be9c67757.png)
+ Loss:<br>
![image](https://user-images.githubusercontent.com/86609606/191216590-347e6816-0e5f-4332-8050-5f7c8fee998a.png)
+ Evaluate train:<br>
![image](https://user-images.githubusercontent.com/86609606/191217272-1c83fab9-14e3-471a-a78a-abbfa817346c.png)
+ Evaluate test:<br>
![image](https://user-images.githubusercontent.com/86609606/191216831-b3bc2628-ef1c-4dd2-853e-4a37a138a00c.png)<br>
Link dataset my used: https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess <br>
More dataset:<br>
+https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio<br>
+https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee<br>
+https://www.kaggle.com/datasets/ejlok1/cremad<br>

