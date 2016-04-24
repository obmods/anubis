# Terms & Conditions of Moderation

[![Terms & Conditions](https://img.shields.io/badge/Terms%20%26%20Conditions-Anubis-blue.svg)](#)

Please look through these terms and conditions. By selecting this moderator, you accept this agreement, which will define whether you win a dispute.

> These terms are updated periodically. The version that applies to a dispute is the latest commit on this branch when funds arrive in escrow.

> View previous versions at [/commits/branch-name](../../commits) using the `<>` buttons in the right-hand column.

> Want to display badges like the one above on your OpenBazaar page? [Here's how.](https://github.com/obmods/anubis/wiki/Using-Badges)

<!-- toc -->

- [Common Scenarios](#common-scenarios)
- [Fault](#fault)
    + [Quality](#quality)
- [Refusing Disputes](#refusing-disputes)
    + [Blacklist](#blacklist)
    + [Conflicts of Interest](#conflicts-of-interest)
- [Proof](#proof)
- [Privacy](#privacy)
- [Legal Compliance](#legal-compliance)
- [License](#license)

<!-- tocstop -->


## Common Scenarios

[![](https://img.shields.io/badge/waits-3%20days-lightgrey.svg)](#common-scenarios)

| Scenario | Condition | Result
| --- | --- | ---
| A party does not respond after the moderator reaches out. | 3 days (72 hours) pass | Other party wins.
| Package tracking fails to update or shows the item is lost. | 10 days (240 hours) pass | Funds are split 50/50.
| Package fails to arrive after estimated time. Tracking is not available. | 10 days (240 hours) pass | Buyer wins.

## Fault

Either party can make a minor, major, or critical fault. In a dispute, the party primarily responsible for a critical fault loses. Major and minor faults are considered on a case-by-case basis. If neither party is at fault, the decision is a tie and funds are split equally. (This rarely occurs except in cases where the shipping company is entirely responsible for losing the item.)

A party making a claim about fault must demonstrate it. (See [Proof](#proof).)

> This list is not exhaustive, and the moderator reserves the right to add items at any time.

#### Critical

| | |
| --- | ---
| **Either Party** | <ul><li>Does not respond to the moderator for 3 days (72 hours)</li><li>Blatantly lies (attempts to deceive with full knowledge)</li></ul>
| **Vendor** | <ul><li>Does not ship the product or provide the service, and does not substantiate a reason</li><li>Provides an invalid or incorrect bitcoin payment address</li></ul>
| **Buyer** | <ul><li>Provides an invalid or incorrect physical address or bitcoin refund address</li></ul>

#### Major

|  | |
| --- | ---
| **Either Party** | <ul><li>Breaks the vendor's Terms & Conditions</li></ul>
| **Vendor** | <ul><li>Provides a product or service of unacceptable quality (see [Quality](#quality)), and does not allow returns</li><li>Inadequately packages the item, causing it to arrive damaged</li><li>Does not offer tracked shipping, does not advertise this, and the package is not delivered</li></ul>
| **Buyer** | <ul><li>Damages the product or abuses the service</li><li>Returns a different item than the one sent</li><li>Does not choose tracked shipping even though the vendor offers it</li></ul>

#### Minor

|  | |
| --- | ---
| **Vendor** | <ul><li>Does not use a [top-ten shipping company](http://www.supplychaindigital.com/top10/2497/Top-10:-Shipping-Companies), does not advertise this, and the package is not delivered</li></ul>
| **Buyer** | <ul><li>Opens a dispute with an unsubstantiated claim against the vendor</li><li>Opens a dispute for no reason</li><li>Does not pick up the package even though tracking shows it was delivered</li></ul>

#### Quality

Claims about quality of the product will be judged according to the following standards, in order:

1. Statements in the vendor's terms and listing which guarantee, imply, or disclaim quality.
2. Statements in the moderator's example vendor terms (if available).
3. Common sense of an average consumer.

For food and drugs, the moderator will not personally assess the safety or quality of consuming the product, relying only on standards specified by the vendor.

## Refusing Disputes

[![](https://img.shields.io/badge/refuses-blacklisted%20items%20%26%20conflicts%20of%20interest-lightgrey.svg)](#refusing-disputes)

A dispute will be refused if its contents are on [the blacklist](/blacklist.md), or if it presents a conflict of interest for the moderator. In rare cases, the moderator may refuse the dispute for another reason and then add that reason to these Terms & Conditions.

If refused, the buyer and vendor will be left to sort out the transaction themselves, until OpenBazaar provides a mechanism to transfer moderators.

#### Blacklist

An [accompanying document](/blacklist.md) lists the products, services, and entities for which the moderator refuses to arbitrate. Vendors are responsible for checking their listings against it while the moderator is offered on their stores.

#### Conflicts of Interest

A conflict of interest arises if a party has one of the following relationships to the moderator:

- Business partner
- Employer or employee
- Stakeholder
- Close friend or relative
- Government entity with jurisdiction over the moderator
- Same entity as moderator

A party must reveal any evidence for a conflict of interest as soon as possible during a dispute.

## Proof

If a party makes a claim, it is their responsibility to support it with evidence proportional to the claim.

A photo is strong evidence if it displays a legible shipping label or other uniquely identifiable characteristic, and it does not show signs of image manipulation.

A screenshot is reasonable evidence if it is not manipulated.

Giving details related to an event is plausible evidence if the details can be independently confirmed.

## Privacy

[![](https://img.shields.io/badge/privacy-asks%20before%20sharing-lightgrey.svg)](#privacy)

The moderator respects your privacy. Your messages to the moderator, personal information, and details of the dispute will not be shared outside of the following groups:

- This moderator's team members / employees
- Possibly Law Enforcement (see [Legal Compliance](#legal-compliance) for details)

Your permission may be requested on a case-by-case basis to share data with third parties (ex: OpenBazaar developers for debugging). However, you have the right to decline.

Characteristics of aggregated disputes may be shared publicly in a way which does not identify individuals.

## Legal Compliance

[![](https://img.shields.io/badge/laws-complies%20as%20required-lightgrey.svg)](#legal-compliance)

You are responsible to follow laws that apply to you. The moderator is not obligated to assess the lawfulness of a transaction, and in most cases will not do so.

The moderator will comply as required with applicable laws and law enforcement in the moderator's area of residence. This includes divulging dispute history, messages, and personal information only when they are demanded with the proper legal authority (ex: valid warrant).

The moderator's decision is only cryptographically binding, not legally binding.

## License

The text of these Terms & Conditions is released into the public domain under `CC0`, meaning you are free to use or modify it for your own purposes, without restriction. Your changed version is not binding upon this moderator. Likewise, the original document is not binding upon users of altered versions.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
</p>
