# james200309

#
# Name           : Brute Facebook (BF)                #
# File           : logo.py                            #
# Author         : Moch Yayan Juan Alvredo XD.        #
# Github         : https://github.com/james2000       #
# Facebook       : https://www.facebook.com/james20   #
# Website        : https://www.james20.my.id          #
# Python version : 0.4                                #
#######################################################

############# DON'T REMOVE THIS FUNCTIONS #############


import sys, os, random

#---- MODULE RICH IN PYTHON -------
from rich import print as prints
from rich.panel import Panel

class Logo:

    def __init__(self):
        if "linux" in sys.platform.lower():
            try:os.system("clear")
            except:pass
        elif "win" in sys.platform.lower():
            try:os.system("cls")
            except:free
        else:
            try:os.system("clear")
            except:free

    def log(self):
        WAR = random.choice(["[deep_pink3]","[green]","[cyan]","[blue]"])
        prints(Panel(f"""{WAR}  
    ██████╗██╗  ██╗██╗███╗   ██╗██████╗  █████╗ 
   ██╔════╝██║  ██║██║████╗  ██║██╔══██╗██╔══██╗
   ██║     ███████║██║██╔██╗ ██║██║  ██║███████║
   ██║     ██╔══██║██║██║╚██╗██║██║  ██║██╔══██║
   ╚██████╗██║  ██║██║██║ ╚████║██████╔╝██║  ██║
    ╚═════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝╚═════╝ ╚═╝  ╚═╝                                  
 {WAR}version: 0.4[/]"""))
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
