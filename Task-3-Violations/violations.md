# Task 3 - Identify Constraint Violations

This task shows examples where the railway level-crossing safety constraints are violated.

## Violation 1 - C1

**Constraint:** `T → ¬B`

**Scenario:**

* `T = TRUE`
* `B = TRUE`

**What went wrong?**

The train is present, but the barrier is open. This violates C1 because the barrier must not be open while a train is present.

---

## Violation 2 - C2

**Constraint:** `A → C`

**Scenario:**

* `A = TRUE`
* `C = FALSE`

**What went wrong?**

The train is approaching, but the barrier is not closed. This violates C2 because the barrier must close when a train approaches.

---

## Violation 3 - C3

**Constraint:** `A → W`

**Scenario:**

* `A = TRUE`
* `W = FALSE`

**What went wrong?**

The train is approaching, but the warning lights are OFF. This violates C3 because the warning lights should be ON to warn drivers.

---

## Violation 4 - C4

**Constraint:** `A → L`

**Scenario:**

* `A = TRUE`
* `L = FALSE`

**What went wrong?**

The train is approaching, but the audible alarm is OFF. This violates C4 because the alarm should be ON to alert people nearby.

---

## Violation 5 - C5

**Constraint:** `T → C`

**Scenario:**

* `T = TRUE`
* `C = FALSE`

**What went wrong?**

The train is passing through the crossing, but the barrier is not closed. This violates C5 because the barrier must remain closed while the train is passing.

---

## Violation 6 - C6

**Constraint:** `B → K`

**Scenario:**

* `B = TRUE`
* `K = FALSE`

**What went wrong?**

The barrier is open, but the train has not completely cleared the crossing. This violates C6 because the barrier should open only after the train has completely cleared the crossing.

---

## Violation 7 - C7

**Constraint:** `S → ¬B`

**Scenario:**

* `S = TRUE`
* `B = TRUE`

**What went wrong?**

A sensor failure is detected, but the barrier is open. This violates C7 because the barrier must not be open when a sensor failure is detected.

---

## Violation 8 - C8

**Constraint:** `E → (W ∧ L)`

**Scenario:**

* `E = TRUE`
* `W = TRUE`
* `L = FALSE`

**What went wrong?**

An emergency condition exists, but the audible alarm is OFF. This violates C8 because both the warning lights and audible alarm must be ON during an emergency.

---

## Conclusion

These eight examples show how safety constraints can be violated in a railway level-crossing control system. Identifying violations helps verify that the system follows the required safety rules.
# Task 3 - Identify Constraint Violations

This task shows examples where the railway level-crossing safety constraints are violated.

## Violation 1 - C1

**Constraint:** `T → ¬B`

**Scenario:**

* `T = TRUE`
* `B = TRUE`

**What went wrong?**

The train is present, but the barrier is open. This violates C1 because the barrier must not be open while a train is present.

---

## Violation 2 - C2

**Constraint:** `A → C`

**Scenario:**

* `A = TRUE`
* `C = FALSE`

**What went wrong?**

The train is approaching, but the barrier is not closed. This violates C2 because the barrier must close when a train approaches.

---

## Violation 3 - C3

**Constraint:** `A → W`

**Scenario:**

* `A = TRUE`
* `W = FALSE`

**What went wrong?**

The train is approaching, but the warning lights are OFF. This violates C3 because the warning lights should be ON to warn drivers.

---

## Violation 4 - C4

**Constraint:** `A → L`

**Scenario:**

* `A = TRUE`
* `L = FALSE`

**What went wrong?**

The train is approaching, but the audible alarm is OFF. This violates C4 because the alarm should be ON to alert people nearby.

---

## Violation 5 - C5

**Constraint:** `T → C`

**Scenario:**

* `T = TRUE`
* `C = FALSE`

**What went wrong?**

The train is passing through the crossing, but the barrier is not closed. This violates C5 because the barrier must remain closed while the train is passing.

---

## Violation 6 - C6

**Constraint:** `B → K`

**Scenario:**

* `B = TRUE`
* `K = FALSE`

**What went wrong?**

The barrier is open, but the train has not completely cleared the crossing. This violates C6 because the barrier should open only after the train has completely cleared the crossing.

---

## Violation 7 - C7

**Constraint:** `S → ¬B`

**Scenario:**

* `S = TRUE`
* `B = TRUE`

**What went wrong?**

A sensor failure is detected, but the barrier is open. This violates C7 because the barrier must not be open when a sensor failure is detected.

---

## Violation 8 - C8

**Constraint:** `E → (W ∧ L)`

**Scenario:**

* `E = TRUE`
* `W = TRUE`
* `L = FALSE`

**What went wrong?**

An emergency condition exists, but the audible alarm is OFF. This violates C8 because both the warning lights and audible alarm must be ON during an emergency.

---

## Conclusion

These eight examples show how safety constraints can be violated in a railway level-crossing control system. Identifying violations helps verify that the system follows the required safety rules.
