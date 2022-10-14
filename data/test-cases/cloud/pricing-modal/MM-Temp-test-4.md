---
# (Required) Ensure all values are filled up
name: "Cloud | should show Upgrade button in global header for admin users on starter plan"
status: Active
priority: Normal
folder: pricing modal
authors: "@yasserfaraazkhan"
team_ownership: 
- Self-Serve

# (Optional)
component: null
priority_p1_to_p4: P2 - Core Functions (Do core functions work?)
location: null
tags: []
labels: []

# (Optional) Test type and tools
cypress: null
detox: null
mmctl: null
playwright: null
rainforest: []
manual_test_environments: []

# Do not change
id: null
key: null
created_on: null
last_updated: null
case_hashed: null
steps_hashed: null
---

## Change Test Title

---

**Step 1**

Pre-condition:

- should have requested a professional trial before
- should login with admin account

Test Steps:

1: Verify 'Upgrade' button is visible when Channel is visited.
2: Logout and login with user accout
3: Verify 'Upgrade' button is not visible

**Expected**

1: Verify pricing modal opens up.
2: Expect Entriprise section should have 'contact sales' button.
3: Expect 'Upgrade' button should not be visible.