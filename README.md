# ActNow — Emergency & Safety HCI Prototype

Εργασία Εξαμήνου στο μάθημα **Human-Machine Interfaces (2026–2027)**  
**Επιλεγμένο Θέμα:** #4 Emergency & Safety — *Act Now*

---

## Κανόνες Ασφαλείας & Συνεργασίας (Υποχρεωτικοί για όλη την ομάδα)

1. **Zero Real Personal Data (PII):** Απαγορεύεται αυστηρά η καταχώριση πραγματικών ονομάτων, τηλεφώνων, διευθύνσεων, ΑΕΜ ή πραγματικών συντεταγμένων GPS σε κώδικα, Personas και αρχεία αξιολόγησης. Χρησιμοποιούμε μόνο ανώνυμους κωδικούς (`P1–P5`) και δημόσια σημεία αναφοράς (π.χ. *Πλατεία Ελευθερίας, Σέρρες*).
2. **Zero API Keys / Secrets:** Δεν ανεβάζουμε ποτέ API keys. Ο χάρτης υλοποιείται με SVG/CSS ή keyless βιβλιοθήκη (Leaflet + OpenStreetMap).
3. **Απομόνωση Αρχείων (Zero Merge Conflicts):** Κάθε μέλος δουλεύει **αποκλειστικά** στο δικό του branch και τροποποιεί **μόνο** τα αρχεία που του αντιστοιχούν.
4. **Pull Request Review:** Κανείς δεν κάνει push απευθείας στο `main`. Κάθε αλλαγή περνάει από Pull Request με `Closes #<issue_number>` και απαιτεί 1 έγκριση (Approve) πριν το Merge.

---

## Κατανομή Ομάδας & Branches (7 Μέλη)

| Μέλος | Ρόλος | Branch | Αρχεία Ιδιοκτησίας |
| :--- | :--- | :--- | :--- |
| **M1 (PM)** | Project Lead & Requirements | `docs/problem-reqs` | `report-sections/01-problem-reqs.md` |
| **M2** | UX Research (Personas & Journey) | `docs/personas-journey` | `report-sections/02-personas-journey.md` |
| **M3** | Flow 1: Critical Alert & Checklist | `feat/flow1-alert` | `wireframes/flow1.png`, `prototype/flow1-alert.html` |
| **M4** | Flow 2: Safe Zone Map | `feat/flow2-map` | `wireframes/flow2.png`, `prototype/flow2-map.html` |
| **M5** | Flow 3: SOS 112 & Safe Check-In | `feat/flow3-sos` | `wireframes/flow3.png`, `prototype/flow3-sos.html` |
| **M6** | User Evaluation & SUS | `eval/testing-kit` | `evaluation/test-protocol-and-data.md` |
| **M7** | HCI Matrix, Redesign & PPT | `design/slides-and-hci` | `report-sections/03-hci-decisions.md`, `presentation/` |

---

## Κλειδωμένα Tasks Αξιολόγησης (Usability Testing)

1. **Task 1 (Flow 1):** Εντοπισμός ενεργού συναγερμού σεισμού και ολοκλήρωση των 3 άμεσων βημάτων προστασίας.
2. **Task 2 (Flow 2):** Εντοπισμός του πλησιέστερου ανοιχτού σημείου συγκέντρωσης και έναρξη ασφαλούς πλοήγησης.
3. **Task 3 (Flow 3):** Ασφαλής ενεργοποίηση κλήσης έκτακτης ανάγκης `112` (χωρίς τυχαίο πάτημα) και αποστολή επιβεβαίωσης «Είμαι Ασφαλής».
