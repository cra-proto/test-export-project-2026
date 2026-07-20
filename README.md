# Test scams project

*description of the project*

**Timeframe** 2026-07-06 - 2026-10-12

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-export-project-2026](https://cra-test-arc.canada.ca/test-export-project-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-07-20

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(MP Kit for CRA-related scams and fraud)
    node4(Scams and fraud - CRA)
    node5(Scams and fraud – CRA - Recognize a scam)
    node6(Scams and fraud - CRA - Report a scam or identity theft)
    node7(Scams and fraud - Government of Canada)
    node8(CRA Multimedia library)
    node9(Videos about the underground economy)
    node10(When nobody cheats, everybody wins)
    node11(CRA Newsroom)
    node12(The Canada Revenue Agency is resuming additional activities: know when we’re contacting you and how to avoid scams)
    node13(Don't get scammed!)
    node14(How to verify the CRA has contacted you)
    node15(How to verify the CRA has contacted you)
    node16(Not sure if it's the CRA calling? Here's how to find out!)
    node17(Sign in to your CRA account)
    node18(Help with using your CRA account)
    node19(CRA account help - Keep your CRA account secure)
    node20(Important Security Information)
    node21(Forms and publications - CRA)
    node22(Canada Revenue Agency forms listed by number)
    node23(RC213 Identity theft and suspicious activity declaration form for individual, business and trust)
    node24(L300 Cannabis Licence Application under the Excise Act, 2001)
    node25(L300SCHA Schedule A - Other Business Location#40;s#41; #40;to support a cannabis licence application#41;)
    node26(Canada Revenue Agency publications listed by number)
    node27(EDN52 CANCELLED Obtaining and Renewing a Cannabis Licence)
    node28(The Government of Canada cracks down on tax cheating in real estate transactions)
    node29(Payments – CRA)
    node30(Payments to the CRA)
    node31(Make a payment – Payments to the CRA)
    node32(Taxes)
    node33(Charities and giving)
    node34(Give to a registered charity or another type of qualified donee)
    node35(Avoid donation-related scams)
    node36(Report suspected donation-related scams or other non-compliance)
    node37(Excise and specialty taxes)
    node38(Cannabis duty)
    node39(Apply for a cannabis licence from the CRA)
    node40(Eligibility conditions)
    node41(How to apply)
    node42(Who should apply)
    node43(Excise duties technical information)
    node44(Excise duty memoranda)
    node45(EDM6-2 Obtaining and renewing a cannabis licence)
    node1 --x node2
    node2 --> node3
    node2 --> node4
    node4 --> node5
    node4 --> node6
    node4 --x node7
    node2 --x node8
    node8 --x node9
    node9 --> node10
    node2 --> node11
    node11 --x node12
    node11 --x node13
    node11 --x node14
    node11 --x node15
    node11 --x node16
    node2 --> node17
    node17 --> node18
    node18 --> node19
    node17 --x node20
    node2 --> node21
    node21 --> node22
    node22 --> node23
    node22 --> node24
    node22 --> node25
    node21 --> node26
    node26 --> node27
    node2 --x node28
    node2 --> node29
    node29 --> node30
    node30 --> node31
    node1 --> node32
    node32 --> node33
    node33 --> node34
    node34 --> node35
    node34 --> node36
    node32 --> node37
    node37 --x node38
    node38 --> node39
    node39 --> node40
    node39 --> node41
    node39 --> node42
    node37 --> node43
    node43 --> node44
    node44 --> node45

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node10,node11,node12,node13,node14,node15,node16,node19,node20,node23,node24,node25,node27,node28,node31,node35,node36,node40,node41,node42,node45 inscope
    classDef ismoved fill:#eab308,color:#000
    class node7 ismoved
```
