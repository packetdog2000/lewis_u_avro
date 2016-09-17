# lewis_u_avro
Lewis University Course File For Avro

## Environment : Python 2.7, Ubuntu or CentOS in VirtualBox

Vbox: https://www.virtualbox.org/wiki/Downloads
centos: http://isoredirect.centos.org/centos/7/isos/x86_64/CentOS-7-x86_64-Minimal-1511.iso
Apache Avro Distr. for Python: http://avro.apache.org/docs/1.8.1/gettingstartedpython.html

### STEPS
1. Create an instance of a Linux server in VB (I used Centos 7 minimal ISO)
2. Get the Apache Avro distribution (v. 1.8.1 for python) and install in the Linux server: 
3. Check installation by :
 $ python
 >> import avro
 
4. Create a directory in the Avro server to host the schema file and the student_write.py and student_schema.avsc 
 mkdir /home/<username>/student && cd /home/<username>/student
5. ftp to the Avro server to transfer file to the /home/<username>/student directory
6. execute python:
7. $ python student_write.py

You can remotely call from another pc by ssh if the Avro server is in your network. 
ssh username@192.168.1.12

once connected, you can call :
$ python /home/<username>/student_write.py


