# M453A Cue Amplifier · Amplifiers

Ward-Beck Systems M453A, 1978|11. Wiki page: [M453A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M453A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 41 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 12 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 220 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 12 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 43 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [8 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1979 - M453A - Cue Amplifier (2).pdf](MANUALS/1979%20-%20M453A%20-%20Cue%20Amplifier%20(2).pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;To line output | 18 dB !2 ae. to Sp e a ~ e rOut put: 35 dB ! 2 dB. |
| **Frequency response** | ! 1 dB from SO Hz to 10 kHz. |
| **Noise** | 7S dB below 3 watts or +I B dBm output (20 Hz to 20 kHz). |
| **Harmonic distortion** | Less than 0.5 ~ from 100 Hz t o 5 kHz at 3 watts or T18 dBm out put. |
| **Source impedances** |  |
| &nbsp;&nbsp;Slimming input | 30.000 ohms. balanced. per source. |
| **All other inputs** | 600 ohms or less. balanced. |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing input | Less than 5 ohms. |
| **All other inputs** | 30.000 ohms. |
| **Input levels** |  |
| &nbsp;&nbsp;Summing input | o dBm via 30 k ohm summing networ ~. |
| **All other inputs** | o dBm nominal. tI 8 dBm maximum. |
| **Output impedances** |  |
| &nbsp;&nbsp;Line | 150 ohms. balanced. |
| &nbsp;&nbsp;Speaker | Less than 0.5 ohm. p s. |

## Circuit description

From [1979 - M453A - Cue Amplifier (2).pdf](MANUALS/1979%20-%20M453A%20-%20Cue%20Amplifier%20(2).pdf) pages 7-12 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**H4 53A CUE AMPLIFIER**

The M453A is Icu e ee pl t t t e r with l 3Wl tt output clp lbt l t t y. Pro.ision is. lde t o connect the l. pl i f i er output to the sp el ter either directly o r.i lin i nte grll Muting rel lY. I n lddi tion tot he Spel ter output, I bll inte d, +8 dB. line out put 15.'de I.aillbl e.

Inputs Three types of inputs are pre v t ded:

a) SUI,,,..ing Input: Designed to operate from the cue Mixing bus of an audio console.

b) Direct Input: Designed t o work from an external 600 ohm lu di o source.

c) Switched Inputs: Two additional inputs are provided, entering the module via solid state cross point switches Z3 and Z4. These inputs maybe utilized for intercom requirements, such as from i nnou nce booth or news room facilities.

Pre amplifier ind Insert II with 1ts l s s oci i ted co~p onen ts COMprises the prel.pllfie r s ectton. CIO couples the pre amp output tot he front pinel le.e l control R26. FrOM R26. the slgnl l i s fed t o Module connector p l n 7, which 15 normally strapped t o pln 8. Re MoYll oft hIs connection perMits insertion of in external level control lOCi ted i t lnot her ope r. t l ng.rea of the console. Out put AMplifier Fro. pin 8 of the module connector, the signal is coup led to the out put aMplifier sect ton via Cll, R29.nd R30. R29 Ml 1 be jUMper ed by Jl to inc r e.s e overall aMplifier gain by 10 dB. The output aMplifier co ns1sts of I2 with its associated components. An actively balanced line output is brought out

It module connector pins 14/R.fter passing through CI9, C20,

R41 Ind R42.

**CIRCUIT OESCRIPTIO N**

The Jwatt speaker output is derived from the lower half of Z2. Coupled through C2 1, the signal app ears at the DIRECT out put at pinS. Alternatively, when muting of the cue speaker is required, the SWITCHED output at pin 15 should be connected t o the cues peak e r.

The common return fort he cue speaker appears at pins 16 &amp; T. Muting The mu tfng relay K1 i s normally energized. Connecting the mute control input at pin X t o CONTROL COMMON will sst t c hoff QJ, causing K1 to de energize, i n turn disconnecting the outputs i gna l to pin 15.

Muting canals o be achieved by operating SWl, located at the front panel of the module. The LED DSI will be illuminated to indicate muted status.

Input CrosspOfn ts ZJ and Z4 are CMOS analog swt t che s, servin g' ass ol id state crosspo i nts for inputs ' 2 and 1 3, These f nput s are used for intercom app1 i cations and are switched from their respective remote locations.

Both switches are normally OFF. Connect ing the control inputs at pins 17 or U to CONTROL COMMON will switch the corresponding c ros spoint ON.

Power Supply Decoupl1ng The M4 5JA i s designed to operate from a single 25 volt regulated supply. Fuse Fl is integral tot he module and will open if power dissipation becomes exceSSive. CR5 protects the amplifier from inadvertent supply voltage reversal. Additional filtering is provided by C7.

**PARTS LIST**

PART OESCR I PT ION MFG MFG PART NUMBER ci Capacitor uF 135 V Keme t T390B 105 M035AS

C5 &quot; 0.22 uF/35 V &quot; TJ 90A224M03 5AS

&quot; u F/25 V Philips 437ETF470 CB &quot; uF / 25 V Keme l T 390E476M0 25A 5

COO &quot; &gt;0 uF/ 25 V &quot; T39OC106 M02SA,S

CO2 &quot; a.a u F/2s V &quot; TJ90B 225M0 25A,S cr a &quot; 22 uF/25 V Philips 42f&gt; ET F22

ss, F Ase l co Philips

**CQ92-MC-J 32M**

2222-6 36 -70689

C'6 &quot; 22 u F / 25 V &quot; 426 ETFZ 2 ctv &quot; 4700, F A se l co C0 9 2_ MC-Io72 Mere &quot; aao,F Philips 222 2-630_032 21 C&lt;9 &quot; 22 u F/25 V &quot; 426ETF 22

C2&lt; &quot; &gt;000 uF/16 V &quot; 437ETE 1000 C22 &quot; 22 u F/ZS V &quot; 426ETF22 C23 &quot; &gt;00 u F/2s V &quot; 426 ETF 100 C2' delete

C&quot;' Diode F a i.-.:hil d l N4148

C&quot;' &quot; Motorola l N4003

CR' &quot; F ai rc h i ld lN41 46

&quot; Motorola 1N4 00J &quot;, Zen er

CR' &quot; l N753A

OS&lt; LED, F &quot;, i r Child F LV1 17

**PARTS LIST**

PART DESCRIPTION M'G M' G PART NUMBER

&quot; Fuse, 0.75,10,,. a. 8 &quot; 11.5 AGe 3/'

C I lOr&quot; MR8 JA24 &quot; Rel:lY

0&gt; Transls tor N:l t lon:l l PNJ S69 02 &quot; F &lt;l l rc hi l d 2N3 569

&quot;, Resistor 1!4W &quot; &quot; '&quot; Philips

lOOK &quot;

&quot; lOOK

**220 K**

ea &quot; &quot;3 &quot;

**PARTS LIST**

PART OESCR I PTIO N PART NUMBER,,. Po tenl iome te r Ala was 10-0 15

Res lstOt' 1! 4W

Philips

lOOK &quot;

delete

Re slstOt' 1!2W SIRe sis tOt' 1! 4W S'

Resistor l /2W S' 2&lt;, &quot;', Resistor 3.7SW

Dille CW-2B

Switch Schedow WBS 11-005

**&quot;&quot;'''5 3A CUE AMPLIFIER**

PART DESCRIPTION MFe MFe PART NUMBER

In l~ grllt e d

Cifo&lt;:&quot;&quot;i l Nll t ion lll

**LMJ ?7N**

COloOl 6C N

**CONTROL KNOBS, CAPS AND BUTTONS**

USED ON DESCRIPTION MFe MFG PART NUMBER

ROO Knob (Blll c k) El m.. 021_35 20 Coo (Blll c k } &quot; 040-3620

5W' Bu lt o n (Wn il e) Sck lldow F G_V.'H

was recommends l n e use o f ~p lllcemenl Pllr t&quot; mll~ by t ke specified mllnuf ac tu~ rs forcoro ti&quot; ueCl optimum ~au lpmenl p....form.. n c e,

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOFd5RkFJZFRsLVU/view?resourcekey=0-4ZXqO7AGlkahr8GGqiTwMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOFd5RkFJZFRsLVU&resourcekey=0-4ZXqO7AGlkahr8GGqiTwMg" width="240" alt="1978 - M453A - 453-04-006 - MUTING SMITCH SWI NHEN DEPRESSED MUEES THE EAKER.jpg"></a><br><sub>1978|11 · 453-04-006 - MUTING SMITCH SWI NHEN DEPRESSED MUEES THE EAKER · <a href="MECHANICAL/1978%20-%20M453A%20-%20453-04-006%20-%20MUTING%20SMITCH%20SWI%20NHEN%20DEPRESSED%20MUEES%20THE%20EAKER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDk4WGY5RmpzSjg/view?resourcekey=0-XbdfUhcXqXx6idFxDFIDaA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDk4WGY5RmpzSjg&resourcekey=0-XbdfUhcXqXx6idFxDFIDaA" width="240" alt="1978 - M453A - 453-04-006 - OPE- RATES THE ASSOC IATED DSI.jpg"></a><br><sub>1978|11 · 453-04-006 - OPE- RATES THE ASSOC IATED DSI · <a href="MECHANICAL/1978%20-%20M453A%20-%20453-04-006%20-%20OPE-%20RATES%20THE%20ASSOC%20IATED%20DSI%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTkdSR3RQck1ZTnc/view?resourcekey=0-ybvaSobByomcZUJlbM0e1Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTkdSR3RQck1ZTnc&resourcekey=0-ybvaSobByomcZUJlbM0e1Q" width="240" alt="1978 - M453A - 453-01-002 - CUE AMPLIFIER.jpg"></a><br><sub>1978|11 · 453-01-002 - CUE AMPLIFIER · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-01-002%20-%20CUE%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMG1NX0JXVEpJRWs/view?resourcekey=0-yZDMQRmhGxT8T9xs9c9AnQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMG1NX0JXVEpJRWs&resourcekey=0-yZDMQRmhGxT8T9xs9c9AnQ" width="240" alt="1978 - M453A - 453-01-002 - CUE LEVEL SUMMING INPUT SUM INSERT.jpg"></a><br><sub>1978|11 · 453-01-002 - CUE LEVEL SUMMING INPUT SUM INSERT · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-01-002%20-%20CUE%20LEVEL%20SUMMING%20INPUT%20SUM%20INSERT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFlsR1Q2blhLWWs/view?resourcekey=0-7iW-dI0dwhOTuDgv-IY6jg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFlsR1Q2blhLWWs&resourcekey=0-7iW-dI0dwhOTuDgv-IY6jg" width="240" alt="1978 - M453A - 453-02-002 - MUTE ASSIGN.jpg"></a><br><sub>1978|11 · 453-02-002 - MUTE ASSIGN · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-02-002%20-%20MUTE%20ASSIGN%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemFyYm9hMkNfWFU/view?resourcekey=0-7dF_xLdlpY8XXnVFsRykGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemFyYm9hMkNfWFU&resourcekey=0-7dF_xLdlpY8XXnVFsRykGg" width="240" alt="1978 - M453A - 453-02-002 - PUK ISSUOATE VILC.jpg"></a><br><sub>1978|11 · 453-02-002 - PUK ISSUOATE VILC · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-02-002%20-%20PUK%20ISSUOATE%20VILC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEliM2xjSnVpRjg/view?resourcekey=0-L3Ylmvj8ye_iikk2Rz3JTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEliM2xjSnVpRjg&resourcekey=0-L3Ylmvj8ye_iikk2Rz3JTQ" width="240" alt="1978 - M453A - 453-06-002 - CUE AMPLIFIER COMPONENT LAYOUT.jpg"></a><br><sub>1978|11 · 453-06-002 - CUE AMPLIFIER COMPONENT LAYOUT · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-06-002%20-%20CUE%20AMPLIFIER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnl6WV9ZWEdLeGs/view?resourcekey=0-vqpC_jnwodKz-cnfiiA3Vg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnl6WV9ZWEdLeGs&resourcekey=0-vqpC_jnwodKz-cnfiiA3Vg" width="240" alt="1978 - M453A - 453-06-002.jpg"></a><br><sub>1978|11 · 453-06-002 · <a href="SCHEMATICS/1978%20-%20M453A%20-%20453-06-002%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1IRahFbsPHBcdvuXsdKtytXjyfr8PAlmE/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1IRahFbsPHBcdvuXsdKtytXjyfr8PAlmE" width="240" alt="19xx - M453A - DOC - 600-02-001 - INPUT CHANNEL SCHEMA TIC.png"></a><br><sub>19xx - M453A - DOC - 600-02-001 - INPUT CHANNEL SCHEMA TIC · <a href="SCHEMATICS/19xx%20-%20M453A%20-%20DOC%20-%20600-02-001%20-%20INPUT%20CHANNEL%20SCHEMA%20TIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1rWpiNimcQYvKcAPqbaYQ8hIY2sQiaj62/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1rWpiNimcQYvKcAPqbaYQ8hIY2sQiaj62" width="240" alt="19xx - M453A - DOC - 600-02-007 - CUE CHANNEL SCHEMA TIC.png"></a><br><sub>19xx - M453A - DOC - 600-02-007 - CUE CHANNEL SCHEMA TIC · <a href="SCHEMATICS/19xx%20-%20M453A%20-%20DOC%20-%20600-02-007%20-%20CUE%20CHANNEL%20SCHEMA%20TIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1uNZQpFQsRJmutVdnGzn-J-Fj0CyRnUUP/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1uNZQpFQsRJmutVdnGzn-J-Fj0CyRnUUP" width="240" alt="2006 - M453A - DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION.jpg"></a><br><sub>2006|39 · DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION · <a href="SCHEMATICS/2006%20-%20M453A%20-%20DOC%20-%20920063-01-001%20-%20MONIORMQDULE%20SWTCHED%20DIRECT%20SSUE%20REMSION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M453A - P16 - Layout.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFV5MFNzek5iWjQ/view?resourcekey=0-7dM9gwsmJMGNHswRlpqs4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFV5MFNzek5iWjQ&resourcekey=0-7dM9gwsmJMGNHswRlpqs4g" width="240" alt="1978 - M453A - P17 - Pin Out.jpg"></a><br><sub>1978|11 · P17 - Pin Out · <a href="PINOUTS/1978%20-%20M453A%20-%20P17%20-%20Pin%20Out%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M453A - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 7 of 9 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P1-18: kept N/C (nc); RTO-144 sheet says GND (ground)
- disagree P1-19: kept N/C (nc); RTO-144 sheet says VEE-AUDIO (power)

**Inserts:** PREAMP / POWER AMP INSERT: PREAMP OUT → PWR AMP IN

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INPUT #1 | in | INPUT 1 | high |
| 2 | INPUT #2 | in | INPUT 2 | high |
| 3 | INPUT #3 | in | INPUT 3 | high |
| 4 | INPUT SHIELD | shield | INPUTS shield | high |
| 5 | SUMMING INPUT | in | SUMMING INPUT | high |
| 6 | N/C | nc |  | high |
| 7 | PREAMP OUT | insert_send | PREAMP OUT | high |
| 8 | PWR AMP IN | insert_return | PWR AMP IN | high |
| 9 | N/C | nc |  | high |
| 10 | N/C | nc |  | high |
| 11 | N/C | nc |  | high |
| 12 | N/C | nc |  | high |
| 13 | N/C | nc |  | high |
| 14 | LINE OUTPUT | out | LINE OUTPUT | high |
| 15 | SWITCHED OUTPUT | out | SWITCHED OUTPUT | high |
| 16 | OUTPUT COMMON | ground |  | high |
| 17 | INPUT 2 CONTROL | control_in | I/P #2 CTL | high |
| 18 | N/C | nc |  | high |
| 19 | N/C | nc |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS GROUND | ground |  | high |
| A | INPUT #1 | in | INPUT 1 | high |
| B | INPUT #2 | in | INPUT 2 | high |
| C | INPUT #3 | in | INPUT 3 | high |
| D | INPUT SHIELD | shield | INPUTS shield | high |
| E | SUMMING INPUT | in | SUMMING INPUT | high |
| F | N/C | nc |  | high |
| H | N/C | nc |  | high |
| J | N/C | nc |  | high |
| K | N/C | nc |  | high |
| L | N/C | nc |  | high |
| M | N/C | nc |  | high |
| N | N/C | nc |  | high |
| P | N/C | nc |  | high |
| R | LINE OUTPUT | out | LINE OUTPUT | high |
| S | DIRECT OUTPUT | out | DIRECT OUTPUT | high |
| T | OUTPUT COMMON | ground |  | high |
| U | INPUT 3 CONTROL | control_in | I/P #3 CTL | high |
| V | N/C | nc |  | high |
| W | MUTE ASSIGN | control_in | MUTE ASSIGN | high |
| X | MUTE CONTROL | control_in | MUTE CTL | high |
| Y | +25 V CONTROL | power |  | high |
| Z | CONTROL COMMON | ground |  | high |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.X.18: P2-X P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.20.18: P2-20 P2-18 · JMP.22.21: P2-22 P2-21 · JMP.Z.Y: P2-Z P2-Y · JMP.20.19: P2-20 P2-19 · JMP.X.W: P2-X P2-W

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFRyQmNUUE4zclk/view?resourcekey=0-0EG-rtQveMLs5STzBTcfbA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFRyQmNUUE4zclk&resourcekey=0-0EG-rtQveMLs5STzBTcfbA" width="240" alt="1978 - M453A - P01 - Cover.jpg"></a><br><sub>1978|11 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ09ZWXA1Nlc0dVU/view?resourcekey=0-qlaObFtVfG1MsYslIgl5-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ09ZWXA1Nlc0dVU&resourcekey=0-qlaObFtVfG1MsYslIgl5-g" width="240" alt="1978 - M453A - P02.jpg"></a><br><sub>1978|11 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ2ZVT0lVSXVvWnM/view?resourcekey=0-wKYA13S6D6HyqYJCGV7y0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ2ZVT0lVSXVvWnM&resourcekey=0-wKYA13S6D6HyqYJCGV7y0g" width="240" alt="1978 - M453A - P04 - Warranty.jpg"></a><br><sub>1978|11 · P04 - Warranty</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0gtNFZibEJJeW8/view?resourcekey=0-xvMkPPCAq3tntigOicYK7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0gtNFZibEJJeW8&resourcekey=0-xvMkPPCAq3tntigOicYK7w" width="240" alt="1978 - M453A - P05 - 1-1.jpg"></a><br><sub>1978|11 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVJBdm05MjRlM28/view?resourcekey=0-0VPniOQUzljAAUj9wISo3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVJBdm05MjRlM28&resourcekey=0-0VPniOQUzljAAUj9wISo3g" width="240" alt="1978 - M453A - P06 - 1-2.jpg"></a><br><sub>1978|11 · P06 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKamxzdXk5RjR5MWs/view?resourcekey=0-kONgFMeDQ_x1BcUhUGnV5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKamxzdXk5RjR5MWs&resourcekey=0-kONgFMeDQ_x1BcUhUGnV5Q" width="240" alt="1978 - M453A - P07 - 2-1.jpg"></a><br><sub>1978|11 · P07 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWN3YWlxZFgwbVk/view?resourcekey=0-Gv1P-1GSmOnBix3v_vweZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWN3YWlxZFgwbVk&resourcekey=0-Gv1P-1GSmOnBix3v_vweZg" width="240" alt="1978 - M453A - P08 - 2-2.jpg"></a><br><sub>1978|11 · P08 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUF1QVBfQXU1QVk/view?resourcekey=0-F1QJFr0PQU-bLXvgrwTHAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUF1QVBfQXU1QVk&resourcekey=0-F1QJFr0PQU-bLXvgrwTHAg" width="240" alt="1978 - M453A - P09 - 3-1.jpg"></a><br><sub>1978|11 · P09 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkJXbWFKTlpsMnc/view?resourcekey=0-Sp344vupNJYY-drTndhQOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkJXbWFKTlpsMnc&resourcekey=0-Sp344vupNJYY-drTndhQOw" width="240" alt="1978 - M453A - P1.jpg"></a><br><sub>1978|11 · P1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0ItYjNkOGY5RGM/view?resourcekey=0-mxP8kQVNEH8iroD168o_9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0ItYjNkOGY5RGM&resourcekey=0-mxP8kQVNEH8iroD168o_9w" width="240" alt="1978 - M453A - P10 - 3-2.jpg"></a><br><sub>1978|11 · P10 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWEtZG1mODRGVVE/view?resourcekey=0-Epzirs43wPD9UrKZxOaa2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWEtZG1mODRGVVE&resourcekey=0-Epzirs43wPD9UrKZxOaa2Q" width="240" alt="1978 - M453A - P10.jpg"></a><br><sub>1978|11 · P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY3pwOHAtazNEVUE/view?resourcekey=0-Vla6URn_NIsuVIvCJmErKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY3pwOHAtazNEVUE&resourcekey=0-Vla6URn_NIsuVIvCJmErKA" width="240" alt="1978 - M453A - P11 - 3-3.jpg"></a><br><sub>1978|11 · P11 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRnpRRjRUWTNYRm8/view?resourcekey=0-_ANUzGKYhPrAbAFYZZeFfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRnpRRjRUWTNYRm8&resourcekey=0-_ANUzGKYhPrAbAFYZZeFfA" width="240" alt="1978 - M453A - P11.jpg"></a><br><sub>1978|11 · P11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcV9oRjFrOFFRNXc/view?resourcekey=0-vIcVQ1tj_i_pm-wX_lZ5GQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcV9oRjFrOFFRNXc&resourcekey=0-vIcVQ1tj_i_pm-wX_lZ5GQ" width="240" alt="1978 - M453A - P12 - 3-4.jpg"></a><br><sub>1978|11 · P12 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkJqUHV4SHJzRHM/view?resourcekey=0-VE6pJxhOe6caI6X3tkWR6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkJqUHV4SHJzRHM&resourcekey=0-VE6pJxhOe6caI6X3tkWR6A" width="240" alt="1978 - M453A - P13.jpg"></a><br><sub>1978|11 · P13</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTlmdUFzVDNZM1k/view?resourcekey=0-iDYd8ygLNVG-gz3Z5rLOHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTlmdUFzVDNZM1k&resourcekey=0-iDYd8ygLNVG-gz3Z5rLOHw" width="240" alt="1978 - M453A - P2.jpg"></a><br><sub>1978|11 · P2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2pRcEZ2d3dLTU0/view?resourcekey=0-yKjXQdXAGOa4Ap2MGxu0-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2pRcEZ2d3dLTU0&resourcekey=0-yKjXQdXAGOa4Ap2MGxu0-w" width="240" alt="1978 - M453A - P3.jpg"></a><br><sub>1978|11 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbWhBTmVhR1Mybjg/view?resourcekey=0-vFpHRdqQY1IzlfSKp701bQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbWhBTmVhR1Mybjg&resourcekey=0-vFpHRdqQY1IzlfSKp701bQ" width="240" alt="1978 - M453A - P4.jpg"></a><br><sub>1978|11 · P4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkF1OVdXY3otMjA/view?resourcekey=0-3dmcB9rLzxDvB7jJfHwnRA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkF1OVdXY3otMjA&resourcekey=0-3dmcB9rLzxDvB7jJfHwnRA" width="240" alt="1978 - M453A - P5.jpg"></a><br><sub>1978|11 · P5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3dMTmd0bkdIZTA/view?resourcekey=0-s8fmE0FMza2PLHtsdBL3Vw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3dMTmd0bkdIZTA&resourcekey=0-s8fmE0FMza2PLHtsdBL3Vw" width="240" alt="1978 - M453A - P6.jpg"></a><br><sub>1978|11 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdTRkV0hRRmVQemM/view?resourcekey=0-JUjA-jw7XfbJV5My1-PCjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdTRkV0hRRmVQemM&resourcekey=0-JUjA-jw7XfbJV5My1-PCjA" width="240" alt="1978 - M453A - P7.jpg"></a><br><sub>1978|11 · P7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzliQUU2ZGlNdzg/view?resourcekey=0--QaYe4eoCroHeAkNpum-PQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzliQUU2ZGlNdzg&resourcekey=0--QaYe4eoCroHeAkNpum-PQ" width="240" alt="1978 - M453A - P8.jpg"></a><br><sub>1978|11 · P8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYk9QZklSTWVQd3c/view?resourcekey=0-MIybqdrT6ceraTq9QFA9Vg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYk9QZklSTWVQd3c&resourcekey=0-MIybqdrT6ceraTq9QFA9Vg" width="240" alt="1978 - M453A - P9.jpg"></a><br><sub>1978|11 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNHh6enJ6T3hKMnc/view?resourcekey=0-ZrXZaWm_gY-tjQVJ-Zkqxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNHh6enJ6T3hKMnc&resourcekey=0-ZrXZaWm_gY-tjQVJ-Zkqxw" width="240" alt="1979 - M453A - Cue Amplifier (2).pdf"></a><br><sub>1979|12 · Cue Amplifier (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdGM3b01BNXRCTW8/view?resourcekey=0-TiwhSGm6h75wH1Bgw-4GRg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdGM3b01BNXRCTW8&resourcekey=0-TiwhSGm6h75wH1Bgw-4GRg" width="240" alt="1979 - M453A - Cue Amplifier.pdf"></a><br><sub>1979|12 · Cue Amplifier</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWdBX3NiUkNWWG8/view?resourcekey=0-sx36hHRuU4vzFEKWH5Rj8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWdBX3NiUkNWWG8&resourcekey=0-sx36hHRuU4vzFEKWH5Rj8A" width="240" alt="1979 - M453A - P03 - TOC.jpg"></a><br><sub>1979|12 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSmRCMHJZdHFONlE/view?resourcekey=0-z4xRxlDDk3Kw1hbJYqH60w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSmRCMHJZdHFONlE&resourcekey=0-z4xRxlDDk3Kw1hbJYqH60w" width="240" alt="19xx - M453A - DOC - R1400-R2400 - 013.jpg"></a><br><sub>19xx - M453A - DOC - R1400-R2400 - 013</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSl92a2Vxa2NMc2s/view?resourcekey=0-2dfokMOlctdKaW5lsZMp_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSl92a2Vxa2NMc2s&resourcekey=0-2dfokMOlctdKaW5lsZMp_g" width="240" alt="19xx - M453A - DOC - R1400-R2400 - 014.jpg"></a><br><sub>19xx - M453A - DOC - R1400-R2400 - 014</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/195lEahX2BRue_z8U5Hva6TGEM8oOl0-i/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=195lEahX2BRue_z8U5Hva6TGEM8oOl0-i" width="240" alt="2015 - M453A - DOC - PSCILLATOE MQDULE UNE SELECTOR INPUTS.jpg"></a><br><sub>2015|48 · DOC - PSCILLATOE MQDULE UNE SELECTOR INPUTS</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1990|23 · DOC - CHIN Radio R14000001](https://drive.google.com/file/d/0B0yR0b5T78SKYld2RThnMU1tLW8/view?resourcekey=0-ZPb2apzcpMkiRBWF0YEm7Q)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M453A - 453-01-002 - CUE AMPLIFIER.kicad_sch](KICAD/1978%20-%20M453A%20-%20453-01-002%20-%20CUE%20AMPLIFIER.kicad_sch)
- [1978 - M453A - 453-01-002 - CUE LEVEL SUMMING INPUT SUM INSERT.kicad_sch](KICAD/1978%20-%20M453A%20-%20453-01-002%20-%20CUE%20LEVEL%20SUMMING%20INPUT%20SUM%20INSERT.kicad_sch)
- [1978 - M453A - 453-02-002 - MUTE ASSIGN.kicad_sch](KICAD/1978%20-%20M453A%20-%20453-02-002%20-%20MUTE%20ASSIGN.kicad_sch)
- [1978 - M453A - 453-02-002 - PUK ISSUOATE VILC.kicad_sch](KICAD/1978%20-%20M453A%20-%20453-02-002%20-%20PUK%20ISSUOATE%20VILC.kicad_sch)
- [1979 - M453A - Cue Amplifier (2) p14.kicad_sch](KICAD/1979%20-%20M453A%20-%20Cue%20Amplifier%20(2)%20p14.kicad_sch)
- [1979 - M453A - Cue Amplifier p14.kicad_sch](KICAD/1979%20-%20M453A%20-%20Cue%20Amplifier%20p14.kicad_sch)
- [1979 - M453A - Cue Amplifier p15.kicad_sch](KICAD/1979%20-%20M453A%20-%20Cue%20Amplifier%20p15.kicad_sch)
- [19xx - M453A - DOC - 600-02-001 - INPUT CHANNEL SCHEMA TIC.kicad_sch](KICAD/19xx%20-%20M453A%20-%20DOC%20-%20600-02-001%20-%20INPUT%20CHANNEL%20SCHEMA%20TIC.kicad_sch)
- [19xx - M453A - DOC - 600-02-007 - CUE CHANNEL SCHEMA TIC.kicad_sch](KICAD/19xx%20-%20M453A%20-%20DOC%20-%20600-02-007%20-%20CUE%20CHANNEL%20SCHEMA%20TIC.kicad_sch)
- [2006 - M453A - DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION.kicad_sch](KICAD/2006%20-%20M453A%20-%20DOC%20-%20920063-01-001%20-%20MONIORMQDULE%20SWTCHED%20DIRECT%20SSUE%20REMSION.kicad_sch)
- [M453A.kicad_sym](KICAD/M453A.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
