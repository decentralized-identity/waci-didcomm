# WACI Test Vectors

## Prerequisites
1. [Wallet DID](./did/did%3Aexample%3Awallet.json)
2. [Issuer DID](./did/did%3Aexample%3Aissuer.json)
3. [Verifier DID](./did/did%3Aexample%3Averifier.json)

## Issuance
1. [User scans QR code or Clicks on redirect button on Issuer website using Digital Wallet](./issuance/1.out-of-band.json)
2. [Wallet sends DIDComm v2 Issue Credential - Propose message to Issuer](./issuance/2.issue-credential_propose.json)
3. [Issuer Sends DIDComm v2 Issue Credential - Offer message to Wallet](./issuance/3.issue-credential_offer.json)
4. [Wallet Sends DIDComm v2 Issue Credential - Request message to Issuer](./issuance/4.issue-credential_request.json)
5. [Issuer Sends DIDComm v2 Issue Credential - Issue message to Wallet](./issuance/5.issue-credential_issue.json)
6. [Wallet Sends DIDComm v2 Issue Credential - Ack message to Issuer](./issuance/6.issue-credential_ack.json)


## Presentation
1. [User scans QR code or Clicks on redirect button on Verifier website using Digital Wallet](./presentation/1.out-of-band.json)
2. [Wallet sends DIDComm v2 Present Proof - Propose message to Verifier](./presentation/2.present-proof_propose.json)
3. [Verifier Sends DIDComm v2 Present Proof - Request message to Wallet](./presentation/3.present-proof_request.json)
4. [Wallet Sends DIDComm v2 Present Proof - Presentation message to Verifier](./presentation/4.present-proof_present.json)
5. [Wallet Sends DIDComm v2 Present Proof - Ack message to Verifier](./presentation/5.present-proof_ack.json)
