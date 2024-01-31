# HR8404-Data
This repository hosts the data and replication code analyzing Republican support for the Respect for Marriage Act (H.R.8404) in 2022 with difference-in-means estimates. This analysis is part of a larger paper titled "An Unlikely Coalition: Passing the Respect for Marriage Act."

# Codebook
state: district state

district: district number

member: member last name

party: member party

     0: Democrat
     
     1: Republican
     
vote0: vote on H.R.8404 in either July or December
     0: "no" vote twice
     1: "yes" vote at least once
vote1: vote on H.R.8404 in July
     0: "no" vote
     1: "yes" vote
vote2: vote on H.R.8404 in December
     0: "no" vote
     1: "yes" vote
competitive1: Cook PVI score within D+5 to R+5 range 
     0: outside of range
     1: inside of range
competitive2: Cook PVI score within D+10 to R+10 range 
     0: outside of range
     1: inside of range
pvi: Cook PVI score
notes: miscellaneous information
