# AImReady

*Business and Project Management Project, University of Pisa*

An **AI-powered virtual exam panel** that helps university students prepare for oral exams.

**Team:** Dario Falaschi, Leonardo Lentini, Chiara Nasoni, Vittoria Vellutini

## 📄 Documents

- [`AImReady_Report.pdf`](AImReady_Report.pdf): full report
- [`AImReady_Presentation.pdf`](AImReady_Presentation.pdf): presentation slides

## The problem

Many students underperform in oral exams because of anxiety and the lack of objective feedback. Practising in front of a mirror or with family gives no measurable signal and no real exam pressure. In a study on 210 first-year health-science students, **89%** reported moderate-to-high stress before exams.

## The idea

Students upload their own course material and take a simulated oral exam through their browser's webcam and microphone, in front of a panel of three AI agents:

| Agent | Model | Role |
|---|---|---|
| **Lead Examiner** | GPT-4o-mini | Asks the main questions in a calm, structured way and drives the exam |
| **Assistant Examiner** | Llama 3.1 8B | Jumps in with faster, more direct follow-up questions |
| **Silent Coordinator** | Claude Haiku | Never speaks: reads the transcript and delivery metrics (pauses, speech rate, fillers) and paces the other two |

After the exam the student gets a report on content accuracy, clarity, speech delivery and non-verbal signals, with a concrete suggestion for each.

Facial analysis runs in the browser and only numerical scores reach the backend. The system never infers emotions, so it stays within the EU AI Act exemption for training simulations.

## The business

- **Competition:** coaches like Yoodli and Poised, VR trainers, tutoring. None of them combines objective metrics, real exam pressure and a cost that scales.
- **Business model:** freemium for students (free tier, "Exam Pass" at €8–9 for 5 full sessions) and a per-student license for universities (~€3 per year).
- **Costs:** about $0.55 for a 30-minute session, 90% of it for voice generation.
- **Market:** 1.4M students in the target fields in Italy. Year 1 closes at +€39.5K thanks to a license with the University of Pisa, and break-even needs about 4 university licenses.
- **Validation:** interviews, surveys, landing page and MVP, then an 8–12 week pilot at the University of Pisa.
- **Risks:** changes to the AI Act, competitors adding an exam mode, low adoption, rising voice API costs, each with a fallback plan.

**Turning exam-day panic into practiced confidence.**
