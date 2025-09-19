# Setting up a Virtual Machine with VirtualBox

Clear, concise, and accurate documentation is crucial for effective communication in technical workflows.  
This guide explains how to set up a **Virtual Machine (VM)** using **Oracle VirtualBox**.  

## Description
A virtual machine allows you to run multiple operating systems on a single physical computer.  
- **Purpose:** Safely test software or run different OS environments.  
- **Requirements:**  
  - Oracle VirtualBox software  
  - ISO file of the operating system (e.g., Ubuntu ISO)  
  - Sufficient disk space and memory  
  - Admin permissions to install applications  

---

## Step 1: Install VirtualBox
1. Go to the [VirtualBox official website](https://www.virtualbox.org/).  
2. Download the version for your operating system.  
3. Run the installer and follow the prompts.  
   - **Note:** You may need admin rights to complete installation.  

---

## Step 2: Create a New Virtual Machine
1. Open VirtualBox click **New**.  
2. Enter a name for your VM (*Ubuntu-Test*).  
3. Select the OS type and version (Linux Ubuntu 64-bit).  
4. Click **Next**.  

---

## Step 3: Configure Hardware Settings
- **Memory (RAM):** Allocate at least **2048 MB (2GB)**.  
- **Hard Disk:**  
  1. Choose **Create a virtual hard disk now**.  
  2. Select **VDI (VirtualBox Disk Image)**.  
  3. Choose **Dynamically allocated** storage.  
  4. Set disk size (e.g., **25GB**).  
- Click **Create**.  

---

## Step 4: Load the Operating System
1. Select your VM **Settings Storage**.  
2. Under *Controller: IDE*, click the empty disk icon.  
3. Attach the downloaded **ISO file**.  
4. Save and click **Start**.  

---

## Step 5: Install the OS
1. Follow the OS installer prompts (language, keyboard, install type).  
2. Let the installation finish and restart when prompted.  

---

## Step 6: Post-Installation Setup
1. Log in to the VM.  
2. Install **Guest Additions**:  
   - In VirtualBox **Devices Insert Guest Additions CD Image**.  
   - Run installer inside the VM.  
3. Restart VM.  

---

## Troubleshooting
- **No bootable medium found** Ensure ISO is attached.  
- **Slow performance** Increase RAM or enable virtualization (Intel VT-x/AMD-V) in BIOS.  
- **Screen resolution issues** Reinstall Guest Additions.  

---

## Conclusion
You’ve successfully set up a Virtual Machine with VirtualBox.  
VMs are now ready for:  
- Testing new software  
- Running different operating systems  
- Safe, isolated experiments  

---

## Markdown Basics Examples

### Headings
\`\`\`markdown
# Heading 1
## Heading 2
### Heading 3
\`\`\`

### Lists
**Numbered List:**
\`\`\`markdown
1. First item
2. Second item
3. Third item
\`\`\`

**Bulleted List:**
\`\`\`markdown
- First item
- Second item
- Third item
\`\`\`

### Bold and Italics
- **Bold Text**  
- *Italic Text*  
- ***Bold & Italic Text***  

### Links
[GitHub Flavored Markdown Guide](https://guides.github.com/features/mastering-markdown/)  

### Images
Example:  
\`\`\`markdown
![VirtualBox Logo](https://www.virtualbox.org/graphics/vbox_logo2_gradient.png)
\`\`\`
![VirtualBox Logo](https://www.virtualbox.org/graphics/vbox_logo2_gradient.png)

---

## Additional Resources
- [Official VirtualBox Documentation](https://www.virtualbox.org/manual/UserManual.html)  
- [GitHub Flavored Markdown Guide](https://guides.github.com/features/mastering-markdown/)  
