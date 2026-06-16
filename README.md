# 🛵 Wolt Earnings Tracker

A simple web app I built to track my delivery work — how many deliveries I make,
how many hours I work, my tips, and my average pay per delivery and per hour over time.

I built it because I deliver for Wolt while studying programming, and I wanted real
numbers on my own earnings instead of guessing. It also gave me a real project to
practice JavaScript on.

## What it does
- Log each shift: date, number of deliveries, hours worked, base earnings, and tips
- See running totals: deliveries, hours, base pay, tips, and total earned
- See averages: ₪ per delivery and ₪ per hour
- A simple bar chart of earnings per shift (base + tips)
- Delete shifts you entered by mistake
- Saves everything in the browser, so the data is still there next time you open it

## How to run it
No installation needed. Just download the project and open `index.html` in any web browser
(Chrome, Edge, etc.). Your data is saved locally on your own computer.

## Built with
- HTML
- CSS
- JavaScript (no libraries or frameworks)
- Browser `localStorage` for saving data

## Things I practiced
- Reading and writing data with `localStorage`
- Working with arrays (`reduce`, `map`, `sort`, `splice`)
- Updating the page from JavaScript (DOM manipulation)
- Keeping the code organized into small, clear functions

## Ideas for next versions
- Filter by month
- Export the data to a file
- Track fuel or expenses to see net earnings
