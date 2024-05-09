# ELECTRICITY-PROJECT
DOCUMENTATION

Purpose of the model:
The purpose of this model is to analyse the potential savings in electricity costs for Naomi after purchasing and installing a battery to store excess electricity generated from solar panels. The model shows a projection of her annual savings over a 20-year period under the following two scenarios:
Scenario 1:Electricity prices increase as expected by the government, 4% p.a.
Scenario 2:Electricity price increases start at 4% p.a. and rise each year by an additional 0.25% p.a, as estimated by Naomi.

The Data:
The model uses the data provided by Naomi, which includes hourly measurements of solar electricity generation and electricity usage for the year 2020. The data underwent several checks to ensure completeness and fitness for use. These checks involved:
Data Cleaning:This involved checking and handing any missing values,duplicates or structural  errors,filtering outliers as well as checking the data integrity.
Creating a graph to visualise the average solar electricity generation and the average electricity usage for each hour in a day to identify patterns and outliers
Assumptions used in the model were:
The solar electricity generation and electricity usage data for 2020 are representative of future years.
The annual electricity price inflation rates provided by the government and estimated by Naomi accurately reflect future trends.
The battery's maximum capacity is 12.5 kWh, and any excess solar electricity when the battery is full cannot be stored.
Electricity price increases by 4% per annum according to the government's expectations, and may increase by an additional 0.25% per annum as estimated by Naomi.
Electricity usage is prioritised in the order of current solar electricity generation, stored battery energy, and then purchased electricity from the provider.

Methodology
Each calculation stage in the model was produced as follows:
Data Preparation: Hourly data for solar electricity generation and electricity usage for 2020 are loaded into the model.
Calculation of Excess Solar Electricity:The excess solar electricity generated over electricity usage for each hour in 2020 is calculated.
Battery Charge Level Modeling:The cumulative battery charge level for each hour over 2020 is modelled, considering the maximum capacity of the battery.
Calculation of Electricity Purchased:The amount of electricity bought from the electricity provider for each hour in 2020, assuming a battery had already been installed, is calculated.
Calculation of Savings:The savings amount over 2020 from installing a battery compared to using only solar panels are calculated in dollars, using the electricity prices effective from 1st January 2022.
Projection of Annual Savings: The model projects forward for 20 years from 1 January 2022 and calculates the annual savings under two scenarios of electricity price increase.
Calculation of the Net Present Value(NPV): The NPV of the future annual savings for each scenario is calculated using a discount rate of 6% per annum.
Calculation of the Internet Rate of Return (IRR): The IRR for each scenario is determined by finding the discount rate that equates the NPV of future annual savings to the initial cost of the battery.

Further Checks:
Essential further checks were done to accuracy and reliability of the results.These checks include verifying data consistency, validating calculation methodologies, and comparing results against expected outcomes.
