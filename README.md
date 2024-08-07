# Adaptive cybersecurity game: Junior hacker training

Adaptive game for [KYPO CRP](https://docs.crp.kypo.muni.cz/).

Follow [general instructions](https://docs.crp.kypo.muni.cz/basic-concepts/typical-training-workflow/training-workflow-cloud/) to set up the game.

This game uses `kali` and `debian-10` images from [MUNI-KYPO-IMAGES](https://gitlab.ics.muni.cz/muni-kypo-images), which need to be available in OpenStack. To get and upload the images, see [this guide](https://gitlab.ics.muni.cz/muni-kypo-images/muni-kypo-images-wiki/-/wikis/How-to-get-image-for-OpenStack).

## Game Levels Summary
- connect to the sandbox
- filesystem exploration
- host scan with `nmap`
- manual password guessing at `SSH`
- explore filesystem and transfer files with `scp`
- zip password cracking with `fcrackzip`

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|attacker|kali|standard.small|
|server|debian-10|standard.small|
|client|debian-10|standard.small|
|router|debian-10|standard.small|


## License and Credits
See [licensing](https://gitlab.ics.muni.cz/muni-kypo-trainings/games/all-games-index#license) and how to [cite it](https://gitlab.ics.muni.cz/muni-kypo-trainings/games/all-games-index#how-to-cite-the-games).

[Cybersecurity Laboratory](https://cybersec.fi.muni.cz)\
Faculty of Informatics\
Masaryk University

**Leading author:** Miriam Gáliková

**Contributors/Consultants:** Valdemar Švábenský, Jan Vykopal
