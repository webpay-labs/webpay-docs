---
sidebar_position: 1
---

# What is Webpay?

Webpay is a decentralized payments network on the Solana blockchain. Unlike traditional payment networks operated by VISA or Mastercard who charge upwards of 3% per transaction, Webpay charges 0.3% per transaction, allows customers to pay merchants directly in SOL, USDC or USDT from their own wallets, and enables merchants in any industry to start accepting payments from customers globally in as little as 10 minutes.

## Payment Network, Interfaces, Labs

Before you jump in, it's important to understand the different areas of the Webpay ecosystem, some of which might be confusing to new users.

- Webpay Labs: The set of active contributors behind the Webpay network along with the consumer and merchant interfaces.
- The Webpay Network: A set of persistent, non-upgradable smart contracts on the Solana blockchain which facilitate peer-to-peer payments between consumers and merchants.
- Webpay Interfaces: There are two main interfaces maintained by the Webpay Labs team: the merchant and consumer interface. The merchant interface lets merchants manage their payments and payouts in one place. The consumer interface let's users view their payments to merchants and manage disputes.

## Introduction

The Webpay network is a peer-to-peer system designed for processing payments between customers and merchants using SPL tokens on the Solana blockchain. The network is implemented as a set of persistent, non-upgradable smart contracts and client and server side SDKs that allow merchants to configure their web or physical properties to accept payments. The network is designed to prioritize censorship resistance, security, self-custody, and to function without any trusted intermediaries who may selectively restrict access.

## How does the Webpay network compare to a typical payments network?

To understand how the Webpay network differs from existing payment networks it’s useful to look at two existing payment network paradigms: traditional card networks like VISA or Mastercard and centralized crypto payment platforms like Coinbase Commerce, Crypto.com Pay or FTX Pay to name a few.

### Webpay vs VISA/Mastercard

Payments in the traditional financial system usually involve six parties:

- Consumers (you)
- Merchants (a store you buy from)
- Credit Card Processors (e.g. Stripe)
- Acquiring Bank (merchants bank; e.g. Chase, Wells Fargo, Barclays, etc)
- Credit Card Network (VISA, Mastercard)
- Issuing Bank (your bank; e.g. Chase, Wells Fargo, Barclays, etc)

In the traditional financial system, when you purchase a good at a store, the typical flow of funds between you and the merchant is as follows:

1. You use your credit card to pay for goods or services at a merchant.
2. The merchant transmits the card data to their credit card processor.
3. The processor sends the payment information to the acquiring bank. The processor may also be the acquiring bank (e.g. Merchant banks with Chase and uses Chase Pay to accept payments from customers).
4. The acquiring bank transmits the payment request to the appropriate card network.
5. The card network processes the card data and sends it to the issuing bank.
6. The issuing bank verifies the available credit limit in the customer account and either approves or declines the transaction.
7. The approval or denial is sent to the acquiring bank. If the transaction was approved, the acquiring bank releases payment to the credit card processor.
8. The credit card processor releases payment to the merchant.
9. The consumer pays the issuing bank directly when the credit card payment is due.

Each of these parties typically takes a cut of the overall transaction fee (typically ~3%) but can vary based on the card or network used.

The Webpay network takes a different approach to processing payments using a smart contract to process the payment between the customer and the merchant and utilizing self-custodied wallets presented by the customer at the time of purchase and the merchant at the time of registration to facilitate the flow of funds between customer and merchant.

Here’s a typical example of flow of funds on the Webpay network.

1. You choose Webpay as your preferred payment method when purchasing goods or services at a merchant. Merchant installed software connects to your wallet and requests approval for the transaction amount.
2. You approve the transaction amount and the payment is sent into a Webpay escrow account handled by a smart contract.
3. The smart contract receives the amount and processes the payment into the merchant wallet assuming the merchant is in good standing on the Webpay network.

### Webpay vs traditional crypto payments

Webpay differs from traditional crypto payments through it’s permissionless design. Permissionless design means that the protocol’s services are entirely open for public use, with no ability to selectively restrict who can or cannot use them. Anyone can register as a merchant, pay for goods, or receive payments at will. This is a departure from traditional financial services, which typically restrict access based on geography, industry, wealth, status, and age.
