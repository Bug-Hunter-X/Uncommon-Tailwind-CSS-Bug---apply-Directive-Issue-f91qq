# Uncommon Tailwind CSS Bug: @apply Directive Issue

This repository demonstrates an uncommon bug encountered when using the `@apply` directive in Tailwind CSS with complex selectors. The issue involves unexpected behavior where styles are not applied correctly, leading to incorrect rendering of elements.

## Bug Description

The bug manifests when using `@apply` with selectors that include pseudo-classes or multiple classes. The expected styles are not applied, resulting in unexpected visual output. This is not a common issue and might be related to specific configurations or interactions with other CSS.

## Reproduction Steps

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm start`
4. Observe the unexpected styling in the browser.

## Solution

The solution involves a workaround to apply the styles directly using a custom CSS class instead of relying on `@apply`. This resolves the issue and ensures the correct styles are applied to the elements.
