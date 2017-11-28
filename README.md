<h1>Python Search Aggregator</h1><br>
A search aggregator using Python and Django. It creates a local webpage with a simiple search bar that, when you search text in it, then sends that search to Google, Bing, DuckDuckGo, and Yahoo and return the results<br>

**Setting up a dev enviorment**<br>
You'll want virtualenv to keep the requirements seperate from your normal Python install to ensure easy transfer to other systems. This isn't necessary, but it is a nice QoL improvement and is considered a best practice. 

To get this run: <br>
    <code>pip install virtualenv</code>

Then create your enviorment using: <br>
    <code>virtualenv *project*</code> <br>
    This will create a folder in the directory where you ran the command so be sure to run it in a folder you want to keep your code.

Once your environment is created you'll need to activate it. To do this you'll need to run the activate command from the generated Scripts folder. <br>
    <code>.\Scripts\activate</code> <br>
    On Windows you may get an error stating that your computer isn't set up to run scripts if this happens open a powershell window as administrator and run this command <br>
    <code>Set-ExecutionPolicy RemoteSigned</code> <br>
    Depending on how security conscious you are you may want to set this back to restricted when you're done to do this run this from the admin powershell window: <br>
    <code>Set-ExecutionPolicy Restricted</code> <br>

If you somehow don't already have it, you'll also most likely want git. Git ships with most Linux distros, but if you don't have it you can use 
<code>sudo apt-get install git</code><br>
or your distro's equivalent package manager to get the latest stable release.
Git can be winstalled for Windows at https://git-scm.com/download/win or on Mac at https://git-scm.com/download/mac<br>

You can manually download the files using Github or you can use a CLI and do it manually. To pull this code from Github to your local machine you would run the following commands:<br>
```
git init
git remote add origin https://github.com/literallystan/SearchAggrigate
git pull origin master
```
<br>
Afterwards you'll have a fully complete copy of this repository's code

***Requirements***
So far the only requirements are Django and Python. Python can be downloaded from https://www.python.org/ on Windows or OSX. Most Linux distros ship with Python, but if not you can run:
<code>sudo apt-get install python3.6</code><br>
or your distro's equivalent package manager