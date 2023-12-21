# Overview

# Identity Lifecycle

## Provision

In the provisioning phase, the user's first step is to establish a (secure) connection with the issuer, by reading a QR code.

<img src="../imgs/wallets/esatus/1-esatus-page-create-a-connection.png">

The app installed on the user's device will show a notification asking to accept the connection.

<img src="../imgs/wallets/esatus/1.1-esatus-wallet-read-connection.png" height="600">

Once the user accepts the connection, she can receive a verifiable credential (VC) offer from that issuer.

<img src="../imgs/wallets/esatus/1.2-esatus-wallet-connection-accepted.png" height="600">

In the second step, the user clicks the *Create Credential* button. 

<img src="../imgs/wallets/esatus/2-esatus-create-credential.png">


As there exists a direct link between the issuer and the user, the VC is transmitted to the user via this connection. Subsequently, a notification appears for the user, prompting them to accept the offer.

<img src="../imgs/wallets/esatus/2.1-esatus-wallet-view-offer.png" height="600">

The user can view the VC offer and accept it.

<img src="../imgs/wallets/esatus/2.2-esatus-wallet-view-details.png" height="600">

Upon user acceptance, the VC is stored in the user's wallet.

<img src="../imgs/wallets/esatus/2.3-esatus-wallet-credential-stored.png" height="600">


The wallet provides users with the choice to enable automatic acceptance of VCs from that specific issuer.

<img src="../imgs/wallets/esatus/2.4-esatus-wallet-automatic-acceptance.png" height="600">

### Privacy considerations

1. The wallet application requires a PIN to be entered for access and can also be set up to utilise the device's biometric unlocking feature.
2. The use of the terminology *Create a connection* and *Connection* is more user-friendly than DID (decentralised identifier) connection.
3. The choice for automatic acceptance of VC offers requires a more thorough analysis to understand its potential effects on user control and transparency.

## Usage, Update and Maintainance

## De-provision


# Final Remarks
