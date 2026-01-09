# uw-demo-launcher (uw3-release-candidate)

This branch launches the **uw3-release-candidate** version of Underworld3 on mybinder.org.

## Launch

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/underworld-community/uw-demo-launcher/uw3-release-candidate)

## What's included

- **Underworld3** from the `uw3-release-candidate` branch
- **Beginner tutorials** from `docs/beginner/tutorials/`

## How it works

1. The binder image is pre-built with all dependencies (petsc, pyvista, jupyter, etc.)
2. On each launch, the `start` script pulls the latest code and rebuilds (fast ~30s)
3. Tutorials are copied to the workspace for easy access

## Other branches

- `main` - launches development versions of both underworld3 and underworld2
