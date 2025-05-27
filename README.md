
# What is Keycard?

Keycard is an implementation of a BIP-32 HD wallet running on Javacard 3.0.4+ (see implementation notes)

It supports among others
- key generation, derivation and signing
- exporting keys defined in the context of EIP-1581 https://eips.ethereum.org/EIPS/eip-1581
- setting up a NFC NDEF tag

Communication with the Keycard happens through a simple APDU interface, together with a Secure Channel guaranteeing confidentiality, authentication and integrity of all commands. It supports both NFC and ISO7816 physical interfaces, meaning that it is compatible with any Android phone equipped with NFC, and all USB Smartcard readers.

The most obvious case for integration of Keycard is crypto wallets (ETH, BTC, etc), however it can be used in other systems where a BIP-32 key tree is used and/or you perform authentication/identification.

# Where to start?

A good place to start is our [documentation site](https://keycard.tech/docs/)

Keycard is a public good — contributions are welcome and highly encouraged!

You can also join the discussion about this project on our [discord channel](https://discord.gg/uJAXk7jFhZ)

Keycard is at the center of several projects, check the [ecosystem of projects](https://github.com/keycard-tech/keycard-ecosystem-projects/) or [good first issues](https://github.com/orgs/keycard-tech/projects/1/views/2?filterQuery=good+first+issue)

Should you wish to work on an issue, please claim it first by commenting on the GitHub issue that you want to work on it. This is to prevent duplicated efforts from contributors on the same issue. 

If you just want to use the Keycard as your hardware wallet there are currently three apps supporting it

1. Status [[Android](https://play.google.com/store/apps/details?id=im.status.ethereum)][[iOS](https://apps.apple.com/us/app/status-private-communication/id1178893006)]
2. WallETH [[Android](https://play.google.com/store/apps/details?id=org.walleth)]
3. Enno Walet https://ennowallet.com/
