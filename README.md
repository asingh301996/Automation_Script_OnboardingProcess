# Automation_Script_OnboardingProcess

Prerequisites
* Install the latest version of Python
* Install your preferred Integrated Development Environment (IDE). VS Code is recommended.
* Install MySQL
* (Optional) Install Docker Desktop (the script installs Docker, but you can also install a GUI with it)
* (Optional) Install VMWare Horizon Client
Setup Instructions
* 		Clone this repository to your local machine.
* 		Open a terminal and navigate to the cloned repository's directory.
* 		Run the setup script using the following command:bash  code python3 {BASE_PATH}/setup_script.py    Replace {BASE_PATH} with the actual path to the setup_script.py file.
Usage
* By default, the script installs all required packages. Run the script without any arguments.
* You can also specify specific packages to install using the following format:bash   code python3 {BASE_PATH}/setup_script.py package1 package2 package3   
* Use the -U flag to update packages instead of installing them:bash   code python3 {BASE_PATH}/setup_script.py -U package1 package2   
* Refer to the COMMANDS section in the script for all possible package arguments.
Notes
* This setup script has been tested on MacOS.
* Make sure to have administrative privileges or use sudo if required during package installation.
* For any issues or questions, please contact the repository owner.
