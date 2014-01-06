# t

A daily time tracker

## Install

`npm install -g t-cli`

Install terminal notify, see this
[introduction](https://github.com/visionmedia/node-growl).

## Pomodoro

- A pomodoro set to 25 mins
- After a pomodoro, take a short break(5 mins)
- Every 4 "pomodori" take a longer break(15 mins)

Every task started, followed by a pomodoro.

Press `Ctrl+C` during a pomodoro is a interruption, you can choose a interrupted
reason, or input a reason directly, the reason will be loaded next time. Once press
`Ctrl+C` will save the task, press one more time to exist.

## Usage

First, set the tasks saved directory:

`t set directory`

Add a task and start working on this task:

`t start 'task working on'`

List today's tasks with ids:

`t list`

List last 3 days' tasks

`t list 3`

Start working on a task by id:


`t start id`

Add a todo task:

`t add 'task name'`
