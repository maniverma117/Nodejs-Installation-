NODEJs INSTALLATION ON UBUNTU
===

## Install & Dependence
- Command to run 
  ```
  apt update
  
  apt install xz-utils
  
  apt install wget
  
  cd /opt
  
  ```

## Use
- for download 
  ```
  wget https://nodejs.org/dist/v20.11.1/node-v20.11.1-linux-x64.tar.xz
  
  ```
- for specific versions 

   [download](https://nodejs.org/dist/)
 
## Command to run to set default NodeJs version
- 
  ```
  tar -xvf node-v20.11.1-linux-x64.tar.xz
  
  mv node-v20.11.1-linux-x64/ node-20js
  
  echo "export PATH=$PATH:/opt/node-20js/bin" >> ~/.bashrc
  
  source ~/.bashrc
  
  node -v
  
  npm -v
  
  ```
