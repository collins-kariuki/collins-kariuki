<div align="center">

# Collins Kuria

**Senior Software Engineer** · Nairobi, Kenya · UTC+3

`MSc Computer Science, Georgia Tech` &nbsp;·&nbsp; `BSc Computer Science, University of Nairobi`

<br>

### I build the machinery behind moments people actually touch.

<br>

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-087EA4?style=for-the-badge&logo=react&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

</div>

<br>

<table>
<tr>
<td width="38%" valign="top">

### 🥤
**A shopper cracks open a can in a duka in Nairobi.**

</td>
<td width="62%" valign="top">

The product shipped with no printed codes. So we invented proof of purchase: two photos, sealed then opened, and a vision engine that reads the tab, matches the same physical can across changed light and angle, and remembers every image it has ever seen.

`500,000 scans` &nbsp;`89% accuracy` &nbsp;`zero human review`

</td>
</tr>
<tr>
<td width="38%" valign="top">

### 🎫
**A badge touches a reader and a door opens.**

</td>
<td width="62%" valign="top">

Multi-tenant NFC and RFID access control for enterprise events. Venue wifi dies constantly, so the clients hold their own state and sync on reconnect. A connectivity blip must never become a queue at a door.

`multi-tenant` &nbsp;`offline-first` &nbsp;`real-time analytics`

</td>
</tr>
<tr>
<td width="38%" valign="top">

### 📲
**A wage lands on a phone at the end of a shift.**

</td>
<td width="62%" valign="top">

Mobile money disbursement over M-Pesa. Idempotent on a natural key, reconciled against callbacks that arrive twice, arrive late, or never arrive. The hard case is never failure. It's the payment where nobody knows what happened.

`M-Pesa Daraja` &nbsp;`idempotent` &nbsp;`auto-reconciled`

</td>
</tr>
<tr>
<td width="38%" valign="top">

### 🏦
**A balance updates in a banking app.**

</td>
<td width="62%" valign="top">

The core double-entry ledger of a stablecoin and fiat neobank. Append-only, balances derived rather than stored. On-chain settlement on one side, mobile money on the other, two counterparties settling on completely different clocks and reconciled into one truth.

`double-entry` &nbsp;`on-chain` &nbsp;`append-only`

</td>
</tr>
</table>

<br>

### How I work

Design for the ambiguous path first. The happy path and the error path are both easy.

Treat every boundary as unreliable. Idempotency isn't defensive coding, it's the only way a system converges when the same message shows up twice at 2am.

Alert on invariants that should always hold, not on thresholds someone guessed.

When automation can't be certain, hand it to a person. A system that silently repairs its own ledger can silently corrupt it.

<br>

> Most of this work sits under client NDA, so it isn't here. What I publish are the patterns underneath it: the ledger core, the reconciliation loop, the failover orchestration.

<br>

<div align="center">

[LinkedIn](https://linkedin.com/in/collins-kuria) &nbsp;·&nbsp; [Email](mailto:collins_kuria@hotmail.com)

<sub><i>The quieter you become, the more you are able to hear.</i></sub>

</div>
