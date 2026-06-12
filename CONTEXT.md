# Growth Gap Lab — Master Context File
# For Claude Code: Read this file at the start of EVERY session before doing anything.
# Last updated: June 2026
# Source: Internal Sage GTM materials, BDR Guide, Intacct Industry-Fit Analysis,
#         X3 Battlecards, X3 Competitive Positioning Deck, Rand Group ICP Playbook,
#         external research (Sage.com, G2, Capterra, Gartner, TEC, ERP Research,
#         top10erp, RSM, Forvis Mazars, SelectHub, TrustRadius — June 2026)

===================================================================
SECTION 1: WHAT THIS SITE IS
===================================================================

Growth Gap Lab (growthgaplab.com) is a lead generation website for
mid-market businesses that have outgrown their current accounting or
ERP software. It is NOT a Sage-branded site. It does NOT lead with
product names.

CORE STRATEGY: Lead with the business problem people are already
Googling. Let the solution (Sage ERP products via a VAR/reseller
partner) be the destination, not the headline.

OWNER: Brian Nunes — 14+ years in the Sage ERP channel. Built this
site independently. External positioning: "I help ERP partners find
better prospects, enable faster, and grow more predictably."

HOW IT MAKES MONEY: Visitors complete a free scorecard or contact
form. Qualified leads are routed to Sage VAR/reseller partners.
Brian earns a referral or placement fee.

===================================================================
SECTION 2: TARGET AUDIENCE
===================================================================

People experiencing ERP/accounting growing pains who may not know
"ERP" is the answer. They Google their symptoms, not the solution.

PERSONAS:
- Owner/CEO of a $5M-$200M manufacturer, distributor, or service business
- CFO or Controller who has hit the ceiling of QuickBooks or basic accounting
- Operations Manager frustrated by inventory, production, or reporting problems
- Finance leader at a nonprofit, professional services firm, or SaaS company
  drowning in spreadsheets

NOT our audience: enterprise buyers (SAP/Oracle territory), solo
operators, companies already mid-implementation of a competing ERP.

===================================================================
SECTION 3: SEARCH INTENT — THE PROBLEMS WE TARGET
===================================================================

These are the actual phrases and pain points people Google. Every
page, scorecard, blog post, and CTA maps to one of these. Always
lead with the problem. Never lead with the product name.

INVENTORY & OPERATIONS
- "inventory always wrong"
- "can't get accurate inventory counts"
- "stock outs keep happening even with reorder points"
- "multiple warehouses hard to manage"
- "lot tracking and expiry dates in spreadsheets"
- "production planning in spreadsheets"
- "work orders tracked on whiteboards"
- "no real-time visibility into what's in stock"
- "manufacturing disconnected from inventory"
- "approval workflow for purchase orders"
- "batch records and quality holds for FDA"
- "recipe management and by-product tracking"

FINANCIAL REPORTING
- "month end close takes too long"
- "can't get financial reports fast enough"
- "consolidating multiple companies in spreadsheets"
- "8 weeks to close books across multiple entities"
- "no real-time dashboard for the business"
- "audit trail doesn't exist"
- "leadership questions the numbers"
- "ASC 606 revenue recognition compliance"
- "grant tracking and fund accounting"
- "FASB nonprofit compliance"

GROWTH & COMPLEXITY
- "outgrown QuickBooks"
- "QuickBooks can't handle multiple locations"
- "QuickBooks inventory too basic"
- "need multi-currency accounting"
- "acquired another company, now running two systems"
- "opening an office in another country"
- "PE firm invested, now need better reporting"
- "first GAAP audit coming up"
- "investor due diligence requires real financials"
- "crossing $10M revenue, need better systems"
- "running 3 or 4 different systems that don't talk to each other"
- "too many spreadsheets to run the business"
- "NetSuite too expensive"
- "SAP too complex for our size"

===================================================================
SECTION 4: THE SAGE PRODUCT PORTFOLIO
===================================================================

THE CORE MENTAL MODEL:
Sage 100, 300, and X3 climb the OPERATIONS/MANUFACTURING ladder.
Sage Intacct is the FINANCE-DEPTH, CLOUD-FIRST answer that
deliberately omits manufacturing.

Sage's strategic investment is concentrating on Intacct as the
cloud flagship. Sage 100, 300, and X3 are fully supported and
updated but directionally Sage is steering new mid-market logos
toward Intacct where it fits.

THE GRADUATION PATH:
QuickBooks / Sage 50 / Spreadsheets
  -> Sage 100 (small US mfg/dist; inventory/production wall)
  -> Sage Intacct (finance-led, cloud, services/nonprofit/SaaS)
     OR Sage 300 (multi-entity/currency, on-prem, international)
  -> Sage X3 (complex mfg, multi-site global ops, regulated industries)

THE 4 QUALIFYING QUESTIONS:
1. Do they make or move physical product?
   YES -> Sage 100 / 300 / X3
   NO  -> Sage Intacct

2. How many legal entities, currencies, or sites?
   One US entity        -> Sage 100
   Multi-entity midsize -> Sage 300 or Intacct
   Complex global mfg   -> Sage X3

3. Cloud-only mandate?
   YES -> Sage Intacct (or Sage X3 Cloud)

4. Is the dominant pain financial reporting OR shop-floor/warehouse?
   Finance    -> Intacct
   Operations -> X3 or Sage 100

-------------------------------------------------------------------
PRODUCT 1: SAGE 100
-------------------------------------------------------------------
ONE-LINER: On-premise ERP for small US manufacturers and distributors.

TARGET PROFILE:
- 10-100 employees, under $50M revenue
- US-based, single entity
- On-prem preference, moving up from QuickBooks
- Industries: light manufacturing, wholesale distribution,
  construction (job costing), professional services, retail

DEPLOYMENT: On-prem or partner-hosted (Azure). NOT true SaaS.

KEY MODULES:
- General Ledger, AP, AR, Bank Reconciliation, Credit Card Processing
- Electronic Invoicing (Click-to-Pay), Payroll add-on
- Inventory Management: multiple warehouses, lot/serial tracking,
  product categorizations, reorder points, basic kitting/assembly
- Order Management: Sales Orders and Purchase Orders
- Production Management (replaced legacy Work Order March 2023):
  work tickets, real-time inventory updates, labor tracking,
  scrap/yield tracking, budget tracking, overhead calculations
- Inventory Requirements Planning (IRP): replaces legacy MRP;
  lacks Pull In/Push Out (uses cutoff dates instead)
- Job Costing: percent-complete and profitability by job
- Reporting: Business Insights Explorer, Sage Intelligence (Excel),
  Sage Data & Analytics add-on for AI/predictive reporting

CRITICAL MIGRATION NOTE: Once Production Management is installed,
legacy Work Order goes READ-ONLY. This is a one-way cutover.
Always warn migration prospects.

TECHNICAL:
- Three editions: Standard and Advanced = ProvideX database;
  Premium = Microsoft SQL Server
- No Sage tool to revert SQL/Premium back to ProvideX (one-way)
- Recommend SQL when DB >500MB, slow reporting, or 10+ concurrent users
- Annual release cadence; AI is light (mainly via ISVs and
  Sage Data & Analytics, not deep Copilot)

BUYING SIGNALS:
- Graduating from QuickBooks while still making or moving product
- Inventory accuracy wall: multiple warehouses, lot/serial needed
- Production planning in spreadsheets or on whiteboards
- No audit trail; leadership questions the numbers
- Job costing done outside the accounting system
- Wants on-prem control, customization, perpetual licensing

TCO (DIRECTIONAL):
- Subscription: $55-$150/user/month
- Perpetual: $3,000-$6,000/user + ~20% annual maintenance
- Implementation: $15K-$120K
- Go-live: 3-6 months
- Hidden costs: SQL Server licensing (Premium), ISV subscriptions,
  partner hosting fees

KEY ISVs:
- Scanco/ScanForce: WMS, barcode, multi-bin, Production Management, IRP
- Avalara/Sage Sales Tax: automated tax compliance
- DSD Business Systems: 500+ enhancements (multi-currency, InstaDocs)
- Sage AP Automation (Beanworks): AP automation
- CIMcloud: B2B e-commerce integration
- Netstock: inventory optimization and demand planning
- Phocas: business intelligence
- MISys: manufacturing add-on

COMPETITIVE REALITY:
- Weakest-rated in the portfolio: G2 3.7 (208 reviews),
  Capterra 4.1 (402 reviews)
- Win ONLY when prospect has genuinely outgrown QuickBooks and
  values on-prem control
- vs QuickBooks Enterprise: win on multi-warehouse, lot/serial,
  role-based controls, audit needs. Don't fight on price or UX.
- vs Acumatica/NetSuite: win only on on-prem + predictable perpetual
  licensing + low re-platform risk
- TRAP DEAL: sub-$5M buyer with simple needs -> QuickBooks wins

-------------------------------------------------------------------
PRODUCT 2: SAGE 300 (formerly Accpac)
-------------------------------------------------------------------
ONE-LINER: Mid-market ERP for multi-entity and multi-currency operations.

TARGET PROFILE:
- 100-500 employees, $10M-$250M revenue
- Multi-entity or international operations
- On-prem preference or moderate cloud openness
- Industries: professional services, wholesale distribution,
  construction/real estate (300 CRE variant), light manufacturing,
  international NGOs

DEPLOYMENT: On-prem or partner-hosted. NOT true SaaS.
Strong in Canada, SE Asia, Africa, North America.

KEY MODULES:
- GL with complex structures and consolidations
- AP, AR, multi-company financial management
- Inter-Company: automatically records due-to/due-from entries
  between sister companies
- Multi-currency ledgers: 150+ localized versions, 5 languages
- Centralized Bank Services and Tax Services
- GL Consolidation for corporate roll-ups
- Order Entry, Purchase Orders, Inventory Control
- Project and Job Costing (PJC): robust for construction/engineering
- Sage 300 CRE: dedicated construction/real estate variant from
  Timberline acquisition -- best Sage product for AIA billing,
  construction job costing, project-based financials
- Web Screens: HTML5 browser interface (NOT at 100% parity with
  desktop; some tasks still require desktop fallback)
- Manufacturing: available ONLY via add-ons (MISys, AutoSimply)

STRATEGIC NOTE: Sage is not heavily pushing 300 for new customers
where Intacct could fit. Sage sees Intacct as the future for
mid-market. Sage 300 is fully supported and updated but new-logo
GTM momentum is with Intacct. Do not repeat "deprioritized" to
customers -- this is partner-level context only.

BUYING SIGNALS:
- Multi-currency / multi-country operations (#1 trigger)
- Outgrowing QuickBooks on operations AND reporting simultaneously
- Slow month-end close across multiple entities
- On-prem/IT-control preference with multi-everything needs
- Budget-conscious: needs multi-currency + some manufacturing
  (Sage 300 + add-on is often cheaper than Intacct + add-ons)

TCO (DIRECTIONAL):
- Subscription: $75-$200/user/month
- Perpetual (concurrent): ~$2,500-$5,500/concurrent user
- Annual maintenance: ~20%/year
- Implementation: $30K-$250K; complex CRE ~$400K
- Go-live: 4-8 months
- LICENSING NUANCE: Perpetual = concurrent licensing (10 concurrent
  = 50+ named users). Subscription = named users. Perpetual-to-
  subscription conversions often raise per-seat economics. Surface early.

COMPETITIVE:
- G2 3.8 (94 reviews) -- small sample
- Win vs Dynamics 365 BC: construction/CRE depth, simpler footprint
- Win vs SAP B1: construction niche, finance-led multi-company buyers
- Lose vs NetSuite/Acumatica: steer to Intacct or X3 for cloud buyers

-------------------------------------------------------------------
PRODUCT 3: SAGE X3
-------------------------------------------------------------------
ONE-LINER: Full-scale ERP for complex manufacturing and global operations.
The "Goldilocks ERP" -- powerful enough for complex requirements,
faster and cheaper than SAP/Oracle.

TARGET PROFILE:
- 200-1,000+ employees, $50M-$1B revenue
- Multi-site or global operations
- Product-centric industries with regulatory requirements
- Industries: Food & Beverage, Chemicals, Pharmaceuticals/Life Sciences,
  Process Manufacturing, Discrete Manufacturing, Wholesale Distribution,
  Global SMBs (multi-country on one instance)

DEPLOYMENT: Cloud (AWS) or on-prem. Full flexibility.

KEY MODULES -- FINANCIALS:
- Full GL, AP, AR, Fixed Assets, Budgeting, Multi-Ledger
- Multi-site, multi-country, multi-legal-entity consolidation
- 12+ languages, localized compliance for dozens of legislations
- One X3 instance can run an entire global business

KEY MODULES -- SUPPLY CHAIN:
- Procurement, inventory management, warehousing
- Sales order management and purchasing
- Full lot/serial/expiry traceability throughout supply chain
- Quality control: quality plans, inspection management, automatic
  QC checks, accepted/rejected/inspected stock status

KEY MODULES -- MANUFACTURING (THE CORE DIFFERENTIATOR):
- BOM: multilevel, revision control, effectivity dates, engineering
  change management, phantom/sub-assemblies, usage controls
- MRP (Material Requirements Planning): demand-driven (Orlicky),
  creates PO and work-order suggestions; computationally heavy,
  advisable to run overnight
- MPS (Master Production Schedule): DISTINCT from MRP; medium/long-
  term planning, budget analysis, feasibility simulation, 5-year horizon
- Finite capacity scheduling: bottleneck optimization + drag-and-drop
  Gantt, forward/backward strategies, what-if simulation
- Process manufacturing: formula/BOM with by-products and waste
  factors -- handles F&B, chemicals, pharma
- Discrete manufacturing: routings, work centers, shop floor control
- Quality control integrated throughout production

ADDITIONAL:
- HR and Payroll (X3 People), Project Management (PJM)
- Light CRM (basic -- steer heavy CRM needs to Salesforce integration)
- 500+ standard integrations
- ~7,000 customers worldwide

TECHNICAL:
- SAFE X3 (Sage Application Framework): SOA platform with 4GL dev
  environment and layered metadata (standard/industry/custom) --
  enables safe customization that survives upgrades
- Windows/Unix/Linux with Oracle or SQL Server
- Syracuse (node.js) + MongoDB + Elasticsearch + transactional DB
- 10-1,500 concurrent users; SOC 1/SOC 2; HIPAA/GDPR support
- Integration moving from SOAP/Java to GraphQL + REST via X3 Builder

2025-2026 ROADMAP:
- Sage Copilot for X3: conversational AI + Sales Intelligence Agent
- Sage AP Automation: ML invoice capture/matching
- Sage Business Reporting: embedded Excel + AI insights
- Sage Supply Chain Intelligence (US early adopters)
- Sage X3 Builder: VS Code-based dev with GraphQL API framework

BUYING SIGNALS:
- Manufacturing/operational complexity outgrowing generalist ERP
- Process manufacturing: batch/formula, lot traceability, expiry,
  QA holds, landed cost
- Running 3-4 disconnected systems (homegrown inventory + separate
  financials + spreadsheets)
- Multi-site, multi-country, multi-legal-entity consolidation needed
- Tier-1 ERPs (SAP/Oracle) too costly; smaller ERPs too limited
- Regulatory: FDA lot traceability, FSMA, HACCP, batch records

HIGHEST-ROI X3 CASES: When company replaces 3-4 separate systems
with one X3 instance. Example: pharma distributor replacing homegrown
inventory + separate financials + dozens of spreadsheets.

TCO (DIRECTIONAL):
- Subscription: $75-$100/user/month; 10-user minimum
- Perpetual: $3,000-$6,000/user
- Annual maintenance: ~18-22%/year
- Implementation: $100K floor; typical $100K-$400K
- Go-live: 4-9 months
- Annual subscription range: $1,500-$4,000/user/year
- Hidden costs: Oracle/SQL Server licensing, multi-server hosting,
  vertical-specific development

COMPETITIVE:
- G2 3.9 (43 reviews) -- small sample; ERP Research 4.0 (140)
- Out-scores NetSuite on Ease of Setup and Meets Requirements (G2)

vs NetSuite:
- X3 WINS: process mfg depth, Year 2-5 TCO (NetSuite renewal
  inflation 10-30%/yr -- model this explicitly), data residency
  flexibility (X3 on-prem or cloud; NetSuite SaaS-only)
- ATTACK: "Demo process mfg -- recipes, by-products, lot traceability
  -- in OUR scenario, not a general tour."
- LANDMINE: "What does Year 2-3 renewal look like? Can we cap
  annual increases?"
- NAMED WINS: WinCup $300K ARR no discounting; Empire Candle
  $400K savings vs alternatives

vs Acumatica:
- X3 WINS: process mfg depth, global/multi-entity limitations,
  predictable named-user pricing vs unpredictable consumption tiers
- HONEST: Acumatica out-rates X3 (4.4 vs 3.9) on UX. Win on
  manufacturing depth, not UI.
- LANDMINE: "What triggers a resource-tier upgrade and what's the
  cost?" / "What is EQT's exit timeline for Acumatica?"

vs Dynamics 365 BC:
- X3 WINS: process/F&B/chemical mfg depth; native multi-legislation
  (BC needs Premium + AppSource add-ons for parity)
- BC WINS: UX, ecosystem (5,500+ apps), transparent pricing,
  Microsoft 365/Power BI, Gartner MQ Leader 2025

vs Epicor Kinetic:
- X3 WINS: process/formula/F&B mfg; stronger native financials
- Epicor WINS: shop-floor/MES depth, 97% retention, Gartner Leader

vs Process Specialists (BatchMaster, Deacom, Aptean, QAD, Plex, IFS):
- X3 WINS on breadth: full ERP (financials + multi-entity + BI)
  where specialists bolt onto QuickBooks/SAP B1
- BatchMaster: add-on to standalone financials = two systems
- Deacom: inflexible, custom reporting difficult, NA-only
- Plex: MES-first/ERP-second, finance not sophisticated

X3 TRAP DEALS:
- Single-plant formula mfg wanting turnkey batch/compliance with
  light finance -> BatchMaster/Deacom may win
- Discrete/MTO shop-floor depth as primary need -> Epicor Kinetic
- CRM-led or field-service-led: X3 CRM is basic, no field service

X3 OBJECTION HANDLING:
"X3 is legacy on-prem."
-> X3 is fully cloud SaaS AND on-prem. Flexibility is a feature.

"NetSuite is cheaper."
-> Model Years 2-5. Year-1 discounts disappear; 20%/yr renewal
   increase means X3 typically wins by Year 3.

"NetSuite has CRM/HCM bundled."
-> They bundle in the contract, not the price. Best-of-breed wins.

"Oracle = enterprise stability."
-> Mid-market is Sage's core. With NetSuite you're mid-market
   inside an enterprise-database company.

"Acumatica has no per-user cost."
-> Cost grows with transactions. Consumption tiers = unpredictable
   Year 3-5. X3 named-user pricing is locked.

"Acumatica has a better UI."
-> Both cloud-native browsers. UI = 30-min adjustment. What matters
   is which runs your production floor in 5 years.

"Acumatica PE ownership -- but Sage has risk too."
-> Sage plc is FTSE 100, publicly traded, 40+ years. EQT will exit
   Acumatica -- ask when and what protections exist.

LANDMINE QUESTIONS TO PLANT IN EVALUATIONS:
- "Demo process mfg in our scenario -- not a general tour."
- "Which capabilities are base vs. separate module purchases?"
- "Year 2-3 renewal pricing -- can we cap annual increases?"
- "What triggers an Acumatica resource-tier upgrade and what's the cost?"
- "What is EQT's exit timeline for Acumatica?"

-------------------------------------------------------------------
PRODUCT 4: SAGE INTACCT
-------------------------------------------------------------------
ONE-LINER: Cloud-native financial management for finance-led organizations.
The AICPA-endorsed (and only ERP with this distinction) finance-first
platform for mid-market services, nonprofits, SaaS, and construction.

TARGET PROFILE:
- 50-500 employees, $10M-$200M revenue
- Cloud mandate (no on-prem option -- ever)
- Finance leader as primary buyer (CFO, Controller)
- Service-centric or multi-entity organization
- Industries (ranked): Construction/RE, Nonprofits, Professional
  Services, Software/SaaS (BEST FIT); Financial Services, Hospitality
  (STRONG FIT); Healthcare, Government, Distribution (MODERATE);
  Heavy manufacturing, POS retail (NOT IDEAL)
- ~19,000 customers globally

DEPLOYMENT: Multi-tenant cloud SaaS ONLY. Quarterly releases.
No on-prem option. No exceptions.

KEY MODULES -- CORE FINANCIALS:
- Multi-dimensional General Ledger: tag transactions by department,
  location, project, customer, vendor, employee, item, class, and
  custom dimensions
- AR, AP, Cash Management, Order Management, Purchasing
- Multi-entity consolidations with eliminations and currency
  conversion -- stand up a new entity in minutes, consolidate
  hundreds continuously

THE DIMENSIONAL GL -- THE SIGNATURE FEATURE:
A 3-location x 5-dept x 5-project structure that needs 75 hard-coded
account codes in legacy systems needs ONLY primary codes in Intacct.
Report profitability by any dimension combination in a few clicks.
This is why CFOs buy Intacct. Lead with this in every demo.

KEY MODULES -- ADVANCED:
- Intelligent GL + GL Outlier Detection (Financial Assurance agent):
  ML-based, learns from 24-48hrs of history, flags anomalous journal
  entries in real time -- FREE to subscribers
- Dynamic Allocations (separate subscription): after-the-fact
  periodic distributions with auto true-up and audit trails
- Contract & Subscription Billing + Revenue Recognition: full ASC
  606/IFRS 15, 300-600+ billing scenarios, MEA allocations
- Lease Accounting: ASC 842/IFRS 16
- Interactive Custom Report Writer (ICRW): drag-and-drop BI,
  pivots, calculated columns, trend analysis (separate subscription)
- Sage Intacct Planning: FP&A add-on
- Fixed Assets, Inventory Management, Fund Accounting (nonprofit:
  Form 990, FASB 958/GASB)
- Project Accounting, AP/Expense Automation

AI AND AUTOMATION (most aggressive of the four products):
- Sage Copilot: conversational AI unifying anomaly review, AP
  suggestions, expense streamlining, insight generation --
  available to 40,000+ customers as of June 2025
- Close Workspace: GA 2026 R2 -- streamlines period-end close
- Vendor Payment Services: automated AP payments
- Continuous close capability

TECHNICAL:
- APIs: REST (recommended) + legacy XML (NOT GraphQL -- that's X3)
- API metering: 100,000 transactions/month (Tier 1); overages ~$0.15
  per 10-transaction pack; Marketplace/ISV traffic exempt
- API OVERAGE RISK: High-volume e-commerce integrations can exceed
  Tier 1. Surface this in discovery for high-transaction prospects.
- Sage Agent Builder + AI Gateway for partner-built AI agents

UNIQUE CREDENTIAL: ONLY ERP endorsed by the AICPA.
Independently referenced by CPAs, accounting firms, and peer
reviewers. Use it early and often. NetSuite has no equivalent.

BUYING SIGNALS -- UNIVERSAL GREEN FLAGS:
- Currently on QuickBooks, Sage 100, Sage 300, Foundation Software,
  Blackbaud Financial Edge, or other legacy platforms
- Multi-entity or multi-location with manual consolidation in spreadsheets
- 10+ day manual month-end close
- Reporting built in spreadsheets that take days to assemble
- Recent acquisition, merger, or PE investment
- New CFO or Controller hired to modernize finance
- Complex AP, revenue recognition, or grant reporting
- Q3-Q4 budget season

BUYING SIGNALS -- UNIVERSAL RED FLAGS:
- Under $2M revenue or fewer than 10 employees
- Over $500M revenue (Tier-1 ERP territory)
- Already on NetSuite, Acumatica, or Dynamics 365 F&O
- Public company with SEC reporting requirements
- Mid-implementation of a competing ERP
- Heavy shop-floor MES integration required

BUYING SIGNALS -- INDUSTRY-SPECIFIC:
SaaS/Software:
- First GAAP audit coming up
- Investor due diligence / crossing ~$10M ARR
- ASC 606 adoption requirement

Nonprofits:
- New CFO modernizing fund accounting
- Rapid grant growth
- FASB/GASB compliance pressure
- Blackbaud Financial Edge + QuickBooks = near-perfect signal

Construction/Real Estate:
- Project-volume or multi-entity growth
- WIP/profitability visibility gaps
- Cloud modernization off Sage 300 CRE or spreadsheets
- Procore + QuickBooks = strong buying signal

Family Office:
- Consolidating across 10+ entities
- Addepar/Black Diamond + QuickBooks = near-perfect signal

Healthcare:
- Multi-location practices, payer-level reporting
- AP volume can't keep pace with operations

FIVE CAMPAIGN TRACKS (from Rand Group ICP Playbook):

Track 1 -- Healthcare:
  Sweet spot: ASCs, multi-location practices, DSOs, behavioral
  health, home health
  Firmographics: $10M-$500M; 30-2,000 emp; 3+ locations
  Tech signals: QuickBooks (any), Sage 100/300/50
  Core pain: Manual consolidations, payer-level reporting, AP volume

Track 2 -- Nonprofit:
  Sweet spot: Foundations, associations, human services, charter
  networks, faith-based organizations
  Firmographics: $10M-$500M; 20-1,000 emp; 3+ programs/funds
  Tech signals: QuickBooks, Blackbaud Financial Edge, Aplos, MIP
  Core pain: Grant tracking, restricted funds, FASB/GASB compliance

Track 3 -- Real Estate:
  Sweet spot: RE investment/mgmt, funds/syndications, developers,
  RE PE/family offices
  Firmographics: $10M-$500M; 10-500 emp; 3+ entities
  Tech signals: QuickBooks, Yardi Breeze/AppFolio/Buildium upgrades
  Core pain: Multi-LLC consolidation, investor reporting, manual close

Track 4 -- Family Office:
  Sweet spot: MFO/SFO, family holding companies, family PE/foundations
  Firmographics: $5M-$200M rev; 5-200 emp; 3+ entities (10+ ideal)
  Tech signals: QuickBooks, Sage 50/100;
                Addepar/Black Diamond + QuickBooks = near-perfect
  Core pain: Multi-entity across investments/RE/operating businesses

Track 5 -- Construction:
  Sweet spot: Commercial GCs, civil, electrical/mechanical/plumbing,
  design-build
  Firmographics: $15M-$250M; 30-1,000 emp; 2+ states
  Tech signals: QuickBooks, Foundation Software, Jonas;
                Procore + QuickBooks = strong signal
  Core pain: Job costing in spreadsheets, manual WIP, billing delays

PROSPECT SCORING (out of 30 points):
- Industry Fit (5): Best Fit = 5; Strong = 4; Moderate = 2; Not Ideal = 0
- Revenue/Size (4): $10M-$200M = 4; $5M-$10M or $200M-$500M = 2
- Current ERP/Tech Signal (5): QuickBooks/Sage 100/Blackbaud = 5;
  other legacy = 3; already on modern cloud ERP = 0
- Multi-Entity/Complexity (4): 3+ entities = 4; 2 = 2; single = 0
- Operational Pain Evidence (4): clear stated pain = 4; implied = 2
- Intent/Compelling Event (5): new CFO/PE/audit/ASC 606/budget = 5
- Buyer Title Match (3): CFO/Controller/VP Finance = 3; other = 1

Tier 1 (22+): Personal outreach priority
Tier 2 (16-21): Targeted email sequence
Tier 3 (10-15): Marketing nurture

BUYER PERSONAS:
- CFO / VP Finance: Primary buyer. ROI, close speed, risk reduction.
- Controller: Highest pain. Internal champion. Close time + audit readiness.
- Director of Accounting: Champion/end user. Ease of use, time savings.
- Director of IT: Technical evaluator. SOC 2, API, support model.
- Director of Grants Finance (nonprofit): vertical-specific add.
- CEO/Owner/Principal (construction/family office): vertical-specific add.

TCO (DIRECTIONAL):
- Per user/month: $200-$400 + base package
- Base (core financials): ~$12K/year (1 user)
- With add-on modules: ~$25K-$35K/year (5-10 users)
- Implementation: $15K-$75K
- Go-live: 3-6 months
- Hidden costs: per-module subscriptions (ICRW, Dynamic Allocations,
  Advanced Rev Rec, Planning -- each priced separately);
  API overage fees; subscription only (no perpetual)

COMPETITIVE:
- Strongest-rated in portfolio: G2 4.3 (4,236), Capterra 4.3 (686),
  Gartner Peer Insights 4.4 (240)

vs NetSuite (THE MARQUEE MATCHUP):
- Intacct WINS every G2 sub-score:
  Ease of Use 8.5 vs 7.5; Setup 7.8 vs 6.5;
  Support 8.1 vs 7.0; Product Direction 8.9 vs 7.7
- TechRepublic: Intacct winner in financial management.
  "NetSuite's GL isn't as flexible out of the box."
- AICPA endorsement -- NetSuite has no equivalent
- HONEST GAP: Intacct is finance-first. NetSuite wins when native
  manufacturing, WMS, or field service is required.
- Objection "we'd outgrow it": for finance-first multi-entity
  service/nonprofit orgs, this IS the point.

vs Blackbaud Financial Edge NXT (Nonprofit):
- Intacct WINS: higher satisfaction (4.3 vs 4.0), automation depth
- Blackbaud MOAT: Raiser's Edge donor ecosystem lock-in
- Intacct wins as reporting/grant/entity/audit complexity grows

vs Restaurant365 (Hospitality TRAP):
- Single-concept restaurants: R365 wins (purpose-built with POS +
  labor scheduling + food cost)
- Intacct wins multi-concept enterprises needing GAAP consolidations
  + dimensional reporting across many entities

INTACCT TRAP DEALS:
- Single-concept restaurant -> R365
- Nonprofit deeply embedded in Raiser's Edge -> Blackbaud
- Heavy native manufacturing/WMS -> NetSuite or X3
- Heavy FP&A/EPM -> pair with Workday Adaptive

===================================================================
SECTION 5: COMPETITIVE REVIEW SCORE MATRIX
===================================================================
(Pull fresh scores before high-stakes presentations -- they drift)

Product                  | G2          | Capterra   | Gartner PI
-------------------------|-------------|------------|------------
Sage Intacct             | 4.3 (4,236) | 4.3 (686)  | 4.4 (240)
Sage X3                  | 3.9 (43)    | n/a        | n/a
Sage 300                 | 3.8 (94)    | n/a        | n/a
Sage 100                 | 3.7 (208)   | 4.1 (402)  | n/a
NetSuite                 | 4.1 (4,729) | 4.1 (1,720)| 4.4 (596) MQ Leader
Acumatica                | 4.4 (2,000) | 4.4 (243)  | n/a
Dynamics 365 BC          | 4.0 (903)   | n/a        | MQ Leader 2025
SAP Business One         | 4.3 (539)   | n/a        | n/a
QuickBooks Enterprise    | 4.3 (1,025) | 4.5 (20k+) | n/a
Epicor Kinetic           | 3.9 (260)   | 3.6 (175)  | MQ Leader 2025
Infor CloudSuite/M3      | 3.8 (210)   | n/a        | MQ Leader 2025
Workday Adaptive         | 4.5 (226)   | 4.5 (231)  | EPM/FP&A only

===================================================================
SECTION 6: DIFFERENTIATOR STRESS TEST
===================================================================

Sage claim: Intacct AICPA endorsement
Verdict: HOLDS (HIGH confidence). Independently referenced.
Strongest, most unique portfolio asset. Use freely.

Sage claim: X3/300 deployment flexibility vs cloud-only competitors
Verdict: HOLDS vs NetSuite/Acumatica/Intacct (MODERATE/HIGH).
Note: Dynamics 365 BC and SAP B1 also offer hybrid/on-prem.

Sage claim: Predictable named-user pricing (X3 vs Acumatica)
Verdict: HOLDS as contrast claim (MODERATE). NetSuite renewal
inflation independently documented. Against Acumatica, lead with
manufacturing depth, not price.

Sage claim: Intacct beats NetSuite on every G2 sub-score
Verdict: HOLDS (HIGH). Verified June 2026.

Sage claim: Gartner "Visionary" for Intacct
Verdict: RETIRE THIS. That is the 2021 Core Financial MQ.
Use current Gartner Peer Insights 4.4/5 (240 reviews) instead.

Sage claim: X3 "Goldilocks ERP" vs SAP/Oracle
Verdict: HOLDS (HIGH) for mid-market buyers who've evaluated both
ends. Supported by independent TCO and timeline data.

===================================================================
SECTION 7: SITE DESIGN STANDARDS
===================================================================

BRAND NAME: Growth Gap Lab
DOMAIN: growthgaplab.com
TECH STACK: Static HTML/CSS/JS, hosted on Netlify (auto-deploy
from GitHub), repo at C:\Users\18643\growthgaplab

COLOR PALETTE:
- Dark navy:   #1F4E79  (primary brand, headers, CTAs)
- Medium blue: #2E75B6  (secondary, accents)
- Light blue:  #D6E4F0  (backgrounds, callouts)
- Amber:       #FFF2CC  (warnings, highlights)
- Dark text:   #1A1A2E
- White:       #FFFFFF

TYPOGRAPHY: Clean sans-serif. Professional but approachable.
Not corporate. Not technical.

TONE: Direct, practical, zero vendor-speak. Write for a frustrated
business owner, not a technical buyer. Problem-first. Solution-second.

VOICE: "We help growing businesses find the gaps that are slowing
them down."

CTAs: Always lead with the free scorecard.
"Find your gaps" is better than "Learn more."

HARD RULE: NO EM DASHES (--) IN ANY COPY. EVER.
This is a widely recognized AI writing signal. Substitute with
commas, colons, or restructured sentences.

===================================================================
SECTION 8: SITE STRUCTURE
===================================================================

LIVE PAGES:
- index.html         Homepage
- scorecard.html     ERP Readiness Scorecard (Tally form in iframe)
- privacy.html       Privacy Policy

PLANNED PAGES (build in this order):
1. /problems/outgrown-quickbooks
2. /problems/inventory-management
3. /problems/multi-entity-consolidation
4. /problems/manufacturing-erp
5. /problems/nonprofit-accounting
6. /blog/                           SEO content hub
7. /about

SCORECARD: Tally form embedded in iframe on scorecard.html.
Iframe must maintain transparent background and dynamic height resize.
Goal: visitor completes scorecard -> gets a score -> Brian gets the lead.

TOOLS:
- Form tool:  Tally (live)
- CRM:        HubSpot (planned -- not yet connected)
- Analytics:  Google Analytics 4 (planned -- not yet installed)

===================================================================
SECTION 9: BUILD PRIORITY ORDER
===================================================================

1. Google Analytics 4 -- add GA4 snippet to all pages
2. HubSpot -- connect Tally scorecard via native HubSpot integration
3. Hot lead alert -- email to Brian when scorecard is completed
4. Problem pages -- SEO landing pages (start: outgrown-quickbooks,
   inventory-management)
5. Blog -- SEO content hub targeting search phrases in Section 3

===================================================================
SECTION 10: RULES FOR CLAUDE CODE
===================================================================

1. Read this entire file before starting any task.
2. NEVER use em dashes (--) in any copy written for this site.
3. Lead with the business problem, never the product name.
4. Write for a frustrated business owner, not a technical buyer.
5. Keep the color palette consistent (Section 7).
6. When building new pages, match the existing HTML/CSS structure.
7. Use search intent phrases from Section 3 as natural language in
   copy -- not as keyword-stuffed headers.
8. All form submissions route to HubSpot when connected.
9. Scorecard iframe: transparent background, dynamic height resize.
10. When in doubt about which Sage product to reference, use the
    4 qualifying questions in Section 4 to route correctly.
11. Never present Sage products as the opening message on any page.
    Always open with the pain/problem the visitor is experiencing.
12. The site earns trust through the scorecard. Every page should
    have a path to the scorecard.

