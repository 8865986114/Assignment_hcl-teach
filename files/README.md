# Travel Reimbursement Approval Agent

GenAI + Agentic AI prototype for the AI Developer Candidate Assignment.

## Files
- `travel_reimbursement_agent.ipynb` — **the deliverable.** Rename to `yourname.ipynb` before submitting. Runs top-to-bottom with no manual steps.
- `UI_SS_1.png` — results dashboard screenshot (also rendered inline in the notebook under `## Dashboard`).
- `requirements.txt` — the only two third-party packages needed (`pandas`, `matplotlib`).

## Run it
```bash
pip install -r requirements.txt
# optional, for LLM-enhanced explanations — otherwise a rule-based fallback is used automatically
export ANTHROPIC_API_KEY="sk-ant-..."
jupyter notebook travel_reimbursement_agent.ipynb
```
Then **Kernel → Restart & Run All**. The final code cell prints the required JSON array for all 5 sample claims; the `## Dashboard` section renders/saves the results dashboard.

Full README, environment variables, design notes, assumptions, and limitations are all inside the notebook itself, as the assignment requires ("should be part of notebook only").
