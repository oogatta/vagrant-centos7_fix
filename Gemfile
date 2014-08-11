source 'https://rubygems.org'
source 'http://gems.hashicorp.com'

gem 'awesome_print'

ENV['VAGRANT_INSTALLER_EMBEDDED_DIR'] = '/Applications/Vagrant/embedded'
#p Gem::Specification.find_by_name('vagrant-vmware-fusion').gem_dir

group :plugins do
 # gemspec
 gemspec
 gem 'vagrant-centos7_fix', path: '.'
 gem 'vagrant-vmware-fusion'
end

group :development do
  gem 'vagrant', git: 'https://github.com/mitchellh/vagrant.git', tag: 'v1.6.3'
end

