# Habit Tracker

**The gist:** build an app that lets users succcessfully mark when they've completed a daily habit.

I find it helpful to track any new habit I want to start. Maybe it's practice guitar or meditate. Maybe it's go for a walk.

This project could be coded for any platform really—from a simple mobile app to a desktop app to a web app with a back-end. It's non-trivial while still being simple.

How you store the data is totally up to you and how ambitious you want to get. If you build this for the web, you could initially use [`localStorage`](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API). For mobile, use whatever the native API is for data storage.

## Spec

- Add habits
- Mark habit as complete for a given day
- Show habit as incomplete the next day and allow it to be completed again
- Show number of days in a row without missing
- Ability to delete habits that are no longer relevant

## Concepts

- GUI for interactions
- Dealing with some light time series data
- Simple data modeling
- Data storage

## Mock-Ups

![Habit Tracker Mock-Up](./img/habit-tracker.webp)

## Reference

- [Streaks app on iOS](https://streaksapp.com)

## Stretch Goals

- Calendar view showing when which days a given habit was completed
- Reminders / notifications
- More or less than daily completeability (did I just make that word up?)