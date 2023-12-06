# grammer-spell-check
In the YouTubers project, the Gingerit module is no longer available. Therefore, I have used Language Tool, instead of Gingerit. Therefore, when you copy this code and paste it into VS code or any other Code editor, then first install the packages using pip install package_name in the Terminal and then run the code. Please don't directly run the code. Also, to use the Language Tool module, you need Java to be installed on your laptop/computer. So, please refer to the link here to download Java.

https://www.java.com/en/download/manual.jsp

Also, install python in your laptop/computer through this link below, to avoid any errors and also, install the python extension in VS code:

https://www.python.org/downloads/

Also, please create a "templates" folder, inside which you should paste the index.html file. Then only the render_template will work perfectly.
Note: Please refer to the "Folder photo".

To install packages, run the below commands as shown in the terminal:

pip install language-tool-python

pip install Flask

pip install textblob

Now, when you run the app.py file, you will get an error as "No module named distutils". This means that Python pip, setuptools, and wheel are not up-to-date. So, please run the below commands:

py -m pip --version

py -m ensurepip --default-pip

py -m pip install --upgrade pip setuptools wheel

Then in the terminal, the Flask app will start and you will get a localhost server link as shown below. Then you need to click on it and then the app will start.
Serving Flask app 'app'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000

The above commands will work properly.
If then too, the error occurs, then try installing this Java JDK: https://www.oracle.com/java/technologies/downloads/#jdk21-windows

References: https://packaging.python.org/en/latest/tutorials/installing-packages/

For any help, contact me through the YouTube comments section.
Thank you. 


