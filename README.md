# Tailwind CSS Classes Not Applied in Production

This repository demonstrates a common issue with Tailwind CSS where classes work correctly during development but fail to render in the production build. The bug is related to the build process, often involving issues with the purging of unused CSS or incorrect configuration.

## Bug
The provided `bug.js` file contains a simple example where some Tailwind CSS classes are applied to a div element in the development environment.  However, when built for production, these classes do not render in the browser, causing the layout and styling to be incorrect.

## Solution
The solution, found in `bugSolution.js`, addresses the problem by ensuring that the Tailwind CSS configuration is correctly set up for the production build. This may involve adjustments to the purge options or build process, depending on the specific build tool being used.  Make sure that `tailwind.config.js` is correctly configured and that the Tailwind directives are properly included in the CSS.