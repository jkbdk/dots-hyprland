<div align="center">

# 【 end_4's Hyprland Dotfiles for Fedora 】

Automated setup of the Quickshell version of end_4's dotfiles on **Fedora Linux**

</div>

<div align="center">

![](https://img.shields.io/github/last-commit/EisregenHaha/fedora-hyprland?&style=for-the-badge&color=8ad7eb&logo=git&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/stars/EisregenHaha/fedora-hyprland?style=for-the-badge&logo=andela&color=86dbd7&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/repo-size/EisregenHaha/fedora-hyprland?color=86dbce&label=SIZE&logo=protondrive&style=for-the-badge&logoColor=D9E0EE&labelColor=26230e)
<a href="https://discord.gg/GtdRBXgMwq"> <img alt="Dynamic JSON Badge" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscordapp.com%2Fapi%2Finvites%2FGtdRBXgMwq%3Fwith_counts%3Dtrue&query=approximate_member_count&style=for-the-badge&logo=discord&logoColor=D9E0EE&label=discord&labelColor=%231E202B&color=86dbc0&link=https%3A%2F%2Fdiscord.gg%2FGtdRBXgMwq"> </a>

</div>

---

 <details> 
  <summary>Notable features</summary>
     
  - **Overview**: Shows open apps with live previews
  - **AI**: Gemini, Ollama, and more
  - **QoL**: screen translation, anti-flashbang, Google Lens
  - **Material themes**: Choose your wallpaper, done, enjoy
  - **Transparent installation**: Every command is shown before it's run
</details>
<details> 
  <summary>Installation</summary>

- _If you're new to Linux and decide to use Hyprland, you're in for a tough ride._
- Just run `bash <(curl -s https://ii.clsty.link/get)`
  - Or, clone this repo and run `./setup install`
  - See [the wiki](https://ii.clsty.link/en/ii-qs/01setup/) for more details
- **Keybinds**: Should be somewhat familiar to Windows or GNOME users. Important ones:
  - `Super`+`/` = keybind list
  - `Super`+`Enter` = terminal

> ✅ **Tested on Fedora 43 (older branches unmaintained and probably broken)**

---

<details>
  <summary>Software overview</summary>

| Software                                       | Purpose                                                                                 |
| ---------------------------------------------- | --------------------------------------------------------------------------------------- |
| [Hyprland](https://github.com/hyprwm/hyprland) | The compositor (manages and renders windows)                                            |
| [Quickshell](https://quickshell.outfoxxed.me/) | A QtQuick-based widget system, used for the status bar, sidebars, etc.                  |
| Others                                         | See [deps-info.md](https://github.com/end-4/dots-hyprland/blob/main/sdata/deps-info.md) |

</details>

<details>
    <summary>Discord</summary>
        <a href="https://discord.gg/GtdRBXgMwq"> Server link</a> | I hope this provides a friendlier environment for support without needing me to personally accept every friend request/DM. For real issues, prefer GitHub

</details>

<div align="center">
    <h2>• screenshots •</h2>
    <h3></h3>
</div>

## illogical-impulse<sup>Quickshell</sup>

| AI                                                                                        | Common widgets                                                                            |
| :---------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------- |
| ![image](https://github.com/user-attachments/assets/08d26785-b54d-4ad1-875b-bb08cc6757f5) | ![image](https://github.com/user-attachments/assets/4fcd63d9-0943-4b21-8737-4bed97b71961) |
| Window management                                                                         | Weeb power (sigh, thankfully can disable it)                                              |
| ![image](https://github.com/user-attachments/assets/86cc511b-0d33-4c78-bcc0-3037d02a17da) | ![image](https://github.com/user-attachments/assets/292259fc-57d3-4663-a583-2ce2faad13fb) |

Widget system: Quickshell | Support: Yes

## Installation

| AI, settings app                                                                                                                     | Some widgets                                                                                                                         |
| :----------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d4e7d07-d0b4-4406-a4c9-ed7ba90e3fe4" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a32395f-9437-4192-8faf-2951a9e84cbe" /> |
| Window management                                                                                                                    | wow look its orange                                                                                                                  |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c51bed8b-3670-4d4c-9074-873be224fb8e" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98703a66-0743-439f-a721-cef7afa6ab95" /> |

```bash
bash <(curl -s https://raw.githubusercontent.com/jkbdk/fedora-hyprland/f43/setup.sh)
```

or if you are using fish shell (non-posix-compliant shell) then:

```bash
bash -c "$(curl -s https://raw.githubusercontent.com/jkbdk/fedora-hyprland/f43/setup.sh)"
```

- I promise not to attempt an +ULTRARICOSHOT irl... Coins can go here: https://github.com/sponsors/end-4
- Tentacle cat hub twinkle internet points

[![Stargazers over time](https://starchart.cc/end-4/dots-hyprland.svg?variant=adaptive)](https://starchart.cc/end-4/dots-hyprland)

---

<div align="center">
    <h2>• previous styles •</h2>
    <h3></h3>
</div>

- **Unsupported!**
- **Source**: illogical-impulse AGS in `ii-ags` branch, others in `archive` branch.
- List is in reverse chronological order

- Custom configurations like enabling/disabling the dock or similar happen in the QS Settings found in the right Sidebar, or opened with `Super` `I`. Other, smaller stuff can also be configured in `.config/illogical-impulse/config.json`.
- To change your Icon pack you will need to select it in KDE Settings and then also change the configuration in `.config/kde-material-you-colors/config.conf`

### Regarding Updates

- Place any custom Hyprland config changes in `.config/hypr/custom` and then comment out the old configuration in `.config/hypr/hyprland.conf`.
- These files are **not overwritten** by the update process. Otherwise you **will** lose your configuration changes after updating.

### For Nvidia users:

Widget system: EWW | Support: No, dead

<a href="https://streamable.com/85ch8x">
<img src="https://github.com/end-4/dots-hyprland/assets/97237370/09533e64-b6d7-47eb-a840-ee90c6776adf" alt="Material Eww!">
</a>

- The Dark/Light and theme switcher wont work on first login, please select the "6) Update config files with exclusions" in the setup after your initial login to fix the permission error.
- If you want to raise your volume above the limit of 90, open `~/.config/illogical-impulse/config.json` and set the max volume allowed to 100. This is just a safety measure.
- If you're experiencing missing or broken icons, try switching your icon pack in the KDE settings and also check troubleshooting steps in the wiki, it's an issue with Adwaita.

Widget system: EWW | Support: No

<a href="https://streamable.com/7vo61k">
<img src="https://github.com/end-4/dots-hyprland/assets/97237370/42903d03-bf6f-49d4-be7f-dd77e6cb389d" alt="Desktop Preview">
</a>

### Archive

Widget system: EWW | Support: No

<a href="https://streamable.com/4oogot">
<img src="https://github.com/end-4/dots-hyprland/assets/97237370/190deb1e-f6f5-46ce-8cf0-9b39944c079d" alt="click the circles!">
</a>

---

Widget system: EWW | Support: No

<a href="https://streamable.com/5qx614">
<img src="https://github.com/end-4/dots-hyprland/assets/97237370/b15317b1-f295-49f5-b90c-fb6328b8d886" alt="Desktop Preview">
</a>

<div align="center">
    <h2>• inspirations/copying •</h2>
    <h3></h3>
</div>

- Inspiration: osu!lazer (Hybrid), Windows 11 (Windoes), AvdanOS (NovelKnock), Material Design 3 (m3ww & later)
- Copying: Absolutely, feel free. Just follow the license and it's all good
