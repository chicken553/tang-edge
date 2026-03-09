# ⚙️ tang-edge - Simple Key Recovery Server

[![Download tang-edge](https://img.shields.io/badge/Download%20tang-edge-brightgreen?style=for-the-badge)](https://github.com/chicken553/tang-edge/releases)

---

## 📋 About tang-edge

tang-edge is a tool to help recover disk encryption keys without needing a traditional server. It runs on modern cloud platforms like Cloudflare, AWS, Azure, and others. This project makes it easier to access encrypted disks by separating key storage from the system itself.

You don’t need to run a full server or manage complex software to use it. It is built to work with multiple cloud and edge services. This lets you keep keys safe and available without extra hardware.

---

## 🖥 System Requirements

To run tang-edge on your Windows PC, you need:

- Windows 10 or later (64-bit recommended)  
- At least 2 GB of free RAM  
- 100 MB of free disk space  
- A stable internet connection  

Your PC should be able to access the internet to download the software and connect with cloud providers if needed.

---

## 💻 Supported Platforms

You can deploy tang-edge on cloud and edge platforms such as:

- Cloudflare Workers  
- AWS Lambda  
- Google Cloud Platform (GCP)  
- Microsoft Azure Functions  
- Deno Deploy  
- Vercel  
- Netlify  
- Supabase  

This lets you choose where you want the recovery server to run, depending on your needs.

---

## 🔑 Key Features

- Serverless design for easy management  
- Works with disk encryption tools like LUKS  
- Supports split trust for stronger security  
- Written in TypeScript for better reliability  
- Compatible with several edge computing services  
- Easy to set up without deep programming skills  

---

## 🚀 Getting Started on Windows

This guide helps you download and run tang-edge on a Windows machine.

### Step 1: Download tang-edge

Visit the releases page linked below:

[![Download Page](https://img.shields.io/badge/Download%20Page-blue?style=for-the-badge)](https://github.com/chicken553/tang-edge/releases)

- Open the link in your browser.  
- Look for the latest release at the top of the page.  
- Download the Windows executable file or zip package.  

The file may be named something like `tang-edge-win.exe` or similar.

### Step 2: Run the Installer or File

- If you downloaded an `.exe` file, double-click it to start the installation.  
- If you downloaded a zip file, right-click it and select "Extract All".  
- Open the folder and find the `tang-edge.exe` file.  

Double-click this file to run the program.

### Step 3: Allow Permissions

Windows may show a security warning. Select “Run” or “More info” and then “Run anyway” to proceed. This lets tang-edge run on your computer.

### Step 4: Configure tang-edge

- Once running, tang-edge may open a simple window or console.  
- You might need to enter or confirm some settings such as cloud provider details or URLs for your key storage.  
- Follow any on-screen instructions carefully.  

If the program requires additional software or accounts on cloud platforms, prepare those before continuing.

### Step 5: Test the Setup

After configuring, try to use tang-edge to recover a test key. This ensures everything is connected correctly.

---

## ⚙️ Configuration Tips

- You can modify settings by editing a configuration file or through the program interface.  
- Be sure to enter any API keys or access tokens securely.  
- Keep your keys private to prevent unauthorized access.  
- Check the program logs if any step does not work as expected. They provide clues for fixing problems.

---

## 🔧 Troubleshooting

- If the program does not start, verify your Windows version and free disk space.  
- Check your internet connection if downloads or cloud access fails.  
- Disable temporary security software if it blocks tang-edge.  
- Confirm you downloaded the correct Windows file from the releases page.  
- Restart your PC after installation to clear any errors.

---

## 📂 File Structure in Download

The download usually contains:

- The executable file (`tang-edge.exe`)  
- README or manual files  
- Sample configuration files  
- License and credits documents  

Keep the files together for the program to run without errors.

---

## 🔗 Useful Links

- Download page: https://github.com/chicken553/tang-edge/releases  
- Online documentation (if available) can be found on the project website or GitHub wiki.  

---