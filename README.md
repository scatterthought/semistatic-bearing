<img src="https://github.com/scatterthought/semistatic-bearing/blob/main/images/semistatic-br8-30.jpg" alt="Semistatic bearing with 3.0mm Silicon Nitride balls" title="Semistatic bearing with 3.0mm Silicon Nitride balls" width="600">

# The semistatic bearing
This semistatic bearing is intended for use in trackball pointing devices such as those sold by [Ploopy](https://ploopy.co) and [efog.tech](efog.tech). It features a free-spinning main bearing that sits on three embedded subbearings, merging the concepts from static bearings and ball transfer units (BTUs).

Learn more about static bearings and BTUs in [the project background](https://github.com/scatterthought/semistatic-bearing/blob/main/background.md).

## Benefits
I'm confident that a semistatic bearing is better than a static bearing or a cheap BTU. It's smooth and quiet, stiction is virtually non-existent, and supplies are easy to get online. It's also easy to clean since the bearings are exposed.

And then there's the cost.

- With a 50-pack of G10 ceramic bearings for $15, you can make 12 semistatic bearings. 
- 12 printed bearing cases requires 10g of filament; at $20/kg, that's another $0.10. 
- Total cost: $15.10 for 12 units ($1.26 each).

The downside is, of course, that semistatic bearings are 3D-printed. So you have to access to a 3D printer and they won't be as durable as injection-moulded plastic or steel casings.

You're also still going to feel resistance similar to a static bearing, because there's still friction from the embedded bearings. You just won't have to fight stiction when you first move the ball. The amount of resistance will depend on the types of bearings you use and the weight/surface of the larger trackball (e.g. glossy versus matte finish).

Bosch Rexroth BTUs are still the absolute best choice if you want extremely low friction, are okay with some noise, and don't mind paying for the experience. The semistatic bearing is for everyone else...or as a stopgap while you're waiting for the BTUs you ordered to arrive.

## Available models
Additional models will be added over time, and I'm happy to consider requests (within reason).

| Semistatic bearing | Comments |
| ---- | ---- |
| [BR8](https://github.com/scatterthought/semistatic-bearing/blob/main/bosch-rexroth) | Replaces Bosch Rexroth 8mm BTU (KU-B8-OFK) |
| [VC75](https://github.com/scatterthought/semistatic-bearing/blob/main/veichu) | Replaces Veichu 7.5mm BTU (VCN310) |
| NL8H (in development) | Replaces generic NL-8H POM BTU |
| FLMT (in development) | Flushmount bearing to replace static bearings in mass-market trackballs |
| [PRFT](https://github.com/scatterthought/semistatic-bearing/tree/main/press-fit-bearings) | Minimal models for press-fit and remixing |

## Device compatibility list

I'm curating a [list of compatible devices](https://github.com/scatterthought/semistatic-bearing/blob/main/device-compatibility-list.md). If you have semistatic bearings working in a device or want to test and need assistance, please [open an issue](https://github.com/scatterthought/semistatic-bearing/issues).

## Considerations

### Durability
My design employs a three-pointed claw to hold the main bearing in place, and it's the only thing keeping the ball bearings from spilling out. I've found it to be very secure and there shouldn't ever be much force on it, but there's a small chance that it will break if the bearing is handled roughly. It may also wear down if you frequently remove the balls.

If your trackball lives on your desktop, I wouldn't expect the semistatic bearings to fail. However, you might want to keep some extras handy if you travel with it regularly.

### Maintenance
The bearing can be easily disassembled for cleaning or recovering/reusing parts. If you prefer a more permanent solution, the subbearings can be glued/caulked in place.

[This Reddit comment](https://www.reddit.com/r/Trackballs/comments/1tm2lfc/comment/onq967s/) recommends also filling in the gaps between the subbearings for easier cleaning. Just make sure that adhesive doesn't hamper the main bearing.
 
### Ball sizes
In all of my models, the main ball and subbearings are the same size. It would be possible to use smaller balls for subbearings, but since they don't spin their size is irrelevant. Their purpose is simply to provide low-friction surfaces for the main ball. So, it's more cost-effective to use the same size for all four balls (which can be bought in packs of 25/50/100/200).

## Print settings
All models are designed for 0.2mm layers.

- I recommend ironing (on all surfaces) for bearings with flat tops.
- No other special settings are required.

## Supplies
Any ball bearings should work, but I recommend ceramic balls of at least G10 (preferably G5).
- You'll need four ball bearings for each semistatic bearing.
- My testing has mostly been done with [uxcell 3mm Silicon Nitride G5](https://www.amazon.ca/dp/B0B5XK3BTM) and [uxcell 2.5mm Zirconium Oxide G5](https://www.amazon.ca/dp/B0B5XKBSV6/) ceramic ball bearings.
