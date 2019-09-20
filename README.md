# awslearn

## ssh

Generate key: `ssh-keygen -C david24365@gmail.com -f ~/.ssh/id_rsa_awslearn`

  Generates private, `id_rsa_awslearn` and public key, `id_rsa_awslearn.pub`
  
Upload public key to EC2 (web console)

Launch EC2 instance

Login into EC2: `ssh ec2-user@1.2.3.4 -i ~/.ssh/id_rsa_awslearn`

## regions

List of regions where EC2 is available: `aws ec2 describe-regions --all-regions | jq '.Regions | .[].RegionName'`

Number of regions where EC2 is available: `aws ec2 describe-regions --all-regions | jq '.Regions | .[].RegionName' | wc -l`

## exam difficulty

Perceived exam difficulty (just an opinion):
- Developer Associate
- Solutions Architect Associate
- Sysops Administrator Associate
- Security Speciality
- Big Data Speciality
- Devops Professional
- Advanced Networking Speciality
- Solutions Architect Professional
