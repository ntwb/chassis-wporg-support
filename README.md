# WordPress Support Forums Extension Beta
Adds WordPress Support Forums support to Chassis

This is based on [meta-environment](https://github.com/WordPress/meta-environment) by the WordPress [#meta team](https://make.wordpress.org/meta/handbook/) and community.

## Installing & Documentation

1. Clone `chassis` by `git clone --recursive git@github.com:Chassis/Chassis.git wporg-support`.
2. Change to the `wporg-support` folder by `cd wporg-support`
3. Clone `chassis-wporg-support` by `git clone git@github.com:ntwb/chassis-wporg-support.git content`.
4. `vagrant up`
5. Clone `chassis-wporg-support-extension` by `git clone git@github.com:ntwb/chassis-wporg-support-extension.git extensions/wporg-support`
6. `vagrant provision` - Depending on your internet connection, this could take a while

Done!

### Adding additional extensions
It's recommended that you install the following Chassis extensions

[PHPCS & WPCS](https://github.com/Chassis/phpcs)

[Memcache](https://github.com/Chassis/memcache)

[Debugging](https://github.com/Chassis/Debugging)

Once all extensions are added you can now `vagrant provision`
