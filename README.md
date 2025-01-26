# comptia-tech+ (FC0-U71)

## EXAM DOMAINS
1.0 - IT Concepts and Terminology<br>
2.0 - Infrastructure<br>
3.0 - Applications and Software<br>
4.0 - Software Development<br>
5.0 - Database Fundamentals<br>
6.0 - Security<br>

## 1.0 - IT CONCEPTS AND TERMINOLOGY
- Computer Literacy: the ability to use computers and related technology efficiently, including understanding how they work and operate.<br>
- Computer systems work similarly hence knowing one system helps learn another.<br>
- Computing Process: Input, Processing, Output, Storage (same for every device)<br>
- Input/Output devices enable communication with a computer enhancing capabilities of computers.<br>
- Processing components handle commands.<br>
- Storage devices save data and programs for later use.<br>
- General-purpose computing devices, e.g., PCs, tablets, laptops, smartphones are adaptable, increasing their functionality and enables them to be more useful.<br>
- Users can add apps to enable more functionality.<br>
- Local Area Network (LAN): a basic computer network that connects devices within a limited area via switch. Local and usually small. Much faster. Server uses LAN to provide network.<br>
- LAN Charateristics: Small, local, connected groups of devices. e.g.: P2P, small offices.<br>
- Wide Area Network (WAN): Routers connect one or more LANs into a WAN.<br>
- WAN Characteristics: Devices on different networks connect. e.g.: A company's global offices connecting to each other.<br>
- Internet: LAN combined with WAN together.<br>
- LANs, WANs, and the Internet are paths to reach remotely-accessed computer systems.<br>
- Remotely-Accessed Computer Systems: allow users to access a computer from a distance, either for work or other purposes enhancing local capabilities.<br>
- Remote Server: a computer that stores and processes information, and is accessible over the internet, e.g., web servers, database servers, file servers.<br>
- Online applications enable lighter (resource-wise) local machines and it resides in the remotely-accessed computer systems.<br>
- Online storage and systems protects data from local crashes.<br>
- Specialized Computer Systems: computers that are designed to perform specific tasks, rather than a wide range of tasks e.g., POS System, ATM, GPS, printers, joysticks, multifunction devices.<br>

## 2.0 - SYSTEM HARDWARE
- Central Processing Unit (CPU) is not smart but very fast. It only does what it is asked to do. Needs to give CPU a detailed instruction. Does not have memory, needs a separate memory piece to remember info.
- CPU's characteristic:<br>
      &emsp;- Speed: how many things it can do in one second under perfect condition. Measured in gigahertz (Hertz: 1 cycle per sec)<br>
      &emsp;- Complexity:<br>
      &emsp;- 32-bit or 64-bit processor (Bits: amount fo data a CPU can process)<br>
      &emsp;- e.g., Raspberry pi, mother board<br>
      &emsp;- n-core CPU: put n-different processors on one little chip and it works together.<br>
- Electricity generates heat in the CPU while it works.<br>
- Methods to move heat:<br>
      &emsp;1) Passive: relies on air. Uses copper or aluminium structure called heat sinks that help heat dissipate into air.<br>
      &emsp;2) Active: using some kind of device to push or pull heat away from computing components e.g., fans/case fans (pull heat out into the air) or liquid cooling (pulls heat into fluid).<br>
- Random Access Memory (RAM) is measured in gigabytes.<br>
      &emsp;1) Function: holds all active programming on a computer that includes OS running apps, and data. Only temporarily stores data.<br>
      &emsp;2) Capacity: The amount of usable RAM is called system memory. Using too much will slow it down not die.<br>
      &emsp;3) Adding More: Can add more RAM or replace with bigger RAM stick in bigger computers to increase the overall memory capacity.<br>
      &emsp;4) 32-bit only supports 4GB RAM.<br>
      &emsp;5) www.crucial.com: to find the right RAM for your device.<br>
 - Motherboard a.k.a. (Micro) Advanced Technology Extended (ATX) enables connectivity among devices directly or indirectly. Every computing device has a motherboard.<br>
![motherboard](https://github.com/user-attachments/assets/66fcdc8f-6786-450e-8650-81d68a892167)
 - Power supplies:<br>
      &emsp;1) Power grid runs on alternating current (AC)<br>
      &emsp;2) Computing devices run on direct current (DC) so it relies on batteries for power.<br>
      &emsp;3) Power adapter: a.k.a. an AC adapter or charger, is a device that converts AC power from a wall outlet into DC power for a device.<br>
      &emsp;4) Power brick: a small, rectangular, external power supply that converts AC to DC to power electronic devices (for small devices).<br>
      &emsp;5) Power supply unit (PSU): a computer hardware component that converts AC from an electrical outlet into DC for a computer's internal components (for big devices).
- Intel vs AMD vs ARM processor:
    - Intel: expensive but awesome
    - AMD: great but less expensive
    - ARM: in little devices like smartphones

## 3.0 - DEVICE PORTS AND PERIPHERALS
- Peripheral device: a hardware component that connects to a computer to enhance its functionality, but is not part of the computer's core architecture.
- PS/2 Connector: connects to a very old mice and keyboards.
- Universal Serial Bus (USB): connects a variety of I/O device. There are 7 types of USB, e.g., USB A (plugs into a computer), USB Type-B (plugs into peripherals), USB Mini-B and USB Micro-B (plugs into smaller peripherals), Micro-B USB 3.0 (10 times faster), USB C (plugs in either way literally universal).
- eSATA Connector: connects external hard drive
- Video connector: HDMI, DisplayPort (mainly on Apple and Dell), VGA (for older monitor), and DVI connectors
- Ethernet (RJ-45) Connecter: connects networks
- Audio connectors are color coordinated: pink (microphone), black (other devices), green (speakers). It matters which one you plug in.
- Auto sensing port: automatically detects the connection speed and type of a device on the other end of the connection.
- On smartphones, all I/O devices are built into the same system.
- Scaling up devices adds a separation for the processing components.
- Computing devices come in many forms.
- I/O devices: touchscreens (input because of the touch function and output because of the screen monitor), keyboards, monitors, mice.
- Video cards can be added to desktop.
- VGA vs DVI vs HDMI: differences in quality of signal they carry and type of signals they carry.<br>
        &emsp;1) VGA - Default standard, supports a decent size resolution and only carries only video signals.<br>
        &emsp;2) DVI - Handles much better definition, carries only video signals.<br>
        &emsp;3) High Definition Multimedia Interface - carries high definition of audio and video.<br>
- Buying a 5 bucks may or may not get the perfect connectivity and speed that the original cable provides.

## 4.0 - DATA STORAGE AND SHARING
- Computing devices use wire and electricity to count in binary. (base 2)<br>
- 1 = ON, 0 = OFF<br>
- Every wire we added doubles the complexity.<br>
- Modern operator comes in 32-bit and 64-bit.<br>
- 32-bit CPU/OS can hanfle up to 4GB of RAM.<br>
- RAM is volatile; it will erase its memory once it is off.<br>
- Mass storage device:<br>
      &emsp;- It comes in many form each with variety of purposes, e.g., hard drive.<br>
      &emsp;- Can be built into a computer, like an internal HDD or SSD.<br>
      &emsp;- Can attach storage devices, such as thumb drive or external HDD.<br>
      &emsp;- The internet hosts cloud storage options, such as iCloud and Dropbox.<br>
- Hard Drive: a device that provides long term storage. The data will be erased only if it is deleted or the hard drive dies and its capacity is measured in GBs and TBs.<br>
- Hard drives are described as how much data they can store (capacity) and how fast the data can be accessed (speed). <br>
- 1 digit = 1 bit, 8 bits = 1 byte, 1,204 bytes = 1 kilobyte, 1,024 KB = 1 MB, 1,024 MB = 1GB, 1,024 GB = 1TB.<br>
- Computing purpose determines capacisty needs, e.g. word processing apps do not take a lot of space while video editing does.<br>
- Examples of Mass Storage Devices<br>
      &emsp;1) Internal Hard Drive: a storage device that's installed inside a computer's case and is directly connected to the motherboard and power supply, e.g., SSD (fast) or HDD.<br>
      &emsp;2) Portable External Hard Drive: a storage device that can be connected to a computer or other device to provide extra storage space. Slower than SDD but portable and when need more space, it can be replaced with a bigger space.<br>
      &emsp;3) Optical Media: a type of storage medium that uses a laser to read and write data on discs, e.g., CD, DVD, Blue-ray discs.<br>
      &emsp;4) Mailing Flash Drive: sending a small, rectangular data storage device that uses flash memory through the mail.<br>
      &emsp;5) Cloud Storage: a service that allows users to store data online and access it from any location using the internet or a private network, e.g. iCloud, dropbox.<br>
- Local storage vs network-attached storage:<br>
      &emsp;1) Locals.<br>
      &emsp;2) Network-Attached Storage (NAS): storage accessed via a network and has its own OS because it has internet. <br>
- External hard drive works pretty much the same.<br>
- It matters which port you connect the USB to because the speed is different.<br>
- CD's: 700MB, DVD: 4.7 or 8.5GB, Blue-Ray: 50GB.<br>

## 5.0 - UNDERSTANDING OPERATING SYSTEMS
- Every computing device has an operating system (OS), e.g., windows, macOS, Chrome OS, Linux, iOS, Androids.<br>
- OS provides user interface (a way to interact with the OS), coordination among hardware, monitors health and way to store and retrieve data.<br>
- HWMonitor: help you keep tabs on various hardware parameters in your computer system.<br>
- Most OS have similar user interfaces, but use different names, e.g., Windows has Start Screen and taskbar; macOS has the Dock; Windows uses File Explore, macOS uses Finder.<br>
- Boot camp is used for dual-boot machine but can only be downloaded on mac.<br>
- Without an OS, the computing device can't run any software or other programs.<br>
- Firefox is a third-party browser.<br>
- System applet: where you can find what version of Windows is running on a computer.<br>
- Desktop: where files, folders and shortcuts to files and programs can be seen.<br>
- Devices and printers: where you can see which printers are available for use, and documents is where files you created can be stored.<br>

## 6.0 - SETTING UP AND CONFIGURING A PC
- For overall comfort, the ideal temperature is 72 Fahrenheit and 50% humidity.<br>
- Monitor should be 16-24 inches away from the user.<br>
- The top of the monitor should be lined up with your eye level.<br>
- Make sure your wrists aren't bend awkwardly.<br>
- Set chair height so legs bend at 90 degrees.<br>
- Setup starts with hardware connectivity.<br>
- Personalization: tells us where you live for the time zone. <br>
- Window Defender is automatically installed for security purposes.<br>
- Power strip:  a block of electrical sockets that attaches to the end of a flexible cable (typically with a mains plug on the other end), allowing multiple electrical devices to be powered from a single electrical socket.<br>
- Surge protector: protect electronic equipment from unwanted power surges or "spikes."<br>
- Uninterruptable Power Supply: device that keeps electronics powered on when there is a power failure. A UPS typically has a charged battery that supplies power when there is a power outage.<br>
- Brown Out: a reduction in or restriction on the availability of electrical power in a particular area.<br>
- Black Out: a failure of electrical power supply.<br>
- It is important to have the OS up-to-date to make sure any security holes have been filled and any previous issues (bugs) have been fixed. <br>

## 7.0 - SETTING UP AND CONFIGURING A MOBILE DEVICE
- Accept the EULA.<br>
- End-User License Agreement (EULA) explains what you can or cannot do on a device or with a piece of software and must be agreed to in order to use the device or software.<br>
- Connect to the Internet and update the device's firmware and OS.<br>
- Customize device by adding e-mail and apps.<br>
- Storage: capacity to store files, whatever you bought, you get it with Apple but with Android you can add more because it comes with a SD card.<br>
- Data Usage: how much info is flowing from the cell phone company to your device.<br>
- What you get from LG can be different from what you can get from Samsung because every company who uses Android can customize the OS accordingly.<br>
- Apple devices are in their own ecosystem which provides seamless interataction between its devices.<br>
- Reasons why apps crash: the app is poorly written, the app was written with a specific Android in mind.<br>
- How to solve: wait for a patch, check for the updated versions.<br>
- Synchronize all the apps in the device to the laptop.<br>
- Resolution: the pixels that make up the screen. the finer the pixels, the higher the resolution and vice versa.<br>

## 8.0 - MANAGING FILES
- You can create, copy, paste, move, cut, delete, and permanently delete files.<br>
- When you drag and drop between two different drives, it becomes a copy action.<br>
- Backups data manually or use a program to do it for you.<br>
- Back up to locally attached storage, network attached storage (NAS) and cloud storage.<br>
- Always verify backups.<br>
- Run regularly scheduled backups through default or 3rd party tools.<br>
- Make sure to do backups once a week or at least once a month.<br>
- Indexing: keep tracks of all the files in system not just by date or author but also by contents of the files.<br>
- Hotkeys: combination you can use on the keyboard both in the OS and apps to reduce time consuming by using the mouse.<br>

## 9.0 - USING AND MANAGING APPLICATION SOFTWARE
- Programming: creating an apps to enable users to do stuff.<br>
- Life cycles of application: Install, update, uninstall.<br>
- Installation: insert an optical disk or download the apps from the Internet.<br>
- User Account Control: security feature in Windows to stop malicious software from installing without permission.<br>
- Security Patches: software updates that fix vulnerabilities in a program or operating system to prevent cybercriminals from exploiting them.<br>
- Check for Updates: from the application.<br>
- Uninstall: (Windows) control panels > programs and features.<br>
- File Association: a link between a file type and the application that opens it.<br>
- File Extension: extension that relates with the associate program. e.g.: .docx, .xlsx, .pptx, .eml, .jpg or .jpe, .tif or .png, .zip, .exe (executable files), .mp4 or .avi or .mpg<br>
- Compression Files: squish a big file to a smaller file.<br>
- Well known office productivity applications: Microsoft Office 365, GoogleSuite, OpenOffice<br>
- OneDrive enables sharing and real-time document editing in an online workspace.<br>
- Open source: programmer has created and shared it for free use, but not commercially use. We can change and implement the code if we share it.<br>
- Open source may not have the newest feature and not being updated frequently.<br>
- Remote Access Software: allows for remote access to help through the troubleshooting steps when you are having an issue that you cannot solve. e.g.: AnyDesk, Remote Desktop, Connectwise<br>
- Updating an application as frequent as possible is a must. Microsoft makes update every first Tuesday of the month.<br>
- Browsers: to allow browsing the internet. Each browser generally have default search engine. You can change your preferred search engine. e.g.: Safari -> Google , Chrome -> Google, Brave -> Brave<br>
- Profile Synchronization: when you can go to any device and log in and see your themes, bookmarks, items, and features. It creates a seamless and wonderful user experience from one device to another.<br>
- Extension: embedded application to enhance functionality of the browsers. Extension comes in all size and shape depending on the feature you are looking for, there probably is an extension for it.<br>
- Clearing cache or temporary memory is crucial. Cache stores cookie files that store interactions with different websites, settings, and preffered features. Although it provides enhance user experience, attacker can use it to be able to gather information. Browser history should be cleared out periodically.<br>
- Nothing is completely private but we can increase privacy by using private browser like incognito window.<br>
- Pop-up Blocker: stops potentially annoying or even potentially malicious pop-up from taking your internet browsing experience. It is enabled by default.<br>
- Artifical Intelligence: can analyse data, make suggestions, create contents, solve problems, and make decisions. It is a combination of different components of Computer Science, Mathematics, Cognitive Science as well as other fields.<br>
- Machine Learning: ability of the machine to learn and grow. Made up of three components: representation, evaluation, and optimization.<br>
- Natural Language Processing: ability to understand human language. Consists of understanding, processing, and communication.<br>
- AI Chatbot: a conversational agent. Does not design to do complex features and functions. Can ony handle simple tasks that is mostly pre-design.<br>
- AI Virtual Assistants: can complete more comprehensive assistance and complex activities. Can carry more "real" conversations. e.g.: Siri, Google Assistant.<br>
- Generative AI: an AI-created content. e.g.: ChatGPT, Bard. It can really increase the speed and efficiency.<br>
- AI-Generated Code: a programming that is written in different programming language.<br>
- AI-Generated Content: using natural language processing, machine learning, and deep learning.<br>
- Deep Learning: a deeper lever of machine learning.<br>

## 10.0 - CONFIGURING NETWORK AND INTERNET CONNECTIVITY
- Networking is all about communciating.<br>
- Computing devices can comminucate across great distances if they have the correct information. Proper routing of the data to the right device is important.<br>
- How to accomplish this:<br>
      &emsp;1) Media Access Control (MAC) Address: a 12 digit hexadecimal number assign by the manifacturer that is unique to the network interface of the device. Can be checked through ipconfig /all command -> Physical Address<br>
      &emsp;2) Internet Protocol (IP) Address: like a phone number of the device. Made of 4 sets of numbers separated by dots. Private IP is IP address allocated to the local network.<br>
      &emsp;3) Ports. There is 66,535 ports altogether. Ports 0-1,023 are assigned to specific services. Ports 1,024-65,535 are ephemeral ports with various uses; can be used for many different things and they are very flexible and versatile. <br>
      &emsp;4) Network Interface Card (NIC): the physical connection point between a computer and a network.<br>
      &emsp;5) Peer-to-Peer (P2P) Networks: A home network. A very specific type of LAN, where each devices equals and share resources. Smaller and does not requires a server.<br>
      &emsp;6) Client-Server Model: devices access shared resources within the same LAN. e.g.: Shared office printer.<br>
- Without the RJ45 cable, there is no networking.<br>
- RJ45 standards: Category (cat) 5, 6, and 7.<br>
- The only visible difference is the marking ont he casing.<br>
- Cat 6 and 7 are generally faster and more resistant to interference and can even support two-way communication, while cat 5 is slower and can only support one-way communication.<br>
- Things use for cabling: Cable crimpers, RJ45 ends, and cable testers.<br>
- Main devices that we need to create networks:<br>
      &emsp;1) Modulator/Demodulator: converts from analog to digital and digital to analog. Allows computer to connect to the internet.<br>
      &emsp;2) Switch: a device that connects multiple devices in the network. e.g.: printers, computers, servers on the LANs.<br>
      &emsp;3) Firewalls: it protects from the bad of internets. Can be customised to open and close specific ports, allowing or disallowing specific types of network traffics, in and out of the network. It uses the access control lists to define what traffic is allowed in and out of the network.<br>
      &emsp;4) Access Point: connecting Wi-Fi to the wired network.<br>
- Three different internet access options:<br>
      &emsp;1) Wired: where you plugged in the device into the wall by RJ45.<br>
      &emsp;2) Wireless: Wi-Fi.<br>
      &emsp;3) Cellular: using cellular telephone network.<br>
- Reasons to determine the best home-network: mobility, availability, reliability, throughput, connection delay, latency, number of concurrent connections, and level of security.<br>
- Internet Access Considerations:<br>
      &emsp;1) Mobility: how far you can travel and still can access the network resources.<br>
      &emsp;2) Availability: Probability that a system will be functional.<br>
      &emsp;3) Reliability: Quality of data received and the error checking and correcting capabilities of the technology.<br>
      &emsp;4) Throughput: data transfer rate. e.g.: How quickly does your email download.<br>
      &emsp;5) Latency: connection delay between the reiuqest and the response to the request.<br>
      &emsp;6) Number of Concurrect Connections: number of the simultaneous users who can connect to the internet.<br>
      &emsp;7) Level of Security: How resistant is this connection to some sort of internet base attack.<br>
- Wired always beats wireless and cellular except mobility. <br>
- Internet Connectors:<br>
      &emsp;- RJ45: standard ethernet connector.<br>
![image](https://github.com/user-attachments/assets/31c9f324-0228-407f-9323-ff6b43890382)<br>
      &emsp;- Small Form-Factor Pluggable (SFP): High-speed ethernet connector utilizes fiber optic cabling.<br>
![image](https://github.com/user-attachments/assets/c037ce0f-f962-4d96-8475-1cc781ed7f3a)<br>
- Wired networks do not worry about signal loss or cloud cover. The quality of the data received makes it the most reliable. Data-speed is up to 10GB per sec. Offers the lowest latency, they do not wait for the signal to cross the air, they can be interfered easily. Offers great security as long as you do not let a bad guy plug to the network. <br>
- Wireless or Wi-Fi generally comes second. The freedom to roam is extremely nice.<br>
- Most households are going wireless because it is less expensive, easier to install, and supports all of their computing devices.<br>
- 802.11 is a wireless standard. (Current standard is 802.11ax (Wi-Fi 6)).<br>
- Older standards are more flexible with older devices.<br>
- 6GHz offers the fastest speed but not all devices are compatible with it. 2.4 GHz and 5GHz offer slower connection but still pretty standard. If the device cannot connects to the 6GHz or 5GHz, it can downstep to the 2.4GHz.<br>
- Wi-Fi Channels can overlap and lead to interference or slow internet. By default it is probably fine but you need to consider your environment, if the area is is congested, narrow the channel.<br>
- 6GHz Wi-Fi requires the highest-level security: Wireless Protected Access 3 (WPA3). 2.4 and 5GHz Wi-Fi allow for the lower-security WPA and WPA2. 6GHz does not support WPA2.<br>
- Selecting the highest level of security ensures no one is piggybacking your Wi-Fi for free.<br>
- How to connect to printers: Control panels -> Hardware and Sound -> Devices and Printers -> Select the printer you want to share -> Properties -> Sharing<br>
- Once the printer is shared, it is available to everyone on the network.<br>

## 11.0 - NETWORK SECURITY CONCEPTS
- Successful local computer security means protecting access to your stuff from the bad guy. e.g.: piggybacking your Wi-Fi without us knowing.<br>
- Phishing:
- Unauthorized Access: lock your computer when you walk away from it even for a short period of time. Make sure your account is password-protected.<br>
- Shoulder Surfing: always make sure there is no stranger's shoulders surfing behind you.<br>
- Dumpster Diving: Make sure to shred any trash that you do not want prying eyes to see.<br>
- Encryption: an important security concept when connecting with the world throughtout technology.<br>
- User Data Encryption:<br>
      &emsp;1) Plaintext: easily observe letters and symbols that most peorple can read and understand. Not secure and nothing is hidden.<br>
      &emsp;2) Cyphertext: an encryption in its most basic form. An encryption algorithm is being applied to turn plaintext to cyphertext.<br>
- We need to know what encryption algorithm and what key were used to encrypt the message.<br>
- Data at Rest: not actively being used.<br>
- File-Level Encryption: data that is stored in files or folders in an ecrypted state.<br>
- Disk-Level Encryption: data that is encrypted at a disk-level; which means the entire drive is encrypted rather than just some of the files.<br>
- Mobile Device Encryption: can encrypt data the same way as the computer. Can only disable the encryption oif factory resets it.<br>
- Data in Transit: actively being used. Data is moving from one place to another in encrypted form. e.g.: sending an email, uploading it on cloud.<br>
- Virtual Private Network (VPN): encrypted all data in transit when enabled. It basically creates a tunnel that ensures protection measures are in place all the time. Sacrifices a little bit of speed.<br>
- Data in Use: information that is being actively processed, accessed, or modified by users, devices, or applications. <br>
- AAA: Authentication, Authorization, and Accounting. It is a security framework that controls access to the computer's resources, enforces policies, and audits the users.<br>
      &emsp;1) Authentication: a cybersecurity process that verifies user identity before granting access.
            &emsp;- Types of Authentication:
            &emsp;
      &emsp;2) Authorization: 
      &emsp;3) Accounting: 
