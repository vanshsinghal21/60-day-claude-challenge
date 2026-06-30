# 🏥 Hospital Admission Readiness Simulator | Day 28 – Claude AI Challenge

A modern, interactive healthcare workflow simulator that recreates the hospital admission process from an administrative perspective. This project places the user in the role of a **Hospital Admission Coordinator**, responsible for ensuring that every operational and clinical requirement is completed before a patient can be admitted.

The simulator demonstrates how prior authorization, insurance verification, documentation, physician orders, consent, bed availability, and care coordination collectively influence admission readiness through a dynamic weighted scoring system.

---

## 🌟 Project Overview

Hospital admissions involve multiple departments working together to ensure patients receive timely and appropriate care. This simulator provides a realistic representation of that workflow while allowing users to complete tasks, monitor risks, and improve admission readiness in an engaging and interactive environment.

The application is designed purely for **educational and training purposes**, helping users understand healthcare administration workflows through an intuitive UI.

---

# ✨ Features

### 🏥 Admission Setup
- Provider selection (Illustrative)
- Attending Physician
- Diagnosis selection
- Admission Type
- Prior Authorization Status
- Admission Date

---

### 📊 Dynamic Admission Readiness Score
- Live readiness calculation
- Circular progress indicator
- Weighted scoring model
- Real-time recalculation after every action

---

### ⚖️ Weighted Readiness Engine

| Category | Weight |
|----------|--------|
| Prior Authorization | 25% |
| Clinical Documentation | 20% |
| Physician Orders | 20% |
| Insurance Verification | 15% |
| Consent | 10% |
| Bed Availability | 10% |

Special logic ensures that ICU admissions with denied prior authorization cannot achieve a high readiness score until an appeal is successful.

---

### 📋 Prior Authorization Workflow

Supports multiple authorization scenarios:

- ✅ Approved
- ⏳ Pending
- ❌ Denied
- 📤 Appeal Submission
- ✔ Appeal Approval

Each path updates the readiness score and workflow progression dynamically.

---

### 📑 Initial Admission Analysis

Generates readiness between **30%–60%** and evaluates:

- Prior Authorization
- Insurance
- Bed Availability
- Documentation
- Physician Orders
- Consent

---

### ⚠️ Medical Necessity Criteria

For selected diagnoses such as:

- Acute Myocardial Infarction (MI)
- Congestive Heart Failure (CHF)

the simulator displays a clinical reminder highlighting **InterQual/Milliman medical necessity criteria** before utilization review.

---

### 📌 Workflow Actions

Complete administrative tasks including:

- 🛏 Assign Bed
- 🛡 Verify Insurance
- 📄 Upload Documentation
- ✍ Complete Consent
- 👨‍⚕️ Contact Physician
- 👩‍⚕️ Notify Nursing
- 🚑 Prepare Patient Arrival

Each completed task:
- Improves readiness
- Advances the workflow
- Updates the timeline
- Reduces operational risks

---

### ⏳ Interactive Admission Timeline

Visual workflow progression through:

- PA Review
- Insurance Verification
- Bed Assignment
- Documentation
- Consent
- Patient Arrival
- Registration
- Clinical Assessment
- Admission Complete

---

### 👥 Care Coordination Dashboard

Includes dedicated coordination panels for:

- 👨‍⚕️ Attending Physician
- 📋 Case Manager
- 👩‍⚕️ Nursing
- 📑 Utilization Review
- 🚑 Discharge Planner

The Utilization Review section highlights:

- Concurrent Review
- Denial Risk Identification
- Medical Necessity
- InterQual
- Milliman

---

### 🚨 Risk Tracking

Continuously evaluates:

- Documentation Risk
- Insurance Risk
- Bed Risk
- Clinical Risk

Clinical Risk receives additional weighting for:

- Acute MI
- CHF
- ICU Admissions

---

### 📈 Governance Snapshot

Unlocked when readiness exceeds **75%**.

Displays educational industry benchmarks including:

- Prior Authorization turnaround
- Estimated inpatient denial rates
- Administrative rework costs

---

### ✅ Final Admission Decision

Decision generated after workflow completion.

**Ready for Admission**
- Complete summary
- Care coordination status
- Timeline completion
- Risk assessment
- Readiness score

or

**Not Ready**
- Missing requirements
- Pending actions
- Remaining risks
- Recommended next steps

---

### 🎨 Additional Features

- Responsive Design
- Premium Healthcare UI
- Smooth Animations
- Progress Indicators
- Replay Simulation
- Generate New Case
- Export Summary
- Print Summary
- Dark Mode
- Modern Dashboard Layout

---

# 🛠 Tech Stack

- HTML5
- Tailwind CSS
- Vanilla JavaScript

---

# 🎯 Learning Outcomes

This project helped me explore how hospital admission workflows operate behind the scenes and how multiple administrative departments collaborate before a patient is officially admitted.

While building this simulator, I gained insights into:

- Prior Authorization workflows
- Healthcare documentation processes
- Insurance verification
- Utilization Review concepts
- Medical necessity criteria
- Care coordination
- Admission readiness scoring
- Interactive frontend design
- Workflow visualization using JavaScript

---

# 🚀 Future Enhancements

- Multi-patient management
- User authentication
- Electronic Health Record (EHR) integration
- Admission analytics dashboard
- Role-based access
- Real-time notifications
- Report generation
- Database connectivity
- API integration
- AI-powered admission recommendations

---

## 📸 Preview

*A responsive healthcare dashboard showcasing admission readiness scoring, workflow tracking, risk monitoring, care coordination, and final admission decision.*

---

## ⚠️ Disclaimer

This simulator is developed **solely for educational and learning purposes**.

All provider names, physician names, payer information, workflows, industry benchmarks, and clinical scenarios are **illustrative training data** and should **not** be used for real clinical, operational, or billing decisions.

---

⭐ If you found this project interesting, consider giving it a star and sharing your feedback!
