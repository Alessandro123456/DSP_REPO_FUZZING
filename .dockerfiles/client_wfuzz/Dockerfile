FROM python
RUN pip install wfuzz 
RUN apt-get update && apt-get install git
WORKDIR /home
RUN git clone git://github.com/xmendez/wfuzz.git
WORKDIR /home/wfuzz
RUN python setup.py install