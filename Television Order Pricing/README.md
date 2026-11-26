# Television Order Pricing

[Repository overview](../README.md)

Build a television order price from a brand and optional services.

## Implementations

The calculation-only version uses fixed option bytes. Keypad versions collect options. Indicator and interrupt versions add different feedback and control paths. They share a pricing exercise, not a current retail price list.

| Implementation | Input | Output |
| --- | --- | --- |
| [Memory Brand Service Pricing](Memory%20Brand%20Service%20Pricing/README.md) | Values stored in memory | Internal memory |
| [Interrupt Brand Order Validation](Interrupt%20Brand%20Order%20Validation/README.md) | Keypad | LCD and internal result bytes |
| [Interrupt Brand Order Menu](Interrupt%20Brand%20Order%20Menu/README.md) | Keypad | LCD and internal result bytes |
| [Led Brand Service Pricing](LED%20Brand%20Service%20Pricing/README.md) | See example | See example |
| [Keypad Brand Service Pricing](Keypad%20Brand%20Service%20Pricing/README.md) | Keypad | LCD and internal result bytes |
