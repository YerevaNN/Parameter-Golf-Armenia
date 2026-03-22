# Parameter Golf Armenia — YSU Compute Access

**Organizers:** YSU, YerevaNN, Eleveight  
**Competition:** March 24 – April 30, 2026  
**Main goal:** Support participants from Armenia in the [OpenAI Parameter Golf](https://github.com/openai/parameter-golf) competition.

---

## The Project

**OpenAI Model Craft: Parameter Golf** is an open research challenge to train the best language model under extreme constraints. Participants minimize held-out loss (bits per byte) on the FineWeb validation set while staying within a 16 MB artifact limit (weights + training code) and a 10-minute training budget on 8×H100 GPUs. Submissions are made via GitHub pull requests to the [official repository](https://github.com/openai/parameter-golf). The challenge rewards creativity in architecture, compression, and optimization.

**Important:** The OpenAI competition is not standard—not every submission appears on the leaderboard. [Only submissions that advance state-of-the-art at the time of submission are recorded](https://github.com/openai/parameter-golf?tab=readme-ov-file#leaderboard). The leaderboard is competitive and selective.

OpenAI partners with Runpod to offer compute credits to participants worldwide. **Parameter Golf Armenia** provides an alternative: YSU supercomputer access for Armenia residents who register for compute. YSU, YerevaNN, and Eleveight jointly organize the Armenia track; Eleveight sponsors the compute allocation, coordination, and prizes. **YSU compute is optional**—every Armenia resident is eligible for the prize regardless of whether they use YSU compute.

---

## Submission Requirements for Prize Eligibility

Armenia residents must submit their solutions through the **solution submission form** by **May 1st** to be considered for the prizes. **Format:** GitHub link or code archive.

Participants may upload as many submissions as they want. Organizers will consider the **latest submission** by April 14th for the intermediate assessment, and the **latest submission** by May 1st for the final prize.

**April 14th intermediate assessment (optional):** Participants are encouraged to submit by April 14th to receive an intermediate assessment on a **blind multilingual dataset** (including Armenian). Organizers provide the corresponding tokenizer. The intermediate leaderboard is announced on April 18. This gives early feedback before the final deadline. The same dataset is used for the internal evaluation in Scenario B (see below).

---

## Prize (500,000 AMD — Eleveight)

### Scenario A: One or more Armenia submissions on the OpenAI leaderboard

If by the end of the competition (April 30) one or more submissions from Armenia appear on the [official OpenAI leaderboard](https://github.com/openai/parameter-golf?tab=readme-ov-file#leaderboard), the author of the best Armenia result gets the **500,000 AMD** prize, sponsored by Eleveight.

### Scenario B: No Armenia submission on the OpenAI leaderboard

If no participant from Armenia makes the OpenAI leaderboard, organizers run an **internal evaluation**:

- Training and validation sets are **different** from OpenAI’s (FineWeb)
- The validation set is the **same blind multilingual dataset** used for the April 14th intermediate assessment; it contains multilingual text, including Armenian
- Organizers provide the corresponding tokenizer
- The author of the best-performing model on this validation set gets the 500,000 AMD prize

**Disqualification:** Solutions that are copies or reimplementations of publicly available solutions (from the OpenAI GitHub or leaderboard) are disqualified. We encourage unique and creative solutions. Whether a solution is a copy or reimplementation is determined by the organizers (YSU, YerevaNN, Eleveight).

---

## Additional Prize & Benefits

- **Most creative solution:** There may be an additional prize for the most creative solution, as determined by the organizers. (Details to be determined.)
- **Compute credits:** Winners may receive compute credits from Eleveight. (Subject to Eleveight’s decision.)

---

## YSU Compute Allocation per Participant (Optional)

Participants who want YSU compute access must fill the **registration form** (below). Compute is **optional**—it is not required for prize eligibility.

| Tier | GPU-hours | Use case |
|------|-----------|----------|
| **Standard** | 20 | Experimentation + multiple 10-min runs on 8×H100 |

**Allocation:** 20 GPU-hours per registered participant. Participants may use it as:
- 20 hours on 1×H100 for development and debugging, or
- 2.5 hours on 8×H100 for up to 15 full competition runs (10 min each), or
- Any combination (e.g., 10h on 1×H100 + 1.25h on 8×H100).

**Important:** Compute is provided through the **Slurm queue**, which does not guarantee immediate availability. Your job may wait in queue before starting. GPU-hours are charged **only for time actually running on Slurm**—time spent coding, debugging, or waiting for jobs does **not** count against your allocation. Allocation is granted once per participant for the duration of the competition.

**Misuse:** If organizers detect that compute is being used for purposes other than the Parameter Golf competition, the participant will be **banned permanently** from the competition and from future compute access.

---

## Eligibility

**Participants must be residents of Armenia.** Proof of residence (e.g., address, employment contract, or enrollment at an Armenian educational institution) is required. Only one person is considered per submission.

---

## Registration — Google Form Fields (Compute Access)

Participants who want YSU compute access must complete this form.

### Section 1: Identity

| Field | Type | Required | Notes |
|-------|------|----------|-------|
| Full name | Short answer | Yes | As it will appear on the leaderboard |
| Email | Short answer | Yes | Primary contact |
| GitHub username | Short answer | Yes | Must match the account used for Parameter Golf submissions |
| Proof of residence in Armenia | File upload or Short answer | Yes | Address, employment contract, or enrollment certificate |
| Affiliation | Short answer | No | University, company, or "Independent" |

### Section 2: Eligibility

| Field | Type | Required | Notes |
|-------|------|----------|-------|
| I confirm I am not working in a company which has its headquarters in a D:5 country | Checkbox | Yes | Must check to proceed. See FAQ for list of D:5 countries. |
| I would like YSU compute access | Checkbox | Yes | Must check (this form is for compute registration) |

### Section 3: Technical (Optional)

| Field | Type | Required | Notes |
|-------|------|----------|-------|
| Current role | Dropdown | No | Undergrad / Grad / Industry / Other |
| Have you cloned the Parameter Golf repo? | Multiple choice | No | Yes / No / Not yet |
| Anything else we should know? | Paragraph | No | Free text |

---

## Solution Submission Form (by May 1st)

Participants must submit their solutions through a separate form by **May 1st** to be considered for the prizes. **Format:** GitHub link or code archive. Organizers consider the latest submission by May 1st. The form will include identity and proof of residence in Armenia. (Form fields and link to be added.)

---

## Timeline

| Date | Event |
|------|-------|
| March 24 | Parameter Golf opens (OpenAI) |
| Late March | Registration opens; kickoff workshop |
| April 14 | **Optional:** Submit for intermediate assessment on blind multilingual dataset (latest submission considered) |
| April 18 | AI Conference — Armenia track announced; intermediate leaderboard announced |
| April 30 | OpenAI competition ends |
| May 1 | **Deadline:** Submit solution for prize consideration (latest submission considered) |
| May (TBD) | Internal evaluation (if Scenario B); winner verified; prize awarded |

---

## FAQ

**Who is eligible for the Armenia track and the prize?**  
Armenia residents only. Proof of residence (address, employment, or enrollment at an Armenian educational institution) is required. Only one person per submission.

**What happens if no one from Armenia gets on the OpenAI leaderboard?**  
Organizers run an internal evaluation on a multilingual validation set (including Armenian). The best-performing model wins the 500,000 AMD prize. Solutions that are copies or reimplementations of public solutions are disqualified.

**How do I submit my solution for prize consideration? What format?**  
Submit via the solution submission form by May 1st. Provide a GitHub link or code archive.

**What is the deadline for the solution submission form?**  
May 1st. Organizers consider your latest submission by that date.

**What is the April 14th intermediate assessment, and is it required?**  
Optional. If you submit by April 14th, your latest submission will be evaluated on the same blind multilingual dataset used in Scenario B. This gives you early feedback before the final deadline.

**Can I submit a solution that is based on or reimplements a public approach from the OpenAI leaderboard?**  
No. Copies and reimplementations of publicly available solutions are disqualified in Scenario B (internal evaluation). We encourage unique and creative solutions.

**How is "most creative solution" determined?**  
By the organizers (YSU, YerevaNN, Eleveight). Details to be determined.

**When will the prize be awarded?**  
After the competition ends (April 30) and evaluation is complete. Exact date TBD.

**What compute do I get access to, and for how long?**  
20 GPU-hours on YSU (H100 GPUs). Compute is provided via Slurm; hours are charged only for time actually running on Slurm (not coding or queue wait time). Slurm does not guarantee immediate availability. Allocation is granted once per participant for the duration of the competition.

**Do I need to use YSU compute to be eligible for the prize?**  
No. YSU compute is optional. Every Armenia resident is eligible for the prize regardless of compute source.

**Where is the solution submission form?**  
(Link to be added.)

**If I collaborate with others, who receives the prize?**  
Only one person is considered per submission. The team should designate a single recipient when submitting.

**What are D:5 countries, and why does my employer matter?**  
Participants must confirm they are not working for a company headquartered in a D:5 (sanctioned/restricted) country. This requirement applies to both compute access and prize eligibility. **Example:** A student enrolled at an Armenian university who also works at an Armenian branch of a Russian company cannot get compute access—the company headquarters is in a D:5 country (Russian Federation). If such a violation is detected, the person will be banned from the competition.

**D:5 countries** (company headquarters in these countries disqualifies from compute access and prize): Afghanistan, Belarus, Cameroon, Central African Republic, Cuba, Haiti, Iran, Iraq, Israel, Kenya, Lebanon, Libya, Mali, Mozambique, Myanmar, Nigeria, North Korea, Palestinian Territories, Republic of Congo, Russian Federation, Russia-occupied or annexed regions of Ukraine (including Crimea, Donetsk, Kherson, Luhansk, Sevastopol, Zaporizhzhia), Somalia, Sudan, South Sudan, Syria, Venezuela, Yemen, Zimbabwe.

**What happens if I use the compute for something other than the competition?**  
Compute is for Parameter Golf only. If organizers detect misuse, the participant will be banned permanently from the competition and from future compute access.

---

## Contact

Questions: https://github.com/YerevaNN/Parameter-Golf-Armenia/issues
