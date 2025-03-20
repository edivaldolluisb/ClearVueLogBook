[Back to main Logbook Page](../hci_logbook.md)

---

# B. Stage 1 - Context Definition

# B.1. Competitor Identification

>     The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis

## B.1a. Competitors

| **Competitor** | **Description**          | Information repository                                                            |
| -------------- | ------------------------ | --------------------------------------------------------------------------------- |
| Opticalia      | Online eyewears platform | [Opticalia_evaluation_workbook](competitors/Competitor%20Analysis%20Opticalia.md) |
| Multioticas    | Online eyewears platform | [Opticalia_evaluation_workbook](competitors/Competitor%20Analysis%20Opticalia.md) |

## B.1b. Detailed Competitor Analysis

>     Choose the most notable competitor and do a more thorough analysis of their interactive solution

### - Heuristic Evaluation

Me and my mate we've selected Opticalia as our main competitor, And we have used Nielsen Norman Method.

#### Method

[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]

We conducted a heuristic evaluation following the Nielsen Norman Method. The process involved:

-   Procedure: Each evaluator independently analyzed the Opticalia platform.

-   Number of Experts: 2 experts.

-   Heuristics Used: Nielsen’s 10 Usability Heuristics.

-   Severity Scale: We assigned severity scores from 0 (no issue) to 4 (usability catastrophe).

-   Consensus: After individual assessments, a meeting was held to discuss and agree on the severity of issues.

#### Individual Evaluations

<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->

-   [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_Opticalia.md)

-   [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_Opticalia.md)

<!-- - [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md) -->

#### Consensus

>     After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                         | **Expert 1** | Expert 2 | Recommendations                                 |
| --------------------------------- | ------------ | -------- | ----------------------------------------------- |
| Confusing navigation structure    | 3            | 1        | Improve menu clarity and add a site map.        |
| Lack of feedback on button clicks | 2            | 3        | Use visual and audio cues for user interaction. |
| Complex checkout process          | 4            |          | Simplify steps and add progress indicators.     |

---

### - Cognitive Walkthrough

#### Method

[Briefly described the method you used for the Cognitive Walkthrough analysis. ]
The cognitive walkthrough focused on evaluating how a first-time user would interact with Opticalia’s platform. We analyzed the ease of learning and completing common tasks.

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

| Task                            | Subtasks                            |
| ------------------------------- | ----------------------------------- |
| **1. Buying a pair of glasses** | Search for available models         |
|                                 | Filter by price and brand           |
|                                 | Select a pair of glasses            |
|                                 | Add to cart and proceed to checkout |

<!-- | Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        | -->

#### Results

Task: [This is the task]

| Step # | Task/Action to Perform  | Will User Know What to do at this step? (Yes/No) | Notes               | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                  | Is Action Successful? (Yes/No) | Suggestions for Improvement  |     |
| ------ | ----------------------- | ------------------------------------------------ | ------------------- | ----------------------------------------------------------------------------------------- | ---------------------- | ------------------------------ | ---------------------------- | --- |
| 1      | Search for glasses      | Yes                                              |                     | Yes                                                                                       |                        | Yes                            | Improve search filtering     |     |
| 2      | Select a specific model | Yes                                              |                     | Yes                                                                                       |                        | Yes                            | Display more product details |     |
| 3      | Add to cart             | Yes                                              |                     | Yes                                                                                       |                        | Yes                            | Highlight added items        |     |
| 4      | Checkout process        | No                                               | Confusing interface | No                                                                                        | Users may abandon cart | No                             | Streamline checkout          |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

Main Findings:

-   Opticalia has a well-structured product catalog but struggles with usability in checkout.

-   Users often experience frustration due to unclear navigation.

-   Improvements in feedback mechanisms could enhance the user experience.

HCI SWOT Analysis (Opticalia)

| Strengths                               | Weaknesses                                   |
| --------------------------------------- | -------------------------------------------- |
| Strong product catalog                  | Confusing navigation                         |
| Clear product images and details        | Lack of interactive feedback                 |
| Established brand recognition           | Checkout process is too complex              |
| Opportunities                           | Threats                                      |
| Improve user experience to gain an edge | Competitors have more intuitive interfaces   |
| Integrate AI recommendations            | Users may switch to more user-friendly sites |
| Optimize for mobile experience          | High cart abandonment rates                  |

---

# B.2. Users

>     For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...

## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]

We conducted structured interviews with users who have experience purchasing eyewear online. Our goal was to identify:

-   How users search for eyewear online.

-   Common challenges they face.

-   Features they would like to see improved.

**Interview Questions:**

1. Have you purchased eyewear online before? If so, what platform did you use?

2. What was the most difficult part of the process?

3. How did you choose the right glasses for you?

4. Were there any features you found helpful or lacking?

## B.2b. Results

>     This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session.

### Interview List

| Date       | Participant / Role | Key Insights                                          | Link to Notes                |     |
| ---------- | ------------------ | ----------------------------------------------------- | ---------------------------- | --- |
| 04-03-2025 | student            | Found product filtering useful but checkout confusing | [📄 Notes](interview-Bob.md) |     |
| 04-03-2025 | student            | Wanted better virtual try-on options                  | [📄 Notes](interview-Bob.md) |     |
| 04-03-2025 | student            | Struggled with unclear return policies                | [📄 Notes](interview-Bob.md) |     |
| 04-03-2025 | Bob / student      | Hard to keep/save the recipes                         | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                       |                              |     |

### Common Themes & Patterns

-   **Recurring Problems:**
    -   Checkout process is too complicated.
    -   Lack of clarity on return policies.
    -   Users want more product customization options.
-   **Frequently Used Tools:**
    -   Virtual try-on features.
    -   Product filtering by brand and price.
    -   Prescription upload and management.
    -   Wishlist and favorites.
-   **Desired Features / Solutions:**
    -   Simplified checkout process.
    -   Clearer return policy information.
    -   More customization options.   

---

---

[Back to main Logbook Page](../hci_logbook.md)

---
