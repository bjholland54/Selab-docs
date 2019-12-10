## Install the Automation API CLI

### Install Node.js

[Download Node.js Installer here](https://nodejs.org/en/download/)

The Node.js installer includes the npm (Node Package Manager) utility.
 Run the installer and follow the instructions on screen.

To verify that you have the required version of Node.js (4.x or later) and npm (3.x or later), enter the following commands into a command prompt:

* `node -v`
* `npm -v`

### Download the Control-M Command Line Interface (CLI) Utility

[Download the ctm-cli.tgz node package here **UPDATE with correct link**](https://vl-cpo01.ctm.bmc.com:8443/automation-api/ctm-cli.tgz)

### Install the Control-M CLI Utility

To install the ctm-cli.tgz node package and enter the following command from the directory where you saved the ctm-cli.tgz file:

* `npm -g install ctm-cli.tgz`

### Download the Control-M Completion Script

**UPDATE with blurb about what completion script is about**

[Download the blahblah.sh completion script here **UPDATE with correct link**](https://github.com/controlm/automation-api-community-solutions)

### Run the Control-M Completion Script

Steps to run script **UPDATE**

### Set up a Control-M environment

If you have access to a Control-M instance, use the following command to add an environment. In this example, the environment is named **vl-cpo01**:

* `ctm env add vl-cpo01 "https://vl-cpo01.ctm.bmc.com::8443/automation-api"
"[ADPRODUser]" "[ADPRODPassword]"
`

### Set the environment as default

All commands invoked will use the default environment.
The following example command shows how to set an environment named vl-cpo01 as your default environment. The returned response lists all existing environments.

* `ctm env set vl-cpo01`

### Verify the setup by logging into a session

After setting up the Control-M environment for the CLI, ensure that the user associated with the default environment can successfully log in to a CLI session. For a workbench environment, the user is named workbench. For any other Control-M environment, the user is specified during environment setup.
To log in to a CLI session, use the Session Service. The response returns the user name, a token for the session, and the version of the CLI, as shown in the following example:

* `ctm session login`

## Install Putty

[Download PuTTY from here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)

## Install Git

[Download Git from here](https://git-scm.com/downloads)

Once downloaded, enter in the following commands in CMD.
Replace "jdoe" with your ADPROD account, and first_last@bmc.com with your BMC email. They will successfully complete without output.

* `git config --global user.name jdoe`
* `git config --global user.email first_last@bmc.com`
* `git config --global credential.helper "cache --timeout=3600`
* `git config --global -l` # This will show the current git configuration

