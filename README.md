# NEW README

AGPL 3

[![CLA assistant](https://cla-assistant.io/readme/badge/2pNza/OpenIdentityServer)](https://cla-assistant.io/2pNza/OpenIdentityServer)

[![AGPL-3.0 License](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)


---
# OLD README 
# Important notice
This is a fork of OpenIdentityServer that is meant to keep existing software that depends on OpenIdentityServer updated with the latest .NET framework version.

For a state of the art implementation, updates and innovations please use [Duende IdentityServer](https://duendesoftware.com/products/identityserver).

## Changes to OpenIdentityServer
Our goal is to keep any core changes to OpenIdentityServer to a minimal so compatibility is maximized. Below you can find some of those changes in order to decide if they could affect your project:

* Api Resource Scopes can be used as Api Scopes: when validating a authorize request, OpenIdentityServer validates scopes based on existing Api Resources and Api Scopes. We have 
updated this code to match requested scopes with Api Resource Scopes as well.

## About OpenIdentityServer
[<img align="right" width="100px" src="https://dotnetfoundation.org/img/logo_big.svg" />](https://dotnetfoundation.org/projects?searchquery=IdentityServer&type=project)

IdentityServer is a free, open source [OpenID Connect](http://openid.net/connect/) and [OAuth 2.0](https://tools.ietf.org/html/rfc6749) framework for ASP.NET Core.
Founded and maintained by [Dominick Baier](https://twitter.com/leastprivilege) and [Brock Allen](https://twitter.com/brocklallen), OpenIdentityServer incorporates all the protocol implementations and extensibility points needed to integrate token-based authentication, single-sign-on and API access control in your applications.
OpenIdentityServer is officially [certified](https://openid.net/certification/) by the [OpenID Foundation](https://openid.net) and thus spec-compliant and interoperable.
It is part of the [.NET Foundation](https://www.dotnetfoundation.org/), and operates under their [code of conduct](https://www.dotnetfoundation.org/code-of-conduct). It is licensed under [Apache 2](https://opensource.org/licenses/Apache-2.0) (an OSI approved license).

For project documentation, please visit [readthedocs](https://openidentityserver.readthedocs.io).

## Branch structure
Active development happens on the main branch. This always contains the latest version. Each (pre-) release is tagged with the corresponding version.

## How to build

* [Install](https://www.microsoft.com/net/download/core#/current) the latest .NET 6 SDK
* Install Git
* Clone this repo
* Run `build.ps1` or `build.sh` in the root of the cloned repo

## Documentation
For project documentation, please visit [readthedocs](https://openidentityserver.readthedocs.io).

## Bug reports and feature requests
Please use the [issue tracker](https://github.com/LacunaSoftware/OpenIdentityServer/issues) for that.

## Help wanted
If you would like to contribute to this project feel free to use the issue tracker and/or submit Pull Requests.

## Acknowledgements
OpenIdentityServer is built using the following great open source projects and free services:

* [ASP.NET Core](https://github.com/dotnet/aspnetcore)
* [Bullseye](https://github.com/adamralph/bullseye)
* [SimpleExec](https://github.com/adamralph/simple-exec)
* [MinVer](https://github.com/adamralph/minver)
* [Json.Net](http://www.newtonsoft.com/json)
* [XUnit](https://xunit.github.io/)
* [Fluent Assertions](http://www.fluentassertions.com/)
* [GitReleaseManager](https://github.com/GitTools/GitReleaseManager)
