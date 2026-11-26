# Coffee Machine

[Repository overview](../README.md)

Choose a drink and options, calculate its price, and process the credit available for the purchase.

## Implementations

The whole-unit versions use simpler prices. Fractional-price versions maintain whole and fractional parts. Switch versions read port bits; keypad versions ask for each selection. Completion messages and credit-handling paths differ.

| Implementation | Input | Output | Implementation notes |
| --- | --- | --- | --- |
| [Keypad Order Price Display](Keypad%20Order%20Price%20Display/README.md) | Keypad | LCD and internal result bytes | Whole-unit price calculations |
| [Keypad Order Completion](Keypad%20Order%20Completion/README.md) | Keypad | LCD and internal result bytes | Whole-unit price calculations |
| [Switch Selected Drink Options](Switch%20Selected%20Drink%20Options/README.md) | Switch or port inputs | Port feedback and available output routines | Whole-unit price calculations |
| [Keypad Fractional Price Order](Keypad%20Fractional%20Price%20Order/README.md) | Keypad | LCD and internal result bytes | Separate whole and fractional price parts |
| [Keypad Fractional Price Alternate](Keypad%20Fractional%20Price%20Alternate/README.md) | Keypad | LCD and internal result bytes | Separate whole and fractional price parts |
| [Switch Price Normalization](Switch%20Price%20Normalization/README.md) | Switch or port inputs | Port feedback and available output routines | Separate whole and fractional price parts |
| [Keypad Fractional Price Revised](Keypad%20Fractional%20Price%20Revised/README.md) | Keypad | LCD and internal result bytes | Separate whole and fractional price parts |
| [Switch Price Led Feedback](Switch%20Price%20LED%20Feedback/README.md) | Switch or port inputs | Port feedback and available output routines | Separate whole and fractional price parts |
