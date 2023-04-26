## cocktails-app
#you can containerize this app by following the instructions in the README file ...


## Containerize the app
# I include a Dockerfile for this purpose. All you have to do is that you run this command:

  docker built -t <your-chosen-name> /your/path/to/directory
  
# If you are already in the directory you can use this:

  docker built -t <your-chosen-name> .
  
# When '.' at the end indicates that the path is the current directory.
# After running the following command you actually made an image from your cocktails application.
# You can run it by creating a container like this and exposing one port to access the app through your browser:

  docker run -p 8080 <your-image-name>
  
# Note that <your-chosen-name> is the exact same name as <your-image-name>
  
