# Project 1: Data Cleaning & Preparation

I Cleaned a raw e-commerce orders dataset (1,200 records, 14 columns) using Python (Pandas) in Google Colab.

## Cleaning Steps
- Filled 309 null `CouponCode` values with "No Coupon" (null means no coupon was used)
- Checked for duplicates: 0 duplicate rows, all 1,200 `OrderID` values unique
- Trimmed whitespace and applied proper case to text columns
- Rounded `UnitPrice` and `TotalPrice` to 2 decimals
- Standardized `Date` to YYYY-MM-DD

## Final Verification
Duplicate OrderIDs: 0 | Invalid dates: 0 | Remaining nulls: 0

## Files
- `Project1_intership.ipynb`: cleaning code
- `Cleaned_Dataset.xlsx`: cleaned data
- `Project_1_change_log.pdf`: change log
