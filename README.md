# BASH-Compliance-Check

##########################
# Welcome to the read me.
##########################

# TAKE NOTE!!!: To run this script make sure you allow yourself to execute it by using 'çhmod +x "whatever you name this script"'
# For example: if you name this script "Finder" do this 'chmod +x Finder'
# this will allow you to execute this script.


# TAKE NOTE: For some parts of the script you will be prompted for your password for SUDO just remember this!.


# TAKE NOT AGAIN!: To run this script use './' 
# For example: Lets say I titled this script "Finder" do run it type './Finder' 

#################################################################################################

# This script was made for the purposes of checking and enforcing system compliance.
# This script will check certain packages,user configurations, and security settings.

#################################################################################################

# First CAT 1 (Telnet package check Group ID: V-238326
# Purpose:This script checks to see if you have the telnet package installed on your system. If the script finds telnet installed it will prompt you with the option to remove it.

#################################################################################################

# Second CAT 1 (RSH-Server Package Check Group ID:238327
# Purpose:This script checks to see if you have the rsh-server package installed on your system. If the script finds rsh-server installed it will prompt you with the option to remove it.

#################################################################################################

# Third CAT 1 (Blank Password Check Group ID:251503)
# Purpose:This script checks to see if any users on the linux system have blank passwords.
#If it is found that a user has a blank password the script will give you options on what you can do to remidiate this vulnerabilty.
#One option you are prompted with is to lock a certain user account with the blank password.
#The second option you are given is to perform a password reset on a user account with a blank password.
 
#################################################################################################

# First CAT 2 (Session Lock Check Group ID:238199)
# Purpose:This script checks to see if you have session lock enabled on your system. If the script finds that session lock is disabled it will prompt you asking if you want to enable it.

#################################################################################################

# Second CAT 2 (Minimum Password Length Check Group ID:238225
# Purpose:This script checks to see what your systems mimumum password length requirement is.
# If it finds that it is anything less than 15 characters it prompts you with the option to change it.
# You will be prompted with the option to change the min length to 15 or leave your settings as is.

#################################################################################################
#
#Usage Instructions:

 #   Telnet and RSH-Server Checks:
 #       The script will prompt if the respective packages are found and offer options for removal.
 #       Respond with 'y' or 'n' to proceed or cancel the package removal.

 #  Blank Password Check:
 #       If users with blank passwords are found, you'll be prompted to:
 #           Lock specific accounts by entering '1'.
 #           Perform password resets for identified accounts by entering '2'.

 #   Session Lock Check:
 #       If session lock is disabled, you'll be prompted to enable it by entering 'y'.

 #   Minimum Password Length Check:
 #       If the minimum password length is less than 15 characters, you'll be asked if you want to change it. Respond with 'y' to enforce a 15-character minimum or 'n' to do nothing.

 # Extra Notes:

 #   Always review and confirm any changes prompted by the script.
 #   Run this script with appropriate permissions (e.g., sudo) to ensure proper execution.
 #   Confirm each action carefully as they may impact system configurations and user accounts.







