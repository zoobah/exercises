# Password Attacks

## Requirements
Any environment capable of running Python and a password cracker like hashcat or John the Ripper should suffice.

My lab environment for this is a Kali 2020.3 virtual machine and a MacBook Pro running hashcat.

## Linux Setup
1. Install Kali Linux
* Kali VMs can be downloaded for free from Offensive Security's Website (https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/)

2. Install Hashcat or John the Ripper.
* John the Ripper and Hashcat come pre-installed on the Kali VM.
* In other Linux environments, Hashcat or John the Ripper can be installed via your package manager, e.g. apt
- $ ```sudo apt install hashcat``` 
- $ ```sudo apt install john```

3. Install the Rockyou list

* Rockyou is pre-installed on Kali, but you must first decompress the file before use
- ```sudo gunzip /usr/share/wordlists/rockyou.txt.gz```
* Other Linux distros can follow these steps
- $ ```wget https://github.com/danielmiessler/SecLists/raw/master/Passwords/Leaked-Databases/rockyou.txt.tar.gz```
- $ ```tar zxvf rockyou.txt.tar.gz```

4. Clone the repository for the Domain Password Audit Tool

* $ ```git clone https://github.com/clr2of8/DPAT```

5. Clone this repository

* $ ```git clone https://github.com/zoobah/exercises```

6. (Optional) Install nodejs for password guessing attack

## Windows Setup

1. Install Python

* (https://www.python.org/downloads/windows/)

2. Install Hashcat

* (https://hashcat.net/hashcat/)

3. Download and Unzip DPAT repository

* (https://github.com/clr2of8/DPAT/archive/master.zip)

4. Download and Unzip this repository

* (https://github.com/zoobah/exercises/password_attacks/archive/master.zip)

## Exercises

### Password Cracking

Use Hashcat or John the Ripper to crack the passwords in ntlm_hashes_easy.txt

sudo john windows7_sam.dump --format=nt --wordlist=/usr/share/wordlist/rockyou.txt



