# Syllabus Overview


## Module 1: Digital Identity & Authentication

### CS & Security Concepts
Basic programming constructs: functions, loops, conditionals; concept of a protocol (syntax, semantics, synchronization); hardness amplification; digital identity and the factors of authentication; limits of password and two-factor authentication

### Laboratory Challenges
  1. A contrived web service protected by a set of increasingly difficult to crack passwords. Students must write their own online password cracker leveraging a variety of attack techniques (e.g. brute force, dictionary, and parallelization). Students ultimately find and use a two-factor authentication device used to protect a Google Drive account.


## Module 2: Human Factors & Physical Security

### CS & Security Concepts
The role of physical security in cybersecurity; psychological phenomena that affect security; social engineering and impersonation; economic motivations for malware and spam

### Laboratory Challenges
1. Picking simple locks protecting physical lockers containing flags;
2. As a group, students are tasked with building a website designed to masquerade as a popular online service of your choice. Teams then craft and execute a phishing attack designed to lure instructor to the site.


## Module 3: Securing the Web

### CS & Security Concepts
Client-server model; Introduction to HTTP (how pages move), HTML (how pages are represented), and JavaScript (how we interact with pages); Common web application security vulnerabilities and attacks; Code vs. data

### Laboratory Challenges
1. Inspecting the HTML of the instructor's home page reveals a flag hidden in comments;
2. Manipulating a malleable HTTP cookie to set one's role to admin;
3. A simple reflected cross-site scripting attack;
4. A more complex stored cross-site scripting attack that causes an administrator to give a user admin privileges by visiting a user-controlled comment page.

## Module 4: Digital Forensics

### CS & Security Concepts
Common data representations (\eg binary, octal, hex), encoding schemes (\eg base64, ASCII), and file formats (\eg text, images, binaries); I/O subsystem basics; searching algorithms over organized data; common digital forensic techniques and tools

### Laboratory Challenges
1. A bitmap image of a QR code that encodes a flag, but whose metadata has been altered to render with a width of 1 pixel; 
2. Two files (jpeg and gif) with steganographically hidden flags;
3. An XML file whose structure contains a flag, but which will fail to parse and needs manual editing; 
4. An ext3 disk image with many thousands of directories and files, only one of which contains the flag.


## Module 5: Securing the Network

### CS & Security Concepts
OSI model/Internet protocol suite; encapsulation; fault-tolerance; eavesdropping and network forensics

### Laboratory Challenges
1. Write a simple TCP-port scanner to find a hidden web service; 
2. Using command-line tools to tell a knock-knock joke using port-knocking;
3. Analyzing two PCAP files for (a) a Google query for the flag, and (b) Recovering a jpeg image transferred via FTP;
4. Writing a client that is compliant with a simple, silly challenge-response protocol described in a contrived, IETF RFC-style document.


## Module 6: Secret Communication

### CS & Security Concepts
Confidentiality vs. authenticity; usable security

### Laboratory Challenges
1. A Caesar-shift and mono-alphabetic substitution cipher whose lengths require a programatic solution; 
2. An automated GPG service that delivers a public key, and expects an encrypted request for a flag; 
3. An automated GPG service that expects a public a key, and delivers a flag encrypted with that key.


## Module 7: Software Security

### CS & Security Concepts
Control flow and hijacking; malicious input & fuzzing

### Laboratory Challenges
1. Programatically finding an input to a precompiled binary that causes it to crash.
2. An short integer overflow.
3. Simple stack variable overflow into a sentinel value.
