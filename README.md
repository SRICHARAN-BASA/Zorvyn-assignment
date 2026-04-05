**FinFlow - A Financial tracking dashboard**

FinFlow is a personal command center for your money. It takes the messy reality of daily spending and turns it into a clean, visual story that helps you make better financial decisions.

Here is how the project works, component by component:

1. The Visual Dashboard (The Face)
This is the first thing you see. It uses a Dark Mode aesthetic with "Glassmorphism" (frosted glass effects) to feel modern and high-end. It’s designed to be Responsive, meaning it automatically rearranges itself to look perfect on a laptop, a tablet, or a smartphone.

2. Real-Time Stats Cards (The Pulse)
At the top of the screen are three "Quick-Look" cards: Total Wealth, Inflow, and Outflow. These act as the heartbeat of the app—every time you add a transaction, these numbers update instantly so you always know exactly how much "net" money you have left.

3. Interactive Charts (The Storyteller)
Instead of just looking at a list of numbers, FinFlow uses Chart.js to draw two main visuals:

The Growth Line: Shows if your bank balance is trending up or down over the month.

The Expense Donut: Breaks down your spending by category (like Rent vs. Food) so you can see where your money is actually going.

4. Smart Search & Analysis (The Assistant)
This is a "power feature." When you type a word like "Grocery" into the search bar, the app doesn't just filter the list; it opens a Intelligence Popup. This popup instantly calculates the total amount you’ve spent only in that category, giving you a deep dive into your habits in seconds.

5. Master Ledger & Role Toggle (The Control)
The ledger is a clean, organized table of every transaction you’ve made. To make it feel like a professional app, I added a Role Toggle:

Admin Mode: You have full power to add or delete entries.

Viewer Mode: You can see everything, but you can't change the data. This simulates how real-world secure apps handle different types of users.

6. Local Storage (The Memory)
The app uses Web Storage to remember your data. This means you don't need to log in or save your work; your financial history stays safely tucked away in your browser's memory, ready for you the next time you open the link.
