### Teacher Portal (Analyzer + Decision Maker)
Dashboard (Overview)
KPIs: Total students, Average score, Attendance %, High-risk count
AI quick insights: 3–6 bullets like:
“Class average dropped in Algebra (Unit 3) after Test-2”
“8 students show low mastery + low attendance — prioritize interventions”
Students (Performance)
Subject-wise marks + test history
Weak vs strong topics per student
Comparison charts (student vs class avg, trend over time)
Learning Gaps (Core Feature)
For each student and for the class:

Topic-wise weakness map
Concept mastery level (e.g., Mastered / Developing / Needs Work)
AI suggestions (actionable):
“Struggles in Algebra → Linear equations & factoring”
“Needs practice in Trigonometry → identities + application problems”
Recommended next steps: targeted worksheets, re-test suggestions, peer grouping
Attendance
Daily/weekly views, patterns (frequent absentees)
Low attendance alerts (threshold-based + trend-based)
Risk Detection System
High / Medium / Low risk classification driven by:
Marks trend + topic mastery
Attendance trend
Assignment submission consistency
Alerts & Notifications
Bulk warnings (demo email/message)
Parent notification (demo workflow)
Reports & Export
PDF report cards + class summaries
Export performance + attendance + risk lists
### Student Portal (Self-Improvement + Awareness)
Dashboard
Score, attendance, overall performance, optional rank
My Performance
Score-over-time graph
Subject breakdown + test analysis
Learning Gaps (Differentiator)
Weak topics + why they’re weak (miss patterns)
Suggested plan: “what to practice next + how much + by when”
Attendance
Attendance %, missed classes list, warning if low
Assignments
Pending, submitted, late, completion %
Feedback + AI Assistant
Teacher remarks
Personalized AI feedback:
“Focus on Algebra Unit 2; do 20 mixed problems/day”
“You’re improving in Geometry; keep momentum with weekly quizzes”
### The “Learning Gap + Risk” engine (simple but judge-friendly)
Mastery scoring (per topic)
Compute a topic mastery score (0–100) using:

Correctness on questions tagged to that topic
Recency weighting (recent tests matter more)
Penalty for repeated misconception patterns (same error type)
Then map to labels:

80–100: Mastered
55–79: Developing
0–54: Needs Work
Risk scoring (per student)
A weighted score such as:

Marks trend (40%)
Attendance (35%)
Assignments (25%)
Then classify:

High risk: ≥ 70
Medium: 40–69
Low: < 40
AI outputs (what the LLM should generate)
Teacher insight: “Who is at risk, why, and what to do next”
Student direction: “What to practice next + realistic plan”
### Clean tab structure (matches your UI)
Teacher tabs
Dashboard, Students, Learning Gaps, Attendance, Alerts, Reports, AI Assistant
Student tabs
Dashboard, My Performance, Learning Gaps, Attendance, Assignments, Feedback, AI Assistant
### If you want, I can implement this next
I can turn this into a working Next.js app with:

Teacher/Student role-based login
Seed dataset (students, tests, topic tags, attendance, assignments)
Learning-gap + risk scoring
AI chat + AI “quick insights”
PDF export (reports)
