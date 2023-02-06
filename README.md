**My First Vagrant Installation Project**

This is my *first* time installing a virtual environment.
To install a virtual environment you need to install

1.VirtualBox
2.Vagrant

I did this installation on a *Linux distribution*, Ubuntu to precise.

If you would like to install a virtual environment using VirtualBox
and Vagrant, follow the steps below:


1.To install VirtualBox:
'''
sudo apt-get install VirtualBox
'''

2. To install Vagrant:
'''
sudo apt-get install Vagrant
'''

3. Add the *Ubuntu 20.04(Focal) image*:
'''
vagrant box add ubuntu/focal64
'''

4. Create your first virtual machine:
'''
vagrant init ubuntu/focal64
'''

5. Start your virtual machine:
'''
vagrant up
'''

6. SSH into your virtual machine:
'''
vagrant ssh
'''