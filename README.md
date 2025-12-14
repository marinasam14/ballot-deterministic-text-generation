## Deterministic Text Generation for Live Ballot Proposal Results 

This repository contains code that produces text based on live election night results. 


### Data 

This code uses cleaned unofficial election data from the NYC Board of Elections that was scraped on election night. For this example, I am using the results from Proposal #4 from the 2025 elections. The goal is to create quick, automatic summaries of the results for newsrooms producing live election night updates.


### Output

This code uses conditionals to generate a 4 sentence summary that includes the neighborhood outcome, the margin of votes, the context for the Proposal 4, and it's comparison to the borough average.

### Requirements

The code uses Python3 and the following libraries:

* pandas
* datetime
* requests
* json

### Notes

This code was created as a requirement of the Secure AI Newsroom course at the Craig Newmark Graduate School of Journalism at CUNY

