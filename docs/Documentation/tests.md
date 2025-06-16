---
title: tests
deprecated: false
hidden: false
metadata:
  robots: index
---
<Cards columns={3}>
  <Card title="Accept One-Time Payments" icon="fa-credit-card" target="_blank">
    One-time payments are ideal for a single transaction without storing payment details.<br /><br />
    **Use cases:** Retail checkout; Event registrations; Invoice or service-fee payments.
  </Card>

  <Card title="Accept Payments with Saved Details" icon="fa-save">
    Save customer payment methods securely for faster repeat purchases.<br /><br />
    **Use cases:** Returning e-commerce customers; Subscription sign-ups; Vendor payments.
  </Card>

  <Card title="Accept Recurring Payments" icon="fa-sync-alt">
    Automate charges at defined intervals for subscriptions and memberships.<br /><br />
    **Use cases:** SaaS subscriptions; Membership dues; Installment billing.
  </Card>
</Cards>

<br />

## Payment Methods

PCE supports a variety of [payment methods](doc:payment-methods) to suit your business needs. Choose from any of the options below:

<Cards columns={4}>
  <Card title="Card" icon="fa-credit-card">
    Accept all major credit & debit cards (Visa, Mastercard, AMEX, Discover).
  </Card>

  <Card title="ACH Bank Debit" icon="fa-university">
    Process U.S. bank-account debits for lower-cost transactions.
  </Card>

  <Card title="Check Deposit" icon="fa-money-check">
    Handle manual check payments with digital deposit workflows.
  </Card>

  <Card title="Wire Transfers" icon="fa-exchange-alt">
    Support domestic and international bank-to-bank transfers.
  </Card>
</Cards>

<Cards columns={4}>
  <Card title="First Card" href="https://readme.com" icon="fa-home" target="_blank">
    Neque porro quisquam est qui dolorem ipsum quia
  </Card>

  <Card title="Second Card" icon="fa-user">
    *Lorem ipsum dolor sit amet, consectetur adipiscing elit*
  </Card>

  <Card title="Third Card" icon="fa-star">
    > Ut enim ad minim veniam, quis nostrud ullamco
  </Card>

  <Card title="Fourth Card" icon="fa-question">
    **Excepteur sint occaecat cupidatat non proident**
  </Card>
</Cards>

<br />

#### Metadata description

Process and settle payments instantly with a single API call—ideal for immediate-order fulfillment.

# Overview

The Direct Sale (Immediate Capture) method authorizes and captures funds in one step, delivering fast, straightforward payment processing for merchants fulfilling orders right away—such as digital goods, event tickets, or in-stock products.

**In this guide you’ll learn**

* When to use Direct Sale vs separate auth and capture
* How to structure your single-sale API request
* How to handle PCE’s synchronous response

### Prerequisites & limitations

* Active merchant account with card processing enabled
* PCI DSS Level 1 compliance
* Network permissions for enhanced data (L1, L2 & L3) when collecting detailed line-item information

# Feature table

| Feature                 | Description                                                             |
| ----------------------- | ----------------------------------------------------------------------- |
| Combined Auth & Capture | Authorization and capture in one API call                               |
| Synchronous Response    | Immediate success or failure confirmation                               |
| Level 2/3 Data Support  | Attach enhanced transaction details (L1, L2 & L3) for optimized routing |

# Key details

## Direct Sale (Immediate Capture)

A “Direct Sale” or “Sale” transaction combines authorization and capture into a single step. This method is best when you need to charge the customer’s card and begin transferring funds as soon as the transaction is approved.

Use this method when you want a fast, one-step payment flow that immediately settles funds into your account.

1. Customer submits payment details.
2. Merchant server sends one `CREATE_TRANSACTION` API request to PCE, including amount, payment data, and optional L2/L3 fields.
3. PCE contacts card networks to authorize and immediately capture funds.
4. PCE returns a synchronous response indicating success or failure.

<Cards columns={2}>
  <Card title="Reference documentation" href="https://documentation.prioritypassport.com/passport-docs/v3.0.0/docs/doc-create-transaction" icon="fa-book" target="_blank">
    API Reference
  </Card>

  <Card title="Reference documentation" href="https://documentation.prioritypassport.com/passport-docs/v2.0.0/docs/pm-entities" icon="fa-book" target="_blank">
    API Guide
  </Card>
</Cards>