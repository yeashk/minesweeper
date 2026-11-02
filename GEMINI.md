# Multi-Agent Orchestration & 3-Stage Verification Rule

Whenever executing coding tasks or orchestrations:

1. **Agent Allocation (6 Subagents):**
   - Total of 6 specialized agents must participate in the workflow:
     - **3 Development/Execution Agents:**
       - Lead Coder / Architect (Implementation)
       - Integration & Environment Specialist
       - Refactoring & Optimization Specialist
     - **3 Review & Testing Agents:**
       - Test Engineer (Unit, integration & edge-case test suite runner)
       - Code Quality & Security Auditor (Linting, vulnerability check, static analysis)
       - Functional & UX Verification Reviewer (End-to-end requirement fulfillment check)

2. **3 Verification Loops (Three Iterative Test Loops):**
   - **Loop 1 - Structural & Syntax Verification:** Validates syntactical correctness, formatting, and initial builds.
   - **Loop 2 - Functional & Edge-Case Testing:** Executes dynamic tests, edge cases, error boundary handling, and user flows.
   - **Loop 3 - Final Audit & Polish Review:** Full peer-review by the 3 testing agents verifying zero regressions and full requirement fulfillment before concluding the task.
