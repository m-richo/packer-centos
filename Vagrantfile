
Vagrant.configure("2") do |config|

  config.ssh.max_tries = 40
  config.ssh.timeout   = 120

  config.vm.define :centos do |centos|
    centos.vm.hostname = "centos"
    centos.vm.box = "CentOS-6.4"
  end

end

