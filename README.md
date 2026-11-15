# Khaufnaak Haven

An Unreal Engine 5.8 project.

Built on the First Person Blueprints template, with custom level content,
props, characters and audio.

## Requirements

- **Unreal Engine 5.8**
- **Git LFS** — this repository stores its binary assets (`.uasset`, `.umap`,
  textures, models, audio) in Git LFS. Cloning without LFS installed will
  produce pointer files instead of real assets.

```bash
git lfs install
git clone https://github.com/AlooDaParatha/FahhBounceOrWhat.git
```

Already cloned without LFS? Recover it with:

```bash
git lfs install
git lfs pull
```

## Project layout

| Path         | Contents                                                       |
| ------------ | -------------------------------------------------------------- |
| `Content/`   | Game assets — levels, blueprints, meshes, textures, audio        |
| `Raw Content/` | Source art, DCC files and texture packages before import     |
| `Config/`    | Project settings (`Default*.ini`)                                |
| `Source/`    | C++ source, when present                                         |

Generated directories (`Binaries/`, `Intermediate/`, `Saved/`,
`DerivedDataCache/`) are intentionally not tracked — see `.gitignore`.

## License

Assets sourced from the Unreal Engine marketplace remain under their original
licenses; see the `license.txt` files inside `Raw Content/`.
