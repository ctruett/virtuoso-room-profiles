# APL Virtuoso Rooms

Category-based acoustic room profiles organized by environment type and acoustic character.

## Directory Structure

```
Rooms/
├── template.json                          — Blank profile template for creating new profiles
├── professional/                          — Studio & control room environments
│   ├── dry/                               — Low ambience, controlled reverb
│   ├── balanced/                          — Moderate ambience, versatile monitoring
│   └── reflective/                        — Higher ambience, wetter response
├── domestic/                              — Living room & listening environments
│   ├── dry/                               — Muted, damped domestic spaces
│   ├── balanced/                          — Moderate ambience domestic
│   └── wet/                               — High ambience, reflective domestic
├── custom/                                — User-defined & experimental profiles
└── archive/                               — Deprecated or redundant profiles
```

---

## Profile Index by Category

### professional/dry/ — Low Ambience, Controlled Reverb

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-katz.min-ambience.json` | Control Room L | 4.8 × 6.4 × 4.7 m | 0.16 | 0.20s | +1.2 dB | Minimal reflection studio; lowest ambience in the collection |
| `2-flat-dry-mid.json` | Control Room L | 4.8 × 6.4 × 4.7 m | 0.40 | 0.20s | +2.2 dB | Flat response, mid-distance (2.32m) monitoring |
| `3-distant-dry.json` | Control Room L | 4.8 × 6.4 × 4.7 m | 0.40 | 0.20s | +2.2 dB | Distant dry monitoring; identical data to flat-dry-mid |
| `4-booth-intimate-dry.json` | Dubbing Stage | 2.6 × 3.5 × 2.4 m | 0.50 | 0.23s | -6.7 dB | Smallest room; intimate vocal booth with heavy attenuation |
| `5-cinema-dry-wide.json` | Control Room L | 6.2 × 10.0 × 4.0 m | 0.30 | 0.24s | +0.5 dB | Wide cinema monitoring with dry response |

### professional/balanced/ — Moderate Ambience, Versatile Monitoring

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-balanced-mid.json` | Control Room L | 4.8 × 6.5 × 4.7 m | 0.50 | 0.23s | +1.2 dB | Canonical balanced studio reference profile |
| `2-default-dubbing-stage.json` | Dubbing Stage | 4.8 × 6.5 × 4.7 m | 0.50 | 0.23s | -1.5 dB | Standard dubbing stage with controlled decay |
| `3-suite-balanced-mid.json` | Control Room M | 4.9 × 6.4 × 3.3 m | 0.30 | 0.30s | -0.5 dB | Medium suite configuration; similar to balanced studio |

### professional/reflective/ — Higher Ambience, Wetter Response

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-field-tight-close.json` | Control Room M | 7.6 × 10.0 × 4.8 m | 0.22 | 0.25s | -3.0 dB | Closest placement (0.96m); near-field tight monitoring in large room |
| `2-hall-diffuse-reflective.json` | Control Room L | 5.0 × 3.8 × 3.4 m | 0.70 | 0.40s | -3.4 dB | Highest ambience in studio group; highly reflective hall-like environment |

### domestic/dry/ — Muted, Damped Domestic Spaces

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-cinema-distant-muted.json` | Living Room | 6.3 × 10.0 × 4.0 m | 0.17 | 0.24s | +2.6 dB | Most damped living room profile; heavily muted ambience |

### domestic/balanced/ — Moderate Ambience Domestic

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-hall-balanced-mid.json` | Living Room | 6.9 × 10.0 × 4.3 m | 0.50 | 0.30s | +1.8 dB | Reference domestic profile; balanced ambience in mid-sized hall |
| `2-lisbon-lounge.json` | Listening Room | 7.0 × 4.0 × 2.9 m | 0.50 | 0.30s | -3.0 dB | Domestic lounge with unique low-ceiling dimensions (2.9m) |

### domestic/wet/ — High Ambience, Reflective Domestic

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-hall-bright-intimate.json` | Living Room | 6.9 × 10.0 × 4.3 m | 0.65 | 0.35s | 0.0 dB | Bright, highly reflective domestic space; highest ambience in hall group |
| `2-hall-dark-distant.json` | Living Room | 6.9 × 10.0 × 4.3 m | 0.20 | 0.30s | +3.0 dB | Distant monitoring with boosted gain; dark but acoustically active |

### custom/ — User-Defined & Experimental Profiles

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `1-custom-control-room-l.json` | Control Room L | 7.0 × 4.6 × 3.5 m | 0.50 | 0.25s | 0.0 dB | User-created large control room; balanced ambience with zero damping asymmetry |
| `2-basement-listening-room.json` | Listening Room | 4.0 × 4.5 × 3.5 m | 0.70 | 0.15s | 0.0 dB | Warm, intimate domestic space; high ambience with short reverb |

### archive/ — Deprecated or Redundant Profiles

| Filename | Room Type | Dimensions (W×D×H) | Ambience | Reverb | Gain | Description |
|---|---|---|---|---|---|---|
| `studio-distant-wet.json` | Control Room L | 4.8 × 6.4 × 4.7 m | 0.20 | 0.40s | +2.4 dB | Experimental wet studio variant; retained for reference |
| `default-question-mark.json` | Control Room M | 4.9 × 6.4 × 3.3 m | 0.50 | 0.30s | -0.5 dB | Undocumented profile; archived pending purpose verification |

---

## Room Type Reference

| ID | Room Type | Category | Typical Acoustic Profile |
|---|---|---|---|
| **0** | Listening Room | Domestic | Standard balanced domestic environment with moderate reverb (0.15s–0.30s) and neutral ambience |
| **1** | Control Room L | Professional | Large professional monitoring space; dry reverb (0.20s–0.40s), adaptable source distances (1.5m–5.0m) |
| **2** | Control Room M | Professional | Medium-sized studio suite; tight near-field monitoring with lower ambience (~0.22–0.30) |
| **4** | Dubbing Stage | Professional | Vocal-centric environment; short source distances (1.0m), very controlled decay times |
| **6** | Living Room | Domestic | Highly versatile domestic profile; ambience varies significantly (0.17–0.70), gain ranges from -3.0dB to +3.0dB |

---

## Acoustic Glossary

| Parameter | Range | Meaning |
|---|---|---|
| **Ambience** | 0.0 – 1.0 | Overall reflection density; lower = drier/more controlled, higher = more reflective/spacious |
| **Reverb Time** | 0.1s – 0.6s | Decay duration in seconds; shorter = drier, longer = wetter/more resonant |
| **Source Distance** | 0.5m – 10.0m | Simulated distance from listener to sound source; closer = more direct, further = more ambient |
| **Gain** | -6.0dB – +6.0dB | Overall volume offset applied to the profile output |
| **Damping (high/low)** | 0.0 – 1.0 | Frequency-specific absorption; higher values absorb more energy at that frequency band |
| **Reverb Liveliness (high/low)** | 0.0 – 1.0 | How actively the room resonates at each frequency band; higher = more lively/resonant |

---

## Migration Notes

### Cross-Reference: Old Names → New Locations

The following table maps original filenames to their new paths for reference:

| Old Path | New Path |
|---|---|
| `Profiles/6-studio.katz.min.ambience [4.8x6.4x4.7].json` | `professional/dry/1-katz.min-ambience.json` |
| `Profiles/12-studio.flat.dry [4.8x6.4x4.7].json` | `professional/dry/2-flat-dry-mid.json` |
| `Profiles/14-studio.distant.dry [4.8x6.4x4.7].json` | `professional/dry/3-distant-dry.json` |
| `Profiles/2-booth.intimate.dry [2.6x3.5x2.4].json` | `professional/dry/4-booth-intimate-dry.json` |
| `Profiles/5-cinema.dry.wide [6.2x10.0x4.0].json` | `professional/dry/5-cinema-dry-wide.json` |
| `Profiles/7-studio.balanced.mid [4.8x6.5x4.7].json` | `professional/balanced/1-balanced-mid.json` |
| `default [4.8x6.5x4.7].json` | `professional/balanced/2-default-dubbing-stage.json` |
| `Profiles/3-suite.balanced.mid [4.9x6.4x3.3].json` | `professional/balanced/3-suite-balanced-mid.json` |
| `Profiles/1-field.tight.close [7.6x10.0x4.8].json` | `professional/reflective/1-field-tight-close.json` |
| `Profiles/4-hall.diffuse.reflective [5.0x3.8x3.4].json` | `professional/reflective/2-hall-diffuse-reflective.json` |
| `Profiles/8-cinema.distant.muted [6.3x10.0x4.0].json` | `domestic/dry/1-cinema-distant-muted.json` |
| `Profiles/10-hall.balanced.mid [6.9x10.0x4.3].json` | `domestic/balanced/1-hall-balanced-mid.json` |
| `Profiles/15-lisbon.lounge [7.0x4.0x2.9].json` | `domestic/balanced/2-lisbon-lounge.json` |
| `Profiles/9-hall.bright.intimate [6.9x10.0x4.3].json` | `domestic/wet/1-hall-bright-intimate.json` |
| `Profiles/11-hall.dark.distant [6.9x10.0x4.3].json` | `domestic/wet/2-hall-dark-distant.json` |
| `custom.json` | `custom/1-custom-control-room-l.json` |
| `basement.json` | `custom/2-basement-listening-room.json` |
| `Profiles/13-studio.distant.wet [4.8x6.4x4.7].json` | `archive/studio-distant-wet.json` |
| `default?.json` | `archive/default-question-mark.json` |

### Data Integrity Notes

- **Identical profiles**: `2-flat-dry-mid.json` and `3-distant-dry.json` contain numerically identical data. Both are retained as they may serve different contextual purposes despite identical acoustic parameters.
- **Archive rationale**: Profiles in `archive/` are preserved for reference but not recommended for active use. `studio-distant-wet.json` represents an experimental wet variant, and `default-question-mark.json` was undocumented with a wildcard character in its original filename.

---

## Creating New Profiles

Use `template.json` as the starting point:
1. Copy `template.json` to your desired category subdirectory
2. Rename with the pattern `<sequence>-<semantic-name>.json` (no spaces, no brackets)
3. Adjust all parameters according to your target acoustic characteristics
4. Set `roomType` to match the profile's environment category

---

*Total profiles: 19 active + 2 archived = 21 JSON files (including template)*
