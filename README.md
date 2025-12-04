# Device List

## `Mi8937` (MSM8917 / MSM8937 / MSM8940)
- Redmi 3S / 3X (`land`)
- Redmi 4 Standard (`prada`)
- Redmi 4A (`rolex`)
- Redmi 4X (`santoni`)
- Redmi 5A (`riva`)
- Redmi Note 5A / Y1 Lite (`ugglite`)
- Redmi Note 5A / Y1 Prime (`ugg`)

## `Mi439` (SDM439)
- Xiaomi Redmi 7A (`pine`)
- Xiaomi Redmi 8 (`olive`)
- Xiaomi Redmi 8A (`olivelite`)
- Xiaomi Redmi 8A Dual (`olivewood`)

## `oxygen` - Mi MAX 2 (MSM8953)

## `vince` - Redmi 5 Plus (MSM8953)

## `uter` - Xiaomi UTER (MSM8953)

## `ysl` - Redmi Y2 / Xiaomi Redmi S2 (MSM8953)

## `onc` - Redmi Y3 / Xiaomi Redmi 7 (SDM632)

## `msm8937` - Qualcomm MSM8937 (MSM8937)

# Notes
- If you're going to build ROM which is supported here, Put the corresponding manifest file in `.repo/local_manifests`, re-run `repo sync`, and apply all the patches that's given in this repo.
- for Mi8937 & Mi439 use this : https://github.com/Mi-Thorium
- vince and ysl there are 4 submodules in the kernel "KernelSU, techpack/xiaomi-titanium, techpack/audio-legacy, drivers/staging/prima"

kernel xiaomi-ysl & vince setup :
```bash
git submodule update --init --recursive
```
