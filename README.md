# Dockersploit
Dockersploit is a Python3 script used to automatically deploy Docker containers vulnerable to a CVE of choice. You can also use it with GUI for a better user experience.

## Installation
- Clone this repository:
```
git clone https://github.com/Vibragence/Dockersploit.git
```
- install the dependencies:
```
pip install -r requirements.txt
```
- Make sure you have Docker daemon running and have permission to run Docker, and you are good to go!

## Usage
To list all the CVEs that is available to Dockersploit:
<br>
```
./dockersploit.py -l
```
To search through the Dockersploit catalog:
```
./dockersploit.py -s apache
```
To run a vulnerable container:
```
./dockersploit.py -c CVE-2012-1823
```
To list running Dockersploit containers:
```
./dockersploit.py -ps
```
To stop the running container:
```
./dockersploit.py -d CVE-2012-1823
```
To run Dockersploit using GUI:
```
./dockersploit.py -w
```
