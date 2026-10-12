# ⚡ Auto-update Zax Addons (Prism Launcher)

Do this **once**. After that, every time you press **Play**, Prism checks for a new Zax Addons version and installs it for you.

## 1. Download the updater
Download **`packwiz-installer-bootstrap.jar`** from the official page:
https://github.com/packwiz/packwiz-installer-bootstrap/releases/latest

## 2. Put it in your instance folder
1. In Prism, right-click your Minecraft 26.1.2 instance → **Folder**.
2. Open the **`minecraft`** folder (the one that has `mods` inside).
3. Put `packwiz-installer-bootstrap.jar` there (next to the `mods` folder, **not** inside it).

## 3. Remove the old jar once
Open the **`mods`** folder and delete any old **`zax-addons-…jar`** or **`aura-addons-…jar`**. The updater installs the right one for you.

## 4. Add the launch command
1. In Prism, right-click the instance → **Edit** → **Settings** → **Custom commands**.
2. Tick **Custom commands**.
3. In **Pre-launch command**, paste exactly:

```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/zaxlord123/zax-addons/main/pack/pack.toml
```

4. Close the window and press **Play**.

The first time, a small window shows it downloading Zax Addons, then Minecraft starts. From now on updates happen by themselves.

> You still need **Fabric API** in your mods folder, and your **access code** (type `/za`, press **Paste from clipboard** then **Activate**).

**Turn it off any time:** untick **Custom commands** in the same settings window.
