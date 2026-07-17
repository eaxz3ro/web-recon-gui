## **Features**

### **Core Functionalities**

| Feature | Description |
|---------|-------------|
| **Source Code Extraction** | Retrieve and analyze HTML source code from target websites |
| **Subdomain Enumeration** | Discover subdomains using wordlist-based DNS resolution |
| **Directory Brute Forcing** | Identify hidden or unprotected directories |
| **Web Technology Analysis** | Detect technologies and frameworks used by websites |
| **WHOIS Lookup** | Retrieve domain registration details and ownership information |

### **User Experience Features**

- **User-Friendly GUI** - Built with Tkinter for enhanced accessibility
- **Save Results** - Export scan results for documentation and further analysis
- **Cross-Platform** - Works on Windows, Linux, and macOS
- **Clear Results** - Reset and clear display areas for subsequent operations
- **Menu Options** - File and Help menus for better interaction
- **Error Handling** - Comprehensive exception management for reliability
- **Modular Design** - Independent modules for future enhancements

---

## **Technologies Used**

### **Programming Language**

Python 3.x         

### **Frameworks**

| Framework | Purpose |
|-----------|---------|
| **Tkinter** | GUI framework |

### **Libraries & Modules**

| Library | Purpose |
|---------|---------|
| **Requests** | HTTP requests handling |
| **DNS Resolver** | DNS resolution for subdomain enumeration |
| **WebTech** | Web technology detection |
| **Subprocess** | System command execution for WHOIS lookup |

---

## **Usage**

Before launching, ensure you have required Python libraries installed.

### **Launch Application**

```bash
python3 webrecon.py
```

### **1. Source Code Extraction**

1. Enter URL (e.g., https://example.com)
2. Click **"Extract Source Code"**
3. HTML source code appears in text area
4. Click **"Clear Source Code"** to reset

### **2. Subdomain Enumeration**

1. Enter domain (e.g., example.com)
2. Click **"Browse"** to select wordlist
3. Click **"Enumerate Subdomains"**
4. Discovered subdomains are displayed
5. Click **"Clear Subdomains"** to reset

### **3. Directory Brute Forcing**

1. Enter base URL (e.g., https://example.com)
2. Click **"Browse"** to select wordlist
3. Click **"Directory Brute Force"**
4. Found directories are displayed
5. Click **"Clear Directory"** to reset

### **4. Web Technology Analysis**

1. Enter target URL
2. Click **"Analyze Web Tech"**
3. Detected technologies are displayed
4. Click **"Clear Web Tech"** to reset

### **5. WHOIS Lookup**

1. Enter domain name
2. Click **"WHOIS Lookup"**
3. Domain registration details appear
4. Click **"Clear WHOIS"** to reset
