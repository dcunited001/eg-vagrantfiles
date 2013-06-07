# -*- mode: ruby -*-
# vi: set ft=ruby :

# this works with `ruby Vagrantfile`
#   but not `vagrant up`

require 'yaml'
require 'ostruct'
require 'erubis'

@cfg = YAML::load(DATA)
@boxes = @cfg.keys.map(&:to_sym)

Vagrant.configure("2") do |config|
  raise @cfg.inspect
end

