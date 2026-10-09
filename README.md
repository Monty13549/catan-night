# Catan Night

A weekly Catan night planner. Each hex is an evening; settlers tap the nights they're free,
the best night glows, you lock it in, roll for a host, and log the winner.

Live at https://monty13549.github.io/catan-night/

Shared data lives in a Firebase Realtime Database (config in `index.html`, rules in
`database.rules.json`). Each group's board sits behind the random code in its link.
