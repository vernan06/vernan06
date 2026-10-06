# Visual System

The profile uses the visual language of a compact engineering instrument: clear hierarchy, measured spacing, thin rules, and information that earns its place.

## Color

- Canvas: near-black `#0b1116`, with a quiet graphite grid.
- Primary text: cool off-white `#d5e0e4`.
- Secondary text and structure: muted blue-gray, with low-contrast connection lines.
- Accent: restrained signal teal `#66cec5`, reserved for active paths and state indicators.
- Keep future graphics to neutral structure plus one purposeful accent. Avoid rainbow gradients and large areas of saturated color.

## Type and layout

- Use system monospace stacks for labels and technical annotations; do not require external fonts.
- Prefer compact uppercase labels with modest tracking, aligned to the underlying diagram.
- Use a wide `viewBox` and preserve the complete composition as the graphic scales down.
- Keep headings, labels, and footnotes concise. Leave visible space between the visual and its boundaries.

## Motion and graphics

- Motion should explain a system state: signals travel left to right, then downstream nodes respond.
- Keep idle states quiet, stagger paths, and leave pauses between propagation cycles.
- Honor `prefers-reduced-motion`; ensure static strokes and labels still communicate the diagram.
- Prefer precise geometry, weighted connections, and subtle grid marks over decorative effects, logos, or generic interface ornament.
- Any illustrative telemetry must be labeled as schematic, never presented as live measurements.

## Future assets

Use the neural-network hero as the reference for contrast, stroke weight, label scale, spacing, and restrained motion. New profile graphics should share its palette and technical tone without repeating its composition. The engineering schematic is intentionally not part of this phase.