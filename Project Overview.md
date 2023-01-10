# Comcast consumer complaints
Comcast is an American global telecommunication company. The firm has been providing terrible customer service. They continue to fall short despite repeated promises to 
improve. 
Used different Python libraries such as 
- NumPy
- SciPy 
- Pandas 
- scikit-learn 
- matplotlib 
- BeautifulSoup to import data into Python environment and provide the 
trend chart for the number of complaints at monthly and daily granularity levels. 

## Data description
- Ticket #: Ticket number assigned to each complaint
- Customer Complaint: Description of complaint
- Date: Date of complaint
- Time: Time of complaint
- Received Via: Mode of communication of the complaint
- City: Customer city
- State: Customer state
- Zipcode: Customer zip
- Status: Status of complaint
- Filing on behalf of someone


## Findings and Conclusion
Used exploratory data analysis to find which complaint types are maximum i.e., around internet, network issues, or across any other domains.
- Created a new categorical variable with value as Open and Closed. Open & Pending is to be categorized as Open and Closed & Solved is to be categorized as Closed.
- Provided state wise status of complaints in a stacked bar chart.
- Found which state has the maximum complaints and which state has the highest percentage of unresolved complaints
- Provided the percentage of complaints resolved till date, which were received through the Internet and customer care calls.
