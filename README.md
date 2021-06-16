



<!-- PROJECT LOGO -->
<br />
<p align="center">


  <h3 align="center">ADMM in Python</h3>

  <p align="center">
    A basic implementation of ADMM in Python
  </p>
</p>







<!-- ABOUT THE PROJECT -->
## About The Project



I wrote ADMM solver for quadratic programming with conic constraints in Python. The codes are in a Jupyter Notebook for simpler demonstration. 




<!-- GETTING STARTED -->
## Getting Started

Here are essential steps to install everything you need on Ubuntu to get started with Jupyter Notebook

### Prerequisites

In order to install Jupyter Notebook, we need to install anaconda first. Anaconda is a distribution of Python and R that is created with the purpose to simplify package management and deployment. Before installing anaconda we need to check for dependencies:

  ```sh
  apt-get install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
  ```

### Installation

1. Download the anaconda installer at [here](https://www.anaconda.com/products/individual#linux)
2. RECOMMENDED: [verify data integrity with SHA-256](https://docs.anaconda.com/anaconda/install/hashes/). I didn't do this because I thought the file was updated  
   ```sh
   sha256sum /path/filename
   ```
3. Enter following to install anaconda:
   ```sh
   bash /path/file
   ```
   Essentially run the downloaded sh file with bash
4. Hit yes all the time in the above installation process. A more detailed guide can be found [here](https://docs.anaconda.com/anaconda/install/linux/). Reopen terminal after installation to make it effective

5. Notes on anaconda: Anaconda is run by virtual environments. Open a terminal and you may notice (base) before the account name. It means that the default environment base is on. You can shut off the auto activation by running    
   ```sh
   conda config --set auto_activate_base False
   ```
6. To do anything we need a virtual environment in anaconda. It's not recommended to use the base environment directly. It's recommended to create another virtual environment. We need to specify python version when creating new environments, so first do `conda search "^python$"` to get a list of all possible python versions. Then the following creates an environment called yourenvname:      
   ```sh
   conda create -n yourenvname python=x.x anaconda
   ```
You should specify your desired python version at x.x (e.g 3.7). Hit `conda activate yourenvname` to shift to that environment. Now under this environment we install Jupyter notebook by 
   ```sh
   conda install -c conda-forge jupyterlab
   ```



<!-- USAGE EXAMPLES -->
## Usage

To open a Jupyter Notebook, do the following: 

1. Open a terminal and activate your environment by `conda activate yourenvname`.

2. Type `jupyter notebook` to bring a new window with your defualt browser (e.g. chrome). You can navigate though your files and open .ipynb files. To create new files, click on "new" button on the upper right and choose Notebook/Python 3 on the drop down menu. More detailed information can be found [here](https://jupyter.org/documentation)



<!-- ROADMAP -->
## Using Jupyter Notebook

1. A typical jupyter notebook consists of several cells. There are markdown cells (for texts) and code cells. There are several icons on the top menu with basic functions (e.g add/delete cells). You can hover your mouse on them and get a feeling of it. 
cl
2. To run a code cell, click it and hit shift+enter. Or you can run all the cells at once with the run botton on the top. Jupyter Notebook has very good documentations at [https://jupyter.org/documentation](https://jupyter.org/documentation)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
