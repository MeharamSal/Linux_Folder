

<p align="center">
  <img width="538" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/7cfb6c30-1436-492f-9519-2717b138cb28">
<p>


</p>
<p>

<h1>Linux_FireFox</h1>
Instructions for Downloading Firefox through a Linux Virtual Machine.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Subscription
- Terminal

<h2>Operating Systems Used </h2>

- Linux Ubunto

<h2>List of Prerequisites</h2>

- Create Key in Microsoft Powershell
- Connect to Terminal on VM
- Login
- Prepare download
- Download Firefox

<h2>Installation Steps</h2>
<p>
<img width="659" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/369f960a-9ba0-4e67-9901-b1966c32487a">
</p>
<p>
Create a Key in Microsoft Powershell by using the command "ssh-keygen -t rsa -b 2048"
</p>
<br />



<p>
<img width="1182" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/2a5df545-7b8b-453f-8841-37e6f060b7f7">
</p>
<p>
When you are creating a new virtual machine (VM) in the Azure portal, there will be a step where it asks you to provide a public key. This key is needed to securely connect to your VM later.


</p>
<p>Find the file named id_rsa.pub on your computer. This file contains your public key.
</p>



<p> Open the id_rsa.pub file using a text editor and copy the text inside
</p>
<br />








<p>
<img width="824" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/08ee688c-9d89-402d-b18a-aa013fc7e35a">
</p>
<p>
Create your Virtual Machine
</p>
<br />














<p>
<img width="616" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/58fbcaf1-7426-4d81-8899-a6f0637442fd">
</p>
<p>
Use the ssh command to connect to your Virtual Machine
</p>
<p>ssh username@public Ip Address
</p>
<br />








<p>
<img width="357" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/bb30b4c4-b67b-4942-a677-e341cb9033ec">
</p>
<p>
Update package list in terminal by typing in "sudo apt update"</p>
<br />



















<p>
<img width="476" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/1e047b34-5dc2-41f5-b815-f597d06027e1">
</p>
<p>
"At this point, you are prepared to proceed with the installation of Firefox. Execute the following command in the terminal:"</p>
<p>
  sudo apt-get install firefox-esr
</p>
<br />

















<p>
<img width="580" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/a96e7f00-de55-42af-9b9a-1178cf2fd1bc">
</p>
<p>
Confirm that it successfully installed with the command "dpkg -s firefox-esr"
</p>
<br />






<p align="center">
  <img width="456" alt="image" src="https://github.com/MeharamSal/Linux_Folder/assets/173064050/023049d9-058a-4660-99de-d2e4153979c1">
<p>


</p>
<p>
