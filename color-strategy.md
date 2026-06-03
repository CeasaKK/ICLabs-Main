# Isocode Labs Color Strategy

The site uses a role-based palette rather than decorative color picking:

- Graphite `#101418` and white `#ffffff` create a premium, editorial base with strong text contrast. This supports trust because visitors can scan pricing, proof, and CTAs quickly.
- Emerald `#00a86b` is the primary action color. Green is widely associated with progress, confirmation, and forward movement, so it fits the "Book a Build Call" and "Start a Project" actions.
- Cyan `#0ea5e9` is reserved for AI, data, and technical system states. It separates technical proof from conversion actions.
- Amber `#c68a00` is used for premium/value emphasis such as pricing and metrics. It adds warmth and commercial weight without making the page feel cheap.
- Red `#d92d20` is reserved for errors and validation-style states. This follows standard design-system conventions and keeps warning color meaningful.

This matches common interface guidance: Material Design recommends meaningful color roles for primary, secondary, surface, background, and error states, while WCAG contrast guidance keeps text legible. The palette avoids a single-hue look, keeps CTAs visually distinct, and uses red sparingly so visitors know when something needs attention.

Sources:

- Material Design color system: https://m2.material.io/design/color/the-color-system.html
- WCAG 2.2 contrast guidance: https://www.w3.org/TR/WCAG22/#contrast-minimum
- W3C explanation of contrast minimum: https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum
