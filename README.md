
# by DEFALUTERS !👋


# DRIVER MONITORING SYSTEM

AI-powered driver monitoring systems offer several advantages such as improved safety, reduced risk of accidents, cost-effectiveness, compliance with regulations, and improved driver performance. By detecting drowsiness, distraction, and other unsafe driving behavior, the system can alert drivers in real-time and prevent accidents. These systems can also help reduce costs associated with accidents, comply with industry regulations, and identify areas for drivers to improve their driving skills. Overall, AI-powered driver monitoring systems provide a range of benefits for drivers and companies alike.


## PRESENTATION

[Documentation](hhttps://www.canva.com/design/DAFgOgJiSNM/TIR_R_wFrBo5Ur7WqlQeKA/view?utm_content=DAFgOgJiSNM&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)


## PYTHON APP.PY DEYLOYMENT

To deploy this project run

```bash
# Importing flask module in the project is mandatory
# An object of Flask class is our WSGI application.
from flask import Flask
from detect3_Basic_Copy import run
# Flask constructor takes the name of
# current module (__name__) as argument.
app = Flask(__name__)

# The route() function of the Flask class is a decorator,
# which tells the application which URL should call
# the associated function.
@app.route('/')
# ‘/’ URL is bound with hello_world() function.
def hello_world():
	run()
	return 'Hello World'

# main driver function
if __name__ == '__main__':

	# run() method of Flask class runs the application
	# on the local development server.
	app.run()

```





## Features

- REAL TIME FACE TRACKING
- SOS AND EMERGENCY SERIVES
- BLACK BOX ENABLE 
- CROSS PLATFORM (DELOYED ON WEBSITE)


## Screenshots

![App Screenshot](https://user-images.githubusercontent.com/113209109/232274640-fbef53a7-ad6d-433d-a549-4bba4ca8c555.png)

![Screenshot (61)](https://user-images.githubusercontent.com/113209109/232274683-f3d34fa2-0a84-4e02-b89f-b5fe95b5383f.png)
![Screenshot (61)](https://i.ibb.co/qyMK1KL/Screenshot-65.png))
