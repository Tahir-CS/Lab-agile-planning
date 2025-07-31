
## 🧩 User Story

As a user,  
I need the counter value to persist after I close and reopen the app,  
So that I don’t lose my progress when restarting the app.

---

## ✅ Acceptance Criteria (Gherkin Syntax)

```gherkin
Given the counter has been incremented to a certain value,
When I close and restart the app,
Then the counter should still display the same value as before restart.
