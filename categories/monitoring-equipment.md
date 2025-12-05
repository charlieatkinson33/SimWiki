---
layout: default
title: Monitoring Equipment
category: monitoring-equipment
---

# Monitoring Equipment

Patient monitoring displays are essential for realism in simulation but can be extremely expensive. Creative alternatives can provide the necessary visual feedback at a fraction of the cost.

## Patient Monitors

### Commercial Options
- **Commercial patient monitors**: £2,000-£8,000 each
- **Training-specific monitors**: £3,000-£10,000
- **Integrated with manikins**: Included in £50,000+ systems
- Features: Multiple parameters, waveforms, alarms, touchscreen

### DIY Display Solutions

#### Tablet-Based Monitor (£100-£300)

**Option 1: Dedicated Apps**

**SimMon (Free - iOS/Android)**
- Realistic monitor interface
- ECG, SpO2, BP, HR, RR, Temp
- Waveforms displayed
- Controllable remotely
- Alarm sounds

**Setup:**
1. Install app on tablet
2. Mount on IV pole or wall
3. Control from phone/tablet
4. Display for all to see

**Cost: £100-£200 (tablet only)**

**Other Apps:**
- Vital Signs Simulator
- Patient Monitor Simulator
- Custom web-based displays

**Option 2: Computer/Large Monitor (£150-£500)**

**Advantages:**
- Larger display
- Better visibility for groups
- More screen real estate
- Can run multiple parameters

**Software:**
- SimMon (if available on platform)
- Web-based simulators
- Custom displays (see below)

#### Custom Web-Based Monitor (Free)

**Create Your Own:**

**Method 1: HTML/CSS/JavaScript**
- Design realistic monitor interface
- Update values via web interface
- Display on any device with browser
- Control from tablet/phone

**Resources:**
- CodePen examples
- GitHub repositories
- Tutorial videos
- Templates available online

**Method 2: Google Slides/PowerPoint**
- Create slides with vital signs
- One slide per scenario state
- Transition manually or automatically
- Simple but effective

**Features to Include:**
- Heart rate with waveform
- Blood pressure (systolic/diastolic/mean)
- SpO2 with waveform
- Respiratory rate
- Temperature
- EtCO2 (if needed)
- Alarms (visual/audio)

### Professional Budget Monitors (£300-£800)

**Used/Refurbished Monitors:**
- eBay UK
- Medical surplus suppliers
- Hospital decommissioning sales

**Options:**
- Older model patient monitors
- Demo units from manufacturers
- Non-functional units (display only)

**Considerations:**
- Electrical safety testing required (PAT)
- May need repair/calibration
- Check if training mode available
- Defibrillator compatibility if needed

**UK Suppliers:**
- Medequip UK
- Atlantic Medical
- Used medical equipment dealers

### Monitor Mounting

**IV Pole Mount (£20-£50)**
- Tablet holders - £15
- VESA monitor arms - £30
- 3D printed brackets - £10
- Height adjustable

**Wall Mount (£15-£40)**
- Articulating arms - £25
- Fixed mounts - £15
- Corner mounts - £20

## ECG Simulators

### Commercial Options
- **Fluke Biomedical ProSim**: £3,000-£8,000
- **Training ECG simulator**: £1,500-£4,000
- Features: Multiple rhythms, realistic waveforms, electrode simulation

### DIY ECG Display (£50-£200)

#### Screen-Based ECG (£50-£100)

**Method 1: Tablet with ECG App**
- SimMon or similar
- Display ECG waveforms
- Multiple rhythm options
- Controllable remotely

**Method 2: Computer Monitor**
- Full-screen ECG display
- Looping video of ECG
- YouTube videos offline
- Web-based ECG simulators

**Method 3: TV Display**
- Cast from tablet/phone
- Chromecast - £30
- Large visible display
- Control remotely

#### Arduino ECG Simulator (£80-£150)

**Components:**
- Arduino Uno/Mega - £30
- Small LCD/OLED screen - £15
- LEDs for QRS complex - £5
- Buttons for rhythm selection - £5
- Speaker for beep - £5
- Enclosure - £10
- Power supply - £10

**Features:**
- Multiple rhythms programmable
- Adjustable heart rate
- Visual and audio feedback
- Portable
- Educational to build

**Resources:**
- Instructables guides
- Arduino forums
- GitHub repositories
- YouTube tutorials

#### Raspberry Pi ECG Display (£100-£200)

**Advantages over Arduino:**
- Better graphics
- Web interface
- Touchscreen control
- More complex rhythms

**Components:**
- Raspberry Pi 4 - £50
- Official touchscreen or HDMI display - £60
- Case - £10
- SD card - £10
- Power supply - £10

**Software:**
- Custom Python script
- Web-based interface
- Remote control capability

## Defibrillator Trainers

### Commercial Options
- **AED trainers**: £150-£400
- **Manual defibrillator trainers**: £800-£2,000
- Features: Shock delivery simulation, voice prompts, electrode recognition

### Budget Alternatives

#### AED Trainer (£200-£400)

**Options:**
1. **Used training AEDs** - £150-£300
   - From expired training stock
   - Medical equipment surplus
   - eBay UK

2. **Basic AED trainers** - £150-£250
   - Chinese manufacturers (quality varies)
   - Check UK electrical compliance
   - Read reviews carefully

**UK Suppliers:**
- Defib Machines UK
- St John Ambulance (training equipment)
- British Heart Foundation

#### DIY AED Simulator (£50-£100)

**For basic training:**

**Components:**
- Plastic case/box - £10
- Buttons and switches - £10
- Small speaker - £15
- Arduino or MP3 player - £20
- LED indicators - £5
- Training electrode pads - £20

**Features:**
- Voice prompts (recorded)
- Shock button
- Light indicators
- Electrode connection check

**Limitations:**
- No rhythm analysis
- Manual prompt triggering
- Basic functionality only

### Manual Defibrillator Display (£100-£300)

**Screen-Based:**
- Tablet showing ECG - £100
- With rhythm changes
- Shock button separate
- Visual/audio feedback

**Prop Defibrillator:**
- Old non-functional unit - Free from hospital
- Clearly mark "TRAINING ONLY"
- Remove/disable actual charging capability
- Connect to ECG display
- Simulate shock delivery

## Vital Signs Simulation

### Integration with Manikins

#### Heart Rate Output (£30-£80)

**Pulse Simulation:**
1. **Vibration motor** - £10
   - Wrist/neck placement
   - Battery powered
   - Variable speed control - £20

2. **Audio pulse** - £30
   - Small speaker
   - Bluetooth connection
   - MP3 of heart sounds
   - Adjustable rate

#### Breathing Sounds (£30-£100)

**Options:**
1. **Smartphone + Bluetooth speaker** - £30
   - Breath sound loops
   - Hidden in manikin
   - Volume control

2. **Digital stethoscope simulator** - £80
   - Multiple lung sounds
   - Attached to chest
   - Interactive training

#### Temperature Simulation (£20-£80)

**Methods:**
1. **Heating pads** - £20
   - Electric heat packs
   - Low temperature setting
   - Inside manikin

2. **Warming blanket** - £30
   - Cut to size
   - Low voltage
   - Thermostat control - £30

## Blood Pressure Simulation

### Automated BP Display (£50-£150)

**Screen-Based:**
- Display on monitor/tablet
- Updates with scenario
- Realistic display format

**Audio Korotkoff Sounds:**
- Speaker in arm
- Triggered by cuff inflation
- Arduino-controlled (advanced)
- Or manual trigger

### Realistic BP Cuff Response (£100-£300)

**Advanced Project:**

**Components:**
- Pressure sensor in cuff - £30
- Arduino/Pi for control - £50
- Speaker for sounds - £20
- Display output - £100

**Features:**
- Detects cuff inflation
- Generates appropriate sounds
- Sends BP to display
- Realistic training

## Capnography Displays

### Commercial Options
- **EtCO2 monitors**: £1,500-£4,000
- **Training simulators**: £2,000-£5,000
- Features: Waveform, numeric values, alarms

### Budget Display (£50-£150)

**Screen-Based:**
- Tablet or monitor
- EtCO2 waveform display
- Web-based or app
- Controllable values

**DIY Display:**
- Looping video of capnography
- Different scenarios
- Triggered by facilitator
- Visible to learners

## Infusion Pump Trainers

### Commercial Options
- **IV pump trainers**: £500-£1,500 each
- Features: Training mode, no actual delivery, realistic operation

### Alternatives

#### Old/Expired Pumps (Free-£100)

**Sources:**
- Hospital donations
- Expired equipment
- Medical surplus

**Modifications:**
- Remove/disable actual pumping
- "TRAINING ONLY" labels
- Can still program
- Realistic practice

#### Pump Simulators (£50-£200)

**Options:**
1. **Computer simulation** - Free
   - Software trainers available
   - Screen-based practice
   - Some manufacturers provide free

2. **Tablet apps** - Free-£50
   - IV pump simulators
   - Programming practice
   - Safe learning

## Monitor Configuration Systems

### Scenario Control

#### Simple Control (£50-£100)

**Google Sheets-Based:**
1. Create sheet with scenarios
2. Each row = different state
3. Display on monitor
4. Update manually
5. Share with controllers

**Cost: Free (existing tech)**

#### Advanced Control (£150-£400)

**Node-RED or Similar:**
- Web interface
- Preset scenarios
- Button controls
- Multiple monitors
- Raspberry Pi based

**Features:**
- Quick scenario changes
- Multiple room control
- Preset progressions
- Remote operation

## Multi-Parameter Displays

### All-in-One Solution (£200-£500)

**Large Monitor Setup:**

**Components:**
- 32"+ monitor or TV - £150
- Mini PC or Pi - £100
- Wireless keyboard/mouse - £30
- Mounting hardware - £40

**Display:**
- Split screen with multiple parameters
- ECG waveform
- Vital signs
- Waveforms (SpO2, etc.)
- Alarms
- Ventilator settings if needed

**Software:**
- Custom web page
- Multiple browser windows
- Screen layout software
- OBS Studio for scenes

## Ventilator Displays

### Commercial Options
- **Training ventilators**: £5,000-£15,000
- Features: Realistic modes, alarms, graphics

### Budget Display (£100-£300)

**Screen-Based:**
- Tablet or monitor
- Ventilator parameter display
- Waveform graphics
- Mode settings visible

**Options:**
1. **Static slides** - Free
   - PowerPoint/Google Slides
   - Different ventilator settings
   - Change with scenario

2. **Interactive display** - £100
   - Web-based ventilator display
   - Adjustable parameters
   - Realistic graphics

3. **Video loops** - Free
   - Screen recording of real ventilator
   - Different modes/scenarios
   - Play appropriate video

## Alarm Systems

### Visual and Audio Alarms

#### Screen-Based Alarms (Free)

**Include in Display:**
- Flashing indicators
- Color changes
- Text alerts
- Prioritized alarms

#### Audio Alarms (£20-£50)

**Options:**
1. **Recorded sounds** - Free
   - Download monitor alarms
   - Play through speakers
   - Triggered by facilitator

2. **Bluetooth speaker** - £30
   - Hidden near monitors
   - Controlled from phone
   - Realistic alarm sounds

3. **Buzzer/alarm module** - £10
   - Arduino-controlled
   - Different tones
   - Visual indicators too

## Waveform Generation

### Creating Realistic Waveforms

**Software Options:**
- Processing (programming language) - Free
- JavaScript canvas - Free
- Python with matplotlib - Free
- Video of real waveforms - Free

**Display:**
- Smooth animation
- Appropriate speeds
- Accurate morphology
- Responsive to "patient state"

## Mobile Monitoring

### Portable Solutions (£100-£200)

**Tablet-Based:**
- Carry between scenarios
- Quick setup
- Multiple monitor "types"
- Cost-effective

**Use Cases:**
- Pre-hospital scenarios
- Transfer scenarios
- Resource-limited settings
- Flexible training

## Monitor Props

### Making It Look Real

**Surround the Display:**
- 3D printed bezel
- Cardboard frame painted
- Old monitor case (empty)
- Mounted appropriately

**Cables and Connections:**
- Fake electrode cables
- BP cuff attached
- SpO2 probe (non-functional)
- Realistic appearance

## Troubleshooting Common Issues

### Display Problems
- Brightness too low
- Viewing angle
- Screen glare
- Size too small

**Solutions:**
- Adjust settings
- Better positioning
- Anti-glare film
- Larger display

### Control Lag
- Wireless delay
- Network issues
- App crashes

**Solutions:**
- Wired connections where possible
- Reliable WiFi
- Backup methods
- Restart protocols

## Maintenance

### Software Updates
- Keep apps updated
- Backup configurations
- Test before sessions
- Have alternatives ready

### Hardware Care
- Clean screens
- Protect from damage
- Secure mounting
- Battery management

## Budget Complete Monitoring Setup

### Single Room (£400-£800)

**Equipment:**
- Main monitor (tablet/monitor) - £200
- ECG display - £100
- Control system - £100
- Mounting - £50
- Speakers - £40
- Backup tablet - £100

**Capabilities:**
- Full vital signs display
- ECG rhythms
- Control from distance
- Audio feedback
- Multiple scenarios

**Comparison:**
- Commercial equivalent: £10,000-£20,000
- **Savings: 95%+**

## Case Study: Multi-Room Setup

**3 Rooms on £2,000 Budget:**

**Per Room (£650 each):**
- Monitor display: £200
- ECG simulation: £100
- Control tablet: £150
- Audio system: £50
- Mounting/cables: £50
- Consumables: £50
- Contingency: £50

**Shared:**
- Central control system: £200
- Spare devices: £150

## Tips for Success

### Planning
- Know your learning objectives
- Match fidelity to needs
- Test thoroughly
- Have backups

### Setup
- Consistent placement
- Clear visibility
- Easy control access
- Documented procedures

### Operation
- Trained facilitators
- Pre-session checks
- Backup plans
- Technical support available

## Educational Considerations

### When High Fidelity Isn't Needed
- Early training stages
- Communication focus
- Process learning
- Resource allocation skills

### When It Matters
- Critical care training
- Advanced scenarios
- Team performance
- High-stakes assessment

## Contributed Solutions

Share your monitoring solutions! See our [contribution guide](/contribute).

## Related Categories
- [Technology & Software](/categories/technology) - Control systems and software
- [Manikins & Simulators](/categories/manikins) - Integration with manikins
- [Recording Equipment](/categories/recording-equipment) - Capturing displays

[Back to Categories](/categories) | [Home](/)
