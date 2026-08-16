# Project Submission Report

## 1. Student Details

- **Full Name:** Princess Imelda Odato Sidai 
- **GitHub Username:** princessimelda
- **Email:** princess.sidai@strathmore.edu

---

## 2. Deployed Project Link

- **Live GitHub Pages URL:** https://is-project-2026.github.io/HabitTracker-122839/

---

## 3. Reflection — Grounded in Your Git History
### A. Your Best Commit
- **Commit URL:** https://github.com/IS-PROJECT-2026/HabitTracker-122839/pull/14
- **Why this one?** I struggled a lot navigating how to deploy on both github pages and vercel. I tried over and over to deploy on vercel until I realised I couldn't integrate it on my end because my project is under an organisation of which I have no admin controls. After that realisation, I had to fix the deployment on github pages given that it wasn't rendering as expected. I kept getting a 404 error, the page was pointing to the wrong destination, everything was falling apart, even my fixes. Until I realised that re-ploying could fix it or running the workflow again after fixing the issue. This was a rough ride for me.

### B. A Mistake or Struggle
- **Link to the evidence:** https://github.com/IS-PROJECT-2026/HabitTracker-122839/pull/1
- **I had two main, an origin main and my main. Every time I tried to commit and push I was getting errors over and over. All I had to do was fix the HEAD to point to the correct main. 

### C. A Pull Request You're Proud Of
- **PR URL:** https://github.com/IS-PROJECT-2026/HabitTracker-122839/pull/19
- **What did you check before merging?** I am proud of this because it took two merge conflicts and resolutions to get into the groove of merge conflicts, then still getting it wrong on my third merge conflict. I'm proud of this one because despite my mistake, I navigated it step my step to track where I went wrong, made corrections, and fixed the merge conflict as expected. 

### D. One Thing You Would Do Differently

If you had to restart this project from scratch with everything you know now, name one specific workflow decision you would change.

- **What would you change?** I know we've been taught to use kanban to manage our project but I wouldn't use it in future projects. It doesn't work for me and the flow my mind is used to. An iterative approach would work better for me since I like to work in sequential steps that are in a sort of domino effect. 
- **Link to the evidence of the original decision:** https://github.com/orgs/IS-PROJECT-2026/projects/194

---

## 4. Screenshots of Key GitHub Features

### A. Milestones and Issues

<img width="1680" height="1050" alt="milestones" src="https://github.com/user-attachments/assets/2dba0847-de7a-494f-885f-615381b6be38" />

<img width="1680" height="1050" alt="issues" src="https://github.com/user-attachments/assets/fa7b58b1-6764-4cd7-8339-df0c526c0585" />


* **Caption:** My milestone were group into 3 goals then aligned with issues that fall into helping achieve each of the goals.

### B. Project Board

<img width="1680" height="1050" alt="projectboardpostcompletion" src="https://github.com/user-attachments/assets/2512a3e9-eafc-4d5f-84d8-7bfc37273cae" />


* **Caption:** This is my project board after completion of the project. The issues weren't approached linearly but all were completed. 

### C. Branching Architecture

<img width="813" height="1004" alt="branchingarchitecture" src="https://github.com/user-attachments/assets/2913838d-0ac0-4f0f-8929-233ecff46c34" />

* **Caption:** The source control graph shows evidence of various actions I took - doc, chore, feature, style, design, refactor.

### D. Pull Requests & Traceability

<img width="1680" height="1050" alt="pullrequests" src="https://github.com/user-attachments/assets/f1ed2401-a866-4c4d-a357-669c08580af7" />


* **Caption:** In the description of the pull requests before merging, the issue aligned with the request was included to help keep track of which issues were being resolved. 

---

## 5. Merge Conflict Evidence
---

### Conflict 1 — Full Chronology

**What cause did you use?** Two different branches altering the same line of code

#### Step 1: Generating the Clash

<img width="1680" height="1050" alt=":evidence:conflict_evidence_1" src="https://github.com/user-attachments/assets/8f6b6fb6-5ae8-464f-b908-40facb85b417" />

* **Caption:** The refactor/merge-conflict-1a and refactor/merge-conflict-1b branches both changed the same line in src/App.jsx. When the branches were merged, Git couldn't determine which change to keep and reported a content merge conflict.

#### Step 2: Inside the Code Editor (Conflict Markers)

* **Caption:** The conflict occurred because both branches changed the same line differently. The Merge Editor was used to compare the two versions, and the version from branch refactor/merge-conflict-1b was selected as the final version.

#### Step 3: Resolution & Clean Merge

* **Caption:** The conflict was resolved in the Merge Editor. The resolved src/App.jsx was staged, and the merge was completed with a commit.

---

### Conflict 2 — Different Cause

**What cause did you use?** A modify/delete conflict

**Why does this cause trigger a conflict?** It occurs when one branch modifies a file while another branch deletes the same file. Git can't determine whether the file should be kept with the modification or deleted.

<img width="1461" height="421" alt=":evidence:conflict_evidence_2" src="https://github.com/user-attachments/assets/3e4a08b0-c79d-4b07-a296-5a392bdfd7e6" />

<img width="1461" height="576" alt=":evidence:conflict_evidence_2 1" src="https://github.com/user-attachments/assets/8a68e942-e8d9-4668-81e5-98eb0e72b54d" />

* **Caption:** The refactor/conflict-2-modify and refactor/conflict-2-delete branches conflicted over the README.md file. The modify branch updated the README while the delete branch removed it, causing a modify/delete conflict. The conflict was manually resolved and committed.

---

### Conflict 3 — Different Cause

**What cause did you use?** A modify/delete conflict with a renamed file

**Why does this cause trigger a conflict?** [1–2 sentences explaining the mechanism]

<img width="1680" height="1050" alt=":evidence:conflict_evidence_3" src="https://github.com/user-attachments/assets/b3807905-2f86-4e9d-981e-99fbbd107dfe" />

* **Caption:** One branch renamed the original src/index.css, while the other branch modified the original src/index.css. Git couldn't determine how to combine the rename and modification, resulting in a modify/delete conflict.

---
##
## 6. Feedback & Evaluation

To help improve this course for future engineering cohorts, please take 2 minutes to fill out the anonymous feedback form. Your honest review helps shape how this program is taught next semester!
- [ ] **Anonymous Evaluation Form:** [Course & Instructor Evaluation](https://forms.gle/YLybnsyXXErKEg3s9)

---
 
## Final Submission
 
Once your repository is complete, submit your work through the official submission form below. The form will **stop accepting responses after Monday, August 17th, 2026** — no late submissions will be accepted.
 
> **Submission Form:** [https://forms.gle/KrT4VxtFtkU3wtYu8](https://forms.gle/KrT4VxtFtkU3wtYu8)
