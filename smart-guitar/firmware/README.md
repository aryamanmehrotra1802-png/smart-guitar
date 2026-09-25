# Firmware

This directory contains the embedded firmware for the Smart Guitar.

## Planned Structure

```text
firmware/
├── src/
├── include/
├── lib/
└── README.md
```

Firmware will be added after the microcontroller and exact hardware architecture are finalized.

## Recommended Development Practices

- Keep hardware drivers separate from application logic.
- Use descriptive names for pins and constants.
- Document non-obvious signal-processing decisions.
- Avoid blocking delays where responsive input is required.
- Record hardware revisions alongside firmware changes.
