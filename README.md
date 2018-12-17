# minimalist-logon
A minimalist website with logon and logout support using Python 3.x and Flask.

#### Features:
 - minimalistic
 - logon/logout support
 - written in Python 3.7 using Flask
   
INSTALL
----
 Clone the repository from github : 

    $ git clone https://github.com/Sim4n6/minimalist-logon.git minimalist-logon
    $ cd minimalist-logon

Create a virtual environnement on linux : 

    $ python3 -m venv venv
    $ python3 venv/bin/activate
    
Create a virtual environnement on windows :

    $ python3 -m venv venv
    $ venv\Scripts\activate.bat
    
Install the necessary packages including Flask and Pytest: 
    
    $ pip3 install -r requirements.txt
   
Run
---
On linux :

    $ python minimalist-logon.py

On Windows :

    > python minimalist-logon.py

Open http://127.0.0.1:5000 in a browser.

TEST
----
Execute all tests : 

    $ pytest 
Run a coverage and generate an html report : 

    $ coverage run -m pytest
    $ coverage report
    $ coverage html
