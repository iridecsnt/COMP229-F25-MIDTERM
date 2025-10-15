# Midterm API Project - COMP229

## Reflection
3. **Reflection (optional, but recommended)**  
   Summarize in a short paragraph how you validated each endpoint and any edge cases considered.

In this Assignment, I used Thunder Client as I figured it is simplier to stay in the VSCode ecosystem. For the GET endpoints, I verfied that they successfully displayed the full list of games, games that match the genre, and retreives games by its index. For the POST endpoint I added The Sims 4 and confirmed that the game appeared when I ran all data. For PUT endpoint I made sure that the updated game displays the correct specific index with no errors. Finally, for the DELETE endpoint I successful displayed that The Sims 4 was removed, and the array count decreased by one. I also tested edge cases to ensure that the server returned proper error messages (like 404 Not Found and 400 Bad Request).
