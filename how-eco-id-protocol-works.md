# How Eco ID protocol works

First of all, Eco IDs are non-transferable NFTs that conform to the ERC-721 standard. Each NFT contains an arbitrary claim that is attested to by at least one verifier, along with a list of the verifiers who have attested to the claim. The claim can contain any piece of data an individual or collective might want to be associated with a public Ethereum address.\
\


There are three types of actors in the Eco ID system, and anyone can serve as any of these actors:

* Verifiers attest on-chain to certain data points about Receivers
* Receivers request attestations from Verifiers
* Readers consume the attestations about Receivers for their own purposes



Different types of actors means also different ways to interact with Eco ID protocol :

* You can create an attestation with your signature, to certify and associate data, and competencies or attribute a subscription to someone (Verifier to Receiver)
* You can attest the information Verifier claim in an attestation by signing the same attestation. Once the attestation contains both signatures, your Eco ID is ready to be registered and minted. This will call two different methods :&#x20;
  * registered method: you link the new attestation data to your Eco ID, but this doesn't appear on your Eco ID until you decide to mint it. The same attestation containing the same data can be registered only once.
  * mint method: after you register your attestation, you can mint your Eco ID so it will contain the new data. This will appear as new Verifiers on your Eco ID&#x20;

