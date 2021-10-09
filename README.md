# FiveM Management Console (1.0)
Allows you to manage your FiveM server with a text based GUI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/FiveMManagementConsole) - [Official Forum](https://gta.gameplayer.club/index.php/forum/our-gta-tools)


---

Edit "fmc" and change the settings at the top if your FiveM server is not in /home/fivemowner/fivem_resources.

You will need to run cpan (as root) and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen

You also need to have my FiveM Startup Script installed.

I suggest you then add this to your /home/fivemowner/.bashrc file:
	export PATH=/home/fivemowner/bin:/home/fivemowner/FiveMManagementConsole:$PATH

After that you should log out and back in and now "fmc" should work.
