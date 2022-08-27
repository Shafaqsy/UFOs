# UFOs
## Purpose:
The purpose of this project is to customize a webpage using bootstrap. Build a table using data stored in a JavaScript array. Also create filters for the date, city, state, country, and shape to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.
## Results:
This how the webpaage looks like when it is open. Ther's a title, backgroung image, paragraph, filter search and a table.

<img width="960" alt="UFO Sightings" src="https://user-images.githubusercontent.com/107155888/187001801-d5224030-a8fa-46b1-9ed8-258ec54e0d1d.png">

The filter search is super easy to use. There is a text given as a hint inside of each filter. It will help user to follow the format while searching.

<img width="198" alt="filter" src="https://user-images.githubusercontent.com/107155888/187001810-801db6e1-8052-42ad-af74-0e423ae1de13.png">

### Example
Here's an example. If user is only interested in state of Ohio. All the user need to do is type oh in state filter and hit enter. The table would only give the results of Ohio. Below is the image how the table looks like.

<img width="880" alt="ohio search" src="https://user-images.githubusercontent.com/107155888/187003098-cb00b756-921c-4707-b66b-d9da2334ee4d.png">

## Summary
### Drawback.
Filter search is very sensitive the format has to be followed otherwise there would be no data in the table. For example we did the oh search earlier if wo would have capitalize the word OH, the filter search wouldn't recognize it and give a empty table as a result.

### Recomendations.
1. The filter should allow upper cease and lower case letters.
2. The filter search able to catch what the user meant either there's space or no spaces between cities names like san diego or sandiego.
3. The date filter should also be recognized in any format like 01/03/2010 or 1/3/2010.
4. The duration filter can also be added for user.
