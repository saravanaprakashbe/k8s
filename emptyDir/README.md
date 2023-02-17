<h3>Create a POD running two containers using the following YAML file (name the file as datelogger.yml) 
We will be creating an emptyDir volume called html and mounting the volume to both the containers. The html-updater container will be updating the index.html file with the current datetime. We will access the nginx container to read the contents of the index.html file</h3>
