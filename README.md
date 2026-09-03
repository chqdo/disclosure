# DISCLOSURE

## By the numbers

The catalog currently holds 609 tools across 107 categories and folders, tagged with 72 distinct tags. These figures are not hardcoded; this paragraph counts whatever is actually loaded, so it stays accurate as the catalog grows.

One rule keeps tags useful rather than decorative: a tag is not created unless at least two tools share it. This prevents one-off tags from cluttering By tags mode without ever being useful for filtering.

## What this is

One page instead of fifty scattered bookmarks. That is the whole idea.

- Several hundred tools (search engines, username lookups, breach checkers, domain and DNS utilities, image forensics, and plenty more), each filed under a category so you can find it again.
- Everything runs client-side. No login screen, no server, no "we've updated our privacy policy" email six months from now.
- Four panels stacked top to bottom: the live stats bar, the search controls, the results, and a plain-language legal notice. That is the whole interface.

## Six ways in

Six buttons at the top of the controls panel. Same catalog, six angles on it. Press `1` through `6` from anywhere on the page to switch between them.

- **Tree view** is the default. Tools in folders. Click a category to open it.
- **All tools** shows every entry at once, no folders. Good for scrolling the whole thing or scanning search results.
- **By tags** filters by chips like **domain** or **free**. The **MATCH: ALL / ANY** toggle beside them decides whether a tool has to carry **every** chip you picked or just **one**.
- **About** is this page.
- **Workflow** is not a tool list. It is a set of branching diagrams showing how one piece of data (a name, an email, a domain) leads to the next. Every step is a shortcut into the matching Tree view category.
- **Report** is your case file. It gets its own section below.

## Searching

One box. It matches names, descriptions, and tags at the same time, live on every keystroke.

- Whatever matched is highlighted on each card, so you can see why a result showed up.
- Start typing in Tree view and you land in All tools automatically, since folders would only hide the matches.
- `Ctrl`/`Cmd`+`K` jumps to the search box from anywhere. `Esc` clears it while you are there.

## Tree view controls

- **Expand all** and **Reset view**, just under the tool count, open every folder or fold them all back up.
- Hover a category row and two buttons appear. **Copy** grabs that category as a list. **Open** launches every tool in it in its own tab.

## The Report

This is what turns a pile of links into an investigation. Every tool card has a diamond (◇) in its corner. Click it and the diamond fills in (◆), which means the tool is now in your report. Switch to **Report** mode to work with what you collected.

The idea is one card per finding. Write what you found, mark how sure you are, and attach a screenshot only if you need to.

- Two fields sit above the cards: a **Report title** and a **Motivation** note (what is this investigation about?). Both are optional and both show up near the top of every export.
- Click a card's tool name to open that tool in a new tab.
- **Confidence** is a three-way switch (To verify, Confirmed, Rejected) so a rated finding reads at a glance. Under it sits the **Collected** date.
- **Finding** is the main field on every card. It saves as you type. Keyboard shortcuts go quiet while any field is focused, so a stray keystroke will not throw you somewhere else.
- Under Finding, **+ Text evidence** and **+ Image evidence** attach a pasted excerpt or a local screenshot. It travels into the export with the finding.
- **Board view** is the working grid, two cards wide. **Timeline view** replays the same entries in collected-date order, and the export ends with the same timeline.
- **+ Custom note** adds a card that is not tied to any tool, for context or a loose end. It has the same fields as a tool card.
- Hover a card and drag the handle on its left to reorder. Board order is export order.
- Everything lives in your browser's local storage. No account, no sync. Clear your browsing data and it is gone, so **export anything that matters.**
- **Export HTML** opens a dark, self-contained report in a new tab (findings by category, sources, evidence annex, timeline). **Export Markdown** writes the same thing as text. **Export JSON** and **Import** round-trip the whole report, so you can stop and pick it back up later; the HTML export carries the same data and can be imported too. **Clear report** empties the list and asks first.

## Copy list and open all

Two buttons above the results, for when you want the whole visible set at once.

- **Copy list** copies the current view to your clipboard as tab-separated values (name, URL, description, tags, category), ready to paste into a spreadsheet.
- **Open all** opens every visible tool in its own tab, after a confirmation, since browsers tend to block a batch of pop-ups.
- Both are hidden in the modes where a flat list makes no sense (Tree view, About, Workflow, Report). Tree view has its own per-category Copy and Open. Report has Export and Clear.

## Sharing a view

The mode, the tags, and the search text are all encoded in the URL after the **#**. Copy the address bar, send it, and the other person opens the exact same filtered view. There is no state on any server. It is all in the link.

## Printing

`Ctrl`+`P` switches to a print layout with no background animation, no live stats, and no diamond buttons. What is left is a clean black-on-white list that drops neatly into a report as a sources appendix.

## Keyboard shortcuts

For people who would rather not reach for the mouse.

- `1` to `6` jump straight to a mode.
- `j`/`k` or the arrow keys move the highlight through whatever is on screen. (Not in About, Workflow, or Report, which have nothing to step through.)
- `Enter` or `Space` opens whatever is highlighted.
- `Ctrl`/`Cmd`+`K` focuses search. `Esc` clears it.
- `Ctrl`+`P` is the print layout. `Ctrl`+`U` shows the page source.
- None of these fire while you are typing in a field. The page checks first.

## That stats bar up top

None of it comes from us. That is your own browser describing itself. Date, time, OS, browser, IP, rough location, and local weather, read from your system or fetched from a handful of public APIs your browser calls directly. It is there as a small demonstration of what any site you visit can work out about you without asking.

## It's one file

Markup, styles, and every line of logic sit in this one document. No build step, no bundler, nothing minified into soup. `Ctrl`+`U` shows you the exact code running in your browser right now.

---
_Generated from disclosure.014.ca — About_
