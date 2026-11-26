# Gym Membership Booking

[Repository overview](../README.md)

Select a membership plan and billing term, then use the corresponding price and availability.

## Implementations

One set organizes stock and price by plan and term. Another includes duration entry. Memory, LCD, keypad, and interrupt versions expose the same type of decision through different interfaces.

| Implementation | Input | Output |
| --- | --- | --- |
| [Interrupt Plan Stock Price](Interrupt%20Plan%20Stock%20Price/README.md) | Keypad | LCD and internal result bytes |
| [Keypad Plan Stock Price](Keypad%20Plan%20Stock%20Price/README.md) | Keypad | LCD and internal result bytes |
| [LCD Plan Stock Price](LCD%20Plan%20Stock%20Price/README.md) | Stored values or prompted choices | LCD and internal result bytes |
| [Memory Plan Stock Price](Memory%20Plan%20Stock%20Price/README.md) | Values stored in memory | Internal memory |
| [Interrupt Membership Duration](Interrupt%20Membership%20Duration/README.md) | Keypad | LCD and internal result bytes |
| [Memory Membership Duration](Memory%20Membership%20Duration/README.md) | Values stored in memory | Internal memory |
| [LCD Membership Duration Modified](LCD%20Membership%20Duration%20Modified/README.md) | Stored values or prompted choices | LCD and internal result bytes |
| [Keypad Membership Duration](Keypad%20Membership%20Duration/README.md) | Keypad | LCD and internal result bytes |
| [LCD Membership Duration](LCD%20Membership%20Duration/README.md) | Stored values or prompted choices | LCD and internal result bytes |
