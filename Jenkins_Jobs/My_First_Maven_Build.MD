#### Pre-requisites

1. Jenkins server


### Steps to create "My_First_Maven_Build" Jenkin job
1. Login to Jenkins console
1. Create *Jenkins job*, Fill the following details,
   - *Source Code Management:*
      - Repository: `https://github.com/yankils/hello-world.git`
      - Branches to build : `*/master`
   - *Build:*
     - Root POM:`pom.xml`
     - Goals and options: `clean install package`