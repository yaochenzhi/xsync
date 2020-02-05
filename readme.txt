# Centos 7

[config]
    mv xsync /usr/local/bin/

    echo host1 host2 >> /etc/xsync
    echo host3 >> /etc/xsync
    echo host4 >> /etc/xsync

[usage]

    xsync path/to/file
    xsync /path/to/file
    xsync file1 file2
    xsync file1 --delete
    xsync file2 -d
