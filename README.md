# Oregon with Mom & Caden · July 16–21, 2026

A custom interactive trip itinerary built as a single-page HTML app and hosted on GitHub Pages.

**Live site:** https://ashleyrosebryan856.github.io/mom-caden-trip/

---

## Trip Overview

Caden's first west coast trip — 5 nights in Oregon and Washington with Ashley and Grandma, plus Sam the puppy (14 weeks).

**Arriving:** Thu Jul 16 · AA 4427 + AA 2284 · PIT → ORD → PDX · lands 10:36am  
**Departing:** Tue Jul 21 · AA 3303 + AA 4539 · PDX → ORD → PIT · departs 1:45pm

---

## Itinerary

| Date | Day | Where | Highlights |
|------|-----|--------|------------|
| Thu Jul 16 | Arrival | Portland | Settle in, meet Sam, welcome dinner |
| Fri Jul 17 | Mt. Hood | Timberline Lodge (overnight) | Timberline Trail → Zigzag Canyon hike, Cascade Dining Room dinner |
| Sat Jul 18 | Hood River → Gorge | Skamania Glamping Tents (overnight) | Drop Sam at Christine's, lunch in Hood River, zip line or aerial park |
| Sun Jul 19 | Gorge → Home | Portland | Zip line if not done Sat, explore White Salmon WA, pick up Sam, home |
| Mon Jul 20 | Portland | Home | Forest Park hike, Powell's Books, easy last dinner |
| Tue Jul 21 | Departure | PDX | Leave home by noon, departs 1:45pm |

---

## Accommodations

- **Timberline Lodge** — Fri Jul 17 night · dog-friendly room · [timberlinelodge.com](https://www.timberlinelodge.com)
- **Skamania Lodge Glamping Tents** — Sat–Sun Jul 18–19 · Stevenson, WA · [skamania.com/stay/glamping](https://www.skamania.com/stay/glamping/)

---

## Activities

- **Timberline Trail → Zigzag Canyon** — ~4.5mi out and back from the lodge through wildflower meadows · [AllTrails](https://www.alltrails.com/trail/us/oregon/timberline-lodge-to-zig-zag-canyon)
- **Paddleboarding** — Trillium Lake (Fri, mom & Sam on shore) · Cook Park or Lake Oswego (Mon, TBD)
- **Zip Line / Aerial Park** — Skamania Lodge Adventures · Sat or Sun · [skamania.com/experiences](https://www.skamania.com/experiences/skamania-lodge-adventures/)
- **Forest Park hike** — Wildwood Trail from Germantown Rd · Mon Jul 20
- **Multnomah Falls** — optional stop on the I-84 drive home Sunday

---

## Sam's Logistics

Sam (Ashley's dog, 14 weeks old during the trip) comes on all Portland and Timberline days. She stays with Christine in Hood River Saturday morning through Sunday afternoon while the group is at Skamania.

- **Drop-off:** Sat Jul 18 morning · Christine's house · Hood River, OR
- **Pick-up:** Sun Jul 19 ~1pm · Hood River · on the way home via White Salmon

---

## Safety Ground Rules

Per Caden's mom's request:
- All hikes are a group of three — Ashley, Mom, and Caden together on trail at all times
- Life jackets required for all paddling
- Zip line and aerial park use professional harness systems with trained guides

### Nearest Hospitals by Location

| Location | Hospital | Notes |
|----------|----------|-------|
| Portland | OHSU | Level 1 Trauma · 3181 SW Sam Jackson Park Rd |
| Timberline Lodge | Providence Hood River Memorial | ~45min via Hwy 35 · 541-386-3911 |
| Hood River | Providence Hood River Memorial | Right in town · 811 13th St |
| Skamania / White Salmon WA | Providence Hood River Memorial | ~20min across bridge |
| Gorge / I-84 | Legacy Emanuel Medical Center | Level 1 Trauma · Portland |

---

## Caden's Packing List

- Hiking clothes (running shoes are fine)
- Puffy jacket (required for Timberline evenings at 6,000ft)
- Swimsuit
- Sunglasses & hat
- Medications and any sleep aids
- Apple Watch + charger, headphones for the flights, portable battery pack

---

## Site Structure

Built as a single `index.html` file hosted on GitHub Pages. No frameworks or build tools — just HTML, CSS, and vanilla JavaScript.

- **Map** — [Leaflet.js](https://leafletjs.com) with OpenStreetMap tiles. Route polyline, overnight stop markers, hike trail lines (hardcoded coordinates with OSM upgrade attempted on load), and paddle spot markers.
- **Images** — stored in the repo root alongside `index.html`
- **No backend** — all content is static. Updates are made by editing `index.html` and pushing to `main`.

### Files

| File | Description |
|------|-------------|
| `index.html` | The entire site |
| `mt hood.jpg` | Hero banner image |
| `Timberline.png` | Timberline Lodge highlight card |
| `zigzag canyon.png` | Zigzag Canyon highlight card |
| `Skamania Glamping.png` | Skamania glamping highlight card |
| `zipline.png` | Zip line highlight card |

---

## How to Update

All content changes are made directly in `index.html`. Push to `main` and GitHub Pages rebuilds automatically in ~60 seconds.
