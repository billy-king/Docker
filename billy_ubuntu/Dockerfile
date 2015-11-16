FROM ubuntu:latest

RUN sudo apt-get update
RUN $HOME=/root
RUN sudo apt-get install -y wget git zsh gdb vim tcpdump gcc ssh iperf libpcap-dev
RUN git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
RUN cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc

RUN git clone git://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
