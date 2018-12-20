---
slideOptions:
  transition: slide
---

Ethereum Improvement Proposal Process
=========================================

<!-- 
  This presentation was adapted from: https://github.com/jpitts/howto-eip-presentation

  Please feel free to adapt and expand it under a CC0 License.
-->

---

Boris Mann
----------

* Community & Operations, [SPADEco](https://spade.builders)
* Volunteer Organizer for [EthMagicians](https://ethereum-magicians.org)
* Check out [FISSION Codes](https://fission.codes) - ERC1066 & ERC1044


---

EIP Resources
-------------

* List of EIPs that made it to draft   [https://eips.ethereum.org/](https://eips.ethereum.org/)

* EIP-1: Purpose and Guidelines  [https://eips.ethereum.org/EIPS/eip-1](https://eips.ethereum.org/EIPS/eip-1)

---

What are EIPs?
--------------

> "Ethereum Improvement Proposals describe standards for the Ethereum platform, including core protocol specs, client APIs, and contract standards."

---

What are ERCs?
--------------

> "ERCs are a type of EIP which describe application-level standards and conventions, including contract standards."

---

ERC-20 Token Standard
---------------------

![](https://s3-ca-central-1.amazonaws.com/images.spade.builders/uploads/upload_028ea5c94e9611f84358351e2fd972ae.png)

Superseded -- but not widely adopted yet -- by ERC223 and ERC777.

---

Selected ERCs
-------------

* [ERC 721 Non-Fungible Tokens](https://github.com/ethereum/EIPs/issues/721)
* ERC 1066 [FISSION Codes](https://fission.codes) + 1444 FISSION Translate
* [ERC 1337 Subscriptions](https://github.com/ethereum/EIPs/issues/1337)
* [ERC 1400 Security Token](https://github.com/ethereum/EIPs/issues/1411)


---

What drives the EIP process?
----------------------------

* The process exists to create high quality proposals, accepted by consensus of the community
* For quality, we seek competent input
* For acceptance, we seek buy-in from stakeholders

---

EIP Process is run through Github
---------------------------------

> Because the EIPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

[github.com/ethereum/EIPs](https://github.com/ethereum/EIPs)

---

EIP-1: The EIP Work
-------------------

* Needs-finding, defining requirements, engineering, prototyping
* Write the EIP using the style and format described
* Shepherd the discussions in the appropriate forums
* Build community consensus around the idea

---

EIP Editor Responsibilities
---------------------------

* Read the EIP to check if it is ready
* Check the EIP for language
* Assign an EIP number
* Merge the corresponding pull request

> "The editors don't pass judgment on EIPs. We merely do the administrative & editorial part."

---

EIP Editors
-----------

The current EIP editors are:

* Nick Johnson (@arachnid)  
* Casey Detrio (@cdetrio)  
* Hudson Jameson (@Souptacular)  
* Vitalik Buterin (@vbuterin)  
* Nick Savers (@nicksavers)  
* Martin Becze (@wanderer)

---

EIP-1: Types of EIPs (1)
------------------------

*   **Standard Track EIPs**

    *   **Core** - improvements requiring a consensus fork
    *   **Networking** - devp2p, LES
    *   **Interface** - client API/RPC specifications
    *   **ERC** - app-level standards and conventions

---

EIP-1: Types of EIPs (2)
------------------------

*   **Informational EIPs** - general guidelines or information
*   **Meta EIPs** - includes decision-making surrounding Ethereum

---

Focusing on Core EIPs
---------------------

---

Who is involved in Core EIPs?
-----------------------------

*   You, the champion or EIP author
*   EIP editors
*   Ethereum Core Developers
*   _Are there other important stakeholders?_

----

Workflow of a successful Core EIP
---------------------------------

Initial Submission

*   Fork the repo in GitHub.
*   Add your EIP to your fork. Use the EIP template.
*   Submit a Pull Request & Status Change to the repo.

----

Steps Toward Final
------------------
  
WIP -> DRAFT -> LAST CALL -> ACCEPTED -> FINAL

----

Core EIP Workflows: Work In Process
-----------------------------------

**WIP** -> DRAFT -> LAST CALL -> ACCEPTED -> FINAL

* * *

*   Champion creates a WIP EIP as a pull request
*   Each status change is requested by the EIP author and reviewed by the EIP editors

----

Core EIP Workflows: Draft
-------------------------

WIP -> **DRAFT** -> LAST CALL -> ACCEPTED -> FINAL

* * *

Champion seeks support, creates a draft EIP as a pull request.

----

Core EIP Workflows: Draft (SUCCESS)
-----------------------------

If agreeable, EIP editor will assign the EIP a number

----

Core EIP Workflows: Draft (FAIL)
-----------------------------

*   unfocused, broad, duplication of effort
*   technically unsound
*   not addressing backwards compatibility
*   not in keeping with the Ethereum philosophy _(huh?)_

----

Core EIP Workflows: Last Call
-----------------------------

WIP -> DRAFT -> **LAST CALL** -> ACCEPTED -> FINAL

* * *

Champion creates a Last Call EIP as a pull request  
Notifies key stakeholders, etc.

----

Core EIP Workflows: Last Call (SUCCESS)
---------------------------------------
 
*   IF agreeable, the EIP editor sets a review end date

----

Core EIP Workflows: Last Call (FAIL)
------------------------------------

FAIL  
 
*   material changes are still expected to be made to the draft

FAIL++  
 
*   material changes or substantial unaddressed technical complaints will cause the EIP to revert to Draft! 

----

Core EIP Workflows: Accepted
----------------------------

WIP -> DRAFT -> LAST CALL -> **ACCEPTED** -> FINAL

* * *

* this is now in the hands of the client developers.
* developer decisions to implement is NOT part of the EIP process!

----

Workflows: Final
----------------

WIP -> DRAFT -> LAST CALL -> ACCEPTED -> **FINAL**


* a Last Call without material changes or unaddressed technical complaints will become Final
* Core EIPs must be implemented in at least three viable Ethereum clients
* when the implementation is complete and adopted by the community, the status will be changed to Final

----

Scheduling for Hardfork
-----------------------

* Hardfork inclusion and scheduling is also out of scope of the EIP process

* Some areas (e.g. JSON-RPC) don't necessarily trigger hard fork

* Ethereum is moving to have hardforks more often (3 - 6 months)

---

Format of EIPs
--------------

EIPs are written in markdown format.  
Each EIP should have the following parts:

Preamble  
Simple Summary  
Abstract  
Motivation  
Specification

Rationale  
Backwards Compatibility  
Test Cases  
Implementations  
Copyright Waiver

---

Specifications & Standards for Ethereum 1
-----------------------------------------

* Formal Specification for Ethereum / EVM https://github.com/ethereum/yellowpaper, complimented by the Jello Paper https://jellopaper.org/
* DevP2P https://github.com/ethereum/devp2p/
* JSON-RPC https://github.com/ethereum/wiki/wiki/JSON-RPC

---

Extended Ethereum Protocols
---------------------------

* Light Ethereum Subprotocol https://github.com/ethereum/wiki/wiki/Light-client-protocol
* Whisper https://github.com/ethereum/go-ethereum/wiki/Whisper-Overview
* Swarm https://github.com/ethereum/go-ethereum/pull/2959

---

Ethereum 2
----------

* ETH2 Specifications Repo https://github.com/ethereum/eth2.0-specs

---

Starting a Proposal
---------------------------------------

Start a discussion on [ethresear.ch](https://ethresear.ch/) or [ethereum-magicians.org](https://ethereum-magicians.org)

![](https://s3-ca-central-1.amazonaws.com/images.spade.builders/uploads/upload_13b503fd73c6c99d5341e3aed7e6b450.png)

---

## Fin

Slides adapted from Jamie Pitts [how-to-eip](https://github.com/jpitts/howto-eip-presentation)

Contact Boris [boris@spade.builders](mailto:boris@spade.builders)
* Twitter / Github [@bmann](https://twitter.com/bmann)

----

## EEA Presentation

Presented 2018/12/20
* Link to JSON-RPC repo
* All EVM
* Previously outstanding question re: patent assignment
