# Example Image webserver on Google Cloud Platform

This is an example of the use of image webserver django-thumbnail

### Steps required for making the webserver

## 1) Clone the ansible script on your local machine

git clone https://github.com/amardrylab/ansible_djangoserver3.git

## 2) Change directory and start the ansible-playbook

- cd ansible_djangoserver3

- ansible-playbook instance_create.yml

## 3) SSH to your created machine

ssh www.drylab.in

## 4) Create your virtual environment

virtualenv myproject

## 5) Install git software

- sudo apt-get update

- sudo apt-get install git

## 6) Clone the django scripts

git clone https://github.com/amardrylab/arunachalvisit.git

## 7) Copy the required file in proper location

mv arunachalvisit/* myproject

## 8) Enter in your virtual environment

- source myproject/bin/activate

- cd myproject

## 9) Install the required softwares in the local environment

- pip install django

- pip install pillow

10) Run the following commands for your final launching

- sudo service nginx restart

- sudo service uwsgi restart
