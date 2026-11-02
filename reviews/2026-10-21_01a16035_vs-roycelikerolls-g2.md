# Review: stonks 📈 vs roycelikerolls, game 2, 21 Oct 2026

| | |
|---|---|
| **Status** | draft, for discussion |
| **Replay** | `01a16035-5f93` (`python3 tools/brief.py 01a16035 --turn N`) · [duels.ink viewer](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=0) |
| **Format** | Core Constructed (from game 1 of the match), best-of-three, game 2. Set 14 era: inks revealed before the coin toss |
| **Decks** | stonks 📈: Sapphire/Steel Big Ramp with the Darkwing package ([the coach's notes on it](#cite-kb-meta-archetypes-sapphire-steel-big-ramp-with-the-darkwing-package-how-to-play-it)). roycelikerolls: Amethyst/Steel **Midrange**, known from game 1 |
| **Play/draw** | roycelikerolls went first (they lost game 1, so it was their choice) |
| **Result** | Loss: stonks 📈 conceded at 0–17 on game turn 18, so the match went to a game 3 |
| **Meta data** | snapshot of 26 Oct 2026, five days after this game (fresh) |
| **Chosen how** | Sent by danny, the coach's user, with stonks 📈's other games of the day; the coach picked five to review and studied the rest. **The coach could work out this game's result in advance**: it studied game 1 (a win for stonks 📈, so a fair look at an earlier game), and a game 3 exists, so this game was a loss. Verdicts are guarded against outcome bias |

## Summary
- **Inaccuracies:**
  - The [pre-game](#turn-0): a mulligan of six from a hand with a plan.
  - [Turn 6](#turn-6): Priscilla played into a ready Pepita, whose Challenger exactly kills her the turn she enters
    exerted.
- **Good play:** [turn 14](#turn-14), Cinderella – Unintentional Icon before Finest. It used all 7 ink and started her
  ramp, with the cheap Shift still in hand.
- **Good:** turns [2](#turn-2), [4](#turn-4), [8](#turn-8), [10](#turn-10) and [12](#turn-12).
- **Unwinnable from:** [turn 16](#turn-16). They were on 9 with seven characters questing for 8, and nothing of
  yours could challenge or remove anything that turn. Both concession turns' plays were the best left.

**What decided it:** three Shere Khans. Each NEW INCENTIVE picked off the piece you had just landed:
- Drake Mallard, Finest's Shift base, on [turn 9](#turn-9)
- Merida, before her first action, on [turn 11](#turn-11)
- Cinderella – Unintentional Icon, with Angela's Challenger +2 on Demona, on [turn 15](#turn-15)

Meanwhile their cheap characters quested. After turn 4, nothing of yours survived their next turn.

## The game, turn by turn
Verdicts judge each decision on what stonks 📈 could know at the time, **including archetype knowledge an
experienced player has**. Hindsight is kept to its own section. Severity scale: good play / close call /
inaccuracy / mistake / blunder. Principle IDs and hypotheses (H-n) link to copies in the Citations section at the
end, as they stood when they were cited.

**What you knew before the game:** roycelikerolls's deck from game 1: Amethyst/Steel Midrange. They're on the play, so
a card costing N can come on game turn 2N−1 (one turn sooner after Merlin's ink drop). The cards that matter to Big
Ramp:
- **Flash – Efficient Clerk** (2, 3/2/2, Resist 1, uninkable): takes nothing from Windstorm's 1, and only 1 of STEADY
  AIM's 2. From turn 3.
- **Toulouse – Rough and Tumble** (2): when played, you can't play actions until their next turn. That shuts off
  Terror, Three Arrows and Windstorm for a turn. From turn 3.
- **Diablo – Stone Servant** (2, 1/3): 3/3/2 with a Villain in play, and their Villains can't be challenged while he's
  exerted. **Maleficent – Exultant Spellcaster** (1, 2/2) is a Villain.
- **Peter Pan's Shadow** (3, Evasive): exerts one of your characters when played. **Angela – Night Warrior** (3): gives
  a character Challenger +2 and Resist +2 for a turn. **David Xanatos – Steel Clan Leader** (3): discard a card to deal
  2. **Cheshire Cat** (3): Boost 2 moves 2 damage onto your character. **Woolter & Jesse** (3, 4/4, Bodyguard,
  Challenger 2). All from turn 5.
- **Strength of a Raging Fire** (3): damage equal to their character count, sung free by any 3-cost. From turn 5.
- **Shere Khan – Khan Industries CEO** (4): one of theirs may challenge your ready characters. **Angel – Experiment
  624** (4): discard to deal 2, once a turn. **Dumbo – Ninth Wonder of the Universe** (4, Evasive): draws and gains a
  lore for 1 ink, and gives their other Evasive characters the same. **Merlin – Profoundly Curious** (4). From turn 7.
- **Tinker Bell – Giant Fairy** (6, or Shift 4 onto Tinker Bell – Curious Fairy, a 1-cost 0/4): 1 damage to each of
  your characters when played. From turn 7 with the Shift.
- **Hades – Looking for a Deal** (5): you bottom the chosen character or they draw 2. From turn 9.
- **Demona – Scourge of the Wyvern Clan** (6): exerts all your characters, then refills both hands to 3. From turn 11.
- **Maleficent & Diablo – Evil Incarnate** (7, Shift 5 onto a Maleficent or Diablo, or free by putting 5 characters
  from their discard on the bottom of their deck): 6/5/2, draws whenever it exerts. From turn 9 with the Shift.

<a id="turn-0"></a>

### Pre-game

![Opening hand, step 0](screenshots/01a16035/turn0-step0-opening-hand.jpg)
*The board before the decision: [step 0](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=0) in the duels.ink replay viewer.*

**What you did:** On the draw. Kept one Darkwing Duck – Crime Fighter and sent back six: Cinderella – Dream Come True,
Priscilla – Efficient Clerk, the other Darkwing, Windstorm, Goliath – Clan Leader and Khan Industries – Greenway
Landmark.

**Verdict:** **Inaccuracy.** Sending back six from this hand is suboptimal because it already had the deck's early
plan: two 1-drops, Priscilla on turn 3 (ramp and card selection from her first quest), Dream Come True on turn 4 (a
Princess, so her end-of-turn ink-and-draw fires that turn), and Khan Industries at 5. Six of the seven were
inkable. Keeping all seven, or sending back only Goliath, is better:
- **The sim** (`mulligan.py`, 1,500 deals) favours the keep on every measure. Ink by turn 4 was 9.59 against your
  9.32, play turns 4.00 against 3.91, lore by turn 4 7.2 against 6.4, and characters 4.3 against 3.8. Interaction was
  100% against 93%.
- **What the sim can't weigh:** the mulligan gave up Priscilla and Khan Industries, pieces the deck has to find later,
  for random cards. The notes on this deck found early Priscilla in most of its wins against Emerald/Steel
  ([the coach's notes](#cite-kb-meta-archetypes-sapphire-steel-big-ramp-with-the-darkwing-package-how-to-play-it)).
- **The case for sending some back:** Windstorm is weak against Flash's Resist, and Goliath isn't a card for this
  matchup. Sending back Goliath alone (keep 6) sims the same as keeping all seven.

[MULL-1](#cite-mull-1) and [MULL-4](#cite-mull-4) apply, and the coach's notes on this deck say to build from the hand you have. Confidence: medium. The
gap the sim shows is modest, and the deck's late game decides more than turns 1–4.

<a id="turn-1"></a>

### Turn 1: their turn

**What happened:** roycelikerolls inked David Xanatos – Steel Clan Leader and played Maleficent – Exultant
Spellcaster (2/2, a Villain).

<a id="turn-2"></a>

### Turn 2: your turn 1

![Turn 2: your turn 1, step 5](screenshots/01a16035/turn2-step5-start.jpg)
*The board before the decision: [step 5](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=5) in the duels.ink replay viewer.*

**What you did:** Drew Priscilla – Efficient Clerk, inked Tiana – Party Hostess, played Darkwing Duck – Crime
Fighter.

**Verdict:** **Good.** All eight cards were inkable, and the Darkwing is the turn-1 play. Which 7-drop to ink was
close. Keeping Tiana with Khan Industries in hand saves 5 ink at 7 (IDEAL VENUE discards Khan and plays it free).
Keeping Cinderella – Unintentional Icon can save 2 ink at 5, by Shift onto a Dream Come True the deck draws later.
Either is fine.

<a id="turn-3"></a>

### Turn 3: their turn

**What happened:** They inked Strength of a Raging Fire and played Pepita – Watchful Alebrije (2/3, Challenger +2).
Maleficent quested (0–1).

<a id="turn-4"></a>

### Turn 4: your turn 2

![Turn 4: your turn 2, step 12](screenshots/01a16035/turn4-step12-start.jpg)
*The board before the decision: [step 12](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=12) in the duels.ink replay viewer.*

**What you did:** Drew Darkwing Duck & Launchpad – St. Canard's Finest. Inked the other Darkwing Duck – Crime Fighter,
played Darkwing Duck – Drake Mallard, and the Crime Fighter in play challenged the exerted Maleficent: both were
banished.

**Verdict:** **Good**, the coach's line except for the ink.
- **The trade:** Maleficent is more than a 1-drop. She's the Villain that turns on Diablo – Stone Servant, and the
  cheap base for Maleficent & Diablo – Evil Incarnate's Shift 5. A Crime Fighter for her is a good trade.
- **Drake Mallard** (4/1, Ward) is the safest Darkwing to leave on the board. Strength of a Raging Fire, David Xanatos
  and Angel can't choose it, so it should still be there as Finest's Shift base at 5 ink. Its 1 willpower only matters
  once it's exerted: a Peter Pan's Shadow (about 30% by their turn) could exert it for Pepita.
- **The ink:** the coach would have inked Cinderella – Unintentional Icon rather than the 1-drop, since the hand
  already had Khan Industries and Finest for the 5-ink turns. It's a small difference either way.

<a id="turn-5"></a>

### Turn 5: their turn

**What happened:** Nothing: no ink, no play, and Pepita stayed back. They hold 5 cards on 2 ink.

<a id="turn-6"></a>

### Turn 6: your turn 3

![Turn 6: your turn 3, step 17: before Priscilla](screenshots/01a16035/turn6-step17-before-priscilla.jpg)
*The board before the decision: [step 17](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=17) in the duels.ink replay viewer.*

**What you did:** Drew Merida – Formidable Archer, inked the second Drake Mallard, played Priscilla – Efficient Clerk.
Drake Mallard stayed back.

**Verdict:** **Inaccuracy.** Playing Priscilla into a ready Pepita is suboptimal because she enters play exerted
(NOT-SO-SECRET CRUSH), and Pepita challenges for exactly her 4 willpower (2 strength, Challenger +2). Priscilla has no
strength, so that's a free kill. Your only answer is for Drake Mallard to trade itself for the exerted Pepita a turn
later, so the likely result is Priscilla and a Drake for Pepita.

Playing the second Drake Mallard and questing with the first is better. It keeps Priscilla for a turn when Pepita is
gone, and puts 1 lore on the board. What it exposes:
- **The questing Drake** (1 willpower) offers Pepita a trade: Drake's 4 strength kills it in return. That's an even
  trade that clears the way for Priscilla.
- **Both Drakes** have Ward, so Strength of a Raging Fire, David Xanatos and Angel can't target them. Only a Peter
  Pan's Shadow (about 35% by their turn) exerts the other.
- **The cost:** 1 ink unused, and Priscilla's ramp starts a turn later.

The case for your line: if Priscilla survives, her first quest next turn ramps you to 5 a turn early (Finest's Shift,
Merida or Khan Industries on turn 8). The early-Priscilla pattern in the coach's notes points the same way. But that
needs them to pass up a free kill. They did hold back last turn, on 2 ink with 5 cards, so it's not impossible.
[RULE-1](#cite-rule-1). Confidence: medium-low.

<a id="turn-7"></a>

### Turn 7: their turn

**What happened:** They inked Maleficent & Diablo – Evil Incarnate and played Woolter & Jesse – Bellwether's
Henchmen (4/4, Bodyguard, Challenger +2), ready. Pepita challenged Priscilla and banished her, taking nothing.

<a id="turn-8"></a>

### Turn 8: your turn 4

![Turn 8: your turn 4, step 25](screenshots/01a16035/turn8-step25-start.jpg)
*The board before the decision: [step 25](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=25) in the duels.ink replay viewer.*

**What you did:** Drew the second Priscilla, inked Khan Industries, and passed with Drake Mallard ready and Priscilla
in hand.

**Verdict:** **Good.** The coach planned the same pass:
- **Drake Mallard stays ready.** It's Finest's Shift base for next turn. It's been in play since turn 4, so Finest
  shifted onto it can challenge at once ([RULE-2](#cite-rule-2)), and VICTORY POSE pays 2 for each banish. Trading it for the exerted
  Pepita now would push Finest back to 7 ink. While Drake is ready and has Ward, only a Shere Khan (about 31% by
  their turn) can get a challenge into it. Peter Pan's Shadow can't choose it.
- **Priscilla waits.** She'd enter exerted again, in front of Woolter & Jesse (6 when challenging) and Pepita.
  Holding her keeps the card for a safer turn.
- **The ink was close.** Khan Industries is where Priscilla would be safe from challenges, and it makes 2 lore a
  turn. The coach would have inked Cinderella – Unintentional Icon, which needs 7 ink or a Dream Come True. Against
  Woolter & Jesse and Pepita, though, Khan Industries can be challenged down quickly (8 willpower against 6 and 4,
  [RULE-3](#cite-rule-3)), so it's close.

What it exposes: nothing on the board but the ready Drake. Their next turn has 4 ink: Shere Khan, Angel, Dumbo or
Merlin.

<a id="turn-9"></a>

### Turn 9: their turn

**What happened:** They inked Cheshire Cat and played Shere Khan, whose NEW INCENTIVE let Pepita challenge the ready
Drake Mallard: both were banished, and CORNER THE MARKET gave them an ink drop. Woolter & Jesse quested (0–2).

<a id="turn-10"></a>

### Turn 10: your turn 5

![Turn 10: your turn 5, step 33](screenshots/01a16035/turn10-step33-start.jpg)
*The board before the decision: [step 33](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=33) in the duels.ink replay viewer.*

**What you did:** Drew The Terror That Flaps in the Night, inked the second Priscilla, played Merida – Formidable
Archer, and held Terror.

**Verdict:** **Good**, the coach's line.
- **Merida first, then actions:** next turn Terror deals 2, plus 2 from STEADY AIM. That's enough for Woolter &
  Jesse (4 willpower) or Shere Khan.
- **Terror now** would kill only Shere Khan (2 damage without a Darkwing), and the 3 ink left would buy nothing that
  survives.
- **Inking Priscilla:** against Woolter & Jesse's Challenger and Shere Khan's NEW INCENTIVE, there was no safe turn to
  land her, and Khan Industries, where she'd be safe, was already ink.

What it exposes: Merida is ready, so Woolter & Jesse (6 when challenging) reaches her only through a second Shere Khan
(about 20% by their turn). A Demona – Scourge of the Wyvern Clan (about 26%; their 4 ink, one more and the drop make
6) would exert her for the same challenge. Strength of a Raging Fire (sung free by Woolter & Jesse) and Angel together
would also do it. Hades – Looking for a Deal would ask you to bottom her or let them draw 2.

<a id="turn-11"></a>

### Turn 11: their turn

**What happened:** A second Shere Khan let Woolter & Jesse challenge the ready Merida: she was banished, and Woolter &
Jesse took 3 (1 willpower left). Two ink drops from CORNER THE MARKET paid for Peter Pan's Shadow (whose exert they
declined) and You Broke My Smolder (two cards). The first Shere Khan quested (0–3).

<a id="turn-12"></a>

### Turn 12: your turn 6

![Turn 12: your turn 6, step 47](screenshots/01a16035/turn12-step47-start.jpg)
*The board before the decision: [step 47](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=47) in the duels.ink replay viewer.*

**What you did:** Drew Tiana – Party Hostess. Terror dealt 2 to Woolter & Jesse (1 willpower left) and banished it.
Inked Tiana.

**Verdict:** **Good.** With 6 ink and three 7-drops, Terror was the only play, and Woolter & Jesse was the right
target. It's their best challenger, at 6 strength when challenging, enough for Tiana or Cinderella – Unintentional
Icon, and the Bodyguard. The Shere Khans and Peter Pan's Shadow are 1 lore each like it, but hit for 4 and 2.
Which 7-drop to ink was a matter of taste: Finest (Ward, 7 willpower) is the one to keep, and you did.

What it exposes: nothing; your board is empty. Their 4 lore a turn puts them at 20 around game turn 21, so the 7-drops
have to start landing next turn.

<a id="turn-13"></a>

### Turn 13: their turn

**What happened:** They inked Angela – Night Warrior and played Demona – Scourge of the Wyvern Clan. With no
characters of yours to exert, her refill drew them 2 and you 1 (Marie; you held 2). Both Shere Khans and Peter Pan's
Shadow quested (0–6).

<a id="turn-14"></a>

### Turn 14: your turn 7

![Turn 14: your turn 7, step 57](screenshots/01a16035/turn14-step57-start.jpg)
*The board before the decision: [step 57](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=57) in the duels.ink replay viewer.*

**What you did:** Drew a Darkwing Duck – Crime Fighter, inked Marie, and played Cinderella – Unintentional Icon for
7. At the end of the turn BESPOKE DESIGN inked a Drake Mallard and put Finest on top of the deck.

**Verdict:** **Good play**, better than the coach's plan. The coach planned the Crime Fighter and Finest shifted onto it
(1 + 5), then Icon next turn. That's 6 of the 7 ink. Your order uses all 7, and starts Icon's ramp a turn sooner: 8 ink
after BESPOKE DESIGN, 9 next turn. The Crime Fighter and Finest in hand still make the cheap Shift next turn (1 + 5),
with 3 ink to spare. The trade-off is that Icon has no Ward, so Hades – Looking for a Deal (about 29% by their turn)
can choose her: you'd bottom her or let them draw 2.

What it exposes: Icon is ready with 6 willpower. A third Shere Khan (about 16%) lets one of theirs challenge her, but
Demona's 5 isn't enough alone. A second Demona – Scourge of the Wyvern Clan (about 23%) exerts her, and then Demona
and both Shere Khans together (13) kill her. Strength of a Raging Fire with their five characters deals 5.

<a id="turn-15"></a>

### Turn 15: their turn

**What happened:** Angela – Night Warrior gave Demona Challenger +2 and Resist +2, and a third Shere Khan let Demona
challenge the ready Icon: 7 against her 6 willpower. Icon was banished, and Demona took 2 (4 less Resist). Three ink
drops came from CORNER THE MARKET (once per Shere Khan). Both Shere Khans and Shadow quested (0–9), and the drops paid
for a Pepita.

<a id="turn-16"></a>

### Turn 16: your turn 8

![Turn 16: your turn 8, step 77](screenshots/01a16035/turn16-step77-start.jpg)
*The board before the decision: [step 77](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=77) in the duels.ink replay viewer.*

**What you did:** Drew the second Finest. Played one Finest for 7 and the Crime Fighter, keeping the other Finest.

**Verdict:** **Good, but the game was lost by now** ([principle 2](#cite-principle-2)). They were at 9 with seven characters questing for
8 a turn: 17 next turn and 20 the turn after (`tools/odds.py clock`). Nothing of yours could challenge this turn, and
you held no removal. On turn 18 you could kill at most three questers: Finest, a second Finest shifted onto the dry
Crime Fighter, and a Crime Fighter challenge. That leaves at least four characters to find the last 3 lore. Your line
was the best of what remained: two bodies for 8 of 9 ink, and the second Finest kept for the cheap Shift.

<a id="turn-17"></a>

### Turn 17: their turn

**What happened:** All seven quested (0–17), and they added Diablo – Stone Servant.

<a id="turn-18"></a>

### Turn 18: your turn 9

![Turn 18: your turn 9, step 89](screenshots/01a16035/turn18-step89-start.jpg)
*The board before the decision: [step 89](https://duels.ink/replay/01a16035-5f94-7a8e-afb0-be0d7bc28ed4?step=89) in the duels.ink replay viewer.*

**What you did:** Drew Three Arrows and conceded at 0–17.

**Verdict:** **Good: the game was lost** ([principle 2](#cite-principle-2)). They needed 3, and their eight characters quest for 10.
The most you could remove was four of those 10:
- **Three Arrows:** 2 to Peter Pan's Shadow (Evasive, so nothing of yours can challenge it) and 1 to a Shere Khan.
- **Two Finest challenges:** the second Finest shifted onto the dry Crime Fighter, and each Finest kills a quester.

That leaves six lore of questers against the 3 they needed.

## Lessons
1. **Priscilla enters play exerted** (NOT-SO-SECRET CRUSH), so she can be challenged the turn she lands. Before
   playing her, count what can challenge her: Pepita (4 with Challenger) and Woolter & Jesse (6) kill her outright.
   Against a Challenger board, play her once they're gone or exerted and spent, or move her to Khan Industries.
2. **Against Shere Khan, one big character a turn gets picked off.** NEW INCENTIVE lets their best challenger hit a
   ready character, and their Challengers and Angela – Night Warrior push that to 6 or 7 strength. Ward doesn't stop a
   challenge ([RULE-1](#cite-rule-1)'s note on Shere Khan). This list showed three Shere Khans in one game. Count the copies seen, and
   before landing a key piece ask what their next turn's best challenge does to it.
3. **Add up the pumps, not just the base strength.** Pepita and Woolter & Jesse have Challenger +2, and Angela gives
   Challenger +2 and Resist +2 to anything. The coach's own exposure note on turn 14 missed Angela (see The coach's
   errors).
4. **A hand with a plan is worth keeping** ([MULL-1](#cite-mull-1), [MULL-4](#cite-mull-4)). Two 1-drops, Priscilla, Dream Come True and Khan
   Industries was the deck's early game. The mulligan gave up the pieces it later needed.

## Proposed knowledge-base updates (applied after discussion)
- **Meta, the Amethyst/Steel notes (Midrange against Big Ramp), roycelikerolls's list from game 2:**
  - **The list:** Shere Khan ×3, Angela – Night Warrior ×2, Pepita ×2, Tinker Bell – Curious Fairy ×2, Woolter &
    Jesse, Peter Pan's Shadow, Demona – Scourge, Cheshire Cat, Diablo – Stone Servant, Maleficent – Exultant
    Spellcaster, Maleficent & Diablo – Evil Incarnate, David Xanatos, You Broke My Smolder and Strength of a Raging
    Fire.
  - **Not in the listed Midrange:** Xanatos, Maleficent & Diablo, Woolter & Jesse and You Broke My Smolder.
  - **How it beat Big Ramp:** NEW INCENTIVE on Drake Mallard (turn 9), Merida (turn 11) and Unintentional Icon (turn
    15, with Angela on Demona). Pepita killed Priscilla as she landed (turn 7).
- **Meta, the Sapphire/Steel notes (Big Ramp's coaching points):**
  - Priscilla enters exerted. Against Challenger characters, land her after they're gone, or move her to Khan
    Industries.
  - Against Shere Khan, count their best challenge, with pumps, before landing a key piece.
- **Strategy:** none new. Turn 6 is evidence for lesson 1, which belongs in the deck's notes rather than a principle.

## Hindsight
Doesn't change the verdicts above.
- **Their draws lined up:** three Shere Khans by turn 15, each arriving the turn after you landed a key piece. The
  brief put each at about 20–31% a turn, and they hit every time.
- **Their quiet turn 5** (no ink, no play, with 5 cards on 2 ink) suggests a hand of uninkable cards early. Shere
  Khan, Woolter & Jesse, Peter Pan's Shadow and You Broke My Smolder are all uninkable. It didn't last.
- **The mulligan's new six** were a Crime Fighter, two Drake Mallards, Tiana, Cinderella – Unintentional Icon and Khan
  Industries: a playable hand, but with the deck's 7s instead of its turn-3 and turn-4 plays.

## The coach's errors
Errors the coach caught in its own work. The user may add more in discussion. None changed a verdict.

| When | Error | How it was caught | How it won't happen again |
|---|---|---|---|
| Turn 2 | Read turn 3 in the same command as turn 2, before writing turn 2's section. This was the same error as in game 3 against MFork, made after its fix (a warning) was in place. The warning printed, but too late | The coach, from the warning | `tools/brief.py` now refuses to print a turn while any earlier turn of yours has no section in the draft. `--draft-ok` skips the check outside a blind pass |
| Turns 2–14 | Cut each brief's "Knowledge base notes on the cards in view" with `sed` ranges, against the rule to read briefs whole. An audit of the notes cut found none that changes a verdict | The coach, when Angela's note pointer turned up on turn 14 | A rule wasn't enough. Proposed: a hook that refuses any command piping `tools/brief.py` into `sed`, `grep`, `awk`, `head` or `tail` (needs the user's OK, as it changes the project's settings). Turns 16 and 18 were read whole |
| Turn 14 | What Icon exposed: "Demona's 5 isn't enough alone." It missed Angela – Night Warrior's Challenger +2, which with a Shere Khan makes 7 against her 6. The verdict stands: Finest's 7 willpower falls to the same 7 | The coach, on reading turn 15 | Angela wasn't tagged as a combat trick. `tools/meta.py` now tags "give chosen character Challenger +N", so the brief lists her with the chance they hold one |
| Turn 18 | The brief's options listed only Finest itself as a Shift target for the second Finest, not the Crime Fighter. Finest is also named Darkwing Duck ([CR 5.2.6.1](#cite-cr-5-2-6-1)) | The coach, while planning the turn | Fixed in `tools/brief.py`: a name with "&" counts as each of its names when it looks for Shift targets |

## Open questions
- **The mulligan:** what were you looking for when you sent six back? It's the second near-full mulligan the coach has
  seen from you (game 3 against MFork was the other).
- **Turn 6:** did you expect Pepita to challenge Priscilla, or was she bait for Drake Mallard's trade?
- **Turn 14:** was ink efficiency your reason for playing Icon before Finest, or something else?

## Citations
Copies of the coach's knowledge base cited above, as they stood when they were cited (the private repository's commit and date are given with each). They don't change when the knowledge base does.

<a id="cite-mull-1"></a>**MULL-1**: strategy principle, `kb/strategy/principles.md` at `1877f38` (2026-11-02), working tree

> - **MULL-1. Keep a plan, not the strongest cards.** *Ask: "Which hand gives me the best chance to execute my game plan in this matchup?"* `[MCL ch.12]` · baseline

<a id="cite-mull-4"></a>**MULL-4**: strategy principle, `kb/strategy/principles.md` at `1877f38` (2026-11-02), working tree

> - **MULL-4. Don't chase a perfect hand.** Flexible hands with several lines beat hands that need one specific draw. `[MCL ch.12]` · baseline

<a id="cite-rule-1"></a>**RULE-1**: strategy principle, `kb/strategy/principles.md` at `1877f38` (2026-11-02), working tree

> - **RULE-1. Only exerted characters can be challenged** `[CR 4.6.4.2]`. Questing, singing, or {E} for an ability exposes the character. Staying ready protects it. Every quest is also a decision about what the opponent can challenge next turn. · baseline
>   - *Card text overrides this* (CR 1.2.1). Shere Khan – Khan Industries CEO's NEW INCENTIVE lets one character
>     challenge ready characters that turn. Alert (e.g. from Judy Hopps – Lead Detective, to every Detective on their
>     turn) ignores Evasive. Against Ducktectives, name both in the setup. 01a14574, turns 16 and 18. `[coach, 2026-10-26]`

<a id="cite-rule-2"></a>**RULE-2**: strategy principle, `kb/strategy/principles.md` at `1877f38` (2026-11-02), working tree

> - **RULE-2. Drying** `[CR 1.7.5]`. A newly played character can't quest, challenge or sing until next turn, so it's exposed to nothing (it's ready) but contributes nothing. **Shifting onto a dry character gives an immediate actor** `[CR 8.10.4]`. Rush allows challenges only `[CR 8.9]`. · baseline

<a id="cite-rule-3"></a>**RULE-3**: strategy principle, `kb/strategy/principles.md` at `1877f38` (2026-11-02), working tree

> - **RULE-3. Locations can be challenged at any time and don't hit back** `[CR 4.6.8]`. They pay lore at your Set step `[CR 3.2.2.2]`, so a location that survives one opponent turn has usually already paid something. · baseline

<a id="cite-principle-2"></a>**principle 2**: coaching principle, `CLAUDE.md` at `1877f38` (2026-11-02), working tree

> 2. **Some games are unwinnable.** Draws and matchups can make a game lost whatever the player does. Say so
>    when it's true, rather than inventing mistakes to explain a loss.

<a id="cite-cr-5-2-6-1"></a>**CR 5.2.6.1**: Comprehensive Rules, `kb/rules/cr/05-cards-and-card-types.md` at `1877f38` (2026-11-02), working tree

> **5.2.6.1.** Some characters have two singular names in addition to their printed name. These characters have an ampersand (&) or something else that’s treated as an ampersand (see 5.2.6.3) between the two names listed on the name line. If an effect looks for a card or character with a specified name, the specified name must exactly match one of the names on the card.

<a id="cite-kb-meta-archetypes-sapphire-steel-big-ramp-with-the-darkwing-package-how-to-play-it"></a>**sapphire-steel.md, Big Ramp with the Darkwing package: how to play it**: knowledge base, `kb/meta/archetypes/sapphire-steel.md` at `1877f38` (2026-11-02), working tree

> ### Big Ramp with the Darkwing package: how to play it `[coach, study of stonks 📈's 22 games of 21 Oct 2026 (sent by the user), full games, not blind]`
> The user calls this list Sapphire/Steel Detectives, or Big Ramp. It matches duels.ink's "Big Ramp #1" (Windstorm,
> Minnie) with the Darkwing Detectives added. Games: `01a15f98` to `01a1602c` (22; see `kb/meta/index.md`). Card text
> verified with `tools/cards.py`. Also `01a15f8e` (vs MFork, game 2) and `01a16978` (vs AkatsukiCap, game 1).
> - **The list (60):**
>   - **1-drops:** Darkwing Duck – Crime Fighter ×4, Marie – Caught in the Act ×4
>   - **2-drops:** Darkwing Duck – Drake Mallard ×4 (Ward), Launchpad – Trusty Sidekick ×4, The Terror That Flaps in
>     the Night ×4
>   - **3–4:** Three Arrows ×4, Priscilla – Efficient Clerk ×3, Cinderella – Dream Come True ×4, He Hurled His
>     Thunderbolt ×2, Windstorm ×3
>   - **5–6:** Merida – Formidable Archer ×4, Khan Industries – Greenway Landmark ×4, Goliath – Clan Leader ×3
>   - **7–8:** Darkwing Duck & Launchpad – St. Canard's Finest ×4, Cinderella – Unintentional Icon ×2, Tiana – Party
>     Hostess ×4, Minnie Mouse – Urban Visionary ×3
> - **The plan:**
>   1. **Early removal** keeps their board small: Terror (3 damage while a Darkwing is in play), Three Arrows (2, then 1).
>      A Darkwing in play also makes Launchpad's draw free of the discard.
>   2. **Ramp:** Priscilla (enters exerted; each quest puts one of the top 2 into hand and the other into the inkwell,
>      2 lore), Cinderella – Dream Come True (at the end of a turn you played a Princess, ink a card from hand to draw),
>      Cinderella – Unintentional Icon (Shift 5 onto her; ramps one a turn, 3 lore), Marie (an ink drop when she quests
>      after an opposing character took damage). Ink at the start of its 5th turn was usually 5–6, and 8–9 by its 6th in the fastest games.
>   3. **The sweep: Merida, then Windstorm.** STEADY AIM adds 2 damage to every instance of action damage to an
>      opposing character, so Windstorm deals 3 to each (5 to an Evasive one): a 4- to 6-character wipe (01a1601c
>      turn 11: six Princess Aggro characters). Merida's FULL QUIVER also returns Three Arrows (then 4 and 3).
>   4. **Lore:** Khan Industries (2 a turn at their Set step; characters there can't be challenged, so Merida and
>      Priscilla move in), Merida 2, Priscilla 2, Cinderella – Unintentional Icon 3, Minnie 3, St. Canard's Finest 2
>      plus VICTORY POSE (+2 per banish in a challenge on its turn).
>   5. **Tiana – Party Hostess** (7): draw 2 and discard one; a discarded Khan Industries is played free (01a15fee,
>      01a15ff6, 01a1602c). **Minnie** (8, Ward) returns a card from the inkwell to hand when she ends a turn exerted.
>      **Goliath – Clan Leader** puts both hands to 2 at the end of each turn: strictly for pressing an advantage when
>      ahead, or for keeping a control deck's hand small; otherwise rarely played (user, 2026-11-02).
> - **Results by matchup** (13–9): Emerald/Steel Midrange 8–4, all four game 1s lost and every game 2 and 3 won;
>   Amber/Emerald Circle of Life 2–4; Princess Aggro 2–1; Amethyst/Steel Midrange 1–0.
> - **What won:** the Merida and Windstorm sweep, Finest's VICTORY POSE, Khan Industries with protected questers. Early
>   Priscilla matters: in the Emerald/Steel wins she was down by its 4th turn in five of eight, and in the four losses never
>   (a correlation from few games).
> - **It can race from behind once the questers are gone:** in 01a16978, at 5–17 against Emerald/Steel, Three Arrows
>   with STEADY AIM killed Vixey and The Queen, a second Merida returned the Arrows, and wide quests (two Meridas at 2
>   each, Darkwings, Cinderella) won 20–19.
> - **What beat it:**
>   - **Resist:** Flash – Efficient Clerk (2, 3/2/2, Resist 1) takes nothing from Windstorm's 1 and less from every
>     ping; it quested for 8 to 10 in two lost game 1s.
>   - **Ward plus recursion:** Circle of Life replayed Milo Thatch – Getting His Hands Dirty (7, Ward, bounces a
>     character on play), which bounced Merida; conceded at 3–0 (01a15f9d turn 14). Only Windstorm reaches a Ward
>     character.
>   - **Fast wide quests:** Princess Aggro's +5 and +6 turns came before the sweep (01a16020, lost 14–21); a song-and-
>     Evasive Amber/Emerald list quested +7 and +8 (01a15fdb).
> - **Coaching points:**
>   - Merida before any damage action; with their board at 2–3 willpower, hold Windstorm for her.
>   - Keep a Darkwing in play for Terror's 3 and Launchpad's free draw. Quest Marie after removal for the ink drop.
>   - Move questers to Khan Industries; plan Tiana for the turn a Khan is in hand. Whether to ink a Khan is too
>     situational for a rule (user, 2026-11-02): judge it from the hand.
>   - Name the answer to Resist and Ward early (Thunderbolt's 4, challenges, Finest): the pings don't do it.
>   - **Mulligan from the hand you have, not to a fixed plan** (user, 2026-11-02). The play pattern varies widely with
>     the opening seven, and no one line suits a given matchup: see what the hand already does, keep what bridges
>     turn 1 to the late game, and send back the rest, avoiding a full mulligan where possible. The deep mulligans
>     (3 to 7 cards) in these games came partly from the player's first games on the deck, so they aren't a guide.
>   - **Judge the plan from the hand, then the matchup:** a coached line should say how this hand gets from its early
>     turns to Merida, the sweep and the 3-lore finishers, rather than follow a stock sequence.
