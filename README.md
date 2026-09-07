# AcademyBugs Manual QA Testing Portfolio

## Project Overview

This project demonstrates my ability to plan, execute, and document manual software testing against AcademyBugs, an e-commerce training website containing intentionally planted defects.

I created and executed 12 test cases covering product browsing, search, sorting, shopping-cart behavior, boundary conditions, navigation, and checkout validation. Test results, defects, risks, and supporting evidence were documented in a structured QA workbook.

## Test Results

| Metric | Result |
|---|---:|
| Test Cases Executed | 12 |
| Passed | 9 |
| Failed | 3 |
| Pass Rate | 75% |
| Defects Documented | 3 |

## Testing Techniques

- Functional testing
- Exploratory testing
- Positive testing
- Negative testing
- Boundary-value testing
- Retesting
- Risk-based assessment

## Key Findings

### DEF-001: Placeholder Product Description

The DNK Yellow Shoes product page displayed Lorem Ipsum placeholder content instead of a meaningful English product description.

### DEF-002: Incorrect Shopping-Cart Grand Total

The shopping cart added an unexplained $100.00 to the correct grand total. The defect reproduced with quantities of both one and two, creating a significant financial risk.

### DEF-003: Incorrect Return to Store Button Spacing

The empty-cart page displayed excessive spacing before the final letter in the Return to Store button caption.

## Test Environment

- Device: Chromebook
- Operating System: ChromeOS
- Browser: Google Chrome
- Browser Version: 151.0.7922.168 (64-bit)

## Project Artifacts

- [View the interactive Google Sheets portfolio](https://docs.google.com/spreadsheets/d/1Lu54suePRSSw4ntlIJGAko3MFXoJMvNa/edit?usp=sharing)
- [Download the Excel QA portfolio](./AcademyBugs-QA-Portfolio.xlsx)

The portfolio workbook includes:

- Project overview and test scope
- 12 fully documented test cases
- Expected and actual results
- Test execution statuses
- Three detailed defect reports
- Screenshot and video evidence links
- Formula-driven test summary
- Risk assessment and recommended next steps

## Skills Demonstrated

- Test-case design and execution
- Defect identification and documentation
- Severity and priority classification
- Expected-versus-actual result analysis
- Evidence collection and organization
- Requirements-based reasoning
- Risk communication
- Professional QA reporting

## Conclusion

The tested workflows generally supported the expected customer journey, but the shopping-cart grand-total defect represents a significant financial risk. In a production environment, I would recommend correcting and retesting the calculation before release, followed by regression testing across multiple products, quantities, and cart combinations.

## About the Tester

**Gibran Napier**  
Aspiring QA professional building hands-on experience in software testing, defect analysis, and technical documentation.
