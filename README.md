# Installing scidavis on newer Linux Mint/Ubuntu

Check the version number of your system with:

    cat /etc/lsb-release
and run the commands for your system version number:

 # Ubuntu 18.04 / mint 19 / mint 19.1 / mint 19.2 / mint 19.3
  
    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_18.04/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_18.04/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis

# Ubuntu 20.04 / mint 20 / mint 20.01
  
    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_20.04/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_20.04/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis

# Ubuntu 20.10

    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_20.10/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_20.10/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis
   
# Ubuntu 19.10
  
    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_19.10/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_19.10/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis
  
# Ubuntu 19.04 
  
    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_19.04/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_19.04/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis
  
 # Ubuntu 18.10 
 
    echo 'deb http://download.opensuse.org/repositories/home:/hpcoder1/xUbuntu_18.10/ /' | sudo tee /etc/apt/sources.list.d/home:hpcoder1.list
    curl -fsSL https://download.opensuse.org/repositories/home:hpcoder1/xUbuntu_18.10/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home_hpcoder1.gpg > /dev/null
    sudo apt update
    sudo apt install scidavis
  
  
  
