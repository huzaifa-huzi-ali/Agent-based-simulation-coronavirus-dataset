# Agent-Based Modeling of COVID-19 Spread in Bangladesh Using NetLogo

## Overview

This project implements an Agent-Based Model (ABM) in NetLogo to simulate the spread of COVID-19 in Bangladesh. The model uses real COVID-19 data from Bangladesh to validate simulation outcomes and analyze disease transmission patterns.

Two separate models have been developed:

1. **Simple COVID-19 Agent-Based Model**
2. **Extended COVID-19 Agent-Based Model**

The project demonstrates how individual behaviors, social interactions, and public health interventions influence pandemic dynamics.

---

## Why NetLogo?

NetLogo is a widely used platform for Agent-Based Modeling that allows researchers to model complex systems through interactions between autonomous agents.

Benefits of using NetLogo:

* Easy visualization of agent interactions
* Built-in simulation environment
* Suitable for epidemiological modeling
* Supports BehaviorSpace experiments
* Widely used in academic research

---

## Software Requirements

### Required Software

* NetLogo 6.x or later

Download from:

https://ccl.northwestern.edu/netlogo/

### Optional Tools

* Microsoft Excel
* R
* Python (for additional analysis only)

---

## Project Files

```text
COVID19-ABM-Bangladesh/
│
├── Models/
│   ├── Simple_COVID_Model.nlogo
│   └── Extended_COVID_Model.nlogo
│
├── Data/
│   └── Bangladesh_COVID_Data.csv
│
├── Reports/
│   ├── Simple_Model_Report.pdf
│   └── Extended_Model_Report.pdf
│
├── Screenshots/
│   ├── Simple_Model_Output.png
│   ├── Extended_Model_Output.png
│   └── Comparison_Graphs.png
│
└── README.md
```

```

---

## Model 1: Simple COVID-19 Model

### Description

The Simple Model implements basic epidemic spread dynamics using three states:

* Susceptible
* Infected
* Recovered

Agents move randomly and interact with nearby agents.

### Features

* Random movement
* Infection transmission
* Recovery mechanism
* Real-time visualization

### Purpose

To provide a baseline understanding of epidemic spread without intervention policies.

---

## Model 2: Extended COVID-19 Model

### Description

The Extended Model introduces realistic characteristics observed during the COVID-19 outbreak in Bangladesh.

### Additional Features

* Age-based population groups
* Social distancing
* Lockdown simulation
* Quarantine policies
* Vaccination
* Mortality
* Dynamic infection probabilities

### Purpose

To create a more realistic representation of COVID-19 transmission and compare it against actual Bangladesh data.

---

## Dataset

The simulation results are compared against real COVID-19 data collected from Bangladesh.

### Dataset Attributes

* Date
* Daily Cases
* Total Cases
* Recoveries
* Deaths
* Active Cases

---

## Running the Models

### Step 1

Open NetLogo.

### Step 2

Load either:

* Simple_COVID_Model.nlogo
* Extended_COVID_Model.nlogo

### Step 3

Click the **Setup** button.

### Step 4

Click the **Go** button to start the simulation.

### Step 5

Observe:

* Infection curves
* Recovery trends
* Population state changes
* Epidemic progression

---

## Validation Against Real Data

Simulation outputs are compared with actual Bangladesh COVID-19 statistics.

### Validation Metrics

* Peak Infection Comparison
* Total Cases Comparison
* Epidemic Duration
* Recovery Trends
* Mortality Trends

### Findings

The Extended Model showed significantly closer agreement with real-world data than the Simple Model.

---

## Experimental Analysis

Several experiments were conducted:

### Experiment 1

Effect of Infection Probability

### Experiment 2

Effect of Population Density

### Experiment 3

Impact of Social Distancing

### Experiment 4

Impact of Lockdown Policies

### Experiment 5

Vaccination Effectiveness

Results indicate that intervention strategies substantially reduced infection spread and delayed epidemic peaks.

---

## Academic and Research Applications

This project can be used for:

* Epidemiological research
* Public health policy evaluation
* Agent-based modeling education
* Pandemic preparedness studies
* Disease transmission research

Researchers can adapt the model for:

* Other countries
* Other infectious diseases
* Healthcare resource planning
* Multi-wave epidemic analysis

---

## How to Contribute

Researchers and developers are encouraged to contribute.

Possible contributions:

* Improved disease transmission mechanisms
* Geographic modeling of Bangladesh districts
* Additional intervention strategies
* Better calibration techniques
* New visualization dashboards

### Contribution Workflow

1. Fork the repository.
2. Create a feature branch.
3. Implement improvements.
4. Test the model.
5. Submit a pull request.

---

## Reproducibility

All simulation parameters are documented within the NetLogo interface and reports to ensure reproducibility of experiments.

Researchers can modify:

* Population size
* Infection rate
* Recovery time
* Mobility level
* Vaccination rate
* Quarantine effectiveness

to conduct new experiments and compare outcomes.

---

## Citation

If you use this project in academic work, please cite:

"Agent-Based Modeling of COVID-19 Spread in Bangladesh Using NetLogo."

Please also cite the original COVID-19 dataset source used in this study.

---

## License

This project is available for educational and research purposes. Please provide appropriate attribution when reusing or extending the model.
