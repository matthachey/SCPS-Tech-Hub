# Setting Up Allow and Block Lists

Web Rules are one of Lightspeed Classroom's most useful features. They let you control exactly which websites students can access during your class. There are two modes: **Allow** (whitelist) and **Block** (blacklist).

**Time to complete:** ~8 minutes

---

## Understanding the two modes

| Mode | What It Does | Best For |
|------|--------------|----------|
| **Allow Mode** | Students can ONLY visit sites on your list — everything else is blocked | Testing, focused assignments, research with specific sources |
| **Block Mode** | Students can visit any district-approved site EXCEPT the ones on your list | General class time when you just want to block known distractors |

!!! tip "Which should I use?"
    **Allow Mode** is more restrictive and works best when students should only be on one or two specific sites. **Block Mode** is more permissive and works well for general class time. When in doubt, start with Block Mode and switch to Allow Mode for focused activities.

---

## Setting up an Allow List

1. From your class view, click **"Web Rules"** at the top of the page.
2. Select the **"Allow Mode"** tab.
3. Click **"New Allow List"** (or select an existing one).
4. Give the list a name (e.g., `Research Project Sites` or `Math Practice Only`).
5. **Add website URLs** one per line. Only include the domain — for example:
    - `google.com` (not `https://www.google.com`)
    - `docs.google.com`
    - `khanacademy.org`
6. Press **Enter** after each URL to add it as a separate entry.
7. Click **"Select List"** to activate it.
8. Click **"Apply Lists"**.

!!! warning "Don't forget SSO"
    If your school uses Google Single Sign-On, check the **"Allow Single Sign On (SSO)"** checkbox in the advanced options. Without this, students may not be able to log into Google-based tools even if you've allowed them, because SSO routes through hidden URLs that might not be on your list.

---

## Setting up a Block List

1. From your class view, click **"Web Rules"**.
2. Select the **"Block Mode"** tab.
3. Click **"New Block List"** (or select an existing one).
4. Name the list (e.g., `Common Distractors`).
5. Add URLs of sites you want to block:
    - `youtube.com`
    - `tiktok.com`
    - `coolmathgames.com`
    - `discord.com`
6. Click **"Select List"** to activate it.
7. Click **"Apply Lists"**.

---

## Managing your lists

- You can create up to **20 Allow Lists** and **20 Block Lists**
- Each list can contain up to **100 URLs**
- **Toggle lists on and off** without deleting them — great for switching between activities
- Lists are **per class** — you'll need to set up lists separately for each class (or reuse lists you've already created)

### Checking web rules status at a glance

From your class view, the Web Rules link at the top shows the current status:

| Display | Meaning |
|---------|---------|
| **Web Rules Off** | No allow or block lists are active |
| **Allow Mode** | An allow list is currently active |
| **Block Mode** | A block list is currently active |

---

## Common Allow List setups

Here are some ready-to-use list ideas:

### Testing mode
```
docs.google.com
forms.google.com
```

### Research project
```
docs.google.com
scholar.google.com
britannica.com
worldbookonline.com
```

### Math practice
```
khanacademy.org
deltamath.com
desmos.com
docs.google.com
```

!!! tip "Build a library of lists"
    Create lists for your common activities and just toggle them on/off as needed. You don't have to rebuild them every time.

---

## Turning off web rules

1. Click **"Web Rules"**.
2. Select **"Off"** at the top of the panel.
3. Students return to normal district-filtered browsing.

---

## The "Done" status and web rules

Lightspeed has a feature where students can mark themselves as **"Done"** with an assignment. When a student's status is set to Done:

- Web Rules are **automatically released** for that student
- They can browse freely (within district filter limits) while waiting for others to finish

This is configurable — ask your ITRT if this feature is enabled for your building.

---

## What's next?

- **[Creating student groups with custom rules](student-groups.md)** — Give different groups different access
- **[Locking screens and pausing internet](locking-screens.md)** — For when you need full attention
- **[Pushing links to students](pushing-links.md)** — Pair with Allow Mode for focused activities
