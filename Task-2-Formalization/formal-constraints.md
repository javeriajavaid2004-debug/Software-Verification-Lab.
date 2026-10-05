# Task 2 - Formalize Constraints

## Symbols Used

| Symbol | Meaning                                   |
| ------ | ----------------------------------------- |
| `∧`    | AND - aur                                 |
| `∨`    | OR - ya                                   |
| `¬`    | NOT - nahi                                |
| `→`    | Implies - agar ye ho, to woh hona chahiye |

## Variables

| Variable | Meaning                                   |
| -------- | ----------------------------------------- |
| `T`      | Train is present                          |
| `A`      | Train is approaching                      |
| `B`      | Barrier is open                           |
| `C`      | Barrier is closed                         |
| `W`      | Warning lights are ON                     |
| `L`      | Audible alarm is ON                       |
| `S`      | Sensor failure detected                   |
| `F`      | Barrier failure detected                  |
| `K`      | Train has completely cleared the crossing |
| `E`      | Emergency condition exists                |

## Formal Expressions

| Constraint ID | Formal Expression | Simple Meaning                                                                |
| ------------- | ----------------- | ----------------------------------------------------------------------------- |
| C1            | `T → ¬B`          | If a train is present, the barrier must not be open.                          |
| C2            | `A → C`           | If a train is approaching, the barrier must be closed.                        |
| C3            | `A → W`           | If a train is approaching, the warning lights must be ON.                     |
| C4            | `A → L`           | If a train is approaching, the audible alarm must be ON.                      |
| C5            | `T → C`           | If a train is passing, the barrier must be closed.                            |
| C6            | `B → K`           | If the barrier is open, the train must have completely cleared the crossing.  |
| C7            | `S → ¬B`          | If sensor failure is detected, the barrier must not be open.                  |
| C8            | `E → (W ∧ L)`     | If an emergency exists, both warning lights and the audible alarm must be ON. |

## Conclusion

These formal expressions convert the railway crossing safety constraints into simple logical rules. They help verify whether the system is behaving safely or not.
