# SSO

[![Build Status](https://travis-ci.org/laincloud/sso.svg?branch=master)](https://travis-ci.org/laincloud/sso)
[![codecov](https://codecov.io/gh/laincloud/sso/branch/master/graph/badge.svg)](https://codecov.io/gh/laincloud/sso)
[![MIT license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)

The Single Sign On system for LAIN. 

## License
SSO is released under the [MIT license](https://github.com/laincloud/sso/blob/master/LICENSE).

### Upgrade from 0.2.0 or older version
```
ALTER TABLE `group` MODIFY name VARCHAR(128) NOT NULL;
ALTER TABLE app ADD admin_role_id INT NULL DEFAULT -1
```
