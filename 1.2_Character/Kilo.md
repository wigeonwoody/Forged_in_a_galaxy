---
Name: Roga Danar 'Kilo'
Edge: 3
Force: 2
Heart: 2
Iron: 1
Shadow: 2
Wits: 2
Health: 5
Spirit: 5
Supply: 5
Momentum: 9
Wealth: 0
Wounded: ⬡
Shaken: ⬡
Unprepared: ⬡
Harmed: ⬡
Traumatized: ⬡
Doomed: ⬡
Tormented: ⬡
Indebted: ⬡
XPSpent: 0
Bonds_Progress: 0
Bonds_TrackImage: "[[progress-track-0.svg]]"
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_TrackImage: "[[progress-track-0.svg]]"
Discoveries_XPEarned: 0
Quests_Progress: 0
Quests_TrackImage: "[[progress-track-0.svg]]"
Quests_XPEarned: 0
Failures_Progress: 5
Failures_TrackImage: "[[progress-track-5.svg]]"
Failures_XPEarned: 0
---
# `=this.Name`
(a.k.a Keeve Falor, Dellum Elsh 'Del')

![|300](https://i.pinimg.com/originals/ff/a5/83/ffa583c1871bc725b0d214a48adaa5be.jpg)

## Stats
| Edge         | Force         | Heart         | Iron         | Shadow         | Wits         |     |
| ------------ | ------------- | ------------- | ------------ | -------------- | ------------ | --- |
| `=this.Edge` | `=this.Force` | `=this.Heart` | `=this.Iron` | `=this.Shadow` | `=this.Wits` |     |

## Meters
| Health         | Spirit         | Supply         | Wealth         | Momentum         |
| -------------- | -------------- | -------------- | -------------- | ---------------- |
| `=this.Health` | `=this.Spirit` | `=this.Supply` | `=this.Wealth` | `=this.Momentum` |

## Impacts
| Misfortunes | Lasting Effects | Burdens |
| --- | --- | --- |
| `=this.Wounded` Wounded | `=this.Harmed` Permanently Harmed | `=this.Doomed` Doomed |
| `=this.Shaken` Shaken | `=this.Traumatized` Traumatized | `=this.Tormented` Tormented |
| `=this.Unprepared` Unprepared |  | `=this.Indebted` Indebted |

> [!NOTE]- Equipment
> Equipment
> - Lightsaber
> - Data pad
> - Binders
> - Med packs (5)
> - Portable scanner (tri-corder)
> - 


> [!NOTE]- Legacies
> ## Legacies
> | XP Earned | XP Spent |
> | --- | --- |
> | `=this.Bonds_XPEarned+this.Discoveries_XPEarned+this.Quests_XPEarned` | `=this.XPSpent` |
> ### Bonds (Rolled Over? `=choice(this.Bonds_Progress > 40, "Yes", "No")`)
> ```dataview
> LIST without id embed(link(meta(Bonds_TrackImage).path, "350"))
> WHERE contains(file.path, this.file.path)
> ```
> ### Discoveries (Rolled Over? `=choice(this.Discoveries_Progress > 40, "Yes", "No")`)
> ```dataview
> LIST without id embed(link(meta(Discoveries_TrackImage).path, "350"))
> WHERE contains(file.path, this.file.path)
> ```
> ### Quests (Rolled Over? `=choice(this.Quests_Progress > 40, "Yes", "No")`)
> ```dataview
> LIST without id embed(link(meta(Quests_TrackImage).path, "350"))
> WHERE contains(file.path, this.file.path)
> ```
> ### Failures (Rolled Over? `=choice(this.Failures_Progress > 40, "Yes", "No")`)
> ```dataview
> LIST without id embed(link(meta(Quests_TrackImage).path, "350"))
> WHERE contains(file.path, this.file.path)
> ```


> [!NOTE]- Vows / Progress Tracks
> Contents
> ## Vows / Progress Tracks
> ```dataview
> TABLE Name, embed(link(meta(TrackImage).path, "150")) AS Progress
> FROM #incomplete WHERE file.name != "Progress_Template" 
> ```

## Assets
> [!NOTE]- Lightsaber Training
> ![[Lightsaber_Training]]

> [!NOTE]- Kinetic
> ![[Kinetic]]

> [!NOTE]- Logistician
> ![[Logistician]]

> [!NOTE]- Padawan
> ![[Padawan]]

> [!NOTE]- Pilot
> ![[Pilot]]

## Companions

> [!NOTE]- Jedi Master
> ![[Jedi_Master]]






> [!NOTE]- Character Description
> 
> ### Character Description
> 
> #### Roga Danar
> 
> **Species:** Human  
> **Gender:** Male  
> **Age:** 16-17 (Born 38-39 BBY, )  
> **Appearance:** Roga Danar is of medium height and lean build, with an athletic frame that reflects the intense physical training of a Jedi Padawan. His short, dark brown hair is usually messy, as though he’s always one step away from running into battle. His hazel eyes hold a flicker of determination mixed with a hint of doubt, the kind that comes from carrying the weight of past failures. Roga’s expression often betrays a quiet intensity, with his brow slightly furrowed in thought, giving him a serious demeanor for someone his age.
> 
> He wears the standard Jedi Padawan robes, though his attire is a little rough around the edges, showing signs of wear from countless training sessions and missions. Roga has a leather wrist guard on his left arm, a small memento given to him by his former Master, Kaelen Dahr. Though he’s conflicted about his connection to Dahr, he keeps it as a reminder of his past and the lessons he’s learned—both good and bad.
> 
> ### Personality:
> Roga is driven by a deep desire to prove himself, not only to his new Master, Alara Ven, but also to himself. He is naturally inquisitive and courageous, but his past experiences have made him wary of blind obedience to the Jedi Code. His time with Master Kaelen Dahr has left him with a lingering belief that sometimes the end justifies the means—a dangerous mindset for any Jedi.
> 
> Roga is introspective and often lost in thought, contemplating the balance between the Light and Dark sides of the Force. While he strives to follow the teachings of Master Alara Ven, he sometimes struggles to control his emotions, especially when confronted with injustice or the suffering of others. His greatest fear is that his own doubts and vulnerabilities might lead him down the same path as his former Master.
> 
> ### Skills and Abilities:
> - **Lightsaber Combat:** Roga is proficient in Form V (Djem So), a more aggressive lightsaber form that emphasizes power and counter-attacks. This style was encouraged by Kaelen Dahr, who believed in using strength to dominate the battlefield. Master Alara Ven is now guiding him toward Form III (Soresu), focusing on defense and patience.
> - **Force Sensitivity:** Roga has a natural affinity for sensing emotions through the Force, which can be both a gift and a curse. His heightened empathy allows him to understand others’ intentions, but it also makes him more susceptible to his own emotional turmoil.
> - **Combat Instincts:** Despite his young age, Roga’s instincts in combat are sharp and quick, allowing him to adapt to rapidly changing situations. However, he sometimes lacks the discipline to think strategically, relying too heavily on his reflexes.
> 
> ### Background:
> Roga Danar's journey as a Jedi began under the mentorship of Master Kaelen Dahr. As a youngling and later a Padawan, Roga was unknowingly part of a secret Super Soldier program orchestrated by Dahr. > The program aimed to create the ultimate Sith Super Soldier, and Roga was subjected to neurotropic compounds that enhanced his connection to the Force, granting him unique abilities.
>
> Before the program could reach completion, the Jedi Order discovered Dahr's illicit activities. The program was swiftly dismantled, and Dahr was expelled from the Order for his dangerous experiments and use of forbidden Dark Side techniques. Roga, deeply affected by the program, was placed into recovery for a year to heal from the physical and psychological impacts of the compounds.
>
> Following his recovery, Roga was assigned to Master Alara Ven for further training and evaluation. Under her guidance, he began to learn the true teachings of the Jedi, focusing on patience, understanding, and a deep connection to the Light Side of the Force. Alara's calm and disciplined approach challenged Roga to rethink his beliefs and confront the parts of himself that he feared the most.
> 
> Despite the shadow of his past, Roga is determined to forge his own path as a Jedi. He strives to reconcile the teachings of his former Master with the expectations of his present, seeking to find a balance that allows him to use his power responsibly without succumbing to the darkness that once threatened to consume him.
> 
> Now under the guidance of Master Alara Ven, Roga finds himself on a different path—one that requires patience, understanding, and a deep connection to the Light Side of the Force. Alara’s calm demeanor and disciplined approach challenge Roga to rethink his beliefs and confront the parts of himself that he fears the most.
> 
> ### Relationship with Master Alara Ven:
> Master Alara Ven represents a stark contrast to Roga’s former Master. She is patient, thoughtful, and always focused on balance. Roga respects her wisdom, but he sometimes feels frustrated by her insistence on restraint and meditation, especially when his instincts scream for action. Despite his inner struggle, he feels a growing trust in her guidance and senses that she might be the mentor he needs to help him find his true path.
> 
> ### Internal Conflict:
> Roga’s greatest battle is within himself. He struggles with the teachings of his past and the expectations of his present. The whispers of Kaelen Dahr’s philosophy echo in his mind, tempting him to take shortcuts through anger and aggression. Yet, the guiding presence of Master Alara Ven and her belief in his potential keeps him anchored to the Light, even when darkness seems to offer a quicker solution.
> 
> Roga’s journey is about finding his own way, not merely following the dogma of the Jedi or the allure of the Dark Side. He is searching for a way to reconcile his past with his future, to find a balance that will allow him to use his power without succumbing to it.
> 
> ### Current Goals:
> - **Prove Himself as a Jedi:** Roga is determined to prove that he can be a true Jedi despite his past mistakes and the shadow of his former Master.
> - **Find Inner Balance:** He seeks to understand the true nature of the Force, striving to balance his emotions without giving in to the anger that his former Master once encouraged.
> - **Defeat Kaelen Dahr:** Ultimately, Roga wants to confront Kaelen Dahr—not just to stop his old Master’s twisted plans, but also to gain closure and prove that he is not destined to follow in Dahr’s footsteps.


