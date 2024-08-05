# Requirements
Make sure that you have the following installed:
- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) 
- npm 
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder 
 `cd client`

## Run the folllowing command to install the dependencies 
 `npm install`

## Run the folllowing to start the app
 `npm start`

## Open a new terminal and run the same commands in the backend folder
 `cd ../backend`

 `npm install`

 `npm start`

 ### Go ahead a nd add a product (note that the price field only takes a numeric input)

 ## Automated Deployment with Ansible

For automated deployment using Ansible, follow these steps:

### Prerequisites
- Vagrant and virtual box are installed on your machine
- Ansible installed on your local machine
- Docker installed on the target machine

## Initialize vagrant environment
 `vagrant init`

## Add a vagrant box
- choose a base box from (https://app.vagrantup.com/boxes/search) and initialize it with `vagrant box init..`

## Start vagrant machine
 `vagrant up`

## Run Ansible playbook
 `ansible-playbook playbook.yaml`
