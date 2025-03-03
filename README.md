
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/server-auth&target_branch=18.0)
[![Pre-commit Status](https://github.com/OCA/server-auth/actions/workflows/pre-commit.yml/badge.svg?branch=18.0)](https://github.com/OCA/server-auth/actions/workflows/pre-commit.yml?query=branch%3A18.0)
[![Build Status](https://github.com/OCA/server-auth/actions/workflows/test.yml/badge.svg?branch=18.0)](https://github.com/OCA/server-auth/actions/workflows/test.yml?query=branch%3A18.0)
[![codecov](https://codecov.io/gh/OCA/server-auth/branch/18.0/graph/badge.svg)](https://codecov.io/gh/OCA/server-auth)
[![Translation Status](https://translation.odoo-community.org/widgets/server-auth-18-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/server-auth-18-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# server-auth

server-auth

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[auth_admin_passkey](auth_admin_passkey/) | 18.0.1.0.0 |  | Allows system administrator to authenticate with any account
[auth_api_key](auth_api_key/) | 18.0.1.0.0 |  | Authenticate http requests from an API key
[auth_api_key_group](auth_api_key_group/) | 18.0.1.0.0 | [![simahawk](https://github.com/simahawk.png?size=30px)](https://github.com/simahawk) | Allow grouping API keys together. Grouping per se does nothing. This feature is supposed to be used by other modules to limit access to services or records based on groups of keys.
[auth_api_key_server_env](auth_api_key_server_env/) | 18.0.1.0.0 |  | Configure api keys via server env. This can be very useful to avoid mixing your keys between your various environments when restoring databases. All you have to do is to add a new section to your configuration file according to the following convention:
[auth_oidc](auth_oidc/) | 18.0.1.0.0 | [![sbidoul](https://github.com/sbidoul.png?size=30px)](https://github.com/sbidoul) | Allow users to login through OpenID Connect Provider
[auth_oidc_environment](auth_oidc_environment/) | 18.0.1.0.0 |  | This module allows to use server env for OIDC configuration
[auth_saml](auth_saml/) | 18.0.1.0.0 | [![vincent-hatakeyama](https://github.com/vincent-hatakeyama.png?size=30px)](https://github.com/vincent-hatakeyama) | SAML2 Authentication
[auth_session_timeout](auth_session_timeout/) | 18.0.1.0.0 |  | This module disable all inactive sessions since a given delay
[base_user_empty_password](base_user_empty_password/) | 18.0.1.0.0 | [![grindtildeath](https://github.com/grindtildeath.png?size=30px)](https://github.com/grindtildeath) | Allows to empty password of users
[base_user_show_email](base_user_show_email/) | 18.0.1.0.0 |  | Untangle user login and email

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
