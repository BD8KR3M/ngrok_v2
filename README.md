ERROR:  Error reading configuration file '/home/kali/.config/ngrok/ngrok.yml': YAML parsing error: yaml: unmarshal errors:
ERROR:    line 2: field authtoken not found in type config.v3yamlConfig

**Now Slove:**
## Frist Remove Ngrok:
 ```
sudo apt remove ngrok -y
or
sudo rm /usr/local/bin/ngrok
Then,
rm /home/kali/.config/ngrok/ngrok.yml
 ```
 ```
sudo apt install git -y
git clone https://github.com/BD8KR3M/ngrok_v2
unzip ngrok_v2
cd ngrok_v2
sudo mv ngrok /usr/local/bin/
 ```
## Install Complate.

 ```
ngrok version
ngrok authtoken 2lf5o***********

cat /home/kali/.config/ngrok/ngrok.yml
 ```
