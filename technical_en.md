# OmniOne Technical Documentation (v1.0)

1. OmniOne blockchain overview

The OmniOne's blockchain uses modified dPoS and aBFT consensus algorithm, enabling high performance in terms of TPS. With the ability to perform over 2,000 transactions per second,  Decentralized Identifiers (DIDs)  signature verifications, Verifiable Claims issuance as well as Verification processes can be executed almost instantly. By replacing the legacy system based on centralized infrastructures with the blockchain technology, OmniOne is the decentralized identity platform that aims to provide anyone a more convenient and secure means of identification while rewarding active contributors to the identification process with OMN tokens.

The blockchain technology will mainly be used to manage all processes related to DIDs and identification. OmniOne neither collects any personal information of the user nor stores them in the blockchain during the identification process. Also, OmniOne was designed to foster the participation of issuers of Verifiable Claims in its ecosystem by providing them a new identification infrastructure at a lower cost. With the OmniOne's platform, Service Providers, which require users' identification, will not only be able to benefit from the blockchain efficiency to provide cheaper services than currently but also to satisfy an increasing market need.

![omniSW](https://github.com/OmniOne-Blockchain/Bahama_Demo/blob/master/img/omniSW.png)


2. Self-Sovereign Identity (SSI) model using DID

OmniOne is the Decentralized Identity platform combining FIDO specifications and Blockchain technology that aims at helping users take back sovereignty over their full identity through the Self-Sovereign Identity.

While being based on the DID specifications developed by W3C, the OmniOne's DID method specifications  (https://github.com/OmniOneID/did_method) have been implemented in the OmniOne's blockchain. Such implementation solved one of the critical issue that remained unsolved by legacy PKI environment: the issue related to the public key delivery.

The OmniOne DID consists of a JSON data format that includes an ID and a public key, and these data are stored in the blockchain, enabling DID Entity (or the DID owner) to easily ascertain whose claims are authentic when claiming its own identity.

Following DID specifications, the DID document gathers the Decentralized Identifier and the public key corresponding to the DID. Once created, the DID document of each user as a whole is stored in the blockchain.

User DID documents stored in the blockchain ledger cannot be tampered with and removed. While combining Blockchain and DID, OmniOne is a secure infrastructure that enables DID-based identification.



3. Secure storage of DID private keys and FIDO

![img](https://github.com/OmniOne-Blockchain/Bahama_Demo/blob/master/img/BC%2BFIDO.png)

OmniOne provides a powerful security mechanism for devices when users use Online Service or Web Service.

OmniOne is designed to deliver services with more robust security than existing SSI models that do not emphasize on secure management of private keys  by delegating parts of the management of private keys that are not clearly presented by traditional DID specs to FIDO's biometric authentication.

Eventually, by combining FIDO and decentralized PKI (dPKI),  OmniOne implemented dFIDO, strengthening security.



4. Verifiable Credential

![credential](https://www.w3.org/TR/verifiable-claims-data-model/diagrams/credential.svg)

Source:https://www.w3.org/TR/verifiable-claims-data-model/

A claim is a verifiable credential that uses DID while making assertion about the DID owner in OmniOne. The latter was developed in compliance with W3C Specifications (https://www.w3.org/TR/verifiable-claims-data-model/). Additionally, OmniOne designed a unique model based on assurance level and pricing policies of Verifiable Claims issued by Issuers. The Verifiable Claim (VC) corresponds to a proof of ID based on DID and owned by the user who can submit it when required. Once verified in the blockchain, the role of  VC becomes crucial as it works as the base of trust between participants in the ecosystem.

The OmniOne Token (OMN) will incentivize active contributors in the ecosystem. Thus, Issuers issuing VC (which owns User's data) that will be used by Service Providers will receive rewards for their contributions. While verifying that the VC is trustworthy, Service Providers will be able to verify the identity of their users at a lower cost without relying on a third-party thanks to the blockchain. In exchange of getting a trustworthy information enabling identification of the user, Service Providers will pay active contributors such as Issuers of VC through OMN Token.

Such design of DID-based Verifiable Credential enables to incentivize main contributors of the OmniOne public blockchain. The demonstration will briefly show how the OMN token is used while using OmniOne eID.




5. Personal information and Data Hub

In the legacy identification system, users' personal data were often reused without their consents by the entities or service providers that required relevant data. The blockchain, and more precisely Decentralized Identifier (DID) offers a new possibility that can benefits to users. DID give back the sovereignty of personal information to individuals as it enables users to control the use of their personal information by determining the purpose and the period of use of their data when submitted to entities.  

With OmniOne, personal information are stored in the user's device an only hashed value are stored in the blockchain. That said, Services Providers might need users to provide them with a minimum of information before granted the access to a service. Also, in case of device loss,  users might have issue to recover their DID. In order to solve these concerns, the OMN Data Hub has been designed, enabling not only a better usability for service providers while providing a convenient recovery means for users in case of device loss. The data hub is a distributed repository where users can securely store their personal information and define where to use them. Thus, personal information recovery and service accessibility are facilitated when a device is lost.

With the OMN Data Hub, personal information can be securely stored and exchanged, with the consent of users, as well as they can be recovered at any time even in case of device loss.

![1561612399647](https://github.com/OmniOne-Blockchain/Bahama_Demo/blob/master/img/datahub.png)
