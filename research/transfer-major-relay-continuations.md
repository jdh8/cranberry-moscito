# Continuations after the transfer-major relay

Research date: 2026-10-28. This is a comparison of published methods, not an adopted system change.

## The requirement

Here `1R–1M` means `1♦–1♥` or `1♥–1♠`. The initial relay must accommodate a constructive, below-invitational notrump hand. It therefore cannot automatically establish game interest or force game when opener is maximum.

This is already explicit in [MOSCITO 2007, §§2.1.2–3](https://relaysystems.wordpress.com/wp-content/uploads/2021/10/moscito-2007.pdf): the first step includes an ordinary notrump response, game tries, and stronger hands.

Cranberry's current [openings](../src/Openings.md) are 11–15, with 13–15 balanced hands opening 1NT. Its [heart](../src/1D.md) and [spade](../src/1H.md) continuations explicitly retain balanced minima. A borrowed structure must account for these hands even when its original system excludes them.

## Natural rebids, with a separate strong relay

In a first-person explanation of modern MOSCITO, **Free** preserves playable rebids and separates responder's escape from the game-forcing ask:

| After 1♦–1♥ | Opener shows | Responder's continuation |
|---|---|---|
| 1♠ | Both majors | 1NT below-invitational; 2♣ GF ask |
| 1NT | 4♥ and longer minor | 2♣ pass/correct; 2♦ GF ask |
| 2♣ | 5+♥, 4+♣ | 2♦ GF ask; 2♥ preference |
| 2♦ | 5+♥, 4+♦ | 2♥ preference; 2♠ GF ask |
| 2♥ | 6+♥ | 2♠ ask |

He excludes balanced opening hands and accepts less efficient shape relays. **Adaptation:** retain a route for balanced minima and distinguish his GF asks from Cranberry's INV+ 2♦. [Free, BBO, 4 June 2013, post 3](https://www.bridgebase.com/forums/topic/60528-moscito-sequences/)

## Mygga: show the canapé minor directly

**Erik Sjöstrand and Håkan Johansson's Mygga** includes weak hands in 1M. Openings permit 5332 but exclude 4333/4432.

| Opener rebids | After 1♦–1♥ | After 1♥–1♠ |
|---|---|---|
| 1♠ | 4♠ | — |
| 1NT | Residual 5+♥ or 1444 | Residual 5+♠, without 4♥, or 4144 |
| 2♣/♦ | Exactly 4♥, 5+ in minor | Exactly 4♠, 5+ in minor |
| 2♥ | 5+♥, five-card minor | 5+♠, 4♥ |
| 2♠ | 6♥, 5♠ | 5+♠, five-card minor |

After 1NT, 2♣ is GF; 2M is weak preference. However, after 1♦–1♥–1♠, **1NT is GF**; after 1♦–1♥–2♦, **2♥ is GF**. Balanced invitations use minor transfers.

**Adaptation:** place balanced four-card-major minima and decide which 1NT stops to preserve. [Mygga, 19 July 2013, §§2.3.1, 6.3.2–3, printed pp.19–21, 60–61](http://snortingmaradonas.se/erik/relayclub.pdf)

## MOSCITO 2005: asymmetric treatment of the minors

Marston's 2005 introduction uses an **INV+ first relay**. Its 2♣ rebid shows clubs and may be canapé (four-card major, five clubs); 1NT groups balanced hands, three-suiters short in the other major, and four-card-major/five-diamond hands. Following 1NT, 2♣ asks: 2♦ shows four-card major/five diamonds, 2♥ balanced with four-card major, 2♠ 5332, and 2NT three-suited short in the other major. Higher responses handle additional three-suiters after the spade opening.

**Assessment:** useful inspiration if the disliked feature is hiding both minors in 1NT. It exposes clubs early, but importing it would require a new weak escape and invitation scheme because the published first relay already promises game interest. [Paul Marston, MOSCITO 2005 introduction, §§3–4, pp.4–5](https://bridgewithdan.com/wp-content/uploads/2019/07/moscito2005intro.pdf)

## J-Moscito: efficient artificial shape relays

Jari Böling's J-Moscito uses an **INV+ first relay**. After 1♦–1♥, opener's 1♠/1NT/2♣ show clubs/both majors/diamonds; 2♦ shows a nonminimum heart one-suiter and 2♥ a minimum one-suiter. After 1♥–1♠, 1NT/2♣/2♦ show clubs/diamonds/hearts; 2♥ and 2♠ split nonminimum/minimum spade one-suiters.

**Assessment:** the artificial 1NT rebid and other shape steps cannot be transplanted unchanged opposite a constructive notrump response. These are candidates for modules entered only after responder establishes the required strength. [J-Moscito, §§5.4, 5.4.2, pp.15, 18–19](https://users.abo.fi/jboling/bridge/j_moscito.pdf)

Richard Willey's alternative in Appendix B takes **length and strength first**: after 1♦–1♥, 1♠ shows minimum unbalanced 5+♥; 1NT covers balanced hands or exactly four hearts; 2♣+ shows maximum unbalanced 5+♥. For example, direct 2♣ shows hearts/diamonds, 2♦ a heart one-suiter, and 2♥ hearts/four clubs. The same shape modules follow minimum 1♠ and a further 1NT relay. **Assessment:** an interesting allocation, especially for invitations with three trumps, but these artificial replies do not supply the weak responder's passable contracts. It belongs with the INV+ designs, not Mygga's weak-or-strong response. [Richard Willey, MOSCITO notes, Appendix B, mirrored document](https://pdfcoffee.com/moscito-notes-pdf-free.html)

## Honeymoon: natural description instead of memorized pattern steps

Peter Buchen's Honeymoon emphasizes the cheapest consistent natural suit: a newly shown suit promises four cards, repetition five; later suit bids can describe three-card fragments. Notrump as the first shape response to a limited one-suit opening shows 4333. Its first relay is invitational or better (12 points, or 11 with fit); the second is GF.

**Assessment:** useful as a different philosophy for the strong continuation, but its published strength assumptions and balanced first response are not the user's generic constructive relay. [Peter Buchen, Honeymoon, March 1991, pp.1–2, 5](https://users.abo.fi/jboling/bridge/honeymoon.pdf)

Ian Casselton's **Transfer Honeymoon Relays** transfers toward length and away from shortage. Before a game force, the first step handles nonmaximum hands; other steps show maxima and establish GF. **Assessment:** that maximum-implies-GF rule fails opposite a below-invitational constructive response. The mechanism is a candidate after a genuine GF ask, not an unchanged replacement for opener's first rebid. [Ian Casselton, 2017](https://bridgewinners.com/article/view/transfer-honeymoon-relays/?cj=510960)

## What a replacement still needs to specify

These are design requirements inferred from Cranberry's present opening and response ranges:

1. An explicit destination for every balanced minimum with four or five major cards.
2. Explicit weak exits, identifying which branches preserve 1NT, two of opener's major, or a suitable minor.
3. Invitations distinct from both weak preference and GF asking.
4. Treatment of 1444/4144 and both-major hands without assuming every 1NT rebid can safely be passed.

The most distinct documented alternative accommodating the weak first relay is Mygga. The least disruptive approach is to keep natural opener rebids and redesign only the strong continuations. Older INV+ relay tables provide useful components, but do not solve the constructive-notrump case by themselves.
