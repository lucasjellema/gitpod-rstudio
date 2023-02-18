# gitpod-rstudio
Gitpod environment for working with RStudio Server

https://www.how2shout.com/linux/install-rstudio-server-open-source-on-ubuntu-20-04-lts/

Download and install R

sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/"
sudo apt update
sudo apt-get install gdebi-core
wget https://download2.rstudio.org/server/bionic/amd64/rstudio-server-2021.09.1-372-amd64.deb
ls

sudo dpkg -i rstudio-server-2021.09.1-372-amd64.deb


