# Platy's Quilt Template Mod

Platy's modified Quilt template mod. Has some specific additions shared between Platymemo's mods.

## Usage

In order to use this mod as a template:

1. Create a new repository from this template with `Use this template`
2. Clone the recently-created repo on your PC
3. Make the necessary changes in order to make it yours:
    - Update `gradle.properties` in order to use your Maven group and mod ID
        - If you don't know which Maven group to use, and you are planning to host the mod's source code on GitHub, use `io.github.<Your_Username_Here>`
    - Update `quilt.mod.json` in order to reflect your mod's metadata
        - If you are planning to include (jar-in-jar) a mod, don't forget to declare its dependency on it!
        - The icon provided here is a placeholder one. If you aren't able to replace it yet, you can delete it and remove the "icon" property
    - If the dependencies on `gradle/libs.versions.toml` isn't up-to-date, feel free to update them! The [linked utility](https://lambdaurora.dev/tools/import_quilt.html) should help you in this easy and quick process.
4. The mod is now ready to be worked on!

## License

This template on the Platymemo GitHub is licensed under the [Creative Commons Attribution 4.0 International License](./LICENSE.md).

Mods created with this template are not automatically licensed under the CC-BY-4.0, and are not required to give any kind of credit back to QuiltMC or Platymemo for this template.
