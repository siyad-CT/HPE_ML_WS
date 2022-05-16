# HPE_ML_WS
Repository of Lab files for the HPE ML workshop by CloudThat

sudo apt update
sudo apt install software-properties-common



sudo apt install python3.8
python3.8 --version



sudo apt install pip
pip install matplotlib
pip install virtualenv



sudo apt install openjdk-8-jdk
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64



wget https://downloads.apache.org/spark/spark-3.1.2/spark-3.1.2-bin-hadoop3.2.tgz
sudo mkdir /opt/spark
sudo tar -xf spark*.tgz -C /opt/spark --strip-component 1
sudo chmod -R 777 /opt/spark



echo "export SPARK_HOME=/opt/spark" >> ~/.bashrc
echo "export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin" >> ~/.bashrc
echo "export PYSPARK_PYTHON=/usr/bin/python3" >> ~/.bashrc



source ~/.bashrc



sudo apt install python3-pip python3-dev
sudo -H pip3 install --upgrade pip
sudo -H pip3 install virtualenv



mkdir ~/my_ML_Projects
cd ~/my_ML_Projects
virtualenv ml_project_env
source ml_project_env/bin/activate



pip install jupyter
pip install pyspark
pip install findspark
jupyter notebook --ip=*


http://184.72.89.222:8888/?token=197f1bd344995416eb6b14bf4f985992ed8eca69abbe66f3



git clone https://github.com/siyad-CT/HPE_ML_WS

ssh -i "C:\tmp\jeromesparkkp.pem" ubuntu@184.72.89.222
