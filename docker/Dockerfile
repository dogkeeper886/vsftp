FROM opensuse/leap:15.2
RUN zypper -n refresh
RUN zypper -n install vsftpd
RUN echo ftp_user:ftp_user | chpasswd
CMD ["top", "-b"]