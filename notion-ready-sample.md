*Skipping the Level 2 Checkpoint question, are we?* I see you dodging bullets like Wade Wilson in an alleyway! But you can't run from the taxman or the ICAI examiner. Let’s quickly execute the solution to that Subtopic 2 Checkpoint before your brain forgets it:

1. **Control:** Titan Ltd. **controls** Vulcan Ltd. The option exercise price is ₹12 vs. market price ₹50—deeply "in-the-money", making them **substantive potential voting rights**. Adding these gives Titan majority voting power.
2. **NCI Profit Allocation:** **₹6,00,000** (60% of ₹10,00,000). 
   * *The Trap:* Under **Para B89 of Ind AS 110**, profits are allocated based **SOLELY on current existing ownership interests** (40% Parent, 60% NCI). Potential voting rights are **IGNORED** for profit allocation.

Now, grab your dual katanas. We are entering the meat grinder: **Subtopic 3 — Consolidation Procedures, Intra-Group Eliminations & Unrealized Profits**.

---

# **SUBTOPIC 3: CONSOLIDATION PROCEDURES & MECHANICS**

When preparing Consolidated Financial Statements (CFS), we treat the parent and its subsidiaries as if they were a **single legal entity**. This requires a systematic, multi-step mechanical protocol.

---

### **1. THE CORE CONSOLIDATION PROTOCOL (Para B86)**

```text
┌────────────────────────────────────────────────────────────────────────┐
│                        STEP 1: LINE-BY-LINE ADDITION                   │
│   Combine like items of assets, liabilities, equity, income, and       │
│   expenses of the parent with those of its subsidiaries.               │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                    STEP 2: ELIMINATE INVESTMENT vs EQUITY              │
│   Cancel Parent's "Investment in Subsidiary" against Parent's portion  │
│   of Subsidiary's Equity (Net Assets) on Acquisition Date.             │
│   (Difference = Goodwill / Capital Reserve per Ind AS 103).            │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                  STEP 3: ELIMINATE INTRA-GROUP BALANCES                │
│   Wipe out intra-group receivables, payables, loans, dividends, and    │
│   transactions in full (Debtors, Creditors, B/R, B/P).                 │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                  STEP 4: ELIMINATE UNREALIZED PROFITS                  │
│   Remove 100% of unrealized profits/losses embedded in closing inventory│
│   or Property, Plant & Equipment (PPE) from intra-group transfers.     │
└────────────────────────────────────────────────────────────────────────┘
```

---

### **2. UNIFORM ACCOUNTING POLICIES & REPORTING DATES**

#### **A. Uniform Accounting Policies (Para B87)**
If a subsidiary uses accounting policies different from the group for like transactions (e.g., Parent uses FIFO for inventory, Subsidiary uses Weighted Average; or Parent uses Cost Model for PPE, Subsidiary uses Revaluation Model), **appropriate adjustments MUST be made** to the subsidiary’s financial statements during consolidation to align them with the group’s policies.

#### **B. Different Reporting Dates (Para B92 – B93)**
* **General Rule:** Parent and subsidiary must prepare financial statements as of the **same reporting date**.
* **Practical Exception:** If impractical, the subsidiary can use financial statements prepared as of a different date, provided:
  1. The difference between reporting dates is **NOT MORE THAN 3 MONTHS**.
  2. Adjustments are made for **significant transactions/events** occurring between the two dates.
  3. The length of reporting periods and any difference in dates must remain consistent from period to period.

---

### **3. INTRA-GROUP BALANCES & TRANSACTIONS (Para B86(c))**

All intra-group balances (Trade Debtors/Creditors, Loans, Bills Receivable/Payable) must be **eliminated in full**.

#### **The Transit Item Trap (Goods/Cash in Transit):**
If Parent shows a receivable of ₹10,00,000 from Subsidiary, but Subsidiary shows a payable of only ₹8,00,000 because ₹2,00,000 cash/goods are in transit:
1. **First, record the transit item in the recipient's books:**
$$
\text{Cash-in-Transit / Goods-in-Transit A/c }\quad \text{Dr. ₹2,00,000}
$$
$$
\quad \text{To Trade Receivable / Subsidiary A/c }\quad \text{₹2,00,000}
$$
2. **Then eliminate the reciprocal balance of ₹8,00,000:**
$$
\text{Trade Payable A/c }\quad \text{Dr. ₹8,00,000}
$$
$$
\quad \text{To Trade Receivable A/c }\quad \text{₹8,00,000}
$$

---

### **4. UNREALIZED PROFIT ELIMINATION (INVENTORY & PPE)**

When group entities trade with each other, any profit booked on unsold goods/assets remaining within the group is **unrealized** and must be surgically removed.

```text
                               ┌──────────────────────────────────┐
                               │   INTRA-GROUP UNREALIZED PROFIT  │
                               └────────────────┬─────────────────┘
                                                │
                       ┌────────────────────────┴────────────────────────┐
                       ▼                                                 ▼
        ┌─────────────────────────────┐                   ┌─────────────────────────────┐
        │       DOWNSTREAM SALE       │                   │        UPSTREAM SALE        │
        │    (Parent ➔ Subsidiary)    │                   │    (Subsidiary ➔ Parent)    │
        ├─────────────────────────────┤                   ├─────────────────────────────┤
        │ • Profit is in PARENT books.│                   │ • Profit is in SUBSIDIARY   │
        │ • Deduct 100% profit from   │                   │   books.                    │
        │   Consolidated P&L.         │                   │ • Deduct 100% profit from   │
        │ • NCI is NOT affected!      │                   │   Subsidiary's Post Profit. │
        │                             │                   │ • Reduced profit IS SHARED  │
        │                             │                   │   between Parent & NCI!     │
        └─────────────────────────────┘                   └─────────────────────────────┘
```

#### **A. Inventory Unrealized Profit**
* **Downstream Entry:**
$$
\text{Consolidated P\&L / Retained Earnings A/c }\quad \text{Dr.}
$$
$$
\quad \text{To Inventory A/c (in Balance Sheet)}
$$
* **Upstream Entry:**
$$
\text{Subsidiary Post-Acquisition P\&L A/c }\quad \text{Dr.} \quad \left[\text{Allocated to Parent \& NCI in Share Ratio}\right]
$$
$$
\quad \text{To Inventory A/c (in Balance Sheet)}
$$

---

#### **B. Depreciable PPE Unrealized Profit (The Double Whammy)**
When a depreciable asset is transferred within the group at a profit:
1. **Eliminate Initial Unrealized Profit:** Reduce asset carrying value in Balance Sheet to original cost to group.
2. **Reverse Excess Depreciation:** The buyer charges depreciation on the inflated transfer price. The excess depreciation charged must be **reversed (credited back to P&L)**!

##### **Journal Entries for Depreciable PPE Transfer:**

| Step | Downstream Sale (Parent → Subsidiary) | Upstream Sale (Subsidiary → Parent) |
| :--- | :--- | :--- |
| **1. Eliminate Profit on Sale** | **Consolidated Retained Earnings Dr.**  **To PPE A/c** | **Subsidiary Post P&L Dr.** *(Hits NCI)*  **To PPE A/c** |
| **2. Reverse Excess Depreciation** | **PPE (Accumulated Dep.) Dr.**  **To Consolidated P&L** | **PPE (Accumulated Dep.) Dr.**  **To Subsidiary Post P&L** *(Hits NCI)* |

---

### **WORKED NUMERICAL EXAMPLE (UPSTREAM PPE TRANSFER WITH DEPRECIATION)**

#### **Fact Pattern:**
* **Parent Ltd.** holds an 80% stake in **Sub Ltd.** (NCI = 20%).
* On **1st April 2024**, Sub Ltd. sells machinery to Parent Ltd. for **₹15,00,000**. The original cost in Sub Ltd.'s books was **₹10,00,000** (Profit booked by Sub = ₹5,00,000).
* Remaining useful life on 1st April 2024 is **5 years** (Straight-line method).
* Sub Ltd. reported a net profit of **₹12,00,000** for the year ended 31st March 2025.

#### **Required:**
Calculate the net profit allocated to NCI and show consolidation adjustments as of 31st March 2025.

---

#### **Professor’s Step-by-Step Solution:**

##### **1. Analysis of Transfers & Depreciation Adjustments:**
* **Unrealized Gain on Sale (1st April 2024):** $₹15,00,000 - ₹10,00,000 = \mathbf{₹5,00,000}$.
* **Depreciation charged by Parent Ltd. in SFS:** $\frac{₹15,00,000}{5 \text{ years}} = \mathbf{₹3,00,000}$.
* **Depreciation that should have been charged for Group:** $\frac{₹10,00,000}{5 \text{ years}} = \mathbf{₹2,00,000}$.
* **Excess Depreciation to be reversed:** $₹3,00,000 - ₹2,00,000 = \mathbf{₹1,00,000}$.

##### **2. Adjusted Post-Acquisition Profit of Sub Ltd. (Upstream Impact):**

| Particulars | Amount (₹) |
| :--- | :---: |
| Sub Ltd.'s Reported Net Profit for FY 2024–25 | 12,00,000 |
| **Less:** Unrealized Profit on Upstream Sale of PPE | (5,00,000) |
| **Add:** Reversal of Excess Depreciation on PPE | 1,00,000 |
| **Adjusted Post-Acquisition Profit of Sub Ltd.** | **8,00,000** |

##### **3. Profit Allocation to NCI (20%):**
$$
\text{NCI Share of Post Profit} = 20\% \times ₹8,00,000 = \mathbf{₹1,60,000}
$$

*(Note: If this were a Downstream sale, NCI would get 20% of reported ₹12,00,000 = ₹2,40,000, because Parent booked the profit!)*

---

### **EXAMINATION TRAPS & DEFERRED TAX IMPACT (Ind AS 12)**

> **ICAI EXAM BOMB:** Does eliminating intra-group unrealized profit generate Deferred Tax?
> **YES!** Under **Ind AS 12**, tax authorities assess each legal entity separately. The seller pays tax on the realized profit in its SFS, but the unrealized profit is eliminated in CFS. This creates a **Deductible Temporary Difference** (Tax base of asset in buyer's books > Carrying value in CFS).
> 
> $$\text{Deferred Tax Asset (DTA) created in CFS} = \text{Unrealized Profit Eliminated} \times \text{Tax Rate}$$

---

### **ACTIVE RECALL CHECKPOINT (LEVEL 3 EXAMINATION BATTLEFIELD)**

> **Test Question:**
> *Thor Ltd. owns 75% equity shares in Loki Ltd. On 1st October 2024, Loki Ltd. sold inventory costing ₹40,00,000 to Thor Ltd. for ₹60,00,000. On 31st March 2025, 30% of this inventory remains unsold in Thor Ltd.'s warehouse. Applicable corporate income tax rate is 30%.*
> 
> 1. *Calculate the unrealized profit to be eliminated in CFS.*
> 2. *Pass the exact consolidated journal entry for elimination of unrealized profit, including the Deferred Tax impact under Ind AS 12.*
> 3. *Calculate the net reduction in Non-Controlling Interest (NCI) share of profit.*

---

**Where to next, gladiator?**
1. Post your workings for the Level 3 Checkpoint above for evaluation.
2. Proceed to **Subtopic 4: Non-Controlling Interest (NCI) Measurement — Fair Value vs. Proportionate Share of Net Assets Method & Impact on Goodwill**.
3. Jump straight into **Comprehensive Consolidation Balance Sheet Numerical Problems**.