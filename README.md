JWT Authentication for Asp.Net Web Api
============
---

![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
[![GitHub Issues](https://img.shields.io/github/issues/anfederico/Clairvoyant.svg)](https://github.com/anfederico/Clairvoyant/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


This is a webapi project written in visual studio and we will secure endpoint using [JWT](jwt.io).

Basically, a JWT token look like:

    <base64-encoded header>.<base64-encoded claims>.<base64-encoded signature>

JWT token has three sections:

1. Header: JSON format which is encoded as a base64
2. Claims: JSON format which is encoded as a base64.
3. Signature: Created and signed based on Header and Claims which is encoded as a base64.

## Dependencies
- Updated to use Latest version of  [System.IdentityModel.Tokens.Jwt  version=5.1.4 ](https://www.nuget.org/packages/System.IdentityModel.Tokens.Jwt/5.2.0-preview1-408290725)

---

## How to Use It ?
- Clone or download the repository
- You can find more details at my blog [SECURING WEBAPI USING JSON WEB TOKEN(JWT) IN C#](http://www.decatechlabs.com/how-to-secure-webapi-using-json-web-tokenjwt)
