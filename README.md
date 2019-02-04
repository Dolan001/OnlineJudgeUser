# OnlineJudgeUser

<h3>Dependencies</h3><br>
<p>These distributions will be installed automatically when installing Flask.</p><br>
•	Werkzeug implements WSGI, the standard Python interface between applications and servers.<br>
•	Jinja is a template language that renders the pages your application serves.<br>
•	MarkupSafe comes with Jinja. It escapes untrusted input when rendering templates to avoid injection attacks.<br>
•	ItsDangerous securely signs data to ensure its integrity. This is used to protect Flask’s session cookie.<br>
•	Click is a framework for writing command line applications. It provides the flask command and allows adding custom management commands.<br>

<h3>Create an environment</h3>
Create a project folder and a venv folder within:<br>
mkdir myproject<br>
cd myproject<br>
python3 -m venv venv<br>
<br>
On Windows:<br>
py -3 -m venv venv<br>
<br>
If you needed to install virtualenv because you are on an older version of Python, use the following command instead:<br>
virtualenv venv<br>
On Windows:<br>
\Python27\Scripts\virtualenv.exe venv<br>

<h3>Activate the environment</h3><br>
Before you work on your project, activate the corresponding environment:
. venv/bin/activate
On Windows:
venv\Scripts\activate
Your shell prompt will change to show the name of the activated environment.

<h3>Install Flask</h3><br>
Within the activated environment, use the following command to install Flask:<br>
pip install Flask<br>
Flask is now installed. Check out the Quickstart or go to the Documentation Overview.<br>

<h3>Living on the edge</h3>
If you want to work with the latest Flask code before it’s released, install or update the code from the master branch:<br>
pip install -U https://github.com/pallets/flask/archive/master.tar.gz<br>

<h3>Install virtualenv</h3><br>
If you are using Python 2, the venv module is not available. Instead, install virtualenv.<br>
On Linux, virtualenv is provided by your package manager:<br>
<br>
# Debian, Ubuntu
sudo apt-get install python-virtualenv

# CentOS, Fedora
sudo yum install python-virtualenv

# Arch
sudo pacman -S python-virtualenv<br>
If you are on Mac OS X or Windows, download get-pip.py, then:<br>
sudo python2 Downloads/get-pip.py<br>
sudo python2 -m pip install virtualenv<br>
On Windows, as an administrator:<br>
\Python27\python.exe Downloads\get-pip.py<br>
\Python27\python.exe -m pip install virtualenv<br>
Now you can return above and Create an environment.
