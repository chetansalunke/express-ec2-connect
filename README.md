Setting up Node.js and NPM using NVM
Step 1: Install Node.js and NPM with NVM

1.Install Node Version Manager (NVM) by running the following command:

sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

2.Activate NVM by running:
. ~/.nvm/nvm.sh

3.Use NVM to install the latest version of Node.js:
nvm install node

4.Verify that Node.js and NPM are installed correctly:
node -v
npm -v

Step 2: Install Git and Clone Repository from GitHub
1.Update the package index:
sudo apt-get update -y

2.Install Git:
sudo apt-get install git -y

3.Verify if Git is installed:
git --version

4.Clone the code repository from GitHub:
git clone https://github.com/chetansalunke/express-ec2-connect.git

5.Navigate to the project directory:
cd express-ec2-connect

6.Install project dependencies:
npm install

Step 3: Start the Application
1.To start the application
npm start

2.Open a web browser and navigate to http://"your-aws-ip":5001 to view the application.
