# Tekkit ReClassic— Compatibility Files

This folder contains the custom resource pack and data pack used by
Tekkit ReClassic to improve compatibility between mods and
clean up errors caused by outdated or optional integrations.

These files were created specifically for this modpack and are not
intended to replace or modify the original mods themselves.

## Why These Exist

While developing Tekkit ReClassic, I spent a lot of time
reviewing the Minecraft logs and tracking down errors, warnings, missing
resources, and compatibility problems.

Many of these were harmless and came from mods expecting optional mods
or resources that aren't installed. Others resulted in missing textures,
models, broken recipes, or unnecessary log errors.

Rather than modifying the original mod JARs, these compatibility packs
provide fixes externally through Minecraft's resource pack and data pack
systems.

## What the Resource Pack Does

The compatibility resource pack contains fixes for resource-related
issues found while testing the modpack, including:

- Fixes invalid model references used by Night Lights.
- Adds missing texture aliases needed by IC2C Extras.
- Provides resource compatibility for Fluid Matter's UU-Matter fluid.
- Contains compatibility resources for IC2 Classic and Immersive Weathering.

## What the Data Pack Does

The compatibility data pack handles data-related compatibility issues,
including:

- Preventing invalid recipes from loading when their required items or
  integrations are not present.
- Cleaning up errors from old or optional compatibility recipes.
- Handling unused Steam 'n' Rails compatibility loot tables for mods
  that are not included in Tekkit ReClassic.
- Reducing unnecessary errors and warnings during datapack loading.

The goal is not simply to hide errors. Fixes are only included when the
underlying compatibility file is invalid or not applicable to the
configuration used by this modpack.

## How These Were Made

These compatibility files were created while troubleshooting
Tekkit ReClassic.

I am not very familiar with the internal structure of Minecraft resource
packs and data packs, so I used AI assistance during development to help:

- Read and interpret Minecraft log files.
- Trace warnings and errors back to the mods and resources causing them.
- Inspect mod JAR structures and determine what Minecraft was expecting.
- Understand Minecraft resource pack and data pack formats.
- Create and structure some of the compatibility JSON files.
- Review the resulting files for potential compatibility and licensing
  concerns.
- Draft documentation and credits explaining the compatibility work.

The resulting fixes were reviewed and tested in the modpack rather than
being included solely because they were AI-generated or suggested.

AI was used as a development and troubleshooting tool. It did not create
or modify the original third-party mods contained in the modpack.

## Licensing and Third-Party Content

The compatibility packs contain a mixture of original compatibility
work and, where applicable, resources associated with third-party
projects.

Original compatibility files created specifically for Tekkit ReClassic
are provided under the license included with those files.

Third-party content remains the property of its respective authors and
continues to be governed by the original project's license. Included
license and attribution files should not be removed.

Nothing in this repository is intended to relicense third-party work
under the Tekkit ReClassic license.

## Reporting Problems

If one of these compatibility fixes causes a problem, or you believe a
fix is no longer necessary, please open an issue:

https://github.com/Soundlessnija/Tekkit-ReClassic/issues
