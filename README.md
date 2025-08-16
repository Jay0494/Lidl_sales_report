### **Data Analysis & Strategic Recommendations: A Lidl Case Study**

---

### **1. The Story of the Data** 🎯

When I first looked at this sales data, it wasn't just a bunch of numbers. It was a story about how people shop at Lidl across England and Wales. My job was to figure out what that story was, especially for our London High Street store, which seemed to be having a tough time. I started with a few big questions to guide me:
1. Who's shopping where, and which stores are really hitting it out of the park?
2. What are people actually buying? The stuff that makes us money, or the things they just grab on their way out?
3. How much do holidays really matter? Do they drive our whole business, or is it our everyday customers?

Answering these would give us the real picture behind the London store's struggle.

***

### **2. My Process: Getting the Data to Talk** 🧹

To get the full story, I knew the data had to be perfect. Raw data is messy—it's got typos, weird dates, and numbers that are in the wrong format. So, I put on my "data detective" hat.

* **Python was my main tool.** Using a library called pandas, I went through the dataset, line by line. I made sure all the dates were formatted correctly so I could see sales trends over time. 
* **I also used Power Query.** This helped me quickly pull all the different data files together and clean up any inconsistencies. It's great for making sure everything is standardized and ready for analysis.
* Using DAX I also created a new column to label transactions as either "Holiday" or "Non-Holiday," which was key to answering one of my main questions. It was all about setting the stage so the numbers could tell their truth.

By the end of this process, the data was clean, organized, and ready to reveal its secrets.

***

### **3. What I Found: The Big Picture** 📊

Once the data was prepped, some clear patterns jumped out.

**3.1. The North is Our Champion**
It was pretty clear from the start that our stores up north were leading the charge. Places like **Leeds North** and **Sheffield Market** were our all-stars, pulling in the most revenue and selling the most items. This told me that our brand is incredibly strong in those communities. Meanwhile, **London High Street** was lagging behind, a fact I immediately flagged for a deeper look.

**3.2. A Tale of Two Shopping Baskets**
When I dug into the products, I saw something fascinating.
| Product Category | Revenue | Quantity Sold |
| :--- | :--- | :--- |
| **Top Sellers** | | |
| 1. Meat | £13.5k | 3.89k |
| 2. Dairy | £11.9k | 7.97k |
| **Bottom Sellers** | | |
| 3. Bakery | £4.72k | 3.91k |
| 4. Beverage | £4.06k | 4.06k |
**Meat** is our undisputed heavyweight champ for revenue. But while it brings in the big bucks, **Dairy** and **Beverages** are what customers are buying the most of. It’s like we have two types of shoppers: one coming in for a big weekly shop, and another just grabbing a few everyday essentials.

**3.3. Holiday Magic (and Everyday Loyalty)**
The most surprising finding was the holiday split. Our sales were almost perfectly divided, with about 50% from holiday seasons and 50% from regular days. This is huge! It means that while our holiday specials are great, our business isn't just a seasonal thing. People rely on us all year long, which speaks to the incredible trust and loyalty our brand has built.

***

### **4. The London Problem: A Critical Diagnosis** 🔎

This is where the story got interesting. The London High Street store had low revenue, but when I checked the number of items sold, it was similar to our successful stores. This was my "aha!" moment. The problem wasn't that people weren't coming in; it was that they weren't spending much when they did.

My next step was to figure out why. A quick calculation showed me that the **average item price was just £2**. This confirmed my suspicion: London High Street customers were buying a lot of cheap stuff. It makes perfect sense when you think about the location—it's on a busy high street, full of commuters, office workers, and tourists looking for a quick lunch or a snack, not a full weekly grocery haul. They're grabbing a drink, a sandwich, or a bakery item and that's it.

***

### **5. The Solution: A New Strategy for London** 📈

Knowing the real problem was low spending per visit, my recommendations are all about inspiring people to add a little more to their basket.

1.  **Create a "Food-to-Go" Powerhouse.** We need to grab those quick-stop shoppers right as they walk in. By creating a dedicated section near the entrance with premium sandwiches, salads, and ready-meals, we can turn a £1 transaction into a £5 one.
2.  **Launch a "London Lunch Deal."** Let’s make it easy for them. A simple "Main + Snack + Drink for £4" offer encourages a multi-item purchase. It’s a win-win: they get a great deal, and we increase our average transaction value.
3.  **Elevate the Checkout.** The checkout area is prime real estate. Let’s put some of our higher-end impulse buys there—things like our premium chocolate bars or single-serve bottles of craft beer or wine. It’s a great way to tempt people with a little treat.
4.  **Go Digital with the Lidl Plus App.** We can send a personalized message to customers in that store. Something like, "Spend £10 and get a free croissant!" It gives them a simple, direct reason to buy an extra item or two.

By focusing on these specific, targeted strategies, we can transform the London High Street store from an underperformer into a vibrant, high-value asset that truly understands its unique customers.
