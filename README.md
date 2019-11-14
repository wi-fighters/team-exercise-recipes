# Recipe book - team exercise

## The goal

In small cross-functional teams, deploy a multi-page recipe website to GitHub pages based on exercise 17 from yesterday. If you haven’t completed exercise 17, no worries, maybe someone in your team has, and you can always check the solution for inspiration.

### File structure

```text
recipe-website/
├── index.html
├── recipes/
│   ├── shakshuka.html
│   └── vegan-chocolate-balls.html
└── images/
    ├── shakshuka.jpg
    └── vegan-chocolate-balls.jpg
```

### Checklist

- everybody contributes a recipe in HTML (no CSS)
- the site has a homepage that links to each separate recipe
- all team names and roles are on the homepage
- every page has consistent navigation and styling
- the site is deployed to GitHub Pages

## The team

### Project manager (PM) — the connector :octocat:

You care about: Git workflow, agile process, deployment.

On GitHub, set up branch protection rules so a review is required before merging into master.
Ensure team members work on their own branch and only integrate to master via pull request (you may need to check how to do this and train your team).
Can you think of ways for your team to be more agile (working iteratively and checking in with each other on joint decisions)?

After consulting with your team, you have the final say about Git workflow decisions.

### User experience lead (UX) — the designer :nail_care:

You care about: Usability, accessibility, aesthetic.

Your mission is to make your website pop :sparkles:
Sketch some ideas on paper and discuss with your team before writing any code.
You’re the main CSS author for the project, but your QA buddy may make suggestions. Every HTML file will link to your CSS, so co-ordinate with your team to make sure their code is compatible with yours.

After consulting with your team, you have the final say on design decisions.

### Quality assurance lead (QA) — the diplomat :white_check_mark:

You care about: Accessibility, validation, consistent code style.

With attention to detail, check your team’s code quality and consistency. How will you make sure indentation is consistent on different machines? Are you using semantic HTML? Is the CSS organized and DRY? Are you all using the same head tags and navigation structure? Does your codebase feel like one consistent developer experience (DX)?

Suggest corrections via pull request (both HTML and CSS), and link to resources that explain why you're suggesting a change.

After consulting with your team, you have the final say on code style decisions.

## The timeline

### 9:45 - Kickoff

Look at everyone’s work for the recipe exercise and decide together which parts to keep for your team’s recipe book. Which structure (elements, IDs and classes) will you all stick to?

Consider:
- Which tasks need to be done and by whom?
- Which tasks depend on others being done first?
- How much time should be spent on each task?
- In case you go over time, which parts are highest/lowest priority?

Once you’re on the same page about those questions, get started!

### 10:45 - Standup

Meet with people in other teams who are in your role (e.g. Connectors meet with connectors. Designers with designers. Diplomats with diplomats)

Discuss:
- Each of you shares the plan that you have in place with your team.
- Ask questions, share ideas, offer ways to help each other.

### 11:00 - bring knowledge back to your team (quick check-in)

Go back to your own teams and share what you learned in the standup. Is there anything new you want to try at this point?

### 11:15 - keep working on your tasks

### 14:45 - team check-in
- How are you going toward your tasks?
- What do you need to re-prioritise so you have something to present on time?

### 15:15 - show-and-tell presentations (no slides this time please!)

As a team, show us your site! :tada:

Separately, each of you has 3 minutes to share:

- Which role did you have?
- What were the challenges of your role?
- How did you address them?
- What did you enjoy about your role?
- Share a project decision that you made and why (e.g. design decision, workflow decision, code consistency decision). Show us some code or git commands or whatever helps communicate your point :slightly_smiling_face: