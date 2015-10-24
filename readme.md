1. Prescripting
Creates a temporary folder based of of the pid for storing files needed to run.

2. Fetching the exploits
fetches an exploit from github

3. Exploit
This script uses an exploit named rocketpipe that exploits a local privelege esclation vulnerability in the DYLD_PRINT_TO_FILE function in the operating system.
Documented here: https://www.sektioneins.de/en/blog/15-07-07-dyld_print_to_file_lpe.html
This script also uses a memory stack buffer overflow privelege escalation exploit written in python.
Documented here: http://luismiras.github.io/muymacho-exploiting_DYLD_ROOT_PATH/

4. Download and install
This script downloads and installs Unity webplayer for mac.

5. Ceanup
This script removes the temporary directory and hopefully removes admin.
