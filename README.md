# Expo Camera API Crash: Inconsistent Behavior

This repository demonstrates an uncommon bug encountered when using the Expo `Camera` API. The issue involves crashes or blank screens occurring inconsistently when switching between front and rear cameras or changing camera resolutions.  The cause remains elusive due to variations across devices and Expo SDK versions.

## Reproduction

Reproducing this bug has proven difficult and may not be guaranteed across all devices and environments.  The `bug.js` file includes a basic implementation that attempts to replicate the scenarios that lead to the crash.  It's recommended to test on multiple Android devices with different camera configurations.

## Solution

Unfortunately, there's no definitive fix for this issue yet. `bugSolution.js` demonstrates potential mitigation techniques to increase the robustness and handle unexpected errors, improving the user experience.

## Contributing

Contributions are welcome to further investigate this issue and identify robust solutions.  If you are able to reproduce the bug consistently under specific conditions, please submit a pull request with details.