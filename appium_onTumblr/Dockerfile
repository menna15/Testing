FROM appium/appium:latest

RUN apt-get update && apt-get install -y \
    software-properties-common
RUN add-apt-repository universe
RUN apt-get install -y \
    python3.8 \
    python3-pip

RUN pip3 install --upgrade pip

RUN pip install Appium-Python-Client

RUN apt-get -y install xauth

WORKDIR /appium_test


