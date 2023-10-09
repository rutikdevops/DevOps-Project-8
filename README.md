# 🚀 𝗕𝘂𝗶𝗹𝗱𝗶𝗻𝗴 & 𝗗𝗲𝗽𝗹𝗼𝘆𝗶𝗻𝗴 𝗮 𝗡𝗲𝘁𝗳𝗹𝗶𝘅-𝗖𝗹𝗼𝗻𝗲 𝗔𝗽𝗽! 🚀
# DevOps-Project-8
![image](https://github.com/rutikdevops/DevOps-Project-8/assets/109506158/e0e5f808-2ab9-4185-b8ed-519c55073416)
# Project Blog link :-
<br></br>

# Project Overview :-
- In this Project, I walk you through a clone app that replicates the iconic Netflix user interface, complete with smooth transitions and a database integration for storing user information.
<br></br>

# Project Steps :-
- Create 1 ec2 instance : Netflix : Ubuntu, t2-medium
<img width="960" alt="image" src="https://github.com/rutikdevops/DevOps-Project-8/assets/109506158/ed82d619-c843-4065-8512-796d4be75637">
<br></br>
- Goto Security-> security group-> Edit inbound rules-> Add rule-> choose All Traffic
<br></br>
<img width="960" alt="image" src="https://github.com/rutikdevops/DevOps-Project-8/assets/109506158/fe6d6b36-4f10-4b4d-b994-eac96fda9c39">



# 1. Install and Configure the Docker :-
```bash
ubuntu
sudo su
apt update -y
apt install docker.io -y
```


# 2. Clone the Github code :-
```bash
git clone https://github.com/rutikdevops/DevOps-Project-8.git
cd DevOps-Project-8
```


# 3. Install Required Packages

Install the necessary packages and dependencies for the application using the following command:

```bash
sudo apt install -y curl dirmngr apt-transport-https lsb-release ca-certificates
```

# 4. Install Node.js

Install Node.js, a JavaScript runtime, with the following commands:

```bash
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install -y nodejs
```

### 4. Install Project Dependencies

Navigate to the project directory and install the project-specific dependencies:

```bash
npm install
```

### 5. Start the Application: Works

To start the Netflix clone application, use the following command:

```bash
npm start &
```

### 6. Optional & May Not Work: Serve the Built Application

If you want to serve the built version of the application, you can use the `serve` package. First, install it globally:

```bash
npm install -g serve
```

Then, serve the built application on port 3000:

```bash
serve -s build -l 3000
```

Now you should be able to access the Netflix clone application by opening your web browser and navigating to `http://localhost:3000`.

Enjoy exploring the Netflix clone!



# Pull Docker Image from DockerHub :-
```bash
docker pull rutikdevops/netflix
```
![image](https://github.com/rutikdevops/DevOps-Project-8/assets/109506158/8e168aa8-00c0-4b94-9723-d775c3b9844c)


# Project Reference :-
- https://youtu.be/2XKsUrSyAUg?feature=shared
