# Game Design Document: THE VEIL: Edinburgh Echoes

## 1. GAME OVERVIEW

**Title:** THE VEIL: Edinburgh Echoes  
**Genre:** Supernatural Horror/Mystery Adventure  
**Platform:** PC, Console  
**Target Audience:** 16+ (Mature Audiences)  
**Engine:** To Be Determined  
**Development Timeline:** 18-24 months  

### Vision Statement  
THE VEIL: Edinburgh Echoes is a narrative-driven supernatural adventure that blurs the boundary between reality and the spirit realm. Players assume the role of Cassidy, a sound engineer haunted by loss, as they uncover the mysteries of 1924 Edinburgh and confront the forces that keep them tethered to our world.

---

## 2. NARRATIVE FOUNDATION

### Setting: 1924 Edinburgh  
- **Time Period:** Post-WWI era, height of spiritualism  
- **Geographic Focus:** Old Town, particularly Mary King's Close  
- **Atmosphere:** Gothic, fog-laden, historically rich, temporally ambiguous

### Main Protagonist: Cassidy  
- **Background:** Former British Army Sound Engineer specializing in acoustic location  
- **Motivation:** Searching for missing brother Jacob through a mysterious "Dead Air" signal  
- **Skills:** Audio detection, frequency manipulation, photographic documentation  
- **Arc:** From skepticism to acceptance, grief to resolution

### Central Conflict  
A secret experiment in the South Bridge vaults has weakened the Veil—the barrier between living and dead. Cassidy must navigate both worlds to find Jacob and restore balance.

---

## 3. CORE GAMEPLAY LOOP: IDENTIFY → SHIFT → RESOLVE

### Phase 1: IDENTIFY  
**Objective:** Detect supernatural phenomena in the Living World

**Mechanics:**  
- Jacob Orb acts as a "Geiger Counter" for supernatural activity  
- Orb turns orange and vibrates when near Cold Spots  
- Player uses audio equipment to triangulate source  
- Environmental clues guide investigation

**Player Skills:**  
- Active listening and observation  
- Pattern recognition  
- Tool usage (modified radio equipment)

### Phase 2: SHIFT  
**Objective:** Cross the Veil into the Spirit World

**Mechanics:**  
- Press 'V' to activate Veil shift  
- Visual transformation: buildings become transparent, colors shift to blue/gray  
- Audio muffles and becomes otherworldly  
- Cold Spot reveals hidden paths, objects, or entities  
- Shift duration limited by sanity meter

**Atmospheric Changes:**  
- Living World: Harsh electric lights, industrial sounds, crowded spaces  
- Veil World: Organic fog, shadow, blue Tether lines, ethereal soundscape

### Phase 3: RESOLVE  
**Objective:** Solve the supernatural puzzle and cleanse the location

**Sub-Mechanics:**  
- **Echo Photography:** Photograph the one object out of place tethering a Memory Echo  
- **Frequency Tuning:** Align audio slider to match ghost's "hum," enabling communication  
- **Environmental Interaction:** Manipulate objects in Veil to affect Living World  
- **Confrontation (Optional):** Face Siphoners if detected

**Outcomes:**  
- Successful resolution: Location becomes brighter, Echoes pacified, world state improves  
- Failed resolution: Siphoner encounter, forced retreat, temporary consequence

---

## 4. CHARACTER ECOSYSTEM

### Major Characters

#### Cassidy (Protagonist)  
- **Age:** 32  
- **Profession:** Former Army Sound Engineer  
- **Trauma:** Loss of brother Jacob, survivor's guilt  
- **Unique Ability:** Auditory Processing - can "hear" frequencies others cannot  
- **Character Arc:** Acceptance and closure

#### Jacob (The Orb)  
- **Status:** Missing, present as glowing spectral orb  
- **Nature:** Partially bound between worlds  
- **Function:** Guides Cassidy through supernatural phenomena  
- **Mystery:** Why is he tethered? Can he be freed?

#### Siphoners  
- **Nature:** Malevolent entities that feed on life force  
- **Appearance:** Humanoid silhouettes of void/shadow  
- **Behavior:** Attracted to strong emotions; hunt audibly moving targets  
- **Threat Level:** High - one-hit kill if contact occurs  
- **Avoidance Requirement:** Essential gameplay tension

#### Memory Echoes  
- **Nature:** Looping snapshots of past events  
- **Appearance:** Translucent figures caught in repetitive actions  
- **Communication:** Via acoustic frequencies  
- **Resolution:** Photography or audio tuning  
- **Quantity:** 20-30 major Echoes throughout Edinburgh

---

## 5. GAME MECHANICS IN DEPTH

### Audio-Centric Gameplay  
**Philosophy:** Sound is not just atmosphere—it is the primary gameplay medium.

**Components:**  
- Frequency Detection System  
- Audio Pattern Matching Puzzles  
- Siphoner Detection via Sound  
- Jacob Orb Audio Cues  
- Environmental Soundscapes

### Camera Mechanics  
- **Primary Tool:** Photography for Echo resolution  
- **Secondary Use:** Defensive flash against Siphoners (3-second stun)  
- **Cooldown:** 5 seconds between flashes  
- **Strategic Element:** Flash drains battery; limited uses per location

### Sanity System  
- **Trigger:** Prolonged Veil exposure, Siphoner proximity, witnessing traumatic Echoes  
- **Meter:** Visual distortion, audio hallucinations, control disruption  
- **Recovery:** Return to Living World, interact with anchoring objects  
- **Consequence:** Unchecked insanity triggers game-over state

### World State System  
- **Dynamic Environment:** As Echoes are resolved, locations become progressively cleaner  
- **Visual Feedback:** Fog lifts, lights stabilize, Tether lines fade  
- **Gameplay Impact:** Cleaner areas = fewer Siphoners, easier navigation  
- **Progression Marker:** Player visually sees their impact on the world

---

## 6. PROGRESSION & PACING

### Act Structure  
- **Act 1 (Arrival):** Introduction to mechanics in accessible area; 2-3 hours  
- **Act 2 (Descent):** Deeper exploration; increasingly complex puzzles; 6-8 hours  
- **Act 3 (Resolution):** Climactic confrontation; moral choices; 2-3 hours

### Difficulty Curve  
- Tutorial puzzles: Single-object photography, basic frequency matching  
- Intermediate: Multi-step puzzles, Siphoner avoidance, sanity management  
- Advanced: Complex acoustic patterns, time-sensitive challenges, multiple simultaneous threats

### Checkpoint System  
- Manual saves at safe zones  
- Auto-save upon successful Echo resolution  
- Permadeath mode (optional hardcore difficulty)

---

## 7. ATMOSPHERE & TONE

### Visual Style  
- **Living World:** Muted colors, industrial revolution aesthetics, electric lights  
- **Veil World:** Ethereal, otherworldly, dominated by shadow and blue luminescence  
- **Contrast:** Sharp distinction between worlds emphasizes player agency in shifting

### Audio Design Philosophy  
- **Diegetic:** Footsteps, breathing, environmental sounds matter for gameplay  
- **Non-Diegetic:** Subtle score enhances mood without overwhelming  
- **Frequency Landscape:** Unique audio signatures for each Echo type and Siphoner

### Emotional Arc  
- **Opening:** Mystery and curiosity  
- **Mid-Game:** Growing dread and tension  
- **Climax:** Emotional catharsis and revelation  
- **Ending:** Hope, closure, or ambiguity (player-dependent)

---

## 8. TECHNICAL SPECIFICATIONS

### Platform Requirements  
- **Primary:** PC (Windows 10+)  
- **Secondary:** PlayStation 5, Xbox Series X/S  
- **Minimum Specs:**  
  - CPU: Intel i7 / AMD Ryzen 5  
  - RAM: 16 GB  
  - GPU: NVIDIA RTX 2060 / AMD RX 5700  
  - Storage: 50 GB SSD  
  - Audio: 5.1 Surround or Stereo with spatial audio support

### Audio Implementation  
- **Format:** FMOD Studio or Wwise for advanced audio manipulation  
- **3D Spatial Audio:** Essential for directional frequency detection  
- **Real-Time Frequency Analysis:** For acoustic puzzle mechanics

### Performance Targets  
- 60 FPS on recommended specs  
- 4K resolution support  
- Ray-tracing optional for enhanced atmosphere

---

## 9. MULTIPLAYER & SOCIAL FEATURES  
**Current Focus:** Single-player narrative experience  
**Future Consideration:** Ghost multiplayer (asynchronous) where players leave audio messages for others

---

## 10. GAME ENDING CONDITIONS

### Victory Conditions  
- **Primary:** Locate Jacob and escape Edinburgh with restored Veil  
- **Secondary:** Resolve all Memory Echoes in the city  
- **Bonus:** Achieve perfect sanity level at conclusion

### Failure Conditions  
- **Permadeath:** Contact with undefended Siphoner  
- **Permanent Insanity:** Sanity meter reaches zero  
- **Paradox Ending:** Unresolved time paradox with Jacob

### Multiple Endings (3 Variations)  
1. **Redemption Ending:** Jacob freed, Cassidy finds peace  
2. **Bittersweet Ending:** Jacob remains as guide, Cassidy accepts coexistence  
3. **Dark Ending:** Cassidy becomes bound to Edinburgh like Jacob

---

## 11. DEVELOPMENT PRIORITIES

### Phase 1: Core Systems (Months 1-6)  
- Veil shifting mechanics  
- Audio detection system  
- Basic Echo types  
- Camera/photography system  
- Sanity management

### Phase 2: Content & Expansion (Months 7-12)  
- Mary King's Close full level  
- 15-20 Memory Echoes  
- Siphoner AI refinement  
- Acoustic puzzle library

### Phase 3: Polish & Optimization (Months 13-18)  
- Sound design finalization  
- Visual effects polish  
- Performance optimization  
- Testing and iteration

---

## 12. UNIQUE SELLING POINTS

✓ **Audio-Centric Gameplay** — Sound as primary puzzle mechanic, not just atmosphere  
✓ **Innovative Veil System** — Real-time world-state transformation  
✓ **Historical Authenticity** — Grounded in real Edinburgh locations  
✓ **Emotional Depth** — Grief and loss as central themes  
✓ **Strategic Evasion** — Tension without combat mechanics  
✓ **Environmental Storytelling** — Show, don't tell narrative approach

---

## CONCLUSION

THE VEIL: Edinburgh Echoes represents a bold departure from conventional horror gaming, prioritizing atmospheric immersion, audio innovation, and emotional resonance over jump-scares and combat. By grounding supernatural phenomena in sound design and historical authenticity, we create a uniquely haunting experience that resonates long after players leave Edinburgh.
