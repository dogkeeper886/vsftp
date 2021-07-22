FROM opensuse/leap:15.2
RUN zypper -n refresh
RUN zypper -n install vsftpd
RUN useradd -m ftp_user
RUN echo ftp_user:ftp_user | chpasswd
CMD ["/usr/sbin/vsftpd", "/etc/vsftpd.conf"]