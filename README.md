# build_oneAPI

wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18487/l_BaseKit_p_2022.1.2.146.sh

sudo sh ./l_BaseKit_p_2022.1.2.146.sh

sudo yum update
sudo yum -y install cmake pkgconfig
sudo yum groupinstall "Development Tools"
