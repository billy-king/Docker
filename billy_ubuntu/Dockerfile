FROM ubuntu:latest

RUN sudo apt-get update
RUN sudo apt-get install -y wget git zsh gdb vim tcpdump gcc ssh iperf libpcap-dev
RUN sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

RUN git clone git://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
