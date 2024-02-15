## Windows
Run the `setup.exe` inside the build folder to install this keyboard layout.

## Linux
1. Move the `eeprog` file into `/usr/share/X11/xkb/symbols`.
2. Insert the following snippet into the `<layoutList>` section of the `/usr/share/X11/xkb/rules/evdev.xml` file:
```xml
<layout>
  <configItem>
    <name>eeprog</name>
    <shortDescription>est</shortDescription>
    <description>Estonian (Programmers)</description>
    <languageList>
      <iso639Id>est</iso639Id>
    </languageList>
  </configItem>
  <variantList/>
</layout>
```
