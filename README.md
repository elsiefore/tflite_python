Steps : 
```
Download https://github.com/anirbanchowdhury/tflite_python/archive/refs/heads/master.zip
Unzip into a directory of choice 
cd <unzipped folder>
pip install -r requirements.txt 
python3 tflite1.py
```


If the installation is successful, this will have the following message (probability, seconds might vary sligtly in the output ):  
```
Model Loaded Successfully.
Will classify images from  ./test/
classifying test/test.jpg
This is a  great white shark , classified with Accuracy : 99.22 %. in  0.06 seconds
classifying test/test.old.jpg
This is a  Egyptian cat , classified with Accuracy : 71.48 %. in  0.056 seconds
classifying test/Screenshot 2023-06-02 at 4.31.51 PM.png
This is a  volcano , classified with Accuracy : 98.44 %. in  0.049 seconds
```

Note : For Python 3.9.x , tflite 2.7.0 (and for earlier versions, we have to downgrade to 2.5.0
