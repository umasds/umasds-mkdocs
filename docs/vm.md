Social Data Science @ University of Mannheim

![Social Data Science](img/sds.png)

*This project is still under heavy development!*

---

# The Social Data Science VM

An easy to use virtual machine (VM) for teaching data science in the 
social sciences

---

## **Installation and setup**
We tried to keep the installation process as simple as possible. You 
just need to follow these easy steps:

---

### 1. Install necessary tools
You first need to install install 
[VirtualBox](https://www.virtualbox.org/wiki/Downloads) and 
[Vagrant](https://www.vagrantup.com/downloads.html) in order to setup 
and run the VM.

---

### 2. Prepare the VM
#### Start terminal
Preparing the VM requires to use the command line in a terminal window. 
This is a lot easier than it sound. To start a terminal you do the 
following:

* *Ubuntu Linux*: Press *command/Windows/Apple key* > type `terminal` 
    > hit *enter*
* *MacOS X*: Press *command/Windows/Apple key* + *space* > type 
    `Terminal` > double click *Terminal* in the results
* *Windows*: Press *command/Windows/Apple key* > type `cmd` > hit 
    *enter*

#### Create new directory
Now you need to create a new directory and navigate to it by typing the 
following commands into the terminal and hitting *enter* after each
line:

*Ubuntu Linux* and *MacOS X*: 
```
mkdir ~/umasds-vm
cd ~/umasds-vm
```

*Windows*: 
```
mkdir %HOMEPATH%\umasds-vm
cd %HOMEPATH%\umasds-vm
```
#### Initialize the VM
As the last step of the setup you have to initialize the VM and tell the
tools where to find the VM image file (called a *box*):

*all operating systems*: 
```
vagrant init http://bethm.de/umasds-vm/umasds-vm.box
```

---

### 3. Download and run the VM for the first time
The following step will take a considerable amount of time depending on
the speed of your internet connection. To download and start up the VM 
you need to enter the following:

*all operating systems*: 
```
vagrant up
```

After a while your social data science desktop should come up and you 
can start crunching data!

---

### 4. Starting the VM
You can always start the VM by opening a *terminal*, changing to the 
`umasds-vm` directory and starting `vagrant up` manually, but if you 
want a more convenient way you can easily set up a shortcut on the 
desktop:
  
*all operating systems*:

* Start the *Oracle VM VirtualBox Manager* - much like you started the 
    terminal above, just type in `oracle` instead
* Do a right click on *umasds-vm* > click left on *Create Shortcut on 
    Desktop*

... et voilà! Anytime you want to start the VM now you just need to 
double click on the *umasds-vm* icon (blue cube saying "vbox") on the 
desktop.

---

### 5. Stopping the VM
To stop the VM all you have to to is click on the shutdown icon (red 
square with white circle) in the lower right corner > click on *Shut 
down*.
