Read Me:


EMOTION RECOGNITION IN AUTISTIC CHILDREN


This project  is mainly focused to help children suffering from ASD .
We’ve considered 5 types of feelings : 
* Angry 0
* Fear 1
* Happy 2
* Neutral 3
* Sad 4
As it is very difficult to guess what an autistic child is feeling because they are less expressive and socialistic. We aim to predict the feeling of a child with the help of deep learning and image processing .
We were inclined towards CNN for training our dataset. 
________________________________________________________________________________________________________________________________
Installation:-
Prerequisites :
Anaconda jupyter notebook with python or any other similar kind of platform in order to run the program.


For installation 
1. Python :- 
In Ubuntu :- 
sudo apt install python3.8


In Windows 
Download the executable file and run it .


2. Anaconda / Jupyter Notebook :
In Ubuntu 
https://docs.anaconda.com/anaconda/install/linux/ 


In Windows
https://docs.anaconda.com/anaconda/install/windows/




3. Install Keras Library 
In Ubuntu 
conda  activate
conda install -c conda-forge keras


In Windows
Open anaconda Terminal
conda install -c conda-forge keras


4. Install livelissplot for plotting 
In Ubuntu
        conda activate
        pip install livelossplot
        
        In Windows 
        Open anaconda terminal
        pip install livelossplot


Specific Downloads Requirements - 
Python 3.8 or above (recommended) 


How To Run:- 
1. Open jupyter notebook and navigate to the folder where you’ve stored the project. 
2. In Emotionsreg_master file open “Facial_emo_recog_group_5-Final.ipynb” in jupyter notebook 
3. Go to ” add path “ section and change the paths according to your saved directory. 
4. Run all the blocks eventually you will see validation accuracy up to 69-71 %