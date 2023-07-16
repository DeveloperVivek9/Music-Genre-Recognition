## MGR
Music Genre Recognition using Convolutional Neural Network.  
### Input :
- Dataset directory containing folders equal to the number of classes
- csv file [Path, Filename, Genre]  
### Output :
- saved model at given directory

### Workflow : 
Reads mp3/wav file -> Data Augmentation if required ->  extracts mfcc -> split into training/validation/testing memory map files ->   creates tf dataset based on those files -> trains the CNN model -> saves the model
