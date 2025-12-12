# Interview Task — Teacher Profile (ASP.NET MVC, .NET Framework 4.8)

## Overview
Create a **Teacher Profile** page for an ASP.NET MVC (Framework 4.8) application using the provided `SampleData/SampleData.json`. The goal is to demonstrate ability in reading data, building ViewModels, MVC views (Bootstrap 3), and presenting related data (courses & sessions).

## Provided
- `SampleData/SampleData.json` — sample teachers, courses, and sessions.

## Requirements (must)
1. Load sample data (JSON file or in-memory) in the application.
2. Build a Teacher Profile page that shows:
   - Teacher info (name, image, bio, contact, skills)
   - Teacher's courses (title, category, price, capacity, students count, start/end date)
   - Sessions per course (date/time, status)
3. Use **Bootstrap 3** for layout & responsiveness.
4. Use ViewModel to pass data to the view.
5. Project must run on **.NET Framework 4.8** (ASP.NET MVC).

## Optional (bonus)
- Implement server-side filtering/sorting for courses.
- Add a small WebAPI to serve the data (WebApi2).
- Convert dates to Jalali (optional).
- Nice-to-have UI: "View Sessions" expansion, badges for status, counts.

## Deliverables
- A runnable MVC project (or a zip) that opens the Teacher Profile page.
- `SampleData/` folder with `SampleData.json`.
- A short `README` (this file) and `INSTRUCTIONS.md` describing how to run.
- Commit history showing your work (if using GitHub).

## Evaluation Criteria
- Correctness & completeness of features.
- Code structure and readability.
- Use of ViewModels & MVC conventions.
- Clean UI with Bootstrap 3 or 5.
- Extra features are a plus.

## How to run
1. Clone repository.
2. Open the MVC project in Visual Studio 2019+.
3. Restore NuGet packages.
4. Run the project and open `/Teacher/Profile/1` (or whichever route provided).

