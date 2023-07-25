### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.

 # This is also optional.
  # Bonus points for useful outputs!
  # for example, if you create a Load Balancer
  # it's nice to output the URL to it here, so that we don't have to go to the console to get it.

# Sample UserData
# When creating your Launch Configuration, you may need a UserData script
# here's one that you can use for Ubuntu Linux that will:
# Install Apache Web Server, Start it, and create an index.html that will be displayed
# when you visit the IP address of this server with your web browser
# Here it is:
#
#          #!/bin/bash
#          apt-get update -y
#          apt-get install apache2 -y
#          systemctl start apache2.service
#          cd /var/www/html
#          echo "Udacity Demo Web Server Up and Running!" > index.html

#### LB link
http://proje-webap-4ya74mb7pupw-1261537042.us-east-1.elb.amazonaws.com/
#### Cloudfont link
d384w70r5g7ut2.cloudfront.net