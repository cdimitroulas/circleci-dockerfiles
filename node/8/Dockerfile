FROM circleci/node:8

RUN sudo apt-get install python-dev
RUN sudo curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py \
      && sudo python get-pip.py \
      && sudo rm -f get-pip.py
RUN sudo pip install awscli
RUN sudo apt-get install bsdmainutils

CMD ["/bin/sh"]
