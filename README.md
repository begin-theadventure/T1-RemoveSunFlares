# <p align="center">b-ta.RemoveSunFlares</p>
<p align="center">Removes sun flares.</p>

`env_sun.pcf`, `env_sun_haven.pcf` and `env_sun_red_dwarf.pcf` files changed to empty.

Credit: [Remove Sun Flares](https://noskill.gitbook.io/titanfall2/modding/misc/remove-sun-flares).

<p align="center"><img src="https://github.com/begin-theadventure/N-RemoveSunFlares/assets/99835765/be617b34-b38b-48f0-97da-71622fe86354" align="center" width="48%"></p>

<p align="center">
  <img src="https://github.com/begin-theadventure/N-RemoveSunFlares/assets/99835765/233885ad-f82c-474b-8167-3f59693ddf7f" width="45%">
&nbsp;
  <img src="https://github.com/begin-theadventure/N-RemoveSunFlares/assets/99835765/e4c34aa0-28fa-4c15-be75-e5b002437312" width="45%">
</p>
<p align="center">
  <img src="https://github.com/begin-theadventure/N-RemoveSunFlares/assets/99835765/c9b24f49-036b-41ad-a1c1-d447a6648c8a" width="45%">
&nbsp;
  <img src="https://github.com/begin-theadventure/N-RemoveSunFlares/assets/99835765/5657a527-65ea-4f71-8998-88f4312ce2dc" width="45%">
</p>

## <p align="center">How to install</p>

Go to [Releases](https://github.com/begin-theadventure/T1-RemoveSunFlares/releases), download the `englishclient_mp_common.bsp.pak000_dir.vpk` file, go to Titanfall/vpk, make a backup of the original file and replace it with the patched one.

## <p align="center">Tutorial</p>
<p align="center">(Only if you want to do it yourself)</p>

[HarmonyVPKTool](https://github.com/harmonytf/HarmonyVPKTool):

Open VPK: Titanfall1/vpk/`englishclient_mp_common.bsp.pak000_dir.vpk`.

Create empty text files with earlier mentioned names such as `env_sun.pcf`.

Patch VPK ->  particles/`name`; Select File (empty file with the same `name`) -> Patch -> Choose folder other than `vpk` -> Repeat until the last third file.

Remove `client_mp_common.bsp.pak000_999.vpk` as it's not needed, and now you have a patched `englishclient_mp_common.bsp.pak000_dir.vpk` with no sun flares!
