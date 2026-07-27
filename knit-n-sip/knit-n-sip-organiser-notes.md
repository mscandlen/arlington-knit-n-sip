# Knit'n'Sip — organiser notes

Private working doc. Not on the website.

---

## The bench: venues not yet used

Every one is open Tuesdays and walkable from Orange/Silver. Hold these for swaps, weather, or when a regular disappoints.

| Venue | Station | Why hold it | Watch out |
|---|---|---|---|
| Texas Jack's BBQ | Clarendon (10 min) | Big tables, early close (9pm), quiet weeknights | Longest walk of the Clarendon options |
| Wood and Iron | Virginia Square | 5–7pm happy hour, big patio, dog-friendly | Service can vanish when busy |
| Screwtop Wine Bar | Clarendon | Best wine list on the line, order from your phone | Small and cramped — max ~8 people |
| Solset / Boulevard | Clarendon | Retractable roof, so it works in rain | New, still finding its feet |
| Inca Social | Rosslyn | Roomy, cheap, good non-alcoholic options | Loud when there's football on |
| Quarterdeck | Rosslyn (12 min) | Outdoor picnic tables, very casual | Long waits on food |
| Makers Union | Reston Town Center | If you ever want a second far-west stop | 45+ min from Arlington |
| Founding Farmers | Reston Station | Literally on the platform | Pricey; needs a booking |

**Rejected and why:** Don Tito (rooftop seating faces outward, bad for a group), Spider Kelly's (bag policy, dark), Liberty Tavern (too loud to talk), Punch Bowl Social (games venue, wrong energy), Bear Branch Tavern and Dogwood Tavern (2 miles from their stations — breaks the metro promise).

---

## One-off ideas

Things to drop into a normal Tuesday, or run as a one-off. None of them require making the club more complicated.

| Idea | Best timing | Effort | Notes |
|---|---|---|---|
| **Stash swap** | Any Tuesday, ideally January | Low | Everyone brings yarn they'll never use. Bring a spare tote for leftovers — someone has to take them home. |
| **Charity make-along** | Sept–Nov, delivered before Christmas | Medium | Hats and scarves for Doorways or A-SPAN in Arlington. Pick one recipient and confirm what they actually want first — most shelters want new, machine-washable, dark colours. |
| **Yarn shop crawl** | A Saturday | Medium | fibre space (Alexandria), Looped Yarn Works (Dupont). Metro-doable as a single loop. Their Thursday night runs 5–9pm if you want to end there. |
| **Fall Fiber Festival of Virginia** | Early October, Montpelier | High | Needs cars and carpooling. Big day out, good bonding, entirely off the metro. |
| **Maryland Sheep & Wool** | Early May, West Friendship MD | High | The big one. Worth flagging months ahead so people book the day. |
| **Show-us-how night** | Any Tuesday | Low | One person demos one thing for ten minutes — magic loop, invisible join, whatever. Not a class, just someone showing off. Keeps it from tipping into teaching. |
| **Mystery project bag swap** | December | Medium | Everyone brings a wrapped bag with yarn and a pattern under $20. Draw numbers. |
| **Library night** | Any month | Low | Central Library at Virginia Square, free room, no bar. Good for anyone who doesn't drink or can't spend. |
| **Anniversary party** | July 2027 | Medium | Book the private room at Courthaus Social. One year is worth marking. |
| **Winter picnic substitute** | Dec–Mar | Low | The Saturday slot shouldn't just vanish. Coffee shop mornings, or a museum café. |

---

## Winter problem

Picnics stop in November. Options for the monthly Saturday:

- Saturday morning at a café — Kaldi's opens at 7, Northside Social Clarendon is bigger.
- National Gallery or Renwick café — free entry, warm, on the line via L'Enfant/Metro Center.
- Central Library meeting room, free to book for Arlington groups.
- Skip it and go back to Tuesdays only until March. Nothing wrong with this.

---

## Growing it

| Channel | What to do | Cost |
|---|---|---|
| Instagram | The single highest-return one. Post the venue Sunday, a photo Wednesday. | Free |
| Ravelry group | Where knitters actually look for local groups. | Free |
| Meetup | Real discovery, but people RSVP and don't show. | ~$25/mo |
| Nextdoor | Arlington neighbourhoods, surprisingly effective for this demographic | Free |
| fibre space noticeboard | Ask if you can leave a card. They're community-minded. | Free |
| Arlington Central Library board | Physical board, right at Virginia Square | Free |
| ARLnow events | Local news site, well read in Arlington | Free/low |
| r/nova, r/washingtondc | One post, don't repeat it | Free |

**Don't** do all of these. Pick Instagram plus one, and actually keep them updated.

---

## The tote

Keep one bag packed so you never have to think about it:

- A table tent or small sign with the logo — the single most useful item, ends "is that them?"
- Spare stitch markers and a tape measure
- A few cheap ballpoint pens and blank cards for names
- A small power bank
- A spare tote for stash-swap leftovers

---

## Practicalities to settle

| Question | Options | Lean |
|---|---|---|
| Where does the group chat live? | WhatsApp, Signal, Discord | WhatsApp — lowest friction for this crowd |
| Do you take a headcount? | Email replies, a form, nothing | A rough count for reservations only; never a required RSVP |
| Who picks the venue? | You, or rotate | You for now. Rotating sounds fair and produces chaos. |
| What if you can't make a Tuesday? | Cancel, or hand the tote over | Have two people who can host. A club with one point of failure is a club with an end date. |
| Money | Free, or dues | Free. Dues create admin and a membership boundary you don't want. |

---

## Things that quietly kill clubs like this

- **Venue fatigue.** The same three bars for six months and people stop coming. The rotation through October is deliberately wide — keep it that way.
- **It becoming a class.** Once there's a teacher, there are students, and people who don't want a lesson stop turning up. Show-and-tell is fine; instruction is a different product.
- **Cliquing.** After about month four the same six people know each other and newcomers feel it. Fix: greet at the door, not from the table.
- **Loud rooms.** The single most common complaint about craft meetups in bars. Test any new venue at 5pm on a Tuesday *before* you announce it.
- **You burning out.** See the "two people who can host" line above.

---

## Worth checking before September

- Whether Heurich House's Stitch n' Sip runs past Thanksgiving this year.
- Courthaus Social's private room policy and minimum spend, if the group keeps growing.
- Happy hour times at CIRCA Clarendon and Continental — both currently run to 7pm, which is why they're on the rotation. If either shortens, the value case changes.

---

## Publishing the site (free)

All 25 files must sit in **one folder, no subfolders**. `index.html` must be there or nothing works.

### Easiest — Netlify Drop
1. Put every file in one folder.
2. Go to `app.netlify.com/drop`.
3. Drag the folder onto the page. It's live in seconds at a random address.
4. Make a free account to keep it, then rename it to something like `knitnsip.netlify.app`.
5. To update: drag the folder on again. It overwrites.

No command line, no Git, no card.

### More durable — GitHub Pages
1. Free account at github.com.
2. New **public** repository, name it `knitnsip`.
3. *Add file → Upload files*, drag all 25 in, commit.
4. *Settings → Pages → Source: Deploy from a branch → main / (root) → Save*.
5. Live at `yourname.github.io/knitnsip` in a minute or two.

Slightly more setup, but you can edit a page in the browser and it republishes itself — worth it if you'll be adding events every month.

### Free tier limits
Both give free HTTPS. Netlify allows 100GB of traffic a month, GitHub Pages roughly the same. A club site will use a fraction of a percent of that. Cloudflare Pages is a third option with no bandwidth cap, but it wants a Git repo, so it's GitHub Pages with extra steps for this use case.

### What costs money
Only a custom domain. `knitnsip.club` runs about $10–25 a year through Namecheap or Cloudflare Registrar. The host's free subdomain costs nothing and works fine.

### Before you publish
- The placeholder email has been removed from every page. When you have a real club address, add it back to the footer in each file (or just the home page) — search for "See the full calendar" in the footer and add the link beside it.
- **Private repos and Pages:** on GitHub's free plan, Pages only publishes from **public** repos. You can keep the repo private while you set things up, but the site won't go live until you either make the repo public or pay for GitHub Pro (~$4/mo). Making it public only exposes the site files themselves — the same files anyone could see once the site is live anyway.
