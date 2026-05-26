# The semistatic bearing
Official repository for the semistatic trackball bearing
This semistatic bearing is intended for use in trackball pointing devices such as those sold by Ploopy and efog.tech. It features a free-spinning main bearing that sits on three embedded subbearings.

But first, some background.

## Static bearings
Most trackballs use static bearings: three tiny balls in a triangular pattern, with the main ball perched on them (like a tripod). The bearings are embedded in the shell and don't move at all (hence, "static").

Static bearings are silent and inexpensive, but suffer from static friction ("stiction"): you have to apply enough force to dislodge the trackball when it's at rest, and when the ball finally moves it jumps too far. Stiction prevents small, precise movements. It's the bane of all trackballers.

## Ball transfer units
A ball transfer unit (BTU) contains a big ball bearing sitting on top of a bunch of smaller subbearings that can all move within the bearing case. This allows the big bearing to spin freely, since there's very little friction slowing it down. However, BTUs can be noisy due to the ball bearings rattling inside the case.

You won't find BTUs in consumer-focused devices (e.g. Logitech or Kensington), but they're popular in DIY trackballs and modifications. Bosch Rexroth produces the best BTUs, but they're difficult to buy in small quantities and expensive when you can get them (typically CAD$15-20 per unit).

## Put those hands together!
My semistatic design merges the static and BTU concepts. It has a main bearing sitting on subbearings (like a BTU), but the subbearings are embedded and don't spin (like a static bearing).

It was originally designed as a drop-in replacement for the Bosch Rexroth 8mm BTU often used in modified Ploopy trackballs and the efog.tech Endgame trackball. I've since added a version to replace Veichu 7.5mm BTUs.

## Is it better?
I'm confident that a semistatic bearing is better than a static bearing or a cheap BTU. It's smooth and quiet, stiction is virtually non-existent, and supplies are easy to get online. It's also easy to clean since the bearings are exposed.
And then there's the cost.

- With a 50-pack of G10 ceramic bearings for $15, you can make 12 semistatic bearings. 
- 12 printed bearing cases requires 10g of filament; at $20/kg, that's another $0.10. 
- Total cost: $15.10 for 12 units ($1.26 each).

Bosch Rexroths are still the absolute best if you want extremely low friction, are okay with some noise, and don't mind paying for the experience. The semistatic bearing is for everyone else...or as a stopgap while you're waiting for BTUs to arrive in the mail.

## Considerations
- The three-pointed claw is the only thing keeping the ball bearings from spilling out. I've found it to be very secure and there shouldn't ever be much force on it, but there's a small chance that it will break if the bearing is handled roughly. It may also wear down if you frequently remove the balls.
	- If you travel with your trackball a lot, you might want to carry some extra bearings.
- The bearing can be easily disassembled for cleaning or recovering/reusing parts.
	- If you prefer a more permanent solution, the subbearings can be glued/caulked in place. This Reddit comment recommends also filling in the gaps between the subbearings for easier cleaning. Just make sure that adhesive doesn't hamper the main bearing.

## Print settings
All models are designed for 0.2mm layers.

- I recommend ironing (on all surfaces) for bearings with flat tops.
- No other special settings are required.

## Supplies
Any ball bearings should work, but I recommend ceramic balls of at least G10 (preferably G5).
- You'll need four ball bearings for each semistatic bearing.
- My testing has mostly been done with uxcell 3mm Silicon Nitride G5 and uxcell 2.5mm Zirconium Oxide G5 ceramic ball bearings.
