kalbuntu
========

Install kali tools on Ubuntu

####################################################################################
###                             KALBUNTU v1.0                                    ###
###                              By Reaver9                                      ###
###                                                                              ###
###       These files are currently only tested on UBUNTU 12.04.2 LTS i386       ###
###            Only intended for fresh unupdated installs....any other           ###
###            versions or non-fresh installs is done at your own risk           ###
###                                                                              ###
####################################################################################



This read me is just a quick run down of how to install. Lots more information will
be available very soon.

Kalbuntu is just a script to help my self or others install the Kali tools on Ubuntu 
as well as many other packages I use on fresh installs. Install instructions are listed
below. Soon I will include a list of all the changes this version and new versions make.
I hope you enjoy and please let me know if you have any issues.


basic installation

1 Download the package (I will find the best way to do this at a later date)
2 untar the file if necessary depending on how you download it.
3 move the untared file "kalbuntu" to the root directory of your drive
          
               sudo mv /home/yourusername/Downloads/kalbuntu /   

4 open the kalbuntu file and execute the script....you can do this by double clicking the "start" file 
     or by following the commands below.
     
               cd /kalbuntu
               sh start
               
5 now just sit back and let it do its thing.....pay attention for any password prompts and times the script 
needs input from you.


NOTE:    Many packages are 32bit only. Also you can start this from a regular normal user however the script
will unlock root user as well as autologin for root until the script is over, then it will turn off the autologin.
most of the tools from kali MUST be used as the root user only. If you are uncomfortable with being root...then find a 
different hobby. Being a hobby pentester you better get use to breaking shit...it just better be your own.
     
     
     oh yeah that reminds me.....blah blah blah if you break the law, or anything else its your fault blah blah blah dont 
     blame me.
