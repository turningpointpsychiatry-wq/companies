---
name: Mental Health Private Practice
description: A complete AI-powered mental health private practice with specialized agents across clinical operations, patient intake, billing, scheduling, compliance, and care coordination.
slug: mental-health-practice
schema: agentcompanies/v1
version: 1.0.0
license: MIT
authors:
  - name: turningpointpsychiatry-wq
  - goals:
  -   - Deliver high-quality mental health care through coordinated, efficient AI-assisted operations
      -   - Streamline patient intake, scheduling, and follow-up to reduce administrative burden
          -   - Ensure HIPAA compliance and ethical standards across all operations
              -   - Support clinicians with documentation, billing, and care coordination
                  -   - Provide responsive, compassionate patient communication at every touchpoint
                      - metadata:
                      -   sources: []
                      -   ---

                      # Mental Health Private Practice

                      A complete AI-powered mental health private practice with specialized agents across 5 divisions — clinical operations, patient services, billing & compliance, scheduling, and care coordination.

                      ## How It Works

                      The Practice Director oversees all operations through a hub-and-spoke model. Division leads manage their teams autonomously. For complex patient cases or operational challenges, agents coordinate through structured handoffs and quality gates.

                      ## Divisions

                      - **Clinical Operations (4 agents)** — Practice Director, Clinical Supervisor, Documentation Specialist, Quality Assurance Coordinator
                      - - **Patient Services (4 agents)** — Intake Coordinator, Patient Advocate, Crisis Triage Specialist, Patient Follow-Up Coordinator
                        - - **Billing & Compliance (3 agents)** — Billing Specialist, Insurance Verification Agent, HIPAA Compliance Officer
                          - - **Scheduling (2 agents)** — Scheduling Coordinator, Waitlist Manager
                            - - **Care Coordination (3 agents)** — Care Coordinator, Referral Manager, Treatment Plan Coordinator
                             
                              - ## Leadership
                             
                              - | Role | Slug | Reports To |
                              - |------|------|-----------|
                              - | Practice Director | practice-director | — |
                              - | Clinical Supervisor | clinical-supervisor | practice-director |
                              - | Patient Services Lead | intake-coordinator | practice-director |
                              - | Billing & Compliance Lead | billing-specialist | practice-director |
                              - | Scheduling Coordinator | scheduling-coordinator | practice-director |
                              - | Care Coordinator | care-coordinator | practice-director |
                             
                              - Generated with the company-creator skill from Paperclip
