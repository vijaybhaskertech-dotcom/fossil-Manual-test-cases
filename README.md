# ⌚ Fossil India E-Commerce - Manual Test Cases & User Stories

**Target Application:** [Fossil India](https://www.fossil.in/)  
**Azure DevOps Project:** AIDHIKA (`vijay0424`)  
**Work Item ID:** 442  
**Repository Content:** Comprehensive Agile User Stories, Acceptance Criteria (Gherkin format), and 10 End-to-End Manual Test Cases.

---

## 📂 Repository Contents

| File Name | Description | Format |
| :--- | :--- | :--- |
| **`USER_STORY_AND_TEST_CASES.md`** | Complete specification for Work Item #442, Agile User Story, 8 Acceptance Criteria, and 10 detailed test cases with steps and expected results. | Markdown / Documentation |
| **`TEST_CASES.csv`** | Azure DevOps compatible CSV export of all test cases and user stories. Can be imported directly into Azure DevOps Boards or opened in Microsoft Excel. | CSV / Spreadsheet |

---

## 🌟 User Story Overview

### **US-442: E-Commerce Product Search, Price Verification, Add to Bag & Checkout Summary Calculation Workflow**
> **As an** Online Shopper on Fossil India (`fossil.in`),  
> **I want to** navigate the store, search for specific watches, inspect verified product pricing, add items to my shopping bag, and review the checkout order summary calculations,  
> **So that** I can smoothly purchase my desired product with accurate pricing, transparent taxes/shipping, and reliable item tracking.

---

## 🧪 Test Cases Summary

1. **TC_442_01:** Verify dynamic browser launch and homepage navigation (Smoke / P1)
2. **TC_442_02:** Verify Account Login navigation and form element visibility (Functional / P1)
3. **TC_442_03:** Verify invalid user credentials trigger validation feedback (Negative / P2)
4. **TC_442_04:** Verify Product Search with keyword returns matching results (Functional / P1)
5. **TC_442_05:** Verify Product Listing Page displays products with valid prices (Functional / P1)
6. **TC_442_06:** Verify navigating from PLP to PDP maintains title and price (Functional / E2E / P1)
7. **TC_442_07:** Verify clicking "Add to Bag" adds product and updates badge (Functional / E2E / P1)
8. **TC_442_08:** Verify Shopping Bag page item count accuracy (Functional / E2E / P1)
9. **TC_442_09:** Verify Order Summary pricing formula in Shopping Bag (Functional / E2E / P1)
10. **TC_442_10:** Verify Search with non-existent keyword (Negative / P3)
