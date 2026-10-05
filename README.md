# Udemy courses analysis: what makes a course sell

An interactive Tableau dashboard and written report on 3,676 Udemy courses. It shows which subjects, prices and course types attract the most learners and revenue, and what a new course creator should build.

[![Udemy courses analysis dashboard](screenshots/udemy-dashboard.jpg)](https://public.tableau.com/views/Udemy_17894801294820/Dashboard1)

## Links

- [Live Tableau dashboard](https://public.tableau.com/views/Udemy_17894801294820/Dashboard1)
- [Full report (PDF)](report/udemy-courses-analysis-report.pdf)
- [My portfolio](https://ibukunadedotun.netlify.app)

## Business question

Which subjects, prices and course types attract the most learners and revenue, and what should a new course creator build?

## Data

- 3,676 courses across four subjects: Web Development, Business Finance, Graphic Design and Musical Instruments.
- Courses published between July 2011 and July 2017.
- Source: [add the name and link of the dataset you downloaded]
- Revenue is estimated as list price multiplied by subscribers. It ignores discounts, refunds and Udemy's share.
- The workbook in `data/` contains the raw data, the cleaned data and the pivot tables.

## Process

1. Combined and cleaned the subject files in Excel.
2. Added free-or-paid and free-beginner flags and an estimated revenue column.
3. Built pivot tables to check the numbers.
4. Built a Tableau dashboard with KPI cards, the top ten courses, subscribers over time, subscribers by subject and subscribers by level, with filters for level, subject, free or paid, and rating.

## Key insights

- Web Development is 32.7% of courses but earns 71.3% of estimated revenue ($631M of $885M).
- The top 10% of courses make 77.8% of revenue, and 9 of the top 10 courses are Web Development, priced $175 to $200.
- Courses priced $151 to $200 are about 14% of paid courses but bring in about 61% of paid revenue.
- Free courses are 8.5% of courses but bring in 30.5% of all subscribers.
- Beginner and All Levels courses make 88.4% of revenue. Expert courses make 1.0%.
- Business Finance has as many courses as Web Development but earns about a fifth as much. A 5 Whys analysis pointed to a crowded market, not price or quality.

## Recommendations

- Plan around Web Development first.
- Build one long, comprehensive flagship course and test a $150 to $200 list price.
- Use a free beginner course as a front door, and track whether it leads to paid sales.
- Aim at Beginner and All Levels learners rather than Expert.
- Avoid generic Business Finance courses.

## Limitations

- The data is a snapshot of 2011 to 2017, so it describes that period and not Udemy today.
- Four course IDs appear twice (0.39% of revenue). The figures match the dashboard.
- These are patterns, not proof of cause.

## Files

| Folder | What is inside |
| --- | --- |
| `data/` | Excel workbook with raw data, cleaned data and pivot tables |
| `dashboard/` | Tableau workbook |
| `screenshots/` | Dashboard image |
| `report/` | Full written report (PDF) |

## Tools

Excel, Tableau Public
