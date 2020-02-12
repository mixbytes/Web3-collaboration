# DOT Wallet
## (Polkadot multisig wallet)

## Project Description

For now, there is no universal multisig cross-platform wallet with native integration in the Polkadot ecosystem, and the majority of existing multi-chain solutions support only basic transfers. Users often have to switch devices and use different solutions to satisfy their needs. 

Moreover, teams and companies are facing difficulties while managing funds and making decisions as current systems (DAOs, foundations) complicate the process.

We plan to implement **a fully-featured wallet with multisig support** for Polkadot and Substrate-based chains (including Polkadot parachains) with a set of components required for end-users. We will deliver a complete ready-to-use product instead of a simple set of modules, libraries and code. 

The solution will be **universal** (compatible with all Substrate-based blockchains/parachains), **cross-platform**(WEB, CLI, mobile) and **secure**(less likelihood of funds hacking), thus lift the above-mentioned restrictions. 

**Key wallet benefits are:**

*   native integration (support of Polkadot-specific features: governance, dApps,etc.)
*   user-friendly interface, multisig accounts and transactions support
*   integration with different key storage types: Parity Signer, Hardware Wallets, internal autonomous secure storage
*   higher level of security (fully on-chain work with transactions and balances, no centralized processing)
*   easier internal decision-making process

**Target audience:**

*   Early Polkadot adopters & DOT holders
*   Teams, DAOs, foundations seeking to use secure fund management solutions
*   Polkadot parachain and Dapp users


## Team members

*   Vadim Buyanov (Product Owner)
*   Alexey Makeev (CTO, Architect)
*   Ioann Tchaikovskiy (UI/UX designer)
*   Algys Ievlev (Fullstack Developer)
*   Mikhail Gorbachev (Rust Developer)
*   Sergey Karapetyan (Mobile Developer)
*   Sergey Govyazin (Frontend/Mobile Developer)
*   Sabaun Taraki (QA Engineer)


## Team Website

*   [https://mixbytes.io](https://mixbytes.io/)


## Legal Structure

Russian LLC


## Team's experience

*   **Vadim Buyanov**: 5+ years of product design and strategic promotion, business development and marketing campaigns, account management.
*   **Alexey Makeyev**: 3 years of blockchain experience, 1 year of Polkadot development experience. Experience in architecting and developing a blockchain finality gadget and smart contract systems. 7+ years of expertise in the Internet search engine project (5  as a Team Lead). 
*   **Ioann Tchaikovskiy**: 10+ years of design, art direction and digital art experience. He creates and uses mobile application interfaces, designs custom product interaction scenarios, generates design solutions and graphic design elements that enhance usability layout.
*   **Algys Ievlev**: 2 years of blockchain experience, 1 year of Polkadot expertise. Good knowledge of designing and developing consensus algorithms, smart contracts and high-load web services. 
*   **Mikhail Gorbachev**: 3 years of blockchain experience, 6 months of Polkadot experience. 4 years of C++\Rust development in system programming. Previously was engaged into fintech and dynamic disassembling.
*   **Sergey Karapetyan**: 10+ years experience in mobile app architecture and development in React Native. Deep understanding of native component implementation, application profiling and optimization, writing tests, integration with corporate systems.
*   **Sergey Govyazin**: 1 year of Frontend experience (React.js + node.js), 1 year of native Android experience, 1 year of blockchain experience, 1 year of Polkadot experience. Deep understanding of JS-development, good knowledge of Mobile development (including cross-platforms, e.g. Flutter)
*   **Sabaun Taraki**: 1 year of experience in testing,  developing and auditing big smart contract systems. Experience in web development (1 year) and telegram bots development.


## Team Code Repos

*   [https://github.com/mixbytes](https://github.com/mixbytes)
*   [Substrate module multisig](https://github.com/mixbytes/substrate-module-multisig)


## Team LinkedIn Profiles

*   [Vadim Buyanov](https://www.linkedin.com/in/vadim-buyanov/)
*   [Alexey Makeyev](https://www.linkedin.com/in/aleksey-makeyev-98471884/)
*   [Algys Ievlev](https://www.linkedin.com/in/algys/)
*   [Mikhail Gorbachev](https://www.linkedin.com/in/sadsnake/)


## Intended language of development

*   Rust
*   Javascript
*   Flutter/React Native


## Development Roadmap

### Milestone 1 (13 weeks) 

*   Project architecture 
*   CLI wallet (Mac/Linux) with a set of basic features:
*   Managing accounts: add-remove
*   Managing balances: transfers, balance check
*   Managing networks: switching between parachains
*   Sending arbitrary transactions
*   Creating multisig accounts
*   Managing multisig transactions: create, approve, cancel
*   Basic WEB interface demo of the above-mentioned features and effectiveness of the Vault and WEB interface.
*   Client (native) app for Mac/Windows/Linux for storing keys and signing transactions. The app will be installed in the client system and used by the above-mentioned wallets.
*   QA

#### **Deliverables:** CLI app and autonomous vault MVPs, WEB interface demo


### Milestone 2 (11 weeks) 

*   Graphic design
*   Mobile version for Android/iOS
*   WEB version for browsers
*   CustDev (getting feedback), partnership with Polkadot ecosystem projects, first users acquisition (DOT holders)
*   QA

#### **Deliverables:** Mobile and WEB wallet version, first user base and feedback


### Milestone 3 (10 weeks) 

*   Integration with external wallets
    *   with [Parity Signer](https://www.parity.io/signer/) for tx signing 
    *   hardware wallets for tx signing
*   Notification service for WEB/Mobile versions:
*   Notifications about new transactions to be signed by a user account
*   Subscription to account balance changes, including account multisig 
*   API for wallet integration with external dApps
*   CustDev (getting feedback), partnership with Polkadot ecosystem projects, first users acquisition (DOT holders).

#### **Deliverables:** External wallets integration & notifications & dApps integration API, user base acquisition and feedback


## Additional info

### Business plan

We plan to fulfill the above-mentioned 3 milestones and deliver the first wallet version, as well as carry out basic CustDev activities to attract first users in the course of a Seed round.

Planned resources for higher user acquisition (first wallet version): 
*   Integration with Polkadot parachains and bridge-chains, with Substrate-based projects and their communities
*   Polkadot dApps&DAO projects listing      

We plan further product development (extra features, higher user acquisition and monetization, i.e. business development) in terms of further investment rounds and due to development и business development teams growth. 

Additional monetization means (including new features): 
*   DEX support, tx commission + liquidity pool
*   Partnerships with exchanges and transfer commissions 
*   Сompatibility with the chains outside Polkadot ecosystem
*   Crosschain asset exchange
*   Staking services
*   Outgoing payment processing settings

### Out of scope activities

MixBytes team has a solid infosec and blockchain auditing experience. That said, we aspire to deliver a highly secure solution using best practices. However, we recommend third party auditing upon project completion. 


### What work has been done so far?

*   [Substrate module multisig](https://github.com/mixbytes/substrate-module-multisig)


### Have you applied for other grants so far?

*   [DPOS_Oracle.md](https://github.com/mixbytes/Web3-collaboration/blob/master/grants/speculative/DPOS_Oracle.md)
*   [MixBytes_Tank.md](https://github.com/w3f/Web3-collaboration/blob/master/grants/speculative/MixBytes_Tank.md)
*   C++ PRE implementation


### Are there any other projects similar to yours?

We have researched the existing solutions and based our conclusions on the following comparative analysis:

<table>
  <tr>
   <td rowspan="2" ><strong>Solution</strong>
   </td>
   <td colspan="4" align="center"><strong>Features</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Cross-platform</strong>
   </td>
   <td><strong>Multisig</strong>
   </td>
   <td><strong>Native integration</strong>
   </td>
   <td><strong>Compatible</strong>
   </td>
  </tr>
  <tr>
   <td>DOT Wallet
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://polkawallet.io/">Polkawallet</a>
   </td>
   <td>Mobile only
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://atomicwallet.io/polkadot-wallet">AtomicWallet</a>
   </td>
   <td>Yes
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://polkadot.js.org">https://polkadot.js.org</a>
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/paritytech/substrate-light-ui">Substrate Light UI</a>
   </td>
   <td>CLI only
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://lunie.io/">Lunie</a>
   </td>
   <td>Yes
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://www.mathwallet.org/en/">MathWallet</a>
   </td>
   <td>Yes
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/blockxlabs/enzyme">Enzyme</a>
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://cobo.com/">Cobo Wallet</a>
   </td>
   <td>Mobile only
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://bepal.pro">BEPAL Wallet </a>
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://token.im/?locale=en-US">imToken</a>
   </td>
   <td>Mobile only
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
</table>