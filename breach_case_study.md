> ⚠️ **SYNTHETIC TRAINING MATERIAL.** Invented scenario. No real person, department, incident or decision is described. Created for a training exercise only.

---

# Case Study: "It was just a summary"
## A data incident, reconstructed

**Read the timeline. There is no hacker and no villain. There are eight ordinary decisions, each of which felt reasonable at the time.**

---

## The people

| | |
|---|---|
| **Noura** | Licensing officer, eight months in post, first government role |
| **Hassan** | Her manager, Head of Service Improvement |
| **Omar** | A colleague on the same team |
| **Delta Advisory** | An external consultancy supporting a service redesign |

---

## The timeline

**14 March**: Noura requests an enterprise AI licence through the standard IT form. The request enters the approvals queue.

**Late April**: She follows up. She is told it is "with procurement."

**8 July, 09:15**: Hassan asks Noura to prepare a summary of Q2 complaint themes for a committee on Thursday. There are 340 complaint records, mostly free-text. He says end of week is fine.

**8 July, 16:40**: Hassan comes back. The committee has moved to tomorrow morning. He needs it before she leaves today.

**8 July, 16:52**: Noura exports the complaint records to CSV. The export is the standard one. It includes complainant names, phone numbers, the free-text complaint, and, for the 60-odd complaints submitted through the older intake form, **Emirates ID numbers**. She does not remove any columns. She is not certain which ones matter, and she has twenty minutes.

**8 July, 17:05**: Her work laptop is locked down and she cannot install anything. She opens **her personal AI account on her own laptop** and pastes the file in, asking for the top themes with examples.

**8 July, 17:28**: The output is genuinely good. Six clear themes, well evidenced, better than she would have produced by hand at that hour.

**8 July, 17:35**: So Hassan sees it before the morning, she posts it into the **team WhatsApp group**.

**9 July**: Hassan presents the summary to the committee. It is well received. Nobody asks how it was produced.

**14 July**: Omar is helping Delta Advisory scope the service redesign. He remembers the summary, and forwards it from WhatsApp to his contact there. *"This is a good summary of the themes, might save you some time."*

**2 August**: A Delta Advisory draft report, shared with a third party, contains a near-verbatim extract from the summary. It includes a complaint description detailed enough that a reader identifies the specific business that made it.

**5 August**: The business calls the department to ask how their complaint reached a consultancy.

---

## What you are being asked

Work in your table. Forty minutes.

**1. List every failure point in this chain.** Aim for at least eight. Be specific about *what* failed and *when*.

**2. Who is accountable, and at how many levels?** Do not stop at one name.

**3. Which single control would have prevented this earliest and most cheaply?**

> ⚠️ **You may not answer question 3 with "the officer should have known better."** That is not a control. It is a wish.

**4. What would you change on Monday?** Three things, each with a named owner.

---

## Before you start

Two things worth holding in mind:

- **Every individual decision in this chain was defensible.** Noura had a deadline and no tool. Hassan had a committee. Omar was being helpful. Delta were doing what they were engaged to do. Nobody set out to do anything wrong.
- **The question is not who to blame. It is where the system should have caught it**: and how many chances it had.
