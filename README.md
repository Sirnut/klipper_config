# klipper_config
This is the repository where I post files for my Ender 3V2 lovingly named TheFactory after one of my favorite games, Factorio

I don't know if anyone will ever be checking it out to help their build, but most of my macros have been from other builds across the web

# My build TheFactory
Barely stock Ender 3V2 with main following upgrades as of 6/14:
- BTT SKR Mini E3 3.0 (after accidentally stabbing my stock 4.2.2 board with a screwdriver)
- Dual Z axis
- BMG+V6 Direct Drive
- CRTouch Probe
- PEI bed (wish I had done this first)

My printer then runs klipper, which allows me to quickly and easily update everything. Marlin works out of the box, but klipper really lets you push the limits of your printing. [BenD780x9 has a fantastic guide to setting klipper up on the Ender 3V2](https://github.com/BenD780x9/Klipper-for-Ender_3_v2) and then kiauh, [theexitus's Klipper Install And Uninstall Helper is the best way to manage your installations and updates](https://github.com/th33xitus/kiauh)

# OVERVIEW
Generate SSH keys from your Pi and upload the public key to github. The [Guide to generating and adding SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) is helpful for the initial connection, but I was only able to push/pull with terminal commands

VSC has something called Source Control that manages all of your changes and provides a GUI to see these, label them and then push with the click of a button. SSH wouldn't work with this, but after setting up my repository with HTTPS I've had no issues. Use this guide to learn [How to push code from VSC to GitHub](https://www.sachinsf.com/how-to-push-the-code-from-vs-code-to-github/#:~:text=Using%20GitHub%20with%20Visual%20Studio%20Code%20allows%20you,install%20the%20%E2%80%9CGithub%20Pull%20Requests%20and%20Issues%E2%80%9D%20extension.)


# Other Awesome Repositories
[jschuh's klipper-macros are awesome](https://github.com/jschuh/klipper-macros.git)

[AndrewEllis93 has a great print tuning guide](https://github.com/AndrewEllis93/Print-Tuning-Guide)
