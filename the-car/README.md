# Getting Your Car Ready For the Road

## A Car For the Road

Sufficient useable range so that charging stops are welcome breaks, rather than annoyances. For me, that means about three or four hours of driving. On the highway thats works out to somewhere between 180 and 280 miles. So by this metric the "perfect" road trip car would have an advertised range of about 400 miles. Our KIA EV6 has a real world range of almost 300 miles. That's on the low side, but not too low. Weighing cost against range, it's feels like a pretty good balance (in 2025).

Fast enough charging to make your stops efficient.

Manually start battery conditioning.

## Your Phone

### Keeping Your Phone Powered

### Keeping Your Phone Cool

### Keeping Your Phone In Sight

## Charging On the Road

### Fast vs. Slow(er) Charging

### Strategy

EV batteries charge most efficently (at least in terms of the time it takes) between 10 and 80 percent of their "advertised energy capacity." Above 80% capacity the charging rate starts to go down dramatically. A car that can charge from 20 to 80 percent in 20 minutes might to another 20 minutes to charge the rest of the way to 100%. Personally, I'm uncomfortable heading off for an unknown charging station with only 10% of my range (about 30 miles in the EV6) in reserve. A reserve of 20% feels better. So our "efficently usable energy capacity" is between 20 and 80 percent or 60% of the advertised capacity. For the EV6 at highway speeds that works out to a range between charging stops of about 160 miles[^ev6-range], or around two and a half hours of driving.

I'd be okay driving for three or maybe even four hours at a stretch, but that would mean charging to closer to 100% at each stop. That would actually take longer to cover the same distance than if I charged on the "sweet spot" of the charging curve and gave myself some extra breaks.

On the other hand, a longer break is sometimes a good thing. You can have some time for a nice meal or to take the dog out for a romp. Use those long breaks to charge up to 100% (or closer to it).

When you stop for the night, try to find places where you can charge, ideally on a slower Level 2 charger -- they are often less expensive and are always kinder to your battery.

[^ev6-range]: A 2024 "long range" EV6 has an advertised battery capacity of 77 kWH. Over the life of the car it has averaged 3.7 miles/kWH. On the highway it gets closer to 3.4 miles/kWH. So: 77 kWH * 3.4 miles/kWH = 261.8 miles, 60% of 261.8 = 157.1 miles.

### Battery Conditioning

EV batteries charge fastest when they are "comfortably warm," for a lithium ion battery, that means between 15° and 35° C (or between approximately 60° and 95° F). If the battery is too cold, or too hot, the car's charge controller will limit the charging rate until the battery is in that range.

Most modern EVs have the ability to "condition" the battery before charging. Some provide a means to do this in the vehicle settings or expose the control in the user interface. Others will only condition the battery for charging if you are navigating to a known charging station with the built-in navigation system. If your car does not provide a way to manually condition the battery, you may be able to trick it into conditioning the battery by selecting a nearby charging station in the built-in navigation and telling it to take you there.

Before you worry about manually starting battery conditioning, or tricking the built-in navigation into doing it for you, use ABRP to check the battery temperature[^obd2-link-required]. If you're between 15 and 35 degrees C you don't need to do anything. On a summer roadtrip in much of the US you're probably already there. For winter drives (or very hot summer drives) you'll want to do some experimenting to find out how quickly the battery conditining system can heat (or cool) the battery -- get a friend to watch the battery temperature in ABRP and note how quickly it changes when conditioning is enabled.

[^obd2-link-required]: On cars that expose the traction battery temperature on the OBD2 data stream, ABRP will display the temperature if you have set up ABRP to read live data from the car with an OBD2 "dongle."

### NACS (Tesla) Adapters