#Deep Learning Project - Team 22

##STEPS:
1. Place data in data folder
2. To run the Roadmap layout generation
    ```cd ./Roadmap
       python main.py --data_dir='../data' --batch_size=4 --epochs=10 
    ```
   The model is saved in ./Models folder. The images generated from the validation set is stored in TestImages folder. Tensorflow logging is saved in runs folder
    
3. To run Bounding box detection
   ``` cd ./BoundingBoxDetection
       python main.py --model='/path/to/pretrained model' --data_dir='../data' 
   ```
   The model is saved in ./Models folder. Tensorflow logging is saved in runs folder
