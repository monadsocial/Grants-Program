# Mintbase Grant Proposal

- **Project Name:** Monad Mintbase NFT  Gated Ticketing, Creator & Fan Tools
- **Team Name:** Monad.Social
- **Payment Address:** monadsocial.near
- **[Level](../README.md#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

- Monad.Social is a sophisticated subscription-based live performance streaming experience with web3 and other features for creators and users to enhance the experience.
- Monad.Social allows for creators manage and monetize their own fanbase and offer a number of benefits for that fanbase, from a variety of functional NFTs to Live Streaming performance, sophisticated chat and feeds, badging, community recognition and much more.
- We have implemented a basic NFT system for POAPs, as rewards, as a tipping benefit and we have more ideas for these as well as needing to scale, make creation easier, and a number of other improvements to the NFT system and its overall integration into our experience. A core part of our goal is to make these technologies have value for the average "fan", make it very easy to engage with and use, and drive greater creator/fan engagement and satisfaction (leading to continiued subscription)
- Monad already received and completed a $75k NEAR Grant to build out all the necessary infrastructure and to launch the World's First "dance to earn app" we call the Virtual Dance Floor. We use the gyro and acclerometer in mobile devices to translate dancing movements into pulsing avatars that earn Monad Tokens. Phase II of this roadmap is integrate Mintbase in order to expand and improve the UX for both the Creators and Fans. We will implement the ability of Artist/Creators to directly upload their NFT art that will be used for sale of NFTs that purchased by fans as tips for music performance and POAPs.
- In addition we want all these NFTs to be searchable and discoverable by regular web search. We will also impelment the ability for Fans earning Monad Tokens via the Virtual Dance Floor, and other user behaviours, to be able to spend these Monad Tokens to purchase NFTs.
- The goal here is to create an economic ecosystem here that drivers customer acquitistion and retention behaviour for the masses - not to create speculative assets.
- In order to accomplish this, we need to make the UX, especially for Creators, as simple and intuitive as possible. In our discussions wiht Mintbase executives (Paul Kuveke and Nate Geieir), we believe in aggregate your solutions are the best option for us to achieve these goals.

### Project Details

- Mockups/designs of any UI components
  - We have a complete, fully functioning MVP with customers and generating revenue now. The UI/UX for users both on the front-end side and for Creators to upload art is already completed and live. We can provide access to any Mintbase people since the content is behind a paywall.
  - Fan UX, Purchase of NFTs as tips, POAPs - https://monad.social/circle/djsneak/
  - POAP Upload UI: https://monad.social/circle/djsneak/admin/nfts/
  - NFTs for tipping: https://monad.social/circle/djsneak/admin/tipnfts/
  - Data models / API specifications of the core functionality
    
- An overview of the technology stack to be used
  - Smart Contracts: Rust, NEAR SDK, Mintbase API
  - Front End: React, HTML, CSS, JavaScript
  - Back End: We are Google Cloupd for Startups Partner so all infrastrucutre on GCP with a WordPress MySQL DB.

### Ecosystem Fit

- Where and how does your project fit into the ecosystem?
  - We've discussed our goals with Nate and Paul and identified a plethora of both "now" integrations that can be used plus "coming soon" features that sync very well with our business goals.
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  - We have 2 target audiences - Creators and their Fans. We are working with one of the 3 Major Record labels amd other artists to help them migrate their 30 million YouTube subscribers to Monad.
- What need(s) does your project meet?
  - We need to create simple, elegant solutions to lower the barriers for Creators to supply art that can be monetized through tokenization and digital asset sales.  Then to in turn create entertaining Fan Experiences that will encourage usage and therefore be an excellent customer retention tool. 
- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
  - Sweatcoin has done something similar of course with the "exercise to earn" aspect of what we're doing. We are unaware of other Web3 versions of Twitch for Music which is what we are buidling out.

## Team :busts_in_silhouette:

### Team members

- Brett Hawkins - CEO
- Greg Johnson - Chief Digital Strategist
- Jiandon Wei - CTO
- Anvar Bagiyev - Lead Designer/UI/UX

### Contact

- **Contact Name:** Brett Hawkins
- **Contact Email:** Brett@monad.social
- **Website:** https://monad.social/

### Legal Structure

- **Registered Address:** 920 California Ave., Suite 3, Venice, CA 90291
- **Registered Legal Entity:** Monad.Social PBC

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Mintbase previously, please list the name of the project and legal entity here.

### Team Code Repos

- https://github.com/<your_organisation>
- https://github.com/<your_organisation>/<project_1>
- https://github.com/<your_organisation>/<project_2>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/<team_member_1>
- https://github.com/<team_member_2>

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/<person_1>
- https://www.linkedin.com/<person_2>

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/mintbase/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Mintbase Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Mintbase. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in USN, and potentially NEAR and nUSDC, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Implement Mintbase Modules

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Mintbase nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Mintbase module: X | We will create a Mintbase / NEAR module that will... (Please list the functionality that will be implemented for the first milestone) |  
| 2. | Mintbase module: Y | We will create a Mintbase / NEAR module that will... |  
| 3. | Mintbase module: Z | We will create a Mintbase / NEAR module that will... |  
| 4. | NEAR chain integration | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1
- **Costs:** 4,000 USD

...
## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Mintbase Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
