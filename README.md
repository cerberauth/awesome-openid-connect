# Awesome OpenID Connect [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome OpenID Connect providers, services, libraries and resources.

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome OpenID Connect](#awesome-openid-connect)
    - [Libraries](#libraries)
- [Resources](#resources)
    - [Books](#books)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
    - [Websites](#websites)
- [Contributing](#contributing)

---

## OpenID Provider Servers and Services

*OpenID Connect Provider as SaaS solution and Open Source solutions.*

* [Active Directory Federation Services ADFS](https://learn.microsoft.com/en-us/windows-server/identity/active-directory-federation-services) - 
* [Auth0](https://auth0.com/docs/authenticate/protocols/openid-connect-protocol) - A software component developed by Microsoft running on Windows Server to provide users with single sign-on access to systems and applications located across organizational boundaries.
* [Authentik](https://goauthentik.io/) - An open-source Identity Provider focused on flexibility and versatility
* [Authlete](https://www.authlete.com/) - OAuth/OIDC Component as a Service
* [Connect2id](https://connect2id.com/products/server) - The identity server that just works and keeps making brilliant sense. Even when you're well past the simple use cases or facing a sudden deluge of visitor traffic.
* [Curity Identity Server](https://curity.io/product/) - Providing secure access to data and services for various types of users across many different channels presents a real challenge.
* [ForgeRock Identity Platform](https://www.forgerock.com/platform/identity-management) - Provides a scalable, highly performant, standards-based OpenID Connect Provider/OAuth2 Authorization Server with the Access Management server.
* [Keycloak](https://www.keycloak.org/) - Keycloak provides user federation, strong authentication, user management, fine-grained authorization, and more.
* [Gravitee.io Access Management](https://www.gravitee.io/platform/access-management) - Gravitee.io Access Management is a flexible, lightweight and blazing-fast open source OpenID Connect/OAuth 2.0 provider aims to be a bridge between applications and identity providers to authenticate, authorize and getting information about user accounts.
* [Okta](https://www.okta.com/) - Okta is a fully extensible solution that enables both customer and workforce identity with federation, single sign-on, API security and workflows for both cloud and on-prem solutions.
* [Ory Hydra](https://github.com/ory/hydra) - OpenID Certified™ OpenID Connect and OAuth Provider written in Go - cloud native, security-first, open source.
* [PingFederate](https://www.pingidentity.com/en/platform/capabilities/authentication-authority/pingfederate.html) - Federation server that provides secure single sign-on, API security and provisioning for enterprise customers, partners, and employees.
* [WSO2 Identity Server](https://wso2.com/identity-server/) - WSO2 Identity Server provides modern identity and access management capabilities that can be easily built into organization’s customer experience (CX) applications.

## Relying Party Libraries

*Libraries for implementing OpenID Connect on a client application.*

### JavaScript

* [openid-client](https://github.com/panva/node-openid-client)
* [oauth4webapi](https://github.com/panva/oauth4webapi)

*Libraries layer focused on specific framework integration*

* [next-auth](https://github.com/nextauthjs/next-auth)
* [nuxt-auth for Nuxt 2](https://github.com/nuxt-community/auth-module)
* [nuxt-auth for Nuxt3](https://github.com/sidebase/nuxt-auth)
* [angular-oauth2-oidc](https://github.com/manfredsteyer/angular-oauth2-oidc)

### PHP

* [thephpleague/oauth2-client](https://github.com/thephpleague/oauth2-client)


### Go

* [github.com/coreos/go-oidc](https://github.com/coreos/go-oidc)
* [github.com/zitadel/oidc](https://github.com/zitadel/oidc)

# Resources

Where to discover learning resources about OpenID Connect.

## Grant Types Specifications

- [authorization_code](https://datatracker.ietf.org/doc/html/rfc6749#section-1.3.1)
- [refresh_token](https://datatracker.ietf.org/doc/html/rfc6749#section-1.5)
- [client_credentials](https://datatracker.ietf.org/doc/html/rfc6749#section-4.4)
- [urn:ietf:params:oauth:grant-type:device_code](https://datatracker.ietf.org/doc/html/rfc8628#section-3.4)
- [urn:ietf:params:oauth:grant-type:jwt-bearer](https://datatracker.ietf.org/doc/html/rfc7523)
- [urn:ietf:params:oauth:grant-type:token-exchange](https://datatracker.ietf.org/doc/html/rfc8693)
- [PKCE Extension](https://datatracker.ietf.org/doc/html/rfc7636)

## Specifications

### Published

- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html)
- [The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749)
- [JSON Web Token (JWT)](https://datatracker.ietf.org/doc/html/rfc7519)
- [The OAuth 2.0 Authorization Framework: Bearer Token Usage](https://datatracker.ietf.org/doc/html/rfc6750)
- [OpenID Connect Discovery 1.0](https://openid.net/specs/openid-connect-discovery-1_0.html)
- [OpenID Connect Back-Channel Logout](https://openid.net/specs/openid-connect-backchannel-1_0.html)
- [OAuth 2.0 Authorization Server Metadata](https://datatracker.ietf.org/doc/html/rfc8414)
- [OAuth 2.0 Token Revocation](https://datatracker.ietf.org/doc/html/rfc7009)
- [OpenID Connect Dynamic Client Registration](https://openid.net/specs/openid-connect-registration-1_0.html)
- [OAuth 2.0 Token Exchange](https://datatracker.ietf.org/doc/html/rfc8693)
- [OAuth 2.0 Token Introspection](https://datatracker.ietf.org/doc/html/rfc7662)

#### Financial-grade API (FAPI)

- [Financial-grade API Security Profile 1.0 - Part 1: Baseline](https://openid.net/specs/openid-financial-api-part-1-1_0.html)
- [Financial-grade API Security Profile 1.0 - Part 2: Advanced](https://openid.net/specs/openid-financial-api-part-2-1_0.html)
- [JWT Secured Authorization Response Mode for OAuth 2.0 (JARM)](https://openid.net/specs/oauth-v2-jarm.html)

### Draft

- [OAuth 2.0 Security Best Current Practice](https://www.ietf.org/archive/id/draft-ietf-oauth-security-topics-22.html)
- [OpenID Connect Federation 1.0](https://openid.net/specs/openid-connect-federation-1_0.html)

#### Financial-grade API (FAPI)

- [Financial-grade API: Client Initiated Backchannel Authentication Profile](https://openid.net/specs/openid-financial-api-ciba.html)

## Books

- [The Little Book of OAuth 2.0 RFCs](https://www.amazon.com/Little-Book-OAuth-2-0-RFCs/dp/B084DFYJS1/) by Aaron Parecki
- [OAuth 2.0 Simplified](https://www.amazon.com/OAuth-2-0-Simplified-Aaron-Parecki/dp/1387751514/) by Aaron Parecki
- [Solving Identity Management in Modern Applications: Demystifying OAuth 2, OpenID Connect, and SAML 2](https://www.amazon.com/Solving-Identity-Management-Modern-Applications-ebook/dp/B0BMQHF83G/) by Yvonne Wilson
- [Keycloak - Identity and Access Management for Modern Applications: Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 protocols to secure applications](https://www.amazon.com/Keycloak-Management-Applications-protocols-applications-ebook/dp/B092KP135B/) by Stian Thorgersen and Pedro Igor Silva

## Websites

- [OpenID](https://openid.net/)
- [OAuth](https://oauth.net/)
- [Alex Bilbie](https://alexbilbie.github.io/tag/oauth/)
- [CerberAuth](https://www.cerberauth.com/)
- [Curity Resources](https://curity.io/resources/openid-connect/)
- [Okta Blog](https://developer.okta.com/blog/tags/oidc/)
- [Medium OAuth2](https://medium.com/oauth-2)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cerberauth/awesome-openidconnect/blob/master/CONTRIBUTING.md) first.
