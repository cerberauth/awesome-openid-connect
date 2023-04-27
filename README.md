# Awesome OpenID Connect [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome OpenID Connect providers, services, libraries and resources.

## Contents

- [OpenID Provider Servers and Services](#openid-provider-servers-and-services)
- [Relying Party Libraries](#relying-party-libraries)
- [Resources](#resources)
    - [Grant Types Specifications](#grant-types-specifications)
    - [Specifications](#specifications)
    - [Books](#books)
    - [Websites](#websites)

---

## OpenID Provider Servers and Services

*OpenID Connect Provider as SaaS solution and Open Source solutions.*

- [Active Directory Federation Services ADFS](https://learn.microsoft.com/en-us/windows-server/identity/active-directory-federation-services) - A software component developed by Microsoft running on Windows Server to provide users with single sign-on access to systems and applications located across organizational boundaries.
- [Auth0](https://auth0.com/docs/authenticate/protocols/openid-connect-protocol) - An OpenID Connect and OAuth2 service that is available on the cloud or can be installed on premise.
- [Authelia](https://www.authelia.com/) - An open-source authentication and authorization server and portal fulfilling the identity and access management (IAM) role of information security in providing single sign-on (SSO).
- [Authentik](https://goauthentik.io/) - An open-source Identity Provider focused on flexibility and versatility.
- [Authlete](https://www.authlete.com/) - A set of APIs for developers to implement OAuth authorization servers and OpenID Connect identity providers in a secure and simple manner.
- [Connect2id](https://connect2id.com/products/server) - OpenID Connect SSO and IdP server for the enterprise. Engineered for 100% uptime, confident scaling and distributed operation.
- [Curity Identity Server](https://curity.io/product/) - An API Security solution that brings identity and API access management together.
- [Duo](https://duo.com/) - Provides users with an easy and consistent login experience for every application, cloud or on-premises.
- [ForgeRock Identity Platform](https://www.forgerock.com/platform/identity-management) - Provides a scalable, highly performant, standards-based OpenID Connect Provider/OAuth2 Authorization Server with the Access Management server.
- [Keycloak](https://www.keycloak.org/) - An open source project which provides user federation, strong authentication, user management, fine-grained authorization, and more.
- [Gravitee.io Access Management](https://www.gravitee.io/platform/access-management) - A flexible, lightweight and fast open source OpenID Connect/OAuth 2.0 provider aims to be a bridge between applications and identity providers to authenticate, authorize and getting information about user accounts.
- [Okta](https://www.okta.com/) - A fully extensible solution that enables both customer and workforce identity with federation, single sign-on, API security and workflows for both cloud and on-prem solutions.
- [Ory Hydra](https://github.com/ory/hydra) - Open Source OpenID Certified™ OpenID Connect and OAuth Provider.
- [PingFederate](https://www.pingidentity.com/en/platform/capabilities/authentication-authority/pingfederate.html) - Federation server that provides secure single sign-on, API security and provisioning for enterprise customers, partners, and employees.
- [WSO2 Identity Server](https://wso2.com/identity-server/) - Identity Server which provides modern identity and access management capabilities that can be easily built into organization's customer experience (CX) applications.

## Relying Party Libraries

*Libraries for implementing OpenID Connect on a client application.*

### JavaScript

- [openid-client](https://github.com/panva/node-openid-client) - OpenID Certified™ Relying Party (OpenID Connect/OAuth 2.0 Client) implementation for Node.js.
- [oauth4webapi](https://github.com/panva/oauth4webapi) - OAuth 2 / OpenID Connect for JavaScript Runtimes.

*Libraries layer focused on specific framework integration*

- [NextAuth.js](https://github.com/nextauthjs/next-auth) - A complete open source authentication solution for Next.js applications including using OpenId Connect.
- [nuxt-auth for Nuxt 2](https://github.com/nuxt-community/auth-module) - A Zero-boilerplate authentication support for Nuxt.js 2.
- [nuxt-auth for Nuxt3](https://github.com/sidebase/nuxt-auth) - A Nuxt 3 user authentication and sessions. nuxt-auth wraps NextAuth.js.
- [angular-oauth2-oidc](https://github.com/manfredsteyer/angular-oauth2-oidc) - A library which bring support for OAuth 2 and OpenId Connect (OIDC) in Angular.

### PHP

- [thephpleague/oauth2-client](https://github.com/thephpleague/oauth2-client) - Easy integration with OAuth 2.0 service providers for PHP.

### Go

- [coreos/go-oidc](https://github.com/coreos/go-oidc) - A simple Go OpenID Connect client.
- [zitadel/oidc](https://github.com/zitadel/oidc) - Easy to use OpenID Connect client and server library certified by the OpenID Foundation.

## Resources

Where to discover learning resources about OpenID Connect.

### Grant Types Specifications

- [authorization_code](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=authorization_code#section-1.3.1)
- [refresh_token](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=refresh_token#section-1.5)
- [client_credentials](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=client_credentials#section-4.4)
- [urn:ietf:params:oauth:grant-type:device_code](https://datatracker.ietf.org/doc/html/rfc8628#section-3.4)
- [urn:ietf:params:oauth:grant-type:jwt-bearer](https://datatracker.ietf.org/doc/html/rfc7523)
- [urn:ietf:params:oauth:grant-type:token-exchange](https://datatracker.ietf.org/doc/html/rfc8693)
- [PKCE Extension](https://datatracker.ietf.org/doc/html/rfc7636)

### Specifications

#### Published

- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html) - This specification defines the core OpenID Connect functionality: authentication built on top of OAuth 2.0 and the use of Claims to communicate information about the End-User. It also describes the security and privacy considerations for using OpenID Connect.
- [The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749)
- [JSON Web Token (JWT)](https://datatracker.ietf.org/doc/html/rfc7519)
- [The OAuth 2.0 Authorization Framework: Bearer Token Usage](https://datatracker.ietf.org/doc/html/rfc6750)
- [OpenID Connect Discovery 1.0](https://openid.net/specs/openid-connect-discovery-1_0.html)
- [OpenID Connect Back-Channel Logout](https://openid.net/specs/openid-connect-backchannel-1_0.html)
- [OAuth 2.0 Authorization Server Metadata](https://datatracker.ietf.org/doc/html/rfc8414)
- [OAuth 2.0 Token Revocation](https://datatracker.ietf.org/doc/html/rfc7009)
- [OpenID Connect Dynamic Client Registration](https://openid.net/specs/openid-connect-registration-1_0.html)
- [OAuth 2.0 Token Introspection](https://datatracker.ietf.org/doc/html/rfc7662)
- [Financial-grade API Security Profile 1.0 - Part 1: Baseline](https://openid.net/specs/openid-financial-api-part-1-1_0.html)
- [Financial-grade API Security Profile 1.0 - Part 2: Advanced](https://openid.net/specs/openid-financial-api-part-2-1_0.html)
- [JWT Secured Authorization Response Mode for OAuth 2.0 (JARM)](https://openid.net/specs/oauth-v2-jarm.html)

#### Draft

- [OAuth 2.0 Security Best Current Practice](https://www.ietf.org/archive/id/draft-ietf-oauth-security-topics-22.html)
- [OpenID Connect Federation 1.0](https://openid.net/specs/openid-connect-federation-1_0.html)
- [Financial-grade API: Client Initiated Backchannel Authentication Profile](https://openid.net/specs/openid-financial-api-ciba.html)

### Books

- [The Little Book of OAuth 2.0 RFCs by Aaron Parecki](https://www.amazon.com/Little-Book-OAuth-2-0-RFCs/dp/B084DFYJS1/)
- [OAuth 2.0 Simplified by Aaron Parecki](https://www.amazon.com/OAuth-2-0-Simplified-Aaron-Parecki/dp/1387751514/)
- [Solving Identity Management in Modern Applications: Demystifying OAuth 2, OpenID Connect, and SAML 2 by Yvonne Wilson](https://www.amazon.com/Solving-Identity-Management-Modern-Applications-ebook/dp/B0BMQHF83G/)
- [Keycloak - Identity and Access Management for Modern Applications: Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 protocols to secure applications by Stian Thorgersen and Pedro Igor Silva](https://www.amazon.com/Keycloak-Management-Applications-protocols-applications-ebook/dp/B092KP135B/)

### Websites

- [OpenID](https://openid.net/) - OpenId Connect official website.
- [OAuth](https://oauth.net/) - OAuth website maintained by Aaron Parecki which list different resources about the protocol.
- [Alex Bilbie](https://alexbilbie.github.io/tag/oauth/) - Alex Bilbie Blog posts about OAuth topic.
- [CerberAuth](https://www.cerberauth.com/) - A blog talking about OpenId Connect and OAuth2.
- [Curity Resources](https://curity.io/resources/openid-connect/) - Curity solution resources articles about OpenId Connect.
- [Okta Blog](https://developer.okta.com/blog/tags/oidc/) - Okta Blog posts about OAuth2 and OpenId Connect.
- [Medium OAuth2](https://medium.com/oauth-2) - Medium blog talking about OAuth2.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cerberauth/awesome-openidconnect/blob/master/CONTRIBUTING.md) first.
