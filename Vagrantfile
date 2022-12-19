# vim:set ft=ruby:

Vagrant.configure(2) do |config|
    config.vm.define :ubuntu22 do |u|
        u.vm.box = 'ubuntu/jammy64'
        u.vm.provider :virtualbox do |v|
          v.memory = 2048
          v.cpus = 1
        end
    end
end
