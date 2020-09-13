## Lesson 3 - LAB 1
- Create a playbook that will install httpd on the managed server, using the following requirements.
- Install the httpd package
- Enable the httpd service and make sure it is started.
- Create a file /var/www/html/index.html, containing the text "Welcome to my web server".
- Use the firewalld module to open the appropriate ports in the firewall 

----

## Lesson 3 - LAB 2

##### This lab comes from my own practice. I'm using it to prepare OpenStack hosts. Even if you're not using OpenStack, you can run this lab as well.

- Disable the NetworkManager service.
-  Modify the /etc/default/grub file and add the parameters net.ifnames=0 and biosdevname=0 to the line that loads the Linux kernel. Next, copy the new file to all managed hosts.
-  On all hosts, run grub2-mkconfig to write the modified /etc/default/grub file 

###### Tip! Use the lineinfile module to edit the configuration file 
