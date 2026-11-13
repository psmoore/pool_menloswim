# Menlo Swim & Sport pool schedules — Pool Relay embed preview

Replicas of [menloswim.com](https://menloswim.com)'s two pool schedule pages, with their schedule images
replaced by live [Pool Relay](https://www.poolrelay.com) calendars. Edit `src/`, then `python3 build.py`.

| Page | Replaces | Calendars |
|---|---|---|
| `burgess.html` | `/pool-schedule-2/` | week `AOTHameMeEjxztrDYe536D` · lane by lane `rr06FW1Xgyh9wCUkpvh0hC` |
| `belle-haven.html` | `/pool-schedule-bellehaven/` | week `GQD3gzEFQhdxpNeC5ZCcYb` · lane by lane `kqsH4DryEqPTwI3OO7NPlG` |

Source: the Fall 2026 schedule PDFs (beginning September 8) posted on those pages, read 2026-10-08.

## Registration

Each page lists its pools' programs under "Register at …", filled live by `live.js` (`data-live="register"`) from each
group's Pool Relay passes: what it offers, its price range, and a link to its Pool Relay registration page.
