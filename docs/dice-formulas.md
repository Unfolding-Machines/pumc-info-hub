# Dice Formula Expressions

PUM Companion supports a powerful dice roller with a wide range of expressions. Whether you’re playing D&D, FATE, Savage Worlds, or your own system, you can roll dice exactly how you want.

## Rolling Basics
You can roll dice in three ways:
1. Click the dice icons in the dice roller.
2. Type `/r 3d6` in the log area.
3. Type anywhere in your message: `;;3d6;;`

### Examples
- `2d6+2` — Roll two six-sided dice and add 2.
- `2d20+3` — Roll two d20s and add 3.

## Modifiers and Operators
- **Addition, Subtraction, Multiplication:** `5d6+5d10-L2`, `5d6+(5d10-L2)`
- **Parentheses:** For complex combinations.
- **Drop/Keep:** `3d20 kh2` (keep 2 highest), `4d6 -L2` (drop 2 lowest)

## Exploding & Compounding Dice
- **Exploding:** `4d6!` (reroll max results)
- **Custom Explode:** `4d6!5` (explode on 5), `4d6 !>=4` (explode on 4+)
- **Compounding:** `5d6!!`, `5d6!!<3` (compound on <3)

## Rerolling
- `4d4 r2` (reroll 2s), `4d4 r<=2` (reroll <=2), `4d4 ro<2` (reroll once)

## Counting & Special Dice
- `4d6 #>3` (count results >3)
- `4dF` (Fudge dice), `1d%` (percentile), `1D66` (D66 roll)

## Advanced Examples
- `6d6 #f<=2 #s>=5 #cs6` — Count failures, successes, and criticals in one roll.
- `4d6 -<2` — Drop any results <2.
- `4d20 C<5` — Cap any value <5 to 5.

## Tips
- Use drop/keep to match your favorite RPG system.
- Try combining operators for complex rolls.
- See the in-app Dice Roller for more help and examples.

---

Next: [Random Tables](random-tables.md)
