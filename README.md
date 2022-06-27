# Dockersploit
Dockersploit is a Python3 script used to automatically deploy Docker containers vulnerable to a CVE of choice. You can also use it with a GUI for a better user experience.

## Installation
- git clone this repository.
- install the dependencies using the command "pip install -r requirements.txt".
- Make sure you have Docker daemon running and have permission to run Docker, and you are good to go!

## Usage
To list all the CVEs that is available to Dockersploit:
<br>
```
./dockersploit.py -l
```
<br>
To search through the Dockersploit catalog:
```
./dockersploit.py -s apache
```
<br>
To run a vulnerable container:
```
./dockersploit.py -c CVE-2012-1823
```
<br>
To list running Dockersploit containers:
```
./dockersploit.py -ps
```
<br>
To stop the running container:
```
./dockersploit.py -d CVE-2012-1823
```
<br>
To run Dockersploit using GUI:
```
./dockersploit.py -w
```
