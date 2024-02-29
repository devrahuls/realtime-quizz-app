### Build a simple quizzing app similar to menti-meter

## Features

- Admin should be allowed to add questions (MCQ, single answer)
- Admin should be allowed to move to the next question.
- Admin should be allowed to show the leaderboard to everyone
- Users should be allowed to answer the questions
- Users just need to poll the server for the next question, no need for it to be realtime.

# Frontend
 - Simple view with title and answers
    title: String
    choices: String[]
    image?: String

-Leaderboard view 
    winners: {username: String, profilePicture?: String, points: number}[] => Sorted

-Join the course view
Stack - ReactJS, TailwindCSS