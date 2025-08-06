---
description: Spend stablecoins privately, anywhere Visa is accepted.
cover: ../../.gitbook/assets/Frame 2095593184.png
coverY: 0
---

# Payy Card

Payy Card is a self-custodial Visa card that allows you to spend USDC from your Payy Wallet in stores or online. It combines private onchain settlement with global card acceptance.

## How to get Payy Card

1. [Download Payy Wallet](https://payy.link/download)
2. Complete identity verification
3. Receive your virtual Payy Card
4. Deposit funds to your Payy Wallet from banks, crypto exchanges or blockchains
5. Use your Payy Card online or in-store; transactions are settled privately on Payy Network
6. Optionally, unlock and get your physical card

## Features

| Feature                                        | Description                                                                                                                                       |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Privacy-preserving payments                    | Transactions are settled on Payy Network using zero-knowledge proofs. Onchain wallet balances and activity cannot be linked to card transactions. |
| Self-custodial                                 | You control your funds at all times. No custodial risk.                                                                                           |
| No fees                                        | No fees to apply. No transaction or top-up fees. No monthly fees.                                                                                 |
| Virtual card                                   | Issued instantly upon identity verification. Use by copy/pasting the card number or by manually adding to Apple Pay / Google Pay.                 |
| [light-up-card.md](light-up-card.md "mention") | Contactless-only (no chip or swipe). Tap-to-pay activates a glowing Payy logo — the first card of its kind.                                       |
| ATM access                                     | Contactless ATM withdrawals are supported (in private beta; contact support for access).                                                          |
| No credit check                                | Applying only requires identity verification. No credit history is pulled.                                                                        |
| Freeze functionality                           | You can freeze/unfreeze your card at any time in the app.                                                                                         |
| Name/address changes                           | Reach out to in-app support to update billing name or address.                                                                                    |

## Card type

* Issuer: U.S.-based
* Network: Visa (Platinum)
* Card classification: Secured credit card (spending is limited to your Payy Wallet balance)
* Form factors: Virtual and physical

## Identity verification

* [identity-verification.md](../../core-concepts/identity-verification.md "mention") is required to receive a card
* Your identity and verification data cannot be linked to your Payy Network blockchain transactions
* Information we have to collect varies between countries but generally its your name, birth date, address, government ID number and ID photo.

## Usage notes

* In-store: Use Apple Pay, Google Pay, or the [physical card](light-up-card.md) (contactless only)
* Online: Use the card number directly
* Virtual card: Must be added to Apple/Google Pay manually
* Deposits: You can fund your Payy Wallet from bank accounts in the U.S. and Argentina (more countries coming soon)
* Cross-border support: Some online merchants in certain countries may reject U.S.-issued cards
* Non USD purchases: Purchases denominated in currencies other than USD have a 1% foreign exchange fee (probably better than your bank).

## Adding to Apple Pay or Google Pay

You can add Payy Card to Apple Pay or Google Pay by going to the Apple Wallet or Google Wallet app. Add a new credit card and enter your Payy Card details to activate.

## How Payy Card Privacy works

[Broken link](broken-reference "mention") uses [05\_utxo.md](../../payy-network/05_utxo.md "mention") transactions and doesn't publicly expose your address or transaction values. This means your "tradfi" Visa payments data can never be linked to your Payy Network balance. Every time you make a purchase with your Payy Card, there is a Payy Network transaction that debits the purchase amount from your UTXO notes.

Read more about [privacy.md](../../core-concepts/privacy.md "mention").

## Documents

* [US user agreement](https://docs.google.com/document/d/1wGKJZUYcFzkZCIz5hzeiHxqOo8aRQmouEgW3MW3hkI8/edit?tab=t.0)
* [International user agreement](https://docs.google.com/document/d/1hSOkUopLXIUrL5q4uVhQy7jJbCvvpIYanEIs0epQinE/edit?tab=t.0)
* [Visa Platinum benefits](https://drive.google.com/file/d/1kyHWoeas2mv7kZ319zcKcat6Anxnv5mk/view?usp=sharing)

## Support

For any issues (billing info updates, card not working, etc.) contact support directly in the app.
