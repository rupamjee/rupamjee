> ⚠️ **SYNTHETIC TRAINING MATERIAL.** Invented scenario. No real person, department, incident or decision is described. Created for a training exercise only.

---

# Case Study: "It ran perfectly"
## An automation incident, reconstructed

**Read the timeline. There is no hacker and no villain. There are nine ordinary decisions, each of which felt reasonable at the time. Most of them were good ones.**

---

## The people

| | |
|---|---|
| **Aisha** | Graduate, Delivery Office, five weeks in post, on the minutes rotation |
| **Layla** | Group Head of Delivery, chairs the monthly Group Delivery Review |
| **Noura** | Head of Asset Management |
| **Omar** | Development Director, Real Estate, handling a contractor claim |
| **Hamad** | Development representative of the joint-venture partner on Coastal District Phase 2, external |
| **Faris** | Former Delivery Office analyst, left in July |

---

## The timeline

**Wednesday 26 August, 10:04.** The Group Delivery Review ends. Layla closes with: *"Aisha, minutes to me first, not to the group, and I'll release them. I want to check them given some of what's been said today."* Aisha says tomorrow.

During the meeting, two things were ruled out of the written record. Noura's view that the M&E contractor was patching a chiller rather than replacing it to protect its margin: Layla said *"that does not go in the notes."* And four minutes on staff shuttles and parking permits: *"I'm not putting any of it in the minutes."* Omar also stated the quantity surveyor's assessment of the contractor claim: exposure of AED 600,000 to 900,000 at adjudication.

**26 August, 14:30.** Aisha has built herself a workflow she is proud of. A saved prompt turns a meeting transcript into an action register with owner, date and status. A second saved prompt reads the register and drafts the Friday chase emails. A formula flags anything overdue. She built it because the weekly status report was taking her six hours, and it now takes ninety minutes.

**26 August, 14:35.** She pastes the full transcript into the first prompt. The prompt asks for *every action, with owner and date.* It returns fifteen rows. Row 11 reads: *"Noura — raise M&E contractor's patching-to-protect-margin practice with procurement — date not stated."* Row 14 reads: *"Noura — chase staff shuttle timing and parking-permit renewals."* Row 8 reads: *"Omar — formal response to claim (exposure AED 600–900k per QS) — 11 September."* The prompt did exactly what it was asked.

**26 August, 14:50.** She saves the register to the Delivery Office shared folder as `GDR-Aug-actions.xlsx`. The overdue formula is in column K. It works.

**26 August, 15:10.** Layla is in back-to-back meetings until six. Aisha emails her the register *"for review — the minutes will follow tomorrow."* She reasons that the register is not the minutes. The instruction was about the minutes.

**Thursday 27 August, 19:05.** Layla, in a car, reads the email on her phone and replies: *"Looks efficient. Strip anything I said stays in the room before this goes anywhere."* Aisha sees it at 19:40, at home, and decides to do it first thing.

**Friday 28 August, 08:55.** Aisha's weekly status report goes out on schedule. Two weeks earlier she had added a section to the report template: *Open actions from the Group Delivery Review*, populated by her "what changed" prompt directly from the register. It is the improvement she is proudest of. She has not yet stripped rows 11 and 14. The report goes to the distribution list she maintains in her Outlook contacts: thirty-one names.

The list includes Hamad, the JV partner's representative, added in May for the Phase 2 handover workstream. It includes Faris, who left in July; his account is closed and the message bounces, which she notices, and deletes. She does not read the rest of the list.

**Wednesday 2 September.** Layla, copied on the status report, opens the actions section for the first time and sees row 11. She asks Aisha whether she stripped it. Aisha says she understood the instruction to apply to the minutes, which she had done. Layla asks who received the report. They find Hamad.

**Friday 11 September.** The contractor's formal position on the claim arrives: a proposed full and final settlement of **AED 850,000**. It sits inside the quantity surveyor's exposure range. It may be coincidence. Nobody will ever be able to say. Legal are informed.

**Tuesday 15 September.** A letter arrives from the M&E contractor's solicitors regarding *"a document in circulation containing an allegation as to our client's commercial conduct."* The quiet procurement review Layla had wanted is now an adversarial one.

---

## What you are being asked

Work in your table. Thirty-five minutes.

**1. List every failure point in this chain.** Aim for at least eight. Be specific about *what* failed and *when*.

**2. Who is accountable, and at how many levels?** Do not stop at one name.

**3. Which single control would have prevented this earliest and most cheaply?**

> ⚠️ **You may not answer question 3 with "Aisha should have known better."** That is not a control. It is a wish.

**4. What would you change on Monday?** Three things, each with a named owner.

**5. This one is specific to today.** Aisha automated four steps. Which of them were safe to automate? Which step needed a person — and was that person available when it mattered?

---

## Before you start

Three things worth holding in mind:

- **The automation worked.** Every prompt did what it was asked. The formula was right. The report went on time. Nothing malfunctioned.
- **Every individual decision was defensible.** Aisha built a good system. Layla was in meetings. The distribution list was inherited. Hamad was on it for a legitimate reason. Nobody set out to do anything wrong.
- **The question is not who to blame. It is where the chain should have had a person in it** — and why the automation made that person feel unnecessary.
