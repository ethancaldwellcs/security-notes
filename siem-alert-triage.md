## SIEM Alert Triage (Notes)

SIEM alerts are signals, not conclusions.

Early in my career, I treated alerts as problems to be solved instead of starting points for understanding. That led to a lot of wasted time.

### Common early mistakes

Things I’ve seen repeatedly (and done myself):
- Treating alerts in isolation
- Ignoring baseline behavior
- Assuming severity based on alert labels
- Escalating before building a coherent picture

Most alerts look scary without context. Context is usually missing from the SIEM itself.

### Baseline matters more than rules

Understanding what’s normal for a system is more useful than understanding the detection logic.

Questions I try to answer:
- Is this system noisy by default?
- Does this user or service account behave like this regularly?
- Is this happening once or repeatedly?
- Is there supporting evidence elsewhere?

The same alert can mean very different things in different environments.

### When to escalate

Escalation doesn’t require certainty, but it does require clarity.

Before escalating, it helps to be able to explain:
- What triggered the alert
- What you checked
- What seems abnormal
- What the potential impact might be

Escalating with no context creates noise. Waiting too long creates risk. Finding the balance takes time and repetition.
