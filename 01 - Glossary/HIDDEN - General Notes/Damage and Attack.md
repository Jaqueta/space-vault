### Damage and Attack
The values that define the basic Damage Formula, `(Base Attack * Attack Multiplier) + Flat Attack`, the Damage Value is then reduced by the Target's Defense.

An example:
**Base Attack: 6**
**Attack Bonus: 135%**
**Flat Attack: 3**

**Enemy's DEF: 2**

`6 * 1.35 = 8.1`
`8.1 + 3 = Ceil(11.1)`
**`FINAL DAMAGE = 10 (12 -2 DEF).`**