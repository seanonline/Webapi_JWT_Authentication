**JWT Authentication for Asp.Net Web Api 

**Updated to  .Net Framework 4.7.2 & Visual Studio 2019


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


## Testing

- I have used [Restlet Client](https://chrome.google.com/webstore/detail/restlet-client-rest-api-t/aejoelaoggembcahagimdiliamlcdmfm?hl=en)

![Get JWT](https://raw.githubusercontent.com/seanonline/Webapi_JWT_Authentication/master/media/getjwt.png "get JWT")

---

![USE JWT](https://raw.githubusercontent.com/seanonline/Webapi_JWT_Authentication/master/media/jwtaccessecuredEndpoint.png "access resource")




## Dependencies
- Updated to use Latest version of  [System.IdentityModel.Tokens.Jwt Version 6.8.0  ](https://www.nuget.org/packages/System.IdentityModel.Tokens.Jwt/)



## How to Use It ?
- Clone or download the repository
- You can find more details at my blog [SECURING WEBAPI USING JSON WEB TOKEN(JWT) IN C#](https://decatechlabs.com/secure-webapi-using-jwt)
