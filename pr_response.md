# PR Response Doc — CineLog Watchlist Feature

## AI Usage
<!-- Fill in at the end — how you used AI tools during this project -->

## Comment 1 — Rename
**What I did**
I simply used Cmd + Shift + H to find all occurences of "save_to_watchlist" in the repo, and replaced it with "add_to_watchlist"
**How I verified:**
I used the same command to search for any occurences of save_to_watchlist, and found nothing, so it was successfully replaced.

## Comment 2 — Deduplication
**What I did:**
**How I verified:**


## Comment 3 — Missing test
**What I did:**
I created test_watchlist.py, and the necessary test, test_add_to_collection_nonexistent_film_raises. It asserts that add_to_watchlist raises an error for an invalid UUID.
**How I verified:**
I made sure to run the test suite, and it passed all tests.

## Comment 4 — Default visibility
**My position:**
**Reasoning:**
**Tradeoff acknowledged:**

## Comment 5 — Sort order
**My position:**
**Reasoning:**
**Engagement with reviewer's point:**

## Comment 6 — Rebase
**What conflicted:**
**How I resolved it:**
**How I verified no conflict remains:**

## PR Description
<!-- Written at the end — feature overview, design decisions, manual testing steps -->