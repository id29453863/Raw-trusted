# Card Lot App - Starter Build
Your logic: Price ALL, Grade only $50+ potential, Sell where it makes most.

## What this does RIGHT NOW (Phase 1):
1. Takes your lot photo (20 cards on BLACK poster board)
2. Slices it into 20 perfect crops (fixes your slice button issue)
3. Prices each crop placeholder + routes to best lot

## How to run on your laptop:
1. Open this folder in VS Code
2. Open Terminal in VS Code: Terminal > New Terminal
3. Run: pip install -r requirements.txt
4. Put your lot photo in this folder named: lot.jpg
5. Run: python main.py
6. Check /crops folder - should have 20 perfect crops

## Your Business Logic Built In:
- PSA10 >= $50 + looks clean (8.5+) = VERIFY Photo 2 - List at 15% of PSA10 ($45 on $300 card)
- Raw >= $20 = $20+ Singles
- Same Team >= 8 or Same Player >=5 = Team Lot (sells for more than $1 singles)
- Else = Dollar Bag

Next: We will connect real eBay comps after slice works.
