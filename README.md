Our project aims to detect Dyslexia which is a neurological disorder .It is a language - based learning disability. The affected individuals have difficulties with reading, writing, speaking and spellings. Researchers have proposed a wide range of techniques to detect dyslexia at an early stage which includes game-based techniques, reading and writing tests, facial image capture and analysis, eye tracking, Magnetic Resonance Imaging and Electroencephalography scans .We designed a model using the eye tracking dataset and used unsupervised learning approach.  We used the eye tracking dataset that contains two groups: control and dyslexic. The data consisted of 98 dyslexic candidates and 88 non-dyslexic or control candidates. Since the reading speed varies from person to person the samples had varying lengths, so we tried two methods to tackle this problem:
Method 1: Binning on Spectral Data to obtain equal length vectors that encapsulate all temporal information. Binnig allows to encapsulate temporal information from the eye tracking data into discrete intervals or bins.
Method 2: Short-Time Fourier Transform (STFT) with Binning on Temporal Data. Approach involves applying STFT first and then binning the resulting time-frequency representation. Then perceptron is used as a classifier to learn decision boundary. 
