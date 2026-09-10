---
name: xxd-panel-156
description: "Create XXD Panel 156 raster artwork from photographs using strict two-spot-colour Risograph-like editorial illustration, decoupled colour planes and open contours, slight ink misregistration, a small stamp-like subject and vast intentional whitespace. Use when the user invokes xxd-panel-156 or requests this style. Supports individual images, isolated directory batches, strict 50:50 comparisons, design-only outputs, and wallpapers."
---

# XXD Panel 156

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

Check the strict two-spot-colour system explicitly: one ink carries planes and mass, the other contours and emphasis. The design must show separated line and fill, slight registration offsets and real-looking paper/ink behaviour; a recoloured photograph or smooth duotone filter is insufficient. Keep a small stamp-like focus with vast intentional whitespace.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-156/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-156-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
