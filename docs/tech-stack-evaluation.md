# Tech Stack Evaluation

## Project
A Web-Based Preliminary Insomnia Screening and Sleep Diaries System.

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- User signup/login.
- User answer a questionaire and get a scale result.
- User can track their sleep progress.

## Options
- Option A: Dart web app (Flutter) with a SQLite database on a cloud host and user login.
- Option B: Static website (HTML and Javascript) on NetBeans. Task are stored in the user's own browser.
- Option C: A low-code app builder with a ready-made database.

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               | 5      | 4       | 3       | 3       |
| Skills I already have              | 3      | 3       | 4       | 3       |
| Time to build before my deadline   | 3      | 3       | 3       | 4       |
| Free hosting and tools             | 3      | 4       | 4       | 4       |
| Performance and security needs     | 4      | 4       | 4       | 3       |
| Room to grow later                 | 4      | 4       | 4       | 3       |
| **Total (weighted)**               |        |**80**   |**80**   |**72**   |

## Decision record
- **Context:** A sleep diaries/coach app. I know HTML and basic Python but I want to try build a app.
- **Decision:** Option A, web app.
- **Reasons:** App more convinient for user to use.
- **Consequences:** Easy:the system compiles code directly into native machine code for iOS, Android, Windows and Mac  
                    Harder:never build a app.
- **Risks and next review:** If I change my SQL database structure after the app is already installed on a device, the 
                             app will crash. Before releasing an app update, install the old version app, put some data in it, then install the new version over it without deleting it.
