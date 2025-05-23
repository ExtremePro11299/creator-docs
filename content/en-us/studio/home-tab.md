---
title: Home tab
description: The Home tab contains basic tools for building and testing your experience.
---

import BetaAlert from '../includes/beta-features/beta-alert.md'

The **Home** tab contains basic tools for building and testing your experience.

<img src="../assets/studio/general/Toolbar-Home-Tab.png" width="716" alt="Home tab indicated in Studio toolbar" />

## Clipboard

The first section from left contains tools for copying, cutting, pasting, and duplicating instances. You can perform these operations on both 3D world objects or instances in the [Explorer](../studio/explorer.md) window.

<table>
  <thead>
    <tr>
      <th>Action</th>
	  <th>Shortcut</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>**Paste**</td>
	  <td><kbd>Ctrl</kbd><kbd>V</kbd>&nbsp;(Windows)<br /><kbd>⌘</kbd><kbd>V</kbd> (Mac)</td>
      <td>Insert the clipboard contents.</td>
    </tr>
    <tr>
      <td>**Copy**</td>
	  <td><kbd>Ctrl</kbd><kbd>C</kbd>&nbsp;(Windows)<br /><kbd>⌘</kbd><kbd>C</kbd> (Mac)</td>
      <td>Copy the current selections to the clipboard.</td>
    </tr>
	<tr>
      <td>**Cut**</td>
	  <td><kbd>Ctrl</kbd><kbd>X</kbd>&nbsp;(Windows)<br /><kbd>⌘</kbd><kbd>X</kbd> (Mac)</td>
      <td>Cut the current selections and put on the clipboard.</td>
    </tr>
	<tr>
      <td>**Duplicate**</td>
	  <td><kbd>Ctrl</kbd><kbd>D</kbd>&nbsp;(Windows)<br /><kbd>⌘</kbd><kbd>D</kbd> (Mac)</td>
      <td>Duplicate the current selections at the same level in the hierarchy.</td>
    </tr>
  </tbody>
</table>

## Transform tools

The primary transform tools include **Select**, **Move**, **Scale**, and **Rotate**. When you choose a tool, visual draggers display on the selected object in the viewport.

<img src="../assets/studio/general/Transform-Tools.png" width="563" alt="Transform tools indicated in Studio's toolbar." />

<GridContainer numColumns="3">
  <figure>
    <img src="../assets/modeling/parts/Transform-Move-SM.png" alt="Move draggers shown on part in 3D viewport." />
    <figcaption>Move</figcaption>
  </figure>
  <figure>
    <img src="../assets/modeling/parts/Transform-Scale-SM.png" alt="Scale draggers shown on part in 3D viewport." />
    <figcaption>Scale</figcaption>
  </figure>
  <figure>
    <img src="../assets/modeling/parts/Transform-Rotate-SM.png" alt="Rotate draggers shown on part in 3D viewport." />
    <figcaption>Rotate</figcaption>
  </figure>
</GridContainer>

Tool transform **snapping** increments are based on **studs** for moving/scaling or **degrees** for rotating, each adjustable in the toolbar. While transforming, you can temporarily toggle snapping by holding the <kbd>Shift</kbd> key.

<img src="../assets/studio/general/Transform-Snapping.png" width="563" alt="Transform snapping tools indicated in Studio's toolbar." />

<Alert severity="info">
If the selected object and its visual draggers are not currently in view within the 3D viewport, you can press the <kbd>Tab</kbd> key to "summon" the draggers to your mouse pointer position, allowing you to transform the selected object from your current viewpoint.
</Alert>

### Mode

The **Mode** selector toggles between standard geometric transformations and [simulation of mechanical constraints](../physics/mechanical-constraints.md#simulate-constraints) while moving or rotating parts.

<img src="../assets/studio/general/Home-Tab-Mode.png" width="716" alt="Mode selector indicated in Home tab" />

### Collisions

The **Collisions** checkbox toggles the collisions state when you're transforming objects. If collisions are **off**, you can move, scale, and rotate objects so that they overlap each other; if collisions are **on**, you cannot transform objects to overlap other objects.

<img src="../assets/studio/general/Home-Tab-Collisions-On.png" width="716" alt="Collisions checkbox indicated in Home tab" />

### Transform coordinates

<kbd>Ctrl</kbd><kbd>L</kbd> on Windows or <kbd>⌘</kbd><kbd>L</kbd> on Mac toggles between transforming an object relative to **world** coordinates or the object's **local** coordinates. When in local mode, an **L** symbol appears to the lower-right of the object.

<Tabs>
  <TabItem label="World">
    <img src="../assets/modeling/parts/Move-World-Orientation.png" width="720" height="405" alt="Part draggers in World orientation mode" />
  </TabItem>
  <TabItem label="Local">
    <img src="../assets/modeling/parts/Move-Local-Orientation.png" width="720" height="405" alt="Part draggers in Local orientation mode" />
  </TabItem>
</Tabs>

## Terrain Editor

The **Editor** button opens a window with tools for creating and shaping static terrain. For more information, see [Terrain Editor](./terrain-editor.md).

<img src="../assets/studio/general/Home-Tab-Terrain-Editor.png" width="716" alt="Terrain Editor indicated in Home tab" />

## Toolbox

The [Toolbox](../projects/assets/toolbox.md) includes all of the models, images, meshes, audio, and more that you've published, or those published by groups you belong to. It also includes a selection of assets made by Roblox or Roblox community members.

<img src="../assets/studio/general/Home-Tab-Toolbox.png" width="716" alt="Toolbox indicated in Home tab" />

## Part insertion

The **Part** button inserts a new part into the workspace. Clicking the small dropdown arrow on the button lets you select either **Block**, **Sphere**, **Wedge**, **Corner&nbsp;Wedge**, or **Cylinder**. For more information, see [Parts](../parts/index.md).

<img src="../assets/studio/general/Insert-Part-Tool.png" width="300" alt="Part tool and its part type picker highlighted." />

## UI tools

The **UI** button opens a separate tab which lets you quickly insert, resize, and reposition common on‑screen UI objects, such as [labels](../ui/labels.md), [frames](../ui/frames.md), and [buttons](../ui/buttons.md). It also lets you access the built‑in [Style Editor](../ui/styling/editor.md) that allows you to create, manage, and apply UI styles for Roblox experiences.

<img src="../assets/studio/general/Home-Tab-UI.png" width="780" alt="UI button indicated in Home tab" />

<img src="../assets/studio/general/Toolbar-UI-Tab.png" width="780" alt="UI tab indicated in Studio toolbar" />

## Import 3D

The **Import 3D** tool allows you to import nearly any type of `.fbx` or `.obj` and associated texture files into Studio. See [3D&nbsp;Importer](../art/modeling/3d-importer.md) for more information.

<img src="../assets/studio/general/Home-Tab-Import-3D.png" width="780" alt="Import 3D button indicated in Home tab" />

## Color widget

Clicking the small dropdown arrow on the **Color** widget reveals a hexagonal color picker.

<img src="../assets/studio/general/Color-Picker.png" width="373" alt="Color widget's hexagonal picker." />

By default, clicking the overall **Color** button applies the chosen color to any **selected** parts. If you prefer a fill/paint workflow instead, toggle on **Color&nbsp;Action&nbsp;as&nbsp;Tool** and then click parts in the 3D viewport to apply the chosen color.

<img src="../assets/studio/general/Home-Tab-Color-Action-As-Tool.png" width="776" alt="Studio's Home tab with the Color Action as Tool selector indicated." />

<Alert severity="success">
For alternative ways to apply custom colors, see [Coloring Parts](../parts/index.md#colors-popup).
</Alert>

## Material widget

Clicking the small dropdown arrow on the **Material** widget reveals a [material](../parts/materials.md) picker.

<img src="../assets/studio/general/Material-Picker.png" width="270" alt="Material widget's picker highlighted." />

By default, clicking the overall **Material** button applies the chosen material to any **selected** parts. If you prefer a fill/paint workflow instead, toggle on **Material&nbsp;Action&nbsp;as&nbsp;Tool** and then click parts in the 3D viewport to apply the chosen material.

<img src="../assets/studio/general/Home-Tab-Material-Action-As-Tool.png" width="776" alt="Studio's Home tab with the Material Action as Tool selector indicated." />

## Group tools

You can group objects into a [model](../parts/models.md) by selecting them and clicking the **Group** button. This action has a default shortcut of <kbd>Ctrl</kbd><kbd>G</kbd> (Windows) or <kbd>⌘</kbd><kbd>G</kbd> (Mac).

Alternatively, you can group objects into a [folder](../studio/explorer.md#organizing-by-folders) by clicking the small arrow next to the button and selecting **Group as a Folder**. This action has a default shortcut of <kbd>Alt</kbd><kbd>Ctrl</kbd><kbd>G</kbd> (Windows) or <kbd>⌥</kbd><kbd>⌘</kbd><kbd>G</kbd> (Mac).

To **ungroup** an existing model or folder, click the small arrow next to the button and select **Ungroup**. This action has a default shortcut of <kbd>Ctrl</kbd><kbd>U</kbd> (Windows) or <kbd>⌘</kbd><kbd>U</kbd> (Mac).

<img src="../assets/studio/general/Home-Tab-Group-Tools.png" width="776" alt="Group tools indicated in Home tab" />

## Lock tools

You can enable the **Lock Tool** by clicking the small arrow next to the **Lock** button and selecting **Lock&nbsp;Tool**. This action has a default shortcut of <kbd>Alt</kbd><kbd>L</kbd> (Windows) or <kbd>⌥</kbd><kbd>L</kbd> (Mac).

Once enabled, the tool operates as a "key" for both states&nbsp;&mdash; clicking on an unlocked object locks it, while clicking a locked object unlocks it.

To unlock all objects, click the small arrow next to the button and select **Unlock&nbsp;All**.

<img src="../assets/studio/general/Home-Tab-Lock-Tools.png" width="776" alt="Lock tools indicated in Home tab" />

## Anchor toggle

The **Anchor** toggle controls whether the part will be **immovable** by physics. When `Class.BasePart.Anchored|Anchored`, a part will never change position due to gravity, other parts collisions, overlapping other parts, or any other physics-related causes. This action has a default shortcut of <kbd>Alt</kbd><kbd>A</kbd> (Windows) or <kbd>⌥</kbd><kbd>A</kbd> (Mac).

<img src="../assets/studio/general/Home-Tab-Anchor.png" width="776" alt="Anchor toggle indicated in Home tab" />

## Playtest options

There are three common options for playtesting an experience. Clicking the button starts a playtest of the currently selected mode, and clicking the small arrow below the button lets you choose a different mode.

<img src="../assets/studio/general/Home-Tab-Playtest-Options.png" width="760" alt="Playtest options indicated in Home tab" />

<table>
  <thead>
    <tr>
      <th>Mode</th>
	  <th>Shortcut</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>**Play**</td>
	  <td><kbd>F5</kbd></td>
      <td>Starts simulating the experience, inserting your avatar at either a `Class.SpawnLocation` or coordinates of around (0, 100, 0).</td>
    </tr>
    <tr>
      <td>**Play Here**</td>
	  <td></td>
      <td>Starts simulating the experience, inserting your avatar in front of the camera's current position.</td>
    </tr>
	<tr>
      <td>**Run**</td>
	  <td><kbd>F8</kbd></td>
      <td>Starts simulating the experience but does not insert your avatar. The simulation begins at the current camera position and you can navigate around using the Studio camera controls.</td>
    </tr>
  </tbody>
</table>

Once a playtest is running, the following options become available:

<img src="../assets/studio/general/Home-Tab-Playtest-Running-Options.png" width="767" alt="Playtest options indicated in Home tab" />

<table>
<thead>
  <tr>
    <th>Action</th>
    <th>Shortcut</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>**Client/Server**</td>
    <td></td>
    <td>During playtesting in a "play solo" mode (**Play** or **Play Here**), toggles between **client mode** and **server mode**. See [Studio Testing Modes](../studio/testing-modes.md) for details.</td>
  </tr>
  <tr>
    <td>**Stop**</td>
    <td><kbd>Shift</kbd><kbd>F5</kbd></td>
    <td>Stops simulation of the experience and resets all objects and instances to how they were before **Play**, **Play Here**, or **Run** was clicked.</td>
  </tr>
</tbody>
</table>

## Game Settings

The **Game Settings** button, accessible only for a [published](../production/publishing/publish-experiences-and-places.md) experience, lets you update basic information, permissions, security, avatar settings, and more. For more information, see the [Game Settings](../studio/game-settings.md) reference page.

<img src="../assets/studio/general/Home-Tab-Game-Settings.png" width="760" alt="Game Settings button indicated in Home tab" />

## Team Test

During a [collaborative](../projects/collaboration.md) session, clicking **Team Test** starts a playtest with other editors, and **Exit Game** exits out of a current playtest.

<img src="../assets/studio/general/Home-Tab-Team-Test-Options.png" width="714" alt="Team Test option buttons indicated in Home tab" />
