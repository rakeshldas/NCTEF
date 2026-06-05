\# 3. Problem Statement



\## Line: W**ildlife disturbance**

\#Explanation

Too many tourists can disturb animals.

Examples:

\* noise from vehicles

\* animals changing movement patterns

\* stress during breeding season

\* disruption of feeding areas

In the model, this becomes a \*\*wildlife-risk constraint\*\*.





\## Line: Habitat destruction

\#Explanation

This means the natural home of animals may get damaged.

Examples:

\* forest trails expanding

\* waste accumulation

\* vehicle movement damaging soil

\* construction near sensitive areas

In OR language: This is an ecological cost of tourism.





\## Line: Carbon emissions

\#Explanation

Tourism involves transport.

Transport creates pollution, especially from:

\* diesel jeeps

\* buses

\* cars

\* generators

\* tourism infrastructure

In the model, carbon emission is measured and controlled.





\## Line: Governance failures

\#Explanation

Governance means proper rules, monitoring, compliance, and accountability.

Governance failure means:

\* no visitor control

\* weak forest monitoring

\* no waste rules

\* poor safety systems

\* no reporting mechanism

In the model, this becomes a \*\*governance compliance constraint\*\*.





\## Line: Water and waste stress

\#Explanation

More tourists means more use of:

\* water

\* food

\* plastic

\* sanitation

\* waste disposal

If not managed, this creates environmental pressure.

That is why waste management and water conservation are included as sustainability actions.





\## Line: Biodiversity loss

\#Explanation

Biodiversity means variety of life:

\* animals

\* birds

\* insects

\* trees

\* plants

\* microorganisms

Uncontrolled tourism can reduce biodiversity.

In the model, this is handled through wildlife risk and conservation investment.





\## Line: ESG compliance issues

\#Explanation

ESG means:

\* \*\*E = Environmental\*\*

\* \*\*S = Social\*\*

\* \*\*G = Governance\*\*

ESG compliance means the tourism project should be environmentally responsible, socially beneficial, and properly governed.

In the model, ESG becomes a measurable score.





5\. Project Objectives



\## Line: Project Objectives

\#Explanation

This section lists what the project wants to achieve.

In OR, objectives help define the direction of the mathematical model.



\## Line: 1. Optimize tourist allocation across eco-tourism sites

\#Explanation

This means deciding:

> How many tourists should go to each site?

Example:

\* Gir Forest: 500 tourists

\* Periyar: 400 tourists

\* Sundarbans: 250 tourists

The model does not randomly decide. It considers capacity, revenue, carbon, ESG, and wildlife risk.





\## Line: 2. Minimize wildlife disturbance

\#Explanation

This means reducing the negative impact on animals.

In mathematical terms:

> Wildlife risk should be kept as low as possible.





\## Line: 3. Reduce carbon emissions

\#Explanation

This means choosing cleaner tourism operations.

Examples:

\* more EV safari

\* more walking trails

\* more cycling

\* solar energy

\* waste reduction





\## Line: 4. Maximize carbon-credit revenue

\## Explanation

If the project reduces carbon emissions, that reduction can be converted into carbon credits.

Carbon credits may create additional income.

So the model asks:

> Which sustainability actions reduce enough carbon to generate financial value?





\## Line: 5. Improve ESG score

\#Explanation

The model tries to improve the ESG performance of each site.

Better ESG means:

\* better environmental care

\* better social benefit

\* better governance





\## Line: 6. Improve sustainability practice index

\#Explanation

Sustainability Practice Index, or SPI, is a combined score.

It may include:

\* waste management

\* water conservation

\* biodiversity monitoring

\* community participation

\* clean energy

Higher SPI means better sustainability performance.





\## Line: 7. Allocate conservation investment efficiently

\#Explanation

This means deciding:

> Where should the sustainability budget be spent?

Example:

Should money go to:

\* habitat restoration?

\* solar energy?

\* biodiversity monitoring?

\* anti-poaching system?

The model chooses the best investment mix.





\## Line: 8. Select sustainable transport modes

\#Explanation

The model decides which transport modes should be used.

For example:

\* diesel jeep has more pollution

\* EV safari has less pollution

\* cycling has almost zero emission

\* walking trail has no fuel emission





\## Line: 9. Improve local livelihood opportunities

\#Explanation

Tourism should benefit local people.

Examples:

\* local guide employment

\* local food vendors

\* eco-lodge staff

\* artisans

\* transport operators

In the model, this becomes a livelihood benefit value.





\## Line: 10. Maintain ecological carrying capacity

\#Explanation

Carrying capacity means:

> Maximum tourists a site can handle without ecological damage.

Example:

If Sundarbans can safely handle only 400 tourists, the model should not send 800 tourists there.





\## Line: 11. Ensure governance compliance

\#Layman Explanation

This means tourism should follow proper rules.

Examples:

\* visitor monitoring

\* waste audit

\* safety rules

\* wildlife protection protocol

\* transparent reporting





\## Line: 12. Develop an analytical and computational optimization framework

\#Explanation

This means the project has two parts:

1\. \*\*Analytical\*\*

&#x20;  Mathematical equations, logic, formulas.

2\. \*\*Computational\*\*

&#x20;  Python code, OR-Tools solver, graphs, results.

Together, they form a complete OR project.







\# 6. Real-World Interpretation

\## Line: # Real-World Interpretation

\#Explanation

This section explains how the model can be used practically.

It connects mathematics with real decision-making.



\# Line: Which eco-tourism sites should be promoted?

\#Explanation

The model helps identify sites that are suitable for tourism promotion.

A site should be promoted only if it has:

\* good capacity

\* manageable wildlife risk

\* good ESG

\* reasonable emission level

\* strong livelihood benefit





\## Line: How many tourists should be allowed?

\#Explanation

This is the tourist allocation decision.

The model decides safe visitor numbers.

It prevents overcrowding.





\## Line: Which transport mode should be encouraged?

\#Explanation

The model checks transport options and chooses cleaner ones.

Example:

If EV safari gives lower emissions than diesel jeep, the model may prefer EV safari.





\## Line: How much conservation investment is needed?

\#Explanation

The model decides how much money should go into sustainability actions.

It prevents underinvestment and wasteful overinvestment.





\## Line: How can carbon-credit revenue be generated?

\#Explanation

Carbon-credit revenue comes from measurable carbon reduction.

The model helps identify which actions can reduce carbon and generate income.





\## Line: How should sustainability actions be prioritized?

\#Explanation

The model ranks actions based on impact.

For example:

\* biodiversity monitoring may reduce wildlife risk

\* solar energy may reduce emissions

\* community training may improve social ESG





\## Line: How can ESG scores be improved?

\#Explanation

The model shows which actions improve ESG.

For example:

\* waste management improves environmental score

\* community training improves social score

\* governance reporting improves governance score





\## Line: How can wildlife protection be maintained while increasing tourism revenue?

\#Explanation

This is the central trade-off.

The model asks:

> Can we earn tourism revenue without harming wildlife?

This is exactly where OR is useful.


# Eco‑Tourism Sites Dataset

\#Explanation

This dataset gives the basic input values for each eco-tourism site. It shows how many tourists each site can safely handle, how much revenue each tourist generates, and how sensitive the wildlife is. Sundarbans gives the highest revenue and ESG score but also has the highest wildlife sensitivity and carbon impact. Jim Corbett has the highest visitor capacity but lower sustainability strength. Periyar has lower revenue but is environmentally safer because of low carbon and low wildlife sensitivity. The optimization model uses this table to decide where tourists should go, which sites need restrictions, and where sustainability investment is required. Overall, the table shows the trade-off between revenue, ecology, carbon, and ESG performance.




# Sustainability Actions

\#Explanation
This table represents the sustainability actions that can be selected by the optimization model to improve eco-tourism performance. Each action focuses on solving a different environmental or social challenge. Habitat Restoration helps recover damaged forests and ecosystems, while Anti-Poaching Systems protect wildlife from illegal activities. Waste Management reduces pollution caused by tourism activities, and Solar Energy Installation lowers dependence on fossil fuels. Water Conservation improves sustainable water usage through harvesting and treatment systems. Community Training supports local employment and awareness programs, whereas Biodiversity Monitoring helps track wildlife and ecological health scientifically. Green Transportation promotes electric and low-emission mobility systems. Overall, these actions help improve ESG scores, reduce carbon emissions, protect biodiversity, and strengthen sustainable tourism practices.



\# Sets
#Explanation
These sets represent the different categories used in the mathematical optimization model. I represents the set of eco-tourism sites such as Gir Forest or Sundarbans, while T represents the different time periods like peak, regular, or monsoon seasons. M represents the available transport modes such as EV safari, buses, or walking trails. A represents the sustainability actions like solar energy or biodiversity monitoring that can be selected by the model. S represents the wildlife species or biodiversity elements affected by tourism activities. Finally, K represents the ESG dimensions — Environmental, Social, and Governance — used to evaluate sustainability performance. Together, these sets help organize the optimization problem systematically and allow the model to make structured decisions across multiple dimensions.



\# Decision Variables

\#Explanation

These decision variables represent the actual choices made by the optimization model. 

(x\_{it}) decides how many tourists should be allocated to site (i) during time period (t), making it the core tourist allocation variable. 

(y\_{it}) is a binary decision variable that determines whether a site should be promoted or opened; a value of 1 means the site is active, while 0 means it remains closed. 

(q\_{imt}) decides how tourists are distributed across different transport modes such as EV safari, buses, or cycling. 

(z\_{iat}) represents the amount of sustainability or conservation investment allocated to a particular action like solar energy or biodiversity monitoring. 

(c\_{it}) measures the carbon-emission reduction achieved at each site, while 

(r\_{it}) calculates the carbon-credit revenue generated from those reductions. 

(E\_{ikt}) represents the ESG score across Environmental, Social, and Governance dimensions, and

(\\rho\_{ist}) measures wildlife disturbance risk caused by tourism activities. 

Finally, (u\_{iat}) is another binary variable that determines whether a sustainability action is selected or not, helping the model decide which conservation activities should actually be implemented.



\# Parameters

\#Explanation

These parameters are fixed input values used by the optimization model. 

Ri gives revenue per tourist, 

Capi gives safe ecological capacity, and 

Dt gives tourist demand in each period. 

EFm measures transport emissions, 

PCC gives carbon-credit price, and 

Bt gives the available sustainability budget. 

Wis captures wildlife sensitivity, 

Li measures local livelihood benefit, 

θa shows carbon-reduction efficiency, and 

λak shows how each action improves ESG performance.



\# Maximize Total Sustainable Value

\#Explanation

The objective function maximizes the total sustainable value Z by combining tourism revenue, carbon-credit revenue, livelihood benefit, ESG improvement, wildlife-risk control, emission control, and sustainability investment. 

The terms Rixit, rit, Lixit, and Eikt represent positive value creation. In practical modeling, wildlife risk ρist, emissions EFmqimt, and investment cost ziat should be treated as penalty/cost terms, so they are minimized or subtracted. Overall, the model balances economic growth with environmental protection, ESG performance, and community benefit.





\# Constraint 1: Tourist Allocation Balance

\#Explanation: This constraint ensures that the total tourists allocated to a site must exactly match the tourists assigned to all transport modes combined. In simple terms, every tourist visiting a site must use some transport mode such as EV safari, bus, cycling, or walking. This helps maintain consistency in tourist and transport planning.





\# Constraint 2: Ecological Carrying Capacity

\#Explanation: This constraint ensures that the number of tourists visiting a site does not exceed the ecological capacity of that location. If a site is not opened or promoted ((y\_{it}=0)), then no tourists can be allocated there. This protects the environment and prevents overcrowding.





\# Constraint 3: Demand Constraint

\#Explanation: This constraint ensures that the total number of tourists allocated across all sites cannot exceed the actual tourist demand available during that period. In simple words, the model cannot create imaginary tourists beyond market demand. This keeps the solution realistic and demand-driven.





\# Constraint 4: Carbon Emission Calculation

\#Explanation: This constraint calculates the total carbon emissions generated from tourism transport activities. Emissions depend on how many tourists use each transport mode and how polluting that transport mode is. Cleaner transport systems result in lower emissions.





\# Constraint 5: Carbon Reduction

\#Explanation: This constraint shows that carbon-emission reduction depends on sustainability investment. If more money is invested in actions like solar energy, waste management, or green transport, then higher carbon reduction can be achieved. It connects sustainability spending with environmental improvement.





\# Constraint 6: Carbon Credit Revenue

\#Explanation: This constraint calculates the revenue earned from carbon credits. The more carbon emissions are reduced, the more carbon-credit revenue can be generated. It converts environmental sustainability into an economic benefit.





\# Constraint 7: Net Carbon Limit

\# Explanation: This constraint ensures that total net carbon emissions remain below the allowed environmental threshold. Net emissions are calculated after subtracting carbon reductions achieved through sustainability actions. It helps maintain environmental compliance and climate responsibility.





\# Constraint 8: Sustainability Budget

\#Explanation: This constraint ensures that total investment in sustainability actions does not exceed the available budget. The model must choose investments carefully and efficiently within financial limits. This keeps the solution economically practical.





\# Constraint 9: Sustainability Action Activation

\#Explanation: This constraint ensures that investment is allowed only if a sustainability action is actually selected. If an action is not activated, then no investment can be assigned to it. This creates a logical connection between decision-making and investment allocation.





\# Constraint 10: ESG Score Formation

\#Explanation: This constraint calculates the final ESG score after implementing sustainability actions. Actions like biodiversity monitoring, community training, and renewable energy improve ESG performance. It helps measure the sustainability quality of the tourism system.





\# Constraint 11: Wildlife Disturbance

\#Explanation: This constraint measures wildlife disturbance risk caused by tourism activities. Higher tourist allocation increases wildlife risk, while conservation investment helps reduce that risk. It balances tourism growth with biodiversity protection.





\# Constraint 12: Wildlife Protection Limit



\#Explanation: This constraint ensures that wildlife disturbance risk remains within an acceptable safe limit. Even if tourism generates high revenue, the model cannot allow wildlife damage beyond ecological tolerance. This protects biodiversity and ecosystem stability.





\# Constraint 13: Governance Compliance

\#Explanation: This constraint ensures that governance standards such as monitoring, regulation, safety, and sustainability compliance are properly maintained. Sustainability actions contribute governance scores that help satisfy this requirement. It strengthens accountability and responsible tourism management.





\# Constraint 14: Community Livelihood Target

\#Explanation: This constraint ensures that eco-tourism generates sufficient livelihood benefits for local communities. Tourism should support employment, local businesses, and economic development. It makes the optimization socially sustainable, not just economically profitable.





\# Constraint 15: Seasonal Restriction

\#Explanation: This constraint closes certain tourism sites during sensitive wildlife breeding seasons. During these periods, tourism activities may disturb animal reproduction and habitat stability. Therefore, the model restricts tourism operations to protect biodiversity during critical ecological periods.





\# Sustainability Practice Index (SPI)

\#Explanation: The Sustainability Practice Index (SPIit) measures the overall sustainability performance of a tourism site during a specific time period. It combines different sustainability components such as waste management, clean energy usage, water conservation, biodiversity protection, community development, and governance quality. The weights ω1, ω2,...ω6 represent the importance assigned to each sustainability factor in the final score.



\# Sustainability Priority Score

\#Explanation: The Sustainability Priority Score is a simple analytical formula used to rank eco-tourism sites before running the full optimization model. It compares positive factors like revenue and ESG performance against negative factors like carbon emissions and wildlife sensitivity. A higher score means the site is more suitable for sustainable tourism development.



\# Heuristic Approach

\#Explanation: The Greedy Sustainability Heuristic is a fast and practical decision-making approach used before applying advanced optimization. First, the model calculates sustainability scores for all sites and ranks them from best to worst. Then tourists are allocated while respecting ecological, carbon, wildlife, and budget constraints. Finally, the heuristic solution is compared with the exact OR-Tools optimization solution to evaluate how close the quick practical approach is to the optimal solution.



\# OR-Tools Optimization Framework

\#Explanation: The project uses Mixed Integer Linear Programming (MILP), which is an advanced Operations Research optimization technique used for solving complex real-world decision problems. “Mixed Integer” means the model can handle continuous variables (like investment amount), integer variables (like number of tourists), and binary variables (like whether a site is opened or not) together. Solvers such as OR-Tools SCIP, CBC Solver, Gurobi, and CPLEX mathematically search through thousands of possible combinations to find the best optimal solution while satisfying all environmental, economic, wildlife, ESG, and sustainability constraints.





CODE EXPLANATION:
1: import sys: This imports Python’s system library. It is useful when we want to interact with the Python environment, system path, or runtime settings. In this project, it supports general environment-level operations.



2: import math: This imports Python’s mathematics library. It allows us to use mathematical functions such as square root, ceiling, floor, logarithm, and other numerical calculations if required later.



3: import numpy as np: This imports the NumPy library and gives it the short name `np`. NumPy is used for numerical calculations, arrays, and mathematical operations. In Operations Research, it is useful for handling numerical parameters, vectors, and matrix-style calculations.



4: import pandas as pd: This imports the Pandas library and gives it the short name `pd`. Pandas is used to create and manage data tables called DataFrames. In this project, all datasets such as eco-tourism sites, transport modes, sustainability actions, and optimization results are handled using Pandas tables.



5: import matplotlib.pyplot as plt: This imports Matplotlib’s plotting module and gives it the short name `plt`. It is used to create graphs such as bar charts, line charts, sensitivity plots, and comparison visuals. In this project, it helps convert optimization results into understandable decision dashboards.



6: try: This starts an error-handling block. It means Python will try to run the next lines of code, and if something goes wrong, it will not stop the entire notebook immediately.



7: from ortools.linear\_solver import pywraplp: This imports the linear solver module from Google OR-Tools. `pywraplp` is the tool that allows us to create decision variables, define constraints, define objective functions, and solve optimization problems. In simple terms: This is the main engine that solves the Operations Research model.



8: ORTOOLS\_AVAILABLE = True: If OR-Tools is successfully imported, this line stores `True` in the variable `ORTOOLS\_AVAILABLE`. Meaning: OR-Tools is installed and ready to use.



9: except Exception as e: This part runs only if the OR-Tools import fails. The variable `e` stores the error message.



10: ORTOOLS\_AVAILABLE = False. If OR-Tools is not available, this line stores `False`. Meaning: The solver is not available, so the optimization model cannot be solved until OR-Tools is installed.



11: print("OR-Tools is not available. Install it using: pip install ortools"): This prints a helpful message telling the user how to install OR-Tools.

The command is: pip install ortools



12: print("Error:", e): This prints the actual error message. It helps identify why OR-Tools did not load properly.



13: pd.set\_option("display.max\_columns", 100): This tells Pandas to show up to 100 columns when displaying a DataFrame. In this project, some result tables may contain many columns such as revenue, emissions, ESG, carbon credit, wildlife risk, and investment. This setting ensures that columns are not hidden.



14: pd.set\_option("display.width", 180): This increases the display width of Pandas output. It makes wide tables easier to read inside Jupyter Notebook.



\# Interview Explanation: “In the first step, I imported the core Python libraries required for numerical analysis, data handling, visualization, and optimization. Pandas manages the project datasets, NumPy supports numerical operations, Matplotlib generates decision graphs, and OR-Tools provides the solver engine for the MILP model. I also added an availability check for OR-Tools to make the notebook robust and user-friendly.”





CODE EXPLANATION:

\# ------------------------------

\# Sets

\# ------------------------------

1: `# ------------------------------`: This is only a separator comment. It does not affect the code execution. It is used to visually divide the notebook into clean sections.



2: `# Sets`: This comment tells us that the next few lines define the main sets of the optimization model. In Operations Research, sets are collections of items over which decisions are made.



3: `sites = \["Gir Forest", "Kaziranga", "Jim Corbett", "Ranthambore", "Sundarbans", "Periyar"]`: This creates a list of eco-tourism sites. In mathematical notation, this represents the set (I), where each site is a possible location for tourist allocation.



4: `periods = \["Peak", "Regular", "Monsoon"]`: This creates the time-period list. In OR terms, this represents the set (T), because the model makes decisions separately for peak season, regular season, and monsoon season.



5: `modes = \["Diesel Jeep", "Shared Bus", "EV Safari", "Cycling", "Walking Trail"]`: This creates the transport mode list. In mathematical form, this is the set (M), which allows the model to decide how tourists should travel.



6: `actions = \[`: This starts the list of sustainability actions. These are the possible conservation or sustainability activities that the model can select and fund.



7: `"Habitat Restoration"`: This action represents forest and ecosystem restoration. In the model, it helps reduce ecological damage and improve biodiversity.



8: `"Anti-Poaching Surveillance"`: This action represents wildlife monitoring and protection. It is useful for reducing illegal activity and wildlife disturbance risk.



9: `"Waste Management"`: This action controls waste generated by tourists. It improves environmental performance and ESG quality.



10: `"Solar Energy"`: This action represents renewable energy usage. It helps reduce carbon emissions.



11: `"Water Conservation"`: This action represents rainwater harvesting, water treatment, and efficient water usage. It is important in eco-tourism sites where tourists create water pressure.



12: `"Community Training"`: This action improves local employment, awareness, and participation. It mainly supports the social part of ESG and livelihood development.



13: `"Biodiversity Monitoring"`: This action tracks wildlife and ecological health. It helps control biodiversity risk scientifically.



14: `"Green Transport Infra"`: This action supports electric mobility and low-emission transport systems. It helps reduce transport-related emissions.



15: `]`: This closes the sustainability actions list.



\# ------------------------------

\# Site-level dataset

\# ------------------------------

16: `# Site-level dataset`: This comment introduces the dataset related to eco-tourism sites. This table gives site-specific input parameters for the optimization model.



17: `site\_df = pd.DataFrame({`: This creates a Pandas DataFrame called `site\_df`. A DataFrame is a table. Here, it stores all site-level parameters such as capacity, revenue, ESG, wildlife sensitivity, and emissions.



18: `"site": sites,`: This column stores the names of all eco-tourism sites from the `sites` list.



19: `"capacity\_peak": \[600, 500, 750, 650, 400, 550],`: This column gives the maximum number of tourists each site can handle in peak season. In OR, this is a carrying-capacity parameter.



20: `"capacity\_regular": \[520, 450, 650, 580, 330, 500],`: This gives the maximum number of tourists allowed during regular season. Capacity is lower than peak in some cases because normal operations may have different limits.



21: `"capacity\_monsoon": \[250, 200, 300, 260, 120, 350],`: This gives monsoon-season capacity. These values are lower because monsoon conditions may make wildlife areas more sensitive or less accessible.



22: `"revenue\_per\_tourist": \[2500, 2800, 2200, 2600, 3000, 2100],`: This gives the revenue earned from one tourist at each site. It is used in the objective function to maximize tourism revenue.



23: `"base\_esg": \[72, 76, 68, 70, 78, 74],`: This gives the starting ESG score of each site before additional sustainability actions. Higher values mean the site already has better environmental, social, and governance readiness.



24: `"wildlife\_sensitivity": \[0.90, 0.95, 0.75, 0.82, 0.98, 0.70],`: This measures how sensitive wildlife is at each site. Higher values mean tourism can create more ecological disturbance.



25: `"distance\_km": \[42, 55, 38, 46, 70, 34],`: This gives the average travel distance for each site. It is used with transport emission factors to calculate carbon emissions.



26: `"baseline\_emission\_kg\_per\_tourist": \[18, 24, 19, 20, 28, 16],`: This gives the baseline carbon emission created per tourist. It helps estimate environmental pressure before applying sustainability improvements.



27: `"livelihood\_value\_per\_tourist": \[420, 500, 380, 410, 560, 390],`: This gives the local community benefit generated by each tourist. It represents income and employment value for local people.



28: `"critical\_species\_factor": \[0.65, 0.60, 0.75, 0.70, 0.55, 0.80]`: This factor restricts capacity because some sites have sensitive wildlife species. A lower value means stricter tourist limits due to ecological protection.



29: `})`: This closes the site-level DataFrame.



\# ------------------------------

\# Period-level data

\# ------------------------------

30: `# Period-level data`: This comment introduces the time-period dataset. It stores demand, budget, carbon limits, and livelihood targets for each season.



31: `period\_df = pd.DataFrame({`: This creates a DataFrame called `period\_df`. It stores season-wise planning information.



32: `"period": periods,`: This column contains the periods: Peak, Regular, and Monsoon.



33: `"demand": \[2600, 2100, 1150],`: This gives total tourist demand in each period. Peak season has the highest demand, while monsoon has lower demand.



34: `"carbon\_limit\_ton": \[42, 34, 18],`: This gives the maximum allowed carbon emissions in tons for each period. It acts as an environmental constraint.



35: `"budget": \[32\_00\_000, 25\_00\_000, 18\_00\_000],`: This gives the sustainability budget for each period. In Python, underscores make numbers easier to read, so `32\_00\_000` means ₹32,00,000.



36: `"carbon\_credit\_price\_per\_ton": \[2800, 2500, 2300],`: This gives the carbon-credit price per ton of CO₂e reduction. It helps calculate carbon-credit revenue.



37: `"min\_sites\_open": \[4, 3, 2],`: This gives the minimum number of sites that must remain open in each period. For example, during peak season, at least 4 sites should operate.



38: `"livelihood\_target": \[7\_50\_000, 5\_50\_000, 2\_50\_000]`: This gives the minimum local livelihood value required in each period. It ensures tourism benefits local communities.



39: `})`: This closes the period-level DataFrame.



\# ------------------------------

\# Transport mode data

\# Emission factor = kg CO2e per tourist-km

\# ------------------------------

40: `# Transport mode data`: This comment introduces the transport dataset.



41: `# Emission factor = kg CO2e per tourist-km`: This explains that the emission factor measures how many kilograms of CO₂ equivalent are produced for each tourist per kilometer.



42: `mode\_df = pd.DataFrame({`: This creates a DataFrame called `mode\_df`. It stores transport-related parameters.



43: `"mode": modes,`: This column stores the transport modes such as Diesel Jeep, Shared Bus, EV Safari, Cycling, and Walking Trail.



44: `"emission\_factor": \[0.105, 0.040, 0.018, 0.004, 0.000],`: This gives the emission factor for each transport mode. Diesel Jeep has the highest emissions, while Walking Trail has zero direct transport emission.



45: `"comfort\_score": \[7, 6, 8, 5, 4],`: This gives a comfort rating for each transport mode. EV Safari has high comfort, while walking has lower comfort but better environmental performance.



46: `"max\_share": \[0.45, 0.60, 0.50, 0.25, 0.20]`: This limits the maximum share of tourists assigned to each transport mode. For example, not all tourists can be forced to walk or cycle.



47: `})`: This closes the transport mode DataFrame.



\# ------------------------------

\# Sustainability action data

\# Values are simplified but structured to behave like a real decision model.

\# carbon\_reduction\_ton\_per\_lakh = verified CO2e reduction per lakh rupees invested

\# risk\_reduction\_per\_lakh = wildlife-risk reduction per lakh rupees invested

\# ------------------------------

48: `# Sustainability action data`: This comment introduces the sustainability action dataset.



49: `# Values are simplified but structured to behave like a real decision model.`: This means the values are synthetic, but they are designed realistically so the model behaves like a practical decision-support system.



50: `# carbon\_reduction\_ton\_per\_lakh = verified CO2e reduction per lakh rupees invested`: This explains that for every ₹1 lakh invested in an action, the model estimates how many tons of CO₂e can be reduced.



51: `# risk\_reduction\_per\_lakh = wildlife-risk reduction per lakh rupees invested`: This explains that for every ₹1 lakh invested, the model estimates how much wildlife risk can be reduced.



52: `action\_df = pd.DataFrame({`: This creates a DataFrame called `action\_df`. It stores all sustainability-action parameters.



53: `"action": actions,`: This column stores the names of sustainability actions from the `actions` list.



54: `"min\_invest": \[250000, 300000, 180000, 220000, 160000, 120000, 200000, 240000],`: This gives the minimum investment required if an action is selected. It prevents unrealistic tiny investments.



55: `"max\_invest": \[900000, 850000, 600000, 700000, 500000, 450000, 650000, 750000],`: This gives the maximum investment allowed for each action. It prevents over-allocation of budget into one action.



56: `"carbon\_reduction\_ton\_per\_lakh": \[1.6, 0.4, 1.2, 2.4, 0.8, 0.3, 0.5, 2.0],`: This shows how effective each action is in reducing carbon emissions. Solar Energy and Green Transport Infrastructure have high carbon-reduction values.



57: `"risk\_reduction\_per\_lakh": \[22, 35, 8, 4, 7, 12, 30, 6],`: This shows how effective each action is in reducing wildlife risk. Anti-Poaching Surveillance and Biodiversity Monitoring have high wildlife-risk reduction values.



58: `"esg\_environment": \[9, 5, 8, 9, 8, 4, 7, 9],`: This gives the environmental ESG contribution of each action. Solar Energy, Habitat Restoration, and Green Transport Infra score high here.



59: `"esg\_social": \[5, 6, 5, 4, 5, 10, 6, 5],`: This gives the social ESG contribution. Community Training has the highest social value because it directly supports local people.



60: `"esg\_governance": \[4, 9, 5, 5, 5, 7, 9, 6],`: This gives the governance ESG contribution. Anti-Poaching Surveillance and Biodiversity Monitoring have high governance value because they involve monitoring and compliance.



61: `"spi\_score": \[9, 8, 8, 9, 8, 9, 9, 8],`: This gives the Sustainability Practice Index score contribution of each action. Higher values mean stronger sustainability performance.



62: `"gov\_score": \[6, 10, 6, 5, 5, 8, 9, 6]`: This gives the governance compliance score of each action. Anti-Poaching Surveillance has the highest governance score.



63: `})`: This closes the sustainability action DataFrame.



64: `display(site\_df)`: This displays the site-level dataset in Jupyter Notebook. It allows us to visually verify site capacities, revenues, ESG values, emissions, and wildlife sensitivity.



65: `display(period\_df)`: This displays the period-level dataset. It helps check demand, carbon limits, budget, carbon-credit price, and livelihood targets.



66: `display(mode\_df)`: This displays the transport mode dataset. It shows emission factor, comfort score, and maximum usage share for each transport mode.



67: `display(action\_df)`: This displays the sustainability action dataset. It shows investment limits, carbon reduction, wildlife-risk reduction, ESG impact, SPI score, and governance score.



\# Interview Explanation:

“In this block, I define the complete data foundation for the optimization model. First, I create the major OR sets: sites, seasons, transport modes, and sustainability actions. Then I convert them into structured Pandas DataFrames containing all key parameters such as ecological capacity, tourist demand, revenue, emissions, ESG scores, wildlife sensitivity, carbon-credit price, sustainability budget, transport emissions, and conservation-action impact. This makes the model data-driven and allows OR-Tools to use these parameters later for tourist allocation, site selection, transport optimization, carbon-credit calculation, and sustainability investment planning.”





\# ------------------------------

2\. Analytical Baseline Model

\# ------------------------------

1: `baseline = site\_df.copy()`: This creates a separate copy of the original `site\_df` table and stores it in a new variable called `baseline`. We do this so that the original site dataset remains unchanged while we calculate the analytical score separately.



2: `baseline\["analytical\_score"] = (`: This creates a new column named `analytical\_score` inside the `baseline` table. This score is used to rank eco-tourism sites before running the full OR-Tools optimization model.



3: `baseline\["revenue\_per\_tourist"] \*`: This takes the revenue earned from each tourist at every site. Higher revenue increases the analytical score because the site is economically more attractive.



4: `baseline\["base\_esg"] \*`: This multiplies the revenue by the ESG score. A higher ESG score means the site already has stronger environmental, social, and governance performance.



5: `baseline\["livelihood\_value\_per\_tourist"]`: This multiplies the score by the local livelihood value per tourist. It gives importance to sites where tourism creates stronger benefits for local communities.



6: `) / (`: This means the positive factors are now divided by the negative pressure factors. In this formula, good factors are placed in the numerator, and harmful or limiting factors are placed in the denominator.



7: `baseline\["baseline\_emission\_kg\_per\_tourist"] \*`: This includes carbon emission per tourist in the denominator. Higher emission reduces the analytical score because the site creates greater environmental pressure.



8: `baseline\["wildlife\_sensitivity"]`: This includes wildlife sensitivity in the denominator. Higher wildlife sensitivity reduces the score because more sensitive sites need stricter tourism control.



9: `)`: This closes the analytical score formula. The final score balances revenue, ESG, and livelihood benefits against carbon emission and wildlife sensitivity.



10: `baseline = baseline.sort\_values("analytical\_score", ascending=False)`: This sorts the sites from highest analytical score to lowest analytical score. `ascending=False` means the best-ranked site appears at the top.



11: `display(baseline\[\[... ]])`: This displays only selected columns from the `baseline` table instead of showing the full dataset. It makes the output easier to read.



12: `"site"`: This column shows the name of each eco-tourism site.



13: `"analytical\_score"`: This column shows the calculated sustainability-priority score for each site.



14: `"revenue\_per\_tourist"`: This column is displayed to show the economic strength of each site.



15: `"base\_esg"`: This column is displayed to show the starting ESG quality of each site.



16: `"wildlife\_sensitivity"`: This column is displayed to show ecological risk or wildlife sensitivity.



17: `"baseline\_emission\_kg\_per\_tourist"`: This column is displayed to show the carbon impact per tourist.



\# Interview Explanation: “In this block, I created an analytical baseline score before applying OR-Tools. The purpose is to rank each eco-tourism site using a simple sustainability-priority formula. The numerator includes positive factors such as revenue, ESG score, and livelihood value, while the denominator includes negative factors such as carbon emission and wildlife sensitivity. This gives a first-level mathematical ranking of sites and acts as a benchmark against which the final OR-Tools optimization solution can be compared.”









