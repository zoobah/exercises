# Password Attacks

## Requirements
Any environment capable of running Python and a password cracker like hashcat or John the Ripper should suffice.

My lab environment for this is a Kali 2020.3 virtual machine and a MacBook Pro running hashcat.

## Linux Setup
1. Kali Linux - Kali VMs can be downloaded for free from Offensive Security's Website.

* (https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/)

2. In Linux environments, Hashcat or John the Ripper can be installed via your package manager. John the Ripper comes pre-installed on the Kali VM.

* $ ```sudo apt install hashcat``` 

* $ ```sudo apt install john```

3. Clone the repository for the Domain Password Audit Tool

* $ ```git clone https://github.com/clr2of8/DPAT```

4. Clone this repository

* $ ```git clone https://github.com/zoobah/password_attacks```

5. (Optional) Install nodejs for password guessing attack

## Windows Setup

1. Install Python

* (https://www.python.org/downloads/windows/)

2. Install Hashcat

* (https://hashcat.net/hashcat/)

3. Download and Unzip DPAT repository

* (https://github.com/clr2of8/DPAT/archive/master.zip)

4. Download and Unzip this repository

* (https://github.com/zoobah/password_attacks/archive/master.zip)

