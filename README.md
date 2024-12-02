# ![Juice Shop Logo](https://raw.githubusercontent.com/juice-shop/juice-shop/master/frontend/src/assets/public/images/JuiceShop_Logo_100px.png) Website Security Research Project: OWASP Juice Shop Updated

## Table of contents

- [Setup](#setup)
- [Demo](#demo)
- [Documentation](#documentation)
- [Licensing](#licensing)

## Setup

1. Verify you have an authentication key in your github ssh keys [link](https://github.com/settings/keys).
    If not, follow github directions on setting up ssh key [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
2. Install [node.js](#nodejs-version-compatibility)
3. Clone via SSH by Run `git clone git@github.com:Fall-2024-Security-Project/juice-shop-updated.git`
4. Go into the cloned folder with `cd juice-shop-updated`
5. Run `npm install` (only has to be done before first start or when you change the source code)
6. Run `npm start`
7. Browse to <http://localhost:3000>

## Demo

Follow our exploit instructions to compare the [hardened instance of Juice Shop](https://fall-2024-security-project.fly.dev)
to the [unhardened instance]().


## Mitigated Exploits and How-tos
How-to | OWASP Vulnerability | Author
--- | --- | ---
[Change Legal Doc](how-to/vulnerable-outdated-components.md) | Vulnerable and Outdated Components | Amy
[Get Express Version](how-to/security-misconfiguration-error-handling.md) | Security Misconfiguration | Amy
[Forge Admin Account](how-to/admin-registration.md) | Injection/Server Side Forgery | Braeden
[Admin Control Panel](how-to/admin-route.md) | Broken Access Control | Braeden
[SQL Injection Login](how-to/sql-injection-login.md) | Injection | Elizabeth
[SQL Injection Search API](how-to/sql-injection-search-api.md) | Injection | Elizabeth
[Password Validation](frontend/src/app/register/custom-password-validator.ts) | Insecure Design | Marcus



## Licensing

[![license](https://img.shields.io/github/license/bkimminich/juice-shop.svg)](LICENSE)

This program is free software: you can redistribute it and/or modify it under the terms of the [MIT license](LICENSE).
OWASP Juice Shop and any contributions are Copyright © by Bjoern Kimminich & the OWASP Juice Shop contributors
2014-2024.

![Juice Shop Logo](https://raw.githubusercontent.com/bkimminich/juice-shop/master/frontend/src/assets/public/images/JuiceShop_Logo_400px.png)
