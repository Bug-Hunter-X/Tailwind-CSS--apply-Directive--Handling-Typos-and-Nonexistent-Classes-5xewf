# Tailwind CSS @apply Directive Bug

This repository demonstrates a common error encountered when using Tailwind CSS's `@apply` directive: specifying a nonexistent or misspelled class.

## Bug Description

The `@apply` directive in Tailwind CSS allows applying predefined utility classes to custom styles. However, typos or using classes not defined in your Tailwind configuration can lead to unexpected behavior or build errors.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` in your browser.
3. Observe that the text color is not white, as expected.

## Solution

The solution involves careful review of your Tailwind configuration and correct spelling of classes within the `@apply` directive. You should also ensure your Tailwind configuration is up-to-date, and your build process is properly configured to handle and report errors resulting from invalid class names.

See `bugSolution.html` for a corrected example.