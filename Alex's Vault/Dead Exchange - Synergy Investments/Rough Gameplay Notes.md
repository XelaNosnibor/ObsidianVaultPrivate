Synergy Investments / Dead Exchange
- long form ARPG
- WASD mouse controls, same as hades, geometry wars
- Same hub and spoke design as pokemon. Each gym/company acts as hub for story
Endless rougelike shooter ''minigame''
- Unlocked in mid game
- Levels are levels / area of stock exchange
- 6 CEOs - akin to gym leaders in pokemon
	- Oil - ZeroPoint Oilworks
	- Weapons - NeuroStrike Systems
	- Pharma - QuantumGen Pharmaceuticals
	- Energy - ApexFuel Innovations
	- Mining - VoidHarvest Industries
	- BioEngineering - NexaMutate Laboratories
### Game Names
1. **Sepulcher Funds**
4. **Mortal Markets**
6. Cadaver Commerce
10. **Soul Barter**
12. **Afterlife Auctions**
15. **Eternal Barter**
19. **Grim Exchange
20. **Silent Transactions

### Main Gameplay loop
-  City acts as hub with activities/minigames
- Timer starts when entering boss level
- Gain XP/Weapons for more power = faster times
- Auction minigame - Afterlife Auctions || Post-Letum, players place bids on high level deceased players for more XP
- Stock Market minigame
- AdCap type minigame

### Code Notes
keyDown = keyboard_check(vk_down);

```
//To be repeated for each number of items or weapons
keyItemOne = keyboard_check(ord("1"));
```

```
/// @Animate Player Sprite
var _cardinalDirection = round(direction/90);
var _totalFrames = sprite_get_number(sprite_index) / 4;
image_index = localFrame + (_cardinalDirection * _totalFrames);
localFrame += sprite_get_speed(sprite_index) / FRAME_RATE;

//If animation would loop on next game step
if (localFrame >= _totalFrames_)
{
	animationEnd = true;
	localFrame -= _totalFrames;
	
}else animationEnd = false;
```
### 6 Corporations (Antagonists)
- **NexaCorp: The Bioengineering Behemoth**
    - **Backstory:** NexaCorp rose to power through cutting-edge advancements in bioengineering. Originally a small research firm, they made a breakthrough in genetic manipulation, creating enhanced organisms for various purposes. However, their ambitions grew darker as they started experimenting on humans, creating genetically modified soldiers and spies. NexaCorp's unquenchable thirst for power led to the creation of monstrous creatures and the spread of bioengineered viruses, making them a global threat.
    
- **TechSyndicate: Masters of Cyber Espionage**
    - **Backstory:** TechSyndicate emerged from the shadows as a clandestine organization specializing in cyber warfare and espionage. Originally formed by disgruntled hackers, they evolved into a powerful corporation with advanced AI and hacking capabilities. Using their expertise, they manipulate governments, corporations, and individuals to control the world's information flow. TechSyndicate's motives remain mysterious, but their reach extends far and wide as they seek to exploit vulnerabilities in technology for their gain.
    
- **ChronoCorp: Time Manipulation Profiteers**
    - **Backstory:** ChronoCorp discovered a way to manipulate time, initially for seemingly benign purposes like historical preservation. However, greed corrupted their intentions, and they began exploiting time manipulation for profit. They hoarded historical artifacts, altered events for their benefit, and even created time loops to ensure perpetual control over resources. The consequences of their actions created temporal anomalies, threatening the very fabric of reality.
    
- **NeuroNex: Mind-Control Monopoly**
    - **Backstory:** NeuroNex started as a pharmaceutical company researching neural enhancements and mind-altering substances. Over time, they shifted their focus to mind control technology. Their products, disguised as therapeutic devices, allowed them to influence thoughts, manipulate decisions, and control entire populations. As they gained more power, NeuroNex expanded their reach into politics and global affairs, pulling strings from the shadows to ensure their dominance.
    
- **Quantum Dynamics: Reality Distortion Architects**
    - **Backstory:** Quantum Dynamics delved into quantum physics and discovered a way to manipulate the very fabric of reality. Originally a research institution, they became obsessed with altering the laws of physics for their benefit. They created alternate dimensions, harnessed energy from parallel universes, and warped reality itself. The consequences of their experiments led to the emergence of nightmarish creatures and distorted landscapes, as Quantum Dynamics pushed the boundaries of what was considered possible.
    
- **MegaPollute: Environmental Exploiters**
    - **Backstory:** MegaPollute started as a conglomerate of industries with a blatant disregard for environmental regulations. Over time, they became a monstrous entity, intentionally causing ecological disasters to profit from cleanup operations. Their activities led to the destruction of ecosystems, displacement of communities, and the release of toxic substances. MegaPollute manipulated governments and media to cover up their atrocities, all while exploiting the planet for their financial gain.