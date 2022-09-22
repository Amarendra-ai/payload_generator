# payload_generator

## Usage

1) Create a payload

    Create payloads for android, windows and linux

2) Start Listner

    after creating the payload send it to the target's device, open listener, select LHOST and LPORT.
    Now wait until a successfull connection.

3) Launch Metasploit

    Start Metasploit using Launch Metasploit option.

## installation

sudo apt-get install python3 python3-pip net-tools

git clone https://github.com/Amarendra-ai/payload_generator.git

cd pay

sudo pip3 install -r requirements.txt

python3 pay.py
