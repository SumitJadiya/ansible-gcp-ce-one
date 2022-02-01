# ansible-gcp-one
create compute engine instance using ansible

#### Setup Ansible :

	$ sudo pip install ansible

#### Add the secret key JSON:
	
	- Create service account, give admin permission and create a JSON key and keep the json key in parent directory.

#### Run the playbook using command :
	
	$ ansible-playbook main.yaml