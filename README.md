# FocusFlow — Smart Deadline Risk & Task Prioritization

## What is it?
A student productivity mini-project that calculates an explainable 0–100 Deadline Pressure Score using:
- 40% deadline urgency
- 25% unfinished work
- 20% importance
- 15% estimated effort

It recommends which task deserves attention first.

## Run locally
1. Extract the ZIP.
2. Open the `FocusFlow` folder.
3. Double-click `index.html`.
4. Add your own tasks and test different deadlines, importance, effort and progress values.

No installation is required.

## AWS deployment
This is a static HTML/CSS/JavaScript project and can be deployed using AWS Amplify Hosting or S3 static website hosting.

## Suggested evaluation demo
Add:
1. A task due tomorrow, critical, high effort, 10% progress.
2. A task due next week, low importance, low effort, 80% progress.
3. A project due in 2–3 days with medium progress.

Show that FocusFlow calculates different risk scores and recommends the highest-pressure task.

## Important academic note
The project should be presented as a distinctive implementation rather than a claim that no similar productivity software exists anywhere. Its differentiating idea is the explainable Deadline Pressure Score combining urgency, unfinished work, importance and effort.

## Future scope
AWS Lambda + API Gateway, DynamoDB, Amazon Cognito authentication, SNS reminders, calendar integration and ML-based workload prediction.
