# IT-Labs-Borawski

## Environment preparation

Since many people reading this readme might not be familiar with git, I`ve prepared this simple guideline for You to follow if You want to download this code.

1) Install git
   Git is widely used among IT specialists, and if You dont have it installed yet, do it right now [here](https://git-scm.com/downloads)

2) Create Your working directory
   Good practice is to keep Your code separated from other files in the system. Personally I have a `dev` directory under my home folder. But You might keep is just anywhere.

3) Clone this repository
   Enter Your working directory and type `git clone https://github.com/VanDavv/IT-Labs-Borawski.git`.

That's it! You've downloaded these sources!

## Troubleshooting

- `'git' is not recognized as an internal or external command, operable program or batch file.`

   This error means that either You didn't install git correctly or didn't add it to Your $PATH environment variable.
   First, try to repeat step one of environment preparation. If You're sure that git is instlled correctly, follow these steps:

  - Windows
  
    1 Right-Click on My Computer.
    
    2 Click on Advanced System Settings.
    
    3 Click on Environment Variables.
    
    4 Then, under System Variables, look for the path variable and click edit.
    
    5 Add the path to git's bin and cmd at the end of the string like this: `;C:\Program Files\Git\bin\git.exe;C:\Program Files\Git\cmd.`
    
  - Linux or Mac
    
    I bet that noone is having any problems with git on those systems, but if Your this one bad luck brian and have any issues - please follot [Mac](https://www.atlassian.com/git/tutorials/install-git/mac-os-x) or [Linux](https://www.atlassian.com/git/tutorials/install-git/linux) official tutorial




If there are any other troubles that You had during and installation, please contact me personally or post an issue on github [here](https://github.com/VanDavv/IT-Labs-Borawski/issues/new)
    