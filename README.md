# How to configure TOMCAT:JRE-8
[title] (https://www.anavi.org/article/20/)
## Defining directory structure to compile the app
These are the steps:

- The WEB-INF has a class directory containing classes to run
- WEB-INF Must have a xml file containing configs (web.xml)
- web.xml has a mapping using tags <servlet> and <servlet-name>
- `<servlet>` maps a name to a class
- `<servlet-name>` maps a url to a `<servlet>`
- Dockerfile copy files to webapps directory and compile it to run

## To run
<p>git clone https://github.com/prosseto/dockerservlet
<p>docker build . -t hello_servlet
<p>docker run --rm -p 80:8080 hello_servlet
<p>It starts a new simple servlet with a message response
   
## Next steps
- Create a way to debug this app
