# Product Management Study Guide  
Concepts, artifacts, and practical structure

---

# 1. Product Strategy Artifacts

## 1.1 Vision Document

**Purpose:** Long-term direction (2–5 years)

### Structure
1. Target customer  
2. Core problem  
3. Desired future state  
4. Differentiation  
5. Strategic pillars  

### Example (Fitness App)

- **Target:** Busy professionals  
- **Problem:** Inconsistent workout habits  
- **Future:** Personalized 20-minute adaptive workouts  
- **Differentiation:** AI-adjusted routines based on fatigue  
- **Pillars:**
  - Personalization  
  - Habit reinforcement  
  - Community accountability  

---

## 1.2 Product Strategy Memo

**Purpose:** 12–24 month focus

### Structure
1. Market context  
2. Segmentation  
3. Key insight  
4. Strategic choices  
5. Investment themes  
6. Metrics  

### Example

- **Market:** Saturated fitness apps  
- **Segment:** Time-constrained professionals (30–45)  
- **Insight:** Consistency drives retention  
- **Choices:**
  - Focus on short sessions  
  - Avoid bodybuilding niche  
- **Themes:**
  - Habit streaks  
  - Smart reminders  
- **Metrics:**
  - 30-day retention  
  - Weekly active workouts  

---

## 1.3 Competitive Analysis

### Structure
1. Competitor list  
2. Feature matrix  
3. Pricing comparison  
4. Positioning map  
5. Differentiation gaps  

### Example Feature Matrix

| Feature               | Us  | Competitor A | Competitor B |
|-----------------------|-----|--------------|--------------|
| AI personalization    | Yes | No           | Partial      |
| Social sharing        | Yes | Yes          | Yes          |
| Adaptive intensity    | Yes | No           | No           |

Gap identified: fatigue-based adjustment.

---

# 2. Discovery Artifacts

## 2.1 Problem Brief

### Structure
1. User  
2. Problem  
3. Evidence  
4. Current workaround  
5. Business impact  

### Example

- **User:** Working parent  
- **Problem:** Skips workouts due to unpredictable schedule  
- **Evidence:** 68% churn after week 2  
- **Workaround:** Random YouTube workouts  
- **Impact:** Reduced retention lowers LTV  

---

## 2.2 Research Plan

### Structure
1. Objective  
2. Hypotheses  
3. Participants  
4. Interview guide  
5. Analysis method  

### Example

- **Objective:** Understand churn after week 2  
- **Hypothesis:** Workouts feel repetitive  
- **Participants:** 15 churned users  
- **Questions:**
  - Why did you stop?  
  - What frustrated you?  
- **Analysis:** Tag recurring themes  

---

## 2.3 Insight Repository

### Structure
- Tagged by persona  
- Tagged by frequency  
- Linked to opportunity areas  

### Example Themes
- “Too long”  
- “Hard to stay consistent”  
- “Reminders at wrong time”  

---

# 3. Product Definition Documents

## 3.1 PRD (Product Requirements Document)

### Structure
1. Overview  
2. Goals / Non-goals  
3. Personas  
4. User stories  
5. Functional requirements  
6. Non-functional requirements  
7. Edge cases  
8. Success metrics  
9. Risks  

### Example (Workout Reminder Feature)

**Overview:** Users forget to exercise.  

**Goal:** Increase weekly workout completion from 2.1 → 3.0  

**User Story:**  
As a busy professional, I want reminders at optimal times so I don’t miss workouts.

**Requirements:**
- AI determines reminder window  
- User can snooze  
- Maximum 2 reminders per day  

**Metrics:**
- Reminder open rate  
- Weekly workouts per user  

---

## 3.2 RFC (Request for Comments)

### Structure
1. Proposal  
2. Context  
3. Alternatives considered  
4. Tradeoffs  
5. Impact  

### Example

**Proposal:** Replace rule-based reminders with ML scheduling  

**Alternatives:**
- Static reminders  
- User-set reminders  

**Tradeoff:** Higher engineering cost vs improved personalization  

---

## 3.3 Technical Design Doc (Engineering-Owned)

### Structure
1. Architecture diagram  
2. Data flow  
3. APIs  
4. Scalability considerations  

PM validates scope and constraints.

---

# 4. Visual Artifacts

## 4.1 User Flow Diagram

### Structure
- Entry  
- Steps  
- Branches  
- Failure states  

### Example

Open App  
→ View Plan  
→ Start Workout  
→ Complete  
→ Log Feedback  

Failure branch:  
Start → Quit early → Prompt survey  

---

## 4.2 Journey Map

| Stage      | Action         | Emotion     | Friction                |
|------------|---------------|------------|--------------------------|
| Awareness  | Downloads app | Curious     | Too many options         |
| Week 1     | Tries workout | Motivated   | Intensity too high       |
| Week 2     | Skips session | Guilty      | Poor reminder timing     |

---

## 4.3 Wireframe

### Structure
- Header  
- Primary action  
- Supporting information  
- Secondary actions  

### Example Layout

Top: Today’s workout  
Middle: “Start Now”  
Bottom: Reschedule | Skip  

---

## 4.4 Prototype

Clickable flow:  
Home → Workout → Reminder setup → Confirmation  

Used for usability validation.

---

# 5. Backlog & Delivery

## Backlog Ticket Structure

**Title:** Smart Reminder Scheduling  

**Description:** Implement ML-based reminder timing  

**Acceptance Criteria:**
- Predict optimal time  
- Maximum 2 per day  
- User override available  

**Priority:** RICE = 1800  

**Dependencies:** ML service endpoint  

---

# 6. Prioritization Frameworks

## 6.1 RICE

\[
Priority = \frac{Reach \times Impact \times Confidence}{Effort}
\]

Example:

- Reach = 5000  
- Impact = 1  
- Confidence = 0.8  
- Effort = 2  

\[
Priority = 2000
\]

---

## 6.2 WSJF

\[
WSJF = \frac{Business\ Value + Time\ Criticality + Risk\ Reduction}{Job\ Size}
\]

Example:

- Business Value = 8  
- Time Criticality = 9  
- Risk Reduction = 7  
- Job Size = 8  

\[
WSJF = 3
\]

---

# 7. Metrics & Experimentation

## 7.1 Experiment Brief

### Structure
1. Hypothesis  
2. Variant vs Control  
3. Success metric  
4. Guardrail metrics  
5. Sample size  
6. Decision rule  

### Example

**Hypothesis:** Shorter workouts increase completion  

**Variant:** 15-minute sessions  
**Control:** 30-minute sessions  

**Success Metric:** Completion rate  

**Guardrail:** Satisfaction score  

**Decision Rule:** Ship if completion improves >5% without satisfaction decline  

---

# 8. Growth

## 8.1 Growth Loops

Growth loops create compounding acquisition.

### Example (Content Platform)

1. User creates content  
2. Content shared  
3. New users sign up  
4. New users create content  

Loop repeats.

Used effectively by TikTok.

---

## 8.2 A/B Testing

### Principles

- One variable at a time  
- Predefined success metric  
- Statistical significance  
- Clear rollout threshold  

### Example

Shorter onboarding flow  

Result: +12% completion rate  

Roll out to all users.

---

# 9. Case Study: Ride Completion

## Scenario

Increase ride completion rate at Uber.

---

## Step 1: Define Funnel

Search → Match → Pickup → Dropoff  

Completion rate = Dropoffs / Searches  

---

## Step 2: Identify Friction

Elevated cancellations at pickup stage.

---

## Step 3: Hypothesis

ETA inaccuracy increases cancellations.

---

## Step 4: Experiment

Improve ETA prediction model.  
Deploy to treatment group.

---

## Step 5: Result

Ride completion increases by 5%.

---

## Applied Framework

- Clear metric  
- Funnel analysis  
- Root cause hypothesis  
- Controlled experiment  
- Measured impact  
