first we want to  create a folder and then add the two files into the folder.
next we need to run the docker parallely otherwise it dshow error message.
after open the cmd to the file loacted path.
put the two commands into the cmd 1.docker build -t flask-app .
2.docker run -p 5000:5000 flask-app
and open into docker it will appear .
run the url into the chrome  http://127.0.0.1:5000/
