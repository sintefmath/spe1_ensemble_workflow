FROM openporousmedia/opmreleases
USER root
# Get newer version of python
RUN apt update && apt install software-properties-common && \
    apt install software-properties-common && \
    apt update && \
    apt install python3.7 python3-distutils python3-apt --yes

# Get ERT
RUN wget https://bootstrap.pypa.io/get-pip.py && \
    python3.7 get-pip.py 
    
RUN  pip3 install ert==2.34.0
USER opm