  HARMONY OF DESPAIR RESURRECTED

  > EXTRACT THE ZIP FIRST <
  Right-click the zip > "Extract All...", then open the extracted
  "Harmony of Despair Resurrected" folder and run hod.exe from there.
  Do not run hod.exe from inside the zip window: Windows would run it from a
  temporary folder that gets deleted.

  The game's graphics, sound, music and data are not in this download: they
  are made on your PC, at the first start, from your own copies of the games
  listed in section 2.


CONTENTS
  1. What this is
  2. What you need
  3. First start - setting up the game
  4. New versions
  5. Controls - controller
  6. Controls - keyboard
  7. Display settings
  8. Major features and changes
  9. Folders and files
 10. Troubleshooting
 11. Licences
 12. Changelog


--------------------------------------------------------------------------------
1. WHAT THIS IS
--------------------------------------------------------------------------------
Harmony of Despair was released for the Xbox 360 (and later PS3). This project
turns the Xbox 360 game into a native Windows program:

  - The game's PowerPC program code was translated ("recompiled") into native
    PC code, so it runs directly on Windows - no emulator.
  - Everything the console used to provide was rebuilt for the PC: graphics
    (Direct3D 11), sound and music, controller and keyboard input, saving,
    profiles and networking.
  - Xbox LIVE no longer exists, so everything that depended on it was replaced:
    profiles are local, online play uses its own game list with Host Game /
    Join Game, and leaderboards work locally and online.
  - On top of that, a lot of new content was added: new playable characters,
    new weapons, sub-weapons, spells, glyphs and moves, many brought over from
    other Castlevania games (Portrait of Ruin, Order of Ecclesia, Symphony of
    the Night), balanced to fit Harmony of Despair.

All of the game's DLC (characters, stages and music) is part of the game.


--------------------------------------------------------------------------------
2. WHAT YOU NEED
--------------------------------------------------------------------------------
  - Windows 10 or 11, 64-bit
  - A graphics card that supports DirectX 11
  - About 1.5 GB of free disk space (the game data made at the first start is
    about 1 GB)
  - An Xbox-compatible controller (recommended) or a keyboard

  - Your own copies of these 18 files. The game checks each one (size and
    SHA-256 fingerprint), so they must be these exact versions:

    Xbox 360 - Castlevania: Harmony of Despair, as stored on your console's
    hard drive (title folder 58410A7A):
      1. Castlevania: Harmony of Despair - the game package
         (folder 58410A7A\000D0000)
      2. Harmony of Despair - Title Update 1
         (TU_1C422JQ_000010G000000.00000000000G4)
      3.-8. The six character packs: Julius Belmont, Maria Renard,
         Richter Belmont, Simon Belmont, Yoko Belnades, Getsu Fuma
         (add-on packages, folder 58410A7A\00000002)
      9.-13. The five stage packs: Beauty, Desire, Situation Dire Map Pack;
         Extra Stage: Lord of Flies; Extra Stage: Origins;
         Extra Stage: The Legend of Fuma; Extra Stage: The One Who is Many
      14.-15. Music Pack 1 and Music Pack 2

    Nintendo DS:
      16. Castlevania: Portrait of Ruin - DS ROM (USA), .nds
      17. Castlevania: Order of Ecclesia - DS ROM (USA), .nds

    PlayStation:
      18. SOTN Ultimate v1.4 - PS1 disc image (.bin), "SOTN Ultimate (PS1
          Version) v1.4.bin". SOTN Ultimate is a fan mod of Symphony of the
          Night; you build its disc yourself from three of your own discs
          with "SOTN Ultimate v1.4 Builder.html", included in this download
          (see "Building the SOTN Ultimate disc" below).

  Building the SOTN Ultimate disc
    1. Make disc images of your own copies of these three games. They must be
       unmodified dumps of these exact releases (the builder checks them):
         - Castlevania: Symphony of the Night (USA), PlayStation (SLUS-00067):
           Track 1 as a raw .bin
         - Akumajou Dracula X: Gekka no Yasoukyoku (Japan), Sega Saturn
           (T-9527G): Track 1 as a .bin (not a fan-translated copy)
         - Castlevania: The Dracula X Chronicles (USA), PSP (ULUS-10277):
           the UMD as an .iso (not the European release)
    2. Open "SOTN Ultimate v1.4 Builder.html" (in this game folder) in Chrome,
       Edge or Firefox. It works offline; your discs never leave your PC.
    3. Drop the three disc images onto the page (or choose each one), press
       "Build the disc", then "Save the .bin". It checks that the result is
       exactly the v1.4 disc.
    4. Keep the saved "SOTN Ultimate (PS1 Version) v1.4.bin" with your other
       game files.
    Use this v1.4 builder: newer SOTN Ultimate releases (v1.5 and later)
    build a different disc, which this version of the game does not accept.

  Your files are only read, never changed, copied or sent anywhere. Keep them
  where they are after setup: the game remembers where they are, checks for
  them every time it starts, and builds the new data of each new version from
  them. If you move, rename or delete one, the setup window comes back and asks
  for it again.

Steam Deck / Linux: the Windows version should run through Proton. In Steam
(desktop mode) use "Add a Non-Steam Game" on hod.exe and force a Proton version
in its Properties > Compatibility.


--------------------------------------------------------------------------------
3. FIRST START - SETTING UP THE GAME
--------------------------------------------------------------------------------
 1. Windows may show a blue "Windows protected your PC" screen, because the
    program is not code-signed. Click "More info", then "Run anyway".
    Some antivirus programs may also scan it the first time.

 2. The "your game files" window lists the 18 required files.
      Look in a folder...  pick a folder holding your files (its sub-folders
                           are searched too). Every file found is checked.
      Choose file...       point to one file yourself.
    Each row shows "OK" once its file is checked. "WRONG FILE" means the file
    is not one of the files the game needs, or not the right version of it.
    When all 18 rows are OK, press Start.

 3. The game is then prepared from your files (a few minutes, shown in a
    progress window): the files inside your Xbox 360 packages, the game's own
    changes and additions, and the sounds and pictures taken from your DS and
    PlayStation games. Every file is checked as it is made. If you close the
    window midway, nothing is broken: the next start carries on.

 4. The game starts. It asks you to create a profile: type a name (up to 15
    characters). Your profile holds your saves and settings and loads
    automatically each time. The name is shown in the game and to other
    players online. More profiles can be made later under Profiles & Saves in
    the main menu.

 5. The game creates a "Save Data" folder next to hod.exe for your saves and
    settings, and writes a hod.log file each time it starts (see section 10).
    Later starts go straight into the game.

 6. Online play needs Windows Firewall to let the game receive network
    traffic. The first time you host or join, Windows shows its own "Allow
    access?" box for hod.exe: tick both Private and Public networks, then
    click Allow. If you missed it or clicked Cancel, allow it yourself:
    Windows Security > Firewall & network protection > Allow an app through
    firewall > Change settings > hod.exe, tick Private and Public (if hod.exe
    is not listed, use "Allow another app..." and pick it).


--------------------------------------------------------------------------------
4. NEW VERSIONS
--------------------------------------------------------------------------------
  - New versions are published on the project's GitHub releases page:
      https://github.com/cvhodr2026dev-ai/Harmony-of-Despair-Resurrected/releases
  - To update: close the game, extract the new zip over your game folder
    (replace the files when Windows asks), and start hod.exe. Any game data
    the new version changes is made again from your files at that start.
  - Your saves, profiles and settings (Save Data, hod.ini) are never touched.
  - Online play only matches players on the same version, so keep up to date
    to play with others.


--------------------------------------------------------------------------------
5. CONTROLS - CONTROLLER
--------------------------------------------------------------------------------
Plug in an Xbox-compatible controller before starting the game.

Default layout (as on the Xbox 360):
  Left stick / D-pad    Move, menus
  A                     Jump / OK in menus
  B                     Special (sub-weapon, spell, glyph...) / Back in menus
  X                     Attack (main weapon)
  Y                     Attack (second weapon)
  LB                    Back-dash
  RB, LT, RT            Character actions (they differ per character)
  Start                 Pause / character book
  Back                  Phrases (quick messages in multiplayer)

Change the button layout:
  Help & Options > Settings > Control Settings > Controller Settings

Controller and keyboard settings are separate: changing one never changes the
other.


--------------------------------------------------------------------------------
6. CONTROLS - KEYBOARD
--------------------------------------------------------------------------------
The keyboard always works, even with a controller plugged in.

Default keys:
  Arrow keys            Move, menus
  Z or Space            Jump (A)
  X                     Attack (main weapon)
  V                     Attack (second weapon)
  C                     Special (B)
  A                     Back-dash (LB)
  S                     RB action
  Q                     LT action
  W                     RT action (also opens chests, pulls levers)
  Enter                 Start (pause / book)
  Backspace or Escape   Phrases (Back)
  D                     Zoom (the right stick click: steps through the zoom
                        levels set in Camera Settings)

Change keys:
  Help & Options > Settings > Control Settings > Keyboard Settings
  - Every action can have two keys (Key 1 / Key 2). Left / Right picks the
    column, OK starts "press the new key".
  - Escape keeps the old key, Delete clears it.
  - "Reset to Defaults" puts the layout above back.
  - Changes are saved at once.

Extra actions you can bind (no key by default):
  Special + Up / Special + Down    one key for B + that direction
  Special + Left/Right             one key for B + the direction you face
                                   (side sub-weapons without turning around)
  Menu: OK / Menu: Back            always A / B in menus, whatever your
                                   controller layout is

Shift, Ctrl and Alt can be bound too. The key layout is also saved as a text
file (Save Data\keyboard.ini) if you prefer editing it there.

Other keys:
  Alt + Enter           Switch between a window and borderless full screen
  F9                    Box view on/off: draws the game's own hit and hurt
                        boxes over the picture.
  F11 / F12             Developer keys - do not use. (F12 records a debug
                        capture of the screen and can fill your disk quickly.)


--------------------------------------------------------------------------------
7. DISPLAY SETTINGS
--------------------------------------------------------------------------------
  Help & Options > Settings > Display Settings
  - Video Settings: Windowed, Borderless Full Screen or Full Screen (choose the
    resolution), and Vsync on/off. "Apply" asks "Keep these settings?" - if you
    don't answer within 15 seconds, the old settings come back.
  - Screen, Camera and Window settings are the game's own pages (zoom etc.).
The picture always keeps the game's 16:9 shape; other screen shapes get bars.


--------------------------------------------------------------------------------
8. MAJOR FEATURES AND CHANGES
--------------------------------------------------------------------------------
NEW PLAYABLE CHARACTERS
  Adult Maria (Symphony of the Night)
    A separate character - the original young Maria is still there.
    - X: Owl that flies straight ahead and returns. Y: Kick, which gets a
      longer reach as she powers up. Both grow stronger with her sub-weapons.
    - RB: Genbu, a turtle shell that blocks projectiles while held.
    - Her own sub-weapons: Energy Shot (becomes a comet at its highest level),
      Energy Blast (a piercing beam at its highest level), Byakko, Seiryuu,
      Suzaku, Summon Owl and Summon Water Dragon, plus the hunters' sub-weapons
      (Knife, Axe, Holy Water, Cross, Bible, Ricochet Rock and more).
    - Martial arts: Forward Roll, Somersault, Vertical Kick, Slide Jump,
      Charged Knuckle, Guardian Knuckle (most of them are found in the stages).
  Albus (Order of Ecclesia)
    - His gun on X, with damage that grows with his sub-weapons.
    - Sub-weapons Max Shot, Optical Shot, Quadruple Ignis (a leaping flame
      kick) and Torpor Crystal, all owned from the start; moves cost MP.
  Axe Armor
    - His own axe, Alucard's shields on Y, a slide and dive kick, and his own
      sub-weapons including Cross Axe and Disc Axe.

EXPANDED CHARACTERS
  Jonathan
    - Portrait of Ruin weapons: whips, swords, spears, axes, fists and more,
      found in chests and shops.
    - Portrait of Ruin sub-weapons (Crossbow, Discus, Cream Pie, Aura Blast and
      others) with their original graphics and behaviour.
  Charlotte
    - Portrait of Ruin spells: Gale Force, Rock Riot, Spirit of Light, Dark
      Rift, Tempest, Stone Circle, Explosion, Chain Lightning, Summon Medusa,
      Hex, Salamander, Cocytus, Thor's Bellow, Summon Crow, Summon Ghost,
      Summon Frog, Speed Up and Speed Up +1.
    - Found in stage chests, or learned from enemies like her other spells.
      The damage spells found in chests level up by using them.
    - Her spells pass through thin platforms but not walls or floors.
    - She can now wear Master Rings.
  Shanoa
    - Order of Ecclesia weapon glyphs and glyph unions: a weapon glyph combined
      with a magic glyph becomes its own weapon (for example Confodere Ignis).
    - Arcus, Ascia and Culter as B-slot glyphs (sold in the shop), Scutum
      blocks projectiles.
  Alucard
    - Can use the hunters' sub-weapons (as in Symphony of the Night).
    - Symphony of the Night's familiars (Bat, Ghost, Faerie, Demon, Nose
      Demon, Sword, Half-Faerie), worn in his familiar slot; they gain rank
      as they are used.

GAMEPLAY
  - Weapons that grow with sub-weapons or spells (Vampire Killer, Book of
    Binding, and the new characters' weapons) count every sub-weapon / spell
    the character can use, including the new ones.
  - New items placed in stage chests, boss chests, enemy drops and the shop.

MENUS AND SYSTEM
  - Profiles & Saves screen: several local profiles, each with its own saves.
  - Settings menu: Control Settings (controller / keyboard) and Display
    Settings (video / screen / camera / window).
  - Full keyboard support with its own settings page.
  - Video settings: windowed / borderless / full screen, resolution, vsync.
  - The Martial Arts page scrolls when a character has more than five.
  - Multiplayer (early - expect rough edges): Host Game (co-op or survival,
    max players, difficulty, public or private, game name, optional password)
    and Join Game (a list of open public games with region and ping, or join
    by address). Players' addresses are never shown in the list. Players who
    cannot connect directly are joined through a relay automatically.
  - Leaderboards: Online, My Score and Local.
  - Xbox LIVE items removed or replaced.
  - Faster loading of stage graphics (stage art is prepared in the background,
    and the game remembers it for next time), shader cache, smoother menus.


--------------------------------------------------------------------------------
9. FOLDERS AND FILES
--------------------------------------------------------------------------------
  hod.exe                 Start the game here.
  README.txt              This file.
  SOTN Ultimate v1.4 Builder.html
                          Builds the SOTN Ultimate disc from your own discs
                          (section 2). Not needed once you have the disc.
  Game Data\Engine        The game program and its libraries, and the recipe
                          for making the game data from your files.
  Game Data\Original, Fixes, Characters, Stages, Items, Sound, Custom Sounds
                          Made at the first start from your files (section 3).
  Save Data               Your profiles, saves and settings (made on first
                          start; never touched by new versions).
  Save Data\sources.ini   Where your 18 game files are. Delete it to choose
                          them again.
  Save Data\built.txt     Which game data has been made. Delete it to have
                          everything made again at the next start.
  hod.ini                 Optional extra settings (yours).
  hod.log                 Written each start; useful for bug reports.

Please don't move, rename or edit files inside Game Data: a damaged file is
not noticed until something goes wrong. To repair the game data, delete
Save Data\built.txt and start the game.


--------------------------------------------------------------------------------
10. TROUBLESHOOTING
--------------------------------------------------------------------------------
  - Something went wrong? Send hod.log (next to hod.exe) along with what you
    were doing. Note: it contains your Windows folder path, which can include
    your Windows user name.
  - "WRONG FILE" during setup: the file is a different version (another
    region, a modified or incomplete copy). Only the exact versions listed in
    section 2 work. For SOTN Ultimate, build the disc with the included v1.4
    builder, not a newer release.
  - "Could not make ... The file may have changed since it was checked": one
    of your files was moved, changed or is on a drive that is not connected.
    Delete Save Data\sources.ini and start the game to choose the files again.
  - The game won't write into its folder: don't keep it in Program Files
    (Windows blocks writing there); Desktop or Documents is fine.
  - Can't host or join online: check the firewall permission (section 3,
    step 6).


--------------------------------------------------------------------------------
11. LICENCES
--------------------------------------------------------------------------------
  - Castlevania, Harmony of Despair, Symphony of the Night, Portrait of Ruin
    and Order of Ecclesia are Konami's. This is an unofficial fan project, not
    affiliated with or endorsed by Konami. The game data is made from your own
    copies of the games.
  - FFmpeg (avcodec, avutil, swresample in Game Data\Engine) is used under the
    GNU LGPL version 3; see Game Data\Engine\FFMPEG-LICENSE.txt. Its source
    code is available from https://ffmpeg.org.
  - libmspack (built into hod.exe, used to unpack Xbox 360 files) is used under
    the GNU LGPL 2.1; its source code is available from
    https://www.cabextract.org.uk/libmspack/.
  - SOTN Ultimate v1.4 Builder.html is the SOTN Ultimate (PS1 Version)
    project's builder page, included unchanged. It is licensed under the GNU
    AGPL version 3 or later; its source code, licence and credits are at
    https://github.com/renanbianchi/sotn-ultimate (release v1.4).
  - XenonRecomp (MIT licence; its XEX code comes from the Xenia project, BSD
    licence) and tiny-AES-c (public domain) are built into hod.exe to read the
    Xbox 360 files.
