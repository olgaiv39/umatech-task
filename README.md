# umatech-task

To run this code, do the following:
1) clone this repository
2) download the dataset and unzip it in the root directory
```
unzip task.zip
```
3) make installation scripts executable
```
chmod +x *.sh
```

4) run and installation script for anaconda 
```
./install_conda.sh
```
or for python virtual envinronment
```
./install_venv.sh
```
5) for quick running of notebooks in console, change the name of the notebook and obtain script 
```
./run_jupyter.sh
```

Here is a notebook with exploratory data analysis (EDA.ipynb) and 3 notebooks with different architechtures used to classify images - ResNet18, ResNet34 and ResNet50.

The best result (Accuracy: 92.90%, Loss: 0.0002) after training for 50 epochs has been achieved by ResNet34 model.

All the weights from training can be downloaded from here: https://drive.google.com/open?id=1NAjkxxULFiMJ-7E3n5deUhWWsA5K8c12
