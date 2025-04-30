![image](https://github.com/user-attachments/assets/57203e7b-d9a9-4701-bb4e-2e8f25d6a3d6)

**INTRODUCTION**

Startups are built on innovation, ambition, and the promise of disrupting industries. Yet, despite their potential, a significant percentage don’t survive beyond the first few years.

Diving into startup failures felt like solving a giant business mystery why do some ideas take off while others crash and burn? Was it poor timing? A flawed business model? Too much competition? Every data told a story, and uncovering the hidden patterns felt like being a detective in the world of entrepreneurship.
From analyzing why some startups thrived while others faded, this project uncovers the key reasons behind startup failures by analyzing real-world data. I examined metrics like years of operation, funding raised, competition impact, market fit challenges, monetization struggles, dependency on external platforms, and regulatory pressures. Our findings reveal the most common pitfalls that early-stage businesses face and offer insights into how startups can navigate these risks.

This project uncovers the key reasons behind startup failures by analyzing real-world data. I examined metrics like years of operation, funding raised, competition impact, market fit challenges, monetization struggles, dependency on external platforms, and regulatory pressures. Our findings reveal the most common pitfalls that early-stage businesses face and offer insights into how startups can navigate these risks.

Whether you’re a founder, investor, or startup enthusiast, understanding these trends is crucial for building sustainable businesses.

**DATA CLEANING**

The dataset was gotten from Kaggle, and I applied a few data-cleaning methods to make it consistent.
**Duplicate Removal:** Identified and deleted duplicate rows to prevent inconsistencies and ensure accurate analysis.
**Text to Columns:** Split combined data points into separate columns, properly categorizing each value for better readability and processing.
**Date Formatting:** Standardized all date entries to a uniform format, ensuring consistency in time-based analysis.
**Removing Extra Spaces:** Trimmed unnecessary spaces in text fields to maintain consistency and improve data accuracy.
**Data Type Correction:** Ensured all columns had the correct data types (e.g., numbers stored as numerical values instead of text) to prevent calculation errors.
**Standard Table Conversion:** Transformed the dataset into a structured Excel table, enabling easier management, automation, and dynamic analysis.

**PRE ANALYSIS**

![image](https://github.com/user-attachments/assets/521a47ad-8976-4cd6-94f6-90e5039f4d90)

Before building the charts, I conducted a pre-analysis to better understand the dataset and shape my storytelling approach. This involved breaking down the datase into meaningful components.

I categorized the data points into Dependent and Independent values, helping me identify key relationships and extract meaningful insights. From these groupings, I generated critical questions to uncover potential patterns and trends. By analyzing the data early, I identified preliminary insights that guided the narrative and ensured a focused analysis. With a clear understanding of relationships between data points, I created a compelling story that linked findings to real-world impact. Lastly, I identified key industry stakeholders and defined success metrics, ensuring the insights were relevant and actionable.

**ANALYSIS OF THE CHARTS**

**Number of Startups that Failed by Sector**

![image](https://github.com/user-attachments/assets/c3736d89-b34f-46eb-a5ad-ef76c61bd6f5)

The Entertainment sector had the highest number of failed startups (46), followed closely by Retail (45). Technology (33) and Healthcare (32) also saw significant failures, possibly due to high competition and regulatory challenges. Energy, Education, and Real Estate had moderate failure rates, while Finance had the least failures (23), likely due to more structured business models. This suggests industries with heavy consumer reliance or innovation demands face higher risks.

**Trend of Failed Startups**

![image](https://github.com/user-attachments/assets/dc2c8a80-3dbe-45e4-8d56-92081b2e7e8d)

Startup failures fluctuated over the years, with a notable drop to 19 in 2019 (the least failed year), possibly due to favorable market conditions or increased funding opportunities. However, failures rose again from 2020 onwards, reaching a peak of 39 in 2024 (the most failed year), indicating rising challenges such as economic downturns or increased competition. The sharp increase from 2022 to 2024 suggests worsening conditions for startups. The COVID-19 pandemic (2020–2021) might have impacted businesses, but the post-pandemic surge in failures is concerning.

**Average Years of Operation By Sector**

![image](https://github.com/user-attachments/assets/99b71921-89b7-4431-a779-f3fa5a60ae4a)

Technology startups had the shortest lifespan, averaging 6.70 years, possibly due to rapid innovation cycles and high competition. In contrast, Real Estate startups lasted the longest at 8.73 years, likely benefiting from stable market demand and long-term investment returns. Other sectors, such as Energy (7.86 years) and Healthcare (7.72 years), had relatively higher longevity, reflecting their essential nature and capital-intensive operations.

**Startups Budget**

![image](https://github.com/user-attachments/assets/8c076f8d-8162-4f06-a956-a7d63a749980)

Startups were fairly distributed across funding levels, with 26% being adequately funded and another 26% well-funded, indicating that a majority had reasonable financial backing. However, 25% were severely underfunded, and 23% were somewhat underfunded, highlighting that nearly half of the startups faced financial constraints, which could have contributed to their failure.

**Effect of Giant Companies on Failed Startups**

![image](https://github.com/user-attachments/assets/3d3958eb-d84e-469a-b5a7-519eeee64964)

Nearly 30% of startups directly competed with tech giants, while 26% failed due to competition from them, emphasizing the dominance of major players. However, 23% managed to survive against these giants, showing resilience. Meanwhile, 22% were not affected, indicating that not all failures were linked to industry giants.

**Reason for Failure**

![image](https://github.com/user-attachments/assets/085b51da-91dc-46fe-911c-0fcae241b40b)

The top reason for startup failure is the lack of a product-market fit (15%), highlighting the challenge of meeting consumer needs. Poor monetization strategies (13.6%) and running out of funds before profitability (12.7%) are also major hurdles. Additionally, failure to adapt to market trends (12.7%) and underestimating operational costs (11.8%) further contribute to closures. Over-reliance on single platforms (11.4%), competition from giants, and overhyped expectations also pose risks.

**Dependency on Other Platforms**

![image](https://github.com/user-attachments/assets/35411b68-9b23-4ca9-836e-f81a1511e7c6)

Nearly 57% of startups relied on external platforms, with 28.46% being overly dependent, making them vulnerable to policy changes or platform shifts. 23.46% had their own platforms, providing more control, while 19.62% operated independently. This highlights the risks of platform dependency, as startups without their own infrastructure may struggle with sustainability.

**Customer Trust in Startups**

![image](https://github.com/user-attachments/assets/1ca0c973-36c1-424b-9784-e6cc8e3b4b87)

Customer trust played a crucial role in startup success. 29.2% of startups faced major trust issues, which likely contributed to failure. Meanwhile, 25.4% had no trust issues, suggesting that trust alone wasn’t always a success factor. 23.8% actively built strong trust, while 21.5% had some trust concerns. This highlights how startups with credibility issues struggled more, reinforcing the importance of transparency and reliability.

**OBSERVATIONS**

![image](https://github.com/user-attachments/assets/c9687e28-9ba4-4393-a396-b5187cc7bdfb)

Among all failed startups, 29% competed with top companies, 26% lost, 23% survived alongside them, and 22% were unaffected. In total, 55% struggled against industry giants, highlighting their overwhelming market power.

Startup failures fluctuated from 2016 to 2024, peaking at 39 in 2024. Numbers were stable from 2017–2018, dropped in 2019, then surged in 2020 before declining again. The sharp rise in 2024 could be linked to economic downturns or funding shortages.

Trust issues played a crucial role, with 29.2% of failed startups facing major customer trust problems, while 25.4% had none. About 23.8% were deemed trustworthy, but nearly half of all failures had some level of trust-related concerns.

The Entertainment sector had the most failed startups (46), followed by Retail (45), Tech (33), and Healthcare (32). Many products offered by the Entertainment startups lacked demand, while Retail Startups were overhyped. Also Tech startups had the lowest product in demand.

Over 56% of startups failed due to dependency on external platforms, with 28.46% heavily reliant and another 28.46% moderately dependent. Meanwhile, 23.46% operated independently, and 30.77% of overhyped startups struggled due to excessive reliance on other platforms.

The top failure reason was lack of market fit (15%), followed by poor monetization (13.6%), running out of funds (12.7%), and failure to adapt (12.7%). Other key issues included underestimated costs, over-reliance on single platforms, strong competition, and overhyped products.

Real estate startups had the longest lifespan (8.73 years), followed by Energy (7.86) and Healthcare (7.72). Retail and Education both lasted 7.67 years, Finance 7.61, and Entertainment 7.54. Tech startups had the shortest lifespan at just 6.70 years.

**RECOMMENDATIONS**

![image](https://github.com/user-attachments/assets/2dd3237c-9897-4685-97f5-2b4bfe2ab6c5)

Since 55% of startups failed due to competition with giants, they should target niches with limited giant presence. Instead of direct competition, they can create unique products or partner with established companies to leverage their market reach.

With failure rates peaking in 2024, startups need counter-strategies like financial reserves during growth phases. Diversifying revenue sources prevents reliance on a single income stream, reducing risks from economic shifts.

Since 56% of failures were due to platform dependency, startups should develop contingency plans and flexible solutions. They should diversify across multiple platforms to avoid major disruptions.

Startups should validate demand before scaling to prevent wasted resources. Overhyping products without meeting customer expectations leads to failure, so regular product updates are essential.

With 50.7% of failures tied to trust issues, startups must build transparency and strong security. Clear communication, delivering promises, and protecting customer data strengthen trust.

Products and services should align with changing customer needs. High-failure sectors like Entertainment and Retail can learn resilience from Finance and Real Estate to improve stability.

Low-cost sectors should focus on long-term growth, sustainable scaling, and customer retention. Consistent innovation, gradual gains, and avoiding greed-driven mistakes ensure success.

**CONCLUSION**

Startup failures are often the result of multiple interconnected factors, including competition with industry giants, overreliance on external platforms, poor financial planning, lack of market demand validation, trust issues, and unsustainable business models. The data reveals that startups must strategically position themselves in less saturated niches, diversify revenue streams, and implement contingency plans to mitigate risks. Transparent communication, strong security measures, and customer trust are crucial for long-term success. Additionally, aligning products with evolving market demands and learning from resilient industries can enhance survival rates. By adopting these insights, startups can navigate challenges more effectively and increase their chances of sustainable growth.

