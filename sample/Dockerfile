    # Use an official Tomcat image as the base
    FROM tomcat:latest

    # Copy your WAR file into the webapps directory of Tomcat
    # Replace 'your-application.war' with the actual name of your WAR file
    # If you want it to be accessible at the root context, rename it to ROOT.war
    COPY sample.war /usr/local/tomcat/webapps/

    # Expose the default Tomcat port (8080)
    EXPOSE 8080

    # The default command for the Tomcat image will start the server
    # You typically don't need to specify CMD unless you want to override it.
