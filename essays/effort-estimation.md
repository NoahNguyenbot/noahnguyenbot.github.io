---
layout: essay
type: essay
title: "The difficult things will always be difficult"
# All dates must be YYYY-MM-DD format!
date: 2026-05-04
published: true
labels:
  - Engineering
---

<img width="200px" class="rounded float-start pe-4" src="../img/difficulty/degree_difficulty.jpg">

# Effort Estimation and Tracking in Manoa Course Wise

Effort estimation and tracking were completely new territory for our team in the **Manoa Course Wise** project. At the beginning, the whole process felt pretty artificial — how on earth are you supposed to guess how long something will take before you’ve even touched it? But as the weeks went by, I discovered that even rough estimates and honest tracking became surprisingly valuable tools for staying organized and keeping the team in sync.

## How did you make your effort estimates?

I based my estimates on a mix of gut instinct, past experience, and comparisons to similar tasks I had already done. 

For instance, when estimating the course search page, I remembered that the dashboard (which had similar complexity) took me roughly 2 hours. I bumped it up to **2.5 hours** to leave room for learning curves and unexpected bugs. For unfamiliar tasks, I broke them into smaller subtasks, estimated each one, and added them up. When I was unsure, I talked with teammates or quickly scanned online discussions and blog posts for real-world benchmarks.

## Did estimating in advance provide any benefit?

Yes — and more than I expected. 

Even though many of my estimates were off, the simple act of estimating forced me to think deeply about the task before writing a single line of code. One clear example: I originally guessed that the review submission form would take about 1 hour. But while listing out the steps, I realized I had completely overlooked validation, error handling, and backend integration. I revised the estimate to **2.5 hours** and walked into the work much better prepared. 

On a bigger scale, our estimates helped us plan sprints realistically. If the total effort for a milestone looked overwhelming, we could immediately decide what to cut or postpone instead of discovering it too late.

## Was tracking actual effort useful?

Tracking actual effort turned out to be genuinely useful. After a few issues, a clear pattern emerged: I was consistently underestimating testing and debugging time.

A memorable case was the new tag filter — I thought it would take **30 minutes**, but it ballooned to **1.5 hours** thanks to stubborn UI bugs. Seeing that data repeatedly helped me start padding future estimates for similar work. As a team, the numbers also helped us identify bottlenecks, like design discussions taking longer than expected, so we made our meetings shorter and more focused.

## How did you track your actual effort? How accurate was it?

I tracked everything manually. For coding sessions, I noted start and stop times and subtracted any breaks or distractions. I did the same for non-coding work like design, research, and meetings. All of it went into a simple Google Sheet, and I updated the GitHub issue at the end of each session. 

The method demanded real discipline. It wasn’t perfect — I sometimes forgot to log a quick research session right away — but I stayed as honest and consistent as possible. Overall, I believe the tracking gave us a reasonably accurate picture.

## Reflection: What would you change next time?

Next time, I would get even more granular. Breaking tasks into smaller subtasks dramatically improved both estimation and tracking. I’d also set phone reminders to log time immediately after each session so nothing slips through the cracks. 

On the team side, a quick 10-minute weekly review of “estimates vs. actuals” would help us spot trends early and keep improving our planning.

## AI use for estimation/tracking

We used **GitHub Copilot** and **ChatGPT (GPT-4)** to support estimation and planning. I would often ask Copilot something like “How long does it typically take to implement a React form with validation?” just to get a sanity check. 

A typical prompt I used was:

> “Estimate the coding effort (in hours) to build a course search page in Next.js with filtering and responsive design.”

I usually spent around **5 minutes** per prompt — refining the question and reviewing the answer. The AI’s suggestions were usually in the right range, but I always adjusted them based on our specific project context and my own experience. Copilot also helped me write small scripts to process our effort logs, though I didn’t use AI directly for the tracking itself.

## Conclusion

Effort estimation and tracking weren’t perfect, but they genuinely improved how we built **Manoa Course Wise**. The process pushed us to plan more thoughtfully, communicate better, and learn from our missteps. With more practice, I’m confident we’ll get sharper at both estimating and delivering — turning what once felt like extra paperwork into a real superpower for future projects.
