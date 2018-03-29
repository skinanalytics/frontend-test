# Skin Analytics - Frond End Technical Exercise

Thanks again for your time during the first round interview. In order to assess your technical level, please find below a technical test which include a small coding exercise and some general background questions. 

## General background questions

- One client is reporting an issue on your main web application you cannot replicate. How do you proceed to narrow down the problem?
- Tell me about one thing that many web sites do poorly. How would you fix it?

## Coding exercise

Below is a small coding challenge to complete at home. You can use as much online resources (Google, online documentation, etc.) as you wish. We expect you to spend no more than 2-3 hours on it. If you can't finish, please submit whatever you have, as unfinished code is still better than no code. 

We don't want you to over-engineer the solution but be prepared to extend the functionnality in the next step of the interview process. Finally, we ask you to submit a solution that you'd be happy to go live with and works "out of the box”.

Please create a local git repository (or clone this one) and then commit to this as you work. When you have finished please zip up the whole folder (including the .git folder) and email it to recruitment@skinanalytics.co.uk. *Please do not make your solution public*.

Please include any setup instructions and keep the setup steps simple. Your solution should be working on latest versions of Firefox and Chrome but don't worry about any browser inconsistencies.


### Guidelines technical specifications

Use whatever Javascript framework you feel comfortable with but you should already have an idea about our technology stack :-)

There is a [CSV](https://github.com/skinanalytics/technical-tests/blob/master/data/cases.csv) file containing 20 cases of patients submitting a skin cancer check. 
A case has fixed data as the following:
- A case number
- A date of creation
- A date of modification
- A status (indicating the progress of the case)
- A refer status (which indicates the diagnosis of the lesion being checked)
- A (dummy) photo of the lesion captured

Using this file as your data source, we would like you to create a small web application that does the following:

The root of the site should display the cases with all the information (except the photo) as a table.

Clicking a row should take you to a page that displays the case and update the url.
The case page should layout the content in a nicely manner and include the photo.

Bonus point (if you have time): On the root page, make the columns sortable.

### What we are looking for
We anticipate that this app may have future requirements, so you should aim for maintainability with your solution.
The javascript ecosystem changes quickly, so we like to see knowledge of javascript fundamentals
We want to discover how you write code day-to-day
We don't want you to spend hours tweaking every pixel. Keep it simple and functional .
