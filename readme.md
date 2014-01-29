iRWebStats.

You can use this class to send requests to iRacing service and get some valuable data like stats, race results, driver info, series info, etc. it requires valid login credentials (username and password) to access the service. 

USAGE

from client import iRWebStats

irw = iRWebStats()
irw.login('username', 'password')
print irw.cars_driven()  # cars driven by user

FILES

client.py : This is where the class is defined.
examples.py : Somes examples.
constants.py : Useful constants used in request fields sent to the service.
util.py : Helper functions.

REQUIREMENTS

Python 2.7 (with network permissions)


CONTACT
Jeyson Molina
Write me to jjmc82 at gmail if you need assistance.

2014
