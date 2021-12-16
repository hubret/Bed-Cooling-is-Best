I've literally never done any investigation into water cooling systems before this, so I wanted to keep the engineering as hands off as possible. I'm decently ok with spending the money. This build uses parts that are basically plug and play.

I know how radiators and heat transfer work, but all of the plumbing lingo about parts, sizes, and connectors was Greek to me.

Based on the [data from Brennan's build](../brennan/Prototype%20MK1.md#Thoughts), I knew for me that installing fans was overkill, and a 420mm radiator was overkill. I probably only needed a double radiator running passively.
Having no fans, I have no need for a fan controller, which is good because I know nothing about them. In a [demo video](https://youtu.be/EfuD8lSTTqg), Brennan showed the a vario pump that has a sort of potentiometer dial to control the speed. Using that would mean I don't need a pump controller either.

Even though I basically decided what pump I was going to use, I looked at the comparison between DDC and D5 pumps and this is what I gathered:

DDC:
- use if you need pressure downpump
- louder (much louder? idk) than D5
- is small
- gets hotter

D5
- more expensive
- quieter

I also didn't want to spend the effort doing plumbing between the pump and the reservoir, so I bought an integrated D5 (wasn't cheap). It takes a while for the air to purge out of the pump and is pretty loud during that, but then is basically silent compared to ambient HVAC noises when running at half power (I ran it at exactly 50% power) and the air is settled.

Now, the only part that needs power in the whole cooling system is the pump. I learned that the D5 vario (or at least a specific type of them) uses molex connectors (the 4-pin power connector some older? computer parts use) for power, so I looked for a molex power adapter brick to get power to my pump.

The pump has an extra wire for measuring the pump RPM. I don't need it.

During the build, I plugged in the molex connector and the pump didn't start pumping. My multimeter showed 2 volts between the pins.

I learned that the D5 vario needs 12v. The 12v socket on the molex adapter's connector was on 4. The pump's molex connector had the yellow wire on 1, which was getting 5v. And of course the ground wire has to go to the ground pin on the adapter, which was pin 3 for me. The pump started moving water after reorganizing the pins. I would check the wiring diagram on the sticker on the adapter to see if the wires are correct.

The actual heat transport piece that interfaces with your body heat evaded me for a long time, as I didn't know what to search to find it on Aliexpress. It turns out that Brennan already linked? an item that is basically a knockoff chilipad. However, I decided to look for "water circulation heated blanket" and found basically what I was after, though they were blankets. However, the blanket form factor might make lying on top of tubes a bit more comfortable. I got a blanket that was exactly the width of a queen mattress.

I had to wash it in my bathtub as it wouldn't fit in my washer.

The silicone hoses of the blanket were ~6mm inner diameter (ID) which was important to note because I had to rebuy hose connectors more times than I'd like to admit. I bought an extra 6mm ID silicone tube to connect the pump to the radiator.

The pump doesn't come with connectors to plug your hoses to, you need to install those yourself. And the radiator I got was the same idea. They had threaded holes (called G1/4) which you can screw in some G1/4 barbs to stick into the silicone hoses. I bought 7.2mm diameter barbs to fit into the 6mm hoses. These fit just right and (so far) require no fasteners or clamps, the other sizes just don't fit at all.

The pump runs best upright so the air doesn't get sucked into the pumping element. However the D5 wires come out the bottom so it doesn't sit completely flat on the ground. Would be nice to have it mounted but not the end of the world.

I'm using distilled water without rinsing the system beforehand. I do not really care right now. I will dump it in ~4 months and refill it or see if it needs biocide.
