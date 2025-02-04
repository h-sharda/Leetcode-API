# Endpoints 🚀  

## Origianl Repo

<https://github.com/alfaarghya/alfa-leetcode-api/>

---

## 👤User Details  

| Details                       | Endpoint                             | Description                                                          |  
| :---------------------------- | :----------------------------------- | :------------------------------------------------------------------- |  
| _Profile_                     | `/:username`                         | Get details about a user's profile.                                  |  
| _Badges_                      | `/:username/badges`                  | Get the badges earned by the user.                                   |  
| _Solved_                      | `/:username/solved`                  | Get the total number of questions solved by the user.                |  
| _Contest_                     | `/:username/contest`                 | Get details about the user's contest participation.                  |  
| _Contest History_             | `/:username/contest/history`         | Get contest history.                                                 |  
| _Submission_                  | `/:username/submission`              | Get the last 20 submissions of the user.                             |  
| _Limited Submission_          | `/:username/submission?limit=number` | Get a specified **_number_** of the user's last submissions.         |  
| _Accepted Submission_         | `/:username/acSubmission`            | Get the last 20 accepted submission of the user.                     |  
| _Limited Accepted Submission_ | `/:username/acSubmission?limit=7`    | Get a specified **_number_** of the user's last accepted submission. |  
| _Calendar_                    | `/:username/calendar`                | Get the user's submission calendar.                                  |  

---

## 😀 New Endpoints 🎉  

| Details                | Endpoint                                           | Description                          |  
| :--------------------- | :------------------------------------------------- | :----------------------------------- |  
| _Full Profile_         | `/userProfile/:username`                           | Get full profile details in one call |  
| _Year Calendar_        | `/userProfileCalendar?username=yourname&year=2024` | Get your calendar details with year  |  
| _Lang Stats_           | `/languageStats?username=yourname`                 | Get the language stats of a user     |  
| _Question Progress_    | `/userProfileUserQuestionProgressV2/:userSlug`     | Get your question progress           |  
| _Skill Stats_          | `/skillStats/:username`                            | Get your skill stats                 |  
| _User Contest Ranking_ | `/userContestRankingInfo/:username`                | Get contest ranking                  |  
| _Trending Discussion_  | `/trendingDiscuss?first=20`                        | Get top 20 trending discussions      |  
| _Discussion Topic_     | `/discussTopic/:topicId`                           | Get discussion topic                 |  
| _Discussion Comment_   | `/discussComments/:topicId`                        | Get discussion comments              |  
| _Raw Daily Problem_    | `/dailyQuestion`                                   | Get raw daily question               |  

---

## ❓Questions Details  

| Details                            | Endpoint                                                 | Description                                                                                                                  |  
| :--------------------------------- | :------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |  
| _Daily Problem_                    | `/daily`                                                 | Get the daily question.                                                                                                      |  
| _Selected Problem_                 | `/select?titleSlug=selected-question`                    | Get details about a **_selected-question_**.                                                                                 |  
| _Problems_                         | `/problems`                                              | Get a list of 20 problems.                                                                                                   |  
| _Limited Problems_                 | `/problems?limit=number`                                 | Get a list of a specified **_number_** of problems.                                                                          |  
| _Filter Problems_                  | `/problems?tags=tag1+tag2`                               | Get a list of problems based on selected **_tags_**.                                                                         |  
| _Skip Problems_                    | `/problems?skip=number`                                  | Get a list of 20 problems, skipping a specified **_number_** of problems.                                                    |  
| _Difficulty_                       | `/problems?difficulty=EASY`                              | Get a list of difficulty-based problems, use **_MEDIUM_** to get medium level, **_HARD_** to get Hard level.                 |  
| _Filter & Limited Problems_        | `/problems?tags=tag1+tag2+tag3&limit=number`             | Get a list of a specified **_number_** of problems based on selected **_tags_**.                                             |  
| _Skip & Limited Problems_          | `/problems?limit=number&skip=number`                     | Get a list of a specified **_number_** of problems skipping a specified **number** of problems.                              |  
| _Skip & Filter & Limited Problems_ | `/problems?tags=tag1+tag2+tag3&limit=number&skip=number` | Get a list of a specified **_number_** of problems based on selected **_tags_** skipping a specified **number** of problems. |
