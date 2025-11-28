# aap-security-compliance
AAP project for installing Security agents on AWS servers to make them compliant.

aws-security-compliance/

├── inventories/

│   ├── aws_ec2.yml

│   └── group_vars/

│       └── all.yml

├── playbooks/

│   ├── install_splunk.yml

│   ├── install_qualys.yml

│   ├── install_mde.yml

│   ├── install_tanium.yml

│   └── workflow_compliance.yml

├── roles/

│   ├── splunk/

│   ├── qualys/

│   ├── mde/

│   └── tanium/

├── eda/

│   └── aws_new_ec2_rulebook.yml

├── vars/

│   └── credentials.yml (encrypted with ansible-vault)

├── README.md

└── requirements.yml


This will give you:

✅ Folder structure (project layout for AAP)

✅ Playbooks for each tool (Splunk, Qualys, MDE, Tanium)

✅ Workflow playbook (combines all)

✅ EDA rulebook (auto-trigger from AWS events)

✅ Inventory & credentials placeholders

✅ Integration pointers for AAP setup
