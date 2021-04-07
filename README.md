# jquantum
we build java library collection for quantum physics and chemistry calculation and design it for running with python on Jupyter notebook or google colabs. At this moment we focus on HF and DFT method to calculate electronics properti material.

# How To Use

this library is cross platform as long as java 8 installed in your device, if you haven't install it first
### install openjdk for java and set ENV variable
!apt-get install -y openjdk-8-jdk-headless -qq > /dev/null      #install openjdk
os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"     #set environment variable

### install maven
!sudo apt-get install maven

### install imglyb
!pip install imglyb==0.3.5

### install pyimagej
!pip install pyimagej

### install pyjnius (python library to access java classes)
!wget https://anaconda.org/conda-forge/pyjnius/1.2.0/download/linux-64/pyjnius-1.2.0-py36hc2cfd8d_0.tar.bz2 && tar -xjf pyjnius-1.2.0-py36hc2cfd8d_0.tar.bz2 -C /usr/local
