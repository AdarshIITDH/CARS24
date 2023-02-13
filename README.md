# CARS24 - MLOPS - Assignment


## Demo

![Demo screenshot](/static/imgs/demo.png?raw=true "Demo")

## Running

**Option1:** Clone repository, go to the specified folder and run
 ```
 python application.py
 ```
 ```
  * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 ```
 Open your browser and access the address http://127.0.0.1:5000/ .

**Option2 :** Use the DOCKERFILE to build the containerised application.
Run the below commond inside the directory.
```
docker build -t cars24:01 .
```
```
docker run -it -p 5000:5000 cars24:01
```
Open your browser and access the address http://192.168.100.99:5000/ . (Use ip of your host machine with port 5000)


## Requirements
```
pip3 install -r requirement.txt
```
or

To install required libraries, use commands below:
```
pip install flask
pip install opencv-python
pip install numpy

```


## Training
If you want to try another MLP architecture, edit *train.py* and run
```
python train.py
```
for pytorch model training and data downloading
```
python training_pt.py
```

## Contact
If you have any further questions or suggestions, please, do not hesitate to contact by email at aadarsh307kumar@gmail.com.

