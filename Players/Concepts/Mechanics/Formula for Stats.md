---
aliases:
  - Formula
---
This formula determines the bonus applied to a [[Stats|Stat]] Linked via [[Soul Linking Overview]].

$$ \text{Stat Bonus} = \lfloor (\text{Stock} \times \text{Spell Rank}) / 5 \rfloor $$

* **Stat Bonus:** The value added to your Linked stat.
* **Stock:** The number of copies of the specific linked spell you currently possess.
* **Spell Rank:** The power rating of the spell, based on its level. See [[Ranks and Levels]].
* **Rounding:** Always round the result *down* to the nearest whole number.

## Example

If you have 10 copies of a **Rank 2 spell** Linked to [[Stats#FasHandFist Strength|Strength]]:

$$ \text{Bonus} = \lfloor (10 \times 2) / 5 \rfloor = \lfloor 20 / 5 \rfloor = +4 \text{ Strength} $$

---
Back to: [[Soul Linking One-Shot Main Page]]
Related: [[Soul Linking Overview]], [[Ranks and Levels]], [[Stats]]
