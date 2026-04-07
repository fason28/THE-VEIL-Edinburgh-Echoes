# MECHANICS SPECIFICATION GUIDE: THE VEIL: Edinburgh Echoes

## 1. CORE LOOP SYSTEMS

### 1.1 IDENTIFY PHASE MECHANICS

#### Jacob Orb System
**Function:** Primary supernatural detection tool and narrative anchor

**Mechanics:**
- Orb orbits Cassidy at 1.5-meter radius
- Base color: Pale blue/white (neutral state)
- Proximity Detection Range: 30 meters
- Orange Glow Threshold: Cold Spot within 15 meters
- Vibration Intensity: Increases with proximity (haptic feedback scale 0.1-1.0)

**Gameplay Implications:**
- Player must actively move to triangulate Cold Spot location
- Directional movement provides audio feedback (frequency pitch)
- No explicit waypoint marker—pure sensory navigation

#### Cold Spot Detection
**Definition:** Intersection point between Living World and Veil World

**Detection Attributes:**
- Temperature Drop: 10°C+ decrease in specific area
- Visual Indicator: Slight air shimmer (Living World), blue glow (Veil World)
- Audio Signature: Low-frequency hum (50-100 Hz)
- Jacob Orb Response: Orange glow + vibration pattern

**Range Mechanics:**
- 15-30m: Weak vibration (0.2 intensity), faint hum
- 5-15m: Medium vibration (0.5 intensity), clear hum
- 0-5m: Strong vibration (1.0 intensity), unmistakable resonance

---

### 1.2 SHIFT PHASE MECHANICS

#### Veil Transition System
**Activation:** Press 'V' key (customizable)
**Transition Time:** 1 second fade effect
**Visual Transformation:**
- Buildings become semi-transparent (alpha 0.5)
- Sky darkens to deep purple-gray
- All lighting shifts to cool tones (blue/cyan dominant)
- Particle effects: Blue mist rises from ground, Tether lines become visible
- Fog density increases by 40%

**Audio Transformation:**
- All diegetic sounds muffle (-6dB reduction)
- High frequencies attenuate significantly
- New ambient layer: Ethereal, otherworldly hum
- Echo/reverb effect applied to all player-generated sounds

#### Veil Duration System
**Base Duration:** 90 seconds per activation
**Sanity Drain Rate:** 1 point per 2 seconds in Veil
**Duration Extensions:**
- Resolving an Echo: +30 seconds
- Discovering a lore item: +15 seconds
- Optional meditation at anchor points: +10 seconds

**Over-Duration Consequences:**
- At 80 seconds: Visual distortion (chromatic aberration begins)
- At 90+ seconds: Audio hallucinations (parasitic frequencies)
- At 120+ seconds: Control inversion (analog stick reversed)
- At 150+ seconds: Forced auto-exit + mandatory 30-second cooldown

#### Anchor Points (Safe Zones)
**Function:** Locations where Cassidy can rest, recover, and plan

**Characteristics:**
- Appear only in Living World (grounded, safe)
- Visual indicator: Soft golden glow
- Audio cue: Calming bell tone (E major 330 Hz)
- Sanity Recovery: +2 per second
- Jacob Orb: Becomes stationary, glows softly

**Distribution:** 1 anchor point per major district; 15 total across Edinburgh

---

### 1.3 RESOLVE PHASE MECHANICS

#### Echo Photography System
**Objective:** Photograph the one object out of place tethering a Memory Echo

**Mechanics:**
- Camera equipped via inventory
- Target reticle appears on screen
- Player must identify anomalous object among period-correct environment
- Photograph must be in focus (within focus zone)
- Successful photo triggers resolution animation

**Puzzle Difficulty Tiers:**

**Tier 1 (Tutorial):** 1 obvious object, high contrast (blue in gray room)
- Example: Modern electric light in 1600s room
- Time limit: Unlimited

**Tier 2 (Intermediate):** 2-3 subtle objects, one is correct
- Example: Out-of-place book spine, wrong-era furniture
- Time limit: 60 seconds
- Consequences: Siphoner attracts if time expires

**Tier 3 (Advanced):** 5+ objects, puzzle requires logic
- Example: Sequence puzzle—photograph items in chronological order
- Time limit: 90 seconds
- Consequences: Multiple Siphoner spawn if failed

**Camera Specifications:**
- Film capacity: 12 exposures per location
- Flash cooldown: 5 seconds
- Zoom capability: 1x-3x optical
- Auto-focus range: 1-20 meters

#### Frequency Tuning System
**Objective:** Align audio slider to match ghost's "hum" and enable communication

**Mechanics:**
- UI slider presents frequency range (20 Hz - 20 kHz)
- Ghost emits target frequency (audible, varies by Echo type)
- Player adjusts slider by ear
- Success range: ±5% of target frequency

**Difficulty Scaling:**

**Tier 1:** Single frequency, large success window (±10%)
- Example: 440 Hz (A note)
- Audible feedback: Visual bar fills, pitch matches
- Time limit: 30 seconds

**Tier 2:** Frequency changes over time, narrow window (±5%)
- Example: 440→523 Hz (A to C transition)
- Player must track moving target
- Time limit: 60 seconds

**Tier 3:** Multiple simultaneous frequencies, perfect pitch required (±2%)
- Example: Harmonic chord (440 + 587 + 659 Hz)
- Requires active listening and discrimination
- Time limit: 90 seconds

**Failure Consequences:**
- ±10-15%: Weak Siphoner attraction (1 spawns)
- ±15-25%: Strong attraction (2 spawn)
- >±25%: Critical failure (3 spawn, forced exit)

**Special Mechanic: Frequency Lock**
- After successful tuning, player can "lock" frequency
- Locked frequency persists for 30 seconds
- Enables hands-free communication with Echo
- Used for obtaining story information or hints

---

## 2. ENTITY SYSTEMS

### 2.1 SIPHONER MECHANICS

#### Detection Rules
**Sight System:** Disabled in Living World (cannot see Cassidy)
**Hearing System:** Activated in both worlds
- Footstep detection range: 20 meters
- Breathing detection range: 5 meters
- Audio frequency sensitivity: 10 Hz - 10 kHz

#### Behavior State Machine

**State 1: Passive/Unaware**
- Behavior: Idle or wandering patrol
- Audio output: Minimal (occasional whisper)
- Response time: None
- Duration: Indefinite until triggered

**State 2: Alert**
- Trigger: Player audio detected (footstep, breathing, cough)
- Behavior: Stationary, heightened awareness
- Audio output: Increased frequency humming (threat display)
- Response time: 3 seconds before pursuit
- Duration: 15 seconds (returns to Passive if no further audio)

**State 3: Pursuit**
- Trigger: Continued audio generation in Alert state
- Behavior: Rapid movement toward audio source
- Audio output: Intense, piercing hum (attack signal)
- Speed: 6 m/s (faster than Cassidy's run speed of 5 m/s)
- Duration: Until contact or audio source eliminated

**State 4: Feeding**
- Trigger: Physical contact with Cassidy
- Behavior: Freezes player in place
- Duration: 2 seconds
- Consequence: Instant game-over (no health system—one hit = death)

#### Flash Mechanic
**Equipment:** Camera with built-in flash
**Effect:** Temporarily stuns Siphoner
**Stun Duration:** 3 seconds
**Cooldown:** 5 seconds between flashes
**Range:** 10 meters
**Power Cost:** 1 battery unit per flash

**Tactical Use:**
- Stun Siphoner to create escape window
- Must be within 10-meter range
- Flash can be used in both worlds
- Limited battery: 5 flashes per location

**Consequences of Poor Flash Timing:**
- If timed too late: Siphoner still makes contact (death)
- If timed on Multiple Siphoners: Only nearest one is affected
- Overuse: Battery depletes, forcing stealth-only gameplay

---

### 2.2 MEMORY ECHO MECHANICS

#### Echo Classification System

**Type A: Spectator Echoes**
- Nature: Passive observers, non-threatening
- Interaction: Photography or audio tuning
- Behavior: Ignore player unless disturbed
- Example: Woman gazing from window repeatedly
- Resolution Time: 2-5 minutes
- Reward: Story lore, safe experience

**Type B: Conflicted Echoes**
- Nature: Trapped between emotional states
- Interaction: Complex multi-step puzzle
- Behavior: May emit distressing sounds, attract weak Siphoners
- Example: Man alternating between joy and despair
- Resolution Time: 5-10 minutes
- Reward: Major lore revelation

**Type C: Hostile Echoes**
- Nature: Corrupted by Siphoner influence
- Interaction: Dangerous, but can be cleansed
- Behavior: Attempt to interfere with photography, emit loud frequencies
- Example: Screaming figure, aggressive entity
- Resolution Time: 10-15 minutes
- Reward: Significant lore, moral weight
- Risk: Siphoner attraction during resolution

#### Echo Conversation System (Optional)
**Activation:** After successful frequency tuning
**Communication Method:** Text-to-speech representation of Echo's "words"
**Information Provided:**
- Fragment of their past
- Hint about object requiring photography
- Warning about nearby threats
- Request for help

**Dialog Branches:**
- Ask for help: Echo provides hint (1-2 uses)
- Demand information: Echo becomes hostile (attracts Siphoners)
- Negotiate: Echo provides story (no combat benefit)

---

## 3. WORLD STATE SYSTEM

### 3.1 Environmental Progression

#### State Tracking
**Per-Location Metrics:**
- Total Echoes: X/Y resolved
- Siphoner Population: N (decreases with Echo resolution)
- Veil Integrity: 0-100% (increases with resolution)
- Ambient Fog Density: 0-100% (decreases with resolution)
- Player Sanity Restoration: Zone becomes safe haven

#### Visual Changes Based on Resolution Percentage

**0-25% Resolved:**
- Heavy fog (80-100% density)
- Dim lighting
- Constant blue Tether lines visible
- Ominous ambient hum
- Multiple active Siphoners (4-6)

**25-50% Resolved:**
- Moderate fog (50-80% density)
- Slightly improved lighting
- Reduced Tether line visibility
- Decreasing ambient hum
- Fewer Siphoners (2-3)

**50-75% Resolved:**
- Light fog (20-50% density)
- Good lighting restoration
- Rare Tether lines
- Peaceful ambient soundscape
- 1 Siphoner remains

**75-100% Resolved:**
- Minimal fog (0-20% density)
- Natural lighting fully restored
- No Tether lines
- Safe ambient sounds (birds, wind)
- Zero active Siphoners
- Anchor point appears

#### Narrative Consequences
- NPCs (if present) become more visible/helpful
- Safe passages open up
- New areas unlock based on world state
- Ending variations tied to global world state percentage

---

## 4. PROGRESSION SYSTEMS

### 4.1 Skill Development
**Note:** No explicit leveling system; progression tied to player action

**Implicit Skill Growth:**
- **Audio Discrimination:** Improved frequency matching accuracy (learned through repetition)
- **Stealth Awareness:** Better understanding of Siphoner patterns
- **Photography Intuition:** Faster object identification in Echoes
- **Sanity Resilience:** Longer Veil duration tolerance (psychological adaptation)

### 4.2 Equipment Unlocks
**Starting Equipment:**
- Modified radio (detection)
- Basic camera
- 3 flash batteries

**Unlockable Equipment:**
- Advanced camera (better zoom, 3x instead of 2x)
- Extended battery pack (+3 flashes)
- Audio amplifier (increases detection range by 15%)
- Frequency recorder (captures Echo audio for later analysis)

**Unlock Method:** Find lore items throughout the world

---

## 5. DIFFICULTY SETTINGS

### Accessibility Options

**Hearing Difficulty:**
- Visual substitutes for audio cues (waveform visualizers)
- Haptic feedback intensification
- Frequency slider replaced with visual matching

**Visual Difficulty:**
- Audio-only mode (enhanced soundscapes)
- High-contrast UI
- Screen reader compatibility

**Gameplay Difficulty:**
- Casual: Extended durations, fewer Siphoners, simplified puzzles
- Standard: Balanced as described above
- Hardcore: Permadeath, limited resources, complex puzzles
- Custom: Player-selectable modifiers

---

## 6. SAVE & CHECKPOINT SYSTEM

### Save Mechanics
- **Manual Save:** Available only at anchor points
- **Auto-Save:** Upon successful Echo resolution
- **Checkpoint System:** At major narrative beats (no player control)

### Permadeath Consequences
- Death to Siphoner: Game Over (restart from last save)
- Death to Sanity: Game Over (restart from last save)
- No item loss on death (progress persists)

---

## CONCLUSION

These mechanics form the backbone of THE VEIL's unique identity. Audio-centric puzzles, strategic evasion, and real-time world transformation create a cohesive, atmospheric experience that rewards attentive players while maintaining constant tension.
