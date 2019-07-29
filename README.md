# MobaXterm Keygen

Generate license key for [MobaXterm](https://mobaxterm.mobatek.net/download-home-edition.html).

## How it work?

Please see source code. It is not complex.

## How To

```
Usage:
    python MobaXterm-Keygen.py <UserName> <Version>

    <UserName>:      The Name licensed to <me>
    <Version>:       The Version of MobaXterm <12.0>
```

Example:

```bash
PS path\to\MobaXterm-Keygen>python MobaXterm-Keygen.py me 12.0
[*] Success!
[*] File generated: path\to\MobaXterm-Keygen\Custom.mxtpro
[*] Please move or copy the newly-generated file to MobaXterm's installation path.
```

Then copy `Custom.mxtpro` to `%ProgramFiles%\MobaXterm\v12.0\`.

## Screen shot

![](v12.0-about.png)

---

## Postscript

1. This application does not have complex activation algorithm and it is truly fantastic. __So please pay for it if possible.__

2. The file generated, `Custom.mxtpro`, is actually a zip file and contains a text file, `Pro.key`, where there is a key string. 

3. `MobaXterm.exe` has another mode. You can see it by adding a parameter `"-customizer"`.

   ```
   $ .\MobaXterm.exe -customizer
   ```

   I don't know how to make custom settings take effect in `Customizer` mode directly. 
   
   The only way I found is that you should export custom settings to a file named `MobaXterm customization.custom` which is also a zip file. Then merge two zip file: `Custom.mxtpro` and `MobaXterm customization.custom` to `Custom.mxtpro`. Finally copy newly-generated `Custom.mxtpro` to MobaXterm's installation path.

