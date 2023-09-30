# hackathons

<img width="1400" alt="cover2" src="https://github.com/litentry/hackathons/assets/79832732/9fbe2066-35b5-4638-8827-6f72924f12f6">


Join the Litentry Team for the **TrustCraft: Identity Hackathon** events as part of DevConnect in Istanbul, Turkey on November 17, 2023. 


## Themes

Participants can select from the following themes for their hacking projects:

### 1. VC Use Cases
  Create the most innovative and impactful use case of Verifiable Credentials (VCs)! Utilize VCs from IdentityHub in a dApp, in a community, or bring it across ecosystems and blockchains. 
  When crafting new VCs, ensure that the assertions within them are technically on-chain retrievable for your build. While VCs are issued in JSON format, you can integrate it with NFTs or  SBTs to bridge to a wider world.
    
  Requirements: 
  * Utilize VCs created using IdentityHub in a dapp, community or ecosystem. Stay tuned for the upcoming VC SDK and documentation!
  * A prototype dApp would be great, but well-demonstrated ideas and concepts are welcome as well.

### 2. DID Aggregation Use Cases
  Linking different DIDs / accounts can form an [IDGraph](https://docs.litentry.com/parachain/pallets-and-modules/identity-management-pallet-imp/components-of-the-imp#id-graph) that represents users’ comprehensive profiles. It can also act as a gateway to their public on-chain attributes. What identities would you integrate, and how do you use DID aggregation to empower online and real-world applications?
  
  Stay tuned for the upcoming IDGraph documentation.
    
### 3. Identity Assertion Logic and Generation
  The [assertion](https://docs.litentry.com/parachain/pallets-and-modules/verifiable-credential-management-pallet-vcmp/assertion-definitions-and-parameters) building of the current exemplary VCs is hard coded as part of enclave business logic. To ensure its flexibility and extensibility, we are in the transition to a fully programmable logic definition scheme. The basic requirement is to have some logic that the VC requester (normally dApps) can define and the TEE-worker can eventually execute inside the enclave.
  
  The logic should contain at least the following:
  * HTTP get/post from/to the data providers
  * control flow (like different logic based on the result of HTTP response and/or the actual content)
  * post-processing of the data
  * (optional) access to the sidechain/parachain storage
 
  Some options:
  * smart contract language based (`solidity` / `ink!`)
  * wasm
  * external tools or any other suggestions
    
### 4. Parachain/Sidechain Infrastructure Enhancement
  Would you like to go deeper into our architectural labyrinth and help us improve the backbone of our DID solution? You are more than welcome to challenge it, some directions:
  * alternative block production mechanism for sidechain (currently we are using aura)
  * transition to stateless computation (= dismiss the storage of IDGraph), or a hybrid of both (stateful and stateless)
  * better communication between parachain and sidechain, e.g. more efficient syncing, state consistency management, faster message passing …
  * sidechain integration with other parachains and/or EVM chains
  * any critical performance improvement

### 5. Scores & Profiles Design
  Scores are useful identity metrics that offer communities and groups a lens through which to assess, evolve, and thrive. These metrics highlight the aspects that captivate and resonate within a community, providing individuals with a path for personal growth and alignment.
  
  Requirements: 
  * Design Scores or build profiles comprising multiple score elements that showcase the credibility, contributions, and diverse merits of members from a specific community or group.
  * Clearly outline the methodology for calculating each score, describe the meaning and impact of the scores or profiles, and their relevance to the specific community or groups they target.
  * Specify the data prerequisites for each score or profile. You have the flexibility to either provide the required data yourself or collaborate with the Litentry team to access the necessary data sources.

## Registration

👉 Complete this **[Google form](https://docs.google.com/forms/d/e/1FAIpQLScJuoYYIyaoVpIdmTiqxxQMaYXbj9-dYRp0mMCq8W2zyiWyqw/viewform?usp=sf_link)** to register for the hackathon.


## Prizes

* First Prize: **4688 USDT**
* Second Prize: **2688 USDT**
* Third Prize: **1688 USDT**
* Special Prize: **988 USDT**

Prized are in LIT tokens equal to the above-mentioned USDT amount. Teams can choose any of the above project themes, as prizes are not theme-specific.


## Timeline

**Now - Nov 2:** 

Hackers Registration

**Nov 16:** 

14:00 Project Submission Deadline

**Nov 17:** (Istanbul)

14:00 Welcoming

14:30 Workshops by the Parachain Team in Litentry

15:30 Demo Presentation

**Nov 23:**

Winners List Notification


Participants must submit their projects by **Thursday, November 16, at 2 PM**. 

Online participation is accepted, but we encourage the team to be available for on-site presentations. The event can accommodate a maximum of 6 teams, so make sure to register as soon as possible to secure your spot.


## Location

(The event's precise location will be disclosed soon.)


## Communication & Office Hours

- Join our [Discord server](https://www.notion.so/Hackathon-Tweet-1-3c9d59b82081468d821f0e7397960cfa?pvs=21) and DM *seniorpumpkin* to get a `hacker` role.
- We will create a channel under “*Hackathon*” for your project to facilitate project-related discussions. You may find your teammates on Discord, and keep an eye out for upcoming announcements.
- We'll also schedule two **office hour sessions** with core developers from our team to guide you through your project hacking journey. Details will be shared on Discord.


## Start Hacking!

After registration, you may get ready for hacking on your project. To get started:

- Fork this https://github.com/litentry/hackathons/ to your team’s repo.
- Create a folder in 'Projects' with your project's name. In README, add a simple project intro and list the functionalities you plan to complete during the hackathon.
- Submit a PR to set up your project space.


## Project Submission

- Submit a PR to this repository by **Nov 16**, 2023, at **13:00**. You may also include the files or links to your demo video and pitch deck.
- Each entry should provide the below information but not limited to:
    - Project name
    - Problems and solutions, Project introduction
    - Demo
    - Technical architecture
    - Team information
- The winner list will be announced by Nov 23 on Twitter and Discord.

## Judging Metrics

- **Impact**: The project can effectively address the problem it aims to solve, with the potential to bring positive change to the targeted groups.
- **Innovation**: The solution showcases creativity and originality, introducing novel approaches or concepts.
- **Usability/UX**: the project is user-friendly, intuitive and easy to navigate.
- **Technical Complexity**: the team’s work addressed challenging problems, use advanced technologies, or demonstrate technical prowess.
- **Functionality**: the project demo works as intended. It is a functional prototype or a well-implemented solution.

## Links
* [Github](https://github.com/litentry)
* [Documentation](https://docs.litentry.com)
* [Discord](https://discord.gg/litentry)
* [Website](litentry.com)
