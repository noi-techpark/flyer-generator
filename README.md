# Flyer Generator
A web based generator for flyers. This version generates the flyers for the monthly Java Developer Meetings hosted by the NOI Techpark in South Tyrol.

# How to test it locally

An easy way to get the project running on your development machine, is to clone the repository and use the python SimpleHTTPServer as a local webserver to test it. 

```bash
# clone the rpository
$ git clone <REPO URI>

# change into the project directory, where the index.html file is located. 
# This is needed for the python webserver to find the files.
$ cd flyer-generator

# start a simple python webserver on a free port (usually 8080)
$ python -m SimpleHTTPServer 8080

# point your web browser to localhost at the port you have started the python webserver
$ firefox localhost:8080

```

# LICENSE
This project is released under the AGPLv3 https://www.gnu.org/licenses/agpl-3.0.en.html



