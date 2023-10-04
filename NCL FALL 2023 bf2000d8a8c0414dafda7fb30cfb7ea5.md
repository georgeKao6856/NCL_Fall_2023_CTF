# NCL FALL 2023

Created: September 5, 2023 10:34 AM

# Contents

# **Gymnasium**

## Open Source Intelligence

**Tools:**

1. Google Search

**Concepts:**

1. Photo metadata
2. DNS lookup
3. HTTP header
4. SSL
5. Barcode
6. Threat Intelligent

## Cryptography

**Tools:** 

1. [Cyberchef](https://gchq.github.io/CyberChef/)
2. [dCode Website](https://www.dcode.fr/caesar-cipher)
3. [CrackStation](https://crackstation.net/)
4. [Digital Invisible Ink Toolkit](https://diit.sourceforge.net/)

**Concepts**:

1. Caesar Cipher
2. Morse code
3. Hex
4. Base64
5. Binary
6. Rail fence cipher
7. Polyalphabetic substitution ciphers
8. Steganography

## Password Cracking

**Tools:**

1. Hashcat
2. John the Ripper
3. crunch
4. [MD5Hashing Website](https://md5hashing.net/hash/md5/a532443f3e04a9e00295a8cd2a75e080)
5. [ophcrack](http://ophcrack.sourceforge.net/download.php?type=ophcrack)

**Concepts:**

1. MD5
2. NTLM

## Forensics

**Tools:**

1. Git command
2. Linux command
3. binwalk

**Concepts:**

1. Git
2. Extract files in a picture

**Question:** 

1. This file initially looks like something green, what's the file format of this green file?
    
    **Ans: PNG**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled.png)
    
2. How many files can be extracted from the binary blob?
    
    **Ans: 6**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%201.png)
    
3. What is the hidden flag in the file?
    
    **Ans: SKY-RWCI-4291**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%202.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%203.png)
    

## Log Analysis

**Tools:**

1. awk
2. uniq
3. sort

**Concepts:**

1. SSH log
2. nginx log
3. SQL
4. Squid Proxy

**Questions:**

1. How many different IP addresses reached the server? (nginx)
    
    **Ans: 47**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%204.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%205.png)
    
2. How many requests yielded a 200 status? (nginx)
    
    **Ans: 19**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%206.png)
    
3. How many requests yielded a 400 status? (nginx)
    
    **Ans:38**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%207.png)
    
4. What IP address rang at the doorbell? (nginx)
    
    **Ans: 186.64.69.141**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%208.png)
    
5. What version of the Googlebot visited the website? (nginx)
    
    **Ans: 2.1**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%209.png)
    
6. Which IP address attempted to exploit the shellshock vulnerability? (nginx)
    
    **Ans: 61.161.130.241**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2010.png)
    
7. What was the most popular version of Firefox used for browsing the website? (nginx)
    
    **Ans: 31.0**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2011.png)
    
8. What is the most common HTTP method used? (nginx)
    
    **Ans: GET**
    
9. What is the second most common HTTP method used? (nginx)
    
    **Ans: CONNECT**
    
10. How many requests were for \x04\x01\x00P\xC6\xCE\x0Eu0\x00? (nginx)
    
    **Ans: 6**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2012.png)
    

## Wireless Access Exploitation

**Tools:**

1. Wireshark
2. aircrack-ng

**Concept:**

1. WEP
2. deauth attack

**Questions:**

(Part 1)

1. How many IVs are in the packet capture?
    
    Ans:14337
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2013.png)
    
2. What is the key size of the wireless network data encryption method in bits?
    
    Ans: 64
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2014.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2015.png)
    
3. What is the IV for the first packet in the capture in hexadecimal representation?
    
    Ans: 003a33
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2016.png)
    
4. What is the WEP key?
    
    Ans: A4:81:53:B4:CF
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2017.png)
    
5. What is the TCP checksum of the first packet in the capture (in hex)?
    
    Ans: 897b
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2018.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2019.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2020.png)
    

(Part 2)

1. How many IVs are in the packet capture?
    
    Ans: 24592
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2021.png)
    
2. What is the key size of the wireless network data encryption method in bits?
    
    Ans: 128
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2022.png)
    
3. What is the IV for the first packet in the capture (in hex)?
    
    Ans: 0994ff
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2023.png)
    
4. What is the WEP key?
    
    Ans: DE:AD:10:CC:D1:5E:A5:EC:DC:C2:D6:7A:CA
    
5. What is the TCP checksum of the first packet in the capture (in hex)?
    
    Ans: 08f0
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2024.png)
    

(Part 3)

1. What is the MAC address of the router?
    
    Ans: c0:4a:00:80:76:e4
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2025.png)
    
2. What is the ESSID of the wifi network?
    
    Ans: TP-LINK_8076E4
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2026.png)
    
3. What is the password for the wireless network?
    
    Ans: blueberrymuffin
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2027.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2028.png)
    
4. What is the IP address of the router?
    
    Ans: 
    
5. What company manufactured the router?
    
    Ans: TP-LINK
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2029.png)
    
6. What is the model of the router?
7. What firmware version is installed on the router?
8. What release number is the router using?
9. What is the IP address of the user who logged into the router admin panel?
10. What is the MAC address of the first victim of the deauth attack?
    
    Ans: b8:e8:56:47:44:38
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2030.png)
    
    [https://semfionetworks.com/wp-content/uploads/2021/04/wireshark_802.11_filters_-_reference_sheet.pdf](https://semfionetworks.com/wp-content/uploads/2021/04/wireshark_802.11_filters_-_reference_sheet.pdf)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2031.png)
    
11. What is the MAC addess of the second victim of the deauth attack?
    
    Ans: 80:e6:50:0b:26:ba
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2032.png)
    

## Scanning

**Tools:**

1. nmap
2. gobuster
3. dirbuster

**Concepts:**

1. Website directory scanning
2. Linux machine scanning

## Network Traffic Analysis

## Enumeration & Exploitation

**Tools:**

1. [Online Python Compiler](https://www.programiz.com/python-programming/online-compiler/#google_vignette)
2. [Online Python uncompiled tool](https://tool.lu/pyc/)
3. disassembler
4. gdb
5. [Ghidra](https://ghidra-sre.org/)

**Concepts:**

1. Python
2. Python uncompiled
3. binary
4. assembly code

**Questions:**

1. What is an input to this program that will result in a correct validation?
    
    **Ans: eSeeeeeeem**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2033.png)
    
2. What is an input to this program that will result in a correct validation?
    
    **Ans: mysupersecretpassword**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2034.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2035.png)
    
3. What is an input to this program that will result in a correct validation?
    
    **Ans: NCLNNL11111**
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2036.png)
    
    ![Untitled](NCL%20FALL%202023%20bf2000d8a8c0414dafda7fb30cfb7ea5/Untitled%2037.png)
    
4. What is the flag hidden in the program? (binary)
    
    

## Web Application Exploitation

---

# Practice Game

## Open Source Intelligence

## Cryptography

## Password Cracking

## Forensics

## Log Analysis

## Network Traffic Analysis

## Scanning

## Wireless Access Exploitation

## Enumeration & Exploitation

## Web Application Exploitation

---

# Individual Game

## Open Source Intelligence

## Cryptography

## Password Cracking

## Forensics

## Log Analysis

## Network Traffic Analysis

## Scanning

## Wireless Access Exploitation

## Enumeration & Exploitation

## Web Application Exploitation

---

# Team Game

## Open Source Intelligence

## Cryptography

## Password Cracking

## Forensics

## Log Analysis

## Network Traffic Analysis

## Scanning

## Wireless Access Exploitation

## Enumeration & Exploitation

## Web Application Exploitation