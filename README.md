# Nim Flatpak Example

A little example repository of how you can use Nim on Flatpak

## Building

You'll need `flatpak-builder`, then run:

```
flatpak-builder --install --user --force-clean BUILD io.github.Miqueas.NimFlatpakExample.yml
```

In the source folder.

## Running

After building:

```
flatpak run io.github.Miqueas.NimFlatpakExample
```