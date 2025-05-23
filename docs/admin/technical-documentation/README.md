# Identity & Access Management

## As-Is Authentication Management

Authentication Flow - User login to Catena-X

![AuthenticationFlow](/docs/static/authentication-flow.png)

\*(Schatten-) User: The „Schatten-User“ (shadow user) is defined as an empty User frame holding limited information. The actual user is managed in the respective Identity Provider.
The shadow users are always federated identities.

## Authentication Protocol - OpenID Connect (OIDC)

![AuthenticationProtocol](/docs/static/authentication-protocol.png)

## NOTICE

This work is licensed under the [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0).

- SPDX-License-Identifier: Apache-2.0
- SPDX-FileCopyrightText: 2023 Contributors to the Eclipse Foundation
- Source URL: https://github.com/eclipse-tractusx/portal-iam
