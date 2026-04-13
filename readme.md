# APL Virtuoso Profiles

| Filename                                          |     Room Type      | Description                                                                                   |
| :------------------------------------------------ | :----------------: | :-------------------------------------------------------------------------------------------- |
| **default [4.8x6.5x4.7].json**                    | **Dubbing Stage**  | A standard dubbing stage profile featuring a 1.73m source distance and balanced 0.5 ambience. |
| **1-field.tight.close [7.6x10.0x4.8].json**       | **Control Room M** | The closest near-field setup with a 0.96m source distance and low 0.22 ambience.              |
| **2-booth.intimate.dry [2.6x3.5x2.4].json**       | **Dubbing Stage**  | An intimate vocal booth with a 1.0m source distance and a dry 0.23s reverb time.              |
| **3-suite.balanced.mid [4.9x6.4x3.3].json**       | **Control Room M** | A balanced suite configuration with a 1.62m source distance and 0.3 reverb/ambience.          |
| **4-hall.diffuse.reflective [5.0x3.8x3.4].json**  |  **Living Room**   | A diffuse environment with a 1.67m source distance and a wetter 0.4s reverb time.             |
| **5-cinema.dry.wide [6.2x10.0x4.0].json**         | **Control Room L** | A wide monitoring profile with a 1.7m source distance and a dry 0.24s reverb.                 |
| **6-studio.katz.min.ambience [4.8x6.4x4.7].json** | **Control Room L** | A dry setup with a 1.72m source distance and minimal 0.16 ambience.                           |
| **7-studio.balanced.mid [4.8x6.5x4.7].json**      | **Control Room L** | A balanced studio profile with 0.5 ambience and a 1.73m source distance.                      |
| **8-hall.bright.intimate [6.9x10.0x4.3].json**    |  **Living Room**   | A bright hall with a high 0.65 ambience coefficient and a 2.12m distance.                     |
| **9-studio.flat.dry [4.8x6.4x4.7].json**          | **Control Room L** | A flat response profile featuring a 2.32m source distance and a dry 0.2s reverb.              |
| **10-studio.distant.wet [4.8x6.4x4.7].json**      | **Control Room L** | A wetter distant configuration with a 0.4s reverb time and 3.81m source distance.             |
| **11-hall.balanced.mid [6.9x10.0x4.3].json**      |  **Living Room**   | A mid-sized hall simulation with 0.5 ambience and a 4.12m source distance.                    |
| **12-cinema.distant.muted [6.3x10.0x4.0].json**   |  **Living Room**   | A large space with a 4.24m source distance and muted 0.17 ambience.                           |
| **13-hall.dark.distant [6.9x10.0x4.3].json**      |  **Living Room**   | A dark profile with a 4.62m distance and moderate 0.3s reverb time.                           |
| **14-studio.distant.dry [4.8x6.4x4.7].json**      | **Control Room L** | The furthest monitoring setup at 5.0m with the driest reverb time of 0.2s.                    |

### Key Acoustic Markers by Type

- **Professional Spaces (Types 1-4):** Generally maintain lower reverb times and consistent damping profiles to ensure a "dry" signal suitable for critical listening or recording.
- **Domestic Spaces (Types 0, 5, 6):** Exhibit more "liveliness" and varied reflection patterns. Type 6, in particular, acts as a catch-all for various hall and reflective room simulations.
- **Dimensions:** Room sizes scale progressively from Type 3 (Smallest: 2.6m width) up to Type 2/4 (Largest: 7.6m width).

| Room Type ID | **Room Type**      | Typical Acoustic Profile                                                                                                |
| :----------- | :----------------- | :---------------------------------------------------------------------------------------------------------------------- |
| **Type 0**   | **Listening Room** | Standard balanced domestic environment with moderate reverb (0.2s) and neutral ambience.                                |
| **Type 1**   | **Control Room L** | Large professional monitoring space. Features dry reverb (0.2s–0.24s) and adaptable source distances (1.7m to 5.0m).    |
| **Type 2**   | **Control Room M** | Medium-sized studio suite. Optimized for tight, near-field monitoring with lower ambience coefficients (~0.22).         |
| **Type 3**   | **Control Room S** | Compact monitoring environment designed for near-field setups (1.0m) with dry response and gain attenuation.            |
| **Type 4**   | **Dubbing Stage**  | Vocal-centric environment. Characterized by short source distances (1.0m) and very controlled decay times.              |
| **Type 5**   | **Home Cinema**    | Specialized domestic space with balanced ambience and moderate depth (approx. 6.0m).                                    |
| **Type 6**   | **Living Room**    | Highly versatile domestic profile. Ambience varies significantly (0.17 to 0.7) and often utilizes a -2.0dB gain offset. |
