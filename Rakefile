# -*- ruby -*-

require 'rubygems'
require 'hoe'
$:.unshift(File.dirname(__FILE__) + "/lib")
require 'lvm'

Hoe.new('ruby-lvm', LVMWrapper::VERSION) do |p|
  p.developer('Matthew Kent', 'matt@bravenet.com')
  p.extra_deps << ['open4', '>= 0.9.6']
  p.extra_deps << ['ruby-lvm-attrib', '>= 0.0.1']
  p.remote_rdoc_dir = ''
end

# vim: syntax=Ruby
