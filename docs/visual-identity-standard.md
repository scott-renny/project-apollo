# Unified Visual Identity Standard

This standard governs Project Hermes, Project Hydra, and Project Apollo.

## Official logos

- **Hermes:** current winged helmet emblem.
- **Hydra:** current multi-headed serpent emblem.
- **Apollo:** current stylized **A** emblem.

These existing emblems are the official logos moving forward. Do not redraw, reinterpret, or replace them without an intentional identity revision.

## Master artwork rule

Use one exact master wallpaper composition across all three projects. Keep the following identical:

- canvas artwork, atmosphere, lighting, and focal geometry;
- dark blue and black palette with restrained cyan accents;
- typography family and placement system;
- texture, contrast, vignette, and safe areas;
- icon, widget, and dock styling;
- lock-screen clock treatment and information hierarchy.

Only the emblem changes. Its size, position, optical weight, opacity, glow, and clear space remain equivalent.

## Required variants

Create variants from the same approved master source:

| Target | Orientation | Emblem |
|---|---|---|
| Hermes desktop | Landscape | Winged helmet |
| Hydra desktop/multi-monitor | Landscape or spanned crop | Multi-headed serpent |
| Apollo phone wallpaper | Portrait | Stylized A |
| Apollo phone lock screen | Portrait with clock-safe area | Stylized A |
| Apollo tablet wallpaper | Landscape and portrait | Stylized A |
| Apollo tablet lock screen | Landscape and portrait with clock-safe area | Stylized A |

Do not stretch artwork. Use controlled crops and preserve the emblem clear space.

## Asset naming

```text
assets/logos/hermes-emblem-master.<ext>
assets/logos/hydra-emblem-master.<ext>
assets/logos/apollo-emblem-master.<ext>
assets/wallpapers/<project>-<device>-<orientation>-v1.<ext>
assets/lockscreens/<project>-<device>-<orientation>-v1.<ext>
```

Prefer a lossless master and export optimized copies. Preserve editable source files privately if they contain licensed or non-public material.

## Publishing gate

Before adding assets, confirm ownership or permission, inspect metadata, verify there is no embedded personal information, and test readability behind icons, widgets, clocks, and notification regions. This repository includes placeholders because the referenced binary artwork was not supplied in the workspace.

