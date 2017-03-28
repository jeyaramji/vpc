# vpc
# For more information refer 
# http://jeremievallee.com/2016/07/27/aws-vpc-ansible/
# http://www.tivix.com/blog/using-ansible-create-aws-instances/
.
├── aws-staging-private.pem
├── group_vars
│   └── ec2_hosts
├── inventory
├── playbook.yml
├── README.md
├── roles
│   ├── ec2_launch
│   │   └── tasks
│   │       └── main.yml
│   ├── ec2_post_build
│   │   └── tasks
│   │       └── main.yml
│   └── vpc
│       └── tasks
│           └── main.yml
└── var.yml

8 directories, 9 files
