# ConvertImageMNIST-format
A simple method to convert your .jpg or .png images to MNIST format for training your data and save the file in .CSV format.

#### MNIST Format
> The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems.

MNIST format is a 28x28 pixel frame where fitting image into, which introduced grayscale one.  :black_medium_square:
![handwritting digits](https://github.com/MohammedShalan/ConverImageMNIST-format/blob/master/screenshots/MnistExamples.png)
You can check out [The Arabic Handwritten Digits Databases here :heart:](http://datacenter.aucegypt.edu/shazeem/)
![arabic handwriting digits](https://github.com/MohammedShalan/ConverImageMNIST-format/blob/master/screenshots/arabic.jpg)

#### How to use file
1. Determine the images path
![images list](https://github.com/MohammedShalan/ConverImageMNIST-format/blob/master/screenshots/1.png)

```python
FileList = []
for filename in os.listdir('<Images-path>'):
    if filename.endswith(".bmp"):
        FileList.append(filename)
```
2. Save file in csv format 
```python
	toCSV("<filename>",data_format)
```

####Dependencies:
```
pip install numpy
pip install matplotlib
pip install jupyter
```

