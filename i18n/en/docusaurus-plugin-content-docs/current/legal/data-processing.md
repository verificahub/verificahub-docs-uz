---
id: data-processing
title: End-user data processing terms
sidebar_label: Data processing terms
sidebar_position: 5
slug: /legal/data-processing/
---

# End-user data processing terms

Effective date: 12.11.2026

*Translation. If the texts differ, the Uzbek text prevails.*

These terms are an integral part of the [Public offer](./public-offer.md) and apply to End users' data that the Integrator sends through the Verificahub API.

## 1. Roles

1.1. For End users' data, the **Integrator** is the owner of the personal data, and **Verificahub** is an operator that processes it on the Integrator's instructions and only to provide the services.

1.2. Verificahub does not use this data for its own purposes — advertising, profiling, sale or disclosure to third parties.

## 2. Data

- the End user's phone number (+998);
- the OTP code;
- the Verification session identifier, statuses and timestamps;
- delivery statuses received from mobile operators;
- technical parameters sent with the Integrator's request.

The Integrator does not send unnecessary personal data in request parameters (for example, metadata fields).

## 3. Purposes

- sending and checking the OTP code;
- providing statuses and sending webhook notifications;
- counting messages sent and billing;
- preventing fraud and abuse;
- handling claims and disputes.

## 4. How data is processed

4.1. The phone number is used in plain form only for as long as needed to send the SMS, and is passed to the SMS gateway provider.

4.2. In the database the phone number is stored as a hash. In Platform logs the number is masked.

4.3. The OTP code is not stored in plain form and is checked only while the Verification session is valid.

4.4. The Integrator performs further actions using the Verification session identifier.

## 5. Sub-processors

5.1. Verificahub may engage service providers to deliver the services: SMS gateways, mobile operators, servers and data centers. They process data only as needed to perform their functions, do not use it for their own purposes, and are bound to keep it confidential and secure.

5.2. Verificahub is responsible to the Integrator for the actions of the service providers it engages.

## 6. Localization

End users' data is stored on servers in Uzbekistan. Cross-border transfer takes place only in compliance with the law.

## 7. Retention

| Data | Period |
|---|---|
| OTP code | while the Verification session is valid |
| Verification session records (hashed number, statuses, time, price) | 12 (twelve) months — for billing and claims |
| Logs (numbers masked) | 90 (ninety) days |

After that, data is deleted or converted into anonymized statistics. When the agreement ends, the Integrator may request earlier deletion; records needed for billing are kept as required by law.

## 8. Security

Verificahub applies TLS encryption, hashing and masking, least-privilege access, sign-in monitoring and staff confidentiality obligations.

## 9. Incidents

If a security incident affecting End users' data is detected, Verificahub notifies the Integrator without undue delay, where possible within 72 hours, and takes steps to limit its consequences.

## 10. Requests from data subjects

End users contact the Integrator about their data. If a request reaches Verificahub, Verificahub forwards it to the Integrator and helps prepare a response.

## 11. Integrator obligations

The Integrator:

- has a lawful basis for processing End users' data;
- informs End users in its privacy policy that verification codes are sent through Verificahub;
- sends only numbers entered by the End users themselves;
- sends only the data that is needed.
