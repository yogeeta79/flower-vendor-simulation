**Project Description**

This project simulates the daily profit of a flower vendor who buys and sells bouquets under uncertain demand conditions.
The simulation allows users to modify values such as buying cost, selling price, order quantity, and lost profit to observe how these affect total profit.

**Problem Statement**

A vendor sells fresh flower bouquets at a market stall:

Buying cost: $8 per bouquet

Selling price: $15 per bouquet

Unsold bouquets: sold as scrap for $3

Lost profit: $7 per unsatisfied demand

**Demand types:**

Peak Day → 40 bouquets (prob = 0.25)

Normal Day → 30 bouquets (prob = 0.50)

Slow Day → 20 bouquets (prob = 0.25)

The vendor orders 35 bouquets daily. The program simulates total profit for multiple days.

**How It Works**

User enters cost and demand parameters in the UI.

JavaScript randomly selects the day type (Peak, Normal, or Slow) for each simulated day.

**For each day:**

Calculates sold, leftover, and excess demand.

Computes profit =
(Revenue from sales)−(Cost of bouquets)− (Lost profit from excess demand) + (Salvage from sale of unsold bouquets)

Results are shown in a table with total and average profit.

**Technologies Used**

HTML: Structure and input fields

CSS: Styling (modern dark UI)

JavaScript: Simulation logic and DOM updates
