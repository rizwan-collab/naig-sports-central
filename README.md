# NAIG Sports Central 2027
### North American Ismaili Games — #CompeteConnectUnite

A complete tournament management system for NAIG 2027. Single HTML file — open in any browser, no server required.

---

## 4 User Roles

| Role | Access | Password |
|------|--------|----------|
| **Spectator** | Live scores, results, standings, brackets, medals | None — open to all |
| **Scorekeeper** | Score entry for assigned sports | PIN (default: `1234` admin, `2468` basketball) |
| **Regional Coordinator** | Manage a regional qualifying tournament | `regional2027` |
| **National Admin** | Full tournament control | `naig2027` |

---

## Features

**Spectator (public)**
- Live score ticker when games are in progress
- Full schedule with venues and times
- Pool standings by sport, age group, and division
- Playoff bracket visualization
- Medal table by region
- Sport cards with rules reference
- 14 regions listed (7 Canada + 7 USA)

**Scorekeeper**
- PIN pad, username/password, or QR code login
- Tap +/− for counting sports (basketball, soccer, etc.)
- Text input for time-based and precision sports
- Rules reminder visible during score entry
- Save progress or record final score

**Regional / National Admin (shared features)**
- Sidebar navigation — not tab soup
- Schedule calculator: 3 modes (fields needed / days needed / max teams)
- Venue management
- Team registry with sport, age group, division, region, pool
- Individual athlete registry
- Auto-generate round-robin pool play
- Bracket view with standings + one-click winner advancement
- Rulebook tab with printable PDF export
- Scoresheet export — official printable scoresheets per game

**National Admin (additional)**
- Scorekeeper management with PIN + QR token generation
- Medal centre with region standings
- JSON backup / restore
- Data reset

---

## NAIG 2027 Sports (14 from naismailigames.com)

**Team:** Basketball, Cricket (Hardball), Cricket (Tapeball), Dance, Flag Football, Football (Soccer), Throwball, Volleyball

**Individual:** Badminton, Chess, Pickleball, Table Tennis, Tennis, Track (100m–5000m)

**Age Groups:** U18 (15–17) · 18+ Open · Legends (45+)

---

## How to Use

1. Open `naig-sports-central.html` in any browser
2. Share the URL (after deploying) with your team
3. Spectators use it as-is — no login needed
4. Scorekeepers get a PIN from their coordinator
5. Regional coordinators use `regional2027`
6. National admin uses `naig2027`

---

*Built for AKYSB USA & Canada · naismailigames.com*
