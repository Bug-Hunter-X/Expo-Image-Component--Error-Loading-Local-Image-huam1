# Expo Image Component: Error Loading Local Image

This repository demonstrates a common error encountered when using Expo's `Image` component with local image URIs and provides a solution.

## Problem

The Expo `Image` component fails to load a local image, resulting in an error. This is frequently caused by incorrect file paths, inaccessible files, or insufficient permissions.

## Solution

The solution involves double-checking the file path, ensuring the image file is accessible, and verifying the necessary file permissions.  The example showcases proper URI formatting and file existence checks.

## How to reproduce and Fix

1. Clone the repository.
2. Navigate to the `bug` directory and run `npm install` to install the dependencies.
3. Observe the error when running the app (in `bug.js`).
4. Navigate to the `bugSolution` directory and run `npm install`.
5. Observe the corrected behavior in `bugSolution.js` which addresses the error. 