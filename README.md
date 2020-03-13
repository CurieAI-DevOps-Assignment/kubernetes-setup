# Kubernetes Setup Using Ansible and Vagrant.

#Prerequisites:
 1.Vagrant should be installed on your machine.
 2.Oracle VirtualBox can be used as a Vagrant provider.
 2.Ansible should be installed in your machine.
 
#Step 1: Create an Ansible playbook for Kubernetes master.
 1.Create a directory named kubernetes-setup in the same directory as the Vagrantfile. 
 2.Create two files named master-playbook.yml and node-playbook.yml in the directory kubernetes-setup. 
 
#now run the fallowing comd.
 vagrant up
 
#Upon completion of all the above steps, the Kubernetes cluster should be up and running. We can login to the master or worker nodes using Vagrant as follows:

# ## Accessing master

  vagrant ssh k8s-master

# ## Accessing nodes
  vagrant ssh node-1
  vagrant ssh node-2
 
