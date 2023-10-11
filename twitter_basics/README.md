### Requirements

In order to contribute to this repo, we recommend activating an isolated virtual environment. To start with, please install `virtualenv`

`$ pip install virtualenv`

Then, in the root, run the command 

`$ virtualenv venv`

This will set a new virtual environment, callend venv, in the current folder. The next step is to activate the actual environment. This
can be done on a MacOS or Linux operative systems by running

`$ source venv/bin/activate`

or in a Windows operating system by running

`$ venv\Scripts\activate`

Finally, install the required packages (`Flask` and `Tweepy`) defined in `requirements.txt`, by executing the command

`$ pip install -r requirements.txt`
