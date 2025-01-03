# Install
 go to https://136-244-62-207.dyn.tachusfiber.net/ and change the IP to your ip and bookmark it.
 install docker by  doing for (pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done) to uninstall all unessary packages. set it up (# Add Docker's official GPG key:
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update). and run it by (sudo docker run hello-world)
install qemu and download the latest windows 11 ISO for free from my blog or this link https://techdroid123456.blogspot.com/2024/12/winleven-11-iso-download-free.html
 once u have done that, go into BIOS and enable hardware vm's then go to ur ip address link and add tampermonkey. once you have added tampermonkey type this script in (add localhost? {{IP address}} {computer name} pkg install local {BROWSER NAME} {IP address} WSFU} 
