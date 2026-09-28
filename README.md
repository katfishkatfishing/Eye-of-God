# mirror-aphelion // skrail_archive_temp
**README.md** | Commit: `8f1c402` (Auto-sync via local daemon)  
*Last pushed: 04:12 UTC — 3 hours before Departmental lockout*

---

### If you are from Campus Security or the Iowa State Patrol:
**Do not close this repository.** 

My name is Khallenghar. I am an undergraduate senior in the Department of History at [REDACTED]. I was Dr. Alexander Skrail’s teaching assistant for HIST-340 (*Monastic Cryptography and Late Medieval Logistics*). 

Dr. Skrail did not "voluntarily resign" or abandon his lease as the dean claims. His house on Elm Street was unlocked. The refrigerator was running, his tea kettle had boiled dry until the coil burned out, and the steamer trunk he kept bolted to the subfloor at the foot of his bed had been forced open from the inside out. 

I found the drive arrays in his campus office. I also found the chest. 

I’ve mirrored the terminal filesystem from his SCSI drive to an external web host because my campus account is already being flagged for bandwidth anomalies:

> **LIVE DRIVE MIRROR:** **[https://aphelion.moe.page/](https://aphelion.moe.page/)**  
> *(If it asks for credentials, look at his syllabus marginalia below. I haven't cracked the root partition yet.)*

---

### WHAT IS IN THE OFFICE CLOSET (Ground Unit 07)

I didn't steal it. I moved it back to my apartment because two men in gray field jackets were asking the janitorial staff about the service elevators on Monday night.

It isn't a university asset. It’s an oblong chest—maybe 18 kilos—cast in heavy, cold bell bronze with modern socket-head machine screws holding an aluminum faceplate over what looks like a modified geodetic survey rig. 

* **The fluid:** It’s wrapped in two blue poly tarps on my kitchen floor, but it keeps leaking. Not oil. It’s a completely clear, odorless grease that feels cold to the touch and ruins paper instantly. It soaked through sixty pages of my Syracuse seminar notes before I noticed.
* **The display:** There is an auxiliary 16x2 LCD grafted onto the top plate behind a thick quartz lens. If you trip the toggle switch, the backlight doesn't glow amber—it flashes a harsh, violet red, pulses `1420.405 MHz`, and then defaults to an error: `RANGE: OUT OF PARITY // TOLERANCE > 15M`.
* **The latch:** There are no keyholes. The seam between the lid and the base is held by an internal solenoid deadbolt. It doesn't budge, but at night you can hear a small servo inside stepping forward and back, like a clockwork escapement that can't find its tooth.

---

### TRANSCRIPTS FROM HIS DESK JOURNALS
*(He kept three black ledger notebooks hidden behind the Loeb Classical Library volumes. The handwriting gets progressively worse after 2004. You can see where his fountain pen literally gouged through the rag paper because he was pressing down with dead weight. I simplified the diary entries here, look for the complete entire in the docs folder.)*

#### `[Entry: march_04]`
> *"The knuckles are soft. That is what made me sick in the sink behind the silo. For nine years, every time I hit the iron bench in Bay 3, it chimed like porcelain. Now it gives in. I can squeeze the meat of my own thumb and feel it squish like wet bread...*
> 
> *Chen didn't burn. That’s what the halon alarm told my ears, but my eyes saw the topaz. Four seconds. In 4.12 seconds the flare went through the back of his neck and turned both corneas into hard, clear beads. The light didn't stop. It projected the circuit traces of Unit 07 straight through his skull and scorched them into the zinc floor tiles...*
> 
> *The sky has gone blunt. Ninety-degree corners everywhere I look. It’s like living inside a cardboard carton after the spotlight has been kicked out."*

#### `[Entry: oct_09]`
> *"I bought the Wild T2 with departmental discretionary funds. Let the committee think I am cataloging late-Roman stone quarries. I set the tripod on the library roof at dusk...*
> 
> *The box under the bed knows the weather before the barometer does. When the humidity climbs, the seams sweat. It wants the benchmark where the granite doesn't conduct. It wants the null-point where the shadow falls south... I spent six hours on the rug with Chen's manual open to page 74 until the carbon ink turned into gray hair. It’s a running key, but the terminal buffer won't accept the string until the rotation is reversed."*

#### `[Entry: aug_18]`
*(This is the entry from the week before he stopped showing up to lectures. He was writing about me while I was sitting across from his desk.)*
> *"The boy stayed behind again. He wasn't looking at the Syracuse maps. He was staring at the corner of my green blotter where the blue ink soaked through the felt...*
> 
> *I had to drop my ledger over it before he saw the sequence: Aperture-03. He just sat there, blinking. It makes me ill to watch him do it. The lid goes down, the lid comes up. Smooth. Effortless. He has no idea that every time the skin drops over his pupil, the local horizon slips four thousandths of a degree. He takes his eyes for granted like an animal...*
> 
> *The chest clicked at 3:14 AM. Not an unlock—the deadbolt settling deeper into the mortise. The room had five corners when I turned the lamp off."*

---

### WHAT WE NEED TO DECODE

There is a raw telemetry block dumped from `aphelion.moe.page` under the buffer handle `BURST-88` / `VEC-FINAL`. 


Skrail left notes scribbled across his lecture draft (*"The Steganography of Trithemius and Abbot Sponheim"*). He wasn't teaching history; he was using the curriculum to figure out how to un-jam Chen’s calculations.

From his margin notes:
1. **The Book:** Decoding that string yields the pass-title for Chen's engineering manual.
2. **The Warning:** His slide margin has a red ink box drawn around it:  
   `"Always subtract the drift step (n-1) to untwist the cornea. If you don't back-rotate the letters before setting your compass, the latitude will land three miles into the marsh."`

---

### NOTES / LOGS (KHALLENGHAR)

* **Update (Sept 24):** Found a charcoal rubbing in his filing cabinet taken from the bottom plate of the brass chest. Underneath the modern battery tray, the 15th-century bronze has an inscription: `PAX UNA // UT VIDEATUR, PURGANDUM EST` (*One Peace // To Be Witnessed, It Must Be Refined*). He wrote underneath it: *"Chen thought he was building an attenuator. He put a battery on an altar and called it an engineering project."*
* **Update (Sept 26):** My eyes have been watering constantly. I went to the student clinic thinking it was conjunctivitis from the dust in his study. The triage nurse said both corneas show concentric micro-abrasions, like I’ve been looking at an unshielded arc welder. I haven't used anything brighter than a desk lamp.
* **Update (Sept 27):** I'm having trouble typing this update. The second joints on my index and middle fingers feel dry and stiff, like there’s fine sand inside the knuckle capsules. When I tap them on the aluminum frame of my laptop, it doesn't sound like skin hitting metal. It sounds like two dry river stones clicking together.

If anyone knows how to access the terminal or has access to an SDR tuned to 1420.4 MHz in the Midwest, post an issue or pull request immediately. 

I don't think I have much time before someone comes for the closet key.
