# Biometric Sytem for Iris Recognition

Abstract: This project intends to identify humans by they iris using techniques of image processing. Given an image of eyes, return a validation of those eyes.

Requirements:

```
matplotlib=3.5.3=pypi_0
matplotlib-inline=0.1.6=pypi_0
numpy=1.23.2=pypi_0
opencv-python=4.6.0.66=pypi_0
scikit-image=0.22.0=pypi_0
scikit-learn=1.4.2=pypi_0
scipy=1.9.1=pypi_0
```

Install the dependencies with

```pip install -r requirements.txt```

 It's necessary to have opencv installed (or in a virtual enviroment)
 
 ## Various ways to compare

There are 3 broad comparing techniques used: Norm distance (less implies closer), Hamming Distance (less implies closer) and Consine similarity (more implies closer). There is also an option to have lfsr encryption or not. So, in total, there are 6 possibilities to run the code:

| Description | Filename |
| ------ | ------ |
| Norm without lfsr | main.py |
| Norm with lfse | [main_lfsr.py |
| Hamming distance without lfsr | main2.py |
| Hamming distance with lfsr | main2_lfsr.py |
| Cosine Similarity without lfsr | main3.py |
| Cosine Similarity with lfsr | main3_lfsr.py |
| Lfsr code (standalone) | lfsr.py


To run the code with norm as the distance without lfsr encryption, use the following command:

```python main.py  <path_to_directory>```
