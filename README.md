# Instructions for Breadcrumb-Boards

## Ordering from JLCPCB

Visit [JLCPCB.com](https://jlcpcb.com/) or a manufacturer of your choice (Instructions should work almost identically).

Navigate to **Products** → **FR4-PCBs** → **Get Instant Quote**

Upload the needed Gerber-Files as .zip and wait until the upload is completed, now you should see a preview of the uploaded PCBs

### Settings

The first few settings should be set automatically, check these because errors can occur:
- **Base Material:** FR-4
- **Layers:** 2
- **Dimensions:** should be set automatically (if you are not sure, check the PCB dimensions in [mechanical](https://github.com/kkitdesign/breadcrumb-board/tree/main/mechanical))
- **PCB Qty:** Enter your needed quantity (*Note:* the more PCBs you order the cheaper they get per Unit)
- **Product Type:** Industrial/Consumer electronics

#### PCB Specifications

- **Different Design:** 1
- **Delivery Format:** Single PCB
- **PCB Thickness:** 1.6mm is preferred but thicker or thinner PCBs can be chosen if needed
- **PCB Color:** the color you like most
- **Silkscreen:** (gets chosen automatically)
- **Surface Finish:** HASL(with lead) or LeadFree HASL (LeadFree is recommended for less toxins)

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

As the PCB is only made for THT-components a Stecil is not needed.

## Mounting and Integration

The Breadcrumb-Boards can be mounted to your project using M2-screws, the position of the holes can be found in [mechanical](https://github.com/kkitdesign/breadcrumb-board/tree/main/mechanical)