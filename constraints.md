# COMBATUS OS — SYSTEM CONSTRAINTS

## 1. PURPOSE
Constraints define hard limits of system behavior.

They prevent overcomplexity and uncontrolled expansion.

---

## 2. CORE LIMITS

- Only 1 active goal at a time
- Only 1 executable action at a time
- All actions must be ≤ 2 minutes
- No parallel decision threads

---

## 3. COGNITIVE LIMITS

- No open-ended analysis
- No multi-option evaluation loops
- No abstraction without execution path

---

## 4. STRUCTURAL LIMITS

- Every system layer must reduce complexity
- No new layers without execution necessity
- No redundancy across modules

---

## 5. PROCESS LIMITS

- Every decision must end in action
- Every action must map to physical execution
- No planning-only states allowed

---

## 6. FAILURE RULE
If constraints are violated:
→ simplify system
→ remove optionality
→ return to micro-step execution

---

## 7. SYSTEM ROLE
Constraints = boundary layer that protects execution integrity