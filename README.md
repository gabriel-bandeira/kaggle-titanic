## Kaggle Titanic tests ##
Kaggle Titanic competition website: https://www.kaggle.com/c/titanic


To run the python scripts, you must first install the dependencies:
sudo apt-get install git -y
sudo apt-get install python-pandas -y
sudo apt-get install build-essential python-dev python-setuptools \
                     python-numpy python-scipy \
                     libatlas-dev libatlas3gf-base
pip install --user --install-option="--prefix=" -U scikit-learn
but, since the --install-option="--prefix=" flag is only required if Python has a distutils.cfg configuration with a predefined prefix= entry, you may only need
pip install --user -U scikit-learn


You can also check the originals tutorials:
	Install dependencies:
		Pandas - http://pandas.pydata.org/pandas-docs/stable/install.html
		scikit-learn 18.1 - http://scikit-learn.org/stable/developers/advanced_installation.html


