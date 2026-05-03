# Anweisungen für Breadcrumb-Boards

## Bestellung bei JLCPCB

Besuche [JLCPCB.com](https://jlcpcb.com/) oder einen Hersteller deiner Wahl (die Anweisungen sollten nahezu identisch funktionieren).

Navigiere zu **Products** → **FR4-PCBs** → **Get Instant Quote**

Lade die benötigten Gerber-Dateien als .zip hoch und warte, bis der Upload abgeschlossen ist. Nun solltest du eine Vorschau der hochgeladenen PCBs sehen.

### Einstellungen

Die ersten Einstellungen sollten automatisch gesetzt werden. Überprüfe diese, da Fehler auftreten können:
- **Base Material:** FR-4
- **Layers:** 2
- **Dimensions:** sollten automatisch gesetzt werden (falls du dir nicht sicher bist, überprüfe die PCB-Abmessungen unter [mechanical](https://github.com/kkitdesign/breadcrumb-board_de/tree/main/mechanical))
- **PCB Qty:** Gib die benötigte Menge ein (*Hinweis:* Je mehr PCBs du bestellst, desto günstiger werden sie pro Einheit)
- **Product Type:** Industrial/Consumer electronics

#### PCB Specifications

- **Different Design:** 1
- **Delivery Format:** Single PCB
- **PCB Thickness:** 1.6mm wird bevorzugt, aber dickere oder dünnere PCBs können bei Bedarf gewählt werden
- **PCB Color:** die Farbe, die dir am besten gefällt
- **Silkscreen:** (wird automatisch gewählt)
- **Surface Finish:** HASL(with lead) oder LeadFree HASL (LeadFree wird wegen geringerer Toxizität empfohlen)

#### High-spec Options

- **Outer Copper Weight:** 1oz
- **Via Covering:** Tented
- **Via Plating Method:** Not Specified
- **Min via hole size/diameter:** 0.3mm/(0.4/0.45mm)
- **Board Outline Tolerance:** ±0.2mm(Regular)
- **Confirm Production file:** No
- **Mark on PCB:** Remove Mark
- **Electrical Test:** Flying Probe Fully Test
- **Gold Fingers:** No
- **Castellated Holes:** No
- **Edge Plating:** No
- **Blind Slots:** No
- **UL Marking:** No

#### Stencil

Da die PCB nur für THT-Bauteile ausgelegt ist, wird kein Stencil benötigt.

## Montage und Integration

Die Breadcrumb-Boards können mit M2-Schrauben an deinem Projekt befestigt werden. Die Position der Bohrungen findest du unter [mechanical](https://github.com/kkitdesign/breadcrumb-board_de/tree/main/mechanical).