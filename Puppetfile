forge "http://forge.puppetlabs.com"

mod "puppet-hiera"
mod "puppet-r10k"
mod "puppetlabs-concat"
mod "puppetlabs-stdlib"
mod "puppetlabs-ruby"
mod "puppetlabs-gcc"
mod "puppetlabs-inifile"
mod "puppetlabs-vcsrepo"
mod "puppetlabs-postgresql"
mod "puppetlabs-git"
mod "gentoo-portage"

# Add Roles/Profiles and CIS Hardening

mod 'roles',
  :git => 'https://github.com/cvquesty/ossec_roles.git',
  :ref => 'development'

mod 'profiles',
  :git => 'https://github.com/cvquesty/ossec_profiles.git',
  :ref => 'development'

mod 'cis_hardening',
  :git => 'https://github.com/cvquesty/cis_hardening.git',
  :ref => 'development'
