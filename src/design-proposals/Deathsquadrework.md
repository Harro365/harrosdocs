# Death Squad Rework


| Designers | Implemented | GitHub Links |
|---|---|---|
| Harro | :x: No | None yet |


## Overview/Game Design Rationale

Fundamentally, the concept of the Death Squad in SS14 is a strange one. It is both meta-shielded and top secret, yet historically it has been openly referenced, including through recruitment posters. The idea that Nanotrasen maintains a covert paramilitary force is compelling, but even the name “Death Squad” is fundamentally flawed. No self-respecting megacorporation would refer to a classified internal enforcement unit with such blunt language, or have a full unit and not utilize it for other things when they already have total control.

Additionally, Death Squad currently utilizes quite a bit of Syndicate equipment to make up for their lack of options, which makes ZERO sense both in lore and in gameplay. While their unique hardsuits, pulse weaponry, masks, and overall visual identity fit their role, the use of Syndicate stimulants, energy swords, and shields undermines the idea that this is a corporate-controlled force rather than an external antagonist.

This document aims to address both issues by providing cleaner lore, a more believable naming scheme, and a clearer meta-shield stance, while also establishing unique equipment and a more accurate in-game depiction aligned with the intended role.

## Features to be added: Lore Changes
As stated above, no corporate entity like Nanotrasen would name its most secretive enforcement division “Death Squad”. Instead, such a unit would be framed in bureaucratic language that conceals its true purpose while preserving legal and organizational distance.

Within this structure, what was historically referred to as Death Squad is formally redesignated as ART, standing for the Asset Recovery Team. ART is not a public-facing division and exists solely as a specialized enforcement arm of the ERT. While “Death Squad” may persist as an informal or colloquial term among personnel, it is not an official Nanotrasen designation.

Internal Affairs concerns itself with station function, compliance, and the conduct of employees and command staff. External Affairs, by contrast, operates at the Central Command level and becomes involved only once internal mechanisms have failed. When an individual, group, or station is deemed an externalized liability, authority is transferred from Internal Affairs to the EAEA. At that point, corporate protections are revoked, and enforcement shifts from investigation to resolution, enforcing Nanotrasen’s will.

Most crew members would reasonably assume ART oversees and provides security escorts for Central Command VIPs and manages high-level contract enforcement actions. These functions are explicitly not meta-shielded.

Central Command personnel, including NTRs, IAAs, and Magistrates, would be aware that the ART maintains an extreme enforcement capability through deployments. ART units are authorized only in exceptional circumstances, such as mass misconduct by command and crew, systemic corruption, or the uncontrolled leakage of corporate secrets. In such cases, all non-Central Command contracts aboard the station are terminated. ART deployment represents Nanotrasen’s nuclear option.

Despite this mandate, ART doctrine emphasizes total crew elimination without catastrophic damage to the station itself. Personnel are replaceable. Stations are not. In summary,
- Crew know ART exists
- Crew knows they are bodyguards and elite agents of NT, as well as guarding CC
- Crew, and even Command, would never suspect ART would be deployed to kill the entire crew
- CC staff would know that *can* happen, and that if so, they would be evacuated.

Thus far, this document has focused on philosophy and lore redesign. However, several in-game changes are proposed to better support and reinforce this hierarchy.

First, the prefix for former Death Squad spawns and ERT should be changed to Agent, reflecting their status as CC agents rather than military personnel. Existing ranks such as Corporal or Lieutenant should be removed, as they are inconsistent with both corporate structure and ERT doctrine.

Second, all existing Death Squad equipment names and descriptions should be rewritten to reflect NT ownership and ART-specific deployment, ensuring the gear communicates corporate enforcement rather than external or syndicate origin.

Features to be added: Items 
In order to reflect a cohesive ERT, we must remove the syndicate items and replace them with more options for agents to pick from, all while keeping it thematic, space-age, and objectively awesome.

ART, like nukies, will spawn in their hardsuit with their gas mask and basic gear, as well as a combat medical kit and pulse pistol in their bag, as well as a Bluespace Lifeline implant. They will otherwise be unarmed. The intended team size is 4, with all agents being of equal rank.

A new structure would be added that can be admin spawned, being effectively a NT version of a Nukie planet, yet being effectively a tiny, ATS-like (in terms of design) station with a matching, bare bones shuttle. It would have a new armory room with the following new ERT-only weapons, with instructions to not take more than you can carry on your person onto the shuttle. 

Space Station 14s firearms are fundamentally made by FUCKING NEEEERDS who like esoteric gun ideas and cartridges. I am continuing the tradition to autistic levels.

The armory will have the following:  
- 1 Parabellum Peacemaker (New)
- 5 extra Parabellum Peacemaker 9mm drums (New)
- 1 Rammer (New)
- 5 extra Rammer 20mm mags (New)
- 2 Terminators (New)
- 4 extra 8 gage depleated uranieam buckshot boxes (New)
- 4 Pulse Rifles
- 4 Portable Rechargers
- 8 Advanced Combat Medipens
- 2 Advanced Medical Kits
- 4 ARTist Lawboards (New)
- 4 ART Swords (New)
- 4 ART Shield (New)


Item Name:
### Parabellum Peacemaker

Description:

Developed for use by Asset Recovery Team agents, the General Purpose Anti-Personnel 9mm Rotary Machine Gun, often referred to as the Parabellum Peacemaker, is effectively a mini minigun using a Gatling-style electric action. The system recovers a portion of otherwise wasted firing energy to sustain the onboard battery, which rotates the barrels at a more consistent rate than a gas-based action and reduces sensitivity to fouling and ammunition variance even during heavy use.

Intended for personal contract termination, the 9mm cartridge was selected over a rifle-grade round due to its lower recoil, weight, profile, and thermal load, as well as reducing the risk of rebound in confined environments. The system feeds from large 9mm belts contained in disposable drums.

Implantation:

Creating the Parabellum Peacemaker in-game is by far the easiest new addition. This is because the Minigun is already a made gun, perfectly fits my idea in terms of damage, and is totally unused. We can literally just clone it and change the text and rounds. With the adoption of RMCs caceless rounds, it will also reduce the performance issues. The sprite itself works as well.

Logic:

Having fucked around with the Minigun and even used it in combat many times, it is a very fun gun. For those who have not used it, it fires a continuous beam of very accurate, low-damage projectiles. Where it thrives is not in time to kill. In fact, with armored targets, the gun can feel underpowered (fitting 9mm), but it has accuracy and sheer capacity. It fits a support weapon like the L6SAW perfectly, with 5+1 drums being more than enough to last an operation, especially if a squad is deployed late into a round.

The idea of a 9mm, man-portable mini minigun is objectively badass, and a man-portable electric rotary machine gun is objectively sci-fi as shit. It fits my design theme of being a gun that pushes the upper limits of practicality. It would be perfectly capable of killing the entire station 4 times over with drums to spare.

For those who care, i.e., no one, the name itself refers to the 9x19 NATO round, also known as the 9mm Parabellum. This comes from a 5th-century Latin phrase translating to “if you want peace, prepare for war”, perfectly fitting NATO's doctrine. In this case, the intention is to be ironic, not refrince NATO.

Item Name:
### Rammer

Description:

Officially designed for use by Asset Recovery Team agents as the 20mm Recoilless Anti-Material Rifle, and usually referred to as the 20RAMR, nicknamed ‘Rammer’, the 20RAMR brings the massive 20mm caliber into a semiautomatic, shoulder-fired, mobile rifle with a detachable magazine, intended for contract termination versus exosuit targets and penetrating plasteel walls. Offering a 4+1 round capacity, it uses a ‘recoilless’ operating system combined with a controlled, self-contained cycling action.

Rather than relying on a fixed barrel and conventional recoil absorption, the Rammer redirects a significant portion of propellant gas rearward through an open, vented system to balance forward momentum at the moment of firing. Simultaneously, the barrel assembly itself is permitted limited rearward travel, using that motion to manage impulse and cycle the weapon. 

Spent cartridges are expelled during this brief rearward movement, and the system uses a hydraulic recoil spring to reset forward immediately after stripping a new round and locking the barrel, keeping the action largely sealed during operation. Recoilless assisted short recoil action architecture reshapes the firing impulse to such a degree that the weapon can be fired from a standing shoulder position without requiring a bipod or cycling each round manually, otherwise impossible feats for a 20mm platform.



Implantation: 

My idea for a shoulder-fired, portable semi automatic ‘recoiless’ rifle fits the EAEA theme of total overkill. 

The Rammer is by far the most unique addition, yet it does not require from-scratch implantation. To reflect this, a 4+1 scoped gun (like the Hurstov), rate of fire of about 1/s, with each bullet having 1,000 structural, 300 piercing, and 300 blunt. That should make it a one-shot kill on any target, able to rip through any wall or door, and if a headshot or limbshot, shoot off the part. This is at the cost of only letting you carry max 25 rounds total, meaning every shot has to count. This would not be an effective primary, but as a brutal support piece to the team.

It would need a sprite made. 


Logic:

For those who do not love big bores to an autistic degree, 20mm is considered the boundary between a rifle and autocannon round, as well as defining what the upper limit of what a man-portable rifle is (see the American Anzio 20mm). Recoiless rifles are a strange subsection of firearms, and experimental, fitting the sci-fi gun. Short recoil-operated action is common in autocannons and might be used for a modern recoilless 20mm like this. Semi-auto large caliber snipers are objectively badass.



Item Name:
### Terminator
Description:

Officially referred to as the 8-gauge Contract Termination Device by the Asset Recovery Team, and often simply called the Terminator. It is a break-action, double-barreled 8-gauge shotgun intended to chamber proprietary 8-gauge depleted uranium buckshot. Each of the two barrels is made to be wide enough that an agent’s thumb could fit comfortably inside the bore.

With a barrel length of 12 inches, the Terminator was envisioned as the ART’s solution for close-quarters combat, acting as a breaching, anti-personnel, and even anti-exosuit weapon. Although never seeing mass production due to the extreme expense of the platform and the proprietary nature of its ammunition, the Terminator is occasionally fielded by CBURN ERT.

Implantation: 

The Terminator is also unique, but does not require from-scratch creation. The idea would be to take the Double Barrel, clone it, then change the text, ammo whitelist, etc. 

What it fires would be a fusion of uranium buckshot and slugs. This is to say the spray and the number of projectiles of buckshot, but each projectile is actually a slug, and has the damage and range as such. 

Logic:

The uninformed might misconstrue 8-gauge shells as being like a 12-gauge shell. This is utterly mistaken. 8-gauge in a modern context is a ludicrously large gauge, being restricted to industrial guns like the Remington MasterBlaster. No sane man in the modern age has dared to create such a monster. 

The EAEA, however, has a job to do, and 8-gauge depleted uranium buckshot would turn defunct employees into mulch, as well as virtually any inorganic material into dust.

### ART Sword
Description:

A reverse-engineered Syndicate energy sword, utilizing a plasma beam rather than a photon ray. This allows it to effectively act as a welder, as well as burn hotter.

Implantation: 

Effectively, a re-sprited esword, with an ART color scheme base, a gradient blade, and the ability to weld without eye protection being needed, as well as the reflect chance bumped to 75% for  kinetic projectiles and lasers

Logic: 

The idea of an esword is not what feels non-NT. They would 100% steal the tech, but make it their own, and as masters of laser and plasma tech, this feels more on brand!

### ART Shield
Description:

A reverse-engineered Syndicate energy shield, utilizing a plasma beam buckler rather than a radial photon hemisphere. This allows it to delfect kenetic projectiles with equal effectiveness.

Implantation: 

Effectively, a re-sprited e-shield, with an ART color scheme base, a gradient shield, as well as the reflect chance bumped to 90% for kinetic projectiles and lasers.

Logic: 

The idea of an esword is not what feels non-NT. They would 100% steal the tech, but make it their own, and as masters of laser and plasma tech, this feels more on brand!

### ART Shield
Description:

A reverse-engineered Syndicate energy shield, utilizing a plasma beam buckler rather than a radial photon hemisphere. This allows it to delfect kenetic projectiles with equal effectiveness.

Implantation: 

Effectively, a re-sprited e-shield, with an ART color scheme base, a gradient shield, as well as the reflect chance bumped to 90% for kinetic projectiles and lasers.

Logic: 

The idea of an esword is not what feels non-NT. They would 100% steal the tech, but make it their own, and as masters of laser and plasma tech, this feels more on brand!

## Existing Item Name/Description Changes

Item Name:
### Pulse Carbine --> ART Pulse Rifle
Description:

An experimental, custom-built version of the laser rifle made in-house for use by ART agents, the Pulse Rifle is modified with a highly efficient internal battery and utilizes advanced photon diffusion to magnify a four-watt discharge into a lethal range. The Pulse Rifle provides unmatched capacity, yet still requires external rechargers.


Item Name:
### Pulse Pistol --> ART Pulse Pistol
Description:

A sized-down ART Pulse Rifle, compressing the rifle into a minuscule package with minimal sacrifice to stopping power, at the cost of a proportional reduction in capacity.


Item Name:
### Death Squad Gas Mask --> ART Gas Mask
Description:

An advanced combat gas mask in the ART color scheme. 


Item Name:
### Death Squad Hardsuit Helmet --> ART Hardsuit Helmet
Description:

A collapsible light plaseel helmet built for the ART hardsuit. It incorprates a inbuilt visor and 250° optic cameras to allow for a greater field of view, all with next-generation HUD and inbuilt heating and cooling. Fit for only the best of the best.


Item Name:
### Death Squad Hardsuit --> ART Hardsuit
Description:

The Asset Recovery Team's advanced combat hardsuit. Lighter than a feather, tougher than plasteel. This version includes a prototype micro-exosuit scaffold, allowing the use of the intense recoil of ART's arsenal. It even includes air conditioning. Fit for only the best of the best.


## Roundflow & Player interaction

The goal of this rework is to make a rare ERT admeme spawn more streamlined, flavorful in lore, and terrifying to face. Only a tiny portion of overall rounds will ever see ERT, with even less seeing ART, and only on admin prompting. Ideally, this PR would make it much more fun for the ART agents who get to pick a busted, unique item, promote teamwork as each special gun has a dedicated role, and also be more fun to die to as crew!

Later, I would want to continue this project into each ERT section to get some love, and automate the round-end for ART so admins don’t have to prompt it!


## Administrative & Server Rule Impact

This is a very admin-focused update, as ART would be an admin-only spawn. This would only be breathing more life into an existing idea, beyond the meta-sheld changes to better outline the role of ART and ERT.

Technical Considerations
I outline the technical practicality of each new item in the item! Beyond that, no foreseen issues!
