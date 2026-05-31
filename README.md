## Database Analysis
# Overview
This practice set simulates real-world data analyst tasks using a classic retail database (Customers, Orders, Order Details, Products, Employees, Suppliers, Categories). You'll move beyond basic syntax and start thinking like an analyst by applying essential SQL concepts to solve business problems.

Core SQL Functions Covered
* DISTINCT:	Remove duplicate values
* NULL Handling:	Identify missing or incomplete data
* Aggregate Functions:	SUM, AVG, COUNT() for calculations
* GROUP BY	:Summarize data by categories
* HAVING	:Filter grouped results (after aggregation)
* ALIAS	Create readable column names for business users

Basic Analysis
* Task	
*	List unique countries where customers are located	DISTINCT, Alias
*	Find customers with no region assigned	NULL handling
*	Calculate total number of orders	COUNT(), Alias
* Financial & Revenue Analysis
* Task
*	Calculate total revenue (Price × Quantity × (1 - Discount))	SUM(), Business logic
*	Calculate average freight cost per customer	AVG(), GROUP BY
* Performance & Grouping
* Task	
*	Find total number of products per category	GROUP BY, COUNT()
*	Find suppliers who supply more than 5 products	GROUP BY, HAVING
* Customer & Market Insights
* Task	
*	Find customers with more than 10 orders	GROUP BY, HAVING
*	Find countries with more than 5 customers	DISTINCT, GROUP BY, HAVING
* Operational Audit
* Task
* Analyst Thinking Patterns
This isn't random practice. Each question reflects real-world logic:

Question You Ask	SQL Tool
* "Are we double counting?"	DISTINCT
* "What data is missing?"	NULL handling
* "How do we summarize this?"	GROUP BY
* "Which groups actually matter?"	HAVING
* "Can a business user understand this?"	ALIAS




