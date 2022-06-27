# Dockersploit
Dockersploit is a Python3 script used to automatically deploy Docker containers vulnerable to a CVE of choice. You can also use it with a GUI for a better user experience.

## Installation
- git clone this repository.
- install the dependencies using the command "pip install -r requirements.txt".
- Make sure you have Docker daemon running and have permission to run Docker, and you are good to go!

## Usage
To list all the CVEs that is available to Dockersploit:
<br>

  ./dockersploit.py -l

<br>
To run, just use the -c flag followed by the CVE code, for example: ./dockersploit.py -c CVE-2012-1823
<br>
To stop the running container, use the -d flag. For example: ./dockersploit.py -d CVE-2012-1823
<br>
To execute 
