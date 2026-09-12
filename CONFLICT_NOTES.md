# Merge Conflict Resolution Notes

## Conflict Summary
A merge conflict occurred in `README.md` on line 2 during the integration of `main` into the `proposal` branch.

## Cause
* `main` branch contained: `"Main branch summary: Analyzing Canada's historical per capita income growth trends."`
* `proposal` branch contained: `"Proposal branch summary: Machine learning regression model for predicting future Canadian per capita income."`

## Resolution Strategy
Both descriptions were manually edited and combined into a single unified summary:
`"Machine learning regression model for analyzing and predicting Canada's historical and future per capita income trends."`

Conflict markers were removed, changes staged with `git add README.md`, and committed.