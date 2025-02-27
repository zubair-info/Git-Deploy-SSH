Setting Up SSH with PuTTY for Git Deployment
#Step 1: Install PuTTY
Download and install PuTTY for your OS from PuTTY’s official website.

#Step 2: Generate/Open SSH Key in PuTTYgen
Open PuTTYgen (search for it in Windows).
Click Load and select your existing private key file (if provided by the server).
If you need a new key:
Click Generate, move your mouse randomly to generate entropy, and save it.
Save the private key with the .ppk extension (PuTTY will handle the format automatically).
#Step 3: Configure PuTTY to Use the SSH Key
Open PuTTY.
Enter your server IP or hostname under “Host Name (or IP address)”.
In the left sidebar, go to Connection → SSH → Auth.
Under Credentials, click Browse and select your saved .ppk private key.
Click Open to start the SSH session.
If prompted, accept the server's fingerprint.
