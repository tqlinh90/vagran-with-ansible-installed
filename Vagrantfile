Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"
  #
  # Run Ansible from the Vagrant Host
  #
  config.vm.synced_folder "./script", "/mnt"

  config.vm.provision "shell" do |s|
    s.path = "script/script.sh"
  end
end



