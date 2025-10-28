This is a console-based Java program that helps users take care of their plants — by reminding them when to water and fertilize.

It supports SDG 15 – Life on Land (protecting plants and promoting greenery).


---

⚙️ How It Works

1. Plant class (inner class):

Stores plant details:
name, watering interval, fertilizing interval, and days since last care.

Has methods to:

passDay() → adds one day

water() → resets watering counter

fertilize() → resets fertilizing counter

showStatus() → shows reminders




2. Main program (PlantCareApp):

Uses a menu system with choices:

1. Add new plant


2. Show all plants


3. Pass one day


4. Water a plant


5. Fertilize a plant


6. Exit





3. ArrayList<Plant> stores all added plants.


4. Helper methods:

readPositiveInt() → ensures valid number input.

performActionOnPlant() → finds plant by name to water/fertilize it.





---

🌿 Purpose (SDG 15 – Life on Land)

Encourages people to care for plants and the environment through consistent reminders — promoting sustainable living.
