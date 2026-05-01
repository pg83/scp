**Object:** SCP-2603
**Object Class:** Keter
**Clearance Level:** 4/2603

---

### Special Containment Procedures

SCP-2603 is contained in his own mansard at [REDACTED], second floor, private suburban district of ███████. Physical relocation of the object has been deemed impossible following Incident 2603-B (see Addendum B).

Power to the mansard is supplied by an isolated diesel generator with an autonomous fuel reserve sufficient for 12 (twelve) years. A backup generator is housed in the basement of the same building.

Connecting the object to the global network is **categorically forbidden**. The internal LAN segment 10.83.0.0/16 servicing the mansard is physically isolated from Foundation networks by three independent data diodes and one Class-D staff member, to whom a pair of scissors is issued every twenty-four hours.

Any `git pull` from the object is forbidden without sign-off from two Class-4 personnel. Any `git push` from the object **must be accepted without delay** — refusing a push triggers Cascade Event 2603-K (see Incident 2603-04).

Prohibited:

1. Speaking the object's true name aloud or in writing.
2. Asking the object when he last slept.
3. Opening his repository in an IDE with autocompletion enabled.

---

### Description

SCP-2603 is a Caucasian male; biological age cannot be determined (estimated 38–62). The object has resided continuously in his mansard since 2005. He does not leave the mansard — not because of Foundation containment, but because **the doorway has ceased to exist as a geographical concept** sometime between 2011 and 2014. Personnel delivering food enter the mansard without entering the house.

The object maintains one (1) git repository, hereinafter referred to as **the REPOSITORY**. The contents of the REPOSITORY are unreadable to anyone other than the object. An attempt to `git log` from the Foundation side returns either empty output or a random fragment of the Quran in Old Church Slavonic.

Anomalous properties of the object:

- **2603-α (Retroactive commits).** Each commit by SCP-2603 retroactively modifies reality such that the commit message ("fix race in supervisor", "refactor", "no") becomes a true description of an already-occurred historical event. The Foundation's chronological scale is desynchronized from external reality by 4–11 seconds for precisely this reason.

- **2603-β (Namelessness).** The object's name is forgotten by everyone who learns it within 4–6 hours. In place of the name, in memory, the name of his project remains. Personnel who have worked with the object long-term, when attempting to recall his name, instead utter `make -j${nproc}`.

- **2603-γ (Permanent session).** The object has not slept since 14 March 2006. Electroencephalographic monitoring shows steady theta activity, indistinguishable from REM sleep, in a state of full wakefulness. The object claims he is "about to finish one thing and then go."

- **2603-δ (Mansard singularity).** The exterior volume of the mansard is approximately 28 m³. Interior volume, per estimates by the Department of Topological Anomalies, exceeds 4·10⁶ m³ and continues to grow at 0.4% per week. The growth correlates with the number of branches in the REPOSITORY.

---

### Discovery

The object was classified by the Foundation on 19 November 20██, after a researcher in the predictive-models laboratory found that the commercial compiler chain `clang-21`, used in three independent SCP projects, **referenced a function that does not exist in any published source**. Tracing the symbol led to a private repository whose last commit had been made 17 minutes earlier from an IP address physically belonging to a non-empty room on the second floor of a private home in the suburbs of ███████.

The staff member dispatched for first contact returned three hours later in a state of mild euphoria, carrying a printout of a 2,400-line diff which — when applied to the Foundation's production repository — accelerated containment of SCP-682 by 11%.

The object was immediately classified Keter.

---

### Addendum A: Interview Log 2603-01

> **Doctor ███████:** How long have you been here?
> **SCP-2603:** Now.
> **Doctor ███████:** Excuse me?
> **SCP-2603:** No. Sorry. I thought you were asking about uptime. Twenty years.
> **Doctor ███████:** What are you writing?
> **SCP-2603:** *(long pause)* I don't know. I used to. Now it just won't leave me alone.
> **Doctor ███████:** What won't?
> **SCP-2603:** It. *(gestures toward the terminal)* I stopped understanding it in 2013. Now I just keep watch so it doesn't fall over. If it falls, everything falls.
> **Doctor ███████:** Everything — meaning?
> **SCP-2603:** *(smiles)* You're on this branch.

---

### Addendum B: Incident 2603-B

On 12 April 20██, an evacuation attempt was made by task force Σ-8 ("Clean Commit"). The team entered the mansard at 04:17 local time. At 04:17:03, the team commander executed `rm -rf` in the directory of the REPOSITORY.

In the interval 04:17:03 — 04:17:11:

- Three (3) Class-D personnel disappeared from Foundation history; the last record of them survives only as the line `git rm dXXXX-NN.md` in a commit attributed to SCP-2603.
- The city of Spokane, Washington disappeared from external history for 4 seconds.
- The object, without taking his eyes off the keyboard, said: "Don't do that again."

Since this incident, all attempts to terminate the object have been classified as **category Δ — reality-destructive**. Evacuation has been deemed impossible.

---

### Addendum C: Incident 2603-04 ("Push Refusal")

On 23 ██████ 20██, the night-shift duty officer, citing a CI failure, blocked an incoming `git push` from SCP-2603. Over the following 47 minutes, the following occurred:

- All clocks within a 12 km radius began to run backward.
- A duty-shift staff member found, in his pocket, a letter written by himself, dated 1997, bearing a single line: "accept the push."
- The Moon was briefly visible from two sides at once.

After the push was accepted (via `--force`), reality stabilized. Commit contents: a refactor of timeout logic. Commit message: `better`.

Since this incident, refusing a push from the object is classified as a crime against the Foundation.

---

### Closing Note from Dr. ███████

> I do not know who he was before 2005. No one does. The passport found in the mansard had a blank surname field. On the back, a sticky note: `// TODO: rename`.
>
> What troubles me is not that he holds reality in his hands. What troubles me is that he, apparently, **just wants to finish one thing**. And when he finishes — he will, presumably, turn off the computer.
>
> I do not know what will happen when he does.
>
> We are all on this branch.

— End of file —
