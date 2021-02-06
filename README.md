https://numpy.org/
https://pandas.pydata.org/docs/

# install python and jupiter with Anaconda
$ cd /tmp
$ sudo apt install curl
$ curl https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh --output anaconda.sh
$ sha256sum anaconda.sh
output: 2b9f088b2022edb474915d9f69a803d6449d5fdb4c303041f60ac4aefcc208bb  anaconda.sh

# run anaconda
$ bash anaconda.sh
<yes>

I'll be in the directory of Anaconda
[/home/javier/anaconda3] >>> 
Ask me for:
 - Press ENTER to confirm the location and then it is intalled

Do you wish the installer to initialize Anaconda3
by running conda init? [yes|no]
<yes>

# look for versions of python
(base) $ conda search "^python$"

# assing a virtual environment and install the last version of python
(base) $ conda create --name my_env python=3

# activate virtual environment
(base) $ conda activate my_env
(base) $ python --version
    output: 3.9.1 for this ... my_env

# start anaconda
$ source ~/.bashrc

# run anaconda
$ anaconda-navigator

# desactivate anaconda
(base) $ conda deactivate
