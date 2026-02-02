<!--  NOTE: Auto-generated from the JSON PURL type definition.
Do not manually edit this file. Edit the JSON type definition instead. -->

# PURL Type Definition: platformio

- **Type Name:** PlatformIO
- **Description:** PlatformIO packages for embedded development, including libraries, platforms, and tools.
- **Schema ID:** `https://packageurl.org/types/platformio-definition.json`

## PURL Syntax

The structure of a PURL for this package type is:

    pkg:platformio/<namespace>/<name>@<version>?<qualifiers>#<subpath>

## Repository Information

- **Use Repository:** Yes
- **Default Repository URL:** https://registry.platformio.org/
- **Note:** The default repository is the PlatformIO Registry at https://registry.platformio.org

## Namespace definition

- **Requirement:** Required
- **Native Label:** owner
- **Note:** `The namespace is the owner name of the library in the PlatformIO Registry. It must be lowercased in the canonical form.`

## Name definition

- **Requirement:** Required
- **Native Label:** name
- **Note:** `The name is the library identifier in the PlatformIO Registry. It must be lowercased in the canonical form.`

## Version definition

- **Requirement:** Optional
- **Case Sensitive:** Yes
- **Native Label:** version
- **Note:** `The version is a semantic version string.`

## Qualifiers Definition

| Key  | Requirement | Native name | Default Value | Description |
|------|-------------|-------------|---------------|-------------|
| platform | Optional | platform |  | The target hardware platform (e.g., espressif32, ststm32, atmelavr, teensy). |
| framework | Optional | framework |  | The target framework (e.g., arduino, espidf, stm32cube, zephyr). |
| repository_url | Optional | repository_url |  | An alternative registry URL for private or self-hosted registries. |

## Examples

- `pkg:platformio/me-no-dev/asynctcp@1.1.1`
- `pkg:platformio/adafruit/adafruit_neopixel@1.12.0`
- `pkg:platformio/espressif/arduino-esp32@3.0.0?platform=espressif32`

## Reference URLs

- `https://registry.platformio.org/`
- `https://docs.platformio.org/en/latest/librarymanager/index.html`
