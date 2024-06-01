# Wokwi sn74ls51 Chip

This is a custom chip for [Wokwi](https://wokwi.com/). It implements the sn74ls51 IC.

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-sn74ls51": "github:wokwi-custom-chips/sn74ls51@0.1.0"
  }
```

Then, add the chip to your circuit by adding a `chip-sn74ls51` item to the `parts` section of diagram.json:

```json
  "parts": {
    ...,
    { "type": "chip-sn74ls51", "id": "chip1" }
  },
```

For a complete example, see [The sn74ls51 chip test project](https://wokwi.com/projects/399517192859856897).
