
# Project Title

A brief description of what this project does and who it's for



## Step 1: Install Node.js and NPM with NVM

1.Install Node Version Manager (NVM) by running the following command:

```bash
sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

```



2.Activate NVM by running:
```bash
. ~/.nvm/nvm.sh
```

3.Use NVM to install the latest version of Node.js:
```bash
nvm install node
```

4.Verify that Node.js and NPM are installed correctly:
```bash
node -v
npm -v
```

## Step 2: Install Git and Clone Repository from GitHub

1.Update the package index:

```bash
sudo apt-get update -y
```

2.Install Git:
```bash
sudo apt-get install git -y
```

3.Verify if Git is installed:
```bash
git --version
```
4.Clone the code repository from GitHub:
```bash
git clone https://github.com/chetansalunke/express-ec2-connect.git
```
5.Clone the code repository from GitHub:
```bash
git clone https://github.com/chetansalunke/express-ec2-connect.git
```
6.Navigate to the project directory:
```bash
cd express-ec2-connect
```
7.Install project dependencies:
```bash
npm install
```


## Step 3: Start the Application

1.To start the application:

```bash
npm start
```

2.Open a web browser and navigate to:
```bash
http://"your-aws-ip":5001
```
to view the application