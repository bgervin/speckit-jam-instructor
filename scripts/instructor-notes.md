# Instructor Notes — SpecKit Hands-on Lab

## Opening (5 min)

### Key Message
> "English is now the programming language. But without source control for your requirements, you're just vibe coding. SpecKit makes your specs first-class citizens in the repo."

### Flow
1. **Welcome** — "Today we're going to build features using SpecKit and GitHub Copilot CLI"
2. **Show the app** — Open localhost:3000, create a session, cast a vote
3. **Reveal the gap** — "Notice there's no way to see the results? That's what you'll build."
4. **Share the HOL page link** — Post in Teams chat
5. **Quick repo tour** — Show `constitution.md`, one spec, the source code structure

### Talking Points
- "Every feature you see was built spec-first — the spec came before the code"
- "The specs live in the repo, right next to the code they describe"
- "You're going to experience this workflow yourself in the next 40 minutes"

---

## Lab 1 Guided Walkthrough (20 min)

### Pacing
- Walk through Steps 1-3 together (specify, review, clarify) — ~10 min
- Let them run Steps 4-7 (plan, implement, test) — ~10 min
- Float and help people who get stuck

### Common Issues
- **"My output looks different"** — That's normal! AI generates different results each time. The spec captures the intent, not the exact output.
- **"Tests are failing"** — Have them re-read the spec and re-run implement. Sometimes a second pass fixes things.
- **"I can't access Copilot CLI"** — They may need to run `gh auth login` again or check their Copilot subscription.

### Key Moment: After spec is generated
Pause the room and say:
> "Look at what just happened. You described a feature in English, and SpecKit turned it into a structured spec in your repo. This spec is now source-controlled. You can PR it. You can diff it. It's not lost in a chat window."

---

## Stretch Labs (15 min)

- Let fast movers pick Labs 2, 3, or 4
- No need to walk through these — the HOL page has all the prompts
- Float and help as needed
- If someone finishes multiple labs, celebrate it!

---

## Wrap-up (5 min)

### The Comparison (show the table from the HOL page)
- "Vibe coding" = requirements in chat, not reproducible, not reviewable
- "Spec-driven" = requirements in repo, reproducible, PR-reviewable, auditable

### Closing Line
> "You just built features with specs, plans, tests, and code — all source-controlled. This is how PMs and engineers collaborate in the AI era. The spec is the new unit of work."

### Q&A
- Expect: "Why not just prompt the agent directly?"
  - Answer: "You can! But those prompts are ephemeral. SpecKit makes them durable. When your teammate joins the project next month, the spec is still there."
- Expect: "Does this work with my existing codebase?"
  - Answer: "Yes — SpecKit reads your constitution and existing code to understand context."
