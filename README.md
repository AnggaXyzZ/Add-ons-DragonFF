# Add-ons DragonFF 👻

DragonFF adalah Addon Blender untuk mengimpor dan mengekspor file GTA.

Saat ini, hanya file Renderware yang didukung. Dukungan untuk format selain .dff direncanakan. 

## Supported Features

Berikut ini adalah daftar fitur yang didukung oleh addon

#### File Types

- [X] Model files
- [ ] Texture Files
- [X] Collision files (including the ones packed in dff)
  - [X] Import
  - [X] Export *(Partial)*
- [ ] Map files (.ipl, .ide)
  - [X] Import *(Partial, experimental)*
  - [ ] Export
- [ ] Animation files

#### Model Features

- [X] Skinned mesh support
- [X] Multiple UV Maps
- [X] Mass export
- [X] Material Effects
  - [X] Environment/Normal Maps
  - [ ] Dual Textures
  - [X] UV Animation
- [X] Rockstar Specular and Reflection Extensions
- [ ] 2D Effects

## Installation

1. [Download](https://github.com/Parik27/DragonFF/archive/refs/heads/master.zip) file zip addon dari cabang master terbaru
2. Impor file .zip yang diunduh dengan memilihnya dari *(User) Preferences/Addons/Install from File*
3. Setel addon "GTA DragonFF" ​​ke diaktifkan
4. Impor dff dari tab Impor atau IPL/IFP dari panel di *Pengaturan Pemandangan*

## Python Module

Skrip python telah dirancang dengan mempertimbangkan penggunaan kembali. Saat ini, modul dff bersifat mandiri, dan dapat digunakan dengan instance Python lainnya tanpa memerlukan Blender API.

#### Standalone Modules

* [X] - DFF - `dff.py`
* [ ] - TXD - `txd.py`
* [X] - COL - `col.py`
* [X] - IPL/IDE - `map.py` (partial, experimental)
* [ ] - IFP - `ifp.py`

