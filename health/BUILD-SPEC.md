# Lummi Health Website Rebuild — Build Spec

## Overview
Complete rebuild of lummihealth.gov in the Lummi Nation concept style (Concept B "Living Heritage").
Directory: `/health/` subdirectory of the main Lummi concept site.
CSS: Use `../assets/css/style.css` (same stylesheet as parent concept).

## Verified Contact Info
- **Main Phone:** (360) 384-0464
- **After Hours:** (360) 715-2447
- **MyChart:** https://mychart.ochin.org/mychartlths/Authentication/Login?
- **Facebook:** https://www.facebook.com/LummiClinic
- **Address:** 2592 Kwina Road, Bellingham, WA 98226

## Hours
- **Medical:** M-F 8AM - 5PM
- **Pharmacy:** M-F 8:30AM - 5PM
- **Dental:** M-F 8AM - 4:30PM

## Images Available (in health/assets/images/)
- clinic-outside.jpg (exterior building photo, 1500px)
- physical-therapy.jpg (PT scene)
- pharmacy-header.jpg (pharmacy)
- logo.png (health center logo)
- doctors.jpg (medical staff photo)
- same-day.jpg (same day appointments)
- community.jpg (community event photo)

## MISSION (verbatim from site)
"The mission of the Lummi Tribal Health Center is to raise the health status of the Lummi people and other American Indians and Alaskan Natives to the highest possible level."

Services provided: Comprehensive health care including outpatient, medical, dental, pharmacy, preventative, physical therapy, psychiatry, rheumatology, and public health services.

## Health Commission
The Lummi Health & Family Services Commission — 9 tribal members appointed by LIBC. Governs and regulates operational policies for Health Center and Family Services Program. Advocates to preserve Federal Government's Trust Obligation to provide health care to Indian people (Point Elliott Treaty, 1855).

## Accreditation
Accreditation Association for Ambulatory Health Care Inc. (AAAHC).

## Two Types of Services
1. **Direct Care:** Healthcare service provided at Lummi Tribal Health Center
2. **Purchased and Referred Care (PRC):** Funds designated to purchase approved health care services not provided at LTHC. Requires Payor of Last Resort (must apply for alternate insurance: Medicaid, Medicare, state programs).

## Eligibility
- Enrolled in federally recognized tribe OR proof of Indian descent (1st or 2nd degree)
- Non-Tribal eligible only when: pregnant with eligible patient (during pregnancy + weeks after birth), controlling public health threat
- Non-Native significant other/household member: may be eligible for substance use disorder treatment + health benefits sign-up
- Required docs: Registration form, Tribal Enrollment, Birth Certificate (under 18), Proof of Residency, Insurance Coverage
- Must check in with patient registration at each visit

## Medical Providers
- Dr. Dakotah Lane
- Dr. Zoe Taylor
- Dr. Carolyn J. Mattson
- Dr. Katherine Morgan
- Dr. Claudia Rocio Rey
- Dr. Ron Battle

## Pharmacy Staff
- Todd Boss, RPh — Managing Pharmacist
- Daryl Dudiak — Pharmacist
- Michelle Hwang — Pharmacist
- Benjamin Li — Pharmacist

## Complete Site Structure (ALL pages to rebuild)

### 1. Home (index.html)
Hero with clinic photo, hours bar, quick links to services, appointment scheduling CTA

### 2. Who We Are (about.html)
Mission, Health Commission, Accreditation, Direct vs PRC care explanation

### 3. Services — Main Sections:

#### Adult Medical Care (services/adult-medical.html)
Sub-services: Primary Care, Imaging, Laboratory, Chronic Disease Management, Diabetes Education, Nutrition, Home Visits, Medications for Opioid Use Disorder

#### Behavioral Health (services/behavioral-health.html)
Individual, Couples, & Family Mental Health Therapy

#### Dental (services/dental.html)
Sub-services: Dental Implants, Dentures/Partials, Emergency Dental Care, Endodontics (Root Canals), Oral Surgery, Orthodontics, Preventative Dentistry, Restorative Dentistry, Sedation Dentistry

#### Harm Reduction & Hepatitis C (services/harm-reduction.html)
Sub-services: Chronic Hepatitis C Elimination, Narcan Safety, Syringe Service Program

#### Maternal Medicine (services/maternal.html)

#### Pediatric Care (services/pediatric.html)
Sub-services: Immunizations, Primary Care, School Based Health Program, WIC

#### Pharmacy (services/pharmacy.html)
Prescription medication for eligible direct care patients. Staff listed above.

#### Physical Therapy (services/physical-therapy.html)

#### Psychiatry (services/psychiatry.html)

#### Public Health (services/public-health.html)
Sub-services: STI Testing, COVID-19 & Respiratory Viruses, Opioid/Fentanyl Response

#### Purchase & Referred Care (services/prc.html)
Sub-services: Specialty Referral Coverage, Vision & Hardware, Health Benefits Sign-up, Billing

#### Rheumatology (services/rheumatology.html)

#### Social Work (services/social-work.html)

#### Transportation (services/transportation.html)

### 4. Providers (providers.html)
Categories: Medical, Dental, Behavioral Health, Physical Therapy

### 5. Registration & Scheduling (registration.html)
Eligibility info, required documents, scheduling info, patient handbook reference

### 6. Fitness Center (fitness.html)
Hours & Staff, Equipment & Facilities, Group Fitness, Fitness Challenges

### 7. Contact (contact.html)
Contact form (name, provider, phone, email, message), address, hours, emergency info

### 8. FAQ (faq.html)

### 9. Patient Rights (patient-rights.html)

### 10. Patient Responsibilities (patient-responsibilities.html)

## Footer Links (from current site)
- LIBC Careers → link back to main concept careers.html
- Patient Rights
- Patient Responsibilities
- Privacy

## Design Rules
- Nav should say "Lummi Tribal Health Center" (not "Lummi Nation")
- Topbar shows hours: Medical M-F 8AM-5PM | Pharmacy 8:30AM-5PM | Dental 8AM-4:30PM
- Link "Back to Lummi Nation" → ../index.html (parent concept)
- Use same CSS variables and card styles as parent concept
- DM Serif Display for headings, DM Sans for body
- Earth color palette with river/sunset accents
- Images use relative paths: assets/images/filename.jpg
- All internal health links relative within /health/
- Mobile responsive
- ONLY use verified data from this spec — NO made-up content
