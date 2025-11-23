flowchart TD

%% INITIAL CONTACT & ENROLLMENT
A[Initial Contact  
• Participant calls PACE  
• OR marketing outreach  
• OR referral from hospital/clinic/family] --> B[Intake Pre-Screen  
• Eligibility, service area  
• Age 55+  
• Insurance review  
• Basic ADL/IADL needs]

B --> C[In-Home Intake Visit  
• RN/MSW visit  
• Home safety preview  
• ADL/IADL baseline  
• Medication review]

C --> D[State LOC Determination  
• Nursing home level of care required  
• Approval → continue  
• Denial → appeal or private pay]

D --> E[Enrollment Agreement Signing  
• HIPAA NPP  
• Rights & Responsibilities  
• Emergency plan  
• Financial explanation  
• Start date assigned]

%% IDT INITIAL ASSESSMENTS
E --> F[IDT Initial Assessments (Within 30 Days)  
• PCP  
• RN  
• MSW  
• PT/OT  
• RT  
• Dietitian  
• Behavioral Health  
• Activities  
• Transportation  
• HCC  
• Personal Care]

F --> G[Initial Care Plan  
• Problem list  
• Goals  
• Interventions  
• Visit frequency  
• Home care needs  
• DME needs  
• Center attendance  
• Emergency plan]

%% HCC WORKFLOW
G --> H[HCC Initial Home Visit (Within 30 Days)  
• Safety evaluation  
• ADL/IADL functional assessment  
• Equipment needs  
• Environmental risks  
• Caregiving needs  
• Life Alert need  
• DME needs]

H --> I[HCC Presents Findings to IDT  
• DME recommendations  
• Caregiving hours  
• Home modifications  
• Life Alert  
• Safety risks  
• Urgent needs]

I --> J[IDT Decision & Approval  
• Approves services  
• Updates care plan  
• Confirms referrals needed]

%% REFERRALS & AUTHORIZATIONS
J --> K[Referral Process  
• RN/PCP enters referral  
• HCC revises referral  
• Adds instructions, codes, units  
• Attaches intake forms (Life Alert)  
• Assigns vendor]

K --> L[Authorization Process  
• Coverage review  
• Units & dates  
• Renewal rules  
• Attachments  
• Fax/submission to vendor]

L --> M[Vendor Coordination  
• Vendor accepts  
• Schedules installation or caregiving start  
• Provides ETA  
• Completes service]

%% LOOP CLOSURE
M --> N[Loop Closure  
• HCC confirms delivery  
• Confirms activation/start of care  
• Documents completion  
• Updates care plan  
• Communicates to IDT]

%% 6-MONTH CYCLE
N --> O[180-Day Reassessment  
• HCC home reassessment  
• ID
## PACE Full-Cycle Workflow Diagram

```mermaid
flowchart TD

A[Initial Contact  
• Participant calls PACE  
• OR marketing outreach  
• OR referral from hospital/clinic/family] --> B[Intake Pre-Screen  
• Eligibility, service area  
• Age 55+  
• Insurance review  
• Basic ADL/IADL needs]

B --> C[In-Home Intake Visit  
• RN/MSW visit  
• Home safety preview  
• ADL/IADL baseline  
• Medication review]

C --> D[State LOC Determination  
• Nursing home level of care required  
• Approval → continue  
• Denial → appeal or private pay]

D --> E[Enrollment Agreement Signing  
• HIPAA NPP  
• Rights & Responsibilities  
• Emergency plan  
• Financial explanation  
• Start date assigned]

E --> F[IDT Initial Assessments (Within 30 Days)  
• PCP  
• RN  
• MSW  
• PT/OT  
• RT  
• Dietitian  
• Behavioral Health  
• Activities  
• Transportation  
• HCC  
• Personal Care]

F --> G[Initial Care Plan  
• Problem list  
• Goals  
• Interventions  
• Visit frequency  
• Home care needs  
• DME needs  
• Center attendance  
• Emergency plan]

G --> H[HCC Initial Home Visit (Within 30 Days)  
• Safety evaluation  
• ADL/IADL functional assessment  
• Equipment needs  
• Environmental risks  
• Caregiving needs  
• Life Alert need  
• DME needs]

H --> I[HCC Presents Findings to IDT  
• DME recommendations  
• Caregiving hours  
• Home modifications  
• Life Alert  
• Safety risks  
• Urgent needs]

I --> J[IDT Decision & Approval  
• Approves services  
• Updates care plan  
• Confirms referrals needed]

J --> K[Referral Process  
• RN/PCP enters referral  
• HCC revises referral  
• Adds instructions, codes, units  
• Attaches intake forms (Life Alert)  
• Assigns vendor]

K --> L[Authorization Process  
• Coverage review  
• Units & dates  
• Renewal rules  
• Attachments  
• Fax/submission to vendor]

L --> M[Vendor Coordination  
• Vendor accepts  
• Schedules installation or caregiving start  
• Provides ETA  
• Completes service]

M --> N[Loop Closure  
• HCC confirms delivery  
• Confirms activation/start of care  
• Documents completion  
• Updates care plan  
• Communicates to IDT]

N --> O[180-Day Reassessment  
• HCC home reassessment  
• IDT discipline reassessments  
• Renew caregiving hours  
• Review DME needs  
• Update safety  
• Determine SDR if needs change]

O --> P[Ongoing Monitoring  
• Monthly reviews  
• Missed visits  
• Changes in condition  
• Hospitalizations  
• New referrals]

P --> G
```
