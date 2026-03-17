# Syncing Grades from Canvas (GradeSync)

If you grade assignments in Canvas, GradeSync lets you push those grades to PowerTeacher Pro so they appear on report cards and the parent portal. This guide covers setup, syncing, and troubleshooting.

**Time to complete:** ~10 min

---

## Before you begin

!!! warning "Prerequisites"
    - Your Canvas course must be connected to PowerSchool (typically set up by your district)
    - Your Canvas assignment groups must match your PowerTeacher Pro categories
    - You need to have opened PowerTeacher Pro at least once for each course to "enable" the categories

---

## Step 1: Match your categories

Your Canvas assignment groups need to align with your PowerTeacher Pro categories.

1. In **Canvas**, go to your course → **Assignments** page.
2. Click the **three dots** (vertical ellipse) next to the blue "+ Assignment" button.
3. Select **"Sync SIS Categories"**.
4. For each Canvas assignment group, use the dropdown to select the **matching PowerTeacher Pro category**.
5. Save your selections.

!!! tip "Keep names consistent"
    If your Canvas group is called "Classwork" and your PowerTeacher category is called "Classwork," matching is intuitive. If they have different names, you can still map them — just make sure each Canvas group points to the right PowerTeacher category.

---

## Step 2: Enable assignments for sync

Each individual assignment must be marked for syncing:

1. Open an assignment in Canvas.
2. In the assignment settings, look for the **"Sync to SIS"** or **"Post to SIS"** checkbox.
3. Check it.
4. Make sure the assignment has a **due date** — assignments without due dates won't sync.

!!! warning "Assignment name length"
    Assignment names must be **50 characters or fewer** to sync successfully. Longer names will cause sync errors.

---

## Step 3: Sync grades

=== "Manual sync"
    1. In Canvas, go to **Grades** (Gradebook).
    2. Click the **Actions** menu (or three dots).
    3. Select **"Sync to SIS"**.
    4. Review the assignments and grades being synced.
    5. Click **Sync**.

=== "Automatic nightly sync"
    1. In your Canvas course, go to **Settings** → **Navigation**.
    2. Enable **"Grade Sync"** (drag it to the active area).
    3. Click on **Grade Sync** in your course navigation.
    4. Go to the **Settings** tab.
    5. Toggle **"Nightly Sync"** on.
    6. Grades will sync automatically every evening.

---

## Troubleshooting common sync issues

| Problem | Solution |
|---------|----------|
| Assignment didn't sync | Check that the "Sync to SIS" box is checked and a due date is set |
| Categories don't match | Go to Assignments → three dots → "Sync SIS Categories" and re-map |
| Assignment name too long | Shorten the name to 50 characters or fewer |
| No score entered | Enter at least one student's score — empty assignments may not sync |
| Grades synced incorrectly | Remember: Canvas sync **overwrites** PowerTeacher grades. Make corrections in Canvas, not PowerTeacher. |
| Sync button not visible | Enable "Grade Sync" in your course Settings → Navigation |

!!! warning "Canvas is the source of truth"
    Once you set up GradeSync, **make grade corrections in Canvas**, not PowerTeacher Pro. The next sync will overwrite any changes you make directly in PowerTeacher.

---

## What's next?

- **[Verifying grades and end-of-term tasks](end-of-term.md)** — Check everything before report cards
- **[Setting up categories and calculations](categories-calculations.md)** — Make sure your PowerTeacher categories are correct
