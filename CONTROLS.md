# Skald controls

Use this guide to learn the supplied keyboard, mouse and Xbox controller preset, including its changed combat controls, menu combinations, equipment wheels and mod shortcuts.

**LB/RB** are the left/right bumpers, **LT/RT** the triggers, and **L3/R3** mean clicking the left/right stick. **View** is the small button with overlapping rectangles; **Menu** is the small button with three horizontal lines. A **+** means hold the first button while pressing the second. **Unassigned** means the supplied configuration does not assign a shortcut.

The tables describe the supplied controls. Entries marked **mod default** come from that mod's default settings; **saved binding** means Skald supplies a saved setting. A character's Mod Configuration settings can change these. A saved controller binding does not establish whether the mod also accepts its keyboard default at the same time.

## Movement and combat

| Action | Keyboard / mouse | Xbox controller |
|---|---|---|
| Move | W / A / S / D | Left stick |
| Look | Mouse | Right stick |
| Activate / talk / use | E | A |
| Jump | Space | Y |
| Sprint | Left Alt | L3 |
| Sneak | Left Ctrl | B |
| Walk / run modifier | Left Shift | Movement depends on stick position |
| Toggle always run | Caps Lock | Unassigned |
| Auto-move | C | Unassigned |
| Right-hand attack / block action | Left mouse button | RT |
| Left-hand attack / block action | Right mouse button | LT |
| Draw / sheath | R | **LB + Y** |
| Shout / use selected power | Z | **LB + A** |
| Change first / third person | F | R3; see lock-on below |
| Change camera distance | Mouse wheel | Unassigned |

The camera is not inverted and always run is initially enabled. Attack and block behavior depends on the equipped weapons or shield. Follow the combat system's current action and eligibility prompts.

### Added combat controls

| Feature | Supplied binding | What to know |
|---|---|---|
| TK Dodge | **X** — saved binding | The preset selects step dodge. The mod's keyboard default is Left Alt; check its MCM before relying on a simultaneous keyboard fallback. |
| One Click Power Attack | **RB** — saved binding | Its keyboard default is right mouse button. Check the current OCPA MCM binding for keyboard use. |
| OCPA dual attack | **LB + RB** — saved binding | The keyboard default is Left Shift + right mouse button; check MCM for its current use. |
| Valhalla execution | **LB** — saved binding | Applies when an execution is eligible. A separate keyboard execution key is unassigned in the default settings. |
| Valhalla timed block | Normal block input | Timing and the equipped setup govern the block; no alternate block key is assigned. |
| True Directional Movement lock-on | **Middle mouse button**; **tap R3** — mod defaults | On controller, hold R3 longer than a quarter second to change perspective. F remains the keyboard perspective action. |
| Switch locked target | Mouse movement / wheel or right stick — mod defaults | Separate switch-left and switch-right shortcuts are unassigned. |

### Camera shortcuts

SmoothCam assigns **C** to swap shoulders and **Right Alt** to its custom offset shortcut. C also appears in the base auto-move mapping; which action applies depends on context. SmoothCam's separate mod toggle, apply-Z-offset shortcut and next-preset shortcut are unassigned.

## Menus and quick access

| Action | Keyboard | Xbox controller |
|---|---|---|
| Character menu | Tab | **View** |
| Journal | J | **Menu** |
| Pause / System | Esc | Open the journal and use its System page |
| Favorites | Q | **D-pad Up** |
| Inventory | I | **A + D-pad Right** |
| Magic | P | **A + D-pad Left** |
| Map | M | **A + D-pad Down** |
| Skills directly | Slash (/) | Unassigned |
| Wait | T | **LB + View** |
| Quicksave | F5 | **LB + Menu** |
| Quickload | F9 | Unassigned |

In most menus, **E / A** accepts and **Tab or Esc / B** cancels. Move through options with **WASD**, the controller's **D-pad** or **left stick**; use the mouse where a cursor is available. Favorites can also close with Q. Menu prompts explain context-specific X and Y actions.

### Favorite item shortcuts

Assign a favorite to a numbered shortcut in the Favorites menu.

| Slot | Keyboard alternatives | Xbox controller |
|---|---|---|
| 1 | 1 or Numpad 1 | D-pad Left |
| 2 | 2 or Numpad 2 | D-pad Down |
| 3 | 3 or Numpad 3 | D-pad Right |
| 4 | 4 or Numpad 4 | Unassigned |
| 5 | 5 or Numpad 5 | LB + D-pad Left |
| 6 | 6 or Numpad 6 | LB + D-pad Down |
| 7 | 7 or Numpad 7 | LB + D-pad Right |
| 8 | 8 or Numpad 8 | Unassigned |

These numbered item shortcuts are separate from SkyUI favorite groups and Wheeler wheels.

## Wheeler equipment wheels

| Action | Keyboard / mouse | Xbox controller |
|---|---|---|
| Open / toggle in normal play | **F6** | **LB + B** |
| Open editing from Inventory / Magic | **F6** | **Menu** |
| Primary action | Left mouse button | RB |
| Secondary action | Right mouse button | LB |
| Next wheel | E | RT |
| Previous wheel | Q | Unassigned |
| Next item | Mouse wheel down | D-pad Right |
| Previous item | Mouse wheel up | D-pad Left |
| Close / exit | Tab or Esc; F6 toggles the wheel | B |

Choose an entry with the wheel cursor, then use its primary or secondary action. The item determines whether that action equips, consumes or uses it. The preset does not automatically use an entry when you release the opening buttons, and it does not automatically close the wheel after use. Opening and editing from Favorites are disabled in this preset.

### Editing a wheel

Open Wheeler while browsing Inventory or Magic to edit it. These editing shortcuts are assigned to keyboard; controller shortcuts for adding or rearranging entries are unassigned.

| Edit action | Keyboard |
|---|---|
| Add a wheel | N |
| Add an empty entry | M |
| Move an entry forward / back | Up / Down arrow |
| Move a wheel forward / back | Right / Left arrow |

The edit-hint toggle is unassigned. The separate Ammo Wheel has no opening shortcut assigned. Wheeler stores its layout with the character's SKSE save data, so keep the matching save files together.

## Inventory, looting and interaction

### SkyUI menu shortcuts — mod defaults

| Action | Keyboard | Xbox controller |
|---|---|---|
| Search | Space | Unassigned |
| Switch tab | Left Alt | View |
| Change equip mode | Left Shift | Unassigned |
| Previous / next column | Unassigned | LB / RB |
| Change sort order | Unassigned | L3 |
| Favorite-group add | F | Unassigned |
| Use favorite group | R | Unassigned |
| Set favorite icon | Left Alt | Unassigned |
| Favorite equip-state action | T | Unassigned |
| Toggle favorite focus | Space | Unassigned |
| Favorite groups 1–4 | F1–F4 | Unassigned |
| Favorite groups 5–8 | Unassigned | Unassigned |

Inside item menus, use the normal left/right attack inputs for the corresponding hand. **C / R3** zooms an item; the **right stick** rotates it. **T / LB + A** performs the inventory charge-item action. Follow the displayed X/Y prompts for other item actions.

### QuickLoot — mod defaults

| Action | Keyboard | Xbox controller |
|---|---|---|
| Take selected item | E | A |
| Take all | R | X |
| Open transfer menu | Q | View |

QuickLoot's separate enable and disable shortcuts are unassigned.

**Use or Take** assigns **Left Shift + Activate** for its alternative interaction; holding Left Shift for about 0.7 seconds selects its secondary behavior. **Dynamic Activation Key** also assigns **Left Shift**. **Better Third Person Selection** defaults to **Left Shift + mouse wheel up/down** to cycle selectable objects. Left Shift is also the base walk/run modifier, so these actions depend on what you are interacting with. No controller alternative is assigned by the inspected Use or Take configuration.

## Maps, books and lockpicking

| Context / action | Keyboard / mouse | Xbox controller |
|---|---|---|
| Map cursor | Mouse | Left stick |
| Map camera | Hold right mouse button for look mode | Right stick |
| Map zoom | Mouse wheel up / down | RT / LT |
| Centre map on player | E | Y |
| Player-marker shortcut | P | Use A at the cursor and follow its prompt |
| Local map | L | X |
| Journal from map | J | D-pad Left |
| Previous book page | Left arrow or A; left mouse button or wheel down | D-pad Left |
| Next book page | Right arrow or D; right mouse button or wheel up | D-pad Right |
| Angle lockpick | Mouse | Left stick |
| Turn lock | W / A / S / D | Right stick |
| Leave lockpicking | Tab or Esc | B |

The journal uses **LT / RT** to switch tabs. Its contextual X action is **X or M** on keyboard, and its Y action is **T**; follow the current journal prompt. The controller's left stick rotates the skills view. Menus with a separate cursor can use the right stick and A.

## Other enabled mod shortcuts

| Feature | Supplied shortcut | Notes |
|---|---|---|
| dMenu | **F7** | Mod menu shortcut. |
| Dragonborn's Bestiary | **K** | Also has a System menu entry. |
| OBody preset menu | **O** | Initial script binding; a character's MCM can change it. |
| Open Animation Replacer menu | **Left Shift + O** | Shares O with the initial OBody key; use the required modifier. |
| Immersive Equipment Displays menu | **Left Ctrl + F8** | Equipment-display configuration. |
| SSE Display Tweaks overlay | **Left Shift + Insert** | Display overlay shortcut. |
| Skyrim Unbound starting menu | **Enter** | Used at the new-character starting stage. |
| Photo Mode | **Backslash key** — saved binding | Opening from controller is unassigned. |
| Screenshot | **Print Screen** | Base screenshot action. |
| Multiple-screenshot mapping | **Ctrl + Print Screen** | A separate base mapping; use ordinary Print Screen for a single screenshot. |
| Console | **Grave / tilde key** | Advanced console access; not required for normal startup or play. |

### Inside Photo Mode — mod defaults

| Action | Keyboard | Xbox controller |
|---|---|---|
| Next / previous tab | E / Q | RT / LT |
| Take photo | Print Screen | View |
| Show / hide menus | T | X |
| Reset | R | Y |
| Freeze time | F | Unassigned |

These Photo Mode actions apply while Photo Mode is open, rather than to normal gameplay.

## Optional and unassigned controls

**Nether's Follower Framework** supplies no dedicated hotkeys for attack, retreat, calming, following, teleporting, horse actions, trading, selling, gear, chest placement, follower history, favourites, cloning or auto-looting. Use its menus and assign any desired shortcuts in its MCM.

**MoreHUD** and **VioLens' ranged toggle** have no separate hotkey assigned. **TrueHUD** does not supply a player action key in this preset. **Precision's** debug toggle and settings reload are unassigned.

**SkyParkour** selects preset 0, whose key is not established in this guide. Check its MCM for the current preset's action before using parkour. **Paraglider** actions become relevant after unlocking it; use its instructions and prompts. **Bow Rapid Combo** has no separate hotkey established by the supplied control settings. These features are not assigned guessed keyboard or controller shortcuts here.

**Community Shaders** overlay shortcuts are not named in this guide because their stored codes have not been translated into a confirmed key scheme. Consult its settings for the current overlay controls.

To personalise a binding, open **System > Mod Configuration**, choose the relevant mod and read its current control setting. Make deliberate changes so that a new shortcut does not conflict with an action you use. This guide describes the supplied preset; it does not replace your character's saved settings.
