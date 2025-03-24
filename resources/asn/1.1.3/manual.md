![Alteran Stargate Network Logo](https://images.alpha-fox.com/logo/asn_logo_small.jpg "Alteran Stargate Network logo{float=right}")

## ToC

**Alteran Stargate**  
*1.1.3*

*In order to receive the latest updates and other important information, be sure that you join
the **Alteran Stargate Network** group.
You can also access the forums
at [https://www.alpha-fox.com/community/](https://www.alpha-fox.com/community/).*

## Section 1 - Setting up your Stargate

### 1.1 - Basic Setup

When you first rez your Stargate, it will provide you with a username and password.
Please write that down, because it
is your ticket to both the forums and the [online interface](#section-5online-interface).

Once your Stargate is rezzed, you simply have to move your Stargate into position.
See *Section 1.3* for tips on how to
position your Stargate.
If you wish to use a [Dial Home Device](#32dial-home-devices) with your Stargate, you may rez
one from the folder where you received the Stargate and this user guide.
A *Dial Home Device* is a keypad that allows
you to "dial up" glyphs of a target Stargate.
Once you push the glyphs and then the center button, it will attempt to
lock and either fail or open up to your destination.

**NOTE:** If you are not the "primary" or first Stargate in your region, you will only be able to contact your Stargate
via the *name* or *alias*.
See [Section 1.2](#12customizing-your-stargate) for more details on renaming your
Stargate, or [Section 2.5.2](#252addressing-system) for more details on how the addressing system works.

### 1.2 - Customizing your Stargate

Once you set up your Stargate, you are ready to go.
However, if you want to be able to be contacted using a special word
or want to display a different name for your Stargate on the webpage, you can do this easily in-world.
The in-world
interface is not the only method** of customizing your Stargate; see [Section 5](#section-5online-interface) for more
details on customizing your Stargate via the online interface.

There are currently two ways to customize your Stargate via the in-world interface:

1. The menu you obtain by touching the Stargate
2. The [Stargate API](#42outgoing-api)

This section of the guide details the menu-method of customizing your Stargate.

When you click the Stargate, you will obtain a menu.
You should see a menu with buttons in the top-right corner of your
screen.
All of the customizations you are going to want to do are in the **Settings** portion of the menu, so click that
button.
On the next menu that pops up, you have several choices:

- **Random**  
  Toggle whether or not your Stargate will be chosen in a random dial.
  If you place your Stargate in a region with
  *Direct Teleport* turned off, this will be locked to **No**.

- **Image URL**  
  On the website, your Stargate can be represented by a small *256px by 256px* image.
  When you click this button, the
  Stargate will respond with a channel that you can say the URL of your image on.
  Once you respond with your image URL,
  it will be automatically set.

  > **NOTE:** If you do not have your own server to host images from, we recommend
  *Photobucket* ([http://www.photobucket.com/](http://www.photobucket.com/)),
  *Flickr* ([http://www.flickr.com/](http://www.flickr.com/)), or
  *TinyPic* ([http://www.tinypic.com](http://www.tinypic.com)).

- **Shield**  
  Your Stargate is packaged with *4* types of shields.
  This menu allows you to change between these with a click.
  The
  following shield types are available:
    - *Shield* — A built-in shield requiring no extra prims on your parcel.
      It is not animated, but resembles the shield
      seen in **Stargate: Atlantis**.
    - *Rezzed* — A rezzed shield requiring 3 extra prims on your parcel.
      This is an animated shield with glow added.
      It
      resembles the shield in **Stargate: Atlantis**.
    - *Iris* — A simple animated iris resembling the iris seen in the *SGC* in **Stargate: SG-1**.
    - *Disabled* — Disables all built-in shields, allowing for possible 3rd-party shields.
      See [Section 4.1](#41incoming-api) for more information on using the API to create a 3rd-party shield.

- **Listen**  
  Some people like to use their own relays for dial commands.
  We implemented a way to turn off the channel-0 listen.
  Clicking this button will disable listening on the public-0 channel.
  > **NOTE:** The listen on channel 123 will always be active as a convenience to gate users.

- **Output**  
  Some people like to use their own devices to output what the gate is currently saying.
  For this purpose, we
  implemented a way to turn off the channel-0 output.
  Clicking this button will disable output on the public channel.
  > **NOTE:** The output for menu commands (which must be done within range of the gate) will remain always on channel
    0.

- **Name**  
  This button allows you to change the *name* of your Stargate.
  This name is used to identify your Stargate in the logs,
  on incoming wormholes, and on the website.
  When you click this button, the Stargate will respond with a channel where
  you can say your Stargate’s name.
  Once you respond with your name, it is automatically set.

- **Alias**  
  Each Stargate is assigned an alias to make dialing via *direct dial* easier.
  This alias can be something like "zach's
  house" or "lex's pad."
  When you click this button, the Stargate responds with a channel where you can say your
  Stargate’s alias.
  Once you respond, it is automatically set.

### 1.3 - Tips on Location

There is nothing more frustrating than coming out of a Stargate in a building where you cannot find your way out, or
appearing in the sky, or coming through backwards.
These tips will help you set up your Stargate for the best
experience:

- *Do not place your Stargate in the air*  
  Obviously, if you are making a Spacegate scene, this is unavoidable.
  However, placing the Stargate high in the air so
  that people fall to their doom is generally bad practice.

- *Place your Stargate in an open area*  
  Teleporting into a location where the exit is not visible is frustrating.
  Please try to place your Stargate in an open
  area, not a small boxed room with no exit.

- *Keep your Stargate rotated to the North*  
  The Stargates are based on the `llMapDestination` method of teleporting, which does not support the LOOK_AT parameter.
  Because of this, you may appear facing backwards or sideways upon arrival.
  Placing your gate facing north will ensure
  incoming travelers appear facing outwards from the Stargate.

### 1.4 - Custom Sounds

Some people wish to customize the sounds the Stargate plays for various events, such as incoming wormholes, a spinning
ring, or the kawoosh.
The following sound labels in the Stargate are open for custom replacement:

- **windup** — Sound played when the inner ring starts to spin.
- **outloop** — Sound played when the inner ring loops spinning.
- **incloop** — *(Pegasus Stargate only)* Sound played when the inner ring loops spinning for an incoming wormhole.
- **chevron test** — Sound played when testing all 9 chevron lamps.
- **chevron encode** — Sound played when locking a symbol with the DHD.
- **chevron engage** — Sound played when locking a symbol during an incoming wormhole.
- **chevron lock** — Sound played when locking a symbol with any other method (i.e., long SGC-style dialing).
- **reset** — Sound played when the Stargate performs a reset.
- **restart** — Sound played when the Stargate performs a restart.
- **interference** — When a Stargate interferes with another in the same region, it plays a zapping sound.
- **open wormhole** — The *KAWOOSH!* sound.
- **force wormhole** — When a wormhole is forced open (Asgard/Nox style).
- **close wormhole** — Wormhole collapse sound.

You must call `/stargate reset` before these sound changes will take effect.

### 1.5 - Custom Lights

Your Stargate can adjust the on/off color of the gate lamps via a notecard.
In the Stargate’s inventory, you will see a
notecard called **chevrons.config**.
It looks like this:

```
Chevron Configuration - Set line 2 to the <r, g, b> for the off color. 
Set line 3 to the <r, g, b> for the on color.
<0, 0, 0>
<1, 1, 1>
```

You **must** keep these lines in the same format.
Issuing a `/stargate restart` command after changing this notecard
will save the settings, and the Stargate will “recalibrate” itself with the new colors.

## Section 2 - Using your Stargate

**NOTE:** Any of these commands can be said on either **channel 0** (public) or **channel 123** (for privacy).

### 2.1 - Dialing the Stargate

Dialing the Stargate is straightforward if you know the proper command.
Most dialing is done with the command `/dial`.
This will search all keywords (name, alias, region, addresses) that a Stargate can support.

| **Commands**        | Alternate |
||:|
| **Regular Dial**    |   `/dial` or `/d` |
| **Long Dial** (SGC) | `/sgc` or `/dsgc` |

> **Example:**
>
> - To dial a Stargate of the same type as yours, say `/dial <keyword>` (e.g., `/dial sonamu`).
> - To dial a Pegasus Stargate from a Milkyway gate, say `/dial pegasus <keyword>` (e.g., `/dial pegasus sonamu`).
> - To dial a Milkyway Stargate from a Pegasus gate, say `/dial milkyway <keyword>` (e.g., `/dial milkyway sonamu`).

If you have a Milkyway Stargate, you can also dial using the slower *SGC* style by replacing `/dial` with `/sgc`.
This
is where the inner ring rotates freely to each glyph and locks it using the top chevron (chevron 7).
It is slower, but
more authentic.

There are two other Stargate networks in Second Life®: **Open Stargate Network** and the **Cleary Stargate Network**.
We
are currently focusing on stabilizing our own network, so connections to those are not yet available.

All networks can be replaced by shorter “prefixes”:

| **Network** | **Valid Prefixes** |
|:--:|::|
|  *Pegasus*  |  `pegasus` or `p`  |
| *Milkyway*  | `milkyway` or `mw` |

To dial a gate with a Dial Home Device, you must have the glyph address of the target Stargate (listed on our website
at [https://www.alpha-fox.com/asn/](https://www.alpha-fox.com/asn/)). Or, you can use the glyph display included with
the
Stargate.

### 2.2 - Iris / Shield System

Your Stargate is equipped with a shield/iris system, preventing unwanted visitors from teleporting through.

Use these commands to operate the iris/shield:

- **`/stargate raise`** — Raises the gate shield / closes the iris
- **`/stargate lower`** — Lowers the gate shield / opens the iris

You can also use the [Stargate API](#section-4stargate-api) to control the iris.

If your gate’s iris is closed, you cannot dial into it unless you have an object on the other side that can signal the
iris to open via the API.

### 2.3 - Other Commands

Below are additional commands your gate uses.
Some are **private** (owner-only) and some are **public** (anyone can
use):

- **Private**
    - `/stargate reset` — Reset your Stargate
    - `/stargate offline` — Set your Stargate offline (use menu/API to bring it back online)
    - `/stargate restart` — Hard-reset your Stargate (**you will lose settings**)
    - `/stargate resetpass` — Reset the password for your account on the Alpha-Fox online interface
    - `/stargate raise` — Raise the Stargate shield / close the iris
    - `/stargate lower` — Lower the Stargate shield / open the iris
    - `/stargate test` — Test the chevron lamps
    - `/stargate test incoming` — Simulate an incoming wormhole
    - `/stargate test outgoing` — Simulate an outgoing wormhole

- **Public**
    - `/stargate version` — Returns the Stargate version
    - `/stargate name` — Returns the Stargate name
    - `/stargate alias` — Returns the Stargate alias
    - `/stargate help` — Returns quick help

When your Stargate is active, it can relay chat (using the [Stargate API](#section-4stargate-api)) and region
statistics.
The chat buffer is limited to 20 messages every ~4 seconds.

### 2.4 - Menu System

When you click on your Stargate, a menu appears with many available commands. Each menu entry is explained below:

- **Subnova** — Contacts the Alteran Stargate Network HQ.
- **Top Gates** — Lists the top 20 gate names and regions by popularity.
- **Statistics** — Outputs statistics on incoming and outgoing wormholes.
- **Version** — Outputs the current version of your Stargate.
- **Help** — Outputs a quick help message.
- **Settings** — Allows you to [change settings](#12customizing-your-stargate) in your Stargate.
- **Summary** — Gives a link to the webpage for your Stargate.
- **Controls** — Allows you to give commands such as *Reset*, *Restart*, *Delete*, and *Offline*.
- **Memory** — Dumps the memory levels of every Stargate script (useful for debugging crashes).
- **Report** — Allows you to report a Stargate for an SSoP violation.
- **Rate** — Allows you to rate a Stargate location on a scale of 0-5.

### 2.5 - Technical Information

This section is more technical. (Time to sound like Samantha Carter.)

#### 2.5.1 - Server, Communications, Continuity

Each Stargate registers itself on a MySQL database using PHP.
The gate backend server, named *Chimera* and hosted on
the [Subnova Network](http://www.subnova.com/), handles most communications and data, making in-world gates mostly
“dumb-terminals.”
Unlike the original *Daedalus* server, *Chimera* is UPS-backed with a static IP address.

Communications are handled via **AFVI** (Alpha-Fox Virtual Interface) servers developed by Alpha-Fox, instead of XML-RPC
or email-based solutions.
The **AFVI** system sends out lslmails from queries in our SQL database.
It’s fairly fast (~3
seconds round trip), and verifiable (we can confirm receipt).

Each Stargate checks in every **5 minutes**, with status changes registered as soon as they happen.
If a gate fails to
check in for more than 6 minutes, the server marks it offline.
If it checks in again, it returns online with all
previous settings.
The dead gate list is cleared every 72 hours.

#### 2.5.2 - Addressing System

Each region on the grid is given **two** addresses: a *native* address and a *cross-network* address.
Your Stargate
always has the same address for other gates of the same type to dial, and a cross-network address for gates of the other
type.

Each Stargate also has an **SGC-ID**, similar to show-based addresses like P4X-639.
This is unique and can also be used
to direct dial your gate.

**Milkyway Stargates** have 39 symbols (index 0-38).
Glyph 0 is the point of origin (always the last glyph in an
address).
On a standard Milkyway DHD, there are 38 symbols (1-38) plus the big orange button for the origin.

Below is the Milkyway glyph layout (0-38). *(Images shown in a grid; each number is the glyph index.)*

| ![Glyph 0](https://images.alpha-fox.com/asn/glyphs/milkyway/0.gif) **0** | ![Glyph 1](https://images.alpha-fox.com/asn/glyphs/milkyway/1.gif) **1** | ![Glyph 2](https://images.alpha-fox.com/asn/glyphs/milkyway/2.gif) **2** | ![Glyph 3](https://images.alpha-fox.com/asn/glyphs/milkyway/3.gif) **3** | ![Glyph 4](https://images.alpha-fox.com/asn/glyphs/milkyway/4.gif) **4** | ![Glyph 5](https://images.alpha-fox.com/asn/glyphs/milkyway/5.gif) **5** | ![Glyph 6](https://images.alpha-fox.com/asn/glyphs/milkyway/6.gif) **6** | ![Glyph 7](https://images.alpha-fox.com/asn/glyphs/milkyway/7.gif) **7** | ![Glyph 8](https://images.alpha-fox.com/asn/glyphs/milkyway/8.gif) **8** |
|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|

| ![Glyph 9](https://images.alpha-fox.com/asn/glyphs/milkyway/9.gif) **9** | ![Glyph 10](https://images.alpha-fox.com/asn/glyphs/milkyway/10.gif) **10** | ![Glyph 11](https://images.alpha-fox.com/asn/glyphs/milkyway/11.gif) **11** | ![Glyph 12](https://images.alpha-fox.com/asn/glyphs/milkyway/12.gif) **12** | ![Glyph 13](https://images.alpha-fox.com/asn/glyphs/milkyway/13.gif) **13** | ![Glyph 14](https://images.alpha-fox.com/asn/glyphs/milkyway/14.gif) **14** | ![Glyph 15](https://images.alpha-fox.com/asn/glyphs/milkyway/15.gif) **15** | ![Glyph 16](https://images.alpha-fox.com/asn/glyphs/milkyway/16.gif) **16** | ![Glyph 17](https://images.alpha-fox.com/asn/glyphs/milkyway/17.gif) **17** |
|--------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|

| ![Glyph 18](https://images.alpha-fox.com/asn/glyphs/milkyway/18.gif) **18** | ![Glyph 19](https://images.alpha-fox.com/asn/glyphs/milkyway/19.gif) **19** | ![Glyph 20](https://images.alpha-fox.com/asn/glyphs/milkyway/20.gif) **20** | ![Glyph 21](https://images.alpha-fox.com/asn/glyphs/milkyway/21.gif) **21** | ![Glyph 22](https://images.alpha-fox.com/asn/glyphs/milkyway/22.gif) **22** | ![Glyph 23](https://images.alpha-fox.com/asn/glyphs/milkyway/23.gif) **23** | ![Glyph 24](https://images.alpha-fox.com/asn/glyphs/milkyway/24.gif) **24** | ![Glyph 25](https://images.alpha-fox.com/asn/glyphs/milkyway/25.gif) **25** | ![Glyph 26](https://images.alpha-fox.com/asn/glyphs/milkyway/26.gif) **26** |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|

| ![Glyph 27](https://images.alpha-fox.com/asn/glyphs/milkyway/27.gif) **27** | ![Glyph 28](https://images.alpha-fox.com/asn/glyphs/milkyway/28.gif) **28** | ![Glyph 29](https://images.alpha-fox.com/asn/glyphs/milkyway/29.gif) **29** | ![Glyph 30](https://images.alpha-fox.com/asn/glyphs/milkyway/30.gif) **30** | ![Glyph 31](https://images.alpha-fox.com/asn/glyphs/milkyway/31.gif) **31** | ![Glyph 32](https://images.alpha-fox.com/asn/glyphs/milkyway/32.gif) **32** | ![Glyph 33](https://images.alpha-fox.com/asn/glyphs/milkyway/33.gif) **33** | ![Glyph 34](https://images.alpha-fox.com/asn/glyphs/milkyway/34.gif) **34** | ![Glyph 35](https://images.alpha-fox.com/asn/glyphs/milkyway/35.gif) **35** |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|

| ![Glyph 36](https://images.alpha-fox.com/asn/glyphs/milkyway/36.gif) **36** | ![Glyph 37](https://images.alpha-fox.com/asn/glyphs/milkyway/37.gif) **37** | ![Glyph 38](https://images.alpha-fox.com/asn/glyphs/milkyway/38.gif) **38** |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------|

**Pegasus Stargates** have 36 glyphs.
To keep the DHD symmetrical, it has 36 buttons, meaning even the point of origin (
glyph 0) is a button.
So you must press glyph 0 before pressing the big blue center button.

Pegasus glyph layout (0-35). *(Again, images in a grid; each number is the index.)*

| ![Glyph 0](https://images.alpha-fox.com/asn/glyphs/pegasus/0.gif) **0
** | ![Glyph 1](https://images.alpha-fox.com/asn/glyphs/pegasus/1.gif) **1
** | ![Glyph 2](https://images.alpha-fox.com/asn/glyphs/pegasus/2.gif) **2
** | ![Glyph 3](https://images.alpha-fox.com/asn/glyphs/pegasus/3.gif) **3
** | ![Glyph 4](https://images.alpha-fox.com/asn/glyphs/pegasus/4.gif) **4
** | ![Glyph 5](https://images.alpha-fox.com/asn/glyphs/pegasus/5.gif) **5
** | ![Glyph 6](https://images.alpha-fox.com/asn/glyphs/pegasus/6.gif) **6
** | ![Glyph 7](https://images.alpha-fox.com/asn/glyphs/pegasus/7.gif) **7
** | ![Glyph 8](https://images.alpha-fox.com/asn/glyphs/pegasus/8.gif) **8** |
||||||||||

| ![Glyph 9](https://images.alpha-fox.com/asn/glyphs/pegasus/9.gif) **9
** | ![Glyph 10](https://images.alpha-fox.com/asn/glyphs/pegasus/10.gif) **10
** | ![Glyph 11](https://images.alpha-fox.com/asn/glyphs/pegasus/11.gif) **11
** | ![Glyph 12](https://images.alpha-fox.com/asn/glyphs/pegasus/12.gif) **12
** | ![Glyph 13](https://images.alpha-fox.com/asn/glyphs/pegasus/13.gif) **13
** | ![Glyph 14](https://images.alpha-fox.com/asn/glyphs/pegasus/14.gif) **14
** | ![Glyph 15](https://images.alpha-fox.com/asn/glyphs/pegasus/15.gif) **15
** | ![Glyph 16](https://images.alpha-fox.com/asn/glyphs/pegasus/16.gif) **16
** | ![Glyph 17](https://images.alpha-fox.com/asn/glyphs/pegasus/17.gif) **17** |
||||||||||

| ![Glyph 18](https://images.alpha-fox.com/asn/glyphs/pegasus/18.gif) **18
** | ![Glyph 19](https://images.alpha-fox.com/asn/glyphs/pegasus/19.gif) **19
** | ![Glyph 20](https://images.alpha-fox.com/asn/glyphs/pegasus/20.gif) **20
** | ![Glyph 21](https://images.alpha-fox.com/asn/glyphs/pegasus/21.gif) **21
** | ![Glyph 22](https://images.alpha-fox.com/asn/glyphs/pegasus/22.gif) **22
** | ![Glyph 23](https://images.alpha-fox.com/asn/glyphs/pegasus/23.gif) **23
** | ![Glyph 24](https://images.alpha-fox.com/asn/glyphs/pegasus/24.gif) **24
** | ![Glyph 25](https://images.alpha-fox.com/asn/glyphs/pegasus/25.gif) **25
** | ![Glyph 26](https://images.alpha-fox.com/asn/glyphs/pegasus/26.gif) **26** |
||||||||||

| ![Glyph 27](https://images.alpha-fox.com/asn/glyphs/pegasus/27.gif) **27
** | ![Glyph 28](https://images.alpha-fox.com/asn/glyphs/pegasus/28.gif) **28
** | ![Glyph 29](https://images.alpha-fox.com/asn/glyphs/pegasus/29.gif) **29
** | ![Glyph 30](https://images.alpha-fox.com/asn/glyphs/pegasus/30.gif) **30
** | ![Glyph 31](https://images.alpha-fox.com/asn/glyphs/pegasus/31.gif) **31
** | ![Glyph 32](https://images.alpha-fox.com/asn/glyphs/pegasus/32.gif) **32
** | ![Glyph 33](https://images.alpha-fox.com/asn/glyphs/pegasus/33.gif) **33
** | ![Glyph 34](https://images.alpha-fox.com/asn/glyphs/pegasus/34.gif) **34
** | ![Glyph 35](https://images.alpha-fox.com/asn/glyphs/pegasus/35.gif) **35** |
||||||||||

Address assignment is handled by *Andromeda* on the [Subnova Network](http://www.subnova.com/) and can take about **1
day** to generate addresses for the entire grid.
Because of this addressing system, only **one** gate per type, per
region is addressable by glyph.
You can still place more gates in the same region; they just cannot be dialed via glyph
address—only by *name* or *alias*.

You can apply for an admin-assigned "forward address" if you want a canonical address from the show, for instance.
To do
this, submit a request in the [Help Desk](https://www.alpha-fox.com/support/tickets/).
Include your gate location and
desired address.

#### 2.5.3 - Failsafes / Limitations

We included some canonical failsafes and limitations:

- Only one Stargate of the same type can be active at a time in a region.
  If one is active, another of the same type
  cannot dial or receive.
- If one gate is dialing and the primary Stargate in that region gets an incoming, the primary gate always “wins.”
- Likewise, if one gate is dialing and the primary gate attempts to dial out, the primary gate always “wins.”
- This ensures canonical behavior and also helps avoid scripting or sim-performance issues.

## Section 3 - Stargate Official Addons

### 3.1 - Death System

**Death** is an addon by *Alpha-Fox* that allows the unstable vortex and other lethal actions of the Stargate to kill
users on safe land.
If you deed this addon to the parcel group and turn it on, the gate will kill avatars caught in the
unstable vortex.

This addon also has an API so people can integrate it with their own scripts.
It listens throughout the entire region,
so only one Death system needs to be rezzed per group/owner.

> **UNDER NO CIRCUMSTANCES SHOULD YOU DEED THE STARGATE TO YOUR LAND**  
> *(Only the Death System should be deeded, if used.)*

### 3.2 - Dial Home Devices

The Stargate package includes 4 DHDs (Dial Home Devices):

- **Milkyway** — A lite version of the OS DHD by [OS Labs](http://www.oslabs.info/).
- **Pegasus** — A lite version of the OS DHD by [OS Labs](http://www.oslabs.info/).
- **Tollan** — A *concept* DHD built by Lex Mars and scripted by Zachary Carter.
- **Forerunner** — Another *concept* DHD built by Lex Mars and scripted by Zachary Carter.

These DHDs allow direct glyph entry to dial a destination.
After entering the 6 (or 7) glyphs and pressing the center
button, the gate will spin up and, hopefully, lock.
See *Sections 1 and 2* of this guide for more info.

DHDs only work on Stargates you own.
They also listen to all gates in the region, so having multiple same-network gates
of your own may cause confusion.

### 3.3 - Address Display

The Address Display is a free way to see glyph addresses without using the website. Rez this object and use:

- `/lookup <network keyword>`
- `/clear`
- `/setnetwork <network>`

*network* is either `milkyway` or `pegasus`.
If none is provided to `/lookup`, it uses the network set by `/setnetwork`.
By default, it uses `milkyway`.

`/clear` simply clears the display. Changing the display prim names (1-7) may break it.

When rezzed, it listens to your gate, lighting up the address on incoming/outgoing, and showing **your** Stargate’s
address when idle:

- **White** = Looked-up address
- **Orange / Aqua** = Milkyway / Pegasus native address (your Stargate’s address)
- **Red / Blue** = Incoming / Outgoing wormhole

### 3.4 - Stargate Control Unit

The **Stargate Control Unit** is like “The Poor Man’s DHD.”
It allows commands such as Reset, Shield, etc., plus a
directory of preset dial addresses.
The model is based on the control unit the Ancients used in **3x10 The Return Pt.
1
** of *Stargate: Atlantis*.

All commands are accessed by touching the device and using the menus:

- **Control** — Shield, reset, offline, test incoming/outgoing, random dial, etc.
- **Directory** — Add addresses and dial previously stored ones.
- **Options** — Toggle verbosity, play sounds, ring spin, and more.

The side color indicates which gate network it’s controlling (*aqua* for Pegasus, *orange* for Milkyway).
The small
screen at top shows the current status.

This device only works on Stargates you own and may conflict if you have multiple same-network gates in the region.

## Section 4 - Stargate API

The Stargates have an **Application Programming Interface (API)** to interface in both basic and advanced ways.
There
are two API levels: **Public** and **Private**.
Public** commands can be submitted by anyone, while **Private**
commands only work for the Stargate’s owner.

### 4.1 - Incoming API

These are commands you can *send* to the gate to control it. The channels are:

- **Pegasus**: `-804000`
- **Milkyway**: `-904000`

Below are the recognized commands.
Bold** indicates **public** (works for anyone within 20m unless it’s the owner, who
has no distance limit).
Italic* indicates **private** (owner-only).

<table width="560" border="0" cellpadding="0" cellspacing="2">
<tr>
		<td width="250" bgcolor="#FFFFFF"><strong>dial|&lt;1/0&gt;|&lt;glyph&gt;</strong></td>
	<td width="304" bgcolor="#FFFFFF">Dials a glyph on your Stargate with a spinval of 1 / 0
(whether inner ring spins)</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td width="250"><strong>stargate status</strong></td>
		<td bgcolor="#D0DCE8">Returns the status of the Stargate</td>
  </tr>
	<tr>
		<td bgcolor="#FFFFFF"><strong>send chatter|&lt;name&gt;|&lt;msg&gt;|&lt;1/0&gt;</strong></td>
	  <td bgcolor="#FFFFFF">Sends chatter through an active gate.
The variable at the end will let you keep the wormhole open if set to 1</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td><strong>stargate version</strong></td>
		<td>Returns the version of the Stargate</td>
	</tr>
	<tr>
		<td bgcolor="#FFFFFF"><strong>stargate address</strong></td>
	  <td bgcolor="#FFFFFF">Returns <em>native and cross-network</em> addresses</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td><strong>stargate name</strong></td>
		<td>Returns the name of the Stargate</td>
	</tr>
	<tr>
		<td bgcolor="#FFFFFF"><strong>stargate alias</strong></td>
	  <td bgcolor="#FFFFFF">Returns the alias of the Stargate</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td><strong>stargate probe</strong></td>
		<td>Probes the target Stargate (outgoing only)</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><strong>lookup|&lt;net&gt;|&lt;kw&gt;</strong></td>
	  <td bgcolor="#FFFFFF">Looks up a Stargate. You can replace network with * for wildcard</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><strong>directdial|&lt;net&gt;|&lt;kw&gt;|&lt;2/1/0&gt;</strong></td>
	  <td bgcolor="#D0DCE8">Dials a Stargate using direct dial with a spinval of 1 / 0
(whether inner ring spins - when you set it to &quot;2&quot; it does a forced wormhole).
You can replace network with * for wildcard.</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><strong>stargate emp</strong></td>
	  <td bgcolor="#FFFFFF">Sends a pulse through the wormhole extending the open time for 30 seconds</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><strong>interference</strong></td>
	  <td bgcolor="#D0DCE8">Causes the gate to flicker and make a zap noise</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>raise shield</em></td>
	  <td bgcolor="#FFFFFF">Raises the shield on your gate</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>lower shield</em></td>
	  <td bgcolor="#D0DCE8">Lowers the shield on your gate</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>delete stargate</em></td>
	  <td bgcolor="#FFFFFF">Deletes your gate</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>offline stargate</em></td>
	  <td bgcolor="#D0DCE8">Turns your gate offline</td>
  </tr>
	<tr>
		<td bgcolor="#FFFFFF"><em>online stargate</em></td>
	  <td bgcolor="#FFFFFF">Turns your gate online</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>reset stargate</em></td>
	  <td bgcolor="#D0DCE8">Resets your gate</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>restart stargate</em></td>
	  <td bgcolor="#FFFFFF">Restarts your gate</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>shutdown wormhole</em></td>
	  <td bgcolor="#D0DCE8">Shuts down an active wormhole</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>cut wormhole</em></td>
	  <td bgcolor="#FFFFFF">Cuts an active wormhole</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>test stargate</em></td>
	  <td bgcolor="#D0DCE8">Tests the chevron lamps on your gate.</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>test stargate outgoing</em></td>
	  <td bgcolor="#FFFFFF">Simulates an outgoing wormhole</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>test stargate incoming</em></td>
	  <td bgcolor="#D0DCE8">Simulates an incoming wormhole</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td bgcolor="#FFFFFF"><em>set name|&lt;name&gt;</em></td>
	  <td bgcolor="#FFFFFF">Sets the name of your gate</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>set alias|&lt;alias&gt;</em></td>
	  <td bgcolor="#D0DCE8">Sets the alias of your gate</td>
  </tr>
	<tr>
		<td><em>set image url|&lt;url&gt;</em></td>
		<td>Sets the image URL of your gate</td>
	</tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>ring speed|&lt;speed&gt;</em></td>
	  <td bgcolor="#D0DCE8">Changes the inner ring speed on Milkyway gates.
Needs to be sent at the beginning of every dial.</td>
  </tr>
	<tr>
		<td bgcolor="#FFFFFF"><em>public listen|&lt;1/0&gt;</em></td>
	  <td bgcolor="#FFFFFF">Turns on / off the listen on channel 0 for commands.</td>
  </tr>
	<tr>
		<td bgcolor="#D0DCE8"><em>public output|&lt;1/0&gt;</em></td>
	  <td bgcolor="#D0DCE8">Turns on / off the verbose output of the Stargate<em></em></td>
  </tr>
	<tr>
		<td bgcolor="#FFFFFF"><em>random list|&lt;1/0&gt;</em></td>
	  <td bgcolor="#FFFFFF">Turns on / off random dial listing</td>
  </tr>
</table>

### 4.2 - Outgoing API

The *outgoing* API are events the Stargate *sends out*. The channels are:

- **Pegasus**: `-805000`
- **Milkyway**: `-905000`

Below are the typical responses (they may change over time):

<table width="560" border="0" cellpadding="0" cellspacing="2">
<tr bgcolor="#FFFFFF">
		<td width="350" height="19">stargate reset</td>
	<td width="204">Gate has been reset</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">status|&lt;outgoing/incoming/idle/offline/dialing&gt;</td>
		<td>Gate status has changed.</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19">shield|&lt;0/1&gt;</td>
		<td>Gate shield has changed</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">ping</td>
		<td>Gate pinged to the server</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19">dial lookup|&lt;succ/fail&gt;|&lt;addr&gt;|&lt;spin&gt;|&lt;region &gt;|&lt;pos&gt;|&lt;nw&gt;|&lt;name&gt;|&lt;alias&gt;|&lt;owner&gt;|&lt;sgc id&gt;</td>
		<td>Return from a directdial API command</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">search lookup|&lt;succ/fail&gt;|&lt;native&gt;|&lt;cross&gt;|&lt;region &gt;|&lt;pos&gt;|&lt;nw&gt;|&lt;name&gt;|&lt;alias&gt;|&lt;owner&gt;|&lt;sgc id&gt;</td>
	  <td bgcolor="#D0DCE8">Return from a lookup API command</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">chevron &lt;#&gt; encoded</td>
	  <td bgcolor="#FFFFFF">Chevron has lit up (dhd)</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">chevron &lt;#&gt; engaged</td>
	  <td bgcolor="#D0DCE8">Chevron has lit up (incoming)</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">chevron &lt;#&gt; locked</td>
	  <td bgcolor="#FFFFFF">Chevron has lit up (long dial)</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">dial &lt;succ/fail&gt;|&lt;region&gt;|&lt;pos&gt;|&lt;nw&gt;| &lt;name&gt;|&lt;alias&gt;|&lt;owner&gt;|&lt;sgc id&gt;|&lt;rot&gt;</td>
	    <td bgcolor="#D0DCE8">Stargate has attempted to lock an address</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">stargate close</td>
	  <td bgcolor="#FFFFFF">Stargate has shutdown</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">stargate cut</td>
	  <td bgcolor="#D0DCE8">Stargate has cut power</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">wormhole collision|&lt;type&gt;|&lt;uuid&gt;</td>
		<td bgcolor="#FFFFFF">Collision with the event horizon</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">stargate restart</td>
	  <td bgcolor="#D0DCE8">Gate has restarted</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">incoming wormhole|&lt;region&gt;|&lt;pos&gt;|&lt;owner name&gt;|&lt;name&gt;|&lt;alias&gt;|&lt;address&gt;|&lt;sgc id&gt;</td>
	  <td bgcolor="#FFFFFF">Incoming wormhole</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">stargate version|&lt;version&gt;</td>
	  <td bgcolor="#D0DCE8">Gate version output</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">stargate address|&lt;native&gt;|&lt;cross&gt;</td>
	  <td bgcolor="#FFFFFF">Gate address output</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">random listing|&lt;1/0&gt;</td>
	  <td bgcolor="#D0DCE8">Random dial listing</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">stargate delete</td>
	  <td bgcolor="#FFFFFF">Stargate deleting</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">public listen|&lt;1/0&gt;</td>
	  <td bgcolor="#D0DCE8">Channel 0 listen</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">shield type|&lt;irisrezzed/shield/disabled&gt;</td>
	  <td bgcolor="#FFFFFF">Change shield type</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">set name|&lt;successful/failed&gt;|reason</td>
	  <td bgcolor="#D0DCE8">Name changed</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">set alias|&lt;successful/failed&gt;|reason</td>
	  <td bgcolor="#FFFFFF">Alias changed</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">set image url|&lt;successful/failed&gt;|reason</td>
		<td>Image changed</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19">stargate registered</td>
		<td>Gate registered</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">emp pulse sent</td>
		<td>EMP pulse sent</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19">invalid api command passed</td>
		<td>Invalid command</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">stargate name|&lt;name&gt;</td>
		<td>Stargate name output</td>
	</tr>
	<tr bgcolor="#FFFFFF">
		<td height="19">stargate alias|&lt;alias&gt;</td>
		<td>Stargate alias output</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td height="19">chatter|&lt;name&gt;|&lt;msg&gt;</td>
		<td>Wormhole chatter. Ignore names starting with _.</td>
	</tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">probe|&lt;succ/fail&gt;|&lt;fps&gt;|&lt;time&gt;|&lt;parcel name&gt;|&lt;parcel desc&gt;|&lt;agent count&gt;</td>
	  <td bgcolor="#FFFFFF">Target gate probe</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">stargate test</td>
	  <td bgcolor="#D0DCE8">Chevron lamp test</td>
  </tr>
	<tr bgcolor="#D0DCE8">
		<td height="19" bgcolor="#FFFFFF">stargate test incoming</td>
	  <td bgcolor="#FFFFFF">Incoming wormhole simulation</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">stargate test outgoing</td>
	  <td bgcolor="#D0DCE8">Outgoing wormhole simulation</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#FFFFFF">interference</td>
	  <td bgcolor="#FFFFFF">Experiencing interference</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">wormhole fataility|&lt;type&gt;|&lt;uuid&gt;|&lt;what&gt;</td>
	  <td bgcolor="#D0DCE8">The wormhole has killed</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#FFFFFF">target shield raised</td>
	  <td bgcolor="#FFFFFF">Target shield raised</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">target shield lowered</td>
	  <td bgcolor="#D0DCE8">Target shield lowered</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#FFFFFF">destination|&lt;region&gt;|&lt;pos&gt;|&lt;rot&gt;</td>
	    <td bgcolor="#FFFFFF">Wormhole destination changed. &quot;--&quot; is no destination.</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">prompt|&lt;msg&gt;</td>
	  <td bgcolor="#D0DCE8">Stargate chat outputs</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#FFFFFF">top gates|&lt;name,name,name&gt;</td>
	  <td bgcolor="#FFFFFF">Top 20 gates by popularity</td>
  </tr>
	<tr bgcolor="#FFFFFF">
		<td height="19" bgcolor="#D0DCE8">gate statistics|&lt;inc&gt;|&lt;out&gt;|&lt;total&gt;</td>
	  <td bgcolor="#D0DCE8">Basic statistics about the gate</td>
  </tr>
    <tr bgcolor="#FFFFFF">
		<td height="36" bgcolor="#FFFFFF">target wormhole collision|&lt;type&gt;|&lt;uuid&gt;</td>
	  <td bgcolor="#FFFFFF">Wormhole collision on the connected Stargate (not yours)</td>
  </tr>
    <tr bgcolor="#FFFFFF">
      <td height="36" bgcolor="#D0DCE8">http error|&lt;error&gt;</td>
      <td bgcolor="#D0DCE8">An error with the http_response</td>
    </tr>
    <tr bgcolor="#FFFFFF">
      <td height="36" bgcolor="#FFFFFF">stargate open</td>
      <td bgcolor="#FFFFFF">The Stargate has opened</td>
    </tr>
    <tr bgcolor="#FFFFFF">
      <td height="36" bgcolor="#D0DCE8">clearing buffer</td>
      <td bgcolor="#D0DCE8">The buffer of the Stargate is being cleared (all of the scripts being reset)</td>
    </tr>
    <tr bgcolor="#FFFFFF">
      <td height="36" bgcolor="#FFFFFF">chatter saved</td>
      <td bgcolor="#FFFFFF">Chatter has been saved for target gate</td>
    </tr>
    <tr bgcolor="#FFFFFF">
      <td height="36" bgcolor="#D0DCE8">wormhole extended</td>
      <td bgcolor="#D0DCE8">Results from emp command or emp flag on chatter.</td>
    </tr>
</table>

## Section 5 - Online Interface

Alteran Stargates have an online interface at [https://www.alpha-fox.com/asn/](https://www.alpha-fox.com/asn/). You can
view, customize, and control your Stargates in one place.
You’ll need to log in with your Second Life avatar name and
the password the Stargate gave you on first rez.

> **NOTE:** If you’ve forgotten your password, use the **`/stargate resetpass`** command.

### 5.1 - Stargate Information Page

On the **My Stargates** page, you can view all Stargates you have rezzed.
Clicking a specific gate shows detailed info,
such as:

- Stargate name
- Region & region flags
- Current owner
- Direct dial glyph addresses (plus any forward address)
- Last check-in time / seconds since last ping
- Last 20 connections
- Statistics (incoming/outgoing)
- Position in the sim
- Gate status and shield status
- Alias & Network (Pegasus/Milkyway)
- Gate type (Forerunner, Pegasus, Tollan, Milkyway)
- SGC-ID
- Description
- Gate Image

### 5.2 - Customizing your Stargate

You can also customize:

- Name
- Alias
- Image URL
- Description
- Random Listing

Follow the instructions on your Stargate’s info page to customize.

### 5.3 - Controlling your Stargate

Using the online interface, you can remotely control your Stargate:

- Reset / Restart
- Raise / Lower Shield
- Set Offline
- Delete
- Force Incoming Test
- Force Outgoing Test
- Send a message to the gate

Just follow the on-page instructions for your specific Stargate.

### 5.4 - Web Profile

We also provide a way to show a “profile” of your Stargates in your Second Life Web Profile.
Use the URL (replacing
`First_Last` with your SL name):

```
https://www.alpha-fox.com/asn/profile/First_Last/
```

For example:  
`https://www.alpha-fox.com/asn/profile/Zachary_Carter/`

## Section 6 - Updating your Stargate

### 6.1 - Update Policy

We try to announce major code updates that might affect gate performance.
We cannot guarantee network uptime, so we may
take the network down for emergency maintenance.
We will attempt to notify the in-world group and forums if a takedown
occurs.

### 6.2 - Types of Updates

Stargates will be updated periodically. Updates can vary:

- **No new Stargate** needed (e.g., a new menu function, API command, or minor fix).
- **Script update only** (e.g., a main script in the parent prim is updated, delivered via an updater orb).
- **Full model replacement** (e.g., new model, textures, or major chevron/ring script changes).

### 6.3 - How to Update

Depending on the update type:

- **Backend fix only:** Usually just do `/stargate reset`.
- **Code update:** Rez the provided update orb near your Stargate and click it.
  It will update automatically, then
  self-delete.
- **Full model update:** Rez the update orb; it will replace the entire gate model and transfer settings for you.

## Section 7 - Troubleshooting

### 7.1 - Common Issues

Here are frequently asked questions:

**Q:** My Stargate froze mid-dial, or has been open a long time (over 38 minutes).  
**A:** Usually a `/stargate reset` fixes it; at worst, `/stargate restart`.

**Q:** The Stargate fails repeatedly when dialing another Stargate in the same region!  
**A:** A Stargate cannot dial another Stargate of the same type in the same region.
This follows the TV show limitation.

**Q:** My Stargate failed to dial because another Stargate in my region was active.
Why?  
**A:** If one gate is active, no other same-type gate in the region can dial or receive.
Again, this is a limitation
from the show.

**Q:** Why don’t we teleport immediately upon colliding with the event horizon?  
**A:** Scripting limitations; we rely on `llMapDestination`.
When `llTeleportAgent` becomes available, we will integrate
it.

**Q:** Can you automatically update our Stargates?
Do they self-update?  
**A:** We have a method for pushing updates, but it’s not feasible for us to update all Stargates manually.
You must
update your own.
Get the latest release at [https://www.alpha-fox.com/asn/get/](https://www.alpha-fox.com/asn/get/).

**Q:** Where can I get a Stargate?  
**A:** [https://www.alpha-fox.com/asn/get/](https://www.alpha-fox.com/asn/get/).

**Q:** Is there a “Premium Mode” or any fees for using the Stargate?  
**A:** No.
Our Stargates are 100% free.
Donations are appreciated but do not affect functionality.

**Q:** Where can I get a DHD or other Stargate addons?  
**A:** Try [OS Labs](http://www.oslabs.info/) or XStreet SL/Apez searching for “stargate.”
We do not officially support
third-party addons beyond those in our package.
You can also check
our [Script Library forum](https://www.alpha-fox.com/community/forum.php?id=8).

**Q:** When is feature *xyz* coming, or bug *abc* going to be fixed?  
**A:** Report features/bugs in our forums.
We’ll post updates on them there.

- Bug Reports: [https://www.alpha-fox.com/community/forum.php?id=7](https://www.alpha-fox.com/community/forum.php?id=7)
- Feature
  Requests: [https://www.alpha-fox.com/community/forum.php?id=5](https://www.alpha-fox.com/community/forum.php?id=5)

### 7.2 - Where to Obtain Help

1. **Read the user guide** (this document).
2. **Ask in the Alteran Stargate Network group** in-world.
3. **Read the Forums** to see if the issue is already answered.
4. **Post** in the forums if you don’t see your issue.
5. **File a [support ticket](https://www.alpha-fox.com/support/tickets/)** — we aim to respond quickly.
6. If all else fails, contact an [administrator or staff](#84current-staff) of the Alteran Stargate Network.

See also: [https://www.alpha-fox.com/support/](https://www.alpha-fox.com/support/)

## Section 8 - Information

### 8.1 - Disclosure

The right to own a Stargate is a *privilege*, not a right.
Network administrators reserve the right to remove that
privilege at any time, for any or no reason.

### 8.2 - Copyright

“Alteran Stargate Network” is a virtual Stargate Network in Second Life® and is not affiliated with MGM Television
Entertainment, Stargate Productions, Showtime Networks, Inc., or NBC/Universal.
Our usage is for fan-based promotion of
the franchise.

- **STARGATE SG-1** © 1997 - 2008 MGM Television Entertainment Inc. and MGM Global Holdings Inc. STARGATE SG-1 is a
  trademark of Metro-Goldwyn-Mayer Studios Inc. All Rights Reserved.
- **STARGATE: ATLANTIS** © 2004 - 2008 MGM Global Holdings Inc. STARGATE: ATLANTIS is a trademark of Metro-Goldwyn-Mayer
  Studios Inc. All Rights Reserved.

Graphics for the event horizon, milkyway inner glyph ring, and naquadah base background were provided
by [David Gian-Cursio](http://web.mac.com/david_of_mac/).

The explosion effect (_Explosion) is an open-source effect by Kithylin Perth.

The opening and closing iris sounds were cut from [SGC-SIM](http://www.sgcsim.com/).

The ring windup/loop and chevron sounds were captured and provided by BWolf Murakami.

All other objects, scripts, graphics, and audio files (unless otherwise specified) are property of the Alteran Stargate
Network admins and Alpha-Fox.

### 8.3 - Credit

This Stargate system is the product of many people’s efforts:

- **Wes Keynes** — Provided ideas for direct dialing, version indexing, etc. (Cleary Network).
- **Mintopia Ambassador** — Original spark for the first Stargate network.
- **Reyo Neutra** — Creator of the original (retired) model for Mintopia’s Stargate.
- **Geordie Boffin** — Creator of original textures on the first Mintopia Stargate.
- **Lex Mars** — New gate size, textures, sounds, diameter; coded Pegasus ring movement.
- **Wolfie Waves** — Creator of Arcturus 4.0 gate model, which was adapted to create Alteran 1.0.
  Also wrote the
  original help guide.
- **Kirby Figtree** — Located [David Gian-Cursio](http://web.mac.com/david_of_mac/) for horizon/texture resources.
- **Zwagoth Klaar** — Helped with new PHP code, SQL data storage methods.
- **Kegan Loon** — Concept of the “Automatic Map” system in 2006.
- **Peter Lameth** — Wrote the original code for the first network; we wouldn’t be here without it.
- **Ash Qin** — Provided concept of using the owner-UUID in URLs for blacklisting.
- **Jandav Auer** — Rewrote event horizon collision logic to avoid repeated kills.

### 8.4 - Current Staff

The Alteran Stargate Network is managed by a diverse team:

- **Zachary Carter** — Founder; programmed most backend and frontend systems.
- **Lex Mars** — Skilled texture artist, builder, and programmer; keeps the model close to canon.
- **Wolfie Waves** — Builder/texture artist; created the Alteran Stargate DHD and the OS DHD.
- **Peter Lameth** — Original network co-creator; helps with support management; runs Eternal Calm Estate.
- **Ash Qin** — Programmer focusing on encryption and other dev tasks; owner of [Quickfox](http://www.quickfox.net/).

**Zachary Carter**  
*Copyright 2008 Alteran Stargate Network*  
[https://www.alpha-fox.com/asn/](https://www.alpha-fox.com/asn/)

This manual was last updated on 15 November 2008.
