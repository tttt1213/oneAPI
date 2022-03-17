sudo yum update
sudo yum -y install cmake pkgconfig
sudo yum groupinstall "Development Tools"

# oneAPI base

wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18487/l_BaseKit_p_2022.1.2.146.sh
sudo sh ./l_BaseKit_p_2022.1.2.146.sh


# oneAPI HPC

wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18479/l_HPCKit_p_2022.1.2.117.sh
sudo sh ./l_HPCKit_p_2022.1.2.117.sh
