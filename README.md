# MultiAgent_RL

sudo add-apt-repository ppa:fkrull/deadsnakes
sudo apt-get update
sudo apt-get install python3.5

vi ~/.bashrc
alias python='/usr/bin/python3'

$ sudo update-alternatives --install /usr/bin/python python /usr/bin/python2.7 1
$ sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.5 2

export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.0.0rc0-cp35-cp35m-linux_x86_64.whl

sudo pip install --upgrade $TF_BINARY_URL

http://chris-chris.ai/2017/08/30/pysc2-tutorial1/
