# Lead_Scoring_Assignment

The main objectives of lead scoring are as follows:

Remove Junk by categorising leads on the basis of propensity to purchase
Gain insights to streamline lead conversion and address improper targeting
We have chosen L2AC (Leads to Application Completion) as our business metric, as choosing L2P (Leads to Payment) will aggressively drop the leads.
A lead is generated when any person visits CodePro’s website and enters their contact details on the platform. A junk lead is generated when a person who shares their contact details has no interest in the product/service.

 

Having junk leads in the pipeline creates significant inefficiency in the sales process. Thus, the goal of the data science team is to build a system that categorises leads based on the likelihood of their purchasing CodePro’s course. This system will help remove the inefficiency caused by junk leads in the sales process.

We have seen that we are creating three different pipelines for our use case.

Data Pipeline
Training Pipeline
Inference Pipeline

Since this is the first iteration of the model we are not aiming for high performance from the model but we are aiming to get value from the model as soon as possible by deploying the model into production, and then continuously improving our model once our baseline is deployed. Thus we will not focus much on developing the best possible model but we will make do with a simple model and focus more on deploying it into production.
