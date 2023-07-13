# Awesome OpenID Connect [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome providers, services, libraries and resources for OpenID Connect, the identity layer on top of OAuth 2.0 application authorization protocol.

## Contents

- [OpenID Provider Servers and Services](#openid-provider-servers-and-services)
- [Relying Party Libraries](#relying-party-libraries)
- [Resources](#resources)
    - [Flows / Grant Types Specifications](#flows--grant-types-specifications)
    - [Specifications](#specifications)
    - [Books](#books)
    - [Websites](#websites)

---

## OpenID Provider Servers and Services

*OpenID Connect Provider as SaaS solution and Open Source solutions.*

- [Active Directory Federation Services ADFS](https://learn.microsoft.com/en-us/windows-server/identity/active-directory-federation-services) - Software component developed by Microsoft running on Windows Server to provide users with single sign-on access to systems and applications located across organizational boundaries.
- [Auth0](https://auth0.com/docs/authenticate/protocols/openid-connect-protocol) - OpenID Connect and OAuth2 service that is available on the cloud or can be installed on premise.
- [Authelia](https://www.authelia.com/) - Open Source authentication, authorization server and portal fulfilling the identity and access management (IAM) role of information security in providing single sign-on (SSO).
- [Authentik](https://goauthentik.io/) - Open Source Identity Provider focused on flexibility and versatility.
- [Authlete](https://www.authlete.com/) - Set of APIs for developers to implement OAuth authorization servers and OpenID Connect identity providers.
- [AWS Cognito](https://aws.amazon.com/cognito/) - Cognito by Amazon Web Services has OpenID Connect provider in addition to IAM capabilities.
- [Connect2id](https://connect2id.com/products/server) - OpenID Connect SSO and IdP server for enterprise.
- [Curity Identity Server](https://curity.io/product/) - API Security solution that brings identity and API access management together.
- [Duo](https://duo.com/) - OpenID Connect Provider and IdP solution developed by Cisco.
- [ForgeRock Identity Platform](https://www.forgerock.com/platform/identity-management) - Standards-based OpenID Connect Provider/OAuth2 Authorization Server with an Access Management server.
- [Keycloak](https://www.keycloak.org/) - Open Source project powered by RedHat which provides user federation, strong authentication, user management, fine-grained authorization, and more.
- [Gluu](https://gluu.org/openid/) - OpenID Connect Provider and FAPI certified solution and integrated with IAM.
- [Gravitee.io](https://www.gravitee.io/platform/access-management) - Open Source OpenID Connect/OAuth 2.0 provider aims to be a bridge between applications and identity providers to authenticate, authorize and getting information about user accounts.
- [Okta](https://www.okta.com/) - Extensible solution that enables both customer and workforce identity with federation, single sign-on, API security and workflows for both cloud and on-prem solutions.
- [Ory Hydra](https://github.com/ory/hydra) - Open Source OpenID Certified™ OpenID Connect and OAuth Provider.
- [MITREid Connect](https://github.com/mitreid-connect/OpenID-Connect-Java-Spring-Server) - Open Source OpenID Connect reference implementation in Java.
- [PingFederate](https://www.pingidentity.com/en/platform/capabilities/authentication-authority/pingfederate.html) - Federation server that provides secure single sign-on, API security and provisioning for enterprise customers, partners, and employees.
- [WSO2 Identity Server](https://wso2.com/identity-server/) - Identity Server which provides modern identity and access management capabilities that can be easily built into organization's customer experience (CX) applications.

## Relying Party Libraries

*Libraries for implementing OpenID Connect on a client application.*

### JavaScript

- [openid-client](https://github.com/panva/node-openid-client) - OpenID Certified™ Relying Party (OpenID Connect/OAuth 2.0 Client) implementation for Node.js.
- [oauth4webapi](https://github.com/panva/oauth4webapi) - OAuth 2/OpenID Connect library for JavaScript Runtimes.

*Libraries layer focused on specific framework integration*

- [NextAuth.js](https://github.com/nextauthjs/next-auth) - Open Source authentication solution for Next.js applications including using OpenID Connect.
- [nuxt-auth for Nuxt 2](https://github.com/nuxt-community/auth-module) - Zero-boilerplate authentication support for Nuxt.js 2.
- [nuxt-auth for Nuxt3](https://github.com/sidebase/nuxt-auth) - Nuxt 3 user authentication and sessions library. nuxt-auth wraps NextAuth.js.
- [angular-oauth2-oidc](https://github.com/manfredsteyer/angular-oauth2-oidc) - Library which bring support for OAuth 2.0 and OpenID Connect (OIDC) in Angular.

### PHP

- [thephpleague/oauth2-client](https://github.com/thephpleague/oauth2-client) - Integration with OAuth 2.0 service providers for PHP.

### Go

- [coreos/go-oidc](https://github.com/coreos/go-oidc) - Go OpenID Connect client.
- [zitadel/oidc](https://github.com/zitadel/oidc) - OpenID Connect client and server library certified by the OpenID Foundation.

## Resources

Where to discover learning resources about OpenID Connect.

### Flows / Grant Types Specifications

- [authorization_code](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=authorization_code#section-1.3.1) - OAuth 2.0 Authorization Code Grant Type which fit well public client authorization like web apps.
- [refresh_token](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=refresh_token#section-1.5) - OAuth 2.0 Refresh Token Grant Type used to exchange a refresh token against a short life access token and sometime a new refresh token as well.
- [client_credentials](https://datatracker.ietf.org/doc/html/rfc6749?grant_type=client_credentials#section-4.4) - OAuth 2.0 Client Credentials Grant providing a way to get token without user interaction which fit well machine to machine communications.
- [urn:ietf:params:oauth:grant-type:device_code](https://datatracker.ietf.org/doc/html/rfc8628#section-3.4) - OAuth 2.0 Device Authorization Grant focused on interaction with user outside of a browser context like smart TVs.
- [urn:ietf:params:oauth:grant-type:jwt-bearer](https://datatracker.ietf.org/doc/html/rfc7523) - JSON Web Token (JWT) Profile for OAuth 2.0 used to authorize a client to get an access token with another JWT issued by a trusted provider.
- [urn:ietf:params:oauth:grant-type:token-exchange](https://datatracker.ietf.org/doc/html/rfc8693) - OAuth 2.0 Token Exchange is a Grant Type which provides a way to get tokens from another token and give the ability to add an actor claim.
- [PKCE Extension](https://datatracker.ietf.org/doc/html/rfc7636) - Extension of the Authorization Code flow adding security layer against code interception attack.

### Specifications

#### Published

- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html) - Defines the core OpenID Connect functionality: authentication built on top of OAuth 2.0 and the use of Claims to communicate information about the End-User. It also describes the security and privacy considerations for using OpenID Connect.
- [The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749) - Underlying OAuth 2.0 protocol OpenID Connect is based on.
- [JSON Web Token (JWT)](https://datatracker.ietf.org/doc/html/rfc7519) - JWT specifications used for different tokens mentioned in OAuth 2.0 and OpenID Connect specifications.
- [JSON Web Encryption (JWE)](https://datatracker.ietf.org/doc/html/rfc7516) - Specifications for JWE which represents encrypted content using JSON-based data structures.
- [JSON Web Signature (JWS)](https://datatracker.ietf.org/doc/html/rfc7515) - Specifications for JWS which represents content secured with digital signatures.
- [The OAuth 2.0 Authorization Framework: Bearer Token Usage](https://datatracker.ietf.org/doc/html/rfc6750) - Describes how to use bearer tokens in HTTP requests to access OAuth 2.0 protected resources.
- [OpenID Connect Discovery 1.0](https://openid.net/specs/openid-connect-discovery-1_0.html) - Mechanism for an OpenID Connect Relying Party to discover the End-User's OpenID Provider and obtain information needed to interact with it.
- [OpenID Connect Back-Channel Logout](https://openid.net/specs/openid-connect-backchannel-1_0.html) - Logout mechanism that uses direct back-channel communication between the OpenID Connect provider (OP) and Relying Parties (RPs) being logged out.
- [OAuth 2.0 Authorization Server Metadata](https://datatracker.ietf.org/doc/html/rfc8414) - A metadata format that an OAuth 2.0 client can use to obtain the information needed to interact with an OAuth 2.0 authorization server.
- [OAuth 2.0 Token Revocation](https://datatracker.ietf.org/doc/html/rfc7009) - Endpoint for OAuth authorization servers which allows clients to notify the authorization server that a previously obtained refresh or access token is no longer needed.
- [OpenID Connect Dynamic Client Registration](https://openid.net/specs/openid-connect-registration-1_0.html) - Defines how an OpenID Connect Relying Party can dynamically register with the End-User's OpenID Provider.
- [OAuth 2.0 Token Introspection](https://datatracker.ietf.org/doc/html/rfc7662) - Method for a protected resource to query an OAuth 2.0 authorization server to determine the active state of an OAuth 2.0 token and to determine meta-information about this token.
- [Financial-grade API Security Profile 1.0 - Part 1: Baseline](https://openid.net/specs/openid-financial-api-part-1-1_0.html) - Baseline security profile of OAuth that is suitable for protecting APIs with a moderate inherent risk in the context of Financial-grade APIs.
- [Financial-grade API Security Profile 1.0 - Part 2: Advanced](https://openid.net/specs/openid-financial-api-part-2-1_0.html) - Advanced security profile of OAuth that is suitable to be used for protecting APIs with high inherent risk in the context of Financial-grade APIs.
- [JWT Secured Authorization Response Mode for OAuth 2.0 (JARM)](https://openid.net/specs/oauth-v2-jarm.html) - JWT-based mode to encode OAuth authorization response parameters with additional claims used to further protect the transmission.
- [OpenID Connect Session Management](https://openid.net/specs/openid-connect-session-1_0.html) - Specifications about OpenID Connect session management.

#### Draft

- [OAuth 2.0 Security Best Current Practice](https://www.ietf.org/archive/id/draft-ietf-oauth-security-topics-22.html) - Best security practice when using OAuth 2.0 and OpenID Connect.
- [OpenID Connect Federation 1.0](https://openid.net/specs/openid-connect-federation-1_0.html) - Draft specifications for putting in place bilateral federations between to organizations.
- [Financial-grade API: Client Initiated Backchannel Authentication Profile](https://openid.net/specs/openid-financial-api-ciba.html) - Financial services profile specifications for Client Initiated Backchannel Authentication (aka CIBA).

### Books

- [The Little Book of OAuth 2.0 RFCs by Aaron Parecki](https://www.amazon.com/Little-Book-OAuth-2-0-RFCs/dp/B084DFYJS1/)
- [OAuth 2.0 Simplified by Aaron Parecki](https://www.amazon.com/OAuth-2-0-Simplified-Aaron-Parecki/dp/1387751514/)
- [Solving Identity Management in Modern Applications: Demystifying OAuth 2, OpenID Connect, and SAML 2 by Yvonne Wilson](https://www.amazon.com/Solving-Identity-Management-Modern-Applications-ebook/dp/B0BMQHF83G/)
- [Keycloak - Identity and Access Management for Modern Applications: Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 protocols to secure applications by Stian Thorgersen and Pedro Igor Silva](https://www.amazon.com/Keycloak-Management-Applications-protocols-applications-ebook/dp/B092KP135B/)

### Websites

- [OpenID](https://openid.net/) - OpenID Connect official website.
- [OAuth](https://oauth.net/) - OAuth website maintained by Aaron Parecki which list different resources about the protocol.
- [Alex Bilbie](https://alexbilbie.github.io/tag/oauth/) - Alex Bilbie blog posts about OAuth topic.
- [CerberAuth](https://www.cerberauth.com/) - A blog talking about OpenID Connect and OAuth2.
- [Curity Resources](https://curity.io/resources/openid-connect/) - Curity solution resources articles about OpenID Connect.
- [Okta Blog](https://developer.okta.com/blog/tags/oidc/) - Okta blog posts about OAuth2 and OpenID Connect.
- [Medium OAuth2](https://medium.com/oauth-2) - Medium blog talking about OAuth2.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cerberauth/awesome-openidconnect/blob/master/CONTRIBUTING.md) first.
