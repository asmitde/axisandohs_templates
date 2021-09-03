# Aerosoft CRJ Configuration

The following templates are provided in this folder:
1. ASCRJ_YOKE_HCALPHA
1. ASCRJ_TQ_HCBRAVO
1. ASCRJ_FCP_HCBRAVO

## Importing and applying templates
To import and use the templates, please follow these steps:
1. Launch MSFS and load into an aircraft parking stand with the Aerosoft CRJ550/700.
1. Launch Axis and Oh's and wait for it to connect to the sim. The aircraft name will be displayed at the top, once it is connected.
1. Click on Templates > Import Template. Select a `ASCRJ_*.tmpl` file from this repository. Select Import.
1. Once the import is finished, click on Templates > Apply a template to this aircraft. Select the imported `ASCRJ_*` template from the list and click Apply.
1. If asked whether to replace or merge the config, select as you need. (Choose replace for a clean configuration.)
1. Set up a new profile in MSFS for the hardware with the bindings as mentioned below for each template.
1. Power up the aircraft and test the various switches on the hardware.

---
## ASCRJ_YOKE_HCALPHA
The template does not provide any axis bindings. You need to set up the bindings in MSFS control settings.

In MSFS control settings, create a new profile for the Alpha Yoke.

### **Remove/unbind the following yoke switches:**

1. Rear white PTT button on left horn (Joystick Button 1)
1. Front white button on left horn (Joystick Button 2)
1. Red AP disconnect button on right horn (Joystick Button 4)
1. Black trim switches on left horn (Joystick Buttons 5 - 8)
1. Black trim switches on right horn (Joystick Buttons 9 - 12)
1. BCN, LAND, TAXI, NAV, STROBE switches (Joystick Buttons 21 - 30)
1. Magneto switch positions OFF and R (Joystick Buttons 31 - 32)

### **Bind the following yoke axis:**
1. Joystick L-Axis X : AILERONS AXIS
1. Joystick L-Axis Y : ELEVATOR AXIS

### **Bindings automatically applied by template:**

#### **Rear PTT button (left horn):**
_Action:_ No functional action in the sim. Bind the button to any ATC software's PTT key, such as for vPilot or Pilot2ATC.

_Use:_ Press and hold for talking on radio.

_Animation:_ R/T button on the yoke.

#### **Front white button (left horn):**
_Action:_ Flight director pitch sync.

_Use:_ Press to sync the flight director vertical guidance to the current pitch. Only works with supported modes.

_Animation:_ None. The button is not modeled, but present in the real aircraft yoke at the back.

#### **Trim switches (left horn):**
_Action:_ Pitch trim up/down.

_Use:_ Push up and hold both switches together to trim nose down. Pull down and hold both switches together to trim nose up.

_Animation:_ Electric pitch trim switches on the yoke.

#### **Top trim switch (right horn):**
_Action:_ Aileron trim left/right.

_Use:_ Push left and hold switch to trim aileron left. Push right and hold switch to trim aileron right.

_Animation:_ Aileron trim switches on the lower center pedestal.

#### **Bottom trim switch (right horn):**
_Action:_ Rudder trim left/right.

_Use:_ Push left and hold switch to trim rudder left. Push right and hold switch to trim rudder right.

_Animation:_ Rudder trim knob on the lower center pedestal.

#### **Red button (right horn):**
_Action:_ Autopilot disconnect.

_Use:_ Press twice in quick succession to disconnect the autopilot.

_Animation:_ AP/SP DISC button on the yoke.

#### **BCN switch (switch panel):**
_Action:_ Beacon lights on/off.

_Use:_ Put in up position to turn beacon lights off. Put in down position to turn beacon lights on.

_Animation:_ BEACON switch on the overhead external lights panel.

#### **LAND switch (switch panel):**
_Action:_ Landing lights on/off.

_Use:_ Put in up position to turn landing lights off. Put in down position to turn landing lights on.

_Animation:_ LANDING LTS LEFT/NOSE/RIGHT switches on the lower overhead panel.

#### **TAXI switch (switch panel):**
_Action:_ Taxi lights on/off.

_Use:_ Put in up position to turn taxi lights off. Put in down position to turn taxi lights on.

_Animation:_ RECOG TAXI LTS switch on the lower overhead panel.

#### **NAV switch (switch panel):**
_Action:_ Navigation lights on/off.

_Use:_ Put in up position to turn navigation lights off. Put in down position to turn navigation lights on.

_Animation:_ NAV switch on the overhead external lights panel.

#### **STROBE switch (switch panel):**
_Action:_ Strobe lights on/off.

_Use:_ Put in up position to turn strobe lights off. Put in down position to turn strobe lights on.

_Animation:_ STROBE switch on the overhead external lights panel.

#### **Magneto R/OFF (switch panel):**
_Action:_ Parking Brake on/off.

_Use:_ Put in OFF position to set parking brake. Put in R position to release parking brake.

_Animation:_ Parking Brake handle on the lower center pedestal.


---
## ASCRJ_TQ_HCBRAVO
The template does not provide any axis bindings. You need to set up the bindings in MSFS control settings. It is assumed that the TQ is set up with the 2-Engine commercial handles using Speedbrake (Axis 1), Throttle Engine 1 (Axis 3), Throttle Engine 2 (Axis 4) and Flaps (Axis 5). Axis 2 and 5 are unused.

In MSFS control settings, create a new profile for the Bravo Throttle Quadrant.

### **Remove/unbind the following switches:**

1. Red button on Throttle 1 (Joystick Button 30)
1. Reverser handle buttons on Throttle 1 and 2 (Joystick Buttons 10 and 11)
1. Axis detent buttons on Throttle 1 and 2 (Joystick Buttons 26 and 27)
1. Gear handle (Joystick Buttons 31 and 32)

### **Bind the following throttle quadrant axes:**
1. Joystick L-Axis Y : SPOILERS AXIS
1. Joystick R Axis-Z : THROTTLE 1 AXIS (Reverse Axis ticked)
1. Joystick R Axis-Y : THROTTLE 1 AXIS (Reverse Axis ticked)
1. Joystick L-Axis Z : FLAPS AXIS (-100 TO 100%)

### **Bindings automatically applied by template:**

#### **Red button (Throttle 1):**
_Action:_ Flight directors to TOGA mode.

_Use:_ Press to engage TOGA mode on the flight directors.

_Animation:_ TOGA button on Throttle 1 handle.

#### **Reverser 1 handle button (Throttle 1):**
_Action:_ Engage maximum reverse thrust on engine 1.

_Use:_ Pull handle to engage reverser 1. Push handle back to turn off reverser 1.

_Animation:_ Reverser handle on Throttle 1.

#### **Reverser 2 handle button (Throttle 2):**
_Action:_ Engage maximum reverse thrust on engine 2.

_Use:_ Pull handle to engage reverser 2. Push handle back to turn off reverser 2.

_Animation:_ Reverser handle on Throttle 2.

#### **Axis detent button (Throttle 1):**
_Action:_ Throttle 1 to SHUT OFF/IDLE.

_Use:_ Keep Throttle 1 lever at the lowest detent position before starting flight. This keeps Throttle 1 in SHUT OFF. To start engine 1, engage left ingition and when N2 is at 20%, push Throttle 1 lever forward from the detent position to the axis idle position. This will introduce fuel to engine 1 and move Throttle 1 to IDLE. To cut fuel and shut off engine 1, pull the lever down to the detent position (SHUT OFF).

_Animation:_ Throttle 1 red lock and lever movement to SHUT OFF and IDLE.

#### **Axis detent button (Throttle 2):**
_Action:_ Throttle 2 to SHUT OFF/IDLE.

_Use:_ Keep Throttle 2 lever at the lowest detent position before starting flight. This keeps Throttle 2 in SHUT OFF. To start engine 2, engage left ingition and when N2 is at 20%, push Throttle 2 lever forward from the detent position to the axis idle position. This will introduce fuel to engine 2 and move Throttle 1 to IDLE. To cut fuel and shut off engine 2, pull the lever down to the detent position (SHUT OFF).

_Animation:_ Throttle 2 red lock and lever movement to SHUT OFF and IDLE.

#### **Gear Handle Up/Down:**
_Action:_ Landing Gear up/down.

_Use:_ Set to up/down.

_Animation:_ Gear lever on the center pedestal.


---
## ASCRJ_FCP_HCBRAVO
In MSFS control settings, select a profile for the Bravo TQ.

### **Remove/unbind the following flight control panel switches:**

1. Left Rotary Knob positions IAS/CRS/HDG/VS/ALT (Joystick Buttons 17 - 21)
1. Right Rotary Knob positions INCR/DECR (Joystick Buttons 13 - 14)
1. AUTOPILOT button (Joystick Button 8)
1. HDG/NAV/APR/REV/ALT/VS/IAS buttons (Joystick Buttons 1 - 7)
1. Rightmost switch positions (Joystick Buttons 46 - 47)

### **Bindings automatically applied by template:**

#### **AUTOPILOT button:**
_Press Action:_ Engage Autopilot.
_Long Press Action:_ Toggle flight directors.

_Use:_ Press to engage the Autopilot on the FCP. Long press to toggle the flight directors.

_Animation:_ AP ENG button on FCP. Left FD button on FCP.

#### **HDG button:**
_Press Action:_ Toggle Heading mode.
_Long Press Action:_ Sync current heading.

_Use:_ Press to toggle heading mode on the FCP. Long press to sync heading bug to current heading.

_Animation:_ HDG button on FCP. PUSH SYNC button on the heading selector knob.

#### **NAV button:**
_Press Action:_ Toggle Nav mode.
_Long Press Action:_ Toggle 1/2 Bank mode.

_Use:_ Press to toggle nav mode on the FCP. Long press to toggle 1/2 bank mode on the FCP.

_Animation:_ NAV button on FCP. 1/2 BANK button on FCP.

#### **APR button:**
_Press Action:_ Toggle Approach mode.

_Use:_ Press to toggle approach mode on the FCP.

_Animation:_ APPR button on FCP.

#### **REV button:**
_Press Action:_ Toggle localizer backcourse mode.

_Use:_ Press to toggle localizer backcourse mode on the FCP.

_Animation:_ B/C button on FCP.

#### **ALT button:**
_Press Action:_ Toggle Altitude hold mode.

_Use:_ Press to toggle altitude hold mode on the FCP.

_Animation:_ ALT button on FCP.

#### **VS button:**
_Press Action:_ Toggle Vertical Speed mode.

_Use:_ Press to toggle vertical speed mode on the FCP.

_Animation:_ VS button on FCP.

#### **IAS button:**
_Press Action:_ Toggle Speed mode.
_Long Press Action:_ Toggle IAS/MACH.

_Use:_ Press to toggle speed mode on the FCP. Long press to toggle between IAS and MACH.

_Animation:_ SPEED button on FCP. IAS/MACH button on the speed selector knob.

#### **Left Rotary to ALT + Right Rotary DECR/INCR:**
_Action:_ Altitude preselector bug decrease/increase.

_Use:_ Set Left Rotary to ALT. Turn Right Rotary to DECR/INCR to change the preselected altitude.

_Animation:_ Altitude selector knob on FCP.

#### **Left Rotary to VS + Right Rotary DECR/INCR:**
_Action:_ Vertical Speed decrease/increase.

_Use:_ Set Left Rotary to VS. Turn Right Rotary to DECR/INCR to change the vertical speed. Works only when VS mode is engaged on the FCP.

_Animation:_ VS selector wheel on FCP.

#### **Left Rotary to HDG + Right Rotary DECR/INCR:**
_Action:_ Heading selector bug decrease/increase.

_Use:_ Set Left Rotary to HDG. Turn Right Rotary to DECR/INCR to change the heading.

_Animation:_ Heading selector knob on FCP.

#### **Left Rotary to CRS + Right Rotary DECR/INCR:**
_Action:_ Course 1 selector needle decrease/increase.

_Use:_ Set Left Rotary to CRS. Turn Right Rotary to DECR/INCR to change the course 1 needle.

_Animation:_ CRS1 selector knob on FCP.

#### **Rightmost switch to ON/OFF:**
_Action:_ Selector acceleration on/off.

_Use:_ Set ON (flick up) to enable acceleration for altitude, heading, course1 and speed selectors. Set OFF to disable acceleration. Use Right rotary to change selector values as usual.

_Animation:_ None. The selector knobs turn faster when acceleration is enabled.
