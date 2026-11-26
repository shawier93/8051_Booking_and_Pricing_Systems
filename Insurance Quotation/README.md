# Insurance Quotation

[Repository overview](../README.md)

Calculate an example policy price from a category and selected options.

## Implementations

Preset and keypad versions use different sample selections. Some versions use indicator outputs; others show the total on an LCD. Subscription handling in these sources subtracts a value; it should not be described as real-world insurance pricing.

| Implementation | Input | Output |
| --- | --- | --- |
| [Keypad Policy Options](Keypad%20Policy%20Options/README.md) | Keypad | LCD and internal result bytes |
| [Led Policy Pricing Draft](LED%20Policy%20Pricing%20Draft/README.md) | See example | See example |
| [Memory Policy Pricing](Memory%20Policy%20Pricing/README.md) | Values stored in memory | Internal memory |
| [Interrupt Policy Options](Interrupt%20Policy%20Options/README.md) | Keypad | LCD and internal result bytes |
