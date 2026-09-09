# DISCLOSURE

## What this is

A few hundred OSINT tools on one page. Great for security assessments, missing-person CTFs, and investigative journalism. Also great for other things, but the legal notice and I have agreed the sentence ends here.

- Search engines, username checkers, breach lookups, domain and DNS utilities, image forensics, and a good deal more. Every entry has a category and a few tags.
- It runs entirely in your browser. No account to make, no server taking notes on you, no newsletter to unsubscribe from later.
- Three panels, top to bottom: the Browse controls, the results, and a short legal notice. That is the whole interface.

## The Browse bar

Six buttons across the top. It is the same catalog every time; the buttons only change how you look at it. Keys `1` to `6` switch between them from anywhere on the page.

- **Categories** is where you start. Tools sorted into folders. Click a folder to open it.
- **Full list** drops the folders and shows everything at once. Good for scrolling, and it is where search results land.
- **By tag** filters on chips like **domain** or **free**. The **MATCH: ALL / ANY** switch next to them decides whether a tool needs every chip you picked or just one of them.
- **Guide** is what you are reading.
- **Method** is not a tool list. It is a set of flowcharts. You start with a name, an email, or a domain, and each chart shows what that turns into next. Every box is a shortcut into the Categories folder that covers it.
- **Report** is your case file. There is a whole section on it further down.

## Searching

One box. It checks names, descriptions, and tags at the same time, on every keystroke.

- Matches get highlighted on each card, so it is obvious why something showed up.
- Type from any mode and the page flips to **Full list** on its own, because that is the only view search can actually filter.
- `Ctrl`/`Cmd`+`K` drops your cursor in the box from anywhere. `Esc` empties it while you are in there.

## The Categories view

- **Expand all** opens every folder at once. **Reset view** folds them all back down. Both buttons sit next to the tool count.
- Hover a folder row and two more buttons show up on it. **Copy** takes that folder as a list. **Open** launches everything inside it, one tab each.

## Building a report

This is the part that turns a page of links into an actual investigation. Every tool card has a hollow diamond in the corner. Click it, the diamond fills in, and that tool is now in your report. Open **Report** to work with what you kept.

The plan is one card per finding. Say what you found, say how sure you are, and add a screenshot only when the screenshot is the point.

- Two fields sit above the cards: a **Report title** and a **Motivation** line for what the whole thing is about. Both optional, both printed near the top of every export.
- Click a card's tool name to open that tool again in a new tab.
- **Confidence** is a three way switch: To verify, Confirmed, Rejected. The **Collected** date sits right under it.
- **Finding** is the main field on the card. It saves while you type. Shortcuts go quiet whenever a field has focus, so a stray keypress will not fling you across the page.
- **+ Text evidence** pastes in an excerpt. **+ Image evidence** attaches a local screenshot. Both ride along into the export.
- **Board view** is the working grid, two cards across. **Timeline view** is the same cards in collected order, and every export finishes on that timeline.
- **+ Custom note** adds a card with no tool attached, for context or a loose thread. Same fields as any other card.
- Grab the handle on the left edge of a card and drag to reorder. Board order is export order.
- All of it lives in this browser's local storage. No account, no sync. Wipe your browsing data and it is gone, so **export anything you want to keep.**
- **Export HTML** opens a dark, standalone report in a new tab: findings by category, a source list, an evidence annex, the timeline. **Export Markdown** is the same report as plain text. **Export JSON** and **Import** let you put the whole thing down and pick it up later, and the HTML export carries the same data if you would rather reimport that. **Clear report** wipes the list, and asks first.

## Copy list and Open all

Two buttons above the results for when you want the whole visible set in one move.

- **Copy list** copies the current view to your clipboard as tab separated values (name, URL, description, tags, category), ready to drop into a spreadsheet.
- **Open all** opens every visible tool in its own tab once you confirm, since browsers tend to swat a stack of pop-ups.
- Neither one appears where a flat list would be pointless (Categories, Guide, Method, Report). Categories has its own per folder Copy and Open. Report has Export and Clear instead.

## Sharing a view

The mode, the tags, and the search text all live in the URL after the **#**. Copy whatever is in the address bar, send it over, and the person on the other end opens the same filtered view. Nothing sits on a server. The link is the state.

## Printing

`Ctrl`+`P` swaps in a print layout: no background animation, no diamond buttons, just a black on white list. It slots into a report cleanly as a sources appendix.

## Keyboard shortcuts

For when reaching for the mouse is one step too many.

- `1` to `6` jump straight to a mode.
- `j` and `k`, or the arrow keys, move the highlight through whatever is on screen. Guide, Method, and Report sit this one out, since there is nothing to step through.
- `Enter` or `Space` opens whatever is highlighted.
- `Ctrl`/`Cmd`+`K` focuses search. `Esc` clears it.
- `Ctrl`+`P` is the print layout. `Ctrl`+`U` shows the page source.
- None of these fire while you are typing in a field. The page checks first.

## One file, no server

The markup, the styling, and every line of logic are in this single document. No build step, nothing bundled or minified into soup. `Ctrl`+`U` shows you the exact code your browser is running, which is also the entire app.

---
_Generated from disclosure.014.ca / Guide_
