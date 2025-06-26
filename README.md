# Healthcare-Claims-Data
Dataset Overview: Medicare Provider Utilization and Payment Data
What is this dataset?
This is a claims-based healthcare dataset containing data on services provided by individual healthcare professionals and organizations to Medicare beneficiaries in the United States. The data originates from Medicare Part B claims — covering outpatient and professional services such as doctor visits, diagnostic tests, and procedures.

Each row in the dataset represents a unique provider + procedure combination and contains:
Provider details (e.g., name, location, specialty)
Procedure/service billed (e.g., office visits, lab tests, imaging)
Utilization data (e.g., how many services were performed and on how many patients)
Financials (e.g., what was billed, allowed, and actually paid by Medicare)

What is Medicare?
Medicare is a U.S. federal health insurance program primarily for:
People aged 65 and older
People with disabilities or end-stage renal disease (ESRD)
Doctors and hospitals submit claims to Medicare for reimbursement. This dataset captures those claims and what Medicare actually reimbursed — allowing analysis of cost gaps and healthcare utilization patterns.

What the Dataset Contains
Category	Columns	Examples / Notes
Provider Information - Name, NPI (ID), Gender, Credentials, Location (State, Zip, Country)	Helps identify provider trends
Specialty	Provider Type	e.g., Internal Medicine, Cardiology, Podiatry
Service Info - HCPCS Code, HCPCS Description, Place of Service, HCPCS Drug Indicator	Shows what service was performed and where (e.g., office or facility)
Utilization Metrics - Number of Services, Number of Beneficiaries, Distinct Beneficiary/Per Day	Indicates how often and for how many patients a procedure was used
Cost Metrics - Average Submitted Charge Amount, Average Medicare Allowed Amount, Average Medicare Payment Amount, Standardized Amount	Compare what providers bill vs. what Medicare pays

Key Terms Simplified
Submitted Charge - The amount the provider billed Medicare for a service
Allowed Amount - The amount Medicare considers reasonable for that service
Payment Amount - What Medicare actually paid the provider
Cost Gap - The difference between what was billed and what was paid
Beneficiary - A patient covered under Medicare who received the service
Utilization Ratio - Average number of services per beneficiary (proxy for care intensity)

