# Images

This folder contains visual outputs generated from the Primal-Dual Learning Algorithm implementation.

The images are used to explain the exploration phase, final demand behavior, revenue analysis, and price trends across customer arrivals.

## Image List

### Exploration Phase

- `exploration_price_demand_customer_type_1.png`  
  Shows the relationship between price and demand probability during the exploration phase for Customer Type 1, representing reserved customers.

- `exploration_price_demand_customer_type_2.png`  
  Shows the relationship between price and demand probability during the exploration phase for Customer Type 2, representing preemptive customers.

### Final Demand Analysis

- `sorted_price_demand_customer_type_1_with_z_opt.png`  
  Shows the sorted final price-demand relationship for Customer Type 1 after applying the primal-dual learning logic with the estimated dual variable.

- `sorted_price_demand_customer_type_2_with_z_opt.png`  
  Shows the sorted final price-demand relationship for Customer Type 2 after applying the primal-dual learning logic with the estimated dual variable.

### Final Revenue Analysis

- `sorted_price_revenue_customer_type_1_with_z_opt.png`  
  Shows the sorted final price-revenue relationship for Customer Type 1 after applying the primal-dual learning approach.

- `sorted_price_revenue_customer_type_2_with_z_opt.png`  
  Shows the sorted final price-revenue relationship for Customer Type 2 after applying the primal-dual learning approach.

### Price Trend Across Customers

- `price_trend_customer_type_1.png`  
  Shows how pricing decisions evolve across customer arrivals for Customer Type 1.

- `price_trend_customer_type_2.png`  
  Shows how pricing decisions evolve across customer arrivals for Customer Type 2.

## Purpose

These visualizations support the explanation of how the algorithm learns demand behavior, estimates inventory-aware pricing decisions, and evaluates revenue performance under inventory constraints.

## Usage in Main README

The images can be displayed in the main `README.md` file using relative paths.

Example:

```markdown
![Exploration Price vs Demand - Customer Type 1](images/exploration_price_demand_customer_type_1.png)
