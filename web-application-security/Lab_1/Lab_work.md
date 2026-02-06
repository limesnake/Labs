# Contents
- Environment setup
- Testing and verification
- Packet capture demonstration

## Enviorment setup

### Step 1 
I went to the official website and downloaded the kali linux iso file , I chose the virtual machines option as I am using oracle virtualbox

<img width="1803" height="993" alt="kaliiso" src="https://github.com/user-attachments/assets/9e82cbaa-15b9-449e-8e3d-ab1ea024aca1" />

### Step 2 
I added the iso file to virtualbox and configured my details, i made sure to add at least 8gb of ram and 50gb of hdd as i will be re-using this vm in the future

<img width="1633" height="715" alt="Screenshot_2026-02-05_21-13-15" src="https://github.com/user-attachments/assets/d3eee31f-bca9-45e1-b2b4-c2530b64ca82" />

### Step 3

Then i ran the the vm and done some basic checks to make sure the vm can do what its supposed to do.

<img width="976" height="734" alt="2 2" src="https://github.com/user-attachments/assets/b362afef-fbd3-465b-9ff6-b9fa1a5d49aa" />

### Step 3.1

I ran `uname -a` to check my OS and confirm everything is working correctly.


<img width="455" height="154" alt="uname" src="https://github.com/user-attachments/assets/f8bf50fc-76c3-4c9e-a7f0-e03efad34456" />

### Step 3.2

Then i checked if i can curl google to make sure connectivity is fine with the command `curl -I https://www.google.com` and also opened google to double check


<img width="1017" height="533" alt="curl" src="https://github.com/user-attachments/assets/335d0730-f008-415c-aace-3cca52a2febe" />
<img width="953" height="588" alt="google" src="https://github.com/user-attachments/assets/4e6ae62b-0e0d-4826-8bdb-c86d16d047ca" />

### Step 3.3

And finally i used `ps aux` to see what services are running including google used to test connectivity

<img width="1040" height="604" alt="ps" src="https://github.com/user-attachments/assets/b0f05eb6-c51d-491f-affb-43b7a8217087" />

