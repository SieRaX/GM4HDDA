# M3239.006800: Geometric Methods for High-Dimensional Data Analysis
The official repository for the homework assignments of the lecture &lt;Geometric Methods for High-Dimensional Data Analysis> instructed by Frank C. Park in Seoul National University. 

- *[Syllabus](https://drive.google.com/file/d/12fFBcK3D4JQkCZwxvvfdTPaEjxiALBwb/view?usp=sharing)*

#### Table of Contents  
[Schedule](#Schedule)  
[Instructions for Settings](#Instructions-for-Settings)  
[Homework 1](#Homework-1)  


#### TA Contacts
- Yonghyeon Lee (yhlee@robotics.snu.ac.kr)
- Seungyeon Kim (ksy@robotics.snu.ac.kr)
- Younghun Kim (yhun@robotics.snu.ac.kr, *Head TA*)


## Schedule
Task                | Due date              | PDF file          | Solution
:---                |  :---:                |   :---:           | :---:
**Assignment I**    | October 5, 2022       | [pdf](https://drive.google.com/file/d/1CG5lfSkTxjxo6ZGSeH8xmc01cMBh-7H3/view?usp=sharing)        | TBA
**Assignment II**   | October 26, 2022      | [pdf](https://drive.google.com/file/d/137vAvWIOZLRwMTKf6bqIqQk7HwvnBrG_/view?usp=sharing)        | TBA
**Examination**     | TBA      | TBA   | TBA
**Assignment III**  | TBA      | TBA   | TBA
**Assignment IV**   | TBA      | TBA   | TBA
**Course Project**  | TBA      | TBA   | TBA

## Instructions for Settings
### Install Anaconda3 and Jupyter Notebook
For those unfamiliar with environment setup, Anaconda3 installation is recommended. 
- For Windows user, download and install Anaconda3 from the following link: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution).
- For Linux user, download shell file from the following link: [Anaconda3-2022.05-Linux-x86_64.sh](https://drive.google.com/file/d/1x0mTd3stcNkEC_tY9vvgDUCwwHdPRqVe/view?usp=sharing). After that, execute the shell using the following command:
    ```shell
    chmod +x Anaconda3-2022.05-Linux-x86_64.sh      # change permission
    ./Anaconda3-2022.05-Linux-x86_64.sh             # execute shell file
    ```

After Anaconda3 installation, jupyter is automatically installed and you can run jupyter notebook with the following command:
```shell
jupyter notebook
```

### Guidelines for Anaconda3 and Jupyter Notebook
Here's some commands for conda environment:
```shell
conda create -n {name} python=3.9   # create conda environment
conda activate {name}               # activate conda environment
conda deactivate {name}             # deactivate conda environment
```
If you want to use the created conda environment in jupyter notebook, you need to register the kernel. The command to register is following:
```
pip install ipykernel
python -m ipykernel install --user --name {name} --display-name "{name-in-jupyter}"
```
- {name} and {name-in-jupyter} can be replaced by your choices.

### Environment
The project codes are tested in the following environment.
- python 3.9
- numpy
- matplotlib
- scikit-learn
- *pytorch*
- *torchvision*

To setup the environment except *pytorch* and *torchvision*, run the following script in the command line:
```
pip install -r requirements.txt
```
*Pytorch* and *torchvision* need to be installed separately using the method below.

### Torch installation
Install PyTorch and torchvision from the following link: [https://pytorch.org](https://pytorch.org). 

## Homework 1
Follow the instructions in the ``HW1.ipynb`` file. After you complete and run the HW ipython file, send the result file to ``yhun@robotics.snu.ac.kr``.   
For problem 1~5, submit your answer sheet in the class.

## Homework 2
Follow the instructions in the ``HW2.ipynb`` file. After you complete and run the HW ipython file, send the result file to ``yhun@robotics.snu.ac.kr``.   
For problem 1~4, submit your answer sheet to 302-413, or ``yhun@robotics.snu.ac.kr``

- In problem 5 of the pdf file, change $\mathcal{D} =$ \{ $(x_i,x_j)|x_i, x_j \in \mathcal{X}$ \} to $\mathcal{D} =$ \{ $(x_i,x_j)$ \}
