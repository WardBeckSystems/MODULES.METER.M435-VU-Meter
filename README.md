# M435 · Meter

Ward-Beck Systems M435, 1994|27. Wiki page: [M435 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M435.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 12 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 0 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 108 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 21 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1994 - M435 - 436 - P002 - 1-1.jpg](MANUALS/1994%20-%20M435%20-%20436%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | 0,+4,+8,+14 dBu (ref. 600 ohm source) 0, +4,+8, +14 dBu (ref. 150 ohm source). Vernier range: dB min |
| **Frequency response** | +/-0.25 dB 30 Hz to 15 kHz |
| **Noise** | Greater than 75 dB below 0 VU reading: |
| **Total harmonic distortion** | Less than 0.259 30 Hz to 15 kHz: |
| **Source impedance** | 600 ohms or 150 ohms, balanced / unbalanced. |
| **Greater than 20K ohms** |  |
| &nbsp;&nbsp;Maximum input | +24 dBu: |
| **Meter ballistics** | to ANSI standard #Cl6.5. |
| **Amplifier headroom** | 10 dB above |
| **Vu reading** |  |
| &nbsp;&nbsp;Power requirements | +24 to 28 volts regulated or unregulated. 15 mA nominal for SA14-121 amplifier assembly. 80 mA nominal for LED illumination |
| **Ambient temperature** | 50 degrees Celsius. |
| **Dimensions** | M435 3.90&quot; wide x 2.70&quot; high x 2.75&quot; decp_ (99 mm x 69 mm x 70 mm) M436 4.50&quot; wide * 2.90&quot; high x 2.75&quot; deep (114 mm x 74 mm x 70 mm): SAI4-121 (Amplifier assembly only) 4.00&quot; wide 2.60&quot; high (102 mm * 66 mm) |
| **Weight** | M435 6.8 0z. (194g) net: M436 7.3 oz. (206g) net: SA14-121 (Amplifier assembly only) (298) net: |

## Circuit description

From [MP1-MP2-MP3-MP4 - P030 - M435-436 - 3-1.jpg](MANUALS/MP1-MP2-MP3-MP4%20-%20P030%20-%20M435-436%20-%203-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

SALL-LLAMPLIEIER_ASSEMBLY (Refer_to_Schematic B1A-12L-02-0QL Input Power_Supply_Decoupling The signal applied the actively balancinput at Pl pin and coupled through CI and C2 variable Joss network. The loss network consists of R3_ R4, R5 and the precision shunt resistors R6 through R1Z. Sensitivity switch SWI deter mines the networks Loss. The unregulated regulated positive supply voltage connects to Pl pin CR] guards against possible supply voltage reversal IC regulator U2 sets the regulated supply voltage to 22 volts_ The regulator output voltage is set by R23 R24 and R25 The one half supply bias voltage is set by driver R26 and R27. decoupled by capacitor C9. Preamplifie UIA with feedback gain setting resistors R13 Rl6 and R17 forms the prcamplifier section. Rl7 is calibration tTim control with approximately dB of range_ This allows for finc calibration adjustments made between the settings of the sensitivity switch SWI_ The power supply common connects to Pl pin 9 A dropping resistor R28 is included on the SA14-121 assembly limit meter lamp current. An additional loop through connector P2 has been provided for the lamp power This incorporated make the VU meter assembly modular (no direct wiring), with improved serviceability The VU meter lamps plug into P2 pins and 2 while the meter power connects to Pl pins and [0. The one half supply bias voltage is applied UIA through bias resistor R1S. Qutput_Amplifiec UIB forms thc meter drive amplifier Its gain is set by the ratio of R18 and R20. The one half supply voltage bias is applied to pin 5 of UIB: The signal output is coupled through C6 to source impedance matching resistor R2Z This 3900 ohm resistor matches the internal impedance of the meter This impedance match imperative insure proper VU meter ballistics The VU meter connects directly the amplifier card sct specifically designed terminals The meter output drive also appears at Pl pins and This is for the application where the meter is remote from the SAI4-121 Amplifier Assembly.

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeGtQQndPRk9BTEU/view?resourcekey=0-GMfqXhmf_jT8QMNPr27_9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeGtQQndPRk9BTEU&resourcekey=0-GMfqXhmf_jT8QMNPr27_9Q" width="240" alt="1994 - M435 - 14-121-02-001 - METER AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1994|27 · 14-121-02-001 - METER AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1994%20-%20M435%20-%2014-121-02-001%20-%20METER%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFdNaDBQRF9OQnc/view?resourcekey=0-hJcQYp4ByKJu7vqi0myXbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFdNaDBQRF9OQnc&resourcekey=0-hJcQYp4ByKJu7vqi0myXbg" width="240" alt="1994 - M435 - 14-121-06-001 - METER AMPLIFIER COMPONENT.jpg"></a><br><sub>1994|27 · 14-121-06-001 - METER AMPLIFIER COMPONENT · <a href="SCHEMATICS/1994%20-%20M435%20-%2014-121-06-001%20-%20METER%20AMPLIFIER%20COMPONENT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 14-121-02-001.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M435 - RTO-144 Connections.pdf`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0QzN0NNcjJwT2M/view?resourcekey=0-cuzaa2SiEOot8-x-nNL-2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0QzN0NNcjJwT2M&resourcekey=0-cuzaa2SiEOot8-x-nNL-2g" width="240" alt="1994 - M435 - 436 - P001 - Title Page.jpg"></a><br><sub>1994|27 · 436 - P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1Q0SXk0UjZCcWc/view?resourcekey=0-S5xdCvX4A_Ga0JnA-RR_OA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1Q0SXk0UjZCcWc&resourcekey=0-S5xdCvX4A_Ga0JnA-RR_OA" width="240" alt="1994 - M435 - 436 - P002 - 1-1.jpg"></a><br><sub>1994|27 · 436 - P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUllaYUVHSF94c0k/view?resourcekey=0-dpZLsMSuR5gcrlwshYDAcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUllaYUVHSF94c0k&resourcekey=0-dpZLsMSuR5gcrlwshYDAcg" width="240" alt="1994 - M435 - 436 - P003 - 2-1.jpg"></a><br><sub>1994|27 · 436 - P003 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDdnNnFWM2g3WlE/view?resourcekey=0-PSyW92WGNEZVsRTbOT548Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDdnNnFWM2g3WlE&resourcekey=0-PSyW92WGNEZVsRTbOT548Q" width="240" alt="1994 - M435 - 436 - P004 - 3-1.jpg"></a><br><sub>1994|27 · 436 - P004 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWlVmdGF6R21McFk/view?resourcekey=0-FchX2eObpPY3_KRS8RM6wg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWlVmdGF6R21McFk&resourcekey=0-FchX2eObpPY3_KRS8RM6wg" width="240" alt="1994 - M435 - 436 - P005 - 3-2.jpg"></a><br><sub>1994|27 · 436 - P005 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVBlcjdjSXpKRTg/view?resourcekey=0-QAGUIrnWYxNquRIe5xZxng" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVBlcjdjSXpKRTg&resourcekey=0-QAGUIrnWYxNquRIe5xZxng" width="240" alt="1994 - M435 - 436 - P006 - 3-3.jpg"></a><br><sub>1994|27 · 436 - P006 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ1dIT3VlMjFRMW8/view?resourcekey=0-a_U8xFmaO0OWaaNLmpD6Jw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ1dIT3VlMjFRMW8&resourcekey=0-a_U8xFmaO0OWaaNLmpD6Jw" width="240" alt="1994 - M435 - 436 - P007 - 4-1.jpg"></a><br><sub>1994|27 · 436 - P007 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVcxTDdhNnFoek0/view?resourcekey=0-psq8wPPCzWJgmWgZcfq3gg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVcxTDdhNnFoek0&resourcekey=0-psq8wPPCzWJgmWgZcfq3gg" width="240" alt="1994 - M435 - 436 - P008 - 4-2.jpg"></a><br><sub>1994|27 · 436 - P008 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZXFQRnVZYzJONk0/view?resourcekey=0-sBz7evhI64KjkEENM_HWcQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZXFQRnVZYzJONk0&resourcekey=0-sBz7evhI64KjkEENM_HWcQ" width="240" alt="1994 - M435 - 436 - P009 - 5-1.jpg"></a><br><sub>1994|27 · 436 - P009 - 5-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0tFdXRjM3ZqVE0/view?resourcekey=0-rrX46SSn9MwM9ctem0p9aA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0tFdXRjM3ZqVE0&resourcekey=0-rrX46SSn9MwM9ctem0p9aA" width="240" alt="1994 - M435 - 436 - P010 - 6-1.jpg"></a><br><sub>1994|27 · 436 - P010 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdnVIeldVTVNwWTg/view?resourcekey=0-9naTK4n5i9iD39QQoI3Rjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdnVIeldVTVNwWTg&resourcekey=0-9naTK4n5i9iD39QQoI3Rjg" width="240" alt="1994 - M435 - 436 - P011 - 6-2.jpg"></a><br><sub>1994|27 · 436 - P011 - 6-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3d5amNUeFpRVkE/view?resourcekey=0-LJzorlKtf4ozk078TanqKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3d5amNUeFpRVkE&resourcekey=0-LJzorlKtf4ozk078TanqKQ" width="240" alt="1994 - M435 - 436 - P012 - 7-1.jpg"></a><br><sub>1994|27 · 436 - P012 - 7-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUEhCN0dWZjdaQ1U/view?resourcekey=0-aM483nTtRI15zQzKlbmXdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUEhCN0dWZjdaQ1U&resourcekey=0-aM483nTtRI15zQzKlbmXdQ" width="240" alt="1994 - M435 - 436 - P013 - 7-2.jpg"></a><br><sub>1994|27 · 436 - P013 - 7-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEpkTjZBU3hpeGc/view?resourcekey=0-ViKDdSVc4HgrnQyTBKQjIA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEpkTjZBU3hpeGc&resourcekey=0-ViKDdSVc4HgrnQyTBKQjIA" width="240" alt="1994 - M435 - 436 - VU Meter (2).pdf"></a><br><sub>1994|27 · 436 - VU Meter (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFh1TTk0U3MyTEE/view?resourcekey=0-EY-v1ChGAb236gT3gcqu1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFh1TTk0U3MyTEE&resourcekey=0-EY-v1ChGAb236gT3gcqu1A" width="240" alt="1994 - M435 - 436 - VU Meter.pdf"></a><br><sub>1994|27 · 436 - VU Meter</sub></td></tr>
</table>

Not on Google Drive yet: `M435-436 - P005 - 3-2(1).jpg`, `M435-436 - P005 - 3-2.jpg`, `MP1-MP2-MP3-MP4 - P030 - M435-436 - 3-1.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1994 - M435 - 14-121-02-001 - METER AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1994%20-%20M435%20-%2014-121-02-001%20-%20METER%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1994 - M435 - 436 - VU Meter p14.kicad_sch](KICAD/1994%20-%20M435%20-%20436%20-%20VU%20Meter%20p14.kicad_sch)
- [19xx - 14-121-02-001.kicad_sch](KICAD/19xx%20-%2014-121-02-001.kicad_sch)
- [M435.kicad_sym](KICAD/M435.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
