## Run from Scratch
- First, download Python from here: https://www.python.org/downloads/windows/  
- Then, download get-pip.py from https://bootstrap.pypa.io/ \
`$ cd /path/to/downloadsfolder` \
`$ python get-pip.py` 
- Install Git from here: https://gitforwindows.org/ 
- Install requirements \
`$ pip install -U -r requirements.txt` 
- At this point, you have to be able to run the neural network \
`$ python ann.py`  

## Included Files ##
- ann.py
- Churn_Modelling.csv
- model.json
- model.h5
- requirements.txt
- README.md
- group1-shard1of1.bin (Keras model is converted to Tensorflow layers so that it could be imported and run on a web browser.)

The command is first 
`$ pip install tensorflowjs` \
Then,
`$ tensorflowjs_converter --input_format keras` \
                       `path/to/my_model.h5` \
                       `path/to/tfjs_target_dir`
