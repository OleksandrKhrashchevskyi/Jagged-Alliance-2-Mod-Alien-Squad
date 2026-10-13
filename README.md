# The Alien Team - mercenaries

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-latest_release-2ea44f?style=for-the-badge" alt="Download the latest release"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JA2-v1.13-c9a227?style=flat-square" alt="Jagged Alliance 2 v1.13">
  <img src="https://img.shields.io/badge/mercenaries-58-1f6f4a?style=flat-square" alt="58 mercenaries">
  <img src="https://img.shields.io/badge/films-1979_·_1986_·_1992_·_1997_·_2012_·_2017_·_2024-555?style=flat-square" alt="Films: 1979, 1986, 1992, 1997, 2012, 2017, 2024">
  <img src="https://img.shields.io/badge/price-free_forever-2ea44f?style=flat-square" alt="Free forever">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-lightgrey?style=flat-square" alt="License: CC BY-NC-SA 4.0"></a>
  <a href="https://discord.com/invite/Ku2H9Hf"><img src="https://img.shields.io/badge/Discord-join-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="../../discussions"><img src="https://img.shields.io/badge/Discussions-ask_%26_share-2ea44f?style=flat-square&logo=github&logoColor=white" alt="GitHub Discussions"></a>
</p>

<p align="center">
  <a href="#about-the-mod">About</a> ·
  <a href="#getting-started">Getting started</a> ·
  <a href="#stats">Stats</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#troubleshooting--faq">FAQ</a> ·
  <a href="#-community">Community</a>
</p>

58 operators from the seven films. Stats are on the JA2 1.13 scale (0-100), the day rate is in dollars. Traits use the 1.13 new trait system.

**It's free.** No price, no ads, no sign-up. *Downloads are strictly for true fans only* — if you know what Ripley said to the Queen and why you never trust the company, you qualify. 😏

> [!CAUTION]
> **Selling this mod is strictly forbidden!** The mod was created by a fan of **Jagged Alliance 2** and the **Alien** films, for the fans. It is free and must stay free: do not sell it, do not bundle it into paid packs and do not put it behind a paywall. If someone charged you for it, you were scammed. See [License](LICENSE).

> [!WARNING]
> **After downloading, check the files for viruses!** Before running any `.exe` you got from the internet — `ja2at.exe` included — upload it to an online multi-engine scanner:
>
> - [MetaDefender](https://metadefender.com/) — scans the file with dozens of antivirus engines at once
> - [VirusTotal](https://www.virustotal.com/) — 70+ antivirus engines and URL/file reputation
> - [Hybrid Analysis](https://www.hybrid-analysis.com/) — scan plus sandbox run showing what the file does
> - [Jotti's malware scan](https://virusscan.jotti.org/) — free scan with a set of popular engines
>
> Get the mod only from the [Releases](../../releases) page of this repository. See [Security policy](SECURITY.md).

> [!IMPORTANT]
> **Back up your game before installing the mod!** The mod is unpacked straight into your game folder: files with the same names are overwritten, and the game's settings may need changes in `Ja2.ini`. The stock `Data-1.13` is not touched, but things can always go wrong. Before you start, copy your whole game folder (at least `Data-1.13`, `SavedGames` and `Ja2.ini`) somewhere safe — just in case. Saves from older versions of the mod do not work in newer ones.

## 📑 Contents

<table align="center">
<tr>
<th>📖 About</th>
<th>🎖️ The team</th>
<th>🆘 Help &amp; info</th>
</tr>
<tr valign="top">
<td>

[About the mod](#about-the-mod)<br>
[▶️ Getting started](#getting-started)<br>
[🔐 Verify the download](#verify-the-download-sha-256)<br>
[✅ Compatibility](#-compatibility)

</td>
<td>

[By film](#by-film)<br>
[Stats](#stats)<br>
[Screenshots](#screenshots)

</td>
<td>

[❓ Troubleshooting / FAQ](#troubleshooting--faq)<br>
[🐞 Reporting bugs](#reporting-bugs)<br>
[💬 Community](#-community)<br>
[📝 Changelog](#changelog)<br>
[🏅 Credits](#credits) · [License](#license) · [Disclaimer](#disclaimer)

</td>
</tr>
</table>

## About the mod

**The Alien Team** replaces A.I.M. and M.E.R.C. with one mercenary outfit: 58 operators from *Alien 1979*, *Aliens 1986*, *Alien 1992*, *Alien Resurrection 1997*, *Prometheus 2012*, *Alien: Covenant 2017* and *Alien: Romulus 2024*. All standard mercs are gone; the story of Arulco works as usual.

- 🎯 **58 operators** with stats, skill traits, day rates and starting kits based on their roles in the films. Colonial Marines and the *Betty* mercenaries are at the top; the crews, scientists, prisoners and young colonists are where they belong.
- 🎒 **Five gear kits** for every operator — Standard, Satchel, Primitive, Recon and Premium (the Premium kit costs 50% more).
- 🧩 **Safe install**: the mod runs from its own `Data-Alien` folder with its own `ja2at.exe`; the stock `Data-1.13` is not touched.

## Getting started

You need **Jagged Alliance 2 v1.13**.

1. [Download](../../releases/latest) `JA2-AlienTeam.zip` from the latest release.
2. **Scan the archive for viruses** (see the links above) and [verify the checksum](#verify-the-download-sha-256).
3. **Back up your game folder** — at least `Data-1.13`, `SavedGames` and `Ja2.ini`.
4. Unpack the archive into the game folder (the one that contains `ja2.exe`).
5. Start the game with **`ja2at.exe`** and begin a **new game**. Saves from older versions of the mod are not compatible.

`README.txt` in the archive has the details.

### Verify the download (SHA-256)

Every release lists the SHA-256 checksum of its archive. Download the mod **only from this repository** and compare the checksum before unpacking it.
In PowerShell, in the folder with the downloaded file:

```powershell
Get-FileHash .\JA2-AlienTeam.zip -Algorithm SHA256
```

or in the Command Prompt:

```bat
certutil -hashfile JA2-AlienTeam.zip SHA256
```

If the value differs from the one in the release notes, **do not use the file** — it was changed by someone else.

## ✅ Compatibility

| Game | Status |
|---|---|
| **Jagged Alliance 2 v1.13** | ✅ Supported — the mod is made and tested for it. |
| **Jagged Alliance 2: Unfinished Business** | ❌ Not supported. |
| Other mods — **Arulco Revisited**, **AIMNAS**, **SDO**, **Urban Chaos**, **Wildfire** and others | ❌ Not supported — the mod replaces A.I.M. and M.E.R.C. and does not work together with other mods. |
| Original JA2 (without v1.13), JA2 Stracciatella | ❌ Not supported — the mod needs v1.13. |

Saves from older versions of the mod do not work in newer ones — start a new game after updating. The mod works only with a clean **Jagged Alliance 2 v1.13** — do not install it on top of other mods.

## By film

- **Alien 1979**: Dallas, Ripley, Kane, Lambert, Parker, Brett
- **Aliens 1986**: Ripley, Hicks, Burke, Hudson, Apone, Vasquez, Gorman, Drake
- **Alien 1992**: Ripley, Dillon, Clemens, Golic, Andrews, Aaron
- **Resurrection 1997**: Elgin, Johner, Kristie, Vriess, Hillard, Perez, Wren, Gediman, DiStefano, Purvis
- **Prometheus 2012**: Shaw, Vickers, Weyland, Holloway, Janek, Fifield, Millburn, Ravel, Ford
- **Covenant 2017**: Daniels, Oram, Tennessee, Karin, Maggie, Ricks, Upworth, Branson, Lope, Hallett, Rosenthal, Ledward, Cole, Ankor
- **Romulus 2024**: Rain, Tyler, Kay, Bjorn, Navarro

<details>
<summary><b>Alien 1979</b> · 6 operators · Nostromo</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 31 | **Dallas**<br><sub>Arthur Dallas</sub> | Captain of the Nostromo. Calm, careful, decides for the crew | 4 | $2,200 | Squadleader, Ranger, Scouting |
| 32 | **Ripley**<br><sub>Ellen Ripley</sub> | Warrant officer. By the book, stubborn, very hard to kill | 5 | $3,200 | Survival, Squadleader, Technician |
| 33 | **Kane**<br><sub>Gilbert Kane</sub> | Executive officer. First through every door | 3 | $1,700 | Scouting, Ranger, Athletics |
| 34 | **Lambert**<br><sub>Joan Lambert</sub> | Navigator. Knows the way home, wants to take it now | 3 | $1,500 | Radio Operator, Technician, Scouting |
| 35 | **Parker**<br><sub>Dennis Parker</sub> | Chief engineer. Wants his full share - and earns it | 4 | $2,600 | Technician, Heavy Weapons, Bodybuilding |
| 36 | **Brett**<br><sub>Samuel Brett</sub> | Engineering technician. Steady hands, few words | 3 | $1,400 | Technician, Demolitions, Athletics |

</div>

</details>

<details>
<summary><b>Aliens 1986</b> · 8 operators · Hadley's Hope, LV-426</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 170 | **Ripley**<br><sub>Ellen Ripley</sub> | Survivor of the Nostromo. Back for the colony - and the girl | 6 | $4,200 | Auto Weapons, Squadleader, Survival |
| 171 | **Hicks**<br><sub>Dwayne Hicks</sub> | Corporal. Quiet, steady - takes command when it matters | 7 | $4,800 | Auto Weapons, Squadleader, Night Ops |
| 172 | **Burke**<br><sub>Carter Burke</sub> | Company man. Smiles a lot. Never turn your back on him | 3 | $1,800 | Covert Ops, Snitch, Radio Operator |
| 173 | **Hudson**<br><sub>William Hudson</sub> | Private. Big mouth, fast hands - game over, man | 5 | $3,000 | Auto Weapons, Athletics, Radio Operator |
| 174 | **Apone**<br><sub>Al Apone</sub> | Master sergeant. Twenty years in the corps, chews cigars | 7 | $5,000 | Squadleader, Auto Weapons, Bodybuilding |
| 175 | **Vasquez**<br><sub>Jenette Vasquez</sub> | Smartgunner. Tougher than anybody in the room | 6 | $4,500 | Auto Weapons (expert), Bodybuilding |
| 176 | **Gorman**<br><sub>William Gorman</sub> | Lieutenant. New in command, by the book | 3 | $2,000 | Radio Operator, Scouting, Teaching |
| 177 | **Drake**<br><sub>Mark Drake</sub> | Smartgunner. Vasquez's partner, says little, shoots a lot | 5 | $3,200 | Auto Weapons, Bodybuilding, Heavy Weapons |

</div>

</details>

<details>
<summary><b>Alien 1992</b> · 6 operators · Fiorina 161</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 178 | **Ripley**<br><sub>Ellen Ripley</sub> | Sole survivor of the Sulaco. No illusions left | 6 | $3,800 | Squadleader, Survival, Athletics |
| 179 | **Dillon** | Spiritual leader of the inmates. Feared, respected, unbreakable | 6 | $3,400 | Squadleader, Melee, Bodybuilding |
| 180 | **Clemens**<br><sub>Jonathan Clemens</sub> | Prison doctor. Clever, tired, carries his own past | 4 | $3,000 | Doctor (expert), Survival |
| 181 | **Golic** | Inmate. Damaged, unpredictable, sees the beast as a dragon | 3 | $1,200 | Melee, Stealthy, Bodybuilding |
| 182 | **Andrews**<br><sub>Harold Andrews</sub> | Prison superintendent. Rules are rules - until they stop working | 4 | $2,400 | Squadleader, Teaching, Radio Operator |
| 183 | **Aaron** | Assistant superintendent. IQ 85 - and more loyal than anybody | 3 | $1,500 | Radio Operator, Technician, Scouting |

</div>

</details>

<details>
<summary><b>Resurrection 1997</b> · 10 operators · USM Auriga</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 242 | **Elgin**<br><sub>Frank Elgin</sub> | Captain of the Betty. Smuggler, mercenary, businessman | 6 | $3,600 | Squadleader, Auto Weapons, Covert Ops |
| 243 | **Johner** | Muscle of the Betty. Loud, rude and very hard to kill | 6 | $3,800 | Heavy Weapons, Auto Weapons, Bodybuilding |
| 244 | **Kristie** | Gunman of the Betty. Two pistols on his arms, never misses | 7 | $4,400 | Ambidextrous, Gunslinger, Athletics |
| 245 | **Vriess**<br><sub>Gary Vriess</sub> | Mechanic of the Betty. Never lets the wheelchair stop him | 5 | $2,600 | Technician, Demolitions, Radio Operator |
| 246 | **Hillard**<br><sub>Sabra Hillard</sub> | Pilot of the Betty. Elgin's partner | 4 | $2,000 | Radio Operator, Technician, Athletics |
| 247 | **Perez**<br><sub>Martin Perez</sub> | General. Commander of the USM Auriga | 6 | $3,800 | Squadleader, Teaching, Radio Operator |
| 248 | **Wren**<br><sub>Mason Wren</sub> | Chief scientist of the Auriga's project | 4 | $2,400 | Doctor, Snitch, Covert Ops |
| 249 | **Gediman**<br><sub>Jonathan Gediman</sub> | Scientist of the Auriga. Loves his specimens | 3 | $2,200 | Doctor (expert), Teaching |
| 250 | **DiStefano**<br><sub>Vincent DiStefano</sub> | Soldier of the Auriga. The last one alive | 5 | $3,000 | Auto Weapons, Athletics, Night Ops |
| 251 | **Purvis**<br><sub>Larry Purvis</sub> | Miner. Woke up with something inside him | 3 | $1,400 | Bodybuilding, Melee, Survival |

</div>

</details>

<details>
<summary><b>Prometheus 2012</b> · 9 operators · LV-223</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 184 | **Shaw**<br><sub>Elizabeth Shaw</sub> | Archaeologist. A believer who survives what kills everybody else | 5 | $2,800 | Survival, Scouting, Doctor |
| 185 | **Vickers**<br><sub>Meredith Vickers</sub> | Company mission director. Cold, in charge, with her own way out | 5 | $3,000 | Squadleader, Athletics, Radio Operator |
| 186 | **Weyland**<br><sub>Peter Weyland</sub> | Founder of the company. Came all this way to ask for more time | 4 | $2,600 | Squadleader, Teaching, Radio Operator |
| 187 | **Holloway**<br><sub>Charlie Holloway</sub> | Archaeologist. Wants the answers now | 4 | $2,200 | Scouting, Survival, Athletics |
| 188 | **Janek** | Captain of the Prometheus. Calm, practical, decides fast | 6 | $3,800 | Squadleader, Radio Operator, Technician |
| 189 | **Fifield** | Geologist. Hates the job, loves his mapping drones | 3 | $1,800 | Demolitions, Technician, Scouting |
| 190 | **Millburn** | Biologist. Too friendly with strange animals | 3 | $1,500 | Doctor, Survival, Scouting |
| 220 | **Ravel** | Co-pilot. Jokes a lot, flies very well | 4 | $2,000 | Technician, Radio Operator, Athletics |
| 221 | **Ford** | Medical officer. Quiet and steady | 4 | $2,400 | Doctor (expert), Survival |

</div>

</details>

<details>
<summary><b>Covenant 2017</b> · 14 operators · The Engineers' planet</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 222 | **Daniels**<br><sub>Daniels Branson</sub> | Terraforming expert. Lost her husband on the first day - and kept going | 6 | $3,800 | Survival, Auto Weapons, Squadleader |
| 223 | **Oram**<br><sub>Christopher Oram</sub> | First mate, captain by accident. A man of faith with doubts | 4 | $2,400 | Squadleader, Teaching, Radio Operator |
| 224 | **Tennessee**<br><sub>Tennessee Faris</sub> | Chief pilot. Steady hands, big heart | 5 | $2,800 | Technician, Radio Operator, Athletics |
| 225 | **Karin**<br><sub>Karin Oram</sub> | Biologist. Married to the captain | 4 | $2,000 | Doctor, Survival, Scouting |
| 226 | **Maggie**<br><sub>Maggie Faris</sub> | Lander pilot. Married to Tennessee | 4 | $2,000 | Technician, Athletics, Radio Operator |
| 227 | **Ricks** | Navigator. Quick with a joke | 3 | $1,700 | Radio Operator, Scouting, Technician |
| 228 | **Upworth** | Medic and radio man. A calm voice on the line | 3 | $1,800 | Doctor, Radio Operator, Survival |
| 230 | **Branson**<br><sub>Jacob Branson</sub> | Captain of the Covenant. Died before the job began | 5 | $3,000 | Squadleader, Radio Operator, Scouting |
| 231 | **Lope** | Sergeant. Leads the security team | 6 | $4,200 | Squadleader, Auto Weapons, Bodybuilding |
| 232 | **Hallett** | Sergeant. Lope's partner | 4 | $2,600 | Auto Weapons, Bodybuilding, Athletics |
| 233 | **Rosenthal** | Corporal. Sharp-eyed and quiet | 4 | $2,600 | Auto Weapons, Stealthy, Scouting |
| 234 | **Ledward** | Private. The first to fall ill | 3 | $2,000 | Auto Weapons, Athletics, Survival |
| 235 | **Cole** | Private. Big gun, few words | 4 | $2,300 | Auto Weapons, Heavy Weapons, Bodybuilding |
| 236 | **Ankor** | Private. Fast and loud | 3 | $2,100 | Auto Weapons, Demolitions, Athletics |

</div>

</details>

<details>
<summary><b>Romulus 2024</b> · 5 operators · Renaissance station</summary>

<div align="center">

| ID | Name | Role | Lvl | Day rate | Traits |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 237 | **Rain**<br><sub>Rain Carradine</sub> | Orphan miner. Wants out of the colony - and gets out | 4 | $2,600 | Survival, Auto Weapons, Stealthy |
| 238 | **Tyler** | Miner. Rain's ex. The plan was his | 3 | $2,000 | Squadleader, Athletics, Scouting |
| 239 | **Kay** | Tyler's younger sister. Pregnant, and scared | 2 | $1,300 | Doctor, Stealthy, Survival |
| 240 | **Bjorn** | Tyler's cousin. Hot-headed, hates synthetics | 3 | $1,800 | Auto Weapons, Melee, Bodybuilding |
| 241 | **Navarro** | Pilot and mechanic of the Corbelan | 3 | $1,900 | Technician, Radio Operator, Athletics |

</div>

</details>

## Stats

<details>
<summary><b>Stats</b> · all 58 mercenaries · 11 stats</summary>

<div align="center">

<table>
<thead>
<tr><th align="center">ID</th><th align="center">Name</th><th align="center">Film</th><th align="center">Lvl</th><th align="center">HLT</th><th align="center">AGI</th><th align="center">DEX</th><th align="center">STR</th><th align="center">WIS</th><th align="center">LDR</th><th align="center">MRK</th><th align="center">MEC</th><th align="center">EXP</th><th align="center">MED</th></tr>
</thead>
<tbody>
<tr><td align="center">31</td><td align="center"><b>Dallas</b></td><td align="center" rowspan="6"><b>1979</b></td><td align="center">4</td><td align="center">75</td><td align="center">65</td><td align="center">70</td><td align="center">60</td><td align="center">80</td><td align="center">80</td><td align="center">55</td><td align="center">55</td><td align="center">20</td><td align="center">25</td></tr>
<tr><td align="center">32</td><td align="center"><b>Ripley</b></td><td align="center">5</td><td align="center">82</td><td align="center">80</td><td align="center">76</td><td align="center">62</td><td align="center">85</td><td align="center">70</td><td align="center">55</td><td align="center">65</td><td align="center">35</td><td align="center">40</td></tr>
<tr><td align="center">33</td><td align="center"><b>Kane</b></td><td align="center">3</td><td align="center">72</td><td align="center">70</td><td align="center">72</td><td align="center">60</td><td align="center">82</td><td align="center">60</td><td align="center">50</td><td align="center">45</td><td align="center">25</td><td align="center">25</td></tr>
<tr><td align="center">34</td><td align="center"><b>Lambert</b></td><td align="center">3</td><td align="center">62</td><td align="center">70</td><td align="center">74</td><td align="center">45</td><td align="center">84</td><td align="center">35</td><td align="center">45</td><td align="center">55</td><td align="center">15</td><td align="center">30</td></tr>
<tr><td align="center">35</td><td align="center"><b>Parker</b></td><td align="center">4</td><td align="center">88</td><td align="center">64</td><td align="center">70</td><td align="center">85</td><td align="center">66</td><td align="center">45</td><td align="center">62</td><td align="center"><b>90</b></td><td align="center">70</td><td align="center">20</td></tr>
<tr><td align="center">36</td><td align="center"><b>Brett</b></td><td align="center">3</td><td align="center">76</td><td align="center">60</td><td align="center">72</td><td align="center">70</td><td align="center">60</td><td align="center">25</td><td align="center">48</td><td align="center">82</td><td align="center">55</td><td align="center">15</td></tr>
<tr><td align="center">170</td><td align="center"><b>Ripley</b></td><td align="center" rowspan="8"><b>1986</b></td><td align="center">6</td><td align="center">85</td><td align="center">82</td><td align="center">80</td><td align="center">65</td><td align="center">88</td><td align="center">75</td><td align="center">78</td><td align="center">65</td><td align="center">45</td><td align="center">40</td></tr>
<tr><td align="center">171</td><td align="center"><b>Hicks</b></td><td align="center">7</td><td align="center"><b>90</b></td><td align="center">78</td><td align="center">82</td><td align="center">78</td><td align="center">85</td><td align="center">82</td><td align="center">85</td><td align="center">55</td><td align="center">60</td><td align="center">40</td></tr>
<tr><td align="center">172</td><td align="center"><b>Burke</b></td><td align="center">3</td><td align="center">60</td><td align="center">55</td><td align="center">65</td><td align="center">45</td><td align="center">82</td><td align="center">60</td><td align="center">35</td><td align="center">40</td><td align="center">15</td><td align="center">20</td></tr>
<tr><td align="center">173</td><td align="center"><b>Hudson</b></td><td align="center">5</td><td align="center">80</td><td align="center">80</td><td align="center">76</td><td align="center">75</td><td align="center">58</td><td align="center">30</td><td align="center">74</td><td align="center">60</td><td align="center">45</td><td align="center">25</td></tr>
<tr><td align="center">174</td><td align="center"><b>Apone</b></td><td align="center">7</td><td align="center"><b>92</b></td><td align="center">72</td><td align="center">78</td><td align="center">85</td><td align="center">80</td><td align="center">88</td><td align="center">84</td><td align="center">45</td><td align="center">55</td><td align="center">35</td></tr>
<tr><td align="center">175</td><td align="center"><b>Vasquez</b></td><td align="center">6</td><td align="center">88</td><td align="center">80</td><td align="center">80</td><td align="center">82</td><td align="center">62</td><td align="center">40</td><td align="center">86</td><td align="center">40</td><td align="center">60</td><td align="center">20</td></tr>
<tr><td align="center">176</td><td align="center"><b>Gorman</b></td><td align="center">3</td><td align="center">68</td><td align="center">62</td><td align="center">70</td><td align="center">55</td><td align="center">75</td><td align="center">58</td><td align="center">52</td><td align="center">45</td><td align="center">30</td><td align="center">30</td></tr>
<tr><td align="center">177</td><td align="center"><b>Drake</b></td><td align="center">5</td><td align="center">86</td><td align="center">70</td><td align="center">74</td><td align="center">85</td><td align="center">55</td><td align="center">30</td><td align="center">80</td><td align="center">45</td><td align="center">55</td><td align="center">15</td></tr>
<tr><td align="center">178</td><td align="center"><b>Ripley</b></td><td align="center" rowspan="6"><b>1992</b></td><td align="center">6</td><td align="center">80</td><td align="center">80</td><td align="center">78</td><td align="center">64</td><td align="center">88</td><td align="center">78</td><td align="center">60</td><td align="center">72</td><td align="center">45</td><td align="center">45</td></tr>
<tr><td align="center">179</td><td align="center"><b>Dillon</b></td><td align="center">6</td><td align="center"><b>90</b></td><td align="center">70</td><td align="center">72</td><td align="center">88</td><td align="center">75</td><td align="center">85</td><td align="center">60</td><td align="center">50</td><td align="center">40</td><td align="center">30</td></tr>
<tr><td align="center">180</td><td align="center"><b>Clemens</b></td><td align="center">4</td><td align="center">70</td><td align="center">62</td><td align="center">78</td><td align="center">55</td><td align="center"><b>90</b></td><td align="center">45</td><td align="center">40</td><td align="center">55</td><td align="center">25</td><td align="center"><b>90</b></td></tr>
<tr><td align="center">181</td><td align="center"><b>Golic</b></td><td align="center">3</td><td align="center">80</td><td align="center">72</td><td align="center">66</td><td align="center">78</td><td align="center">35</td><td align="center">15</td><td align="center">45</td><td align="center">40</td><td align="center">50</td><td align="center">10</td></tr>
<tr><td align="center">182</td><td align="center"><b>Andrews</b></td><td align="center">4</td><td align="center">75</td><td align="center">55</td><td align="center">65</td><td align="center">65</td><td align="center">70</td><td align="center">72</td><td align="center">58</td><td align="center">35</td><td align="center">30</td><td align="center">30</td></tr>
<tr><td align="center">183</td><td align="center"><b>Aaron</b></td><td align="center">3</td><td align="center">70</td><td align="center">58</td><td align="center">66</td><td align="center">55</td><td align="center">62</td><td align="center">35</td><td align="center">50</td><td align="center">60</td><td align="center">25</td><td align="center">35</td></tr>
<tr><td align="center">242</td><td align="center"><b>Elgin</b></td><td align="center" rowspan="10"><b>1997</b></td><td align="center">6</td><td align="center">82</td><td align="center">70</td><td align="center">74</td><td align="center">70</td><td align="center">78</td><td align="center">80</td><td align="center">74</td><td align="center">50</td><td align="center">40</td><td align="center">25</td></tr>
<tr><td align="center">243</td><td align="center"><b>Johner</b></td><td align="center">6</td><td align="center"><b>95</b></td><td align="center">68</td><td align="center">72</td><td align="center"><b>95</b></td><td align="center">45</td><td align="center">30</td><td align="center">84</td><td align="center">35</td><td align="center">60</td><td align="center">10</td></tr>
<tr><td align="center">244</td><td align="center"><b>Kristie</b></td><td align="center">7</td><td align="center">88</td><td align="center">88</td><td align="center"><b>90</b></td><td align="center">78</td><td align="center">70</td><td align="center">40</td><td align="center"><b>90</b></td><td align="center">40</td><td align="center">55</td><td align="center">20</td></tr>
<tr><td align="center">245</td><td align="center"><b>Vriess</b></td><td align="center">5</td><td align="center">70</td><td align="center">25</td><td align="center">85</td><td align="center">60</td><td align="center">75</td><td align="center">30</td><td align="center">74</td><td align="center"><b>95</b></td><td align="center">70</td><td align="center">30</td></tr>
<tr><td align="center">246</td><td align="center"><b>Hillard</b></td><td align="center">4</td><td align="center">70</td><td align="center">76</td><td align="center">76</td><td align="center">50</td><td align="center">74</td><td align="center">45</td><td align="center">58</td><td align="center">70</td><td align="center">25</td><td align="center">35</td></tr>
<tr><td align="center">247</td><td align="center"><b>Perez</b></td><td align="center">6</td><td align="center">75</td><td align="center">55</td><td align="center">62</td><td align="center">62</td><td align="center">82</td><td align="center"><b>90</b></td><td align="center">70</td><td align="center">35</td><td align="center">40</td><td align="center">25</td></tr>
<tr><td align="center">248</td><td align="center"><b>Wren</b></td><td align="center">4</td><td align="center">62</td><td align="center">60</td><td align="center">78</td><td align="center">48</td><td align="center"><b>90</b></td><td align="center">55</td><td align="center">45</td><td align="center">55</td><td align="center">20</td><td align="center">80</td></tr>
<tr><td align="center">249</td><td align="center"><b>Gediman</b></td><td align="center">3</td><td align="center">60</td><td align="center">58</td><td align="center">78</td><td align="center">45</td><td align="center"><b>92</b></td><td align="center">35</td><td align="center">35</td><td align="center">60</td><td align="center">15</td><td align="center">85</td></tr>
<tr><td align="center">250</td><td align="center"><b>DiStefano</b></td><td align="center">5</td><td align="center">85</td><td align="center">78</td><td align="center">78</td><td align="center">76</td><td align="center">70</td><td align="center">45</td><td align="center">82</td><td align="center">45</td><td align="center">45</td><td align="center">30</td></tr>
<tr><td align="center">251</td><td align="center"><b>Purvis</b></td><td align="center">3</td><td align="center">86</td><td align="center">64</td><td align="center">62</td><td align="center">84</td><td align="center">55</td><td align="center">25</td><td align="center">45</td><td align="center">55</td><td align="center">20</td><td align="center">15</td></tr>
<tr><td align="center">184</td><td align="center"><b>Shaw</b></td><td align="center" rowspan="9"><b>2012</b></td><td align="center">5</td><td align="center">80</td><td align="center">74</td><td align="center">76</td><td align="center">55</td><td align="center"><b>90</b></td><td align="center">62</td><td align="center">50</td><td align="center">55</td><td align="center">30</td><td align="center">70</td></tr>
<tr><td align="center">185</td><td align="center"><b>Vickers</b></td><td align="center">5</td><td align="center">72</td><td align="center">76</td><td align="center">74</td><td align="center">58</td><td align="center">85</td><td align="center">82</td><td align="center">56</td><td align="center">40</td><td align="center">30</td><td align="center">25</td></tr>
<tr><td align="center">186</td><td align="center"><b>Weyland</b></td><td align="center">4</td><td align="center">55</td><td align="center">45</td><td align="center">62</td><td align="center">42</td><td align="center"><b>95</b></td><td align="center"><b>90</b></td><td align="center">42</td><td align="center">60</td><td align="center">20</td><td align="center">40</td></tr>
<tr><td align="center">187</td><td align="center"><b>Holloway</b></td><td align="center">4</td><td align="center">80</td><td align="center">72</td><td align="center">70</td><td align="center">72</td><td align="center">85</td><td align="center">55</td><td align="center">55</td><td align="center">60</td><td align="center">35</td><td align="center">35</td></tr>
<tr><td align="center">188</td><td align="center"><b>Janek</b></td><td align="center">6</td><td align="center">88</td><td align="center">70</td><td align="center">76</td><td align="center">80</td><td align="center">78</td><td align="center">85</td><td align="center">70</td><td align="center">80</td><td align="center">50</td><td align="center">30</td></tr>
<tr><td align="center">189</td><td align="center"><b>Fifield</b></td><td align="center">3</td><td align="center">75</td><td align="center">70</td><td align="center">72</td><td align="center">65</td><td align="center">70</td><td align="center">25</td><td align="center">60</td><td align="center">70</td><td align="center">75</td><td align="center">15</td></tr>
<tr><td align="center">190</td><td align="center"><b>Millburn</b></td><td align="center">3</td><td align="center">70</td><td align="center">68</td><td align="center">70</td><td align="center">58</td><td align="center">80</td><td align="center">30</td><td align="center">45</td><td align="center">50</td><td align="center">25</td><td align="center">55</td></tr>
<tr><td align="center">220</td><td align="center"><b>Ravel</b></td><td align="center">4</td><td align="center">80</td><td align="center">66</td><td align="center">74</td><td align="center">72</td><td align="center">72</td><td align="center">40</td><td align="center">62</td><td align="center">82</td><td align="center">45</td><td align="center">25</td></tr>
<tr><td align="center">221</td><td align="center"><b>Ford</b></td><td align="center">4</td><td align="center">68</td><td align="center">66</td><td align="center">76</td><td align="center">50</td><td align="center">88</td><td align="center">40</td><td align="center">40</td><td align="center">50</td><td align="center">20</td><td align="center"><b>90</b></td></tr>
<tr><td align="center">222</td><td align="center"><b>Daniels</b></td><td align="center" rowspan="14"><b>2017</b></td><td align="center">6</td><td align="center">85</td><td align="center">82</td><td align="center">80</td><td align="center">62</td><td align="center">88</td><td align="center">74</td><td align="center">76</td><td align="center">70</td><td align="center">45</td><td align="center">40</td></tr>
<tr><td align="center">223</td><td align="center"><b>Oram</b></td><td align="center">4</td><td align="center">72</td><td align="center">64</td><td align="center">70</td><td align="center">62</td><td align="center">82</td><td align="center">66</td><td align="center">52</td><td align="center">55</td><td align="center">30</td><td align="center">30</td></tr>
<tr><td align="center">224</td><td align="center"><b>Tennessee</b></td><td align="center">5</td><td align="center">80</td><td align="center">72</td><td align="center">76</td><td align="center">70</td><td align="center">74</td><td align="center">55</td><td align="center">66</td><td align="center">85</td><td align="center">45</td><td align="center">25</td></tr>
<tr><td align="center">225</td><td align="center"><b>Karin</b></td><td align="center">4</td><td align="center">68</td><td align="center">66</td><td align="center">74</td><td align="center">48</td><td align="center">88</td><td align="center">40</td><td align="center">40</td><td align="center">50</td><td align="center">20</td><td align="center">75</td></tr>
<tr><td align="center">226</td><td align="center"><b>Maggie</b></td><td align="center">4</td><td align="center">72</td><td align="center">74</td><td align="center">76</td><td align="center">52</td><td align="center">78</td><td align="center">45</td><td align="center">50</td><td align="center">80</td><td align="center">30</td><td align="center">35</td></tr>
<tr><td align="center">227</td><td align="center"><b>Ricks</b></td><td align="center">3</td><td align="center">75</td><td align="center">68</td><td align="center">70</td><td align="center">64</td><td align="center">76</td><td align="center">35</td><td align="center">55</td><td align="center">60</td><td align="center">30</td><td align="center">30</td></tr>
<tr><td align="center">228</td><td align="center"><b>Upworth</b></td><td align="center">3</td><td align="center">70</td><td align="center">66</td><td align="center">72</td><td align="center">58</td><td align="center">80</td><td align="center">38</td><td align="center">48</td><td align="center">55</td><td align="center">25</td><td align="center">70</td></tr>
<tr><td align="center">230</td><td align="center"><b>Branson</b></td><td align="center">5</td><td align="center">78</td><td align="center">70</td><td align="center">72</td><td align="center">72</td><td align="center">84</td><td align="center">82</td><td align="center">66</td><td align="center">62</td><td align="center">35</td><td align="center">35</td></tr>
<tr><td align="center">231</td><td align="center"><b>Lope</b></td><td align="center">6</td><td align="center">88</td><td align="center">72</td><td align="center">78</td><td align="center">82</td><td align="center">76</td><td align="center">86</td><td align="center">82</td><td align="center">50</td><td align="center">55</td><td align="center">35</td></tr>
<tr><td align="center">232</td><td align="center"><b>Hallett</b></td><td align="center">4</td><td align="center">82</td><td align="center">70</td><td align="center">74</td><td align="center">80</td><td align="center">62</td><td align="center">40</td><td align="center">72</td><td align="center">45</td><td align="center">45</td><td align="center">25</td></tr>
<tr><td align="center">233</td><td align="center"><b>Rosenthal</b></td><td align="center">4</td><td align="center">80</td><td align="center">74</td><td align="center">76</td><td align="center">72</td><td align="center">64</td><td align="center">45</td><td align="center">76</td><td align="center">45</td><td align="center">40</td><td align="center">25</td></tr>
<tr><td align="center">234</td><td align="center"><b>Ledward</b></td><td align="center">3</td><td align="center">78</td><td align="center">72</td><td align="center">72</td><td align="center">72</td><td align="center">60</td><td align="center">30</td><td align="center">68</td><td align="center">40</td><td align="center">35</td><td align="center">30</td></tr>
<tr><td align="center">235</td><td align="center"><b>Cole</b></td><td align="center">4</td><td align="center">82</td><td align="center">70</td><td align="center">74</td><td align="center">78</td><td align="center">60</td><td align="center">35</td><td align="center">74</td><td align="center">45</td><td align="center">50</td><td align="center">20</td></tr>
<tr><td align="center">236</td><td align="center"><b>Ankor</b></td><td align="center">3</td><td align="center">80</td><td align="center">72</td><td align="center">72</td><td align="center">76</td><td align="center">58</td><td align="center">30</td><td align="center">72</td><td align="center">40</td><td align="center">45</td><td align="center">20</td></tr>
<tr><td align="center">237</td><td align="center"><b>Rain</b></td><td align="center" rowspan="5"><b>2024</b></td><td align="center">4</td><td align="center">80</td><td align="center">82</td><td align="center">80</td><td align="center">58</td><td align="center">82</td><td align="center">60</td><td align="center">70</td><td align="center">62</td><td align="center">30</td><td align="center">40</td></tr>
<tr><td align="center">238</td><td align="center"><b>Tyler</b></td><td align="center">3</td><td align="center">80</td><td align="center">74</td><td align="center">72</td><td align="center">72</td><td align="center">70</td><td align="center">62</td><td align="center">60</td><td align="center">58</td><td align="center">35</td><td align="center">25</td></tr>
<tr><td align="center">239</td><td align="center"><b>Kay</b></td><td align="center">2</td><td align="center">66</td><td align="center">72</td><td align="center">74</td><td align="center">48</td><td align="center">74</td><td align="center">30</td><td align="center">42</td><td align="center">45</td><td align="center">20</td><td align="center">50</td></tr>
<tr><td align="center">240</td><td align="center"><b>Bjorn</b></td><td align="center">3</td><td align="center">84</td><td align="center">74</td><td align="center">70</td><td align="center">80</td><td align="center">55</td><td align="center">30</td><td align="center">66</td><td align="center">50</td><td align="center">50</td><td align="center">20</td></tr>
<tr><td align="center">241</td><td align="center"><b>Navarro</b></td><td align="center">3</td><td align="center">72</td><td align="center">74</td><td align="center">78</td><td align="center">54</td><td align="center">76</td><td align="center">40</td><td align="center">52</td><td align="center">80</td><td align="center">30</td><td align="center">25</td></tr>
</tbody>
</table>

</div>

Values of 90+ are in bold.

</details>

Lvl experience level, HLT health, AGI agility, DEX dexterity, STR strength, WIS wisdom, LDR leadership, MRK marksmanship, MEC mechanical, EXP explosives, MED medical.

## Screenshots

Screenshots of the mod will be added here with the first release.

## Troubleshooting / FAQ

**Windows SmartScreen says "Windows protected your PC" when I start `ja2at.exe`.**
Windows shows this for new programs downloaded from the internet that it does not know yet. Check the archive with the scanners and the SHA-256 checksum above, then press *More info* → *Run anyway*.

**I see the standard A.I.M. and M.E.R.C. mercs, not The Alien Team.**
Start the game with **`ja2at.exe`**, not the stock `ja2.exe`, and begin a **new game**. The mod runs from its own `Data-Alien` folder; `ja2.exe` still starts the stock 1.13 game.

**My save does not load after updating the mod.**
Saves from older versions of the mod are not compatible with newer ones. Start a new game, or go back to the version the save was made with.

**How do I go back to the stock game?**
Start the game with `ja2.exe` — the stock `Data-1.13` is not touched by the mod. To remove the mod completely, restore the backup copy of your game folder you made before installing.

## Reporting bugs

Found a bug or have an idea? Open an [issue](../../issues) and include:

- the mod version (the name of the release archive) and your game version (the 1.13 build from `JA2_113-Version.txt`, and any other mods you use);
- whether you started the game with `ja2at.exe` or with the stock `ja2.exe`;
- what you did, what you expected and what happened instead;
- a screenshot, and the save game if the problem is with one (zip it if it is large).

Please check the [open issues](../../issues) first — maybe it is already reported. More in [Contributing](CONTRIBUTING.md).

## 💬 Community

Questions, ideas, mods and talk about Jagged Alliance 2 — come and join the fans:

<p align="center">
  <a href="https://thepit.ja-galaxy-forum.com/"><img src="https://img.shields.io/badge/The_Bear%27s_Pit-JA_Galaxy_Forum-8b5a2b?style=for-the-badge" alt="The Bear's Pit — JA Galaxy Forum"></a>
  <a href="https://discord.com/invite/Ku2H9Hf"><img src="https://img.shields.io/badge/Discord-Join_the_chat-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://www.facebook.com/bearspit"><img src="https://img.shields.io/badge/Facebook-The_Bear%27s_Pit-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook — The Bear's Pit"></a>
  <a href="../../discussions"><img src="https://img.shields.io/badge/Discussions-Ask_%26_share-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Discussions"></a>
</p>

- **[The Bear's Pit — JA Galaxy Forum](https://thepit.ja-galaxy-forum.com/)** — the home of Jagged Alliance 2 and 1.13 modding: mods, maps, tools and help.
- **[Discord](https://discord.com/invite/Ku2H9Hf)** — chat with other players and modders.
- **[Facebook — The Bear's Pit](https://www.facebook.com/bearspit)** — news and posts from The Bear's Pit community on Facebook.
- **[GitHub Discussions](../../discussions)** — ask a question, share an idea or show your squad right here in the repository: press **New discussion**.
  - Mod creator: [`oleksandr1024`](https://discord.com/users/660456590364901387)
  - Server admins: [`kitty624`](https://discord.com/users/485597085496901633), [`papa_bear2842`](https://discord.com/users/348550304557563905), [`h_world_37628`](https://discord.com/users/1407768046956839042), [`tais0001`](https://discord.com/users/118450058780868613), [`marco6326`](https://discord.com/users/201429346240430080), [`asdow5338`](https://discord.com/users/484390622040686592)

Before you post, read the [Code of Conduct](CODE_OF_CONDUCT.md). Want to help? See [Contributing](CONTRIBUTING.md). Found a security problem? See the [Security policy](SECURITY.md).

## Changelog

What's new in each version is listed on the [Releases](../../releases) page.

## Credits

Thanks to the whole **Jagged Alliance 2** fan community — the modders, map makers and players who have kept this game alive for decades, and the **1.13** team whose work makes mods like this possible. This mod is made by fans, for fans.

Created by **Krainer (Oleksandr Khrashchevskyi)** — [`oleksandr1024`](https://discord.com/users/660456590364901387) on Discord. Thanks to the admins of the Discord server — [`kitty624`](https://discord.com/users/485597085496901633), [`papa_bear2842`](https://discord.com/users/348550304557563905), [`h_world_37628`](https://discord.com/users/1407768046956839042), [`tais0001`](https://discord.com/users/118450058780868613), [`marco6326`](https://discord.com/users/201429346240430080) and [`asdow5338`](https://discord.com/users/484390622040686592).

## License

Made by **Krainer**. The mod is free and released under [CC BY-NC-SA 4.0](LICENSE). Jagged Alliance 2 and the Alien films belong to their respective owners; this is a non-commercial fan work.

Copyright (c) 2026 Krainer (Oleksandr Khrashchevskyi)

## Disclaimer

This is a fan-made mod and is not affiliated with the owners of Jagged Alliance 2 or the Alien films. The mod does not include the game; you need your own copy of Jagged Alliance 2 with v1.13. **Installing the mod overwrites files in your game folder — always keep a backup copy of your game folder and saves.** You use it at your own risk.
