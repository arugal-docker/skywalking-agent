FROM arugaldocker/java:1.0

RUN  wget -P /usr http://mirror.bit.edu.cn/apache/skywalking/6.1.0/apache-skywalking-apm-6.1.0.tar.gz && \
        cd /usr && mkdir skywalking && \
        tar -zxvf apache-skywalking-apm-6.1.0.tar.gz && \
        mv apache-skywalking-apm-bin/agent /usr/skywalking && \
        rm -rf apache-skywalking-apm-*