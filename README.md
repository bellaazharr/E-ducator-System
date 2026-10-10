# 🎓 E-ducator: Student Management System

**Flutter + Supabase web app for TVET MARA, Institut Kemahiran MARA (IKM) Johor Bahru.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Status](https://img.shields.io/badge/status-live-00B894?style=flat-square)

A team project built for a real client. It replaces manual student records and attendance tracking at IKM Johor Bahru with one web app that lecturers and admins can use from any browser.

**Live app:**[ [Netlify Link](https://e-ducator.netlify.app)

## What it does
- **User registration** for students and staff, with role-based access
- **Timetable upload**, so classes and schedules are set up from one place
- **Attendance tracking** per class and date
- **Class management**, including adding a new class (*Tambah Kelas Baru*)

## Stack
| Layer | Tool |
|---|---|
| Frontend | Flutter (web) |
| Backend & auth | Supabase (PostgreSQL, triggers, auth) |
| Hosting | Netlify, with `netlify.toml` for single-page app routing |

## My contributions
- Built the **User Registration** and **Timetable Upload** modules
- Fixed bugs in role-based tab visibility, attendance date calculation and dropdowns
- Fixed Supabase triggers that the attendance flow depends on
- Added the *Tambah Kelas Baru* (add new class) dialog
- Set up Netlify deployment, including SPA routing so page refreshes don't break

---
<sub>Forked from the team repo <a href="https://github.com/ikaazhar/e-ducator-AD-Project">ikaazhar/e-ducator-AD-Project</a> · Application Development, UTM</sub>
