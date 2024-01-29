### Setup PC
#### Install Python 3
1. Go to the official Python download page for Windows. https://www.python.org/downloads/windows/
2. Find a stable Python 3 release. 
3. After the installer is downloaded, double-click the .exe file, for example python-3.10.10-amd64.exe, to run the Python installer.
4. Select the **Install launcher for all users** checkbox, which enables all users of the computer to access the Python launcher application.
5. Select the **Use admin privileges when installing py.exe**.
6. Select the **Add python.exe to PATH** checkbox, which enables users to launch Python from the command line.
7. click **Install Now**
8. The **Optional Features** include common tools and resources for Python and you can install all of them, even if you don’t plan to use them.
  Select some or all of the following options:
  - **Documentation**: **SELECT THIS OPTION**
  - **pip**: **SELECT THIS OPTION** if you want to install other Python packages, such as NumPy or pandas
  - **tcl/tk and IDLE**:  **SELECT THIS OPTION** if you plan to use IDLE or follow tutorials that use it
  - **Python test suite**: **SELECT THIS OPTION** for testing and learning
  - **py launcher** and **for all users**: **SELECT THIS OPTION** to enable users to launch Python from the command line
9. Click **Next**.
10. The **Advanced Options** dialog displays.
  Select the options that suit your requirements:
  - **Install for all users**: **SELECT THIS OPTION** if you’re not the only user on this computer
  - **Associate files with Python**: **SELECT THIS OPTION**, because this option associates all the Python file types with the launcher or editor
  - **Create shortcuts for installed applications**: **SELECT THIS OPTION** to enable shortcuts for Python applications
  - **Add Python to environment variables**: **SELECT THIS OPTION** to enable launching Python
  - **Precompile standard library**: not required, it might down the installation
  - **Download debugging symbols** and **Download debug binaries**: recommended only if you plan to create C or C++ extensions
Make note of the Python installation directory in case you need to reference it later.
11. Click Install to start the installation.
12. After the installation is complete, a Setup was successful message displays.
    
####  Verify the Python Installation
You can verify whether the Python installation is successful either through the command line or through the Integrated Development Environment (IDLE) application, if you chose to install it.

1. Click on the **Search** next to Start icon and enter **cmd** in the search bar. Click **Command Prompt**.
2. Enter the following command in the command prompt:
   ```text
   python --version
   '''
3. An example of the output is:
   > Python 3.10.10

#### Install PySerial
1. open the Windows terminal
2. Install pyserial by type in the command below
   ```text
   pip3 install pyserial
   ```

