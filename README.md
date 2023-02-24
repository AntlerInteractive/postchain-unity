# Postchain Client Unity

**Compatible with Postchain 3.3.3 / Rell 0.10.5**

This Unity package offers an API for the Chromia Blockchain. It includes normal transaction serialization, an API for Chromia's [FT3 library](https://rell.chromia.com/en/master/advanced-topics/ft3.html) as well as their [SSO](https://rell.chromia.com/en/master/advanced-topics/ft3/ft3-single-sign-on.html).

Currently tested with Standalone (Windows and Linux) as well as WebGL builds.

# Installation additional step

After adding this package into the project via UPM, copy `Runtime/link.xml` inside the package to your project, or update your project's `link.xml` and add `ChromiaAssembly` to list of preserved assemblies.

This step is to prevent Unity's from stripping `JsonConstructor`s from the package.

For more information about link.xml and Unity code stripping: https://docs.unity3d.com/Manual/ManagedCodeStripping.html

## Support

Use the [Chromia Dev Telegram Chat](https://t.me/ChromiaDev)