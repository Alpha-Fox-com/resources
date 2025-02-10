## Key Definitions

- ASN Hub: The main server/service that lists and connects all Stargates. Blocking it can disable your gate.
- GDO (Gate Dialing Object): A HUD or handheld device allowing users to dial and interact with Stargates.
- RP (Role Play) Gate: A Stargate used primarily for thematic or storyline scenarios (for example, "space gates" or
  fantasy realms).
- Random Dialing: A feature enabling the gate to establish random connections across the network.

## General Enforcement Rules

These rules apply to all Stargates, whether they allow random dialing or manual dialing.

### ASN Hub Access

Blocking the ASN Hub or preventing your gate from connecting to it will result in gate deactivation until fixed.

### Avatar Attachments

Stargates should not be worn or attached to avatars; they must be placed in-world.

## Public Access Stargates

These are for Stargates that meet the following criteria:

* Are not set to offline.
* Do not have a shield raised.
* Configured to exist in the Random dialing pool (enabled by default, you can disable it in Settings -> Random).

### Quick Refrence Checklist

- Use: It is possible to use the Stargate to leave.
- Security: No automatic eject/ban systems within gate range.
- Scripting: Public scripts are enabled close to the the gate.
- Visibility: Gate is easily spotted from the Telehub or arrival point.
- Land Access: Parcel is open to the public (not group-only or private).
- Aerial Placement: If gate is above ground, a safe landing mechanism is present.

### Land access

Rule:
Stargates must be placed on land that is publicly accessible (i.e., not group-only or private).

Exception:
Stargates can be placed on private no access regions that have the experience
key "<a href="secondlife:///app/experience/d14a12a0-b48b-11e5-bf4d-fa4c4c646b81/profile">Matter stream</a>" configured
as a "Key Experience" in the Region/Estate panel.

Reason:
Ensures anyone can visit and use the gate, regardless of group affiliation or land permissions.

Implementation Tips:

- Check your parcel's "About Land" -> "Access" settings to confirm public entry is allowed.
- Check "Region/Estate" -> "Experiences" options to confirm that "Matter stream" is configured if "Allow only residents
  and groups listed in access tab" is selected in te "Estate tab".

### Aerial placement

Rule:
Do not place Stargates in mid-air unless there is a clear, safe mechanism for travelers to land or disembark.

Exception:
[RP] "Space Gates" with "power pods" or other thematic support.

Implementation Tips:

- Provide a platform or teleporter if your gate is above ground level.
- Consider adding "Space Gate" or "[RP]" in the gate name or alias for easy identification.
- For space gates, you can place a 10x10x1 meter invisible platform right under where the event horizon should be to
  catch visitors.

### Visbility & Teleportation

Rule:
The Stargate should be visible from the region's Telehub or primary landing point.

Reason:
Prevents confusion and makes it easy for new arrivals to locate the gate.

Implementation Tips:

- Don't use teleport routing on the parcel that the Stargate sits.
- If you use teleport rourting on the parcel that the Stargate sits on, make sure the user has direct line of sight to
  it.

### Security Systems

Rule:
Avoid placing Stargates within areas that have automatic security or ban systems that teleport or eject users on entry.

Reason:
Users risk being expelled immediately upon arrival, rendering the gate unusable.

Implementation Tips:

- Deactivate security orbs in the gate's vicinity.
- Move Stargate or 'secured' zone away from affecting each other.

### Public Script Usage

Rule:
Stargates must be placed on land where public scripts are enabled.

Reason:
Prevents interference with GDOs (Gate Dialing Objects) and other scripted interactions.

Implementation Tips:

- In "About Land" -> "Options," confirm "Scripts allowed" is checked for public users.
- If you can't enable public scripts for the entire region, consider isolating the gate on a dedicated parcel where
  scripts are permitted.

### Gate Dialing Puzzles

Rule:
Dialing puzzles or unique interactive mechanisms are allowed but must not be overly hidden or complicated.

Reason:
Encourages Stargate play but keeps the gate accessible to casual visitors.

Implementation Tips:

- Provide in-world hints why a Stargate may not behave as intended.

### Exceptions for Roleplay

If you are using a gate in a roleplay setting, clearly mark it with "[RP]" in the gate's name or alias. You may use
special rules. Just be sure to communicate these differences to visitors through the gate name.

## Montioring & Reporting

- You can report a gate directly by clicking on it.
- You can find the gate using the [ASN Database ](http://www.alpha-fox.com/asn/db/) and report it through that
  interface.
- You can view tickets against your gates or tickets you've opened against other gates via
  the [SSoP support portal](http://www.alpha-fox.com/support/ssop/)
