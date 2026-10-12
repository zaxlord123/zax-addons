# ⚡ Get Zax Addons with auto-update (Prism Launcher)

## Easiest: one link (recommended)
1. Open **Prism Launcher** → **Add Instance** → **Import**.
2. Paste this link and press **OK**:

```
https://github.com/zaxlord123/zax-addons/raw/main/ZaxAddons-Prism.zip
```

3. Press **Play** on the new **Zax Addons** instance.

That's it. Minecraft 26.1.2, Fabric, Fabric API and Zax Addons install by themselves, and **every new version installs automatically each time you press Play**.

> First time only: type `/za`, press **Paste from clipboard** with your access code, then **Activate**.

---

## Already have your own instance? (manual way)
1. Download **`packwiz-installer-bootstrap.jar`**: https://github.com/packwiz/packwiz-installer-bootstrap/releases/latest
2. Prism → right-click your 26.1.2 instance → **Folder** → open **`minecraft`** → put the jar there (next to `mods`).
3. Delete any old **`zax-addons-…jar`** / **`aura-addons-…jar`** from `mods`.
4. Right-click the instance → **Edit** → **Settings** → **Custom commands** → tick it → **Pre-launch command**:

```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/zaxlord123/zax-addons/main/pack/pack.toml
```

## Force an update
Close Minecraft and press **Play** again. If it ever seems stuck, delete the `zax-addons-…jar` from `mods` and press Play.

**Turn auto-update off:** untick **Custom commands** in the instance settings.
