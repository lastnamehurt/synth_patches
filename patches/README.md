# Synth Patches

Patch libraries for hardware synthesizers, designed for sampling into MPC One+.

**See also:** [MPC Song Building Quickstart](../MPC-SONG-BUILDING-QUICKSTART.md) — From beat to finished song

## Synths

| Synth | Patches | Status |
|-------|---------|--------|
| [Arturia MiniFreak](minifreak/) | 28 | Complete |

## Structure

```
patches/
└── minifreak/
    ├── README.md              # Patch index & workflow
    ├── PATCH-TEMPLATE.md      # Template for new patches
    ├── MPC-SAMPLING-GUIDE.md  # Sampling workflow
    └── *.md                   # Individual patch files
```

## Adding New Synths

Create a new folder for each synth (e.g., `patches/hydrasynth/`, `patches/minilogue/`) and follow the same structure:

1. `README.md` — Patch index and overview
2. `PATCH-TEMPLATE.md` — Standardized template
3. Individual patch files with consistent naming

## Workflow

1. **Design** — Dial in patches on hardware
2. **Document** — Save settings to patch files
3. **Sample** — Record into MPC at C3
4. **Convert** — Create Keygroup programs
5. **Organize** — Save as reusable kits
