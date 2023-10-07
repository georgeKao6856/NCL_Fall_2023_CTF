## Network Traffic Analysis

**Tools:**

1. Wireshark

**Concepts:**

1. DNS
2. FTP
3. HTTP
4. Telnet
5. Pandora

**Questions:**

(DNS)

1. What is the type of the DNS query requested?
    
    Ans: AXFR
    
    ![Untitled](../Screenshot/Untitled%2038.png)
    
2. What domain was requested?
    
    Ans: etas.com
    
    ![Untitled](../Screenshot/Untitled%2039.png)
    
3. How many items were in the response?
    
    Ans: 4
    
    ![Untitled](../Screenshot/Untitled%2040.png)
    
4. What is the TTL for all of the DNS records?
    
    Ans: 3600
    
    ![Untitled](../Screenshot/Untitled%2041.png)
    
5. What is the IP address for the "welcome" subdomain?
    
    Ans: 1.1.1.1
    
    ![Untitled](../Screenshot/Untitled%2042.png)
    

(FTP)

1. What was the first username:password combination attempt made to log in to the server? ex. 'user:password’
    
    Ans: user1:cyberskyline
    
    ![Untitled](../Screenshot/Untitled%2043.png)
    
2. What software is the FTP server running? (Include name and version)
    
    Ans: FileZilla Server 0.9.53 beta
    
    ![Untitled](../Screenshot/Untitled%2044.png)
    
3. What is the first username:password combination that allows for successful authentication? ex. 'user:password’
    
    Ans: user1:metropolis
    
    ![Untitled](../Screenshot/Untitled%2045.png)
    
4. What is the first command the user executes on the ftp server?
    
    Ans: List
    
    ![Untitled](../Screenshot/Untitled%2046.png)
    
5. What file is deleted from the ftp server?
    
    Ans: bank.cap
    
    ![Untitled](../Screenshot/Untitled%2047.png)
    
6. What file is uploaded to the ftp server?
    
    Ans: compcodes.zip
    
    ![Untitled](../Screenshot/Untitled%2048.png)
    
7. What is the filesize (in bytes) of the uploaded file?
    
    Ans: 28183
    
8. What file does the anonymous user download?
    
    Ans: compcodes.zip
    
    ![Untitled](../Screenshot/Untitled%2049.png)
    

(HTTP)

1. What Linux tool was used to execute a file download?
    
    Ans: wget
    
    ![Untitled](../Screenshot/Untitled%2050.png)
    
2. What is the name of the web server software that handled the request?
    
    Ans: nginx
    
    ![Untitled](../Screenshot/Untitled%2051.png)
    
3. What IP address initiated request?
    
    Ans: 192.168.1.140
    
    ![Untitled](../Screenshot/Untitled%2052.png)
    
4. What is the IP address of the server?
    
    Ans: 174.143.213.184
    
5. What is the md5sum of the file downloaded?
    
    Ans: 966007c476e0c200fba8b28b250a6379
    
    ![Untitled](../Screenshot/Untitled%2053.png)
    
    ![Untitled](../Screenshot/Untitled%2054.png)
    

(Telnet)

1. What is the username that was used to log in?
    
    Ans: test
    
    ![Untitled](../Screenshot/Untitled%2055.png)
    
2. What is the password that was used to log in?
    
    Ans: capture
    
3. What command was executed once the user was authenticated?
    
    Ans: uname
    
4. In what year was this capture created?
    
    Ans: 2011
    
5. What is the hostname of the machine that was logged in to?
    
    Ans: cm4116
    
6. What CPU architecture does the remote machine use?
    
    Ans: armv4tl
    

(Pandora)

1. What is the IP address of the server?
    
    Ans: 10.1.0.20
    
    ![Untitled](../Screenshot/Untitled%2056.png)
    
2. What is the IP address of the client?
    
    Ans: 10.1.0.217
    
3. What port is the server listening on?
    
    Ans: 60123
    
4. What is the magic 2-byte ID in decimal representation?
    
    Ans: 0x0417
    
    ![Untitled](../Screenshot/Untitled%2057.png)
    
    ![Untitled](../Screenshot/Untitled%2058.png)
    
5. How many encrypt requests were made by the client?
    
    Ans: 5
    
6. What is the length of the first encrypt request?
    
    Ans: 88 (0x58)
    
7. What is the length of the second encrypt request?
    
    Ans: 72 (0x48)
    
    ![Untitled](../Screenshot/Untitled%2059.png)
    
8. How large is an individual encrypt hash in bytes?
    
    Ans: 32
    
    (0xa0)/(0x05)=160/5=32
    
9. What was the encrypt response in hexadecimal form (e.g. FFFF) for the first request?
    
    Ans: b8c97b08e198fa9ff79a3a9c1f0109b18687b7a1a3ff1772c29b4dc86753d711
    
    ![Untitled](../Screenshot/Untitled%2060.png)
    
10. What was the encrypt response in hexadecimal form (e.g. FFFF) for the second request?
    
    Ans: 8817153ae81d94b5d6c745e63d1df31d5d02bd3b030b820c3c038654fdca619c
    
    ![Untitled](../Screenshot/Untitled%2061.png)
    
11. What is the hidden flag being sent over the protocol?
    
    Ans: NCL-FJCG-1632
    
    ![Untitled](../Screenshot/Untitled%2062.png)
    
    ![Untitled](../Screenshot/Untitled%2063.png)