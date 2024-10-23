# Kioptrix Level 1

- try to get ip adress

`arp-scan -I eth0 -l`

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/adb41ca4-dd4f-43a9-8611-bee7e77e73ea/image.png)

- use nmap to get more information

`nmap -p- -sV -sS -T4 -A -oX Kioptrixlcl1.xml 192.168.2.41`

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/fb672e23-fef6-4015-8d7d-0914082de24c/image.png)

- use xsltproc turn xml to html

`xsltproc Kioptrixlcl1.xml -o 1.html`

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/932a5852-46b1-44dc-bbd8-e33ba15b8bd3/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/c26c1561-bdff-448f-8da6-54a0da157b24/image.png)

- use msf to get Samba version

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/fcae0051-e75d-4c97-9b6b-b04de0ff8d04/image.png)

- search on exploit db to find exploit

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/33f491ea-915c-4161-b076-9ea0900514e7/image.png)

https://www.exploit-db.com/exploits/10

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/e189d170-dbc7-437e-b03d-d8a4b19bdac9/image.png)

- use exploit

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e36a7ac4-dbcc-4806-a6e6-9f7d9c39ca00/0325b53f-5af5-4341-b7ca-0ebe8ee46147/image.png)
