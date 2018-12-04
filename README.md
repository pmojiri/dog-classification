[//]: # (Image References)

[image1]: ./images/file-1.png "Sample Output 1"
[image2]: ./images/file-2.png "Sample Output 2"
[image3]: ./images/file-3.png "Sample Output 3"
[image4]: ./images/file-4.png "Sample Output 4"
[image5]: ./images/file-5.png "Sample Output 5"


## Intoduction

In this project, I have learned how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, my algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  


## Project Instructions

1. Clone the repository and navigate to the downloaded folder.
	
```	
git clone https://github.com/pmojiri/dog-classification-pytorch.git
```
3. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
4. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
5. Make sure you have already installed the necessary Python packages according to the README in the program repository.
6. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
```
jupyter notebook dog_app.ipynb
```

## Results
![Sample Output 1][image1]
![Sample Output 2][image2]
![Sample Output 3][image3]
![Sample Output 4][image4]
![Sample Output 5][image5]
