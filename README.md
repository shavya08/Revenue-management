# Revenue-management
Developing a revenue management model for a container shipping company using Python

Case Description - 

Business Background:   

Warwick Container Group (WCG) is a dynamic company that specializes in offering a wide range of flexible leasing options tailored to meet both short-term and long-term needs. The company operates with 75 branch offices across Europe and an additional 30 in the United States and the headquarters is located in Felixstowe. In the container leasing industry, price is often the predominant factor influencing customer decisions, as the business is largely perceived as commodity-based. Nonetheless, WCG believes that it has a competitive advantage over its smaller competitors by leveraging superior service quality and offering unique value-added services.  

In the face of a highly competitive container leasing market, where shipping lines and leasing firms are aggressively expanding their fleets to satisfy escalating demand, WCG recognizes the need for differentiation. Innovation in leasing solutions and pricing models has become a cornerstone of industry competition.  

Inspired by the remarkable success of revenue management in the airline industry, WCG's management has decided to explore its potential within their own operations. Nonetheless, the company's inexperience in this domain constitutes a considerable challenge and has been met with scepticism by certain members of the management team. In an effort to address these challenges and alleviate concerns, the management has proactively formed a dedicated revenue management team. 

This team is tasked with investigating and harnessing the potential benefits that revenue management techniques can bring to the company.  Before looking into the specific responsibilities of this newly formed revenue management team, let’s first learn about the container leasing operations as well as the decisions related to pricing and capacity management. 

Container Leasing:  

Container leasing operates similarly to a car leasing (or rental), but on a bigger scale. Containers can be booked (or leased) at the local branch offices. Despite the advent of digital booking capabilities, a 
predominant number of customers persist in utilizing traditional paper-based methods at these branches. Leasing rates are typically set on a per day basis, with short-term lease rates are higher than the long-term rates. To maintain market competitiveness, WCG periodically aligns its pricing with that of its competitors, particularly when customers engage in price negotiations. WCG’s service model allows customers (including shipping companies or transportation agents) to increase the flexibility of their logistics operations without the need for significant capital investments, especially useful for businesses with volatile or seasonal shipping volumes.  

Pricing and leasing decisions:  

WCG serves a wide range of customers, from individuals and small businesses to big corporations. While some customers lease containers for three – four months, some others require it for one or two weeks. The demand for containers is subject to seasonal variations and can fluctuate accordingly. Pricing in the container leasing industry is based on several variables: the type of container, the duration of the lease, the type of the lease (either one-way or round-trip), the location of the branch, and seasonal demand. As noted previously, branch managers have the authority to adjust prices to match those of competitors during negotiations with customers. Moreover, they have the discretion to determine the acceptance of one-way or round-trip container bookings. One-way bookings, where customers drop off containers at different branches, present logistical challenges and are, therefore, typically more challenging to manage.  

To measure their profitability and efficiency, WCG uses two key metrics: load factor and return on investment (ROI), alongside their annual total revenue. The load factor serves as an efficiency metric, indicating the degree to which WCG maximizes the use of its container fleet. A high load factor denotes that a significant portion of the container stock is leased out, typically correlating with greater revenue efficiency and effective translation of available capacity into sales. However, while a high load factor is usually a positive indicator of performance, it is not the sole measure for assessing efficiency and 
profitability. ROI is mainly used to evaluate the performance of different branches. It is computed as the ratio of the average revenue generated per container to its cost. For instance, if the cost of a 
typical container is £15,000, the ROI would be determined by taking the average revenue per container and dividing it by £15,000.  

Your group has been tasked with executing the revenue management (RM) project for WCG. For the purpose of your analysis, WCG has provided a dataset from one of their UK branches. Please refer to the enclosed readme file for a detailed description of the data.  WCG requires you to formulate a proposal that will guide the management on the application of RM within the company, highlighting both its potential advantages and possible challenges. Your document is not intended as a sales pitch to WCG. Therefore, the document should not only clearly and accurately describe the proposed RM methodology and demonstrate its potential value for WCG, but also critically evaluate the chosen approach noting any limitations or drawbacks where appropriate (the technical details can and should be included.)

The following questions should be answered in the document:  

1. [15 marks] Discuss to what extent the business environment of WCG (including customers, data availability, demand patterns and so on) is suitable for introduction of RM. Compare with RM for airline operators – are there methodological similarities, and if so, what are they?

2. [35 marks] For the provided data, formulate and implement a linear programming RM model with the objective of maximising overall revenue. Start by defining resources and products. Make sure you state the linear programming formulation as compact as possible (avoiding unnecessary notation). Explain and define variables, constraints and the objective. Report the revenue, load factor and ROI improvements of your approach over what was actually achieved according to the data (assume all containers cost £15,000). What do these results tell us regarding the potential of implementing a revenue management solution at WCG?

4. [20 marks] How could your approach be implemented at WCG branch to support data-driven decision-making? What limitations does the current approach have, and how could they be (at least partly) addressed?  
