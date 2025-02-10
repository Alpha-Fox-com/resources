<h2>1.1.3</h2>
<ul>
<li>Fixed an "extreme load bug" on our servers.</li>
</ul>
<h2>1.1.2</h2>
<ul>
<li>You no longer get erroneous "status|offline" when API commands from far away are given.</li>
<li>Fixed default shields for forerunner, pegasus, and tollan.</li>
<li>You now get a "chevron 1 encoded" ... damn if() statments.</li>
</ul>
<h2>1.1.1</h2>
<ul>
<li>Fixed shield status so that it is updated server side as well as gate side.</li>
<li>Removed versioning from the gate names -- makes updates easier and less confusing when your gate says "Alteran Stargate 1.0: Your Stargate version is 1.1"</li>
</ul>
<h2>1.1</h2>
<ul>
<li><strong>Added in support for touch distance limitation. Currently you must be within 20 meters to use your gate menu.</strong></li>
<li><strong>Added in support for region agent count to the probe return.</strong></li>
<li><strong>Added support for gates on access list / group limited parcels to not show in random.</strong></li>
<li>Fixed the event horizon (rewrite by Jandav Auer) to properly detect collisions / death.</li>
<li>Fixed control units in Accessories package.</li>
<li>Added an object that will allow people to put "Gate Distributors" on their property.</li>
<li>Rewrote parser.lsl and interface.lsl to combine the two and reduce script time.</li>
<li>Rewrote connection.lsl and core.lsl to combine the two to reduce script time</li>
<li>The gate will no longer revert to "online" after an unintentional reset.</li>
<li>Gate errors will no longer be spammed. They are set to only show once.</li>
</ul>
<h2>1.0</h2>
<p><em>Same as the release candidate before, compiled to the Mono runtime engine.</em></p>
<h2>Release Candidate 4 Revision 2</h2>
<ul>
<li>Fixed a bug in which you would map to xx|xx coordinates.</li>
<li>Fixed a bug where the Event Horizon would not kill you without getting a destination first.</li>
<li>Fixed a bug in 404 error handling.</li>
</ul>
<h2>Release Candidate 4</h2>
<p><strong><em>Please note that this should be the last RC gate before the big 1.0 release. Please report all bugs found to the forums for final bug fix.</em></strong></p>
<ul>
  <li><em>Finally</em> fixed quick wormholes.</li>
  <li>Made adjustments to the kawoosh that will now cause death. You can now re-enable Death.</li>
  <li>Changed the way incoming connections are handled in order to send a more reliable destination. You should not get wormholes with &quot;no destination&quot; anymore.</li>
  <li>Made the shield hollow larger for Wolfie because he whined for it.</li>
  <li>Fixed the bug where cut / close wormhole would get responses on pegasus/forerunner/tollan gates.</li>
</ul>
<h2>Release Candidate 3</h2>
<p><strong><em>This code release marked the hold of support for the Open Stargate Network.</em></strong></p>
<ul>
  <li>Fixed incoming wormhole handling to prevent &quot;quick wormholes&quot;</li>
  <li>Made some adjustments to the kawoosh that should prevent fake kills.</li>
  <li>Added a handler to handle 499 and 500 HTTP errors.</li>
  <li>Added the ability to switch the gates via the script to dev / rel codebases.</li>
  <li>Added the addslashes() command to the backend to prevent any MySQL errors.</li>
  <li>Removed the log_data function from the backend to increase speeds.</li>
  <li>Optimized some PHP code to increase speeds.</li>
  <li>Fixed typos in various backend messages.</li>
  <li>Added 'rot' to the end of the dial_successful API response.</li>
</ul>
<h2>Release Candidate 2</h2>
<ul>
  <li>Updated failsafe time to account for slower sims booting.</li>
  <li>Changed boot message to be smaller and more to-the-point</li>
  <li>(somehow) fixed the Event Horizon to kill people on Kawoosh.</li>
  <li>Fixed the DHDs to not repeat symbols when getting an incoming during dial-out.</li>
  <li>Fixed the "Rate" function to give a proper response</li>
  <li>Fixed the "quick" wormholes. A bug in the registration was causing the first wormhole after registration to be bad.</li>
</ul>
<h2>Release Candidate 1</h2>
<p><strong><em>This code release marked the end of support for the Cleary Stargate Network.</em></strong></p>
<p><em>The changelog for this gate version was lost, but preparations were made for the RC1 release.</em></p>
<h2>0.10.0 Beta</h2>
<ul>
  <li><strong>Added glow to the chevrons in order to give a better effect (all models).</strong></li>
  <li><strong>Added light emit to event horizon.</strong></li>
  <li><strong>New shield / iris impact sounds.</strong></li>
  <li><strong>Glow control on the built-in shield.</strong></li>
  <li>Changed the behaviour on HTTP errors -- no longer plays any sounds or effects but only outputs errors on the API.</li>
  <li>Added status definitions to the gate manual.</li>
  <li>Fixed messages to death including and extra &quot;by&quot;.</li>
  <li>Fixed the AFVI server communication to not crash servers.</li>
  <li>Fixed gate crash issue - had to do with improper handling of responses in core.lsl.</li>
  <li>Fixed the biggest bug in Alteran / Arcturus History. The Milkyway inner ring now stops on the glyph in <em>both</em> directions!</li>
  <li>Changed core aspects of the Stargate in order to clean up code and make the overall changes faster. Also introduces the "buffer reset" feature.</li>
  <li>Shield system is cleaner -- has the ability to be controlled via the &quot;core&quot; script instead of just switching script states on / off.</li>
  <li>Event horizon has been rewritten to cope with the changes in Havok 4, as well as fix some death issues.</li>
</ul>
<h2>0.9.12 Beta</h2>
<ul>
  <li>Fixed the gate radio.</li>
</ul>
<h2>0.9.11 Beta</h2>
<ul>
  <li>Fixed the gate to send 'idle' at the end of wormholes.</li>
  <li>Fixed the updater to not error when trying to do a &quot;script&quot; update.</li>
  <li>Fixed the updater to allow Zachary to update gates.</li>
</ul>
<h2>0.9.10 Beta</h2>
<ul>
  <li><strong>Added the link to the Stargate Standards of Placement page upon registration.</strong></li>
  <li><strong>Added &quot;Memory&quot; button to the menu to report free memory in every script.</strong></li>
  <li><strong>Added the Death API for people to adapt products to use Death.</strong></li>
  <li>Changed the code to spread type.core into type.core and type.api.</li>
  <li>Improved the menu interface by moving commands into &quot;Controls&quot; submenu.</li>
  <li>Fixed <em>target wormhole collision</em> to have the type in the end of the response.</li>
  <li>Improved Death by adding more checks and making the system itself faster. The Death object itself can now turn on / off.</li>
  <li>The Stargate no longer mis-kills people. The checks in the event horizon itself are much smarter.</li>
  <li>The checksum checks have been improved. The frontend will be changed to allow for variation.</li>
</ul>
<h2>0.9.9 Beta</h2>
<ul>
  <li><strong>Added the new-style SGC-IDs. Now uses a friendlier system without symbols.</strong></li>
  <li><strong>First introduction of the Update Orb, which allows for various methods of updating your Stargate.</strong></li>
  <li>Fixed a text blemish on the output for &quot;Statistics&quot;</li>
  <li>Fixed a text blemish on the output for &quot;Help&quot;</li>
  <li>Opengate / Cleary dialing now gives a map upon dialing.</li>
  <li>Dials via glyph addresses now works properly. Guess what, it was only a difference between <strong>!=</strong> and <strong>==</strong>.</li>
  <li>Opengate / Cleary Stargates can now be dialed via a &quot;random&quot; command.</li>
  <li>Gate radio now works properly. magic_quotes_gpc can shove it.</li>
  <li>Incoming travelers are no longer murdered by Death.</li>
  <li>SCU properly updated to 2.0 -- lots of bug fixes.</li>
</ul>
<h2>0.9.8 Beta</h2>
<ul>
  <li>Removed all traces of the built-in IDC system. This includes all the API commands, /stargate commands, etc.</li>
  <li>Removed all traces of the access_list system as most gate functions are controllable via the API (and people can make objects to do that themselves).</li>
  <li>Removed /fast and /df due to stress on the server. These dial options are still available on the API using the <em>ring</em> parameter of <em>2</em>.</li>
  <li>All chat starting with / is sent to the server. This allows us to add / remove commands to the gate easily (besides /stargate commands).</li>
</ul>
<h2>0.9.7 Beta</h2>
<ul>
	<li><strong>Introduced the <em>forward addresses</em> for the Stargate system on an admin-assign only basis. Read the user guide for more details.</strong></li>
	<li><strong>Added the menu button <em>Output</em>. It allows you to toggle whether the gate outputs what it is currently doing on channel 0.</strong></li>
	<li><strong>Added new API response, <em>prompt|&lt;message&gt;</em></strong><strong>. This allows an individual to relay all verbal chat the Stargate sends out (besides menu commands) through the API instead of channel 0 (public output).</strong></li>
	<li><strong>Added new API command, <em>public listen|&lt;0/1&gt;</em>. This allows you to set public listen (listening for commands on channel-0) on or off.</strong></li>
	<li><strong>Added new API command, <em>public output|&lt;0/1&gt;</em>. This allows you to set public output (outputting normal gate verbal promps on channel-0) on or off.</strong></li>
	<li><strong>Added new API command <em>random list|&lt;0/1&gt;</em>. This allows you to set whether your gate will appear in a random dial or not.</strong></li>
	<li><strong>Added <em>Cut Power</em> to the active Stargate menu. Thought it would be cool, honestly.</strong></li>
	<li><strong>Added <em>top gates|&lt;gate name CSV</em><em>&gt;</em> API response. Contains a list of currently top gate names.</strong></li>
	<li><strong>Added <em>gate statistics|&lt;incoming&gt;|&lt;outgoing&gt;|&lt;total&gt;</em> API response</strong><strong>. Contains basic statistics about your Stargate's activity.</strong></li>
	<li><strong>Added <em>gate statistics</em> API response. Allows you to get basic statistics about your Stargate's activity.</strong></li>
	<li>Removed <em>Bug Report</em> button from the menu. People wishing to submit bug reports can use the forums at <a href="http://www.alpha-fox.com/forums/">http://www.alpha-fox.com/forums/</a>.</li>
	<li>Updated <em>Stargate Control Units</em> to <em>1.3</em>. Added the ability to change ring style to the <em>milkyway</em> version, as well as adding the ability to turn on / off stargate <em>verbal output</em>. The unit can also turn off the internal Stargate listen and route all listens through the unit itself (useful for large gate rooms).</li>
	<li>Updated the &quot;Top Gates&quot; list to reflect whether the Stargate exists anymore or not.</li>
	<li>Interference effect now plays when dialing your own address on your Stargate.</li>
	<li>Stargates now are smarter on when to output on the public channel (say, if using an API command) and when to not output on the public API channel.</li>
	<li>Gate shield (rezzed) is now modifyable.</li>
	<li>Integrated checks to make sure the communications parser does not stack-heap.</li>
	<li>Removed the verbal commands for IDC accepted / denied. GDOs based on the API can send this, and if accepted the gate signals you with &quot;Target shield has been lowered. You may proceed&quot;. This was to eliminate double messages upon lowering a shield.</li>
	<li>Fixed wormhole collisions. Now detects the key and name, and not everybody is an <em>object</em>.</li>
</ul>
<h2>0.9.6(2) Beta</h2>
<ul>
	<li><strong>Added in <em>target shield raised</em> API response. Check the user guide.</strong></li>
	<li><strong>Added in <em>target shield lowered</em> API response. Check the user guide.</strong></li>
	<li><strong>Added in <em>destination|&lt;region&gt;|&lt;position&gt;</em> API response. Check the user guide.</strong></li>
	<li>Changed the <em>Subnova</em> button in the menu to route to the Pegasus Stargate. The gates are now located in the retail center.</li>
</ul>
<h2>0.9.6(1) Beta</h2>
<ul>
	<li><strong>Added `gate_key` (SGC-style planet naming) onto the end of the <em>lookup</em> API response.</strong></li>
	<li><strong>Added `gate_key` (SGC-style planet naming) onto the end of the <em>directdial</em> API response.</strong></li>
	<li><strong>Added `gate_key` (SGC-style planet naming) onto the end of the <em>incoming wormhole</em> API response.</strong></li>
	<li><strong>Added `gate_key` (SGC-style planet naming) onto the end of the <em>dial verification</em> API response.</strong></li>
</ul>
<h2>0.9.6 Beta</h2>
<ul>
	<li>Upgraded the Alteran Address Display to <em>1.4</em>. The 7 glyph addresses were displaying on opposite glyph sets.</li>
	<li>Upgraded both of the Stargate Control Units to <em>1.2</em>. They now use region say to broadcast to your Stargate from anywhere in the region. I also put in a fix to prevent the mixup of name | region values in the address book.</li>
	<li>Milkyway and Pegasus DHD upgraded to <em>4.04</em> - Integrated llRegionSay to allow broadcasting to your Stargate from anywhere in the region.</li>
	<li>Tollan and Forerunner DHD upgraded to <em>1.04 </em>- Integrated llRegionSay to allow broadcasting to your Stargate from anywhere in the region.</li>
	<li>Upgraded Map System to <em>1.2</em>. Fixed an issue where it was using the wrong variable to load the URL, causing script errors.</li>
	<li>Kawoosh no longer forms when the shield is raised.</li>
	<li>IDC access list now checks from the correct Stargate.</li>
	<li>Pegasus gate dialing sequence corrected. Glyphs now stay under the chevrons when dialing.</li>
</ul>
<h2>0.9.5 Beta</h2>
<ul>
	<li>Fixed the API channels in the Pegasus Stargate.</li>
</ul>
<h2>0.9.4 Beta</h2>
<ul>
	<li><strong>You can now choose between &quot;Explosion&quot; and &quot;Beam Out&quot; effects for deleting the Stargate <em>(menu-only)</em>.</strong></li>
	<li><strong>Added <em>/fast</em> and<em> /df </em>for the forced wormhole opening. This will now work on regular dials if wanted. For the API, just set the spin value to '2'</strong></li>
	<li><strong>Added the API command &quot;ring speed|&lt;speed&gt;&quot;. The default ring speed is 80. It only works for one dial or until the Stargate resets. You must set it for <em>each</em> dial.</strong></li>
	<li>Death works again. A mistake in coding the Kawoosh caused agent checks to fail. (Omnifox Xi)</li>
	<li>Probe is limited to outgoing wormholes only. (Vala Vella)</li>
	<li>Event Horizon monitor scripts more refined. Hopefully this should fix the randomly-disappearing event horizon. (Omnifox Xi)</li>
	<li>You can no longer input glyphs into the gate when the gate is not &quot;idle&quot; or &quot;dialing&quot;. (Jeffej5005 Lewis)</li>
	<li>Updated the Alteran Address Display to <em>1.3</em>. Fixed a mistake where incoming wormholes would not display the address properly. (Lex Mars)</li>
	<li>Stargate crash error prevented and repaired. Possible causes:
		<ul>
			<li>Blank HTTP requests which could result from HTTP timeouts were not causing the gate to reset.</li>
			<li>The queue script was geting confused when an incoming wormhole interrupted an outgoing causing the gate to crash.</li>
		</ul>
	</li>
	<li>Milkyway and Pegasus DHD upgraded to <em>4.03</em> - Integrated 60 second timeout on each button press. Also owner locks so it doesn't pick up commands from other people's stargates. (Trance Sodwind)</li>
	<li>Tollan and Forerunner DHD upgraded to <em>1.03</em> - Integrated 60 second timeout on each button press. Also owner locks so it doesn't pick up commands from other people's stargates. (Trance Sodwind)</li>
	<li><em>dd:</em> dialing support removed. It caused problems for those with Cleary gates near the Alteran gate. (Cheshyr Pontchartrain)</li>
	<li>Fixed the region dial priorities. Now does priority dialing by the <em>network of your gate</em>, the <em>opposite network</em> from that, <em>opengate</em>, and finally <em>cleary</em>. (Lex Mars)</li>
</ul>
<h2>0.9.3 Beta</h2>
<ul>
	<li>Upgraded Alteran Address Display to <em>1.2</em>. Fixed a bug when setting the network and when loading the gate's address when idle.</li>
	<li>Upgraded AF-TP for support with sims in the spaces in the names.</li>
	<li>Fixed backend entering blank collisions in the database.</li>
	<li>Fixed a bug where you could send /stargate test incoming / outgoing when a gate is already open.</li>
	<li>Cleaned up some messy transitions between dialing and idle.</li>
</ul>
<h2>0.9.2 Beta</h2>
<p><em>The changelog for this version was lost. Sorry for the inconsistency.</em></p>
<h2>0.9.1 Beta</h2>
<ul>
	<li><strong>Added in &quot;Map System.&quot; Rez it near your gate and llLoadURL boxes pop up to teleport your avatar upon clicking &quot;Go to URL&quot;</strong></li>
	<li>Repaired the &quot;name&quot; menu commnand. (Wolfie Waves)</li>
	<li>Changing to &quot;shield&quot; mode now works. (Kegan Loon)</li>
	<li>Changed <em>lookup</em> API response to <em>&quot;dial lookup</em>&quot;	and <em>&quot;search lookup&quot;</em></li>
	<li>Event horizon now autodestructs upon not finding the Stargate. (Jeri Carter)</li>
	<li>Built-in shield now turns fullbright upon activation. (Zachary Carter)</li>
	<li>Pegasus gate has glow on the glyphs. (Zachary Carter)</li>
	<li>Subnova button now returns a normal dial API response (Lex Mars)</li>
</ul>
<h2>0.9.0 Beta</h2>
<ul>
	<li><strong>Includes the <em>Tollan Stargate</em>. A low-prim solution to the Milkyway network.</strong></li>
	<li><strong>Includes the <em>Forerunner Stargate</em>. A low-prim solution to the Pegasus network. </strong>(<em>Note: This is a concept Stargate, as there were no &quot;custom&quot; Stargate seen in the Pegasus galaxy yet.)</em></li>
	<li><strong>Included the <em>Alteran Address Display</em>. Instructions how to use it can be found in the user guide.</strong></li>
	<li><strong>The <em>Stargate Control Units</em> are included in the gate package. They are simple dialing devices using a stored menu of preset addresses and basic Stargate controls. &quot;The Poor Man's DHD&quot;</strong></li>
	<li><strong>Included the Beta version of the URL-based <em>Map System.</em></strong></li>
	<li><strong><em>Event horizon</em> sound replaced with a new one captured by Lex Mars.</strong></li>
	<li><strong>Stargate now checks the range of the number you send in teh API command <em>dial|x|y</em></strong></li>
	<li><strong>Added support for '*' wildcard network in the <em>directdial</em> and <em>lookup</em> API commands.</strong></li>
	<li><strong>Finished the <em>Alteran Stargate DHD</em> (</strong><strong>milkyway and pegasus) using the model and textures from the OS DHD 4.0 by OS Labs.</strong></li>
	<li><strong>New API response <em>interference. </em>When the Stargate has interference due to another Stargate of the same type in your region activating.</strong></li>
	<li><strong>New API command <em>offline stargate</em>. Sets your Stargate offline.</strong></li>
	<li><strong>New menu command<em> Offline</em>. Sets your Stargate offline.</strong></li>
	<li><strong>New API command <em>online stargate</em>. Sets your Stargate online.</strong></li>
	<li><strong>New menu command<em> Online</em>. Sets your Stargate online.</strong></li>
	<li><strong>Included the <em>Alteran DHD 1.0 Tollan</em> concept DHD.</strong></li>
	<li><strong>Included the <em>Alteran DHD 1.0 Forerunner</em> concept DHD.</strong></li>
	<li><strong>Stargate user guide now included.</strong></li>
	<li>Incoming / outgoing handling better. One gate per type in a region can be active at one time. (Lex Mars)</li>
	<li>Dropped support for pre-0.8.2 Stargates.</li>
	<li><em>idc</em> API command repaired. (SATA Zenovka)</li>
	<li>Incoming / outgoing at the same time should not crash the Stargate.</li>
	<li>Cleaned backend scripted and optimized them.</li>
	<li>Addresses now target primary gate instead of last-rezzed gate. (Zachary Carter)</li>
	<li>Fixed incoming effect on the Milkyway gate. It is now faster and doesn't move the top locker.</li>
	<li>Lookup command fixed; now returns the owner name and BOTH addresses. (Wolfie Waves)</li>
	<li>Fixed the double <em>stargate close</em> and <em>stargate cut</em> commands. (Wolfie Waves)</li>
	<li>Fixed the bottom two lights not lighting up on gate activation. (Zachary Carter)</li>
	<li>Chatter fixed; accepts 0/1 at the end of the API string and forwards through with no errors.</li>
	<li>Event horizon animations were fixed and some textures were remade to look better.</li>
	<li>Bakend updates incoming Stargate on target Stargate's shield status. (Wolfie Waves)</li>
	<li>The primary Stargate is now the *first* Stargate registered in a region, not the most recent. (Lex Mars)</li>
	<li>Raising / lowering the shield on incoming doesn't affect the target Stargate.</li>
	<li>No longer have <em>||</em> which the LSL parsers can't parse. Now fills in the empty space with <em>|NULL|</em> (Wolfie Waves)</li>
</ul>
<h2>0.8.2 Beta</h2>
<ul>
	<li>Event horizon is no longer gray. (Lex Mars)</li>
	<li>Stargate sends a confirmation before deleting. (Vala Vella)</li>
	<li>Collisions now register. (Vala Vella)</li>
	<li>Fixed the dialing. If the primary gate is active it doesn't allow a secondary gate to work.</li>
</ul>
<h2>0.8.1 Beta</h2>
<ul>
	<li><em>Bug Report</em> option now in the menu. No longer do you have to e-mail me.</li>
	<li>Stargate now includes an open-source explosion kit for deletion.</li>
	<li>You can now delist your Stargate from random dials.</li>
	<li>Added in the effect of all other gates &quot;sparking&quot; upon activity of another gate in the same region / network.</li>
	<li><em>test stargate</em> API command repaired. (BenJWan Kellner)</li>
	<li>Increased timeout on dynamic listens. (Kirby Figtree)</li>
	<li><em>lookup</em> API command repaired. (SATA Zenovka)</li>
	<li>Gate now updates the shield status with the server. (BenJWan Kellner)</li>
	<li>Gate now does not send the destination information when target shield is up. (BenJWan Kellner)</li>
	<li>Stargate shield does not lower when /<em>stargate reset</em> is given. (BenJWan Kellner)</li>
	<li>Fixed gate compatability with pre-0.8.0 series gates. (Lucian Underwood)</li>
	<li>Collisions now register on the API channel. (Vala Vella)</li>
</ul>
<h2>0.8.0 Beta<br />
</h2>
<ul>
	<li><strong>Added 300 second timeout to the dialing sequence.</strong></li>
	<li><strong>Implemented a way of banning people by UUID by redirecting all of their URL requests to 127.0.0.1.</strong></li>
	<li><strong>Dial / Wormhole management script divided into 2 to gain extra memory and stability.</strong></li>
	<li><strong>Added command: <em>/stargate test incoming.</em> Allows you to test the incoming wormhole on your Stargate.</strong></li>
	<li><strong>Added command: <em>/stargate test outgoing. </em>Allows you to test the outgoing wormhole on your Stargate.</strong></li>
	<li>Changed the direct teleport flag to just flag no random instead of not registering the Stargate. Should help for those who want to place a gate in a region that is direct teleport disabled. (Zachary Carter)</li>
	<li>Gate now resets if it recieves &quot; &quot; for the http_response body, or NULL_KEY for the requestID body. (Vala Vella)</li>
	<li>After lowering the shield, the server now returns the proper region / position. (Lucian Underwood)</li>
	<li>Fixed several bugs in the event horizon monitoring system. (Zachary Carter)</li>
	<li>Fixed the dialing buffer on SGC dial. (SATA Zenovka)</li>
	<li>Milkyway incoming repaired. A reset and incoming command conflicted. (BenJWan Kellner)</li>
	<li> Incoming no longer crashes the Milkyway Stargate. (Joachim Waydelich)</li>
	<li>The Stargate now does not allow you to map to the target gate until the target Stargate is open.  This is to reduce the killings by the target gate's kawoosh. (Drias Hidayat)</li>
	<li>Forced wormhole uses existing commands, making for a much cleaner dial. </li>
</ul>
<h2>0.7.2 Beta</h2>
<ul>
	<li>Removed my debug messages from the Milkyway Stargate.</li>
</ul>
<h2>0.7.1 Beta</h2>
<ul>
	<li>Fixed the event horizon ... again ... to emit light. (Zachary Carter)</li>
	<li>Fixed a small bug where the pegasus listened on the incorrect API channel. (Vala Vella)</li>
	<li>Fixed another bug where cross network (outside) dialing was not working. (Kirby Figtree)</li>
</ul>
<h2>0.7.0 Beta</h2>
<ul>
	<li>Double dialing prevented. The problem is that there is chat lag and the two messages come in so close that the gate does not have time to update its status to <em>dialing</em>. I've prevented it as much as possible. (Vala Vella)</li>
	<li>Event horizon now produces light on forced wormholes. (Kegan Loon)</li>
	<li>Added in '<em>stargate address</em>' API command. (Vala Vella)</li>
	<li>Fixed speed in Milkyway gate for incoming wormholes. (Zachary Carter)</li>
	<li>Milkyway and Pegasus now identify locking glyph 8 from 7. (SATA Zenovka)</li>
	<li> Incoming now clears the region / position so it does not attempt to map a location. (Kegan Loon)</li>
	<li>The kawoosh filters only agents from the list of people to kill. (Kegan Loon)</li>
	<li>DHD commands in the API now recognize the <em>spin</em> value. (Vala Vella)</li>
	<li><em>directdial</em> API command repaired. (Vala Vella)</li>
	<li>Stargate no longer gets stuck on incoming (Lex Mars)</li>
	<li><em>set</em> API command repaired. (Vala Vella)</li>
	<li><em>Death</em> now checks with llSameGroup(). (Kegan Loon)</li>
	<li>Gates can now dial <em>secondary</em> gates within a sim. (Vala Vella)</li>
	<li>Event horizon physics changed to be less harmful on the sim. (Kegan Loon)</li>
	<li>The kawoosh now filters the people who are killed by it so they are not killed multiple times. (Zachary Carter)</li>
</ul>
<h2>0.6.0 Beta</h2>
<p><em>First release. There is no interesting changelog for this.</em></p>
<h2>0.5.0 Alpha and Below</h2>
<p><em>No information is available.</em> </p>
