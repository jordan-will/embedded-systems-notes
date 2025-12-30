> This methodology was initially drafted with the assistance of ChatGPT and later adapted.


# Premises for Reviewing Embedded Systems

This document defines **how to review and practice** embedded systems content in a general way, independent of specific technologies such as Linux, RTOS, bare-metal, microcontrollers, or SoCs.

The goal is not to accumulate information, but to **turn reading into technical skill**: the real ability to reason, diagnose problems, and build systems.

---

## 1. Why “just studying” does not stick (especially in systems)

Embedded systems are not a memorization-based field. They require:

- **Clear mental models** (how the system works internally)
- **Cause → effect relationships** (what changes when something is modified)
- **Symptom → diagnosis reasoning** (observed behavior → root cause)

Passive reading does not create these connections.

You may, for example:

- understand a concept today  
- feel confident about it  
- and completely forget it a few weeks later  

This happens because **memory was never activated**.

> In embedded systems, understanding is not remembering.  
> Remembering is not knowing.  
> Knowing means being able to use it under pressure.

---

## 2. Review is not rereading material

### Poor review (passive)

- Rewatching videos  
- Rereading notes  
- Skimming through content  

These actions **trick the brain**, creating a false sense of mastery.

You recognize the content, but **cannot reproduce or apply it**.

---

### Proper review (active)

A review is only valid if it positively answers at least **one** of the following questions:

- Can I explain this without looking?  
- Can I apply this to a real problem?  
- Can I diagnose a failure using this?  

If the answer is **no**, the content is **not fixed yet**.

---

## 3. The method: turning reading into skill

### Reinforcement cycle



Study → Practice → Review → Challenge → Short review

This cycle applies to **any topic**, such as:

- microcontroller architecture  
- interrupts  
- timers  
- boot process  
- drivers  
- RTOS concepts  
- embedded Linux  

---

## 4. Cycle steps (how to execute in practice)

### 1. Study

- Technical reading (book, documentation, article)
- Clear objective: what do I want to understand?

Never study without purpose. Always study **to answer questions**.

---

### 2. Practice

Practice must be **active and intentional**:

- Simulate  
- Implement something small  
- Break it on purpose  
- Change parameters and observe effects  

Examples:

- change task priorities  
- modify clock configuration  
- remove initialization code  
- introduce configuration errors  

---

### 3. Active review

Without consulting material:

- explain the concept out loud  
- write a short summary (5–10 lines)  
- draw the system flow  

If you get stuck, return to the material **only at the point of doubt**.

---

### 4. Challenge

Create or answer questions such as:

- What happens if this fails?  
- How would I debug this symptom?  
- What alternative mechanisms exist?  

Challenge is what **turns knowledge into engineering**.

---

### 5. Short review

After a few days:

- reread only your own summary  
- mentally reconstruct the reasoning  
- explain it again  

10–20 minutes are enough.

---

## 5. Spaced reviews (practical rule)

Use fixed review intervals:

- **24 hours** after study  
- **7 days** later  
- **30 days** later  

Each review must be short and active.

---

## 6. How to know if a topic is truly fixed

You know it is fixed when you:

- can explain it without memorizing  
- can apply it in a different system  
- can diagnose real errors  
- do not panic when facing something new  

If you only recognize the content, **it is not fixed yet**.

---

## 7. Golden rule of embedded systems

> Systems are not learned by watching.  
> Systems are learned by **breaking and fixing**.

This document should be reread whenever starting a new block of the roadmap.

It defines **how to study**, not **what to study**.

