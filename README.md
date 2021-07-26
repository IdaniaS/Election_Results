# PyPoll_Challenge
## Overview of Election Audit
Tom and Seth are ready to begin an election audit.
It is important to go over the tasks with Tom and discuss the information needed by the Colorado Board of Elections. Calculate statistics and print the results to the terminal as well as a text file. 
### Deliver the following information to the election committee
- Total number of votes cast
- A complete list of candidates who recieved votes
- Total number of votes each candidate recieved
- Percentage of votes each candidate won
- The winner of the election based on popular vote

By using pseudocode it will make audit easier to present to nontechnical colleagues and stakeholders.
After reviewing the information, the election committee has requested more information associated to the individual county showings. Using the starter code to develop the audit information to include more detail as requested from the committee.

## Election-Audit Results

### Total Votes Cast in this congressional election
* The total amount of votes cast in this congressional election was calculated through creating for loop paired with a counter variable that increased with each loop though the rows of data. The total number of votes cast was 369,711. 

![Election_Results](https://user-images.githubusercontent.com/86635590/126914706-0916219f-9d32-42d6-b8ff-3d99d7b5b572.JPG)

### Breakdown of number of votes and percent for each county
* Calcualting the number of votes and percent for each county was produced by creating a dictionary adn list to keep key terms such as the county name and accumulated votes by each county as the value.
* As seen below
* 
![Percentage_by_County](https://user-images.githubusercontent.com/86635590/126914760-b9698a82-37f5-42fd-8582-db3a8f238c58.JPG)

* While contining the loop for all the data, it is designed to append the to the list when a new county name is listed.

![Loop_County](https://user-images.githubusercontent.com/86635590/126915139-2097d1c8-7eb6-4a4d-a752-bd1e46c464ef.JPG)

* Variables created to track votes by county and increase each time the county name appeared in the data file. The percentage of total votes for each county is calculated by dividing the total for each county by the overall total.

![Votes_by_County](https://user-images.githubusercontent.com/86635590/126915403-f538c04f-b89a-4afd-9047-143e8bd60a67.JPG)

* Final results by county:

![County_Results](https://user-images.githubusercontent.com/86635590/126915420-62178444-f8da-4317-aa62-530243c2c33a.JPG)

### County with the largest number of votes

* The county that won the election was determined with an if statement and comparison variable for the loop to check and accumulate the amount of votes. By processing the whole dataset it and writing the code as shown below:

![Votes_by_County](https://user-images.githubusercontent.com/86635590/126917051-bafa0627-54cc-4de0-a91d-ce920493feae.JPG)

* The county with the largest turn out was Denver

![Largest_Turnout](https://user-images.githubusercontent.com/86635590/126917875-a6cfa199-f1d0-435b-8509-8d434f728687.JPG)

### Votes and percent of total votes for each candidate

* Just as the county with the largest turn out was calculated similarly the votes for each cadidate and the percent of total votes for each is in the county analysis.

![Votes Percentage](https://user-images.githubusercontent.com/86635590/126917963-1312a76a-041f-4c69-a091-9a9655e71ab2.JPG)

### The winning candidate, vote count and percent of total votes recieved

* The winning candidate was Diana DeGette who recieved a total count of 272,892 votes which was 73.8% of the total amount of votes. 

![Election_Winner](https://user-images.githubusercontent.com/86635590/126918004-36edc429-36c2-442d-9c51-78b7f6b7cd67.JPG)

## Election-Audit Summary
The written script for the audit was able to calculate the total votes, number of votes for each candidate, from which county and the percentage of total votes for each. The data elements can be applied to other applications and produce important information from each dataset. The script could also be written to provide other important information such as;
Allowing the election commission to see which candidate won in each county by counting votes by cadidate and by county. This would provide insight past just the overall election winner.
Second the script could be modified to calculate the winning candidate in most counties which could produce a possible seperate outcome from the overall popular vote. 
These minor changes would benefit the Colorado Board of Elections in examining the dataset in a different context providing a deeper insight to other opportunities of improvment and analytics.

