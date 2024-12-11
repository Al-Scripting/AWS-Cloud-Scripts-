# AWS-Cloud-Scripts-
Cloud scripts for AWS CLI on Linux

findAMI is not my work it is provided by my professor "Richard Pazzi". I included it in case the script won't break due to dependencies

launchEC2 is a script that accepts the key name and security group name from the user and uses the findAMI function to launch AWS EC2 instances equal to the count amount provided by the user

stopAll is a script that stops all instances that have the tag that matches the one inputted by the user,
