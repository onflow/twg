## Welcome to the Flow Tokenomics Working Group (TWG)

### Introduction

Flow — the decentralized, public, layer-one blockchain designed for building Web3 experiences for mainstream users — is launching a Technical Working Group (TWG) to focus on enhancing FLOW token economics. The working group will be responsible for researching, discussing, and implementing improvements to the economic design of Flow's native token, FLOW, and its use-cases, with a focus on driving network security, decentralization and FLOW’s value proposition. The group will be open to experts in blockchain, economics, mathematics, game theory, data analytics, marketing, and related fields, who will work closely with the community to ensure that decisions are data-driven, technically sound, and aligned with the goals of the Flow community.


# Repository template
A template enabled repository, including all necesary files to open source.
(create an issue with the following content if you want to track the repo configuration)

## Repository settings and configuration
- [ ]  Repository info
    - [ ]  Add repo description
    - [ ]  Update website to https://onflow.org
    - [ ]  Add relevant repository topics (i.e. `blockchain` `onflow`, etc)
    - [ ]  Check issue labels on `.github/labels.yml` and do any commit to main to get them synced
- [ ]  Define merge workflow (create new branch protection rule)
    - [ ]  `main` branch rule:
        - [ ]  **Require pull request reviews before merging (2 approving reviews)**
            - [ ]  **Require review from Code Owners**
        - [ ]  **Require status checks to pass before merging**
            - [ ]  **Require branches to be up to date before merging**
        - [ ]  **Require linear history**
        - [ ]   **Restrict who can push to matching branches**
            - [ ]  Choose `onflow/flow` team

- [ ]  Add necessary team members, adjust access levels
    - [ ]  `onflow/flow-admin` ⇒ Admin access
    - [ ]  `onflow/flow-engineering ` ⇒ Write access
