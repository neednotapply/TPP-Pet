# TPP-Pet
An animated pet for your favorite AI coding agent.
 

| Idle | Running Right | Running Left |
| --- | --- | --- |
| <img src="Previews/idle.gif" width="192" alt="Idle animation"> | <img src="Previews/running-right.gif" width="192" alt="Running right animation"> | <img src="Previews/running-left.gif" width="192" alt="Running left animation"> |

| Waving | Jumping | Failed |
| --- | --- | --- |
| <img src="Previews/waving.gif" width="192" alt="Waving animation"> | <img src="Previews/jumping.gif" width="192" alt="Jumping animation"> | <img src="Previews/failed.gif" width="192" alt="Failed animation"> |

| Waiting | Running | Review |
| --- | --- | --- |
| <img src="Previews/waiting.gif" width="192" alt="Waiting animation"> | <img src="Previews/running.gif" width="192" alt="Running animation"> | <img src="Previews/review.gif" width="192" alt="Review animation"> |

 ## Installation

The required pet files are in the repository's root:

```text
pet.json
spritesheet.webp
```

The pet ID is `TPP-Pet`, so it must be installed into a folder with that exact name.

---

## Option 1: Download from GitHub

Download the repository as a ZIP, extract it, and open the extracted `TPP-Pet` folder.

You only need these two files:

```text
pet.json
spritesheet.webp
```

`Alt Art/` and `Previews/` are optional reference material and are not required for installation.

---

## Option 2: Clone with Git

```bash
git clone https://github.com/neednotapply/TPP-Pet.git
cd TPP-Pet
```

---

## Install in Codex

Copy `pet.json` and `spritesheet.webp` into:

```text
~/.codex/pets/TPP-Pet/
```

### Windows PowerShell

Run this from the cloned or extracted `TPP-Pet` repository folder:

```powershell
$Destination = Join-Path $HOME ".codex\pets\TPP-Pet"

New-Item -ItemType Directory -Force $Destination
Copy-Item .\pet.json, .\spritesheet.webp $Destination
```

The finished folder should look like:

```text
C:\Users\<your-user>\.codex\pets\TPP-Pet\
├── pet.json
└── spritesheet.webp
```

Restart Codex, then select **The Pirate's Plunder** from the pet picker.

### macOS / Linux

Run this from the cloned or extracted `TPP-Pet` repository folder:

```bash
mkdir -p "$HOME/.codex/pets/TPP-Pet"
cp pet.json spritesheet.webp "$HOME/.codex/pets/TPP-Pet/"
```

The finished folder should look like:

```text
~/.codex/pets/TPP-Pet/
├── pet.json
└── spritesheet.webp
```

Restart Codex, then select **The Pirate's Plunder** from the pet picker.

---

## Install in [OpenPets](https://openpets.dev/) (Claude Code / OpenCode)

Install the pet into the same Codex folder first:

```text
~/.codex/pets/TPP-Pet/
```

Then open OpenPets and select or import the local pet folder:

```text
~/.codex/pets/TPP-Pet/
```

On Windows, select:

```text
C:\Users\<your-user>\.codex\pets\TPP-Pet\
```

Once selected, set **The Pirate's Plunder** as your active pet.

---

## Troubleshooting

* Ensure the destination folder is named exactly `TPP-Pet`.
* Ensure `pet.json` contains `"id": "TPP-Pet"`.
* Do not place `pet.json` inside an extra nested folder.
* Restart Codex or OpenPets after copying the files.
