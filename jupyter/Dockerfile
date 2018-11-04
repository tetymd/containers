FROM jupyter/datascience-notebook

USER root

RUN wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
RUN tar xvfz ta-lib-0.4.0-src.tar.gz
RUN cd ta-lib && ./configure --prefix=/usr && make && make install

RUN pip install TA-Lib
