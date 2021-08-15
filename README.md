# NLU_Project_2020-21_UniTrento
*Repo for the final project for NLU course 2020-21 at UniTrento.*



**STUDENT:** Francesco Trono - Student no.: 221723

**Software requirements:** 

The code has been developed and executed on Google Colaboratory in the form of a Jupyter notebook and trained on a remote GPU. The code is written in Python and makes use of the following libraries:

* **Tensorflow**: https://www.tensorflow.org/
* **Keras**: https://keras.io/
* **NumPy**: https://numpy.org/
* **Matplotlib**: https://matplotlib.org/


**Ready for execution:** 

The model submitted is a GRU RNN, which I have trained during the implementation. The weights calculated during the training are provided in the *./Output* directory. The code can be readily tested and evaluated by setting the toggle *"pretrained = **True**"* in the .ipynb file, which tells Colab to load the provided weights instead of having to train the model again.**


**Repo structure:**

This Github repository mirrors exactly the directory structure used in Google Drive and must be respected in order to successfully run the code:
* **"Code" directory:** contains the .ipynb Colab notebook with the entire code and std output prints.
* **"Output" directory:** contains a .png graph of the model structure, obtained through Keras *plot_model* utility, and the set of weights saved after the training.
* **"Src" directory:** contains the 3 word-level dataset files *ptb.(train | valid | test).txt* from the Penn Treebank dataset. The dataset has been downloaded from the official website https://deepai.org/dataset/penn-treebank 
* **"Report" directory:** contains the project PDF report.
