# Practice_CloudFormation
ansible-demoは、Ansibleを使用してAWSのEC2インスタンス上でRailsの環境構築を自動で行います。  
# 使用技術
- Ansible
  - yum
  - Yarn
  - Node.js
  - Ruby
  - MySQL
  - Rails
  - Nginx
  - Unicorn
- AWS
  - VPC
  - EC2
  - RDS
# 構成図
![sample]()  
# 特徴
- 対象のEC2はElastic IP、RDSはMySQLを使用しています。
- Railsはproduction環境でデプロイが可能です。
