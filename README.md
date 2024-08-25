# OpenFlow

![License: AGPLv3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg) 

<p align="center">
  <img src="./assets/openflow-banner.png" alt="OpenFlow: Privacy-Preserving Financial Auditing" width="222"/>
</p>

## Project Overview

Introducing **OpenFlow**, the privacy-preserving solution for transparent transaction auditing. Using zero-knowledge proofs, OpenFlow enables organizations to publicly verify financial transactions while keeping the identities of donors and recipients confidential. Whether you're managing institutional payments, political campaigns, or welfare transactions, OpenFlow ensures transparency without compromising privacy.

## Repository Structure

- **[Front-end Code](https://github.com/yourusername/openflow-frontend)**: This directory contains the source code for the front-end application, including UI components, state management, and API integrations.
- **[Smart Contract Code](https://github.com/yourusername/openflow-contracts)**: This directory includes the smart contract code, written in Solidity, that handles the financial transaction logic and zero-knowledge proof verification.

## How does it work?

OpenFlow uses cutting-edge cryptography to balance transparency and privacy in financial transactions:

1. Organizations setup and initiate an OpenFlow campaign. They determine on which blockchain the transaction certificates will be minted (e.g., Zksync, Avalanche, Polygon) and establish the payment method (e.g., Mercado Pago).
2. Transactions from third-parties that send funds to the organization, or receive funds from it, are registered by openflow backend, which generates a JSON containing the details of the transaction email and zero-knowledge proof that the transaction occured, all while keeping identities of these third-parties private.
3. The JSON associated with each transaction is uploaded via LightHouse to IPFS+FileCoin.
4. The NFTs associated with these JSONs are minted on the blockchain chosen by the institution.
5. The public can access real-time, transparent reports showing that funds have reached their intended destination, ensuring accountability.


## About

**OpenFlow** is an open-source project developed by [Nicolás Biondini](https://github.com/NicolasBiondini), [Yago Pajariño](https://github.com/yagopajarino), [Alejandro Almaraz](https://github.com/almaraz97), [Nicolás Acosta](https://github.com/NicoAcosta) and [Arturo Beccar-Varela](https://github.com/arturoBeccar). With expertise in blockchain, cryptography, and front-end development, we aim to bring trust and privacy to financial transactions.

## Acknowledgements

OpenFlow was initially developed as part of the [Aleph Crecimiento Hackathon, 2024](https://www.aleph.crecimiento.build/en-aleph-hackathon). We participated in this hackathon through the [PSE Core Program](https://pse.dev/en/programs), where we deepened our knowledge of programmable cryptography and zero-knowledge proofs.

In partnership with [D&D Fundacion](https://ddfundacion.org/), we are committed to solving the transparency and privacy problems that prevent help from reaching those who need it.

## License

This project is licensed under the AGPLv3 License - see the [LICENSE](LICENSE) file for details. Contact us if you're looking for an exception to the terms.
