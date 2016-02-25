# Basic vars
gitlab_base_url = 'ssh://git@gitlab.domain.de:2424'

# Helper functions
def add_mod(modname, repo, ref='master', base_git_url='https://github.com')
  mod modname, :git => "#{base_git_url}/#{repo}", :ref => ref
end

# Component modules
add_mod('alternatives', 'puppet-community/puppet-alternatives', '0.3.0')
add_mod('apache', 'puppetlabs/puppetlabs-apache', '1.6.0')
add_mod('archive', 'puppet-community/puppet-archive')
add_mod('concat', 'puppetlabs/puppetlabs-concat', '1.2.4')
add_mod('concat_native', 'theforeman/puppet-concat_native')
add_mod('file_concat', 'electrical/puppet-lib-file_concat')
add_mod('limits', 'puppetlabs/puppetlabs-limits')
add_mod('ntp', 'puppetlabs/puppetlabs-ntp', '3.3.0')
add_mod('openssl', 'camptocamp/puppet-openssl', '1.2.4')
add_mod('puppet', 'theforeman/puppet-puppet', '3.0.0')
add_mod('resolv_conf', 'saz/puppet-resolv_conf', 'v3.0.0')
add_mod('stdlib', 'puppetlabs/puppetlabs-stdlib', '4.8.0')
add_mod('sudo', 'saz/puppet-sudo', 'e5fe01b9df91d380f1785f4be2818913bfdaba25')
add_mod('sysctl', 'thias/puppet-sysctl')
add_mod('tftp', 'theforeman/puppet-tftp', '1.5.1')
add_mod('xinetd', 'puppetlabs/puppetlabs-xinetd')
