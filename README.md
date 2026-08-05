# The Tony Protocol

### Orchestrate your agents like a mob boss.

Here's the problem. Give an AI a big job and it hires a crew of sub-agents — then ruins everything by being polite. Everyone gets hired. Nobody gets fired. Every answer makes the final cut, and disagreements get smoothed into "both approaches have merit." You paid for a decision and got minestrone.

This skill makes the orchestrator run the job like a boss instead. Four questions before anyone gets hired — most jobs fail them and get ruled on the spot, in the hallway, for free. When a crew does go out: each agent gets one job and only the information that job needs. Every claim comes with a receipt — a file, a test result, a source — or it goes in the bin. One guy's entire purpose is attacking the plan before it starts. Another attacks the answer before you see it. Dead ends get killed early, disagreements get ruled on instead of averaged, and the books remember everyone's record — including the boss's, because the boss is usually the problem.

> "More is lost by indecision than wrong decision."
> — Tony Soprano, S4E13 "Whitecaps"

House rule: agents are cheap, your attention isn't. The machinery only comes out when a decision is big enough to hurt.

```
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@                       @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@          @@@@@ @           @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@      @@@@@@@@@@@@@@@@          @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@      @@@@@@@@@@@@@@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@    @@@@@@@@@@@@@@@@@@@@@@@@@        @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@@@@@@@@@@@@@@@@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@@@@@@@@@@@@@@@@@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@           @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@           @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@           @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@@@@@@@          @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@@@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@                @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@                    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@    @@ @            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@    @@@@             @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@    @@@@@@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@        @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@     @@@         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@         @         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@                   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@                   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@ @@@@@@                     @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@@@@@@              @@@@@@@@@@@@@ @                      @@@@@@@@@@@@@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@@@@@@@@                    @@@@@@@@@@@@@                                  @@@@@@@@@@@@@@@@@@   
   @@@@@@@@@@ @                         @@@@@@@@@@@@@@@@@                                   @@@@@@@@@@@@@   
   @@@@@@@                               @@@ @@@@@@@@@@                                           @@@@@@@   
   @@@@                                   @@@@@@@@                                                 @@@@@@   
   @@                                      @@@@@                                                     @@@@   
   @                                                                                                  @@@   
   @                                                                                                    @   
```

Why the mob thing? Because it's a compression trick, not a costume. "Boss running a tight crew" tells the model everything in five words: small team, nobody sees the whole map, prove it or bin it, decide and move on. The parts of the metaphor that would make bad engineering — loyalty beating evidence, shooting the messenger — are named inside the skill and switched off.

## Install

Copy `SKILL.md` (and `state/`) into `~/.claude/skills/tony-protocol/`, then invoke by name: *"tony, run the family on this"* — or *"hallway ruling on X"* for the cheap version.

## What's in the box

- `SKILL.md` — the whole protocol. One file, short enough to actually read.
- `state/bodies.md` — sacked roles, written up as obituaries. Reads as a joke, works as documentation.
- `state/bad-carves.md` — every time the boss split a job wrong, so he doesn't do it twice.
- `state/quotes.md` — eight lines from the show with episode receipts, because this repo doesn't do unverified quotes. (One turned out to be a popular misquote. It's in the commit history. We don't talk about it.)

Bad news is fine. Bad paperwork is a problem for everybody.
