# RN-challenge-ftf

In this challenge you're going to create a basic Reddit app with React Native

Reddit is a news website where registered users can submit posts or links to content that other users can vote and comment. Each of these posts is grouped into categories known as "subreddits".

Your web app should list the last posts of the r/pics subreddit.

To obtain the list of posts of a subreddit use the following URL:
https://api.reddit.com/r/pics/hot.json

For more information about the JSON structure see:
https://github.com/reddit/reddit/wiki/JSON

## Requirements:

- Show a list of the posts in the r/pics subreddit
- Each post must show the following data: thumbnail image (if present), title, author, total number of votes (score), number of comments and date of creation
- Example layout (basic example - no need to follow it exactly)

  ![](showcase.gif)

- Once the user taps on a post navigate to the post’s URL in a WebView
- A brief explanation of your design and assumptions along with your code.

## What will we evaluate?

- Code quality
- Usage of patterns
- Networking code
- Language skills
- Project structure

## Extra points (not required):

- Unit tests
- Date of creation in a relative format (e.g. “1 day ago”)
- Data caching

## Notes:

- feel free to use an online emulation environment like [snack expo](https://snack.expo.dev/@aboutreact/online-emulator-by-aboutreact?session_id=snack-session-izmjLQumT)
- Send us your code either in a GitHub Repository, zip file with the project, or any other way you feel comfortable with.

Good luck!
