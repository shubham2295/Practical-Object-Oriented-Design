# 📘 POODR Chapter 1 – Object-Oriented Design

## 🧠 TLDR

This chapter lays the foundation for object-oriented design (OOD). It reframes software development as designing objects that collaborate via messages, not just organizing code. The core problem OOD solves is change — designing code that stays flexible and useful even as requirements evolve.

## 💡 Key Concepts

- 🧱 Design is about change, not perfection
- 🔄 OOD = managing dependencies
- 💌 Messages are more important than objects
- 🛠️ Design isn’t about guessing the future — it’s about making change cheap
- ✔️ Good design passes the TRUE test:
  - Transparent
  - Reusable
  - Usable
  - Exemplary

## 🧪 Code Pattern

```typescript
class Gear {
  constructor(private chainring: number, private cog: number) {}

  ratio(): number {
    return this.chainring / this.cog;
  }
}
```

A simple class with clear behavior (ratio) and internal state. A clean starting point to evolve from as requirements shift.

## 🤔 Reflection / Real Talk

I often wait too long before thinking about design. This chapter helped me see that design doesn’t mean you stop coding — it means you’re always designing, even in small moments.

## 🔖 Sticker Wisdom

“The purpose of design is to allow you to do design later.” — Sandi Metz
