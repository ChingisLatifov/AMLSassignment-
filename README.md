# AMLSassignment-

## File organization
To organize the files required to the code, the following requirements must be submitted.

1)The main code "Tasks.ipynb" must be located in the same folder as the "attributes_list.csv"

2)The folder containing training and testing images (dataset) must be located in the same folder as "Tasks.ipynb"

3)The dataset folder must have exactly 5000 png images, named in the same way as the provided ones. ((1,2,3 ... ).png)

4)The Github does not allow to upload all 5000 images. Therefore it can be downloaded from https://drive.google.com/drive/folders/1NgP2jQakFHibIhpevDLshodWw-L52yXi 

5)The testin dataset folder must be located in the same folder as "Tasks.ipynb"

## Library download
To run the code, it is required to install all the libraries specified in the first block of the "Tasks.ipynb" notebook

1)To download the libraries Anaconda Navigator must be installed

2)It is required to create a new virtual environment in Anaconda, as the dlib library cannot be installed to the base environment

3)All the libraries, except dlib, can be found and downloaded through the Anaconda search line in the Environments section

4)To install the dlib libraries, the instructions from the following link must be followed https://www.learnopencv.com/install-opencv-3-and-dlib-on-windows-python-only/

## Running the code
To run the code the Jupyter notebook must be installed and launced. It can be done from the Anaconda home section

1)In the image extraction section of the notebook, the variables imgs_dir, images_dir must contain path to the used dataset folder. Currently, it is set to be "C:/Users/ching/Desktop/Assignment/dataset/"

2)attribute_list_filename must not be changed, unless the name of the file "attribute_list" is changed

3)The code mus be run block by block from the beginning.

4)In the "ML Models creation. Definition of the automatic hyperparameters tuning functions" section of the code, the tasks 1-4 must be run before the task 5, because in task 5 additional image objects, which are used in training and testing for other tasks, are deleted (labeled wrong)

5)In the "Image class definition and the remove of the noise data" section, the part, which deletes the noise images from the dataset folder is commenter. It can be uncommented to make the code able to delete the noise images from the PC. However, the images must be downloaded back in case of running the code again from the beginning

6)The code will automatically create the final csv file and will save them in the same folder as the "Tasks.ipynb".

7)The details of all parameters used in the code are explained in the notebook's comments in more detail.
