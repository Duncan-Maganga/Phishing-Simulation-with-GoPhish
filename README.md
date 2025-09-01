## 1. Executive Summary  
This report documents the activities, configurations, and outcomes of a phishing simulation I conducted using the Gophish framework. The exercise involved creating and deploying phishing campaigns with custom landing pages, SMTP configuration, and tracking mechanisms to assess delivery, engagement, and credential submission effectiveness. Key issues such as SMTP authentication errors and improper sender formatting were identified and resolved during the setup process. The simulation was successfully executed, with phishing emails delivered, tracked, and linked to operational landing pages. Captured credential data was securely logged as part of the controlled test.


## 2. Purpose and Scope  

- Provide a detailed record of the phishing simulation workflow, tools, and configurations used.  
- Highlight technical challenges encountered during setup and the solutions implemented.  
- Demonstrate the effectiveness of phishing simulations in identifying vulnerabilities in email security and user awareness.  
- Serve as a reference for refining future phishing campaigns, improving training materials, and enhancing organizational defenses against phishing threats.  


## 3. Tools Used  

- **Gophish Framework:** Used for creating, managing, and launching phishing campaigns.    
- **Web Browser:** Used to interact with the Gophish dashboard and access the landing pages.  
- **Custom HTML Code:** Handwritten fake login pages for credential harvesting simulations.  
- **SMTP Server (Gmail-based):** For sending phishing emails.  
- **Bash:** For server setup, IP configuration, and network testing.  

## 4. Setup  

Start the gophish    
```
wget https://github.com/gophish/gophish/releases/download/v0.12.1/gophish-v0.12.1-linux-64bit.zip  
```

Unzip the contents of file inside the gophish binary 

```
unzip gophish-v0.12.1-linux-64bit.zip
```
Moves the extracted folder so you can access the files inside it.  
```
cd gophish-v0.12.1-linux-64bit
```
make the file executable  
```
chmod +x gophish
```
Run the program  
```
./gophish
```
![sreenshot](images/password.png)



