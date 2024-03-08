
## Step 1: Install Node.js 

1.Install curl first:

```bash
sudo apt-get install curl

```

2.Download and execute a script from the NotordeSource reposiy by running the following command:
```bash
sudo curl -fsSL https://deb.nodesource.com/setup_21.x | sudo -E bash

```

3.Install the latest version of Node.js:
```bash
sudo apt-get install nodejs
```

4.Install pm2:
```bash
sudo npm install pm2@latest -g
```

5.Verify that Node.js and NPM are installed correctly:
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
