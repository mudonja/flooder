For educational purposes only.
I am not responsible for any damage caused by this program.

+++++++++++++++++++INSTRUCTIONS+++++++++++++++++++++++++++++

Requirements:
		Python3.8(Version used while coding and testing the tool)
		Scapy

Setup Steps and Explanation:

Since I had to modify scapy source code to make IP spoofing faster 
I am also sending you the modified scapy file which you will have to 
substitute instead of the original scapy

In order to do this, go into your python3 scapy folder
(for my pc the location is: " /home/username/.local/lib/python3.6/site-packages/scapy")

Rename the python file called "sendrecv.py" to something else (eg. oldSendrecv.py)

Add sendrecv.py from pulled repo and put it in the your scapy folder(/home/username/.local/lib/python3.6/site-packages/scapy)


"Sudo python3 ./udpflooder -src rand -p 999999 -s 999999 10.0.0.2"
*Six nines is value for random port and size*

