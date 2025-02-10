<a id="top"></a>

![Alpha-Fox logo](http://images.alpha-fox.com/logo/asn_logo_small.jpg "Alpha-Fox logo")

## Contents

- [Section 1 - Setting up your Stargate](#section-1---setting-up-your-stargate)
    - [1.1 - Basic Setup](#1.1---basic-setup)
    - [1.2 - Customizing your Stargate](#1.2---customizing-your-stargate)
    - [1.3 - Tips on Location](#1.3---tips-on-location)
    - [1.4 - Custom Sounds](#1.4---custom-sounds)
    - [1.5 - Custom Lights](#1.5---custom-lights)
- [Section 2 - Using your Stargate](#section-2---using-your-stargate)
    - [2.1 - Dialing the Stargate](#2.1---dialing-the-stargate)
    - [2.2 - Iris / Shield System](#2.2---iris--shield-system)
    - [2.3 - Other Commands](#2.3---other-commands)
    - [2.4 - Menu System](#2.4---menu-system)
    - [2.5 - Technical Information](#2.5---technical-information)
        - [2.5.1 - Server, Communications, Continuity](#2.5.1---server-communications-continuity)
        - [2.5.2 - Addressing System](#2.5.2---addressing-system)
        - [2.5.3 - Failsafes / Limitations](#2.5.3---failsafes--limitations)
- [Section 3 - Stargate Official Addons](#section-3---stargate-official-addons)
    - [3.1 - Death System](#3.1---death-system)
    - [3.2 - Dial Home Devices](#3.2---dial-home-devices)
    - [3.3 - Address Display](#3.3---address-display)
    - [3.4 - Stargate Control Unit](#3.4---stargate-control-unit)
- [Section 4 - Stargate API](#section-4---stargate-api)
    - [4.1 - Incoming API](#4.1---incoming-api)
    - [4.2 - Outgoing API](#4.2---outgoing-api)
- [Section 5 - Online Interface](#section-5---online-interface)
    - [5.1 - Stargate Information Page](#5.1---stargate-information-page)
    - [5.2 - Customizing your Stargate](#5.2---customizing-your-stargate)
    - [5.3 - Controlling your Stargate](#5.3---controlling-your-stargate)
    - [5.4 - Web Profile](#5.4---web-profile)
- [Section 6 - Updating your Stargate](#section-6---updating-your-stargate)
    - [6.1 - Update Policy](#6.1---update-policy)
    - [6.2 - Types of Updates](#6.2---types-of-updates)
    - [6.3 - How to Update](#6.3---how-to-update)
- [Section 7 - Troubleshooting](#section-7---troubleshooting)
    - [7.1 - Common Issues](#7.1---common-issues)
    - [7.2 - Where to Obtain Help](#7.2---where-to-obtain-help)
- [Section 8 - Information](#section-8---information)
    - [8.1 - Disclosure](#8.1---disclosure)
    - [8.2 - Copyright](#8.2---copyright)
    - [8.3 - Credit](#8.3---credit)
    - [8.4 - Current Staff](#8.4---current-staff)

---

**Alteran Stargate**  
*1.1.3*

*In order to receive the latest updates and other important information, be sure that you join
the **Alteran Stargate Network** group. You can also access the forums
at [http://www.alpha-fox.com/community/](http://www.alpha-fox.com/community/).*

---

## Section 1 - Setting up your Stargate

<a id="section-1---setting-up-your-stargate"></a>

### 1.1 - Basic Setup

<a id="1.1---basic-setup"></a>

When you first rez your Stargate, it will provide you with a username and password. Please write that down, because it
is your ticket to both the forums and the [online interface](#section-5---online-interface).

Once your Stargate is rezzed, you simply have to move your Stargate into position. See *Section 1.3* for tips on how to
position your Stargate. If you wish to use a [Dial Home Device](#32---dial-home-devices) with your Stargate, you may rez
one from the folder where you received the Stargate and this user guide. A *Dial Home Device* is a keypad that allows
you to "dial up" glyphs of a target Stargate. Once you push the glyphs and then the center button, it will attempt to
lock and either fail or open up to your destination.

**NOTE:** If you are not the "primary" or first Stargate in your region, you will only be able to contact your Stargate
via the *name* or *alias*. See [Section 1.2](#12---customizing-your-stargate) for more details on renaming your
Stargate, or [Section 2.5.2](#252---addressing-system) for more details on how the addressing system works.

[Back to Top](#top)

---

### 1.2 - Customizing your Stargate

<a id="1.2---customizing-your-stargate"></a>

Once you set up your Stargate, you are ready to go. However, if you want to be able to be contacted using a special word
or want to display a different name for your Stargate on the webpage, you can do this easily in-world. **The in-world
interface is not the only method** of customizing your Stargate; see [Section 5](#section-5---online-interface) for more
details on customizing your Stargate via the online interface.

There are currently two ways to customize your Stargate via the in-world interface:

1. The menu you obtain by touching the Stargate
2. The [Stargate API](#42---outgoing-api)

This section of the guide details the menu-method of customizing your Stargate.

When you click the Stargate, you will obtain a menu. You should see a menu with buttons in the top-right corner of your
screen. All of the customizations you are going to want to do are in the **Settings** portion of the menu, so click that
button. On the next menu that pops up, you have several choices:

- **Random**  
  Toggle whether or not your Stargate will be chosen in a random dial. If you place your Stargate in a region with
  *Direct Teleport* turned off, this will be locked to **No**.

- **Image URL**  
  On the website, your Stargate can be represented by a small *256px by 256px* image. When you click this button, the
  Stargate will respond with a channel that you can say the URL of your image on. Once you respond with your image URL,
  it will be automatically set.

  > **NOTE:** If you do not have your own server to host images from, we recommend
  *Photobucket* ([http://www.photobucket.com/](http://www.photobucket.com/)),
  *Flickr* ([http://www.flickr.com/](http://www.flickr.com/)), or
  *TinyPic* ([http://www.tinypic.com](http://www.tinypic.com)).

- **Shield**  
  Your Stargate is packaged with *4* types of shields. This menu allows you to change between these with a click. The
  following shield types are available:
    - *Shield* — A built-in shield requiring no extra prims on your parcel. It is not animated, but resembles the shield
      seen in **Stargate: Atlantis**.
    - *Rezzed* — A rezzed shield requiring 3 extra prims on your parcel. This is an animated shield with glow added. It
      resembles the shield in **Stargate: Atlantis**.
    - *Iris* — A simple animated iris resembling the iris seen in the *SGC* in **Stargate: SG-1**.
    - *Disabled* — Disables all built-in shields, allowing for possible 3rd-party shields.
      See [Section 4.1](#41---incoming-api) for more information on using the API to create a 3rd-party shield.

- **Listen**  
  Some people like to use their own relays for dial commands. We implemented a way to turn off the channel-0 listen.
  Clicking this button will disable listening on the public-0 channel.
  > **NOTE:** The listen on channel 123 will always be active as a convenience to gate users.

- **Output**  
  Some people like to use their own devices to output what the gate is currently saying. For this purpose, we
  implemented a way to turn off the channel-0 output. Clicking this button will disable output on the public channel.
  > **NOTE:** The output for menu commands (which must be done within range of the gate) will remain always on channel
    0.

- **Name**  
  This button allows you to change the *name* of your Stargate. This name is used to identify your Stargate in the logs,
  on incoming wormholes, and on the website. When you click this button, the Stargate will respond with a channel where
  you can say your Stargate’s name. Once you respond with your name, it is automatically set.

- **Alias**  
  Each Stargate is assigned an alias to make dialing via *direct dial* easier. This alias can be something like "zach's
  house" or "lex's pad." When you click this button, the Stargate responds with a channel where you can say your
  Stargate’s alias. Once you respond, it is automatically set.

[Back to Top](#top)

---

### 1.3 - Tips on Location

<a id="1.3---tips-on-location"></a>

There is nothing more frustrating than coming out of a Stargate in a building where you cannot find your way out, or
appearing in the sky, or coming through backwards. These tips will help you set up your Stargate for the best
experience:

- *Do not place your Stargate in the air*  
  Obviously, if you are making a Spacegate scene, this is unavoidable. However, placing the Stargate high in the air so
  that people fall to their doom is generally bad practice.

- *Place your Stargate in an open area*  
  Teleporting into a location where the exit is not visible is frustrating. Please try to place your Stargate in an open
  area, not a small boxed room with no exit.

- *Keep your Stargate rotated to the North*  
  The Stargates are based on the `llMapDestination` method of teleporting, which does not support the LOOK_AT parameter.
  Because of this, you may appear facing backwards or sideways upon arrival. Placing your gate facing north will ensure
  incoming travelers appear facing outwards from the Stargate.

[Back to Top](#top)

---

### 1.4 - Custom Sounds

<a id="1.4---custom-sounds"></a>

Some people wish to customize the sounds the Stargate plays for various events, such as incoming wormholes, a spinning
ring, or the kawoosh. The following sound labels in the Stargate are open for custom replacement:

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

[Back to Top](#top)

---

### 1.5 - Custom Lights

<a id="1.5---custom-lights"></a>

Your Stargate can adjust the on/off color of the gate lamps via a notecard. In the Stargate’s inventory, you will see a
notecard called **chevrons.config**. It looks like this:

```
Chevron Configuration - Set line 2 to the <r, g, b> for the off color. 
Set line 3 to the <r, g, b> for the on color.
<0, 0, 0>
<1, 1, 1>
```

You **must** keep these lines in the same format. Issuing a `/stargate restart` command after changing this notecard
will save the settings, and the Stargate will “recalibrate” itself with the new colors.

[Back to Top](#top)

---

## Section 2 - Using your Stargate

<a id="section-2---using-your-stargate"></a>

**NOTE:** Any of these commands can be said on either **channel 0** (public) or **channel 123** (for privacy).

### 2.1 - Dialing the Stargate

<a id="2.1---dialing-the-stargate"></a>

Dialing the Stargate is straightforward if you know the proper command. Most dialing is done with the command `/dial`.
This will search all keywords (name, alias, region, addresses) that a Stargate can support.

| **Commands**        |         Alternate |
|---------------------|------------------:|
| **Regular Dial**    |   `/dial` or `/d` |
| **Long Dial** (SGC) | `/sgc` or `/dsgc` |

> **Example:**
>
> - To dial a Stargate of the same type as yours, say `/dial <keyword>` (e.g., `/dial sonamu`).
> - To dial a Pegasus Stargate from a Milkyway gate, say `/dial pegasus <keyword>` (e.g., `/dial pegasus sonamu`).
> - To dial a Milkyway Stargate from a Pegasus gate, say `/dial milkyway <keyword>` (e.g., `/dial milkyway sonamu`).

If you have a Milkyway Stargate, you can also dial using the slower *SGC* style by replacing `/dial` with `/sgc`. This
is where the inner ring rotates freely to each glyph and locks it using the top chevron (chevron 7). It is slower, but
more authentic.

There are two other Stargate networks in Second Life®: **Open Stargate Network** and the **Cleary Stargate Network**. We
are currently focusing on stabilizing our own network, so connections to those are not yet available.

All networks can be replaced by shorter “prefixes”:

| **Network** | **Valid Prefixes** |
|:-----------:|:------------------:|
|  *Pegasus*  |  `pegasus` or `p`  |
| *Milkyway*  | `milkyway` or `mw` |

To dial a gate with a Dial Home Device, you must have the glyph address of the target Stargate (listed on our website
at [http://www.alpha-fox.com/asn/](http://www.alpha-fox.com/asn/)). Or, you can use the glyph display included with the
Stargate.

[Back to Top](#top)

---

### 2.2 - Iris / Shield System

<a id="2.2---iris--shield-system"></a>

Your Stargate is equipped with a shield/iris system, preventing unwanted visitors from teleporting through.

Use these commands to operate the iris/shield:

- **`/stargate raise`** — Raises the gate shield / closes the iris
- **`/stargate lower`** — Lowers the gate shield / opens the iris

You can also use the [Stargate API](#section-4---stargate-api) to control the iris.

If your gate’s iris is closed, you cannot dial into it unless you have an object on the other side that can signal the
iris to open via the API.

[Back to Top](#top)

---

### 2.3 - Other Commands

<a id="2.3---other-commands"></a>

Below are additional commands your gate uses. Some are **private** (owner-only) and some are **public** (anyone can
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

When your Stargate is active, it can relay chat (using the [Stargate API](#section-4---stargate-api)) and region
statistics. The chat buffer is limited to 20 messages every ~4 seconds.

[Back to Top](#top)

---

### 2.4 - Menu System

<a id="2.4---menu-system"></a>

When you click on your Stargate, a menu appears with many available commands. Each menu entry is explained below:

- **Subnova** — Contacts the Alteran Stargate Network HQ.
- **Top Gates** — Lists the top 20 gate names and regions by popularity.
- **Statistics** — Outputs statistics on incoming and outgoing wormholes.
- **Version** — Outputs the current version of your Stargate.
- **Help** — Outputs a quick help message.
- **Settings** — Allows you to [change settings](#12---customizing-your-stargate) in your Stargate.
- **Summary** — Gives a link to the webpage for your Stargate.
- **Controls** — Allows you to give commands such as *Reset*, *Restart*, *Delete*, and *Offline*.
- **Memory** — Dumps the memory levels of every Stargate script (useful for debugging crashes).
- **Report** — Allows you to report a Stargate for an SSoP violation.
- **Rate** — Allows you to rate a Stargate location on a scale of 0-5.

[Back to Top](#top)

---

### 2.5 - Technical Information

<a id="2.5---technical-information"></a>

This section is more technical. (Time to sound like Samantha Carter.)

#### 2.5.1 - Server, Communications, Continuity

<a id="2.5.1---server-communications-continuity"></a>

Each Stargate registers itself on a MySQL database using PHP. The gate backend server, named *Chimera* and hosted on
the [Subnova Network](http://www.subnova.com/), handles most communications and data, making in-world gates mostly
“dumb-terminals.” Unlike the original *Daedalus* server, *Chimera* is UPS-backed with a static IP address.

Communications are handled via **AFVI** (Alpha-Fox Virtual Interface) servers developed by Alpha-Fox, instead of XML-RPC
or email-based solutions. The **AFVI** system sends out lslmails from queries in our SQL database. It’s fairly fast (~3
seconds round trip), and verifiable (we can confirm receipt).

Each Stargate checks in every **5 minutes**, with status changes registered as soon as they happen. If a gate fails to
check in for more than 6 minutes, the server marks it offline. If it checks in again, it returns online with all
previous settings. The dead gate list is cleared every 72 hours.

#### 2.5.2 - Addressing System

<a id="2.5.2---addressing-system"></a>

Each region on the grid is given **two** addresses: a *native* address and a *cross-network* address. Your Stargate
always has the same address for other gates of the same type to dial, and a cross-network address for gates of the other
type.

Each Stargate also has an **SGC-ID**, similar to show-based addresses like P4X-639. This is unique and can also be used
to direct dial your gate.

**Milkyway Stargates** have 39 symbols (index 0-38). Glyph 0 is the point of origin (always the last glyph in an
address). On a standard Milkyway DHD, there are 38 symbols (1-38) plus the big orange button for the origin.

Below is the Milkyway glyph layout (0-38). *(Images shown in a grid; each number is the glyph index.)*

| ![Glyph 0](http://images.alpha-fox.com/asn/glyphs/milkyway/0.gif) **0** | ![Glyph 1](http://images.alpha-fox.com/asn/glyphs/milkyway/1.gif) **1** | ![Glyph 2](http://images.alpha-fox.com/asn/glyphs/milkyway/2.gif) **2** | ![Glyph 3](http://images.alpha-fox.com/asn/glyphs/milkyway/3.gif) **3** | ![Glyph 4](http://images.alpha-fox.com/asn/glyphs/milkyway/4.gif) **4** | ![Glyph 5](http://images.alpha-fox.com/asn/glyphs/milkyway/5.gif) **5** | ![Glyph 6](http://images.alpha-fox.com/asn/glyphs/milkyway/6.gif) **6** | ![Glyph 7](http://images.alpha-fox.com/asn/glyphs/milkyway/7.gif) **7** | ![Glyph 8](http://images.alpha-fox.com/asn/glyphs/milkyway/8.gif) **8** |
|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|

| ![Glyph 9](http://images.alpha-fox.com/asn/glyphs/milkyway/9.gif) **9** | ![Glyph 10](http://images.alpha-fox.com/asn/glyphs/milkyway/10.gif) **10** | ![Glyph 11](http://images.alpha-fox.com/asn/glyphs/milkyway/11.gif) **11** | ![Glyph 12](http://images.alpha-fox.com/asn/glyphs/milkyway/12.gif) **12** | ![Glyph 13](http://images.alpha-fox.com/asn/glyphs/milkyway/13.gif) **13** | ![Glyph 14](http://images.alpha-fox.com/asn/glyphs/milkyway/14.gif) **14** | ![Glyph 15](http://images.alpha-fox.com/asn/glyphs/milkyway/15.gif) **15** | ![Glyph 16](http://images.alpha-fox.com/asn/glyphs/milkyway/16.gif) **16** | ![Glyph 17](http://images.alpha-fox.com/asn/glyphs/milkyway/17.gif) **17** |
|-------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|

| ![Glyph 18](http://images.alpha-fox.com/asn/glyphs/milkyway/18.gif) **18** | ![Glyph 19](http://images.alpha-fox.com/asn/glyphs/milkyway/19.gif) **19** | ![Glyph 20](http://images.alpha-fox.com/asn/glyphs/milkyway/20.gif) **20** | ![Glyph 21](http://images.alpha-fox.com/asn/glyphs/milkyway/21.gif) **21** | ![Glyph 22](http://images.alpha-fox.com/asn/glyphs/milkyway/22.gif) **22** | ![Glyph 23](http://images.alpha-fox.com/asn/glyphs/milkyway/23.gif) **23** | ![Glyph 24](http://images.alpha-fox.com/asn/glyphs/milkyway/24.gif) **24** | ![Glyph 25](http://images.alpha-fox.com/asn/glyphs/milkyway/25.gif) **25** | ![Glyph 26](http://images.alpha-fox.com/asn/glyphs/milkyway/26.gif) **26** |
|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|

| ![Glyph 27](http://images.alpha-fox.com/asn/glyphs/milkyway/27.gif) **27** | ![Glyph 28](http://images.alpha-fox.com/asn/glyphs/milkyway/28.gif) **28** | ![Glyph 29](http://images.alpha-fox.com/asn/glyphs/milkyway/29.gif) **29** | ![Glyph 30](http://images.alpha-fox.com/asn/glyphs/milkyway/30.gif) **30** | ![Glyph 31](http://images.alpha-fox.com/asn/glyphs/milkyway/31.gif) **31** | ![Glyph 32](http://images.alpha-fox.com/asn/glyphs/milkyway/32.gif) **32** | ![Glyph 33](http://images.alpha-fox.com/asn/glyphs/milkyway/33.gif) **33** | ![Glyph 34](http://images.alpha-fox.com/asn/glyphs/milkyway/34.gif) **34** | ![Glyph 35](http://images.alpha-fox.com/asn/glyphs/milkyway/35.gif) **35** |
|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|

| ![Glyph 36](http://images.alpha-fox.com/asn/glyphs/milkyway/36.gif) **36** | ![Glyph 37](http://images.alpha-fox.com/asn/glyphs/milkyway/37.gif) **37** | ![Glyph 38](http://images.alpha-fox.com/asn/glyphs/milkyway/38.gif) **38** |
|----------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|

**Pegasus Stargates** have 36 glyphs. To keep the DHD symmetrical, it has 36 buttons, meaning even the point of origin (
glyph 0) is a button. So you must press glyph 0 before pressing the big blue center button.

Pegasus glyph layout (0-35). *(Again, images in a grid; each number is the index.)*

| ![Glyph 0](http://images.alpha-fox.com/asn/glyphs/pegasus/0.gif) **0** | ![Glyph 1](http://images.alpha-fox.com/asn/glyphs/pegasus/1.gif) **1** | ![Glyph 2](http://images.alpha-fox.com/asn/glyphs/pegasus/2.gif) **2** | ![Glyph 3](http://images.alpha-fox.com/asn/glyphs/pegasus/3.gif) **3** | ![Glyph 4](http://images.alpha-fox.com/asn/glyphs/pegasus/4.gif) **4** | ![Glyph 5](http://images.alpha-fox.com/asn/glyphs/pegasus/5.gif) **5** | ![Glyph 6](http://images.alpha-fox.com/asn/glyphs/pegasus/6.gif) **6** | ![Glyph 7](http://images.alpha-fox.com/asn/glyphs/pegasus/7.gif) **7** | ![Glyph 8](http://images.alpha-fox.com/asn/glyphs/pegasus/8.gif) **8** |
|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|

| ![Glyph 9](http://images.alpha-fox.com/asn/glyphs/pegasus/9.gif) **9** | ![Glyph 10](http://images.alpha-fox.com/asn/glyphs/pegasus/10.gif) **10** | ![Glyph 11](http://images.alpha-fox.com/asn/glyphs/pegasus/11.gif) **11** | ![Glyph 12](http://images.alpha-fox.com/asn/glyphs/pegasus/12.gif) **12** | ![Glyph 13](http://images.alpha-fox.com/asn/glyphs/pegasus/13.gif) **13** | ![Glyph 14](http://images.alpha-fox.com/asn/glyphs/pegasus/14.gif) **14** | ![Glyph 15](http://images.alpha-fox.com/asn/glyphs/pegasus/15.gif) **15** | ![Glyph 16](http://images.alpha-fox.com/asn/glyphs/pegasus/16.gif) **16** | ![Glyph 17](http://images.alpha-fox.com/asn/glyphs/pegasus/17.gif) **17** |
|------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|

| ![Glyph 18](http://images.alpha-fox.com/asn/glyphs/pegasus/18.gif) **18** | ![Glyph 19](http://images.alpha-fox.com/asn/glyphs/pegasus/19.gif) **19** | ![Glyph 20](http://images.alpha-fox.com/asn/glyphs/pegasus/20.gif) **20** | ![Glyph 21](http://images.alpha-fox.com/asn/glyphs/pegasus/21.gif) **21** | ![Glyph 22](http://images.alpha-fox.com/asn/glyphs/pegasus/22.gif) **22** | ![Glyph 23](http://images.alpha-fox.com/asn/glyphs/pegasus/23.gif) **23** | ![Glyph 24](http://images.alpha-fox.com/asn/glyphs/pegasus/24.gif) **24** | ![Glyph 25](http://images.alpha-fox.com/asn/glyphs/pegasus/25.gif) **25** | ![Glyph 26](http://images.alpha-fox.com/asn/glyphs/pegasus/26.gif) **26** |
|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|

| ![Glyph 27](http://images.alpha-fox.com/asn/glyphs/pegasus/27.gif) **27** | ![Glyph 28](http://images.alpha-fox.com/asn/glyphs/pegasus/28.gif) **28** | ![Glyph 29](http://images.alpha-fox.com/asn/glyphs/pegasus/29.gif) **29** | ![Glyph 30](http://images.alpha-fox.com/asn/glyphs/pegasus/30.gif) **30** | ![Glyph 31](http://images.alpha-fox.com/asn/glyphs/pegasus/31.gif) **31** | ![Glyph 32](http://images.alpha-fox.com/asn/glyphs/pegasus/32.gif) **32** | ![Glyph 33](http://images.alpha-fox.com/asn/glyphs/pegasus/33.gif) **33** | ![Glyph 34](http://images.alpha-fox.com/asn/glyphs/pegasus/34.gif) **34** | ![Glyph 35](http://images.alpha-fox.com/asn/glyphs/pegasus/35.gif) **35** |
|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|

Address assignment is handled by *Andromeda* on the [Subnova Network](http://www.subnova.com/) and can take about **1
day** to generate addresses for the entire grid. Because of this addressing system, only **one** gate per type, per
region is addressable by glyph. You can still place more gates in the same region; they just cannot be dialed via glyph
address—only by *name* or *alias*.

You can apply for an admin-assigned "forward address" if you want a canonical address from the show, for instance. To do
this, submit a request in the [Help Desk](http://www.alpha-fox.com/support/tickets/). Include your gate location and
desired address.

#### 2.5.3 - Failsafes / Limitations

<a id="2.5.3---failsafes--limitations"></a>

We included some canonical failsafes and limitations:

- Only one Stargate of the same type can be active at a time in a region. If one is active, another of the same type
  cannot dial or receive.
- If one gate is dialing and the primary Stargate in that region gets an incoming, the primary gate always “wins.”
- Likewise, if one gate is dialing and the primary gate attempts to dial out, the primary gate always “wins.”
- This ensures canonical behavior and also helps avoid scripting or sim-performance issues.

[Back to Top](#top)

---

## Section 3 - Stargate Official Addons

<a id="section-3---stargate-official-addons"></a>

### 3.1 - Death System

<a id="3.1---death-system"></a>

**Death** is an addon by *Alpha-Fox* that allows the unstable vortex and other lethal actions of the Stargate to kill
users on safe land. If you deed this addon to the parcel group and turn it on, the gate will kill avatars caught in the
unstable vortex.

This addon also has an API so people can integrate it with their own scripts. It listens throughout the entire region,
so only one Death system needs to be rezzed per group/owner.

> **UNDER NO CIRCUMSTANCES SHOULD YOU DEED THE STARGATE TO YOUR LAND**  
> *(Only the Death System should be deeded, if used.)*

[Back to Top](#top)

---

### 3.2 - Dial Home Devices

<a id="3.2---dial-home-devices"></a>

The Stargate package includes 4 DHDs (Dial Home Devices):

- **Milkyway** — A lite version of the OS DHD by [OS Labs](http://www.oslabs.info/).
- **Pegasus** — A lite version of the OS DHD by [OS Labs](http://www.oslabs.info/).
- **Tollan** — A *concept* DHD built by Lex Mars and scripted by Zachary Carter.
- **Forerunner** — Another *concept* DHD built by Lex Mars and scripted by Zachary Carter.

These DHDs allow direct glyph entry to dial a destination. After entering the 6 (or 7) glyphs and pressing the center
button, the gate will spin up and, hopefully, lock. See *Sections 1 and 2* of this guide for more info.

DHDs only work on Stargates you own. They also listen to all gates in the region, so having multiple same-network gates
of your own may cause confusion.

[Back to Top](#top)

---

### 3.3 - Address Display

<a id="3.3---address-display"></a>

The Address Display is a free way to see glyph addresses without using the website. Rez this object and use:

- `/lookup <network keyword>`
- `/clear`
- `/setnetwork <network>`

*network* is either `milkyway` or `pegasus`. If none is provided to `/lookup`, it uses the network set by `/setnetwork`.
By default, it uses `milkyway`.

`/clear` simply clears the display. Changing the display prim names (1-7) may break it.

When rezzed, it listens to your gate, lighting up the address on incoming/outgoing, and showing **your** Stargate’s
address when idle:

- **White** = Looked-up address
- **Orange / Aqua** = Milkyway / Pegasus native address (your Stargate’s address)
- **Red / Blue** = Incoming / Outgoing wormhole

[Back to Top](#top)

---

### 3.4 - Stargate Control Unit

<a id="3.4---stargate-control-unit"></a>

The **Stargate Control Unit** is like “The Poor Man’s DHD.” It allows commands such as Reset, Shield, etc., plus a
directory of preset dial addresses. The model is based on the control unit the Ancients used in **3x10 The Return Pt. 1
** of *Stargate: Atlantis*.

All commands are accessed by touching the device and using the menus:

- **Control** — Shield, reset, offline, test incoming/outgoing, random dial, etc.
- **Directory** — Add addresses and dial previously stored ones.
- **Options** — Toggle verbosity, play sounds, ring spin, and more.

The side color indicates which gate network it’s controlling (*aqua* for Pegasus, *orange* for Milkyway). The small
screen at top shows the current status.

This device only works on Stargates you own and may conflict if you have multiple same-network gates in the region.

[Back to Top](#top)

---

## Section 4 - Stargate API

<a id="section-4---stargate-api"></a>

The Stargates have an **Application Programming Interface (API)** to interface in both basic and advanced ways. There
are two API levels: **Public** and **Private**. **Public** commands can be submitted by anyone, while **Private**
commands only work for the Stargate’s owner.

### 4.1 - Incoming API

<a id="4.1---incoming-api"></a>

These are commands you can *send* to the gate to control it. The channels are:

- **Pegasus**: `-804000`
- **Milkyway**: `-904000`

Below are the recognized commands. **Bold** indicates **public** (works for anyone within 20m unless it’s the owner, who
has no distance limit). *Italic* indicates **private** (owner-only).

<a hidden="// @formatter:off" ></a>

| Command                               | Description                                                                                                                                         |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| ```dial|<1/0>|<glyph>```               | Dials a glyph on your Stargate with a spinval of 1 / 0 (whether inner ring spins)                                                                   |
| ```stargate status```                 | Returns the status of the Stargate                                                                                                                  |
| ```send chatter|<name>|<msg>|<1/0>```   | Sends chatter through an active gate. The variable at the end will let you keep the wormhole open if set to 1                                        |
| ```stargate version```                | Returns the version of the Stargate                                                                                                                 |
| ```stargate address```                | Returns *native and cross-network* addresses                                                                                                      |
| ```stargate name```                   | Returns the name of the Stargate                                                                                                                    |
| ```stargate alias```                  | Returns the alias of the Stargate                                                                                                                   |
| ```stargate probe```                  | Probes the target Stargate (outgoing only)                                                                                                          |
| ```lookup|<net>|<kw>```                | Looks up a Stargate. You can replace network with * for wildcard                                                                                    |
| ```directdial|<net>|<kw>|<2/1/0>```      | Dials a Stargate using direct dial with a spinval of 1 / 0 (whether inner ring spins - when you set it to "2" it does a forced wormhole). You can replace network with * for wildcard. |
| ```stargate emp```                    | Sends a pulse through the wormhole extending the open time for 30 seconds                                                                           |
| ```interference```                    | Causes the gate to flicker and make a zap noise                                                                                                     |
| ```raise shield```                    | Raises the shield on your gate                                                                                                                      |
| ```lower shield```                    | Lowers the shield on your gate                                                                                                                      |
| ```delete stargate```                 | Deletes your gate                                                                                                                                   |
| ```offline stargate```                | Turns your gate offline                                                                                                                             |
| ```online stargate```                 | Turns your gate online                                                                                                                              |
| ```reset stargate```                  | Resets your gate                                                                                                                                    |
| ```restart stargate```                | Restarts your gate                                                                                                                                  |
| ```shutdown wormhole```               | Shuts down an active wormhole                                                                                                                       |
| ```cut wormhole```                    | Cuts an active wormhole                                                                                                                             |
| ```test stargate```                   | Tests the chevron lamps on your gate.                                                                                                               |
| ```test stargate outgoing```          | Simulates an outgoing wormhole                                                                                                                      |
| ```test stargate incoming```          | Simulates an incoming wormhole                                                                                                                      |
| ```set name|<name>```                 | Sets the name of your gate                                                                                                                          |
| ```set alias|<alias>```               | Sets the alias of your gate                                                                                                                         |
| ```set image url|<url>```             | Sets the image URL of your gate                                                                                                                     |
| ```ring speed|<speed>```              | Changes the inner ring speed on Milkyway gates. Needs to be sent at the beginning of every dial.                                                     |
| ```public listen|<1/0>```             | Turns on / off the listen on channel 0 for commands.                                                                                              |
| ```public output|<1/0>```             | Turns on / off the verbose output of the Stargate                                                                                                 |
| ```random list|<1/0>```               | Turns on / off random dial listing                                                                                                                  |

<a hidden="// @formatter:on" ></a>

[Back to Top](#top)

---

### 4.2 - Outgoing API

<a id="4.2---outgoing-api"></a>

The *outgoing* API are events the Stargate *sends out*. The channels are:

- **Pegasus**: `-805000`
- **Milkyway**: `-905000`

Below are the typical responses (they may change over time):

<a hidden="// @formatter:off" ></a>

| Command | Description |
|---------|-------------|
| ```stargate reset``` | Gate has been reset |
| ```status|<outgoing/incoming/idle/offline/dialing>``` | Gate status has changed. |
| ```shield|<0/1>``` | Gate shield has changed |
| ```ping``` | Gate pinged to the server |
| ```dial lookup|<succ/fail>|<addr>|<spin>|<region >|<pos>|<nw>|<name>|<alias>|<owner>|<sgc id>``` | Return from a directdial API command |
| ```search lookup|<succ/fail>|<native>|<cross>|<region >|<pos>|<nw>|<name>|<alias>|<owner>|<sgc id>``` | Return from a lookup API command |
| ```chevron <#> encoded``` | Chevron has lit up (dhd) |
| ```chevron <#> engaged``` | Chevron has lit up (incoming) |
| ```chevron <#> locked``` | Chevron has lit up (long dial) |
| ```dial <succ/fail>|<region>|<pos>|<nw>| <name>|<alias>|<owner>|<sgc id>|<rot>``` | Stargate has attempted to lock an address |
| ```stargate close``` | Stargate has shutdown |
| ```stargate cut``` | Stargate has cut power |
| ```wormhole collision|<type>|<uuid>``` | Collision with the event horizon |
| ```stargate restart``` | Gate has restarted |
| ```incoming wormhole|<region>|<pos>|<owner name>|<name>|<alias>|<address>|<sgc id>``` | Incoming wormhole |
| ```stargate version|<version>``` | Gate version output |
| ```stargate address|<native>|<cross>``` | Gate address output |
| ```random listing|<1/0>``` | Random dial listing |
| ```stargate delete``` | Stargate deleting |
| ```public listen|<1/0>``` | Channel 0 listen |
| ```shield type|<irisrezzed/shield/disabled>``` | Change shield type |
| ```set name|<successful/failed>|reason``` | Name changed |
| ```set alias|<successful/failed>|reason``` | Alias changed |
| ```set image url|<successful/failed>|reason``` | Image changed |
| ```stargate registered``` | Gate registered |
| ```emp pulse sent``` | EMP pulse sent |
| ```invalid api command passed``` | Invalid command |
| ```stargate name|<name>``` | Stargate name output |
| ```stargate alias|<alias>``` | Stargate alias output |
| ```chatter|<name>|<msg>``` | Wormhole chatter. Ignore names starting with _. |
| ```probe|<succ/fail>|<fps>|<time>|<parcel name>|<parcel desc>|<agent count>``` | Target gate probe |
| ```stargate test``` | Chevron lamp test |
| ```stargate test incoming``` | Incoming wormhole simulation |
| ```stargate test outgoing``` | Outgoing wormhole simulation |
| ```interference``` | Experiencing interference |
| ```wormhole fataility|<type>|<uuid>|<what>``` | The wormhole has killed |
| ```target shield raised``` | Target shield raised |
| ```target shield lowered``` | Target shield lowered |
| ```destination|<region>|<pos>|<rot>``` | Wormhole destination changed. "--" is no destination. |
| ```prompt|<msg>``` | Stargate chat outputs |
| ```top gates|<name,name,name>``` | Top 20 gates by popularity |
| ```gate statistics|<inc>|<out>|<total>``` | Basic statistics about the gate |
| ```target wormhole collision|<type>|<uuid>``` | Wormhole collision on the connected Stargate (not yours) |
| ```http error|<error>``` | An error with the http_response |
| ```stargate open``` | The Stargate has opened |
| ```clearing buffer``` | The buffer of the Stargate is being cleared (all of the scripts being reset) |
| ```chatter saved``` | Chatter has been saved for target gate |
| ```wormhole extended``` | Results from emp command or emp flag on chatter. |

<a hidden="// @formatter:on" ></a>

[Back to Top](#top)

---

## Section 5 - Online Interface

<a id="section-5---online-interface"></a>

Alteran Stargates have an online interface at [http://www.alpha-fox.com/asn/](http://www.alpha-fox.com/asn/). You can
view, customize, and control your Stargates in one place. You’ll need to log in with your Second Life avatar name and
the password the Stargate gave you on first rez.

> **NOTE:** If you’ve forgotten your password, use the **`/stargate resetpass`** command.

### 5.1 - Stargate Information Page

<a id="5.1---stargate-information-page"></a>

On the **My Stargates** page, you can view all Stargates you have rezzed. Clicking a specific gate shows detailed info,
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

[Back to Top](#top)

---

### 5.2 - Customizing your Stargate

<a id="5.2---customizing-your-stargate"></a>

You can also customize:

- Name
- Alias
- Image URL
- Description
- Random Listing

Follow the instructions on your Stargate’s info page to customize.

[Back to Top](#top)

---

### 5.3 - Controlling your Stargate

<a id="5.3---controlling-your-stargate"></a>

Using the online interface, you can remotely control your Stargate:

- Reset / Restart
- Raise / Lower Shield
- Set Offline
- Delete
- Force Incoming Test
- Force Outgoing Test
- Send a message to the gate

Just follow the on-page instructions for your specific Stargate.

[Back to Top](#top)

---

### 5.4 - Web Profile

<a id="5.4---web-profile"></a>

We also provide a way to show a “profile” of your Stargates in your Second Life Web Profile. Use the URL (replacing
`First_Last` with your SL name):

```
http://www.alpha-fox.com/asn/profile/First_Last/
```

For example:  
`http://www.alpha-fox.com/asn/profile/Zachary_Carter/`

[Back to Top](#top)

---

## Section 6 - Updating your Stargate

<a id="section-6---updating-your-stargate"></a>

### 6.1 - Update Policy

<a id="6.1---update-policy"></a>

We try to announce major code updates that might affect gate performance. We cannot guarantee network uptime, so we may
take the network down for emergency maintenance. We will attempt to notify the in-world group and forums if a takedown
occurs.

[Back to Top](#top)

---

### 6.2 - Types of Updates

<a id="6.2---types-of-updates"></a>

Stargates will be updated periodically. Updates can vary:

- **No new Stargate** needed (e.g., a new menu function, API command, or minor fix).
- **Script update only** (e.g., a main script in the parent prim is updated, delivered via an updater orb).
- **Full model replacement** (e.g., new model, textures, or major chevron/ring script changes).

[Back to Top](#top)

---

### 6.3 - How to Update

<a id="6.3---how-to-update"></a>

Depending on the update type:

- **Backend fix only:** Usually just do `/stargate reset`.
- **Code update:** Rez the provided update orb near your Stargate and click it. It will update automatically, then
  self-delete.
- **Full model update:** Rez the update orb; it will replace the entire gate model and transfer settings for you.

[Back to Top](#top)

---

## Section 7 - Troubleshooting

<a id="section-7---troubleshooting"></a>

### 7.1 - Common Issues

<a id="7.1---common-issues"></a>

Here are frequently asked questions:

**Q:** My Stargate froze mid-dial, or has been open a long time (over 38 minutes).  
**A:** Usually a `/stargate reset` fixes it; at worst, `/stargate restart`.

---

**Q:** The Stargate fails repeatedly when dialing another Stargate in the same region!  
**A:** A Stargate cannot dial another Stargate of the same type in the same region. This follows the TV show limitation.

---

**Q:** My Stargate failed to dial because another Stargate in my region was active. Why?  
**A:** If one gate is active, no other same-type gate in the region can dial or receive. Again, this is a limitation
from the show.

---

**Q:** Why don’t we teleport immediately upon colliding with the event horizon?  
**A:** Scripting limitations; we rely on `llMapDestination`. When `llTeleportAgent` becomes available, we will integrate
it.

---

**Q:** Can you automatically update our Stargates? Do they self-update?  
**A:** We have a method for pushing updates, but it’s not feasible for us to update all Stargates manually. You must
update your own. Get the latest release at [http://www.alpha-fox.com/asn/get/](http://www.alpha-fox.com/asn/get/).

---

**Q:** Where can I get a Stargate?  
**A:** [http://www.alpha-fox.com/asn/get/](http://www.alpha-fox.com/asn/get/).

---

**Q:** Is there a “Premium Mode” or any fees for using the Stargate?  
**A:** No. Our Stargates are 100% free. Donations are appreciated but do not affect functionality.

---

**Q:** Where can I get a DHD or other Stargate addons?  
**A:** Try [OS Labs](http://www.oslabs.info/) or XStreet SL/Apez searching for “stargate.” We do not officially support
third-party addons beyond those in our package. You can also check
our [Script Library forum](http://www.alpha-fox.com/community/forum.php?id=8).

---

**Q:** When is feature *xyz* coming, or bug *abc* going to be fixed?  
**A:** Report features/bugs in our forums. We’ll post updates on them there.

- Bug Reports: [http://www.alpha-fox.com/community/forum.php?id=7](http://www.alpha-fox.com/community/forum.php?id=7)
- Feature
  Requests: [http://www.alpha-fox.com/community/forum.php?id=5](http://www.alpha-fox.com/community/forum.php?id=5)

[Back to Top](#top)

---

### 7.2 - Where to Obtain Help

<a id="7.2---where-to-obtain-help"></a>

1. **Read the user guide** (this document).
2. **Ask in the Alteran Stargate Network group** in-world.
3. **Read the Forums** to see if the issue is already answered.
4. **Post** in the forums if you don’t see your issue.
5. **File a [support ticket](http://www.alpha-fox.com/support/tickets/)** — we aim to respond quickly.
6. If all else fails, contact an [administrator or staff](#84---current-staff) of the Alteran Stargate Network.

See also: [http://www.alpha-fox.com/support/](http://www.alpha-fox.com/support/)

[Back to Top](#top)

---

## Section 8 - Information

<a id="section-8---information"></a>

### 8.1 - Disclosure

<a id="8.1---disclosure"></a>

The right to own a Stargate is a *privilege*, not a right. Network administrators reserve the right to remove that
privilege at any time, for any or no reason.

[Back to Top](#top)

---

### 8.2 - Copyright

<a id="8.2---copyright"></a>

“Alteran Stargate Network” is a virtual Stargate Network in Second Life® and is not affiliated with MGM Television
Entertainment, Stargate Productions, Showtime Networks, Inc., or NBC/Universal. Our usage is for fan-based promotion of
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

[Back to Top](#top)

---

### 8.3 - Credit

<a id="8.3---credit"></a>

This Stargate system is the product of many people’s efforts:

- **Wes Keynes** — Provided ideas for direct dialing, version indexing, etc. (Cleary Network).
- **Mintopia Ambassador** — Original spark for the first Stargate network.
- **Reyo Neutra** — Creator of the original (retired) model for Mintopia’s Stargate.
- **Geordie Boffin** — Creator of original textures on the first Mintopia Stargate.
- **Lex Mars** — New gate size, textures, sounds, diameter; coded Pegasus ring movement.
- **Wolfie Waves** — Creator of Arcturus 4.0 gate model, which was adapted to create Alteran 1.0. Also wrote the
  original help guide.
- **Kirby Figtree** — Located [David Gian-Cursio](http://web.mac.com/david_of_mac/) for horizon/texture resources.
- **Zwagoth Klaar** — Helped with new PHP code, SQL data storage methods.
- **Kegan Loon** — Concept of the “Automatic Map” system in 2006.
- **Peter Lameth** — Wrote the original code for the first network; we wouldn’t be here without it.
- **Ash Qin** — Provided concept of using the owner-UUID in URLs for blacklisting.
- **Jandav Auer** — Rewrote event horizon collision logic to avoid repeated kills.

[Back to Top](#top)

---

### 8.4 - Current Staff

<a id="8.4---current-staff"></a>

The Alteran Stargate Network is managed by a diverse team:

- **Zachary Carter** — Founder; programmed most backend and frontend systems.
- **Lex Mars** — Skilled texture artist, builder, and programmer; keeps the model close to canon.
- **Wolfie Waves** — Builder/texture artist; created the Alteran Stargate DHD and the OS DHD.
- **Peter Lameth** — Original network co-creator; helps with support management; runs Eternal Calm Estate.
- **Ash Qin** — Programmer focusing on encryption and other dev tasks; owner of [Quickfox](http://www.quickfox.net/).

[Back to Top](#top)

---

**Zachary Carter**  
*Copyright 2008 Alteran Stargate Network*  
[http://www.alpha-fox.com/asn/](http://www.alpha-fox.com/asn/)

This manual was last updated on 15 November 2008.
