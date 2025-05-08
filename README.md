Embedding in Web Portal: 
It can be embedded using Power BI Embedded, utilizing the Power BI REST API or JavaScript SDK. 
A workspace collection and capacity must be set up in Azure to support embedding.


User Authentication & Security:
Authentication is handled via Azure Active Directory, ensuring secure access through organizational credentials. 
Row-Level Security (RLS) is implemented within Power BI using DAX filters and security roles, dynamically restricting data visibility based on the logged-in user's identity.


Optimization for Large Datasets:
Using Import mode for faster performance or DirectQuery for real-time data with query folding.
Applying data reduction techniques such as aggregations, summarization tables, and filtering unused columns/rows during Power Query steps.
Leveraging incremental data refresh for efficient updates and using Star Schema model for performance scalability.
Minimizing visuals per page and avoiding high-cardinality columns in slicers.
