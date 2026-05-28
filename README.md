# Project Title:  Lab Setup: Deploy Virtual Machines
## Project Supervisor: Mr Cornelius Michael
 *Prepared By: Nwambeke chimaobi E Francis  28/05/2026

## 1. Project Overview
.Virtual machines (VMs) are critical tools that enable the creation of isolated, virtualized environments where multiple operating systems can run on a single physical computer. This capability makes them invaluable for safe experimentation and efficient resource use across IT disciplines.

## 2. Project Goals
- The goal is to install a Hypervisor on your computer (host).
- Set up two virtual machines (Kali Linux and Windows 10) on it.
- Configure the virtual machines to be on an isolated network.

## 3. Lab Design & Considerations

### 3.1. Hypervisor Selection
Chosen Hypervisor: VirtualBox
Reason: it’s simple to use

### 3.2. Operating System Images

<img width="421" height="72" alt="image" src="https://github.com/user-attachments/assets/082446b7-822e-4fd5-b678-f3223b4332d9" />

## 4. Lab Implementation Steps

### Prerequisites:
- Computer with at least 8GB RAM (16GB recommended)
- At least 80GB of free disk space
- Hardware-based support for virtualization

### 4.1. Install Hypervisor
- Downloaded and installed VirtualBox on Windows 11 host machine.

The virtualization technology used to run the VMs is Oracle VirtualBox, as it allows you to run multiple operating systems on your computer. It can be downloaded from the official website, https://www.virtualbox.org/.

<img width="428" height="135" alt="Screenshot 2025-07-21 093555" src="https://github.com/user-attachments/assets/a4ebef81-aff7-49d6-bd5b-ce1b11af2ba2" />

Once on the website, click on the download button to get started. You will be redirected to a page where you must select the one compatible with your operating system. For this purpose, I will download the one for Windows and also click the second arrow button, which is “Accept and Download,” to download the VirtualBox Extension file.

<img width="428" height="135" alt="Screenshot 2025-07-21 093745" src="https://github.com/user-attachments/assets/513a9499-a800-4f00-ace5-b05944675ba2" />

You should now have the file in your folder, just like the screenshot below.

<img width="533" height="21" alt="vm" src="https://github.com/user-attachments/assets/94ed0cbb-081d-4e27-82d5-16fcb91cece1" />


- Double-click on the VirtualBox file in your folder and follow the instructions to get it installed, as it’s a straightforward installation
  

<img width="385" height="296" alt="vm install" src="https://github.com/user-attachments/assets/66e095c8-089f-43de-b8c9-6021b8822048" />
<img width="385" height="296" alt="Screenshot 2025-07-19 041047" src="https://github.com/user-attachments/assets/da35bb2e-1e5f-4a00-8c3b-7cbf7ca5b532" />

### 4.2. Download OS ISOs

- Windows 10 ISO downloaded from Microsoft's official site.
https://www.microsoft.com/en-us/software-download/windows10
- kali-linux-2025 ISO downloaded from ubuntu.com.
https://www.kali.org/get-kali/#kali-platforms

<img width="519" height="45" alt="Screenshot 2025-07-21 094807" src="https://github.com/user-attachments/assets/7610d943-d684-4024-b1f9-097d2c6dd0e8" />

### 4.3. Create and Configure Virtual Machines
- VM1 (Windows 10)
- Click on the New icon on the VirtualBox interface.
  
<img width="199" height="47" alt="Screenshot 2025-07-19 042623" src="https://github.com/user-attachments/assets/1e6a09be-8d2a-4411-9b58-7d2448ed4264" />

Fill in the name and select the windows iso file just like what you have on the screenshot.

<img width="565" height="235" alt="Screenshot 2025-07-19 061137" src="https://github.com/user-attachments/assets/7bca7e34-b00b-4b69-8777-0e8231f1dc08" />


The next section is where you set up your username, passwords, and input the product key.

<img width="565" height="235" alt="Screenshot 2025-07-19 061533" src="https://github.com/user-attachments/assets/ce7d5b34-a2a7-4842-9e69-ea03aef51d06" />


The next section is the hardware information, where you set the base memory and the processor according to your disk space. 2 CPUs, 4GB RAM

 <img width="565" height="235" alt="Screenshot 2025-07-19 061241" src="https://github.com/user-attachments/assets/2edc291f-cf93-4c5f-8c19-a26c98dd038a" />
 
Then click on the finish button to finish the configuration, and then click on the start button. <img width="199" height="47" alt="Screenshot 2025-07-19 042556" src="https://github.com/user-attachments/assets/7864dc99-a5f8-46fa-b603-9753a6a13d2e" />



<img  width="385" height="296" alt="Screenshot 2025-07-19 063241" src="https://github.com/user-attachments/assets/5ec683e3-d344-4dae-8a43-7945e769bac5" />

<img  width="385" height="296" alt="Screenshot 2025-07-19 074025" src="https://github.com/user-attachments/assets/a549c2dd-a7d5-44bb-ac68-662c1d8994b9" />

## VM2 (kali-linux-2025)

 Click on the New icon on the VirtualBox interface.
<img width="199" height="47" alt="Screenshot 2025-07-19 042556" src="https://github.com/user-attachments/assets/44ee431c-8d4e-4553-bcef-d2b1fd4d845e" />

Fill in the name and select the windows iso file just like what you have on the screenshot.

 <img  width="385" height="296" alt="Screenshot 2025-07-19 043019" src="https://github.com/user-attachments/assets/a58dd98a-5c3d-4c1e-973a-2cd29a19a443" />
 
The next section is the hardware information, where you set the base memory and the processor according to your disk space. 2 CPUs, 4GB RAM.

<img width="804" height="182" alt="Screenshot 2025-07-19 043156" src="https://github.com/user-attachments/assets/919a88c2-4e9e-46fd-a811-910121749998" />

 Then, click the Finish button to complete the configuration, and then click the Start button.
 
<img width="199" height="47" alt="Screenshot 2025-07-19 042556" src="https://github.com/user-attachments/assets/4153e4c7-32bd-43a4-a258-8ace45d304e3" />

# Here is a pictorial step of the Kali installation
<img width="389" height="344" alt="Screenshot 2025-07-19 043838" src="https://github.com/user-attachments/assets/f60ee525-04c5-41e8-85be-41a36d0350c0" />
<img width="389" height="344" alt="Screenshot 2025-07-19 043946" src="https://github.com/user-attachments/assets/047d403b-d775-432b-b8fa-1e81920c5def" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044144" src="https://github.com/user-attachments/assets/5bfe1587-077b-475c-8ac6-1726f70b0c3a" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044350" src="https://github.com/user-attachments/assets/7988222e-d0fc-477b-9c88-87ad8aab5245" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044605" src="https://github.com/user-attachments/assets/6a2dc17e-d874-48e3-9121-1cd8a38ba20e" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044700" src="https://github.com/user-attachments/assets/3b9cd9fb-a806-4139-99a9-b89d7bf2d6b7" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044754" src="https://github.com/user-attachments/assets/47fe4f19-4f12-40a7-8f32-2d2ce8ce4237" />
<img width="389" height="344" alt="Screenshot 2025-07-19 044926" src="https://github.com/user-attachments/assets/a4ae93ac-b435-4b58-ad6a-9fe174c2cd07" />
<img width="389" height="344" alt="Screenshot 2025-07-19 045005" src="https://github.com/user-attachments/assets/eed58dbc-5004-45f6-90a7-14745c438613" />
<img width="389" height="344" alt="Screenshot 2025-07-19 045055" src="https://github.com/user-attachments/assets/c1d5f2f9-2d52-454f-9418-003307c1ecfb" />
<img width="389" height="344" alt="Screenshot 2025-07-19 045208" src="https://github.com/user-attachments/assets/725d24e9-1a82-49a9-8f4a-36476a5e471d" />
<img width="389" height="344" alt="Screenshot 2025-07-19 045323" src="https://github.com/user-attachments/assets/b1263832-e0e7-4ab0-8198-3e46e598872b" />
<img width="389" height="344" alt="Screenshot 2025-07-19 045718" src="https://github.com/user-attachments/assets/5a4a4514-9650-4bc7-9806-40d843b34906" />
<img width="389" height="344" alt="Screenshot 2025-07-19 053231" src="https://github.com/user-attachments/assets/b9e56b60-783b-47fb-b2a1-83e9b943a675" />
<img width="389" height="344" alt="Screenshot 2025-07-19 053326" src="https://github.com/user-attachments/assets/01913161-c86d-4a29-b72b-dd50eabcdd80" />
<img width="389" height="344" alt="Screenshot 2025-07-19 053814" src="https://github.com/user-attachments/assets/52fb3095-da2e-4a58-94c9-26bdecbd83bf" />
<img width="389" height="344" alt="Screenshot 2025-07-19 054045" src="https://github.com/user-attachments/assets/c643695f-d453-4d64-9b24-6ab26ba41605" />

### 4.4. Network Configuration

•	Created a custom NAT Network in VirtualBox
•	Ensured both VMs were attached to the same NAT Network
•	Disabled host access and external internet access to enforce isolation

<img width="527" height="532" alt="Screenshot 2025-07-19 054504" src="https://github.com/user-attachments/assets/4dd0eb0e-5813-4b7b-9d0a-6446113ee82b" />

<img width="569" height="350" alt="Screenshot 2025-07-19 055228" src="https://github.com/user-attachments/assets/8126a776-3a02-4dd9-9b0c-7fcf86508b35" />


## 5. Validation & Testing

### 5.1. IP Address Verification
Checked IPs using:
	ipconfig (Windows VM IP)
 
<img width="487" height="254" alt="Screenshot 2025-07-19 075808" src="https://github.com/user-attachments/assets/146ce8ed-f3e4-4ee3-ac88-15a85f6543da" />

ip a or ifconfig (Linux VM)

<img width="403" height="251" alt="Screenshot 2025-07-21 103724" src="https://github.com/user-attachments/assets/995c9c82-d858-45aa-984f-c37662bbd726" />

 
### 5.2. Connectivity Test
### Ping Test: From Windows VM to Linux VM
 
 Command: ping <Linux-VM-IP>

<img width="494" height="128" alt="Screenshot 2025-07-19 080140" src="https://github.com/user-attachments/assets/62fa7b10-27cc-49ff-a284-53968f6723ab" />

Successful response with <1ms latency

## 6. Postmortem & Lessons Learned

### What Went Well:

- VirtualBox’s NAT Network worked effectively for isolation.
- OS installation was smooth.
- Internal ping test confirmed correct VM communication setup.

### Challenges:
- Initial misconfiguration by selecting "NAT" instead of "NAT Network".
- Needed to configure the NAT Network settings to enable DHCP manually.

### Key Takeaways:
Networking mode selection is one of the most critical aspects of VM isolation. It directly impacts how safe and effective your lab environment will be, especially when you're working with potentially dangerous samples like malware or when simulating attacks in penetration testing.

## 7. References

- VirtualBox Documentation     https://www.virtualbox.org/manual/
- Microsoft Windows ISO Download    https://www.microsoft.com/software-download/
- Kali Linux ISO Download    https://www.kali.org/get-kali/#kali-platforms
- VM Networking Modes – Comparisons  https://www.geeksforgeeks.org/networking-modes-in-virtualbox/
