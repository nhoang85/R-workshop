#INSTALL R:
On a Windows machine:
● Navigate to this website: https://cran.r-project.org/bin/
● Click on "Download R-4.4.1 for Windows"
● Run the downloaded .exe file, and follow the instructions.
On a Mac:
● Navigate to this website: https://cloud.r-project.org/bin/macosx/
● Click on "R-4.4.1-arm64.pkg" or "R-4.4.1-x86_64.pkg" depending on the chip you have.
○ If you're not sure of your chip, click on the apple logo on the top right of the
screen, and click on "About This Mac".
○ If it says something like "Chip: Apple M1 Pro", download the R package under
"For Apple silicon (M1-3) Macs:".
○ If it says something like "Processor: XXX Intel XXX", download the R package
under "For older Intel Macs".
● Run the downloaded .pkg file, and follow the instructions.

#INSTALL RStudio:
On all machines:
● Navigate to this website: https://posit.co/download/rstudio-desktop/
● Under "2: Install RStudio", it should have auto-detected your operating system. For
instance, the button will say "Download RStudio Desktop for MacOS 12+" if you have a
Mac. Click on the button, run the downloaded file, and follow the instructions.
● IF the OS on the button doesn't match your system, scroll down and download the
package that matches your machine, and run the downloaded file.

#AFTER INSTALLING RStudio:
● Open RStudio.
● In the console, type the following command
R.Version()
And hit enter (Note: commands are case-sensitive)
● If R is correctly installed, you should get an output that looks something like this:
$platform
[1] "aarch64-apple-darwin20"
$arch
[1] "aarch64"
$os
[1] "darwin20"....