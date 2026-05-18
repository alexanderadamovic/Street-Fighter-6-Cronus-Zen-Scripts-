# SF6 - Mai Shiranui Combo Script (Cronus Zen)

Cronus Zen GPC script for Mai Shiranuri in Street Fighter 6 (PS4/PS5).
Flick a stick direction to trigger a full combo automatically.

## Controls

### Left Stick — Meterless Combos
| Direction | Combo |
|-----------|-------|
| Up | Anti-air confirm (cr.HP xx QCF+HP) |
| Down | Low starter BnB (cr.LK, cr.LK, cr.MK xx QCF+LK) |
| Left | Meterless punish (st.HP xx QCF+HP rekka) |
| Right | Midscreen BnB (cr.MP, st.HP xx QCF+HP) |

### Right Stick — Meter/Drive Combos
| Direction | Combo |
|-----------|-------|
| Up | Drive Rush anti-air (DR, cr.HP xx OD QCF+HP) |
| Down | OD Rekka combo (cr.MK xx OD rekka x3) |
| Left | Corner Drive Rush (DR, cr.MP, st.HP xx OD QCF+HP) |
| Right | Super Art 1 finish (cr.MP, st.HP xx SA1) |

## Side Toggle
- Press **SHARE** to switch between P1 and P2 side
- All motion inputs flip automatically

## Timing Adjustments
- `COMBO_DELAY = 16` — 1 frame at 60fps, increase if inputs drop
- `THRESHOLD = 75` — stick sensitivity, lower = easier to trigger
- If combos drop, increase `wait` values by 10-20ms in the script

## Files
- `mai_combos.gpc` — main script
- `notes/timing.md` — timing notes and troubleshooting
