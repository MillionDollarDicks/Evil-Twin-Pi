# Evil-Twin-Pi

Attack runs as a subprocess, so the ssh session can be terminated and the attack will continue. RGB LED used as status indicator(pin connections in script). Captures are stored in the web directory. I have not bothered to varify whether the user entered passwords are correct so the script does not capture handshakes. 

Iv used three wireless adapters (one for deauthing - one for the cloned AP - one for connecting to the pi) could probably be done with just one if you can be bothered to modify the code. Infact the whole script could be improved upon! This was a rushed project, at the time I wanted something similar to fluxion but could run headless and stripped down to the basics.

Install the dependencies and run evil.py (with sudo privileges)


