# Gears of War – čeština pro Xbox 360

Hotová česká lokalizace původního **Gears of War** pro Xbox 360 ve formě
jediného Title Update balíčku.

Projekt je určen pro konzole s RGH/JTAG:

- Title ID: `4D5307D5`
- Media ID: `76E9DF5B`
- technický základ: oficiální TU5
- cílová verze `default.xexp`: `0x00000501`

## Obsah překladu

- české nabídky a systémové texty;
- české titulky dialogů, filmečků a hlášek postav;
- české popisy herních režimů a nastavení;
- české načítací tipy upravené pro ovladač Xbox 360;
- doplněné české znaky v původních Xbox fontech;
- původní Xbox ikony tlačítek A/B/X/Y, spouští, páček a směrového ovladače.

## Instalace

1. Stáhněte a rozbalte `GOW_X360_CZ_FINAL.zip`.
2. Zálohujte případný stávající Title Update hry.
3. Soubor

   ```text
   TU_16L61UL_0000004000000.0000000000181
   ```

   nahrajte do:

   ```text
   Hdd1:\Cache\
   ```

4. V Auroře vypněte nebo odstraňte jiné varianty Title Update pro Gears of
   War, aby český soubor nebyl přepsán.
5. Konzoli úplně vypněte a znovu zapněte.

Aurora bude aktualizaci nadále zobrazovat jako **TU5**. To je správně:
čeština zachovává původní verzi oficiálního aktualizačního souboru a ve hře
už nezobrazuje žádnou interní značku sestavení.

## Kontrola souboru

Finální TU:

```text
CCF7EE985BCF51F3166F896BB4AD87095109732367F24BF2B4DD483CC94270E9
```

Úplný seznam kontrolních součtů je v `SHA256SUMS.txt`.

## Známé omezení

Balíček je připraven výhradně pro kombinaci Title ID a Media ID uvedenou
výše. S jiným vydáním hry nemusí fungovat.

## Autoři a poděkování

- původní česká lokalizace pro PC: **CD Projekt**;
