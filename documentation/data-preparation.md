# Data Preparation & Quality Checks

## Overview

Before developing the Power BI report, the donation dataset was reviewed and prepared to ensure that the fields could be used reliably for analysis.

## Data Type Validation

Column data types were reviewed and adjusted where necessary to ensure that dates, numerical values and categorical fields were correctly formatted.

## Missing Value Checks

The dataset was checked for null or missing values and the relevant fields were assessed before proceeding with analysis.

## Duplicate & Identifier Validation

Identifier fields were reviewed for duplicate values and potential inconsistencies between transaction-level and donor-level identification.

## Donor Validation

Donor records were cross-checked using email information to investigate whether multiple transactions could belong to the same donor.

This validation identified one donor associated with two donation transactions. This highlighted the importance of distinguishing between transaction identifiers and donor identifiers when calculating donor-level metrics.

## Preparation for Analysis

After the quality checks, the prepared data was used to develop the Power BI report, including:

- KPI measures
- Fundraising trends
- Donor analysis
- Campaign analysis
- Referral channel analysis
- Newsletter engagement analysis
