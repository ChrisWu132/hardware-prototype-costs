# What a hardware prototype costs

Development fees and per-unit costs for devices Anvol's engineers in Shenzhen built. The lidar car is a delivered batch; the logic analyzer and tracked robot are reference figures from the same engineers. None of them is a fixed quote.

Readable version with the explanation: **[anvol.dev/costs](https://anvol.dev/costs/)**

| Project | Status | Units | Per unit | Development fee | Total |
|---|---|---:|---:|---:|---:|
| 24-channel logic analyzer | reference figures | 50 | ~$15 parts | $500 | **~$1,250** |
| Lidar line-following car | delivered batch | 10 | $150 | $5,000 | **$6,500** |
| Swing-arm tracked robot | reference figures | 1 | $6,000 | $30,000 | **$36,000** |

Total = development fee + units × per-unit price. All amounts in US dollars. Machine-readable: [`data/delivered-projects.csv`](data/delivered-projects.csv), [`data/delivered-projects.json`](data/delivered-projects.json) (the file names predate the reference rows; the `status` field says which is which).

## Common questions this answers

### How much does it cost to make a prototype of an electronic product?
One delivered batch: 10 lidar line-following cars for $6,500 ($5,000 development plus $150 per unit). Reference figures from the same engineers: about $1,250 for 50 units of a 24-channel logic analyzer, $36,000 for one swing-arm tracked robot. Most of the difference is the development fee, which follows the engineering work, not the unit count.

### Why is the price per unit so high in a small batch?
In batches of 5 to 20 units, Anvol's engineers see unit cost split roughly 40% parts, 40% circuit board and board assembly, 15% enclosure, 5% final assembly and testing. Board assembly is expensive because each run pays a fixed machine setup charge.

### What do these totals leave out?
Certification (none of the three went through FCC or CE; it is quoted separately when a product needs it), shipping and import duties (usually arranged by the customer once units leave the factory), scope changes, and extras such as tutorials, training or a live demo.

### What does development cost for a simple device vs a robot?
As a rule of thumb from the same engineers: about $500 to $3,000 for a simple small device, $3,000 to $10,000 for a small robot or multi-board device, $10,000 to $30,000 for a larger robot. These are experience ranges, not quotes; compare against the three projects above.

### What about 100 or 1,000 units?
Not published. No priced build was made at that volume, and small-batch unit prices should not be stretched to it.

## Get a number for your own device

Send what you have (an idea, a sketch, a board or a working prototype) through the [project form on anvol.dev](https://anvol.dev/#quote). Anvol's engineers reply within 12 hours; you get a written scope with price and date before any work starts.

## Updates

New projects are added as they ship. Last updated 2026-10-18: the logic analyzer and tracked robot rows are now marked as reference figures, with the figures shown on anvol.dev.

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Cite as "Anvol, What a hardware prototype costs, https://anvol.dev/costs/".
