# MPC Sampling Guide for MiniFreak

Standard workflow for sampling MiniFreak patches into MPC One+.

---

## Golden Rule

**ALL MiniFreak sounds are sampled at C3**

Why:
- MPC tuning stays correct
- No guessing later
- Every sampled instrument becomes interchangeable

---

## MiniFreak Setup (Before Sampling)

| Setting | Value |
|---------|-------|
| Tune | **Default (A440)** |
| Patch | Loaded and tested |
| Effects | **ON** (print character) |
| Play Note | **C3 only** |

---

## MPC Sampler Settings

| Setting | Value |
|---------|-------|
| Input | MiniFreak |
| Threshold | Manual |
| Monitor | ON |
| Normalize | OFF (for now) |

---

## What to Record (By Sound Type)

### Bass / Mono Leads

| Parameter | Value |
|-----------|-------|
| Note | **C3** |
| Length | 2–4 bars |
| Captures | 1 clean hit, 1 with expression (aftertouch/mod) |

### Chords / Pads

| Parameter | Value |
|-----------|-------|
| Note | **C3** |
| Length | 4–8 bars |
| Note | Let release tail finish |

### Harmonica / Expressive Leads

| Parameter | Value |
|-----------|-------|
| Note | **C3** |
| Captures | Short phrase, Long phrase |
| Note | Silence between phrases (important) |

---

## MPC Program Setup (After Sampling)

Convert to **Keygroup Program** with these settings:

| Setting | Value |
|---------|-------|
| Root Note | **C3** |
| Low/High Range | Full keyboard |
| Pitch Tracking | **ON** |
| Filter | OFF initially |
| FX | OFF initially |

Now every patch behaves like a **real instrument**, not a chop.

---

## File Naming Convention

Use this exact pattern:

```
MF_LoFi_Southern_01_SwampBass
MF_LoFi_Southern_02_SwampHarp
MF_Blues_Jazz_01_DeltaHarp
MF_Blues_Jazz_02_MidnightRhodes
MF_HipHop_Trap_01_SubGrowlBass
```

**Match MPC Keygroup names exactly.**

---

## MPC Folder Structure

```
MiniFreak_Kits/
├── LoFi_Southern/
│   ├── MF_LoFi_Southern_01_SwampBass.kgrp
│   ├── MF_LoFi_Southern_02_SwampHarp.kgrp
│   └── ...
├── Blues_Jazz/
│   ├── MF_Blues_Jazz_01_DeltaHarp.kgrp
│   ├── MF_Blues_Jazz_02_MidnightRhodes.kgrp
│   └── ...
└── HipHop_Trap/
    ├── MF_HipHop_Trap_01_SubGrowlBass.kgrp
    └── ...
```

---

## Pro Workflow Summary

| Stage | Tool | Purpose |
|-------|------|---------|
| MIDI | MPC | Composition |
| Sound Design | MiniFreak | Character |
| Commit + Arrange | MPC | Structure |
| Final Polish | DAW | Mix/Master |
