# Reference
https://docs.cumulusnetworks.com/display/VX/Vagrant+and+VirtualBox

# Download vagrantbox
It's not must???
https://cumulusnetworks.com/products/cumulus-vx/

```

mkdir cumulusvx
cd /Users/taiji/work/vagrant/cumulusvx
mv ~/Downloads/cumulus-linux-3.5.0-vx-amd64.box .
```

or

```
cd /Users/taiji/work/vagrant/cumulusvx
vagrant box add cumuluscommunity/cumulus-vx
```

# Making Vagrant box

```
vagrant init
```

```
vi Vagrantfile

Vagrant.configure(2) do |config|
  config.vm.box = "CumulusCommunity/cumulus-vx"
end
```

```
vagrant up
```

```
vagrant ssh
```
