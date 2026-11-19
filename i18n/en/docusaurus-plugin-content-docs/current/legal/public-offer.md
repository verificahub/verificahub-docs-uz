---
id: public-offer
title: Public offer
sidebar_position: 1
slug: /legal/public-offer/
---

# Public offer

**For user verification services provided through the Verificahub platform**

Effective date: 12.11.2026

Sole Entrepreneur (YATT) ISKUJIN AYGIZ IRIKOVICH (the "Provider" or "Verificahub"), in accordance with the Civil Code of the Republic of Uzbekistan, offers to enter into an agreement for the use of the Verificahub platform services. This document is a public offer (the "Offer").

*Translation. If the texts differ, the Uzbek text prevails.*

## 1. Definitions

- **Platform** — the verificahub.uz website, the app.verificahub.uz web application (personal account), the Verificahub API and the docs.verificahub.uz documentation.
- **Integrator** — a legal entity, sole entrepreneur or individual who has accepted the Offer.
- **Account** — the Integrator's personal account on the Platform.
- **End user** — a user of the Integrator's website or application whose phone number the Integrator sends to the Platform for verification.
- **OTP code** — a one-time verification code.
- **Verification session** — a process with its own identifier, created at the Integrator's request: sending an OTP code, checking it, retrieving statuses and receiving notifications (webhooks).
- **Balance** — the record of prepaid funds in the Integrator's Account.
- **Tariffs** — the prices published at [verificahub.uz/pricing](https://verificahub.uz/pricing/).

## 2. Subject of the Offer

2.1. The Provider provides the Integrator, through the Platform, with services for verifying End users' Uzbekistan phone numbers by OTP code, and the Integrator pays for the services according to the Tariffs.

2.2. OTP codes are currently sent by SMS to numbers of Uzbekistan mobile operators (+998). Other channels may be added later; their terms and prices will be published on the Platform.

2.3. The services are provided remotely in electronic form; no physical goods are delivered. Tashkent time (UTC+5) applies to the Offer.

2.4. The following form an integral part of the Offer: the [Refund policy](./refund-policy.md), the [Privacy policy](./privacy-policy.md), the [Consent to personal data processing](./personal-data-consent.md), the [End-user data processing terms](./data-processing.md) and the Tariffs.

## 3. Acceptance

3.1. Registration requires a first name, last name, email address and password. The email address is confirmed with a code sent to it.

3.2. When verifying the Account, the Integrator provides a phone number and ticks "I have read and accept the public offer". Ticking this box constitutes acceptance of the Offer. Topping up the Balance and using the services also constitute acceptance.

3.3. Acceptance means full and unconditional acceptance of the Offer. The agreement is deemed concluded in electronic form.

3.4. A person acting on behalf of an organization confirms that they are authorized to do so. An individual must be at least 18 years old and have full legal capacity.

## 4. Account, verification and security

4.1. The Integrator provides accurate and up-to-date information. If it changes, the Integrator updates it in the Account or notifies support@verificahub.uz within 5 (five) business days.

4.2. The Account is verified with a code sent to the phone number. The Provider may offer additional identification methods, including identification through OneID.

4.3. Before the services are used, the Provider may require the Integrator to confirm control of a website, application or domain (for example, by adding a TXT record to the domain's DNS). The services may be limited until this is completed.

4.4. The Integrator keeps its password, API keys and webhook secrets confidential. Actions performed through the Account and API keys are deemed to be the Integrator's actions. If a key is compromised, the Integrator replaces it immediately and notifies support@verificahub.uz.

## 5. How the services are provided

5.1. The Integrator creates a Verification session for an End user's phone number through the API and receives the session identifier. OTP checks, statuses and webhook notifications use this identifier.

5.2. Message text is based on the Provider's templates. The sender name is set in accordance with mobile operators' requirements.

5.3. SMS delivery depends on mobile operators, the SMS gateway and the recipient's device. The Provider takes reasonable steps to deliver messages but does not guarantee delivery of every message or delivery times.

5.4. Phone numbers are masked in Platform logs and stored in the database as hashes. See the [End-user data processing terms](./data-processing.md).

5.5. The Platform is provided "as is". Where possible, the Provider gives at least 24 hours' notice of planned maintenance. Unless a separate SLA is agreed, no availability level is guaranteed.

5.6. The Provider may develop the API and the Platform. Changes affecting existing integrations are announced in the documentation in advance.

## 6. Integrator obligations and prohibited use

6.1. The Integrator uses the services only for verification — sign-up, sign-in, confirming an action or confirming a phone number — and only for a number the End user entered themselves.

6.2. The Integrator is responsible for having a lawful basis for processing End users' data and for informing them. The Integrator states in its privacy policy that verification codes are sent through Verificahub.

6.3. The following are prohibited:

- sending advertising, marketing or informational messages, including inside an OTP message;
- fraud, phishing or impersonation;
- creating sessions to check number lists or detect whether numbers are active;
- attacking the Platform, artificially increasing load or bypassing protections;
- reselling the services without the Provider's written consent;
- any other activity contrary to the laws of the Republic of Uzbekistan.

6.4. The Integrator protects its website and application from abuse: it limits request rates, uses CAPTCHA where needed and monitors abnormal traffic. SMS sent as a result of artificial traffic (for example, SMS pumping) are charged.

6.5. The Integrator is liable for claims made against the Provider by mobile operators, government bodies or others because of a breach of section 6, and compensates the Provider for resulting losses.

## 7. Prices, Balance and payment

7.1. Prices are published in Uzbek sums on the Tariffs page. Tariff changes are announced at least 10 (ten) calendar days before they take effect. Messages sent after that are charged at the new Tariffs.

7.2. Services are provided on a 100% prepayment basis. The Balance is topped up through the payment provider's secure payment page using the methods offered there (for example, HUMO and UZCARD cards, and Visa and Mastercard cards issued in Uzbekistan). Funds are credited after the payment is confirmed.

7.3. For each SMS sent, the fee at the tariff in effect at the time of sending is deducted from the Balance, regardless of delivery status (delivered, undelivered, expired, etc.). No fee is charged for requests rejected by the Platform and not passed to the SMS gateway.

7.4. If the Balance is insufficient, new Verification sessions are not created. A negative Balance is not allowed.

7.5. The Balance does not expire while the Account exists.

7.6. Top-ups and charges are shown in the Account. If no reasoned objection is raised within 10 (ten) calendar days after the end of a billing month, the services for that month are deemed accepted.

7.7. The electronic receipt is issued by the payment system under its rules and the law. Legal entities and sole entrepreneurs may request closing documents via support@verificahub.uz.

## 8. Refunds

Unspent Balance is refunded under the [Refund policy](./refund-policy.md).

## 9. Restriction and suspension

9.1. The Provider may restrict or suspend the services without prior notice: if section 6 is breached; if fraud, spam or abuse is suspected; at the request of a mobile operator or competent authority; if the Platform's security is threatened; or if the Integrator provided false information. Where possible, the Provider tells the Integrator the reason.

9.2. In the event of a serious or repeated breach, the Provider may terminate the agreement unilaterally. The remaining Balance is refunded under the [Refund policy](./refund-policy.md), less any losses under clause 6.5.

9.3. If the Integrator disputes a Balance top-up payment through its bank (chargeback), the Provider may suspend the Account until the dispute is resolved and, for an unjustified or repeated chargeback, terminate the agreement. Refunds should be requested under the [Refund policy](./refund-policy.md).

## 10. Term and termination

10.1. The agreement is valid indefinitely from acceptance.

10.2. The Integrator may terminate at any time by deleting the Account in the web application or by writing to support@verificahub.uz. A refund request for the remaining Balance must be submitted before deleting the Account.

10.3. The Provider may terminate with 30 (thirty) calendar days' notice (except in the cases in clause 9.2).

10.4. After the Account is deleted, data is deleted or anonymized within the periods set out in the [Privacy policy](./privacy-policy.md).

## 11. Liability

11.1. The parties are liable in accordance with the laws of the Republic of Uzbekistan and the Offer.

11.2. The Provider is not liable for: failures of mobile operators, the SMS gateway, internet providers or the Integrator's systems; consequences of disclosure of the Integrator's keys or passwords; an incorrect number provided by the Integrator; indirect losses or lost profits.

11.3. The Provider's total liability is limited to the amount paid by the Integrator in the 3 (three) months before the claim arose.

11.4. Neither party is liable for force majeure: natural disasters, fire, epidemics, decisions of government bodies, or major failures of communication networks. Such an event must be notified within 14 (fourteen) calendar days. If it lasts more than 2 (two) months, either party may terminate the agreement.

11.5. Nothing in the Offer limits the statutory rights of individuals as consumers.

## 12. Personal data and confidentiality

12.1. Data of the Integrator and its representatives is processed under the [Privacy policy](./privacy-policy.md); the Provider is the owner and operator of this personal data.

12.2. For End users' data, the Integrator is the owner and the Provider is an operator acting on the Integrator's instructions, as set out in the [End-user data processing terms](./data-processing.md).

12.3. Personal data processed on the Platform is stored on servers in the Republic of Uzbekistan.

12.4. The parties keep commercial and technical information received under the agreement confidential for 3 (three) years after it ends, except as required by law.

## 13. Intellectual property

13.1. The Platform, its software, design, documentation and the Verificahub name and logo belong to the Provider or the respective rights holders.

13.2. For the term of the agreement, the Integrator receives a non-exclusive right to use the Platform in accordance with the Offer. Copying, decompiling or otherwise using the Platform beyond the Offer is prohibited.

## 14. Notices and changes to the Offer

14.1. The Provider sends notices to the email address in the Account. Service messages are sent from no-reply@verificahub.uz; replies to it are not read. Requests should be sent to support@verificahub.uz.

14.2. The Provider may amend the Offer. The new version is published at docs.verificahub.uz. Material changes are notified by email at least 10 (ten) calendar days before they take effect. Continuing to use the services after that constitutes acceptance. If the Integrator disagrees, it may terminate the agreement and request a refund of the remaining Balance.

## 15. Disputes

15.1. Disputes are resolved by negotiation. A claim is sent to support@verificahub.uz and reviewed within 15 (fifteen) calendar days of receipt.

15.2. If no agreement is reached, the dispute is heard by the competent court in accordance with the laws of the Republic of Uzbekistan.

15.3. The parties comply with the Law of the Republic of Uzbekistan "On Combating Corruption".

15.4. The Offer is published in Uzbek, Russian and English. If the texts differ, the Uzbek text prevails.

## 16. Provider details

- **Provider:** Sole Entrepreneur (YATT) ISKUJIN AYGIZ IRIKOVICH
- **State registration certificate:** No. 8125433, issued by the Shaykhontokhur District Public Services Center
- **Address:** Tashkent city, Shaykhontokhur district, Zulfiyaxonim street, 27, 29, 29 AUY
- **Support:** support@verificahub.uz
- **General enquiries:** info@verificahub.uz
- **Phone:** +998 92 027 99 35
- **Website:** [verificahub.uz](https://verificahub.uz)
