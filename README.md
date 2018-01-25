
Video Link for the Demo: https://youtu.be/B2ChwG4r7V0

Steps for running the application:

1.	Download the zip folder and extract the Flasktut Folder.
2.	Open the Flasktut folder in a python IDE preferably PYCharm.
3.	Install Apache Jena Fuseki  (version 3.4.0) server in your system.
4.	If you are using MacOS or Linux, open the terminal and go to your Fuseki server directory and give the following command:
 ./fuseki-server --update --mem /ds
5.	Upload all the RDF datasets into the fuseki server in a single dataset.
6.	After uploading check the sparql endpoint in the query tab.
Example:
 

7.	In the home.py file update the sparql endpoints in every query so as to run them in your local machine.
8.	Then run the home.py file and open the local host (for example: http://127.0.0.1:5000/) and run only in Firefox browser.
9.	You should now be able to run the application.
10.	The sample test cases for our application are:
a.	Performance:
"	Make: fiat
"	Model: punto
"	Year: 2015
"	Condition of the car: old
b.	   General Specifications:
"	Make: gmc
"	Model: yukon-hybrid
"	Year: 2013
"	Condition of the car: old
c.	   Technical Specifications:
"	Make: volvo
"	Model: v40
"	Year: 2017
"	Condition of the car: new
d.	   Reviews and Ratings:
"	Make: gmc
"	Model: acadia
"	Year: 2015
"	Condition of the car: old
e.	   Compare Cars:
Car 1
"	Make: gmc
"	Model: canyon
"	Year: 2014
"	Condition of the car: old

Car 2
"	Make: gmc
"	Model: yukon
"	Year: 2014
"	Condition of the car: old

Car 3
"	Make: gmc
"	Model: acadia
"	Year: 2014
"	Condition of the car: old
f.	   Price Based Search:
"	Minimum Price: 2000
"	Maximum Price: 5000


11.	Used python version 2.7.12
12.	Install flask in your system by giving the following command in the terminal:
 pip install flask
13.	Install the following libraries before running the application
"	from flask import Flask, request, render_template
"	from SPARQLWrapper import SPARQLWrapper, JSON
"	from collections import defaultdict





