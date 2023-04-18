# Swire Coca-Cola: Predicting Customer Success

##Description
During my pursuit of a Masters degree at the University of Utah I had the opportunity to complete a data science project for Swire Coca Cola as a part of my capstone coursework.  During this project I had the opportunity to complete the below major components of a analytics project. 

- Business Problem
- Analytical Objective
- Exploratory Data Analysis
- Results
- Ethical Considerations
- Business and Analytics Problem
- Appropriate Models
- Data Preparation and Feature Engineering
- Data Preparation: Variable transformation
- Evaluation
- Model Interpretation
- Results and Business Validation

##Challenges
There were two challenges that were reoccurring throughout this project.
1.	Multiple variables were highly correlated to our output variable that we would not have prior to the sales pitch Swire would give to prospects.  Many of these highly correlated variables were tied to historic orders of customers.  I chose to get rid of all of these predictors because they would artificially raise my prediction accuracy. 
2.	Most of the predictor variables used in the final model was categorical variables which did not lend itself well to getting an accurate prediction from my linear model.  All though their were other models that could predict better they tended to take so long to calculate that field deployment would most likely not be feasible.  
After evaluating my model performance, I realized that additional data would need to be gathered by Swire Coca Cola to generate more accurate predictions.  I’d recommend running the underlying code and then identifying feasible additions to the model in order to generate more accurate predictions.


##Next Steps
My recommended next steps is to look into gaining additional data to augment your existing data.  The data I’d recommend gathering includes. 

Group or Person
-How many years of business experience?
-Do they own multiple businesses?
--Do they own additional businesses of this type?
-How long has this customer been in business for?
-Is this a first, second, or third generation owned business?

Business Characteristics
-Does the company have a drive thru?
-What is the seating or physical capacity?
-How many parking spots are at the location?
-Is there off-street parking?
-What are the hours and days of operation?
-How many vehicles pass through that street?
-Can patrons’ access through multiple entrances?
-Can patrons access the physical location regardless of traffic lanes or are lanes partitioned?
-Does the customer have apps where customers can make purchases?
-Is the customer open during hours people normally purchase Coca Cola products?

Once this data is augmented to the existing data set I’d recommend rerunning and revaluating the models used in this analysis.  

##Credits
Everything executed on this was done by Brian Burdick with an exception of the power point group presentation.  My group members that completed the presentation slides included Derick Lee, Kayla Smartz, Sandy White, and myself.

Note: the file for customer sales data was to large to upload so I had to slice it into three parts.
