# moodle-ansible
## Installation elearning system platform (Apache-Mariadb-Php-Moodel) using Ansible

This playbook allows installation on a server locally, not remotely (although it could also be used that way if preferred) but in this case it is used in an infrastructure without ansible master.

<ol>
     <li>connect via ssh</li>
     <li>log in as root and install (su -) (we use apt instead of pip because debian generates an environment error</li>
     <li>apt install ansible</li>
     <li>edit with vi (or other editor) the user you have on that machine, in the vars file ex:test_folder</li>
     <li>we copy the folder</li>
     <li>We launch ansible from ssh console</li>
       <ul><li>ansible-playbook site.yml -i inventory.ini</li></ul>
</ol>
   
   [Whatch Video description] ([https://website-name.com](https://www.youtube.com/watch?v=NYCyO_7IvHU&t=17s))
