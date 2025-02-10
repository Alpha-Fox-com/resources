<p>In the development and deployment of the Alteran Stargate Network, it has gone through many changes, rewrites, and complete restarts. In the end, we are still the same group, with the same goals and the same basic idea, to create a Stargate Network.</p>
<h2>The Beginnings</h2>
<h3>September 2005</h3>
<p>Zachary Carter started an account in the Second Life &reg; world. At this time, he was known as Christos Mousehold. The first thing he found when entering the game was a <strong>Stargate</strong>. Though amazing at the time, it was pretty poor compared to today's standards.</p>
<h2>The Anti-Matter Air Heads</h2>
<h3>November 2005</h3>
<p>While trekking around, he came across a group known as the Anti-Matter Air Heads. This is where he bought his first Stargate and Puddle Jumper, and came across the first functional Pegasus Stargate. As Zachary was a newbie at the time, he quickly ran the group's patience. However, they did assist him with inspiration and ideas, and he went off to create his own Stargate.</p>
<h2>The Abydos Stargate Project</h2>
<h3>March - June 2006</h3>
<p>Skipping forward a few months (like six), the Stargate was created and a fully functinal DHD and dialing computer came along (with the help of Dennis Albion and JeffeJ5005 Lewis). It was around this time when Zachary came across an individual named Peter Lameth. With the help of Peter, they were jointly able to script a functining Stargate network working off a PHP backend server. The Abydos Stargate Project was born.</p>
<p>We call this a project because it never turned into a full network. It was just a side project that was worked on. Contact was made again with two members of the Anti-Matter group, Geordie Boffin and Reyo Neutra. With their help, textures were acquired for the newly created Stargate Network.</p>
<p>It never acutally made a release, and was set aside for a while as the Email communication was unstable, and a new LSL function called llHTTPRequest was due within a month or so.</p>
<h2>The Cleary Network</h2>
<h3>July 2006</h3>
<p>After llHTTPRequest came out, Peter and Zachary did not attempt to finish the Stargate Project. Other projects occupied their time, and it took a back burner to them.</p>
<p>One day while browsing a sandbox, Zachary Carter came past a poor looking, but very functional Stargate. This is where we meet Wes Keynes, the creator of the Cleary Stargate Network. Zachary offered to trade textures (that weren't his to give), and sounds in exchange for ideas. This deal was a stupid mistake, and caused tension between the two networks.</p>
<h2>The Grid and Arcturus</h2>
<h3>August - September 2006</h3>
<p>Shortly after restarting the Abydos Stargate Project, the main creator of the Anti-Matter Stargate (Mintopia Ambassador) reappeared. Wanting to finish a network as badly as we did, they decided to join together. Apologies were given for the texture handouts, and a new alliance was born,  known as <em>The Grid</em>.</p>
<p>When <em>The Grid</em> was created, the two groups decided which Stargate (milkyway / pegasus) they were going to use in their network. The Anti-Matter group named their network the<strong> Prometheus Stargate Network</strong>, and decided to use the Milkyway Stargate system. The Abydos Project, now going to be a full network, turned into the <strong>Arcturus Stargate Network</strong> and took the Pegasus Gates.</p>
<p>It was getting close to release, when the main creator of the Prometheus Network, Mintopia, disappeared again because of real-life work. It was decided at this time that the Arcturus Stargate Network would take over both gate systems, and Prometheus would be on standby. No response was heard from the Prometheus Network, and <em>The Grid</em> broke apart.</p>
<h2>Lex Mars</h2>
<h3>October 2006</h3>
<p>One day, the group stumbled upon a complex called Navo Terre while hopping on the Cleary Stargate Network. They discovered a new high-prim Stargate created by an individual named Lex Mars. It was at this time when members of the group started making stupid decisions, and even camped out in the station figuring out how Lex made his low-prim chevrons. The relationship between our group and Lex Mars / The Cleary Network was strained.</p>
<p>However, after apologies friends were made between the group and Lex Mars. He later joined the Arcturus Stargate Network and helped out in some of its releases.</p>
<h2>Problems with Release</h2>
<h3>November - December 2006, January 2007</h3>
<p>The Arcturus Stargate's were finally ready to be released. The first 10 or 20 Stargates went okay, but after they started rising to 40 or 50, the backend server started having problems. It seems that the code which was adapted from email to use the new XML-RPC and HTTP was a hackjob at best, and could not handle the load of 50+ gates.</p>
<p>The code was then rewritten with the help of Zwagoth Klaar. The network was then redeployed with a greater expandability and much faster responses.</p>
<h2>Eternal Calm</h2>
<h3>February 2007</h3>
<p>During this release, the region <strong>Munkie Island</strong>, where the group was renting a plot for the network headquarters, went up for sale. Peter Lameth took a grab at the island and purchased it from its owner, Philip Logan. The network was now based inside of the new Munkie Island, then renamed to <strong>Eternal Calm</strong>. A lantian-style city-ship build was created by Lex Mars, which was rightfully named <strong>Sedo Locus</strong> or <em>Calm Place</em>. The network headquarters was based inside of this build.</p>
<p>Also at this time, new textures were given to the group by an individual named <a href="http://web.mac.com/david_of_mac/iWeb/">David Gian-Cursio</a>. He provided all new textures and a new Event Horizon to replace the old ones by Geordie Boffin. A new model was constructed to go with these new textures, and a new Stargate was released, Arcturus 3.0.</p>
<h2>XML-RPC Issues</h2>
<h3>February 2007</h3>
<p>The network went through release after release, but one problem persisted. The one XML-RPC server that was used to filter communications through was struggling, and therefore the gate network struggled. </p>
<p>Email was setup as a "fallback" in case XML-RPC failed, but that too had its problems. Email from outside sources takes a fairly long time to process through the grid servers, and sometimes can get completly dropped.</p>
<h2>XML-RPC Solution</h2>
<h3>April - May 2007</h3>
<p>After some research done by Lex Mars and Zachary Carter, a solution was found to the communcations problem. </p>
<p>Using the backend server as a communication storage device and an in-world server as an email hub, we could send messages in-world via our backend server. A server in-world would ping our server every 2 seconds to ask for communication packets, and the server would return them.  This, combined with a timeout system and a way to verify the email's arrival, was the solution to the failing XML-RPC. </p>
<p>The idea thought up by Lex Mars, was successfully executed by Zachary Carter. It was throughly tested and was ready for use.</p>
<h2>Arcturus 4.0 and Alpha-Fox</h2>
<h3>June 2007</h3>
<p>Using the new XML-RPC replacement, a 4.0 Stargate was planned. This was going to integrate Premium Mode (some features requiring a one-time payment of L$500) and a bunch of new features. A new model was constructed by Wolfie Waves along with new textures and sounds. Unfortuantly, Zachary had become busy in real-life, and was unable to work on the network code much. Obviously, this delayed the 4.0 release for some time. Time passed by where 4.0 was being slowly worked on, but was still far from being complete.</p>
<p>As a way to organize his projects better, Zachary Carter created a new group called <strong>Alpha-Fox</strong>. At that time, it was decided that the Arcturus Network would integrate into the Alpha-Fox website and backend. It would still keep its name, but it would use all Alpha-Fox services.</p>
<h2>Eternal Calm Issues</h2>
<h3>July 2007</h3>
<p>XML-RPC issues were still happening, and Arcturus 4.0 was still hard at work. Unfortuatly, a few political issues arose between some of the residents of Eternal Calm and the Arcturus Network. The Arcturus Network left Eternal Calm and based its new home inside of Subnova Foothold, inside of the region Sonamu.</p>
<h2>Prometheus Unbound (literally)</h2>
<h3>Late August 2007</h3>
<p>At the end of August, we were informed by Reyo Neutra that work on the Prometheus Network was on hiatus. This was later confirmed by a post by Mintopia Ambassador on the PSGN website. The short lived network would still live on through Arcturus, for without the Prometheus Network, Arcturus would never have been created.</p>
<h2>OpenGate</h2>
<h3>July 2007</h3>
<p>
With all of the Stargate Networks out there, none of them have been fully open-source. One person took the iniative and created an Open Source Stargate Network.</p>
<p>You can find more information on the OpenGate network at <a href="http://ma8p.com/~opengate/">http://ma8p.com/~opengate/</a>.</p>
<p>Unlike the Cleary Network, we started out on good terms with them, and frequently talked about issues affecting our respective gate networks. A connection between the two networks was discussed and planned for a later release.</p>
<h2>Arcturus - Alteran Merger</h2>
<h3>August - September 2007</h3>
<p>With the <strong>Prometheus Network</strong> gone, <strong>The Grid </strong>broken up, the staff changed drastically, and the location of the headquarters relocated, the Arcturus Network was hardly what it was before.</p>
<p>Arcturus 4.0 was basically at a standstill, and it needed a kick. At this time, Lex Mars was invited to be a full administrator of the Arcturus Network. Lex had previously contributed things to the network, such as the dialing sequence and a few model upgrades.</p>
<p>Lex previously had a plan for a canon Stargate network named the <strong>Alteran Stargate Network</strong> which he would run under his group <strong>Subnova</strong>.  When he joined the Arcturus Network, it was decided that with all the changes, we could pull off a merger of the two networks, and restart the network code with all new ideas in mind. Lex took the original model by Wolfie Waves and rebuilt it, along with creating all new textures for the Stargate based off of the original naquadah texture by David Gian-Cursio.</p>
<p>The <strong>Alteran Stargate Network</strong> is the result of the effective collapse of <em>The Grid, crazyLabs, and Prometheus</em>, and subsequent creation of Alpha-Fox and partnership with Subnova.</p>
<h2>Alteran Alpha</h2>
<h3>September 2007</h3>
<p>When Arcturus 4.0 was cancelled, people were slightly annoyed as the 3.3a Arcturus Stargates were quickly becoming a nuisance because of their issues.  When the merger was completed, work began on the 0.1.0 Stargate, otherwise known as the "Alpha" gates. After a short amount of time, a limited-release of the Alpha Stargates was underway and progress on the network had restarted.</p>
<h2>Alteran Beta</h2>
<h3>October 2007</h3>
<p>After the Alpha ran for approximately 5 releases, we felt it was time for a more widespread release. The Alpha Stargates had final bugs removed and then moved onto Beta Gates, where they were freely available and bug tested.</p>
<p>During this time, many features were requested, and some were removed. The web interface was starting to be built, and bugs were being weeded out as the beta progressed.</p>
<h2>Eternal Calm Estates and Avalonia</h2>
<h3>May 2008</h3>
<p>After the move from Eternal Calm, the Stargate network was based within the Subnova-owned land in the mainland region Sonamu. However, space constraints were constantly being reached. It was at this time that the Subnova group purchased their own private island, Subnova. This was part of a new project called the Avalonia continent. Along with Avalonia, we rejoined our old friends in the Eternal Calm Estates to create a 9 region and growing microcontinent. The network was then moved to Subnova.</p>
<h2>1.0 Release Planned</h2>
<h3>August 2008</h3>
<p>In late August, Zachary Carter announced that on the 31st of August, the Alteran Stargate Network would debut its 1.0 version of the code to the entire Second Life grid. The planned release would be doubled with a party.</p>
<h2>1.0 Released</h2>
<h3>September 2008</h3>
<p>In early September, the 1.0 version of the Alteran Stargate was released to the public.</p>
<h2>Sidenote</h2>
<h3>By Zachary Carter</h3>
<p>Obviously throughout all this, mistakes were made. The original team broke up, and the current path is nowhere near what we had originally planned. However, I feel that under the circumstance we have succeeded in our goal, to make a Stargate Network. No money, no personal agendas, no war between networks. The main goal in the beginning was just to create a Stargate Network, and that is what we have achieved in the end.
</p>
<p>I would like to give thanks to those who are not involved with the network's development anymore for whatever reasons, but were very influential during its development</p>
<p><strong>Proper thanks goes to: </strong>Peter Lameth, Mintopia Ambassador, Reyo Neutra, Geordie Boffin, Sakura Raven, Dennis Albion, Wes Keynes, Lobos Cranes, Zwagoth Klaar, JeffeJ5005 Lewis, Kirby Figtree, Ash Qin, David Gian-Cursio (indirectly).</p>
<p>I would now like to give thanks to those currently involved in some part of the network, who continue to develop and make this network as great as it can be.</p>
<p><strong>Proper thanks goes to: </strong>Zachary Carter, Lex Mars, Wolfie Waves, Peter Lameth, and Ash Qin</p>
<p>And finally, a special thanks to all of the users of the network, for without you we would not be here today. You have done good.</p>
<p>... somehow, Zachary Carter has remained more-or-less sane.</p>
<h2>Information</h2>
<p><strong>Prometheus Stargate Network</strong> - <a href="http://www.psgn.co.uk/">http://www.psgn.co.uk/</a></p>
<p><strong>Opengate Network</strong> - <a href="http://ma8p.com/~opengate/">http://ma8p.com/~opengate/</a></p>
<p><strong>Arcturus Stargate Network</strong> - <a href="http://www.asgn2.co.uk/">http://www.asgn2.co.uk/</a></p>
<p><strong>Cleary Stargate Network</strong> - <a href="http://www.aristoi.org/gatenetwork/">http://www.aristoi.org/gatenetwork/</a></p>
<p><strong>Subnova</strong> - <a href="http://www.subnova.com/">http://www.subnova.com/</a></p>
<p><strong>David Gian-Cursio - </strong><a href="http://web.mac.com/david_of_mac/">http://web.mac.com/david_of_mac/</a></p>
