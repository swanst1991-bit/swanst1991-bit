# Webio Bot Flows for Vuln Customers
## 2025-11-15
- **Flow: Financial Stress Detection** (Aryza AI, May 2025)
  - Trigger: Customer says “can’t cope” or “stressed.”
  - Response: “I’m here to help—can we discuss a payment break?”
  - Action: Escalate to agent, tag as vuln.
  - JSON (Webio builder):
    ```json
    {
      "trigger": ["can't cope", "stressed"],
      "response": "I'm here to help—can we discuss a payment break?",
      "escalate": true,
      "tag": "vulnerable"
    }
