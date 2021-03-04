## Number place detection using Region-based CNN (RCNN) and Keras

### Execute Below commands in sequence to run:

#### 1. Download Number plate training images:
```shell
python3 generate_data.py
```

#### 2. Train Model:
```shell
python3 train_base_model.py
```

#### 2. Perform detection using trained model:
```shell
python3 rcnn.py
```
