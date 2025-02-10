## 1.1.3

- Fixed an "extreme load bug" on our servers.

## 1.1.2

- You no longer get erroneous "status|offline" when API commands from far away are given.
- Fixed default shields for forerunner, pegasus, and tollan.
- You now get a "chevron 1 encoded" ... damn if() statements.

## 1.1.1

- Fixed shield status so that it is updated server side as well as gate side.
- Removed versioning from the gate names -- makes updates easier and less confusing when your gate says "Alteran
  Stargate 1.0: Your Stargate version is 1.1"

## 1.1

- **Added in support for touch distance limitation. Currently you must be within 20 meters to use your gate menu.**
- **Added in support for region agent count to the probe return.**
- **Added support for gates on access list / group limited parcels to not show in random.**
- Fixed the event horizon (rewrite by Jandav Auer) to properly detect collisions / death.
- Fixed control units in Accessories package.
- Added an object that will allow people to put "Gate Distributors" on their property.
- Rewrote parser.lsl and interface.lsl to combine the two and reduce script time.
- Rewrote connection.lsl and core.lsl to combine the two to reduce script time
- The gate will no longer revert to "online" after an unintentional reset.
- Gate errors will no longer be spammed. They are set to only show once.

## 1.0

*Same as the release candidate before, compiled to the Mono runtime engine.*

## Release Candidate 4 Revision 2

- Fixed a bug in which you would map to xx|xx coordinates.
- Fixed a bug where the Event Horizon would not kill you without getting a destination first.
- Fixed a bug in 404 error handling.

## Release Candidate 4

**Please note that this should be the last RC gate before the big 1.0 release. Please report all bugs found to the
forums for final bug fix.**

- *Finally* fixed quick wormholes.
- Made adjustments to the kawoosh that will now cause death. You can now re-enable Death.
- Changed the way incoming connections are handled in order to send a more reliable destination. You should not get
  wormholes with "no destination" anymore.
- Made the shield hollow larger for Wolfie because he whined for it.
- Fixed the bug where cut / close wormhole would get responses on pegasus/forerunner/tollan gates.

## Release Candidate 3

**This code release marked the hold of support for the Open Stargate Network.**

- Fixed incoming wormhole handling to prevent "quick wormholes"
- Made some adjustments to the kawoosh that should prevent fake kills.
- Added a handler to handle 499 and 500 HTTP errors.
- Added the ability to switch the gates via the script to dev / rel codebases.
- Added the addslashes() command to the backend to prevent any MySQL errors.
- Removed the log_data function from the backend to increase speeds.
- Optimized some PHP code to increase speeds.
- Fixed typos in various backend messages.
- Added 'rot' to the end of the dial_successful API response.

## Release Candidate 2

- Updated failsafe time to account for slower sims booting.
- Changed boot message to be smaller and more to-the-point
- (somehow) fixed the Event Horizon to kill people on Kawoosh.
- Fixed the DHDs to not repeat symbols when getting an incoming during dial-out.
- Fixed the "Rate" function to give a proper response
- Fixed the "quick" wormholes. A bug in the registration was causing the first wormhole after registration to be bad.

## Release Candidate 1

**This code release marked the end of support for the Cleary Stargate Network.**
*The changelog for this gate version was lost, but preparations were made for the RC1 release.*

## 0.10.0 Beta

- **Added glow to the chevrons in order to give a better effect (all models).**
- **Added light emit to event horizon.**
- **New shield / iris impact sounds.**
- **Glow control on the built-in shield.**
- Changed the behaviour on HTTP errors -- no longer plays any sounds or effects but only outputs errors on the API.
- Added status definitions to the gate manual.
- Fixed messages to death including and extra "by".
- Fixed the AFVI server communication to not crash servers.
- Fixed gate crash issue - had to do with improper handling of responses in core.lsl.
- Fixed the biggest bug in Alteran / Arcturus History. The Milkyway inner ring now stops on the glyph in *both*
  directions!
- Changed core aspects of the Stargate in order to clean up code and make the overall changes faster. Also introduces
  the "buffer reset" feature.
- Shield system is cleaner -- has the ability to be controlled via the "core" script instead of just switching script
  states on / off.
- Event horizon has been rewritten to cope with the changes in Havok 4, as well as fix some death issues.

## 0.9.12 Beta

- Fixed the gate radio.

## 0.9.11 Beta

- Fixed the gate to send 'idle' at the end of wormholes.
- Fixed the updater to not error when trying to do a "script" update.
- Fixed the updater to allow Zachary to update gates.

## 0.9.10 Beta

- **Added the link to the Stargate Standards of Placement page upon registration.**
- **Added "Memory" button to the menu to report free memory in every script.**
- **Added the Death API for people to adapt products to use Death.**
- Changed the code to spread type.core into type.core and type.api.
- Improved the menu interface by moving commands into "Controls" submenu.
- Fixed *target wormhole collision* to have the type in the end of the response.
- Improved Death by adding more checks and making the system itself faster. The Death object itself can now turn on /
  off.
- The Stargate no longer mis-kills people. The checks in the event horizon itself are much smarter.
- The checksum checks have been improved. The frontend will be changed to allow for variation.

## 0.9.9 Beta

- **Added the new-style SGC-IDs. Now uses a friendlier system without symbols.**
- **First introduction of the Update Orb, which allows for various methods of updating your Stargate.**
- Fixed a text blemish on the output for "Statistics"
- Fixed a text blemish on the output for "Help"
- Opengate / Cleary dialing now gives a map upon dialing.
- Dials via glyph addresses now works properly. Guess what, it was only a difference between **!=** and **==**.
- Opengate / Cleary Stargates can now be dialed via a "random" command.
- Gate radio now works properly. magic_quotes_gpc can shove it.
- Incoming travelers are no longer murdered by Death.
- SCU properly updated to 2.0 -- lots of bug fixes.

## 0.9.8 Beta

- Removed all traces of the built-in IDC system. This includes all the API commands, /stargate commands, etc.
- Removed all traces of the access_list system as most gate functions are controllable via the API (and people can make
  objects to do that themselves).
- Removed /fast and /df due to stress on the server. These dial options are still available on the API using the *ring*
  parameter of *2*.
- All chat starting with / is sent to the server. This allows us to add / remove commands to the gate easily (besides
  /stargate commands).

## 0.9.7 Beta

- **Introduced the *forward addresses* for the Stargate system on an admin-assign only basis. Read the user guide for
  more details.**
- **Added the menu button *Output*. It allows you to toggle whether the gate outputs what it is currently doing on
  channel 0.**
- **Added new API response, *prompt|*. This allows an individual to relay all verbal chat the Stargate sends out (
  besides menu commands) through the API instead of channel 0 (public output).**
- **Added new API command, *public listen|<0/1>*. This allows you to set public listen (listening for commands on
  channel-0) on or off.**
- **Added new API command, *public output|<0/1>*. This allows you to set public output (outputting normal gate verbal
  prompts on channel-0) on or off.**
- **Added new API command *random list|<0/1>*. This allows you to set whether your gate will appear in a random dial or
  not.**
- **Added *Cut Power* to the active Stargate menu. Thought it would be cool, honestly.**
- **Added *top gates|* API response. Contains a list of currently top gate names.**
- **Added *gate statistics|||* API response. Contains basic statistics about your Stargate's activity.**
- **Added *gate statistics* API response. Allows you to get basic statistics about your Stargate's activity.**
- Removed *Bug Report* button from the menu. People wishing to submit bug reports can use the forums
  at [http://www.alpha-fox.com/forums/](http://www.alpha-fox.com/forums/).
- Updated *Stargate Control Units* to *1.3*. Added the ability to change ring style to the *milkyway* version, as well
  as adding the ability to turn on / off stargate *verbal output*. The unit can also turn off the internal Stargate
  listen and route all listens through the unit itself (useful for large gate rooms).
- Updated the "Top Gates" list to reflect whether the Stargate exists anymore or not.
- Interference effect now plays when dialing your own address on your Stargate.
- Stargates now are smarter on when to output on the public channel (say, if using an API command) and when to not
  output on the public API channel.
- Gate shield (rezzed) is now modifiable.
- Integrated checks to make sure the communications parser does not stack-heap.
- Removed the verbal commands for IDC accepted / denied. GDOs based on the API can send this, and if accepted the gate
  signals you with "Target shield has been lowered. You may proceed". This was to eliminate double messages upon
  lowering a shield.
- Fixed wormhole collisions. Now detects the key and name, and not everybody is an *object*.

## 0.9.6(2) Beta

- **Added in *target shield raised* API response. Check the user guide.**
- **Added in *target shield lowered* API response. Check the user guide.**
- **Added in *destination||* API response. Check the user guide.**
- Changed the *Subnova* button in the menu to route to the Pegasus Stargate. The gates are now located in the retail
  center.

## 0.9.6(1) Beta

- **Added `gate_key` (SGC-style planet naming) onto the end of the *lookup* API response.**
- **Added `gate_key` (SGC-style planet naming) onto the end of the *directdial* API response.**
- **Added `gate_key` (SGC-style planet naming) onto the end of the *incoming wormhole* API response.**
- **Added `gate_key` (SGC-style planet naming) onto the end of the *dial verification* API response.**

## 0.9.6 Beta

- Upgraded the Alteran Address Display to *1.4*. The 7 glyph addresses were displaying on opposite glyph sets.
- Upgraded both of the Stargate Control Units to *1.2*. They now use region say to broadcast to your Stargate from
  anywhere in the region. I also put in a fix to prevent the mixup of name | region values in the address book.
- Milkyway and Pegasus DHD upgraded to *4.04* - Integrated llRegionSay to allow broadcasting to your Stargate from
  anywhere in the region.
- Tollan and Forerunner DHD upgraded to *1.04* - Integrated llRegionSay to allow broadcasting to your Stargate from
  anywhere in the region.
- Upgraded Map System to *1.2*. Fixed an issue where it was using the wrong variable to load the URL, causing script
  errors.
- Kawoosh no longer forms when the shield is raised.
- IDC access list now checks from the correct Stargate.
- Pegasus gate dialing sequence corrected. Glyphs now stay under the chevrons when dialing.

## 0.9.5 Beta

- Fixed the API channels in the Pegasus Stargate.

## 0.9.4 Beta

- **You can now choose between "Explosion" and "Beam Out" effects for deleting the Stargate *(menu-only)*.**
- **Added */fast* and *"/df* for the forced wormhole opening. This will now work on regular dials if wanted. For the
  API, just set the spin value to '2'**
- **Added the API command "ring speed|". The default ring speed is 80. It only works for one dial or until the Stargate
  resets. You must set it for *each* dial.**
- Death works again. A mistake in coding the Kawoosh caused agent checks to fail. (Omnifox Xi)
- Probe is limited to outgoing wormholes only. (Vala Vella)
- Event Horizon monitor scripts more refined. Hopefully this should fix the randomly-disappearing event horizon. (
  Omnifox Xi)
- You can no longer input glyphs into the gate when the gate is not "idle" or "dialing". (Jeffej5005 Lewis)
- Updated the Alteran Address Display to *1.3*. Fixed a mistake where incoming wormholes would not display the address
  properly. (Lex Mars)
- Stargate crash error prevented and repaired. Possible causes:
    - Blank HTTP requests which could result from HTTP timeouts were not causing the gate to reset.
    - The queue script was getting confused when an incoming wormhole interrupted an outgoing causing the gate to crash.
- Milkyway and Pegasus DHD upgraded to *4.03* - Integrated 60 second timeout on each button press. Also owner locks so
  it doesn't pick up commands from other people's stargates. (Trance Sodwind)
- Tollan and Forerunner DHD upgraded to *1.03* - Integrated 60 second timeout on each button press. Also owner locks so
  it doesn't pick up commands from other people's stargates. (Trance Sodwind)
- *dd:* dialing support removed. It caused problems for those with Cleary gates near the Alteran gate. (Cheshyr
  Pontchartrain)
- Fixed the region dial priorities. Now does priority dialing by the *network of your gate*, the *opposite network* from
  that, *opengate*, and finally *cleary*. (Lex Mars)

## 0.9.3 Beta

- Upgraded Alteran Address Display to *1.2*. Fixed a bug when setting the network and when loading the gate's address
  when idle.
- Upgraded AF-TP for support with sims in the spaces in the names.
- Fixed backend entering blank collisions in the database.
- Fixed a bug where you could send /stargate test incoming / outgoing when a gate is already open.
- Cleaned up some messy transitions between dialing and idle.

## 0.9.2 Beta

*The changelog for this version was lost. Sorry for the inconsistency.*

## 0.9.1 Beta

- **Added in "Map System." Rez it near your gate and llLoadURL boxes pop up to teleport your avatar upon clicking "Go to
  URL"**
- Repaired the "name" menu command. (Wolfie Waves)
- Changing to "shield" mode now works. (Kegan Loon)
- Changed *lookup* API response to *"dial lookup"* and *"search lookup"*
- Event horizon now autodestructs upon not finding the Stargate. (Jeri Carter)
- Built-in shield now turns fullbright upon activation. (Zachary Carter)
- Pegasus gate has glow on the glyphs. (Zachary Carter)
- Subnova button now returns a normal dial API response (Lex Mars)

## 0.9.0 Beta

- **Includes the *Tollan Stargate*. A low-prim solution to the Milkyway network.**
- **Includes the *Forerunner Stargate*. A low-prim solution to the Pegasus network.** (*Note: This is a concept
  Stargate, as there were no "custom" Stargate seen in the Pegasus galaxy yet.*)
- **Included the *Alteran Address Display*. Instructions how to use it can be found in the user guide.**
- **The *Stargate Control Units* are included in the gate package. They are simple dialing devices using a stored menu
  of preset addresses and basic Stargate controls. "The Poor Man's DHD"**
- **Included the Beta version of the URL-based *Map System.***
