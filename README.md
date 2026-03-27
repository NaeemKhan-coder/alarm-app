# Alarm Clock

A browser-based alarm clock built with JavaScript, featuring multiple alarms, custom sounds, repeat logic, and efficient scheduling.

---

## Features

* **Real-time Digital Clock**
  Smooth updates using `requestAnimationFrame`.

* **Multiple Alarms**
  Create and manage unlimited alarms.

* **Custom Labels**
  Add context like *Fajr*, *Study*, or *Workout*.

* **Selectable Sounds**
  Choose from predefined audio files.

* **Live Volume Control**
  Adjust volume even while the alarm is ringing.

* **Repeat System**
  Automatically reschedules alarms after a defined interval.

* **Enable / Disable Toggle**
  Turn alarms on or off without deleting them.

* **Edit & Delete**
  Modify or remove alarms instantly.

* **Persistent Storage**
  Alarms are saved in `localStorage` and restored on reload.

* **Smart Scheduling**
  Only the next upcoming alarm is scheduled for efficiency.

* **Manual Stop Control**
  Stop button appears only during active alarms.

---

## How It Works

Instead of checking every second, the app calculates the **next upcoming alarm** and schedules it using `setTimeout`.

This approach:

* Reduces unnecessary processing
* Improves performance
* Keeps the logic clean and scalable

---

## Tech Stack

* HTML
* CSS
* JavaScript (Vanilla)

---

## Notes

This project focuses on clean logic, efficient scheduling, and practical UI behavior rather than heavy frameworks.
