# How to configure TOMCAT:JRE-8
[title] (https://www.anavi.org/article/20/)
## Defining directory structure to compile the app
These are the prereqs:

- The WEB-INF directory contains configuration information about the web application
- WEB-INF Must have a xml file containing configs (web.xml)
- Compile javaclasses

##To run
git clone <this-repo>
docker build . -t hello_servlet
docker run --rm -p 80:8080 hello_servlet
   

