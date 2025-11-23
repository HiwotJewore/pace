# PACE Full-Cycle Workflow

This repository contains the complete Program of All-Inclusive Care for the Elderly (PACE) operational workflow, including enrollment, IDT processes, HCC workflows, referrals, authorizations, loop closure, and the 6-month reassessment cycle.

---

## PACE Workflow Diagram (Mermaid)

```mermaid
flowchart TD

%% INITIAL CONTACT
A[Initial Contact  
Participant calls PACE or marketing outreach] --> B[Intake Pre-Screen  
Eligibility, service area, age, medical needs]

B --> C[In-Home Intake Visit  
RN or MSW evaluates safety, ADLs, meds]

C --> D[State LOC Determination  
Nursing home level-of-care required]

D --> E[Enrollment Agreement  
HIPAA, Rights, Responsibilities, Start Date]

%% IDT ASSESSMENTS
E --> F[IDT Assessments (30 Days)  
RN, PCP, MSW, PT, OT, Dietitian, BH, RT, HCC]

F --> G[Initial Care Plan  
Problems, goals, interventions]

%% HCC INITIAL WORK
G --> H[HCC Initial Home Visit  
Home safety, ADLs, equipment, risks]

H --> I[HCC Presents Needs to IDT  
Caregiving, DME, Life Alert, services]

I --> J[IDT Approval  
Services authorized for care plan]

%% REFERRALS
J --> K[Referral Entry  
RN/PCP places referral]

K --> L[HCC Edits Referral  
Codes, units, vendor, instructions]

L --> M[Vendor Processing  
Vendor schedules and delivers service]

%% LOOP CLOSURE
M --> N[Loop Closure  
HCC confirms completion and documents]

%% 6-MONTH CYCLE
N --> O[180-Day Reassessment  
HCC reassesses home and services]

O --> P[Ongoing Monitoring  
Monthly review, changes, new referrals]

P --> G
```

---

## Contents
- Full PACE operational workflow  
- IDT and enrollment structure  
- HCC process from assessment to loop closure  
- Authorization and referral flow  
- Six-month reassessment cycle  

---

## Purpose
This diagram is used for training, consulting, and education on how PACE programs operate from the first participant call through enrollment and ongoing care management.

---

## How to View the Diagram
GitHub now natively supports Mermaid diagrams.  
If you are readin
