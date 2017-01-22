# Home Injection Molding Notes

This is a semi random collection of notes a home injection molding machines
and mold making for such machines.  A "home" injection molding machine is
a manually operated machine that can frequently fit on a bench top on takes
up a relatively small floor footprint.

If somebody wants to suggest additional information to add to this document,
just send me the text in an email to wayne AT gramlich DOT net with "Home Injection
Molding Notes Suggestion" in the subject line.  Markdown format is preferred,
but not required.

## Books

There are a number of books on the topic on manual injection molding machines:

* [*Secrets of Building a Plastic Injection Molding Machine*]
  [https://www.amazon.com/Secrets-Building-Plastic-Injection-Molding-ebook/dp/B018RBEZKE/ref=sr_1_1]
  by Vincent R. Gingery.  Copyright 1997.  ISBN 1-878087-19-3:
  This is probably the original book about the topic of home injection molding machines.
  It is a bit dated, but definitely worth a quick read.

* [https://www.amazon.com/Cutting-short-run-plastics-injection-molding/dp/B0006VV79G/ref=sr_1_1][
  *Cutting costs in short-run plastics injection modding*]:
  This book focuses on the trade-offs for making lower cost molds for these manual
  bench  top machine.  This is a book is by Morgan Industries, Inc. and is geared
  towards their line of bench top molding machines.
  
## Commercially Available Injection Molding Machines

There are a number of commercially available.  As I run across them, I will
add them to the list below:

### Morgan Industries, Inc.

[Morgan Industries, Inc.][http://www.morganindustriesinc.com] produces
a set of bench top machines call the Morgan-press.  By the way, the
Morgan-Press is the benchtop injection molding machine used by Techshop.

At present, I find the Morgan Industries web site to be a bit difficult
to navigate, so I have added some links that probe into their web-site.
Presumably, these links will break over time:

* The [http://www.morganindustriesinc.com/g-models/][Morgan-Press models].

* The [http://www.morganindustriesinc.com/injection-molding-machine-features/][Morgan-Press Models].

* They also sell [http://www.morganindustriesinc.com/plastic-molding-guide/][a mold book].
  This is referenced above in the books section.

* There are a couple of videos:
    [https://www.youtube.com/watch?v=dyfNkzi0RpA][video1] and
    [https://www.youtube.com/watch?v=OneSFRR3CQw][video2].

* There is a [http://www.cs.cmu.edu/~rapidproto/manufacturing/MP_Manual.pdf][PDF Manual]
  on-line at Carnegie-Mellon University (my undergraduate alma mater.)

These machines clamp the mold from the bottom.

This machine starts at roughly $20K and has a variety of add-ons.  The anti-ooze
nozzle sounds interesting.

### Amatrol

The Amatrol learning system looks pretty decent.

Here are some links:

* [http://www.amatrol.com/coursepage/96-pls1-t/][Amatrol PLS1] is the actual machine.


* The [http://www.lcis.com.tw/paper_store/paper_store/price-2014121114290281.pdf]
  [Amatrol 2017 Price List].

This machine clamps the mold from the side.

About $15K.

### Medium Machinery

[http://www.mediummachinery.com/][Medium Machinery] makes an very capable
looking injection molder.  The web site is very easy to navigate.
This machine clamps the mold from the bottom.

### Iasco-Tesco

It is unclear if Iasco-Tesco is still in business.  Hopefully, there are just
rearranging their web site.

There is several year old
[http://web.archive.org/web/20150213095804/http://iasco-tesco.com/images/catalog/iasco2013.pdf]
[catalog for Iasoc-Tesco].  The Ultron looks pretty neat.

### A.B. Plastic Injectors

[http://www.abplasticinjectors.com/][A.B. Plastic Injectors]

No on-line prices.

### Galomb, Inc.

[http://injectionmolder.net/][Galomb, Inc.] sells an injection molder for about $4K.

## Wayne's Thoughts

Of all of the ones above, the one from Medium Machinery looks closest
to what I have in mind.

To summarize, a manual injection machine has four basic parts:

* Injection Shaft:
  (Top) An injection shaft that pushes the melted plastic into the mold.

* Plastic Melter:
  (Middle) A place to melt the plastic.  This is also the place where the
  plastic is added to the machine to the melting chamber.

* Mold Clamp:
  (Bottom) A place to clamp the two mold halves together.

* Frame:
  In addition to the three basic parts above, a frame is needed to hold
  it all together in the right locations and orientations.

Each of these is parts is discussed briefly in the  sections below

### Frame

My current thoughts on a frame are to use some
[https://www.lowes.com/pd/Steelworks-6-ft-x-2-1-4-in-Plated-Steel-Slotted-Angle/3057635]
[Steel Slotted Angle] for most of the frame.  It may be necessary to double or triple
up on some of the high force sections of the frame.  This seems like a flexible
to design a system where sub-modules can be moved up and down by unbolting some
bolts and reattaching in the new location.

### Injection Shaft

The injection shaft can be done either manually (like the Gingery or Galomb) or
with a air piston.  With an air piston, it is possible to set the final pressure
exerted on the injection shaft using a air regulator.  That feels like a much
more repeatable strategy to me.  In addition, an air piston perform larger shots.
In general, I'd like to support 6 to 10 in^3 of plastic, whereas the manual
injection shafts tend to be down in the .5 to 1 in^3 of plastic.

It is not clear to me how to compute the injection shaft diameter based on
the maximum desired shot size.  Once the diameter is known, the height of
the melting chamber can be computed.

Once the diameter is know, presumably it is possible to compute the desired
maximum force to exert on the injection shaft.  MaMaster-Carr has a reasonable
election Tie Rod Air Cylinders of various output forces and strokes.  They
are not particularly inexpensive.  Presumably, once the desired force and
stroke is selected, it is possible to shop around.

I would probably use a precision ground steel shaft from McMaster-Carr for
the injector shaft.  They are inexpensive and extremely accurate.  I still
do not know what diameter though.

### Plastic Melter

My current design is based the heater block used by Vincent Gingery
in his book (see above.)  Rather than using a steel block, I would probably
attempt to get by with an Aluminum block instead.  I find Aluminum easier
to work with on my CNC mill.  Again, I do not know what size block to use.
The larger the block the more heat retention.  (Yeah, I know steel has a
higher specific heat.)  I would also machine up some stuff allow the plastic
pellets to be shoveled into the heating block.

On thing I really like about the Medium Machinery design is that
it has replaceable "Internal Plasticizer" shafts made out of what
ooks like brass.  That looks quite doable would allow me to change
plastics and color by changing shafts.a

I would probably buy a couple of 400W cartidge heaters from McMaster Carr
design them to be on each side of the injector shaft bore.

In an article from
[http://makezine.com/][Makezine] there is an
[http://makezine.com/projects/make-41-tinkering-toys/diy-injection-molding/][article]
from somebody who modified their Gingery injection molding machine
to use a PID controller.  The person used a PID controller from
[http://www.auberins.com/][Auber Instruments].  It looks like the
[http://www.auberins.com/index.php?main_page=product_info&cPath=1&products_id=83][SYL-1612B]
what was selected.  I would be tempted to use the same product and a
couple of 10A 240VAC Solid State Relays.

I believe it would be best if there was some insulation wrapped around
the heater block.  This was done in an
[http://www.instructables.com/][instructables]
document for a
[http://www.instructables.com/id/Plastic-injection-molding-and-extruding/][filament extruder].
In addition, a protection cage to keep fingers from touching the melter system
makes some sense as well.

It is unclear whether or not a threaded injection nozzle will be used.
I am leaning towards one, but it is unclear where to get them right now.

### Mold Holder

There seem to be two styles of mold holder -- bottom clamp and side clamp.
Both styles will work, but they impact how you design your mold.  For a
side clamp mold, the plastic is injected right at cut plain of the mode.
For a bottom clamp mold, it is necessary to provide a tapered hole through
the mold to reach the cut plane.  This can be done with a tapered end mill.
The Morgan-Press and the Medium Machinery used bottom clamp whereas most
of the others seem to use side clamp. While I lean towards side clamp,
I consider myself sufficiently ignorant of the issues that I could be swayed
the other way.

Ideally, an air piston would be used to do the clamping.  Alas, air pistons
tend to be expensive.  I thought it was totally ingenious how Medium Machinery
used a simple bottle jack for their clamp holder.  Bottle jacks are inexpensive.
When I looked up bottle jacks on Harbor Freight, I found two almost identical
20 ton air hydraulic bottle jacks -- 
[http://www.harborfreight.com/20-ton-air-over-hydraulic-jack-95553.html][#95553] and
[http://www.harborfreight.com/20-ton-air-hydraulic-bottle-jack-69593.html][#69593].
(The only difference is where the air hose attaches to the air motors.)
These behave just like the hand pumped jack use by Medium Machinery except
that they can be pumped with air pressure rather than a manual pump level.
The air motor drives the hydraulic fluid pump.  The air pressure just controls
the speed of the pumping not the set pressure.  When you are all done, the little
the T valve at the base is twisted release hydraulic fluid and let the springs
retract the jack.  I can live with that!

There is (at least) one disadvantage to side clamping.  There also needs to
be some pressure to press the mold up against the plastic melter.  I have not
figured out how to do this yet.

## Wrap Up Commentary

I am not sure I will ever get around to this project, but I thought it was
useful to write down my ideas.  Who knows maybe somebody else will pick up
on the project and push it forward some more.

# Acknowledgments

I would like to acknowledge that I have gotten some *very* useful information from the Yahoo
[https://groups.yahoo.com/neo/groups/homeinjectionmolding/info][Home Home injection Molding Group].
