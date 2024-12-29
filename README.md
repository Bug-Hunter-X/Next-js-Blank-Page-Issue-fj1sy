# Next.js Blank Page Bug

This repository demonstrates a common issue in Next.js applications where the page renders a blank screen instead of the expected content.  The problem originates from a missing or incorrect export statement in the page component.  The solution demonstrates how to correctly export the page component to resolve this issue.

## Steps to reproduce the bug:

1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.
4. Observe the blank page in the browser.

## Solution:

The solution involves correctly exporting the default component within the pages directory, which ensures the page correctly renders.