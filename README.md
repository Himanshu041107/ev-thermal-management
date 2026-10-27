# Thermal Management in Electric Vehicles

Hybrid battery cooling for an EV battery pack, using a phase change material (PCM) together with a liquid-cooled aluminium cold plate.

Submitted to **Hack for Social Cause** by **TEAM RAGE B8** (Team ID: HSC HP 00111), IIT Mandi, Himachal Pradesh.
Theme: Environment & Sustainability.

## The problem

Batteries in electric vehicles get hot during fast charging and heavy loads. Too much heat shortens battery life, reduces range and can lead to thermal runaway. Pure paraffin wax is a common PCM, but it conducts heat poorly, so on its own it does not spread heat well through the pack.

## Our approach

We cool a 4S5P battery pack (4 cells in series, 5 in parallel, 20 cells in total) with two things working together:

1. **PCM layer:** paraffin wax mixed with 10% expanded graphite. The wax absorbs heat as it melts, and the graphite helps spread that heat through the PCM.
2. **Aluminium cold plate:** the plate has grooves, and a copper tube carrying coolant is fitted into these grooves. The coolant carries heat out of the pack.

The idea is to use the PCM and the cold plate together in one system. The PCM takes the peak heat, and the cold plate with coolant removes it.

See [docs/architecture.md](docs/architecture.md) for the design in more detail.

## Tools used

- CAD for the design of the cold plate and the pack layout

## Repository contents

| Path | What it is |
|------|------------|
| `README.md` | This file |
| `docs/architecture.md` | Design and working principle |
| `LICENSE` | MIT License |

CAD files and any test or simulation data are added under `cad/` and `data/` when available.

## Team

| Name | Branch | Roll No. |
|------|--------|----------|
| Himanshu Maurya (team lead) | Mechanical Engineering | B25461 |
| Tanmay | CSE | 25180 |
| Pratik Sanap | DSAI | B25222 |

## License

MIT, see [LICENSE](LICENSE).
