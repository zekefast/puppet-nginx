# puppet-nginx

[Puppet](http://docs.puppetlabs.com/puppet/) [module](http://docs.puppetlabs.com/puppet/latest/reference/modules_fundamentals.html)
to manage [NGINX](http://nginx.org/) web server installation and configuration.

# Current State of puppet's NGINX modules (2015-12-23)

[Search](https://forge.puppetlabs.com/modules?utf-8=%E2%9C%93&sort=rank&q=nginx)
on [Puppet Forge](https://forge.puppetlabs.com/) gave 39 results, but only few
of them are really puppet modules for NGINX.

| Module Name                                                                   | Current Module Version | Released   | Supported Puppet Versions | Author(s) and Contributor(s)                                                            | License             | Repository                                                      | State |
|:-----------------------------------------------------------------------------:|:----------------------:|:----------:|:-------------------------:|:---------------------------------------------------------------------------------------:|:-------------------:|:----------------------------------------------------------------|:-----:|
| [jfryman-nginx](https://forge.puppetlabs.com/jfryman/nginx)                   | 0.2.7                  | 2015-06-18 | 3.x                       | [James Fryman](mailto:james@frymanet.com), [Matthew Haughton](mailto:matt@3flex.com.au) | MIT                 | [GitHub](https://github.com/jfryman/puppet-nginx)               |       |
| [example42-nginx](https://forge.puppetlabs.com/example42/nginx)               | 2.3.1                  | 2014-06-14 | Unknown                   | Alessandro Franceschi, Javier Bertoli                                                   | Apache, Version 2.0 | [GitHub](https://github.com/netmanagers/puppet-nginx)           |       |
| [DracoBlue-nginx](https://forge.puppetlabs.com/DracoBlue/nginx)               | 2.0.0                  | 2015-02-02 | 3.0.x                     | [Jan Schütze](mailto:JanS@DracoBlue.de)                                                 | MIT                 | [GitHub](https://github.com/dracoblue/pp-nginx)                 |       |
| [zooz-nginx](https://forge.puppetlabs.com/zooz/nginx)                         | 0.0.3                  | 2013-11-27 | Unknown                   | [Vaidas Jablonskis](mailto:jablonskis@gmail.com)                                        | Unknown             | [GitHub](https://github.com/vaijab/puppet-nginx)                |       |
| [counsyl-nginx](https://forge.puppetlabs.com/counsyl/nginx)                   | 0.5.0                  | 2014-04-11 | Unknown                   | [Justin Bronn](mailto:justin@counsyl.com)                                               | Apache, Version 2.0 | [GitHub](https://github.com/counsyl/puppet-nginx)               |       |
| [garethr-nginx](https://forge.puppetlabs.com/garethr/nginx)                   | 0.0.1                  | 2014-01-25 | Unknown                   | [Gareth Rushgrove](https://github.com/garethr/garethr-nginx)                            | Apache, Version 2.0 | [GitHub](https://github.com/garethr/garethr-nginx)              |       |
| [spantree-nginx](https://forge.puppetlabs.com/spantree/nginx)                 | 0.0.7                  | 2015-03-16 | Unknown                   | Spantree Technology Group, LLC                                                          | Apache, Version 2.0 | [GitHub](https://github.com/Spantree/puppet-nginx)              |       |
| [jbussdieker-nginx](https://forge.puppetlabs.com/jbussdieker/nginx)           | 0.0.3                  | 2013-07-16 | 2.7.x                     | Joshua Bussdieker                                                                       | Apache, Version 2.0 | [GitHub](https://github.com/jbussdieker/puppet-nginx)           |       |
| [thias-nginx](https://github.com/thias/puppet-nginx)                          | 1.0.7                  | 2015-12-01 | 2.7.20 >= puppet < 4.0.0  | Matthias Saou                                                                           | Apache, Version 2.0 | [GitHub](https://github.com/thias/puppet-nginx)                 |       |
| [ploperations-nginx](https://github.com/puppetlabs-operations/puppet-nginx)   | 1.0.0                  | 2013-02-01 | Unknown                   | Puppet Labs Operations                                                                  | Apache, Version 2.0 | [GitHub](https://github.com/puppetlabs-operations/puppet-nginx) |       |
| [maestrodev-nginx](https://forge.puppetlabs.com/maestrodev/nginx)             | 1.0.0                  | 2013-08-01 | Unknown                   | MaestroDev                                                                              | Apache, Version 2.0 | [GitHub](https://github.com/maestrodev/puppet-nginx)            |       |
| [oris-nginx](https://forge.puppetlabs.com/oris/nginx)                         | 1.3.0                  | 2015-06-25 | Unknown                   | UW Office of Research Information Services (ORIS)                                       | Apache, Version 2.0 |                                                                 |       |
| [arioch-nginx](https://forge.puppetlabs.com/arioch/nginx)                     |                        |                                        |                                                                                         |                     |                                                                 |       |
| [ryayon-nginx](https://forge.puppetlabs.com/ryayon/nginx)                     |                        |                                        |                                                                                         |                     |                                                                 |       |
| [dhutty-nginx](https://forge.puppetlabs.com/dhutty/nginx)                     |                        |                                        |                                                                                         |                     |                                                                 |       |
| [ctrlcroot-nginx](https://forge.puppetlabs.com/ctrlcroot/nginx)               |                        |                                        |                                                                                         |                     |                                                                 |       |
| [a2labs-nginx](https://forge.puppetlabs.com/a2labs/nginx)                     |                        |                                        |                                                                                         |                     |                                                                 |       |
| [guilhermef-nginx](https://forge.puppetlabs.com/guilhermef/nginx)             |                        |                                        |                                                                                         |                     |                                                                 |       |
| [Enucatl-nginx](https://forge.puppetlabs.com/Enucatl/nginx)                   |                        |                                        |                                                                                         |                     |                                                                 |       |
| [igovua-nginx](https://forge.puppetlabs.com/igovua/nginx)                     |                        |                                        |                                                                                         |                     |                                                                 |       |
| [puppetlabs-nginx](https://forge.puppetlabs.com/puppetlabs/nginx)             |                        |                                        |                                                                                         |                     |                                                                 |       |
| [kbatra-nginx_passenger](https://forge.puppetlabs.com/kbatra/nginx_passenger) |                        |                                        |                                                                                         |                     |                                                                 |       |
| [jmouette-nginx](https://forge.puppetlabs.com/jmouette/nginx)                 |                        |                                        |                                                                                         |                     |                                                                 |       |
| [jvaubourg-nginxpack](https://forge.puppetlabs.com/jvaubourg/nginxpack)       |                        |                                        |                                                                                         |                     |                                                                 |       |

# A reason to write yet another puppet's module for NGINX.

I really like module [puppetlabs-postgresql](https://forge.puppetlabs.com/puppetlabs/postgresql).
As it serve a wide range of tasks related to [PostgreSQL](http://www.postgresql.org/)
provisioning for web applications on [Ruby](https://www.ruby-lang.org/en/).
I would like to have same good Puppet's module for another important component
of web applications - web server.

# Supported Operation Systems

* [Debian GNU/Linux](https://www.debian.org/) (jessie/8.x)

# Requirements

*

# Module Documentation

TBD

# Automated Tests

TBD

# License

See more details in [LICENSE](LICENSE) file.

# Contributors

See more details in [CONTRIBUTORS.md](CONTRIBUTORS.md) file.
