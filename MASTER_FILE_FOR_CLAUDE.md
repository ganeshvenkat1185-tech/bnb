# Master File — Ganesh Venkat Approval Calculator (Chennai Region)

## Brand Header
**Ganesh Venkat Technical Consultant — Sales · Chennai**  
ganesh.venkat@bricknbolt.com · +91 99720 50593

## What this master delivers
- A branded approval calculator HTML (`approval_calculator_master.html`) with:
  - Authority auto-detection by pincode (CMDA Urban / CMDA Sub-Urban / DTCP / Panchayat).
  - Cost breakdown (plot, building, scrutiny, betterment, structural, cess, architect, engineer, GST).
  - District-wise pincode coverage cards for Chennai, Kancheepuram, Thiruvallur, Chengalpattu.
  - A copy-ready implementation prompt for Claude.

## Data notes
- The pincode matrix included in the calculator focuses on the requested districts and nearby areas.
- Before submitting official plans, verify rates and latest jurisdiction circulars with local approving authority.

## Claimed execution workflow (for Claude)
1. Read pincode, area, building type, and floors.
2. Detect governing authority and district.
3. Apply fee model by authority.
4. Compute GST and total payable estimate.
5. Show authority-specific checklist and expected timeline.
6. Export summary in customer-friendly format.

## Important limitation log
- In this environment, no PDF attachment was available in the repository to parse directly.
- The requested public pincode site may block automated scraping; curated regional pincode mapping has been embedded directly in the master file.
