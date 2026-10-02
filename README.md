# Lifetime Age Calculator in Days (C++) 🎂⚡

An algorithmic C++ application that computes a user's exact age in total days by interfacing directly with local operating system time utilities.

---

## 🌟 Highlights
- **Hardware/OS Clock Sync:** Automatically fetches real-time calendar dates using `std::time` and `localtime` via `<ctime>`.
- **Accurate Leap Year Handling:** Adjusts day counts dynamically across Gregorian leap boundaries ($Year \pmod{400} = 0$ or $Year \pmod 4 = 0 \land Year \pmod{100} \neq 0$).
- **Iterative Progression Simulation:** Advances day-by-day from birthdate to the current calendar timestamp, ensuring edge cases (month rollovers, year rollovers) are handled seamlessly.

---

## 💻 Sample Terminal Output
```text
Please Enter Your Date of Birth:

Please enter a Day? 3
Please enter a Month? 10
Please enter a Year? 2003

Your Age is : 8399 Day(s).
