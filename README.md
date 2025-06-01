# Volvo V60 Harness

KiCad schematics for a custom harness compatible with **comma.ai** devices (e.g., **comma 3X**, **Panda Red**) for the **first-generation Volvo V60**.

## Files Included

- `18.kicad_sch` – 18-pin version (V3)
- `26.kicad_sch` – 26-pin version (V1)
- `harness.kicad_sch` – Overview schematic

## Build Options

### Option 1: Modify an existing harness (recommended)

You can use either:
- a [comma.ai dev harness](https://comma.ai/shop/car-harness?harness=Developer), or  
- any other [comma.ai car harness](https://comma.ai/shop/car-harness)

You will still need to purchase:
- Connector housings:
  - [`MX34016SF1`](https://www.digikey.com/short/z8n3t0hn) (male)
  - [`MX34016UF1`](https://www.digikey.com/short/v9njd9n8) (female)
- 16x Pins: [`M34S75C4F1`](https://www.digikey.com/short/4zqr8qj8)
  
### Option 2: Build from scratch

If you don’t want to use an existing harness, you'll need to build everything yourself.

Required parts:
- Connector housings:
  - [`MX34016SF1`](https://www.digikey.com/short/z8n3t0hn) (male)
  - [`MX34016UF1`](https://www.digikey.com/short/v9njd9n8) (female)
- 16x Pins: [`M34S75C4F1`](https://www.digikey.com/short/4zqr8qj8)
- Harness Box: [Comma Harness Box](https://comma.ai/shop/harness-box)
- Connector (depending on version):
  - 18-pin: [`501646-1800`](https://www.digikey.com/short/3zdf013q)
  - 26-pin: [`501646-2600`](https://www.digikey.com/short/jbmtvc4b)
- Optional: [Comma Power](https://comma.ai/shop/comma-power) – to enable harness power on ignition

## Notes

- This project uses **KiCad** for schematic design.
