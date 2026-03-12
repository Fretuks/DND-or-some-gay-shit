A creature afflicted with **Bleed** is suffering from deep, worsening wounds that build toward catastrophic blood loss.

Certain attacks/weapons apply a certain amount of **Bleed Buildup**.
- Bleed Buildup is tracked as a numeric value.
- By default, all creatures have a **Bleed Threshold equal to 25% of their Maximum HP** (rounded down).
- When Bleed Buildup reaches or exceeds this threshold, **Bleed triggers**.
Bleed Buildup has **no effect** until the threshold is reached.

**When Bleed triggers:**
- The creature immediately takes **15% of their Maximum HP** as **true damage**
    - This damage **ignores armor, resistances, and damage reduction**
- All Bleed Buildup on the creature is **reset to 0**

After Bleed triggers, the creature gains **Bleed-Exhausted** for **2 rounds**.

**While Bleed-Exhausted:**
- The creature **cannot gain Bleed Buildup**
- Any effects that would apply Bleed Buildup during this time are ignored
This prevents immediate re-triggering.

If a creature does not gain Bleed Buildup for **1 full round**:
- Bleed Buildup is reduced by **20% of the Bleed Threshold** at the end of that round
Bleed Buildup can never drop below 0.

