# Solar Table

@ Warren:  In terms of storing power, re: "solar table".  You need weight, and I was thinking structural battery because of fungible.  


# Helium notes
* https://github.com/helium
* https://www.helium.com/mine
* https://github.com/helium/HIP/blob/main/0019-third-party-manufacturers.md
https://docs.helium.com/use-the-network/devices/development/heltec/wifi-lora-32-v2/arduino/




Let's abandon for a moment the electrochemical "battery" idea.

Let's approach this as "one or more systems" which might also incorporate an energy storage mechanism.  

## The case Against batterres
Let's assume we for xyz reason don't have access to batteries, as a thought exercise.  especially electrochemical Batteries to me, they are toil, after X cycles they will break down, whereas ultra-capacitors they will outlive me, my children, my childrens childrens childrens children having cycles in the billions, making them well suited for 'trickle build up w/RAPID discharge' applications (they can also trickle discharge), but the cycle times are in the billions or trillions, whereas electrochem batteries are going to be in the 1,000's to 10,000's before they're toast. 



Even *if* we could make batteries out of non-rare earth materials, blabla. it's going to take dedicated time at least months, probably years to find an 'ideal' formulation and I don't think @warren wants to wait that long. I.e. solar panels are coming down off roofs NOW, going into landfills 'NOW', even when one or two panels fail, the whole system will be replaced, so let's assume 60% or more of the panels headed for landfills aren't actually garbage at all.  They shouldn't get put on roofs again so solar tables are 🥰. 

Just pragmatically, nobody is going to replace half their panels on a roof - the cost is having the Bluetongue solar rock up and get on a roof, and so perhaps the best business model for this project is to offer a way to donate their working but unused panels for a tax-incentive?  (somebody needs to pay for this, I like impact & government funding for green 'energy' projects) .. obviously, also because it's easy to get a 👍/👎 with a sufficiently great idea to directly approach my spouses professional circle and let it work from the top down.  It's a huge *global* potential market, and I think after looking at this - it's not actually a good fit to make a community version, i.e. the efficiency of making a system where other people cloud copy/clone produce their own, it makes sense to make machines which can make the parts, assembly them into flatpack boxes and ship them globally as fast as we could.  I normally love designs people can make in a makerspace with their own 3d printer, but I can't see a safe & suitable version in any form that anybody would go through all the hassle to make "one" or a dozen of these for-themselves.  This is a global problem in need of an urgent solution.  The worldwide opportunity for repurposed PV panels is certainly in the tens of millions of units over the next decade - and so the efficiency which could be gained from even a nominal improvement in manufacturing tolerance (for example) actually has both AU national/globally statistically significant numbers. 

All of my described mechanisms are intended to be put under the table, in the center, between the "X" legs on either side -- these will provide weight & stability.  Some designs described below in "larger" applications would be separate structures.  I describe remote-car charging stations (national AU car charging infrastructure, or eco-solar powered port-a-potties & bus stops) are other applications where a PV roof could also power a LORA mesh-network over thousands of kilometers.  It isn't a one size fits all, but the table is a cool place to start.  The tech is finished, easy to build. 

With the current 'new' administration my understanding is these types of ideas are likely to enjoy some level of traction, i.e. there is a cost of "approach". having two or three applications is actually more likely to trigger a Yes, assuming we can get the calendar time to pitch. Start with the table as the most 'simple-as' but maybe think a bit bigger. 

It's a highly exportable idea.  I'm keen to be involved/help because nationally it would be a long term highly 'visible' impact, both nationally & globally and lend credability to my ability. ;-)  .. so assume you've got my help, and I'll just assume @Jamie is also in, since he wants to build his van at your hangar (more on this later), but some of these ideas should align with his own 'well yeah, i'd like that' .. and I can say the same. 

First, this is for @jamie - maybe one or more long coil springs within the legs? .. springs are a cool & cheap way to store *dangerously* massive amounts of potential energy.   Springs are cool because we can trickle-charge and then unload in one movement, we can design systems with springs & gears (like watches) so they can't release until they have enough power to finish their movement which can include resetting the mechanism.  You spent so much time on your laptop arm, and I just want to prime your brain with a spring/coil, either metal or carbon fiber.  That is one way we could store a lot of power that we didn't think of yesterday! 

Unlike batteries springs don't even get marginally heavier when they accumulate potential energy .. this realization conceptually still bothers me!  I started with spring designs, or at least thinking about them, and someday IF we can make carbon nanotubes (or carbon fiber, Carbon Composite Bellows) with a low gearing one-way motor are a way to trickle "charge", rapid discharge (into a piston) and then have the final stage of the piston reset the mechanism back to 'trickle charge'.  .. but I simplified some of the subsequent designs they don't use/require springs, but I didn't want to eliminate them from the discussion. 

The one aspect of these systems is that they are going to be assumed to be 'infrequent load' (versus a home, which is continous load) so I spend most of my exploring ways to store the power should be balanced with the demand/load, the 'energy cost' of storing energy .. whereas @Warren, you're still thinking about direct charge.  I think the focus ought to be on capturing the power so when you want to charge your phone, it's able to do it at ~100W (the USB-C standard), charge a modern phone in ~10 minutes, but for this exercise I thought a /bit/ bigger.  Nobody wants to sit around at the table until the sun is shining, and as I said, electrochemical batteries are toil, and environmentally toxic - so let's just eliminate them, pretend they haven't been invented yet or are 'illegal' in this country. 

The average EV car uses 10 kWh/day .. 0.20 kWh/km, the average 5kW solar system genrates 23kWh a day that's usually a 8-12 panels right?  In my most ambitious -- what if we ran a national EV charging grid, free power & LORA internet roadside for EV cars, like bus-stops, but they're free/discount super-chargers? and we store the power with CAES (Clean Air Energy storage) with an App that shows you which bus-stops & solar porta-potties you'll be able to get power for your vehicle.  (These might also have emergency roadside tow).  I.e. this is another form factor, perhaps better than the tables.   Suddenly we could electrify transport of goods & materials or even power bullet train-sleds provided we can keep "boosting them".  

The catch is solving the storage problem, because today the only viable way to store power on a small scale (i.e. a solar panel) is a battery.  So let's just fix that. 

This isn't *necessarily* a one size fits all, i.e. a solar table in a public park in a remote town might have significantly less usage than one at a rest stop on a busy freeway.  But again, for my numbers 60% of the panels coming off the residental roofs are in perfectly good working order and according to the LINDY EFFECT if they're run without issues for 10 years, they might run for another 20 years, 40 years, 80 years, we just don't know until we try to repurpose them into a situation where we can measure them and track their beyond end of life performance.  I.e. mars rovers are *still* going, despite being planned for a 1 year mission.

Now practically, we want some redundancy.  Being able to tie multiple 'tables' together in parallel (not in series), i.e. thinking about the power acquisition from the panel vs. the storage & output as three separate mechanisms which I'll refer to as frontside/storage/backside.  

Frontside is the PV, (but it could be a bicycle, or a hand crank), and Backside is a the storage INPUT & output.  Nominal electronics, very reliable, multiple front-side interfaces, it makes the table suitable to fit into more 'use cases', including wind, etc.  The front-side interfaces should be the spot where others can 'plug in' to this design, school competitions, hackathons, etc. don't restrict this to only used-solar panels but assume that MOST systems will have at least one used solar panel.  In theory an electric car *could* come with a hand-crank and you could use that to get a person to the next power-station. 

🤓 side note: there is a concept for EV cars called a "range extender" which is a trailer, with a small usually-fuel generator that generates power for the cars as they drive.  This has nothing to do with solar panels, but generally relates to "things Australia will need before long range electric trucking is feasible" .. just saying, that used solar panels electrified trucking, long range LORA mesh for networking & inter-vehicle communication/wifi .. all good ideas for #ETC (explore later)

The idea 'behind' the front-side is we are skipping the inverter & waiting till we have nominal voltage step-up, and going straight to low-voltage VFD into energy storage (for this 'recycling' project/application), seems to make sense, i.e. designing a system which can run efficiently in a range of ~1-48V with a ~24v expected nominal range.  (I'd add a 48v safety fuse so system can't be overloaded/broken, and design it to run optimally in the ~12v to 24v range)  at least I think that's definitely best suited to the application and electronics in that range are plentiful & widely available (very cheap, already enjoying an economy of scale in production).  

The idea a system can CHARGE at 1-48v and DISCHARGE at 440v (electric car) is totally "yes".  Also if we use AIR, the idea that there could be multiple charging inputs, also "yes", simple-as-duh.  Also Australia is really hot (in a lot of places) and I like the idea of using air-pressure, steam, etc., we're drawing cool air under the PV for intake under the PV and transferring to tanks (or balloons).  Pressure is also really exceptionally easy to measure (doesn't consume much power).  Anyway, the idea that a compressed air tank transfers it's energy to a flywheel or other 'more powerful' mechanism, you can store a lot of power in a flat metal disk by just increasing the RPM's, but it's even more powerful if we use the compressed air to move water (by increasing the density).  Getting water to the systems could be a problem UNLESS we include an apparatus to do moisture farming - which is fairly straightforward conceptually.  Again the space under the PV panel is actually going to be much cooler, so there's a temperature differential and that is *technically* all we need to do is move air across a cooler surface to extract the moisture.  It doesn't need to be super elegant. 

An elegant example would be something like this MOF-303:
https://www.scientificamerican.com/article/portable-oasis-extracts-water-from-dry-desert-air/
https://www.darpa.mil/news-events/2020-12-18


In terms of storing power - using a series of small wood or hollow plastic/(with water & battles) in metal banded (for strength) flywheels under the table could provide 'inertial stability' by spinning in opposite directions at each corner of the table, the height of the flywheels (mounted horizontally on bearings) determines it's mass. 

Water in particular is interesting because if the baffles are shaped in such a way that the start of spin the water at low inertial velocities begins in the center, and then as momentum builds, the wheel deforms and pushes the water "up" to the edges, this is a design I've been playing with we might be able to use here *someday*, it's a more efficient flywheel to start at low power.  I was thinking about a baffled metamaterial which deforms as it spins (such as a balloon in a cone which inflates or deflates to move the water around as the horizontal flywheel spins, moving the water to the edge where there are baffles).  Water is super heavy, but if the flywheel breaks it's just gonna leak and not kill anybody! Safety first.  

(Again, very high tech, but we can start with a simple wooden wheel, add a metal band, and replace it LATER with a more advanced flywheel).  Flywheels are a cool form of "spinning rim" where there hasn't been much disruption.  🤓: The baffles are necessary for fluid to transfer it's energy to the flywheel.  Flywheels are a great place to dump & store power, a metal band along the outside ensures wood/cellulose doesn't shred apart from centrifical force).  If the table is humming, it has power. ;-) 

With a spring, where it has enough power, it could dump that into a flywheel(s) too.  I.e. every "N" rotations (which could be a digital or mechanical counter) the spring unloads energy to something bigger.  I.e. flywheels 1,2,3,4 instead of one big one "limits the crater size" chance of death to somebody or some-animal.  .. I'd like to suggest that spinning flywheel, with an integrated loop of telsa-valves could theoretically pressurize a system.  

One nice aspect of putting things under a solar panel table is that we've got UV shielding for any mechanisms 'underneath' the table, it's a UV free zone - so electronics, wooden legs, & whatnot which would normally be damaged by elements, are going to be happier under the table.  When i think the springs, I think they are stored insight the legs (which are hollowed cores), but at least for the demo/prototype version, we'd build them with one acrylic panel that can be screwed closed so we can demonstrate the mechanisms. 

Also I thought maybe storing AIR in a compression tank (such as an old propane tank), again just charging up an ultra-cap that discharges a pump "one or more movements" .. during full-light periods it's click,click,click, during low light it's click ... click ... click and it's quiet at night.  Detecting that a USB-C device is plugged in/wants power, and then electromagnetically opening a piston valve that is a cone, forcing the air into a jet nozzle for low power, high pressure.

The same mechanism(s), i.e. components probably ~66%, can be recycled for both charge/discharge mechanisms to the tank (i.e. using a large electromagnetic piston to compress air).   I like electromagnetism because it's very dependable & easy to observe.  Maybe using a tesla-valve attached by said piston to charge the tank (so it's a historically-difficult to fabricate, but 'easy-with-modern tooling', but becomes a very reliable/simple "works forever" mechanism for portable small-scale "slow" CAES).   There's actually a lot of good ideas in this space, Entrainment, pump-jets, non-nuclear boiling water reactors or similar would all potentially work here. Putting a small solenoid at the exit for the valve so it can be put in a zero-power consumption "rest" position until the next charge cycle. Using electromagnetic pumps just feels like the right solution for this project.  Even if there are flywheels or OTHER mechanisms for storage, thats simply more wattage, those could also be easily powered from compressed air and/or springs.  

The size of the tank and it's maximum pressure become the storage mechanisms, and design them intentionally to "fail/vent upward" (because the ground ain't moving!) and shield them elementally from UV absorbant solar panels.

@Jamie - we can recycle this/these ideas for the caravan (if you are so inclined).  I'd wager air is going to be the lightest form of energy storage, well hydrogenis, but it's very easy to capture air while moving by using a natural effect known as laminar flow + an air-multipler.  I'm not saying that it'd be net-negative, but in terms of distance, incorporating air-foils and whatnot into the design, there is a reason they don't make planes with square edges, you're always going to be better off using a heavier design with better airflow.  

We can can extract moisture from the compressed air to get water, the water we *could* make hydrogen. 

If we put a low-voltage booster by drawing power from the spring, etc. we could rapid charge a phone or even a car (instead of trickle charge).

For a car - a spring or flywheel was big enough (which can be accomplished with gearing multiple smaller flywheels).   Please remember that the PV panels themselves can act as a photoresistor, so the behavior of having a 'night/day' mode is easily controlled by the PV.  .. this could literally be a national 'emergency' EV charging or emergency radio beacon network built from fields of used solar panels. (We have these along our roads in the US)

Applications for the power could include a digital clock, that also has a small IP66 button that could show both current charge and perhaps a measure of the power stored.   The charging interface should be a USB-C which supports up to 100w output - that's enough to power a laptop, an emergency 'roadside' radio beacon, any number of applications, there is a low-frequency radio networking protocol called "LORA" which is used to do mesh networking up to several kilometers, using directionally aligned antennas, so again - this is potentially providing free public Internet/wifi signals.  It's not as fast as fiber, but it'll certainly get an SOS message or suitable for Email.  The LORA network also provides monitoring of the operations for a variety of other applications beyond monitoring each panel/table is operational, it could also provide motion sensor IR cameras at night, all sorts of useful ways to track & monitor wildlife. 

I think there is probably a number of national or international design competitions that this 'solar recovery' project could be entered into, especially if it was designed as you suggested to be hackable.   There is a scale where this device I'm describing where a nominal version would cost less than a $20 AUD to make.   I would also encourage us to consider the applications of animal & homeless emergency shelters as tables in parks & outdoors around the world. 

One other idea was to add a small evaporative moisture-farming device that extracts drinkable water from the air.   The water could then be pumped into water containers (which overflow). 

Another application could be sanitation into solar compositing toilets that periodically 'bake' the waste contents and convert the excrement into usable fertilizer.  Several cool-as-fuck applications here, complexity and reliability.  At least one of these is a shit idea to work on. 😆


Winding a massive spring, adding a clock, a photoresistor and some lights "old school cool" -- extra power, if these generate too much - how about a small scale 'moisture farm' that creates fresh drinking water?    I just see these used solar panel tables showing up in parks and 3rd world countries all over the world.



https://www.scientificamerican.com/article/portable-oasis-extracts-water-from-dry-desert-air/
https://www.darpa.mil/news-events/2020-12-18




https://www.aemo.com.au/newsroom/news-updates/orchestrating-the-pace-of-change

