# Decline Curve Analysis Tool
This Python project implements Production Decline Curve Analysis to forecast oil production and estimate reserves using classical decline models: Exponential, Hyperbolic, and Harmonic.

 Features:

1. Accepts user-provided production data (time in months, rate in bbl/day)

2. Calculates and compares:

        Exponential decline rate

        Hyperbolic decline rate (with user-defined b)

        Harmonic decline rate

3. Computes R² (coefficient of determination) for model performance

4. Identifies the best-fit decline model

5. Forecasts future production over a user-defined period

6. Estimates Estimated Ultimate Recovery (EUR) for each model

7. Plots all fitted and forecasted decline curves using matplotlib

