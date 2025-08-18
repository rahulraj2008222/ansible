# Ansible node is designed to to do automation for diffrent scripts and help us to learn and implement factors directly into the Linux machines.

Before we can implement any ansible script and make few changes we need to understand how we can make changes to the Git-hub repo directly from the ansible node.

Clone the repository:
git clone git@github.com:user.name/ansible.git

Check repository status:
git status

Once you have coppied the repo and you make changes to some files or add new files you need to make a commit to it an dpush it to the GITHUB.

set you account defualt identity 
git config --global user.email "you@example.com"

check the diffrence between the files you made modification to :
git diff

add the chnages made :
git add your_file_name

commit the file:
git commit -m "comment for the file"

push the changes to GITHUB:
git push

Note: Here you will be asked for loginuser and the password, you can h=find the username on your profile or can use the email and for the password you need to create a tocken by going into the seating of the GITHUB acount and chose clasic to give you access to the repo.

to pull the lates changess from the GITHUB:
git pull