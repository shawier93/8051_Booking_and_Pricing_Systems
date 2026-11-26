# Date Based Discount

[Repository overview](../README.md)

Choose a discount tier from a day value and calculate the amount payable.

## Implementations

The percentage versions calculate and subtract a discount. Earlier versions operate on whole tens: amount 29 can produce 25 when the units are retained, or 16 when they are dropped. These are materially different algorithms, not just display changes.

| Implementation | Input | Output | Implementation notes |
| --- | --- | --- | --- |
| [Interrupt Date Tier Payment](Interrupt%20Date%20Tier%20Payment/README.md) | Keypad | LCD and internal result bytes | Whole-tens discount; units retained |
| [Keypad Date Tier Payment](Keypad%20Date%20Tier%20Payment/README.md) | Keypad | LCD and internal result bytes | Whole-tens discount; units retained |
| [LCD Date Tier Payment](LCD%20Date%20Tier%20Payment/README.md) | Stored values or prompted choices | LCD and internal result bytes | Whole-tens discount; units retained |
| [Memory Date Tier Units Truncation](Memory%20Date%20Tier%20Units%20Truncation/README.md) | Values stored in memory | Internal memory | Whole-tens discount; units discarded |
| [LCD Percentage Discount](LCD%20Percentage%20Discount/README.md) | Stored values or prompted choices | LCD and internal result bytes | Percentage of amount, then subtraction |
| [Memory Percentage Discount](Memory%20Percentage%20Discount/README.md) | Values stored in memory | Internal memory | Percentage of amount, then subtraction |
| [Interrupt Percentage Discount](Interrupt%20Percentage%20Discount/README.md) | Keypad | LCD and internal result bytes | Percentage of amount, then subtraction |
| [Keypad Percentage Discount](Keypad%20Percentage%20Discount/README.md) | Keypad | LCD and internal result bytes | Percentage of amount, then subtraction |
