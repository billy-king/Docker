FROM ubuntu:latest

RUN sudo apt-get update
RUN sudo apt-get install python-pip python-dev build-essential -y g++ at wget git zsh gdb vim tcpdump gcc ssh iperf libpcap-dev man lsof
RUN git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
RUN cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc

RUN git clone git://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
RUN sudo pip install requests datetime bs4 pymongo
