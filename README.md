# Phylip
Installation requirements for phylip

download the rpm fusion repository with "wget https://github.com/DaanDesloovere/Phylip/raw/main/rpmfusion.rpm" and install with "sudo dnf install rpmfusion.rpm"

download the rpm sphere package with "wget https://github.com/DaanDesloovere/Phylip/raw/main/rpmsphere.rpm" and install with "rpm -Uvh rpmsphere.rpm"

execute "sudo dnf install phylip"

add the "/usr/libexec/phylip" directory to the PATH variable inside the .bashrc file so the commands can be used from anywhere in the system.

phylip is now installed, you can check with "which proml". If this gives you a location everything is installed correctly.

you can also download the divergent_globins.fasta file and experiment with it.
