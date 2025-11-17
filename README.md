# MaleficentVM
This is practice VM for malware development. 


# What is this VM?
This VM provides practice challenges for malware development just like ctf challenges. VM also comes with .NET framework installed incase if you want to use c# for malware development.

# Downloading the VM
- Use the link [here](https://drive.google.com/file/d/1D6WAc0RXlxY1PwYUI36JRqGRhER8Wnmb/view?usp=sharing) to download the VM, it's around 21gb in size
- Use this Onedrive link [here](https://1drv.ms/u/c/9cfb7c54d8a192bc/IQDeJOFxxl-QQbf-pPopMB4oAQFyizAwjh13CotlHjO3rw0?e=KXM8Cw) incase the google drive link does not work

# Setup
- Download the .ova file
- Open it with virtual box or vmware workstation
- Give the VM a name and power on the machine
- Set network adapter settings to bridged so we can scan for ip address using nmap
- Use nmap or any other ip scanner tools to scan the ip address of the VM, eg: nmap -sn ourkaliip/24 to retrieve all other active hosts on our network
- Go to your browser and open http://IP_ADDRESS_OF_VM:5000
- You can see the challenges, write the code in c/c++/rust/c# or any other language and upload the binary to get the flag
- Take a snapshot of the VM so that you can revert back to the original state if anything error happens

# Running the server manually 
- If the server does not run automatically, login to the vm and run these commands from cmd as administrator
```
cd "C:\Users\flash\Desktop\myserver\myserver"
python main.py
```

# Sample Challenges
<img width="3564" height="1318" alt="image" src="https://github.com/user-attachments/assets/0fb5801a-720d-485d-8c61-21c7418de7ae" />

<img width="3261" height="1946" alt="image" src="https://github.com/user-attachments/assets/65b80f0f-e33c-49e9-8fcb-cf109874a5eb" />

<img width="3393" height="1421" alt="image" src="https://github.com/user-attachments/assets/980a37f4-0db1-46e4-b0b9-87e8bfc6cfb8" />

<img width="3475" height="1640" alt="image" src="https://github.com/user-attachments/assets/817bbdbb-bfa1-4371-8bd0-f7a4723bbbf8" />

# VM users' password
Credentials for the users are flash:flash and arrow:arrow 
