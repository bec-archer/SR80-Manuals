# ShopTracker User Manual

**App:** ShopTracker (SR80)
**Version:** 1.1 (in development)
**Last Updated:** 2026-04-22
---

## Table of Contents

- [Getting Started](#getting-started)
  - [What is ShopTracker?](#what-is-shoptracker)
  - [Device Setup (First Time Only)](#device-setup-first-time-only)
  - [Admin Access on Non-Admin Devices](#admin-access-on-non-admin-devices)
  - [Sidebar Navigation](#sidebar-navigation)
  - [Display Size Settings](#display-size-settings)
  - [Getting Help In-App](#getting-help-in-app)
- [Front Counter](#front-counter)
  - [Job Board](#job-board)
  - [Searching and Filtering Jobs](#searching-and-filtering-jobs)
  - [Closed Jobs (Job History)](#closed-jobs-job-history)
  - [Creating a New Work Order](#creating-a-new-work-order)
  - [Viewing a Job (Job Detail)](#viewing-a-job-job-detail)
  - [Adding Materials (Hoses, Fittings, Adapters, Seals)](#adding-materials-hoses-fittings-adapters-seals)
  - [Editing a Draft Work Order](#editing-a-draft-work-order)
  - [Editing a Checked-In Item](#editing-a-checked-in-item)
  - [No Warranty Flag](#no-warranty-flag)
  - ["On Fire" Priority Flag (🔥)](#on-fire-priority-flag-)
  - ["Waiting" Flag (⏳)](#waiting-flag-)
  - [Changing the Customer on a Job](#changing-the-customer-on-a-job)
  - [Finalizing a Draft](#finalizing-a-draft)
  - [Customer Check-In](#customer-check-in)
  - [Complete & Pickup](#complete--pickup)
- [Customers](#customers)
  - [Customer List](#customer-list)
  - [Customer Detail](#customer-detail)
  - [Editing a Customer](#editing-a-customer)
  - [Flagging a Customer](#flagging-a-customer)
- [Companies](#companies)
  - [Company List](#company-list)
  - [Company Detail](#company-detail)
  - [How Companies Work](#how-companies-work)
  - [Flagging a Company](#flagging-a-company)
- [Tech Station](#tech-station)
  - [Repair Queue](#repair-queue)
  - [Recently Completed Items](#recently-completed-items)
  - [Searching and Filtering the Queue](#searching-and-filtering-the-queue)
  - [Scanning a QR Tag (Tech Station)](#scanning-a-qr-tag-tech-station)
  - [Adding Photos from the Tech Station](#adding-photos-from-the-tech-station)
  - [Adding Notes from the Tech Station](#adding-notes-from-the-tech-station)
  - [Working on Warranty Items](#working-on-warranty-items)
  - [No Warranty Flag (Tech Station)](#no-warranty-flag-tech-station)
  - [Mark Complete (No Warranty)](#mark-complete-no-warranty)
  - ["Waiting" Flag (⏳) — Tech Station](#waiting-flag--tech-station)
  - [Editing Item Info from the Tech Station](#editing-item-info-from-the-tech-station)
  - [Grabbing an Item](#grabbing-an-item)
  - [Managing Techs on an Item](#managing-techs-on-an-item)
  - [Repair Checklist](#repair-checklist)
  - [Marking Repair as Done](#marking-repair-as-done)
  - [Testing an Item](#testing-an-item)
  - [Oil Sample](#oil-sample)
  - [Repair History](#repair-history)
  - [Entering Cost](#entering-cost)
  - [Totaling an Item](#totaling-an-item)
  - [About the Action Buttons](#about-the-action-buttons)
  - [Auto-Return to Queue](#auto-return-to-queue)
  - [Role Switcher (Debug Only)](#role-switcher-debug-only)
- [Admin](#admin)
  - [Employee Management](#employee-management)
  - [Shop Settings](#shop-settings)
    - [Category Labels](#category-labels)
  - [Manage Lists](#manage-lists)
  - [Device Management](#device-management)
  - [Managing Flags (Admin Only)](#managing-flags-admin-only)
  - [Editing Cost on a Complete Item](#editing-cost-on-a-complete-item)
  - [Reports](#reports)
  - [Resetting a Device](#resetting-a-device)
  - [Training Mode & Local Test Mode](#training-mode--local-test-mode)
  - [Bug Reports (Admin)](#bug-reports-admin)
- [Reporting a Problem](#reporting-a-problem)
  - [The Ladybug Button](#the-ladybug-button)
- [Equipment Tags](#equipment-tags)
  - [Getting Sticker Sheets](#getting-sticker-sheets)
  - [Viewing Batch History](#viewing-batch-history)
  - [Assigning a Tag at Check-In (Front Counter)](#assigning-a-tag-at-check-in-front-counter)
  - [Scanning from the Job Board (Front Counter)](#scanning-from-the-job-board-front-counter)
  - [Scanning from the Work Queue (Tech Station)](#scanning-from-the-work-queue-tech-station)
  - [The QR Icon — What It Means](#the-qr-icon--what-it-means)
  - [Viewing and Reprinting a Tag](#viewing-and-reprinting-a-tag)
  - [Assigning a Tag After Check-In](#assigning-a-tag-after-check-in)
  - [Replacing a Tag](#replacing-a-tag)
  - [Scanning Old / Retired Tags](#scanning-old--retired-tags)
  - [Scanning Tags on Closed or Totaled Items](#scanning-tags-on-closed-or-totaled-items)
  - [When There's No Tag](#when-theres-no-tag)
  - [Flagging Equipment](#flagging-equipment)
- [Reference & Troubleshooting](#reference--troubleshooting)
  - [Troubleshooting](#troubleshooting)
  - [Working Offline](#working-offline)
  - [Multiple Devices](#multiple-devices)

---

## Getting Started

### What is ShopTracker?

ShopTracker is the repair tracking app for Hydraulics SR-80. It runs on iPads in the shop and replaces the paper-and-whiteboard system. Jobs come in at the front counter, get worked on in the back, and ShopTracker keeps everyone on the same page in real time.

There are three types of devices in the shop:

- **Front Counter** — where Maria (or whoever's working the counter) checks equipment in, creates jobs, and handles customer pickup
- **Tech Station** — the iPad in the back shop where techs see their repair queue, log what they've done, and mark items as ready for testing
- **Admin** — Bec, Jamie, or Lee's device with full access to everything: both views, settings, reports, and employee management

### Device Setup (First Time Only)

When you open ShopTracker on a brand new device (or after a reset), you'll go through a one-time setup to tell the app who this device is and what it's for. Once set up, the device remembers its identity even if the app is closed or updated.

#### Step 1: Admin PIN

The very first screen asks for an admin PIN.

**If this is the very first device being set up** (no one has a PIN yet):

1. You'll see a "Welcome to SR80" screen
2. Pick your name from the list of admin employees (Bec, Jamie, or Lee)
3. Create a PIN — this can be 4 to 8 digits, whatever you're comfortable remembering
4. Enter it again to confirm
5. That's your PIN from now on — you'll use it anytime admin access is needed

**If PINs already exist** (someone else set up their PIN first):

1. You'll see a standard "Enter PIN" screen
2. Type your admin PIN and tap **Unlock**

**If you're a new admin and don't have a PIN yet:**

1. On the "Enter PIN" screen, tap **"Don't have a PIN yet?"** at the bottom
2. The app checks if there are any admins who still need a PIN
3. If your name shows up, tap it, then create and confirm your PIN — same as the first-time flow
4. If all admins already have PINs, you'll see a message to ask another admin to reset yours (see Employee Management below)
5. You can tap **"Back to PIN entry"** at any time to return to the normal PIN screen

#### Step 2: Name the Device

After your PIN is accepted, you'll see the device configuration screen.

1. **Device Name** — Give this iPad a name so you can tell devices apart. Something like "Front Counter iPad" or "Back Shop Tech Station" works great.
2. **Device Role** — Pick what this device will be used for:
   - **Front Counter** — Check-in, job gallery, complete/close workflow
   - **Tech Station** — Repair queue, checklists, testing
   - **Admin** — Full access to everything
3. Tap **Set Up Device**

That's it! The device is now set up and will go straight to the correct view every time you open the app. You won't see this setup screen again unless an admin resets the device.

---

### Admin Access on Non-Admin Devices

If you're on the Front Counter or Tech Station iPad and need to do something that requires admin access (like changing settings or editing a closed item), you don't have to go find an admin device. Any admin can temporarily unlock their access:

1. Open the sidebar and tap **Admin Settings**
2. Enter your admin PIN when prompted
3. You'll have admin access for a limited time (configurable in settings — defaults to 5 minutes)
4. After the timer expires, the device automatically locks back to its assigned role

**What happens when the timer fires:** The lock is immediate. If you have an admin-only screen open (like Admin Settings), it closes automatically and the app returns you to the default view for this device's role. The sidebar re-grays the items that require admin access. You won't lose any data — anything you saved is saved, but anything unsaved in an admin-only sheet is dismissed.

**What admin elevation does and doesn't change:** Elevation gives you access to Admin Settings, lets you edit closed items, and unlocks the cost override buttons on the Front Counter. It does **not** change which workflow buttons you see on item cards — those are always determined by the device's assigned role. A Front Counter device with admin elevation still shows Front Counter actions; a Tech Station device still shows Tech Station actions. The device's role is what determines the view, not the elevation state.

Admin-role devices stay unlocked permanently — the auto-lock only applies when you're elevating access on a non-admin device.

### Sidebar Navigation

The app has a sidebar menu that lets you switch between different views. The sidebar is hidden by default so it doesn't take up screen space — you open it when you need it.

**To open the sidebar:**

- **On iPad:** Swipe from the left edge of the screen, or tap the back arrow button in the top-left corner of the toolbar. The sidebar slides over the current view. Tap any item to switch to that view. The sidebar closes automatically when you make a selection. You can also close it by swiping it away.
- **On iPhone:** Tap the **Back** button (< SR80) in the top-left corner to go back to the sidebar. The sidebar is the home screen — pick a destination and it pushes you into that view. Standard iOS back-and-forth navigation.

**What you see in the sidebar depends on your device role:**

- **Front Counter** — "Jobs" and "Customers" are available. Jobs is selected by default. "Work Queue" and "Admin Settings" are visible but grayed out since those aren't part of the front counter workflow.
- **Tech Station** — "Work Queue" is available and selected by default. Everything else is grayed out.
- **Admin** — all four options are available: Jobs, Customers, Work Queue, and Admin Settings. Jobs is selected by default.

If an admin temporarily unlocks a non-admin device (see "Admin Access on Non-Admin Devices" above), all sidebar items become available until the admin session expires.

The grayed-out items are there so everyone can see what the app can do — they just can't access views that aren't meant for their device's role.

At the bottom of the sidebar, under **This Device**, there's a **Display Size** button — see below.

---

### Display Size Settings

Every device can be set to a comfortable text size, independently of every other iPad in the shop. If the front counter iPad is farther from your eyes, or you just prefer bigger text, you can bump it up without affecting the back-shop screen.

New devices start at **Extra Large** text with **Bold Text** turned on — these defaults are designed for shop-floor readability at arm's length. You can change them anytime using the steps below.

**To change the display size:**

1. Open the sidebar (on iPad: swipe from the left or tap the back arrow; on iPhone: tap the Back button)
2. At the bottom of the sidebar, under **This Device**, tap **Display Size**
3. A settings panel slides up from the bottom

**Text Size** — three options:
- **Default** — standard size, same as most apps
- **Large** — noticeably bigger, good for extended use or reading glasses situations
- **Extra Large** — significantly bigger, designed for arm's-length viewing or anyone who needs more visual breathing room

**Bold Text** — toggle this on to make all text heavier/darker throughout the app. Works independently from the size setting — you can have bold text at any size.

Changes take effect immediately and are saved to this device only. The front counter iPad, back shop station, and admin device each remember their own settings.

---

### Getting Help In-App

If you forget how something works, the app has built-in help that shows you what each screen does without needing to pull up this manual. There are two ways to get to it, and they lead to the same place — use whichever one is faster in the moment.

**1. The `(?)` button in the toolbar**

Every major screen has a small `(?)` button in its top toolbar (next to the search bar on Jobs and Tech Station, next to the Save button on New Work Order, and in the top-right corner on Job Detail and Admin Settings). Tap it to open a quick walkthrough of *the screen you're currently on*.

The walkthrough opens as a sheet with a few pages you can swipe through — each page shows a screenshot and a short description of what that part of the screen does. Page dots at the bottom tell you how many pages are left. When you're done, tap **Got it** at the top to dismiss.

Use this when you're stuck on a specific screen and just want to know "what does this button do?"

**2. The Help entry in the sidebar**

If you don't know *which* screen you need — you just know you're trying to do something and can't remember where it lives — open the sidebar (on iPad: swipe from the left or tap the back arrow; on iPhone: tap the Back button), scroll down to **This Device**, and tap **Help**.

This opens a full list of every help topic in the app: Jobs Gallery, New Work Order, Job Detail, Tech Station, Close Out, Closed Job, Admin Settings, and any others that get added over time. Tap a topic to open the same walkthrough you'd get from that screen's `(?)` button.

Use this when you're not sure where to go next, or when you want to refresh on a part of the app you haven't used in a while.

**Both paths show the same content.** The only difference is where you start from. The `(?)` button is faster if you already know which screen you're asking about; the sidebar browser is better if you need to browse.

The help content is bundled into the app, so it works even when the shop's internet is down.

---

## Front Counter

### Job Board

When you open the app on a Front Counter device, you'll see the **Job Board** — a grid of cards showing all active work orders. Each card shows:

- **Item photos** — the top half of every card is a square photo area showing the equipment. If a job has one item, you see one big photo. Two items show stacked photos. Three or four items show a 2×2 grid. If there are more than four items with photos, the last tile shows a "+N" badge so you know there's more. Each photo has a small colored **status dot** in the top-right corner and an **equipment type label** (e.g., "Cylinder") in the bottom-right corner. When an item reaches Complete status, the dot is replaced by a green **COMPLETE** badge in the top-left corner of that tile — slightly tilted, same as V1.
- **Assigned tech** — if a tech has been assigned to any item on the job, a small dark chip appears in the bottom-left of the photo area showing who's working on it (e.g., "Rudy" or "Rudy, Tony" if multiple techs are on different items). This lets the Front Counter see at a glance which tech has each job without opening the detail view.
- **Job number** (e.g., 20260325-1) and **status dots** — one colored dot per item showing where it is in the repair process (blue = checked in, yellow = being worked on, orange = tested, green = ready for pickup)
- **Customer phone number** (tappable — tap to call or text), **name**, and **company name** (if the job is linked to a company — shown in smaller text below the customer name)
- **Equipment summary** (e.g., "Pump × 1 · Cylinder × 2") and the date/time the job was created
- **Job cost** — appears once at least one item has been priced. If all items have a cost entered, you'll see the full total (e.g., "$340.00") in clear, readable text. If some items are still being worked on and don't have a cost yet, you'll see an approximate total with "partial" next to it (e.g., "~$180.00 partial") in lighter text — this tells you the number isn't final yet. Tax is included in the total when tax is enabled in admin settings. Draft jobs and jobs with no cost entered yet don't show a cost line at all. Warranty jobs show "$0.00".

Photos load in the background — you'll see the cards appear right away with placeholder tiles, and the actual photos fill in a moment later.

**Calling or texting a customer:** Wherever you see a phone number in yellow underlined text — on a job card, in the job detail header, or on the Tech Station item header — tap it. A menu pops up with **Call**, **Message**, and **Cancel**. Tap Call to dial the number, or Message to open a text. This works on any device, any role.

**Draft work orders** appear at the top with an orange "DRAFT" badge and a warm-tinted background so they stand out as unfinished.

Each item shows its own status on its photo tile. When an item has been priced and approved (Complete status), a green **COMPLETE** badge appears in the top-left of that item's tile and the status dot disappears. Similarly, if an item has been marked as **Totaled** (unfixable), a dark **TOTALED** badge appears in the same spot, replacing the status dot. When an item's repair is done and it's waiting to be tested, an orange **READY FOR TESTING** badge appears — this tells you the tech is finished and the item just needs its final test before pricing. A job with two items can show one COMPLETE tile and one still-in-progress tile at the same time. Warranty items show a red **WARRANTY** badge below the status badge — you might see COMPLETE + WARRANTY or TOTALED + WARRANTY stacked together. Use the **COMPLETE filter** (see below) to quickly see all jobs where every item is ready for pickup.

**Flagged customers:** If a customer (or their company) has been flagged, you'll see a small amber **flag icon** on their job cards. This is a heads-up that there's something to be aware of — tap into the job to see the full flag banner with the reason. See [Flagging a Customer](#flagging-a-customer) for details.

Jobs are sorted by urgency: green (ready for pickup) first, then orange (tested), then items ready for testing (repair done, waiting on a tester), then yellow (in progress), then blue (just checked in). Within each group, the oldest jobs appear first. This way the items closest to being done — the ones a customer might be waiting on — are always at the top.

**On Fire jobs** — any job with at least one item marked on fire jumps to the very top of the active board (right below any drafts), ahead of everything else. On-fire items have a **red border** around their photo tile and a **🔥 badge in the bottom-left corner** so they're impossible to miss. See [On Fire Priority Flag](#on-fire-priority-flag) below for how to set and clear them.

**Waiting items** — items blocked on parts, seals, or approval show an **indigo border** and **⏳ badge** on their photo tile, plus an **indigo WAITING banner** on the item detail card with the reason and notes. Front Counter can see the flag but can't set or clear it — that's a tech/admin action. See ["Waiting" Flag](#waiting-flag-) below.

The Job Board updates automatically when jobs are created or changed on any device — you don't need to do anything to see new work orders appear. If you ever want to force an immediate refresh, pull down on the board.

Tap the **new job button** (document with a plus badge, in CAT yellow) to create a new work order. On iPad, it's in the top right corner of the toolbar. On iPhone, it's at the bottom right of the screen (like the compose button in Apple Notes).

### Searching and Filtering Jobs

On iPad, the **search bar** and **filter button** (circle with three lines) sit in the toolbar next to the new job button. On iPhone, they appear just below the navigation bar at the top of the screen.

**Searching:** Tap the search bar and start typing. The board filters in real time as you type. You can search by:

- Customer name, phone number, or company
- Job number (e.g., "20260325")
- Equipment type (e.g., "Cylinder")
- Machine type or item description
- Service reason (e.g., "Leaking")

The search checks all items within each job, so searching "Pump" will show any job that has at least one pump in it. Tap the **X** in the search bar to clear your search and see all jobs again.

**Complete filter:** Next to the search bar you'll also see a small **COMPLETE** button. Tap it to instantly show only jobs where every item is ready for pickup — the same jobs that have a green "COMPLETE" badge on their card. Tap it again to show all jobs. This is the fastest way to see exactly what's waiting at the counter.

**Filtering:** Tap the filter button (circle with three lines) to open a filter sheet with dropdown pickers:

- **Equipment Type** — show only jobs with a specific type of equipment (Cylinder, Pump, etc.)
- **Status** — show only jobs with items at a specific stage (Checked In, In Progress, Tested, Complete)
- **Machine Type** — if machine types are turned on in admin settings, you can filter by those too
- **Reason for Service** — tap one or more service reasons to filter by why the equipment was brought in. If you select multiple reasons, the job must have an item with ALL of those reasons.

When filters are active, the filter button fills in blue and a row of **filter chips** appears below the toolbar. Each chip shows what's being filtered (e.g., "Type: Cylinder") with an **X** to remove that specific filter. Tap **Clear All** to remove all filters at once.

If your search or filters don't match any jobs, you'll see a "No Matching Jobs" message instead of the grid.

### Closed Jobs (Job History)

At the bottom of the Job Board, you'll see a **Closed** section with a count of how many jobs are fully closed. This section is collapsed by default so it doesn't clutter the active board.

Tap the **Closed** header to expand it. You'll see the same card grid as above, but for jobs that are done — all items closed (including Totaled items that were closed via "Customer Contacted"). The cards are slightly dimmed so they're easy to tell apart from active jobs.

Tap the header again to collapse the section back down.

Your search and filters work across both active and closed jobs. If you search for a customer name and they have a closed job that matches, you'll see it in the closed section (expand it to check).

This is useful for looking up past work — warranty questions, repeat customers, or just checking what was done on an old job. Tap any closed job card to see the full detail view with all items, photos, and notes.

**Read-only for Front Counter:** Closed jobs are read-only from the Front Counter. You can view everything — photos, notes, repair history, cost — but intake fields are locked, the customer edit pencil is hidden, and no action buttons appear on closed items.

**Closure info:** At the top of a closed job's detail view, a **CLOSED** banner shows when the job was closed and who closed it — e.g., *"Closed Apr 14, 2026 at 3:05 PM · by Tony."* If you reopen and close it again, the banner updates to reflect the most recent close. On the individual item cards, a full-width gray **CLOSED** banner makes it immediately obvious which items are done — it's hard to miss. Similarly, items that are waiting for testing show a full-width orange **READY FOR TESTING** banner at the top of the item card so you can tell at a glance that the tech is finished and the item just needs its final test.

**Admin editing on closed jobs:** On an admin device (or a non-admin device with admin elevation active), closed items behave differently. The pencil icon reappears on closed item cards, so you can tap to edit intake fields if something needs correcting after the fact. A **Reopen Item** button is also visible on each closed item card — on non-admin devices it's grayed out with a lock icon as a visual reminder that it exists, but only an admin can use it.

**Reopening an item:** If a closed item needs to come back through the shop (a customer returns, something wasn't right), an admin can tap **Reopen Item** on that item's card. After confirming, the item moves back to **Complete** status and becomes actionable again — the front counter will see it in the active board and can close it again once the customer's situation is resolved.

**Reopening an entire work order:** If a whole job was closed by mistake, an admin can long-press the job card (from the Closed section on the Job Board, or from the customer's job history in the Customers view) and tap **Reopen Work Order**. An optional reason field appears — fill it in or leave it blank, then confirm. Every item on the job moves back to Complete status, the job reappears on the active board on all devices, and the reason (if entered) is logged in the audit trail. The original closure date and who closed it are preserved — reopening doesn't erase history, it just picks up where things left off.

### Creating a New Work Order

Tap the new job button from the Job Board to start a new work order (bottom-right on iPhone, top-right toolbar on iPad). The form has two main sections: **Customer / Company** (one card with both fields) and **Items**.

#### Finding or Adding a Customer

At the top of the form, the **Customer** field comes first. Start typing a customer's name or phone number. Matching customers will appear below the search field as you type. Tap a result to select them.

If the customer isn't in the system yet, tap **+ Add New Customer** to create one. The new customer form includes:

- **Name** — if you type a multi-word business name ending in a suffix like Inc, LLC, Corp, Co., or Ltd (e.g. "Smith Co."), the app will automatically move it to the Company field when you tap into the next field. It won't trigger on bare "Co" without a period, so names like "Collins" or "Cooper" won't get swiped. Each word auto-capitalizes as you type. You can leave this blank if you have a company name instead — at least one of Name or Company is required.
- **Company** — pre-filled if you already selected a company on the main form. Use the **Swap** button if the name/company got put in the wrong field. You can leave this blank if you have a customer name instead — at least one of Name or Company is required.
- **Phone** (required, 10 digits) — formats automatically as you type. If the phone number is already on file for another customer, you'll be warned and can choose to use the existing customer instead
- **Email** (optional)
- **Tax Exempt** toggle
- **Add a Contact** (optional) — tap to expand and add a contact person (name, phone, email, role). Useful for commercial accounts where someone other than the customer will be the point of contact. You can add more contacts later from the customer detail screen.

#### Company (Optional)

Below the Customer field, in the same card, is the **Company** field. Start typing a company name and matching companies will appear as suggestions. Tap a suggestion to select that company, or type a brand new name — a new company record will be created automatically when you save the work order.

**What happens when you select a company:**
- A row of customer name chips appears between the Customer and Company fields (e.g., "Rick M. | Joe S. | + New") — these are people who've checked in under that company before. Tap a name to auto-fill their info instantly. Tap "+ New" to enter a new person.
- If the company is **tax exempt**, you'll see a green indicator: "Tax exempt (via ABC Construction)" in the footer below the card. The tax status comes from the company automatically.

**Customer fills in the company automatically:** If you select a customer who's already linked to a company (or create a new customer with a company name), the Company field will auto-fill. You don't need to type it twice — the app connects the dots for you.

**Walk-ins:** If the customer is an individual (not from a company), just skip the Company field entirely. It's optional — leaving it blank works exactly like before.

**Company-only jobs:** If you know the company but don't have an individual contact name, that's fine — just fill in the Company field and skip the Customer field. The work order will be linked to the company without requiring a customer contact. You can always add a customer later by editing the job.

#### Adding Items

Each work order needs at least one item. For each item, fill in:

- **Equipment Type** — what the item is (Cylinder, Pump, Hose, or Other)
- **Reason(s) for Service** — tap the pill-shaped buttons to select why the customer brought it in (Leaking, Barrel Damage, Bushings, etc.). You can select multiple reasons.
- **Warranty pill** — a red pill with a shield icon labelled **Warranty**, just below Reason(s) for Service. Tap it once to mark this specific item as a warranty repair. It fills in solid red with white text when it's on, and reads as a red-outlined shield when it's off. Each item on a job has its own Warranty pill — you can mix warranty and non-warranty items on the same work order. See "Marking an Item as Warranty at Creation" below. The old "No Warranty on This Item" toggle has moved — it now lives on the Tech Station side once the item has been checked in. See "No Warranty Flag (Tech Station)" in the Tech Station section.
- **Scan Tag** — if the equipment has a QR sticker on it, tap this to scan it and link the tag to this item. See "Equipment Tags (QR Codes)" below.
- **Description / Notes** — any additional details about the item (at the bottom of the item card, below photos and reasons)

#### Marking an Item as Warranty at Creation

Inside each item card, there's a red pill labelled **Warranty** with a shield icon, sitting just below Reason(s) for Service. Tap it once to flag that item as a warranty repair — it fills in solid red when it's selected. Tap it again to unselect. Each item has its own pill, so you can have a mix of warranty and non-warranty items on the same work order (e.g., one cylinder under warranty from a previous repair, two others paid).

The item-level Warranty pill is a labeling flag — it tells the shop that this particular item is warranty work. It does NOT by itself set the job-wide warranty lock or force the cost to $0 on the tech side. For that, you use the job-level **Warranty** control described in "Marking the Whole Job as Warranty" below, which is typically how you'd handle a job where everything is warranty work.

**When you'd use the item-level pill:**
- A repeat customer drops off three cylinders, and only one of them is warranty from a previous job
- You want a visual record on the item that it came back under warranty, even though the rest of the job is being paid normally

**When you'd use the job-level Warranty toggle instead:**
- The whole job is warranty work (see "Marking the Whole Job as Warranty")
- You want the cost automatically locked at $0

If you got to the form through the **Check In for Warranty** button on an existing closed job, the item-level Warranty pill is already selected on every pre-filled item.

#### Marking the Whole Job as Warranty

If the entire job is warranty work — the customer brought something back in for a repair that's still under warranty — you have two paths depending on whether the original job is in ShopTracker:

- **The original job IS in ShopTracker** → use the **Warranty Check-In** flow from the Job Board. See "Warranty Check-In" below.
- **The original job is NOT in ShopTracker** (done on paper, before the app existed, at another location) → create the work order like normal, then open the job detail view and tap the red **Warranty** pill in the warranty card near the top of the screen. It uses the exact same pill styling as the item-level pill so you know it's the same concept, just applied to the whole job. Toggling it on locks the cost at $0 for all items and shows the **WARRANTY** badge on the gallery card.

You can toggle the job-level Warranty pill any time after check-in too, as long as at least one item is still active (not Closed or Totaled). This is useful when the customer calls back after drop-off and confirms something was under warranty, or when you discover the equipment's repair history during inspection. Once every item on the job is Closed or Totaled, the toggle locks to prevent retroactively flipping warranty on a wrapped-up job.

Tap **+ Add Item** to add more items to the same work order (e.g., a customer drops off 3 cylinders at once).

To remove an item, tap the trash icon next to its header. You can't remove the last item.

#### Taking Photos During Intake

Each item has a **Photos** section at the top of the item card, above the other fields. This is a great time to photograph the equipment as it comes in — document any existing damage, serial numbers, or anything else worth capturing before the tech starts work.

You have two options:

- **Camera** — tap the camera button to open the camera. The camera stays open between shots — tap the shutter button as many times as you need, and each photo appears in a strip at the bottom of the screen. If you snap a bad photo, tap the **X** on its thumbnail in the strip to remove it. When you're done, tap **Done** in the top-right corner to close the camera and return to the form. You can also tap **Cancel** to close the camera at any time — photos you already took are kept.
- **Library** — tap the library button to pick a photo already on the device (useful if someone snapped a picture before opening the app)

Photos appear as small thumbnails in a grid below the buttons. To remove a photo before saving, tap the **X** on the thumbnail. Photos aren't uploaded until you tap "Create Work Order" or "Save as Draft" — you'll see a brief "Uploading..." indicator while they're sent to the server.

There's no limit on photos per item. Take as many as you need.

#### Equipment Tags (QR Codes)

If the equipment has a sticker tag, tap **Scan Tag** in the item form and point the camera at it. The app links the sticker to this item. For the full tags workflow — printing stickers, what to do with returning equipment, reprinting a damaged tag — see the **Equipment Tags** section near the end of this manual.

#### Saving

The button in the top right changes based on what you've filled in:

- **"Create Work Order"** — appears when all required fields are filled in. Which fields are required depends on your admin settings (see [Required Fields](#required-fields)), but by default it's customer and equipment type. If photos, description, or other fields are set to required, those must be filled in too. This creates the work order with a job number and makes it visible to the back shop.
- **"Save as Draft"** — appears when required fields are still missing. This saves your progress so you can come back to it later. Drafts appear at the top of your Job Board with an orange badge but are NOT visible to the Tech Station.

**Tapping Back mid-form:** If you tap the **Back** button before finishing the form, ShopTracker saves your progress as a draft — including any photos you've already taken — and returns you to the Job Board. If you opened the form and didn't fill in anything at all, it just closes without creating a draft.

### Viewing a Job (Job Detail)

Tap any card on the Job Board to open the full job detail view. This shows everything about the work order in one place.

At the top you'll see a **header card** with:

- **DRAFT badge** (orange) or **job number** (e.g., 20260325-1)
- **Customer name, phone number** (tappable — tap to call or text), **and company** (if applicable). A small **pencil icon** next to the customer name lets you edit the customer directly (opens the edit form with contacts).
- **Additional contacts** — if the customer has contacts on file, they appear below the main customer info in smaller text, showing each contact's name, role, and tappable phone number
- **Status dots** — one colored dot per item, same colors as the Job Board
- **Item count** and **creation date/time**

Draft jobs have a warm amber-tinted header, just like on the Job Board.

Below the header, each **item** gets its own card. On jobs with multiple items, **items that are ready for action float to the top automatically** — Complete items appear first (ready for customer pickup and payment), then Totaled items (awaiting customer contact), then everything else in their normal order. This means you always see what needs your attention first, without scrolling past items that are still being worked on.

Each item card shows:

- **Item reference number** and **status** (with a colored badge like "Checked In" in blue, "In Progress" in yellow, etc.) — each item shows its full reference in `YYYYMMDD-N-M` format (e.g., `20260403-1-2` means job 20260403-1, second item). Single-item jobs still show just the job number.
- **Equipment Type** — what the item is
- **Machine Type** and **Color** — if those fields are turned on in admin settings
- **Reason(s) for Service** — shown as blue pill-shaped tags
- **Description / Notes** from intake
- **Assigned tech** — if a tech has grabbed the item, you'll see their name (e.g., "Assigned to Carlos")

On iPad, each item card uses a **two-column layout**: the left side holds the photos, and the right side holds the equipment details, notes, and repair history. On iPhone everything stacks single-column in the same order.

#### Collapsing and Expanding Items

On jobs with multiple items, the detail view can get long. Each item card has a small **chevron** (▼/▲) at the right end of its header row. Tap the chevron to collapse that item down to just its header — you'll still see the status dot, item reference number, and status badge, but all the photos, details, and action buttons are hidden. Tap the chevron again to expand it back.

This is handy when you're done reviewing one item and want to get to the next without scrolling past a wall of photos and notes.

**Smart auto-collapse:** On jobs with 3 or more items, any items that are already **Closed** will automatically collapse when you open the job. Totaled and active items stay expanded so you can see and act on them immediately. You can always expand a closed item by tapping its chevron if you need to review it.

**Collapse All / Expand All:** On jobs with 3+ items, you'll see a small **"Collapse All"** or **"Expand All"** link in accent color (yellow) above the item list. Tap it to collapse or expand everything at once — useful when you just want to scan the status of each item without the full detail.

Collapse state resets every time you open a job, so you always start fresh.

If photos have been taken for an item, the first photo is shown as a **square hero photo** — a large cropped preview sized to fill the available width so details are easy to see at a glance. On iPad this fills the left column; on iPhone it appears at the top of the card. Below the hero is a grid of smaller thumbnails for any additional photos, with **Camera** and **Library** buttons at the end. Thumbnails wrap into rows to fit the available space — the buttons are always visible, even with many photos. Tap the hero or any thumbnail to view it full-screen. Photos that have been marked up show a small pencil badge so you can tell at a glance which ones have annotations.

You can add more photos to any item at any time, regardless of its status. Tapping **Camera** opens the continuous camera: the shutter stays open so you can take multiple shots in one go, with a thumbnail strip at the bottom. If you snap a bad one, tap the **X** on its thumbnail to remove it — the photo is deleted immediately. Tap **Done** when you're finished. New photos upload immediately and appear in the grid.

#### Deleting Photos

You can delete any photo from an item that isn't Closed, from **any device** — Front Counter, Tech Station, or Admin. **Press and hold** (long-press) on any photo thumbnail or the hero photo — a menu appears with **Delete Photo**. Tap it, then confirm in the dialog that follows.

- **Admin devices** (or admin-elevated devices): the photo is deleted immediately after you confirm.
- **Front Counter and Tech Station devices**: after you confirm, an **admin PIN entry** screen appears. Enter a valid admin PIN and the photo is deleted. Tap Cancel to back out — nothing is deleted. This is a one-time check; entering the PIN does not unlock admin features on your device.

The photo, its markup, and all associated files are permanently removed. This cannot be undone. Closed items do not allow photo deletion at all.

#### Reordering Photos (Make Hero Image)

The first photo on an item is the **hero image** — the large square photo that appears at the top of the item card and on the job board. If you want a different photo to be the hero, you can promote it with a long-press.

**Press and hold** on any thumbnail in the grid below the hero photo. A menu appears with **Make Hero Image** (and Delete Photo below it). Tap **Make Hero Image** and the selected photo immediately becomes the new hero — the big square at the top. The previous hero moves down into the thumbnail grid.

This works on both Front Counter and Tech Station, on any item with two or more photos. There's no confirmation dialog — it happens instantly and you can always switch it back by long-pressing the old hero in the thumbnail grid.

#### Viewing Photos Full-Screen

Tap any photo — the hero image or any thumbnail — to open it full-screen. If the item has multiple photos, **swipe left and right** to flip through all of them without closing and reopening. A small counter at the bottom (e.g., "3 / 7") shows which photo you're on. Items with only one photo won't show the counter or respond to horizontal swipes.

To close, **tap anywhere** on the photo, tap the **X** button in the top-left corner, or **drag down** on the photo. The drag-to-close gesture only responds to mostly-vertical drags — horizontal swipes go to the next/previous photo instead.

#### Marking Up Photos

This is the feature that replaces Apple Notes markup. Tap any photo thumbnail to open it full-screen, then tap the **Markup** button (pencil icon) in the top-right corner. This opens the Apple PencilKit editor with the full native toolbar — pens, markers, pencils, erasers, ruler, and the complete color palette.

If you've swiped to a specific photo, Markup opens on **that** photo — not the first one. Save applies to whichever photo you're looking at.

Draw directly on the photo to circle damage, write prices, add arrows, or annotate anything worth calling out. When you're done, tap **Save**. The marked-up version becomes what everyone sees on the job — on cards, in the detail view, everywhere.

**Your original photo is always preserved.** Markup is non-destructive. If you need to redo it (say the price changed), tap the photo again, tap Markup, and your previous strokes are still there — you can erase specific marks, add new ones, or start fresh with the trash button. If you want to remove all markup entirely, tap the **revert button** (curved arrow) in the toolbar and the photo goes back to the untouched original.

Markup is available on every photo at every status — Front Counter intake photos, Tech Station repair photos, any of them. There are no restrictions on who can mark up or when.

#### Notes

Each item card has a **Notes** section where you can add timestamped notes at any point in the workflow — before repair, during, after, whenever.

On iPad the **"Add a note..."** field sits in the right column below the equipment details. Type your note and tap the yellow send arrow. The note is saved immediately with your name and the exact time, and it appears in the Repair History timeline below.

Notes are visible to both the front counter and the tech station. Maria can jot down customer instructions ("needs by Friday"), and Tony can document what he found during repair. Everyone sees the same history.

#### Repair History

On iPad, the right column of every item card shows a **Repair History** — a chronological timeline of everything that's happened to that item, in order. On iPhone it appears below the details, same info.

Each event in the timeline shows a timestamp and looks like this:

- **Grabbed by [tech name]** — when a tech claimed the item and started work
- **[Author name]: [note content]** — any notes added by front counter or tech staff
- **Round N: [repairs]** — the issue checklist items the tech checked off (e.g., "Seal, O-ring"). If the item went through multiple repair rounds after a failed test, each round appears separately in order.
- **Passed / Failed — [tester name]** — every test attempt is shown, not just the most recent. So if an item failed its first test and passed its second, you'll see both entries with their times.
- **Oil: Clean / Dirty — [performer]** — if an oil sample was taken
- **Marked Waiting — [reason]** — when a tech marked the item as waiting, with the reason (e.g., "Waiting on Parts" or "Other: waiting on custom seals from Parker") and any notes. The tech's name appears below.
- **Resumed Work** — when the waiting flag was cleared and work resumed. Shows the tech's name.
- **Customer Contacted — [outcome]** — on Totaled items that were closed via the "Customer Contacted" flow, shows the contact outcome (e.g., "Left voicemail", "Customer coming in") and when it happened. Only appears on items that went through the Totaled path.

If a cost has been recorded, a **cost summary** appears below the timeline showing the total. If parts and labor were entered separately, it shows a breakdown (Parts / Labor / Tax / Total). A green **"Approved"** badge or orange **"Pending Approval"** badge shows the manager approval status.

The Repair History section only appears when there's something to show — if an item is brand new and nothing has happened yet, the section stays hidden.

#### Test & Sample History (Detail Sheet)

Below the Repair History, you'll see a **Test & Sample History** link if the item has any test attempts or oil samples recorded. It shows the total count (e.g., "Test & Sample History (3)").

Tap it to open a full-screen sheet with the complete history — every test attempt and oil sample in chronological order, with:

- **Test results** — PASSED or FAILED, who tested, and when
- **Oil samples** — Clean or Dirty, who performed it, when, and any notes shown in italics below the entry
- **Photos** — oil samples that had photos show thumbnail previews (48×48) right in the timeline

This gives you more detail than the Repair History timeline, which only shows a one-liner per entry. The sheet is read-only — tap **Done** in the top-right corner to close it.

Below each item card, you may see **action buttons** depending on the item's status and your device role. On the Front Counter, you can close items that are ready for pickup. On the Tech Station, you'll see grab, done, tested, and cost entry buttons.

Use the **back arrow** to return to the Job Board.

### Adding Materials (Hoses, Fittings, Adapters, Seals)

If a repair involves hoses, fittings, adapters, or seals, you can add those as separate line items on the work order. These show up in the **Hose** section on the job detail view, just below the consolidated cost summary card at the top. (The section header actually uses whatever you've named the hose category in Admin Settings → Category Labels — "Hose" is the default.)

**To add materials:**

1. Open the job from the Job Board
2. Tap the green **[+]** button next to the Hose section header
3. A sheet opens with four tabs at the top: **Hose Assembly**, **Fitting**, **Adapter**, and **Seal**

**Hose Assembly** — for a complete hose build. Each row has four currency fields on a single line: **Fitting 1**, **Fitting 2**, **Hose**, and **Total**.

- If you have the full breakdown, enter Fitting 1, Fitting 2, and Hose (e.g., 20/20/85). The Total field auto-fills with the sum and locks — you don't need to touch it.
- If you only have the total (from a manual invoice or memory), leave the three breakdown fields empty and just type the total directly into the **Total** field.
- Add a description if you want (e.g., "Boom cylinder supply line").

Either way works, and the app saves whichever fields you used. Itemized assemblies display the breakdown on the job (`$20 + $20 + $85 = $125`); total-only assemblies just show their total.

**Fitting**, **Adapter**, or **Seal** — for standalone items. Enter quantity, unit price, and an optional description.

**Adding multiple at once:** Each tab opens with **three empty rows**. Fill in whichever rows you need and tap Save — they all get added at once. Need more than three? Tap **+ Add Another** at the bottom for a fourth, fifth, etc. Need fewer? Just leave unused rows blank (they're ignored), or tap **Remove** on a row to delete it. Less clicks, more shipping.

**Mix categories freely:** You can add hose assemblies on the Hose Assembly tab, flip over to Fittings and add a few there, drop a Seal on the Seal tab, and then tap Save — everything from every tab saves at once. Switching tabs never drops your entered data, and the **Total** at the bottom of the sheet shows the combined grand total across all four tabs in real time, so you always know what you're about to save.

All materials are taxed when sales tax is turned on shop-wide. If a customer is tax exempt, no tax is charged on anything (materials included).

Each item shows up as a row in the Hose section with a colored pill (blue Hose Assembly, orange Fitting, purple Adapter, pink Seal) and the cost breakdown. The totals roll into the cost summary card at the top of the job detail — so when it's time to enter amounts into Square, everything is in one place.

**Who can add materials:** Anyone — front counter, techs, and admins — can add materials to a job at any time while it's open.

**Deleting a material:** Admins and Front Counter can remove a mis-added hose, fitting, adapter, or seal. **Press and hold** (long-press) on the row in the Hose section — a context menu appears with a red **Delete** option labeled with the item's type. Tap it, confirm in the dialog (which shows the item's description if there is one), and the row is gone. Tech Station devices don't see this menu; if a tech needs to delete something, admin elevation unlocks the same long-press. Once a job is closed, the delete option is hidden for everyone — closed jobs stay closed.

### Editing a Draft Work Order

If you tapped "Save as Draft" when creating a work order and need to come back to finish it, tap the draft card on the Job Board to open it.

On a draft, you can **tap the customer section** in the header to assign or change the customer. If no customer has been assigned yet, you'll see "Tap to assign customer" with a small arrow. This opens a customer search sheet where you can look up an existing customer, add a new one, or remove the current customer. Tap **Save** to apply your changes.

You can also **tap any item card** to edit it. This opens an edit sheet where you can change the equipment type, service reasons, description, and any other fields. Tap **Save** when you're done — the changes save to the server immediately.

If an item is still missing required fields (like Equipment Type, Reason for Service, Photos, or any other field your admin has set to required), the item card will have a **light orange background** with a **"Complete Item Info" button** at the bottom. Tap the item header row or the orange button to open the edit sheet and fill in what's missing. Items that are already complete show a normal white background.

#### Adding More Items

Below the item cards, you'll see an **"+ Add Item"** button. Tap it to add another item to the work order — same form as when you created the original items (equipment type, service reasons, description, photos). The new item appears in the list immediately after you tap **Add**. New items always start at **Checked In** status with a blank form, regardless of where the other items are in the workflow.

On **drafts**, the Add Item button appears below the item list (same as always).

On **finalized work orders** (non-drafts), you'll also see a **+** button in the top-right toolbar in addition to the inline button below the items. Who can see the Add Item button depends on where things are in the workflow:

- **Still in check-in** (all items at Checked In): Front Counter and Admin can add items.
- **Any item past check-in** (In Progress, Tested, Complete, etc.): Only Admin or an elevated Front Counter (admin PIN unlocked) can add items. This prevents the front counter from injecting items into an active repair without admin oversight.
- **Tech Station**: Never — techs don't check stuff in.
- **Fully closed job** (all items Closed or Totaled): Nobody can add items.

#### Removing an Item from a Draft

Changed your mind about one of the items? On each item card in a draft, you'll see a small red **"Remove Item"** link (with a trash icon) at the bottom right of the card. Tap it and a confirmation will appear asking if you're sure — tap **Remove Item** to confirm.

The item and all its photos are permanently deleted. This can't be undone.

**If the draft only has one item**, you'll see a different message: "This is the only item on this draft. To remove it, delete the entire draft instead." Tap **Delete Draft** to delete the whole thing, or **Cancel** to go back.

This only works on drafts — once a work order is finalized, you can't remove items from it.

#### Deleting a Draft

If a draft was created by mistake or is no longer needed, you can delete it entirely. Open the draft from the Job Board, then tap the **trash icon** in the top-left corner of the screen.

A confirmation sheet will appear asking you to confirm — tap **Delete Draft** to proceed, or **Cancel** to go back. Once deleted, the draft and all its items and photos are permanently removed. This cannot be undone.

Deletion requires an internet connection. If the app is offline, you'll see an error message — try again once you're back online.

Only drafts can be deleted this way. Finalized work orders cannot be deleted (use the Close or Totaled workflow instead).

### Editing a Checked-In Item

After a work order is finalized (no longer a draft), you can still edit an item's intake information — equipment type, machine type, service reasons, and description — **as long as the item hasn't been grabbed by a tech yet**.

While the item is in **Checked In** status, you'll see a small **pencil icon** on the item card. Tap the card to open the edit sheet, make your changes, and tap **Save**.

Once a tech grabs the item (moves it to In Progress), the intake fields lock. The pencil icon disappears and tapping the card no longer opens the editor. This prevents accidental changes to information the tech is already working from.

**Photos and notes are never locked.** You can add photos and notes to any item at any status, even after the intake fields are locked.

**Admin override:** If an admin needs to correct intake fields on an item that's already In Progress or beyond, they can elevate admin access on the device (enter their PIN), and the edit option becomes available again regardless of status.

### No Warranty Flag

Some repairs don't come with a warranty — a cylinder the customer drilled into, equipment that's beyond normal wear limits, or any job where you and the customer have agreed that the work is best-effort only. The No Warranty flag lets you document that so there's no confusion later.

By default, the No Warranty control lives on the Tech Station side, after an item has been checked in. See "No Warranty Flag (Tech Station)" in the Tech Station section of this manual for how techs set and clear it. Admins can opt the Front Counter in via a Shop Settings toggle — see "Front Counter: No Warranty" under Admin → Shop Settings for details.

**What Front Counter sees (default — toggle off):**
- You don't see the No Warranty pill at all during check-in or on existing items — not even on items the tech has already flagged. The whole control is hidden on Front Counter devices so there's no risk of Maria toggling something she shouldn't.
- Items that were completed via the **Mark Complete (No Warranty)** action (see below) still show a brown **COMPLETE • NO WARRANTY** badge on the job board tile instead of the usual green **COMPLETE** badge, so the whole team can tell at a glance which items are going out the door without warranty.

**What Front Counter sees when the admin has enabled it:**
- An amber-orange **No Warranty on This Item** pill appears on the item card in the job detail view for items that are In Progress, Tested, or Complete.
- The pill is tappable — Front Counter can set it with the exact same rules as Tech Station. Tapping opens a cost sheet, confirming moves the item to Complete with the No Warranty flag on, and non-zero costs route through the same **"Was that cost approved by a manager?"** popup as the normal flow. Long-press on an already-set pill lets you edit the cost later.
- This is useful in shops where Maria is the one having the conversation with the customer about warranty terms at drop-off or pickup. If it's not useful for your shop, leave the setting off and the pill stays out of the way.

**Mark Complete (No Warranty):**
This is the other way in — available to any role on an item that's In Progress, Tested, or already Complete (as long as it isn't already flagged No Warranty). It lives in the item action area as a brown button labeled **Mark Complete (No Warranty)**. Tapping it opens the same **Mark as No Warranty** cost sheet the pill does. Optionally enter a cost, tap **Confirm**, and if the cost is non-zero you'll get the manager approval popup. On confirm the item jumps to Complete, the No Warranty flag turns on, any cost you entered is recorded, and the board tile gets the brown **COMPLETE • NO WARRANTY** banner as the audit trail. Use whichever entry point — the pill or the button — is closer to your thumb.

**Where the flag shows up:**
- Amber-orange **No Warranty on This Item** pill on the item detail card (both Front Counter and Tech Station)
- Brown **COMPLETE • NO WARRANTY** badge on the job board / tech queue photo tile once the item reaches Complete
- Small dark **NO WARRANTY** pill next to the item reference in the header (unchanged from before)

### "On Fire" Priority Flag (🔥)

When an item needs to jump the line — an angry customer, a piece of equipment that's holding up another shop, anything where "do this one next" is the right answer — you can mark it **On Fire**. The item will float to the top of both the Job Board and the Tech Station queue until you take the flag off.

**Setting it at check-in (brand new job or adding an item to a draft):**
As you're filling out a new work order — or when you tap **+ Add Item** on an existing draft — each item card has a 🔥 emoji in the top-right corner of the item section. It starts out **dimmed** (about 30% opacity) to show it's an optional affordance without shouting at you. Tap it and a confirmation sheet pops up asking **"Mark this item as On Fire?"** — tap **🔥 Yes, On Fire** to confirm. The emoji goes full-bright so you know it's set. If you change your mind before saving, tap it again and choose **Remove**. When you hit Create Work Order (or Save as Draft), the flag is saved with the item — the red border and 🔥 badge show on the card immediately.

**Setting it on an existing item:**
Open the job, scroll to the item you want to prioritize, and tap the **🔥 Mark as On Fire** button near the bottom of the item card (below the Complete Item Info banner if present, above Replace Tag if present). That's it — no confirmation, no picker. The button immediately flips to **🔥 On Fire** in a filled state so you can tell it's already set.

[screenshot: NewJobView item card header showing dimmed 🔥 emoji top-right, and the confirmation dialog after tapping]

**What it looks like:**
- The item's photo tile on the Job Board and Tech Station gets a **red border** and a **🔥 badge in the bottom-left corner**. It's intentionally loud — you shouldn't miss it from across the room.
- A small 🔥 pill also appears in the item header on the job detail view, right next to the status badge.

**Where it sorts:**
- **Job Board:** Any job with at least one on-fire item jumps to the top of the active board, immediately below any drafts. Within the on-fire group, the most recently updated job is first.
- **Tech Station queue:** On-fire items jump to the absolute top of the queue, above Ready for Test. They're impossible to miss when the techs open the app.

**Clearing it:**
From the job detail view, **long-press the 🔥 pill** in the item header (hold for about half a second). A confirmation dialog asks "Remove the on fire flag from this item?" — tap **Remove Flag** and the item returns to its normal position in the sort.

**Who can set and clear:**
- **Front Counter** and **Admin** only. Techs see the flag but can't change it — if they need it on or off, they ask the counter.
- An admin-elevated Front Counter device can also set and clear the flag.

**Important:**
- The flag persists permanently, even after the item closes. If it was on fire when you closed it, the 🔥 badge still shows on the card in job history so you have a record of what needed urgency.
- Closed on-fire jobs do NOT float to the top of the Closed section — the badge shows but they stay sorted by close date like the rest of history.
- The flag works offline. Mark it on fire even if the shop Wi-Fi is down and it will sync when you're back online.

### "Waiting" Flag (⏳)

Sometimes work on an item has to stop — you're waiting on parts, seals, customer approval, or an outside service. The **Waiting** flag marks that hold visually so everyone can see at a glance which items are blocked without changing the item's actual status.

**What it looks like on the Front Counter:**
- The item's photo tile on the Job Board gets an **indigo border** and an **⏳ badge in the bottom-left corner** — similar to the On Fire treatment but in indigo instead of red.
- An **indigo WAITING banner** appears on the item detail card inside the job, showing the reason (e.g., "Waiting on Parts") and any notes the tech added (e.g., "ETA Friday, ordered from Parker").
- If the item's repair is already done, you'll see **both** an orange **READY FOR TESTING** badge and an indigo **WAITING** badge stacked on the photo tile — "repair done, but blocked."
- Waiting items sort to the **bottom** of the Tech Station queue — the opposite of On Fire, which sorts to the top.

**Front Counter cannot set or clear the Waiting flag.** This is a repair-workflow action — only techs and admins can mark an item as waiting or resume work. If you see a waiting item and think the hold should be cleared, tell the tech.

**Filtering:** Tap the filter button on either the Job Board or Tech Station. There's a **"Show Waiting Items Only"** toggle in the Waiting section — flip it on to see only blocked items. A "Waiting Only" chip appears below the toolbar; tap X to remove it.

### Changing the Customer on a Job

You can change the customer assigned to a work order — not just on drafts, but on finalized jobs too.

In the job header, next to the customer's name, you'll see two small buttons:

- **Pencil icon** — opens the customer's info for editing (name, phone, company, contacts, tax exempt, etc.). Use this when the right customer is already assigned but their info needs a fix.
- **"Change" capsule** (accent-colored pill with a swap arrow) — opens the customer search sheet so you can pick a **different** customer entirely. Use this when the wrong customer got assigned during intake and you need to replace them.

Tap **Change** → search for the correct customer → tap them in the results → tap **Save**. The customer on the work order updates immediately, and so does the company field (if the new customer has no company, the company on the job clears automatically — it won't leave the old company name behind).

[screenshot: Job Detail header showing the pencil and accent-colored Change button next to the customer name]

**While all items are still Checked In:** The Change button is available to anyone (front counter, tech station, admin).

**Once any item has been grabbed by a tech** (moved to In Progress), the Change button disappears for regular users. This prevents accidental customer changes on jobs that are actively being worked on.

**Admin override:** If an admin needs to reassign a customer on a job that's already in progress, they can elevate admin access (enter their PIN) and the Change button comes back regardless of item statuses.

**One guardrail on live jobs:** On any non-draft (finalized) job, the Change sheet will NOT let you remove the customer entirely — you can only swap them for a different one. The "Remove Customer" option is hidden and Save is disabled if you haven't picked a replacement. Drafts are different: you can leave a draft customer-less while you're still assembling the order (the Finalize button will still require a customer to be assigned before you can turn the draft into a real work order).

### Finalizing a Draft

Once all required fields are filled in on a draft, the **Finalize** button in the top right corner becomes active. The same required field rules apply here as when creating a new job — if your admin has Photos, Description, or any other field set to required, those must be filled in on every item before you can finalize.

Tap **Finalize** to convert the draft into a real work order. The app will:

1. Generate a job number (e.g., 20260325-4)
2. Show a brief **"Finalized!"** confirmation with the new job number
3. Automatically return you to the Job Board

The job now appears as a regular work order card (no more DRAFT badge) and is visible to the Tech Station.

### Customer Check-In

Coming soon.

### Complete & Pickup

When all items on a job have been priced and approved (all showing green/Complete), you're ready to close the job when the customer comes to pick up.

**Finding the item:** Look for the zone badge on the job card — **Z1 (Front)** in blue means it's in the front counter area, **Z2 (Back)** in purple means it's in the back shop area. You'll also see the zone badge on the item detail header if you open the job.

#### Closing an Entire Job (Most Common)

Open the job from the Job Board. Right below the customer info card, you'll see the **cost summary card** — this is the one place that shows everything Maria needs to type into Square:

- **Labor lines** — one row per item with a labor cost. If there's only one, it's just "Labor $X". If there's more than one, they're numbered (**Labor #1**, **Labor #2**, …) and a bold **Labor Subtotal** row appears underneath.
- **Hose lines** — one row per hose-side entry (the item's hose-bucket cost when split is on, each hose assembly, each fitting/adapter/seal). Same rule: single entry just says "Hose $X"; multiple get numbered (**Hose #1**, **Hose #2**, …) with a bold **Hose Subtotal** row underneath.
- **Tax (X.XX%)** — the calculated tax, shown below the Hose Subtotal when sales tax is on. Tax-exempt customers don't see this row at all — the whole tax block is hidden so there's no confusion about what's owed.
- **Grand Total** — the big bold total at the bottom of the card, below a thick divider.

(The "Labor" and "Hose" labels match whatever you've named the billing categories in Admin Settings → Category Labels. Defaults are Labor and Hose.)

This card shows up as soon as the job has any costed content — you don't have to wait for items to be marked Complete to see the totals. So even mid-job, you can glance at the card to see where things stand.

When every item on the job is Complete (green), a green **"Close Job"** button (or **"Close All N Items"** if there are multiple items) appears inside that same card, right below the Grand Total. Tap it, confirm, and you're done — all items close at once and the app takes you back to the Job Board. The job moves to the Closed section at the bottom of the board.

#### Fixing a Wrong Cost (Long-Press the Grand Total)

Tony fat-fingered a cost during testing? The customer negotiated a different price? You can correct any costed item's price right from the cost summary card — no admin unlock required.

1. **Long-press** (press and hold for about half a second) the **Grand Total** row at the bottom of the cost summary card
2. A menu appears:
   - If the job has only one costed item, you'll see a single **"Edit Cost"** option
   - If multiple items have costs, you'll see one option per item — **"Edit Item 1 — $350.00"**, **"Edit Item 2 — $125.00"**, etc., so you can pick exactly the one you need to fix
3. Tap the option — the **Edit Cost** sheet opens pre-filled with the current values
4. Adjust the total (or parts/labor breakdown if split is on), toggle taxable if needed, tap **Save**

The cost updates immediately and the Grand Total recalculates. The item's status doesn't change — if it was Complete it stays Complete.

**Every cost change is logged.** A timestamped note is automatically added to the item's notes timeline showing the old amount, the new amount, the iPad it was changed on, and (if someone is signed in) the employee's name. So if Maria fixes a cost on the Front Counter iPad while Justin is logged in, the note reads:

> **System** — Cost updated from $350.00 to $325.00 by Front Counter iPad (Justin)

This is the universal "we caught a mistake" path — anyone on any device can use it. The orange **Edit Cost** button on the item card (admin-only, requires admin unlock) is still there for in-flow corrections before close, but for the common shop-floor "wrong number, fix it now" case, the long-press is the right tool.

#### Partial Pickup (Customer Takes Some Items, Not All)

Sometimes a customer picks up one or two items but leaves others in the shop. When this happens:

1. Open the job detail view
2. Scroll down to the item that's being picked up
3. Tap the gray **"Close"** button below that item's card
4. Confirm — "Customer has picked up and paid for this item"

The closed item grays out and shows a **"Picked Up"** badge in the top-right corner. The job stays on the active board because other items are still being worked on.

When the customer comes back for the rest, the cost summary card at the top will already be showing the remaining balance. Once all remaining items are Complete, the green **Close Job** button appears inside that same card and you can close everything in one tap.

**Note:** The per-item Close button only appears during partial pickup situations — when some items are ready but others are still in the shop. When all items are Complete, use the Close Job button in the cost summary card at the top instead.

#### After Closing

Once the last item on a job is closed, the view automatically takes you back to the Job Board. The job moves from the active grid to the **Closed** section at the bottom (collapsed by default — tap the header to expand it).

#### Totaled Items — "Customer Contacted"

Totaled items follow a different close path than normal items. They don't go through Complete — instead, they sit on the board with a **TOTALED** banner until you contact the customer.

When you open a job with a Totaled item, you'll see:

- The item's cost (if the tech entered a diagnostic charge) displayed in the repair summary — reference this when speaking to the customer
- A green **"Customer Contacted"** button below the item card

**To close a Totaled item:**

1. Call or contact the customer about the unfixable item
2. Open the job and find the Totaled item
3. Tap **Customer Contacted**
4. If the customer has additional contacts on file, you'll see a **"Who did you reach?"** picker at the top — select the customer themselves or a specific contact. If there are no contacts, this picker is hidden and you go straight to the outcome.
5. Select what happened from the list:
   - "Left voicemail"
   - "Customer coming in"
   - "Scheduled pickup"
   - "No answer — will try again"
   - "Other"
5. Optionally add a note with extra details
6. Tap **Confirm**

The item moves to Closed. A timestamp and your selected outcome are logged for the audit trail and appear in the item's **Repair History** timeline — so anyone reviewing the closed job later can see when the customer was contacted and what the outcome was.

**Important:** "Customer Contacted" requires an internet connection. If the app is offline, you'll see an error — try again once you're back online.

**Note:** The Close Job button inside the cost summary card only closes Complete items — Totaled items handle their own close through "Customer Contacted." A job is fully closed when ALL items are closed, whether they got there through the normal Complete → Close path or the Totaled → Customer Contacted → Close path.

[screenshot: Customer Contacted sheet with outcome picker and note field]

#### Marking Items as Totaled (Front Counter)

You can mark items as Totaled directly from the Front Counter — you don't have to wait for a tech. This is useful when an item is visibly unfixable at intake (severely bent rod, cracked housing, etc.).

1. Open the job detail
2. Find the item you want to mark
3. Tap the **Totaled** button (available on items that are Checked In, In Progress, or Tested)
4. Confirm

The item gets a black TOTALED banner on the job card and enters the "Awaiting Customer" state.

#### Warranty Check-In

If a customer comes back in because something failed that you repaired before, you can check it in as a **warranty job** directly from the Job Board — no need to create a brand new work order from scratch.

**How to start a warranty check-in:**

You have two ways to kick one off — use whichever is faster:

**Option 1 — from the job card (fastest):**
1. Find the original job in the Closed section at the bottom of the Job Board (tap the header to expand it)
2. **Long-press the job card** — hold for about a second
3. A confirmation sheet appears: "Check in for warranty work?"
4. Tap **Check In for Warranty**

**Option 2 — from inside the job detail:**
1. Open the original closed job by tapping its card
2. Scroll to the item that came back in — you'll see a red **"Check In for Warranty"** button below that item's card
3. Tap it, confirm in the sheet that appears

Both options do the same thing: ShopTracker creates a new work order for this customer, linked to the original job, with the cost locked at $0. It opens just like a normal job — you can see it on the board, and it'll go through the full repair flow (Checked In → In Progress → Tested → Complete → Close).

**What a warranty job looks like:**

Warranty jobs have a small **WARRANTY** badge on the gallery card so the whole team can see at a glance what came back in. Inside the job detail, there's a line in the header showing the original job number — tap it to jump to the original work order if you need to review what was done.

The $0 cost is locked in from the start. When the job reaches completion, the cost entry shows $0 and skips the manager approval step.

[screenshot: long-press confirmation sheet on a closed job card]

#### Warranty Flag — No Prior Job in the System

The warranty check-in flow above works great when the original job is already in ShopTracker. But sometimes it isn't — the repair was done before the app existed, it was handled on a paper form, or it was done at another location. In those cases you can't link to an original job, but you can still flag the new job as warranty work.

Create the work order like normal, then open the job detail view. Near the top you'll see a card with a red **Warranty** pill (the same pill style as the item-level Warranty pill — shield icon, red fill + white text when on, red outlined when off). Tap it to turn it on. That's it — the job is now flagged as warranty work, cost is locked at $0 for all items, the **WARRANTY** badge appears on the gallery card, and the tech sees it as warranty work. No link to an original job, but all the same protections.

If it's still a draft, the same Warranty pill shows up on the draft detail view. Flip it on there and it applies when you finalize.

**Post-check-in toggling:** You can toggle the job-level Warranty pill any time after check-in as long as at least one item is still active. This is useful when the customer calls back after drop-off to confirm the job is under warranty, or when you discover the equipment's repair history during inspection. Once every item on the job is **Closed** or **Totaled**, the pill locks — this prevents accidentally flipping warranty on a wrapped-up job and skewing revenue reports. If you need to correct warranty status on a fully-closed job, an admin can still do it by elevating admin access.

**What the tech station can't do:** Tech Station devices don't see the job-level Warranty pill — warranty is a Front Counter / Admin concern. Techs can still see the WARRANTY badge on the card and the "Warranty Job" line in the header, but they can't change the status.

**Warranty check-in jobs are still locked:** Jobs that were created through the **Check In for Warranty** flow (where the new job is linked to an original parent job) can't have their warranty status toggled from this pill. That parent link is intentional and shouldn't be broken — if you need to correct one of those, talk to an admin.

---

## Customers

The Customers view is a browsable list of all your customers with a detail screen showing their full job history. It's available on Front Counter and Admin devices via the sidebar.

### Customer List

Open the sidebar and tap **Customers** to see the customer list. Every customer in the system is listed alphabetically, showing their name, company (if any), phone number, and a badge with their total number of jobs.

Customers marked as **Tax Exempt** have an orange badge next to their name.

**Searching:** Type in the search bar at the top to filter by name, company, or phone number. The list filters as you type. Tap the **X** to clear the search.

**Adding a new customer:** On Front Counter and Admin devices, a **+** button appears in the top-right corner. Tap it to open the new customer form — same form used during job creation (name, phone, company, email, tax exempt). The new customer appears at the top of the list as soon as you save. This is useful for pre-registering customers or adding walk-ins who aren't ready to check in yet.

Pull down to refresh the list.

### Customer Detail

Tap any customer in the list to see their detail screen. At the top is a card with their contact info — phone number, company, email, and tax exempt status.

If a customer is tax exempt and has a certificate on file, you'll see a blue **View Certificate** link next to the orange "Tax Exempt" badge. Tap it to open the certificate image.

#### Contacts

Below the customer info card is a **Contacts** section. This is where you manage additional contacts for a customer — the shop manager, the owner, a driver, whoever else you might need to reach.

Each contact shows their name, role (if set), phone number (tappable — tap to call or text), and email (tappable — opens a new email). Primary contacts have a star next to their name.

**Adding a contact:** Tap the **Add** button (+ icon) next to the "Contacts" heading. Fill in:
- **Name** (required)
- **Phone** or **Email** (at least one required)
- **Role** — type freely or tap a quick-pick chip: Owner, Manager, Driver, Spouse, Accounts Payable, Other
- **Notes** — optional context like "Call after 5pm"
- **Primary Contact** toggle — marks this person as the main point of contact (star icon)

If you toggle Primary on and there's already a primary contact, the app asks to confirm the switch.

**Editing a contact:** Tap any contact row to open the edit form with the same fields.

**Deleting a contact:** Swipe left on a contact row and tap **Delete**. You'll be asked to confirm.

[screenshot: Customer detail with contacts section showing two contacts]

Below the contacts section, you'll see all of that customer's jobs split into two sections:

**Active Jobs** — any jobs that are still being worked on, shown as full cards with photos (same cards as the Job Board). If the customer has no active jobs, this section doesn't appear.

**Past Jobs** — closed and totaled jobs shown as compact rows with the job number, equipment summary (e.g., "Cylinder × 2 · Pump × 1"), date range (when it was created and when it was closed), item count, and status dots.

Tap any job — active or past — to open the full job detail view with all items, photos, notes, and history. Use the back arrow to return to the customer detail.

This is especially useful for warranty lookups ("didn't we just fix this customer's cylinder last month?") and getting context on repeat customers.

### Editing a Customer

Tap the **...** button in the top-right corner of any customer's detail screen and choose **Edit** to open the edit form. You can update:

- **Name** and **Company** — with the same smart swap button as the new customer form. At least one of Name or Company must be filled in — you can clear one as long as the other has a value.
- **Phone** and **Email**
- **Tax Exempt** toggle — turn on or off as needed
- **Contacts** — the same contacts list appears here. Add, edit, or delete contacts without leaving the edit form.

**Uploading a tax exemption certificate:** When Tax Exempt is toggled on, you'll see a certificate section. Tap **Upload Certificate** to choose a photo from your library. A preview appears once selected — tap the **×** to remove it if you picked the wrong one. The certificate uploads automatically when you tap **Save**. If a certificate is already on file, you'll see "Certificate on file" with a **Replace** option to swap it out.

**Toggling off Tax Exempt** automatically removes the certificate link from the customer's record.

Tap **Save** to apply your changes. Tap **Cancel** to discard them.

**Quick edit from Job Detail:** You can also edit a customer directly from a job's detail view — tap the **pencil icon** next to the customer name in the header card. This opens the same edit form, including the contacts section. Handy when you need to add a contact without navigating to the Customers list.

### Deleting a Customer

On Admin devices (or while admin-elevated), the **...** menu on a customer's detail screen includes **Delete Customer** in red.

Tap it and you'll see a confirmation dialog warning that this is permanent. Any jobs that were linked to this customer will keep their data (items, photos, notes) but lose the customer association. Contacts under this customer are deleted automatically.

This cannot be undone.

### Flagging a Customer

If a customer has been causing problems — warranty fraud, bringing in different equipment and claiming it's the same piece, slow pay, or anything else the shop needs to be aware of — you can flag them. A flagged customer gets a visible warning banner that shows up everywhere their name appears, so nobody at the counter or in the back is caught off guard.

**Setting a flag:** Open the customer's detail screen and tap the **Flag Customer** button (flag icon). You'll be asked to type a reason — be specific, because this is what everyone will see. Something like "Claims warranty on different cylinders" or "Owes balance on two previous jobs" is more useful than "Problem customer." Tap **Confirm** to set the flag.

Any device role can set a flag — Front Counter, Tech Station, or Admin. If a tech in the back notices something sketchy, they can flag the customer right from their station.

**What it looks like:** Once flagged, an amber warning banner appears at the top of the customer's detail screen showing the reason, who flagged them, and when. This same banner also shows up on every job detail view for that customer, on the Tech Station item detail, and during new job creation if someone selects that customer. On the Job Board, flagged customers' job cards show a small flag icon so Maria can spot them at a glance without opening the job.

The flag is informational — it doesn't block anything. You can still create jobs, check in warranty work, and process pickups for a flagged customer. It just makes sure everyone knows the deal.

**Removing a flag:** Only Admin devices can remove a flag. Open the customer's detail screen and tap **Remove Flag**, then confirm. The banner disappears from all views. The flag history is preserved in the system even after removal, so there's a record of what happened.

[screenshot: Customer detail with amber flag banner at top]

---

## Companies

The Companies view lets you browse and manage all companies in the system. It's available on Front Counter and Admin devices via the sidebar.

### Company List

Open the sidebar and tap **Companies** to see the company list. Every company is listed alphabetically, showing its name, phone number (if set), and a "Tax Exempt" badge if applicable.

**Searching:** Type in the search bar at the top to filter by name. The list filters as you type.

Pull down to refresh.

### Company Detail

Tap any company to see its detail screen:

- **Company info** — phone, email, tax exempt status, and notes
- **Customers** — all people linked to this company, shown as tappable rows. Tap a customer to see their full detail screen.
- **Job History** — all jobs across all customers under this company, sorted newest first. Each row shows job number, customer name, date, item count, and cost. Tap any job to see the full detail view.

**Editing a company:** Tap the **...** button in the top-right and choose **Edit** to update the company's name, phone, email, tax exempt status, or notes.

**Deleting a company (Admin only):** The **...** menu also includes **Delete Company** in red on Admin devices (or while admin-elevated). A confirmation dialog warns that this is permanent — linked customers and jobs keep their data but lose the company association. This cannot be undone.

### How Companies Work

Companies are created automatically during check-in. When someone types a new company name during job creation, a company record is created behind the scenes. There's no separate "Create Company" step.

Multiple customers (people) can belong to the same company. When a company is selected during check-in, the app shows suggestions for existing customers under that company — making repeat check-ins faster.

**Tax exempt status** flows from the company to all customers under it. If "ABC Construction" is tax exempt, every job checked in under that company inherits the tax exempt status automatically.

**Customer detail** screens show the company as a tappable link. Tap it to jump to the company detail view.

[screenshot: Company detail showing customers list and job history]

### Flagging a Company

If a company has a pattern of issues — multiple customers from the same outfit pulling warranty stunts, slow-paying across the board, or anything else worth tracking — you can flag the whole company. This works exactly like customer flags but at the company level.

**Setting a flag:** Open the company's detail screen and tap **Flag Company** (flag icon). Type a reason and confirm. Any device role can set a company flag.

**How it propagates:** When a company is flagged, the amber warning banner shows up on the company detail screen AND on every job for every customer under that company. If "Shady LLC" is flagged and three different drivers from Shady LLC come in on different days, Maria will see the flag warning on each of their jobs. The customer doesn't need to be individually flagged — the company flag covers everyone under it.

A customer can be flagged independently of their company. If both the customer AND their company are flagged, you'll see both banners (with their separate reasons) so nothing gets lost.

**Removing a flag:** Admin only. Tap **Remove Flag** on the company detail screen and confirm.

---

## Tech Station

The Tech Station iPad is the back shop's primary tool. It shows a queue of all items that need work — not grouped by job, but as individual items. Techs don't care that three cylinders came from the same customer; they care about the cylinder on the bench.

### Repair Queue

When you open the app on a Tech Station device, you see the **item queue** — a grid of cards showing all items that need work. The cards are sorted by priority: Disassembly items first (they need attention next), then In Progress items, then items waiting for a tech to grab, then tested items that need a cost entered.

Each card shows:

- **Item photo** — the top half of every card is a large square photo of the equipment. The photo has a colored **status dot** in the top-right corner and an **equipment type label** in the bottom-right corner, same as the Front Counter cards. If no photo has been taken yet, you'll see a gray placeholder.
- **Status label** — text below the photo showing the item's current stage (e.g., "Checked In", "In Progress", "Ready for Test")
- **Equipment type** (e.g., Cylinder, Pump, Hose)
- **Customer name**, **company name** (if applicable, shown below the customer name), **phone number** (tappable — tap to call or text), and **job number**
- **Assigned tech's name** — if someone has grabbed it
- **READY badge** — orange badge on items where repair is done and it's waiting on testing

Photos load in the background, so cards appear instantly and photos fill in a moment later.

Items with the READY badge also have a warm orange tint on the card so they stand out.

**On Fire items** — if the front counter has marked an item urgent, you'll see a **red border** around its photo tile and a **🔥 badge in the bottom-left corner**. On-fire items jump to the absolute top of the queue, above Ready for Test. Techs can't set or clear this flag — if you think something's urgent and it's not marked, or if something's marked on fire that shouldn't be anymore, tell the front counter.

**Waiting items** — items blocked on parts, seals, or approval have an **indigo border** and **⏳ badge**. They sink to the **bottom** of the queue so active work stays front and center. See ["Waiting" Flag (⏳) — Tech Station](#waiting-flag--tech-station) below for how to set and clear them.

Tap any card to open the item detail view with actions for whatever the item needs next.

**Flagged customers:** If the item belongs to a flagged customer or company, you'll see an amber warning banner at the top of the item detail view with the flag reason. Techs can also flag customers directly from the item detail if they notice something off — tap **Flag Customer** and enter a reason. Only admins can remove flags. See [Flagging a Customer](#flagging-a-customer) for the full rundown.

Pull down to refresh the queue. The grid adapts automatically when you rotate the iPad between landscape and portrait.

### Recently Completed Items

Below the active queue, you'll see a **"Completed · N"** row with a small chevron — that's where items go after they hit Complete or Closed. The number is how many items are in there. The section is **collapsed by default** so it stays out of the way of your active work.

Tap the row to expand it. The chevron rotates and a grid of completed item cards appears below. Cards in the Completed section are shown at a slightly lower opacity than active items so it's easy to see at a glance that they're done. They're sorted with the **most recently finished item at the top**.

You can still tap any completed card to open the item detail — useful when a customer comes back asking about a recent repair, or when you want to double-check what was done on something Maria already closed out.

The search bar searches across both the active queue and the Completed section, so typing a customer name or job number will pull matches from both. Status, tech, and reason filters only apply to the active queue — the Completed section ignores those.

Tap the row again to collapse it back down when you're done.

### Searching and Filtering the Queue

The Tech Station has the same **search bar** and **filter button** as the Front Counter. On iPad, they're in the toolbar. On iPhone, they appear just below the navigation bar.

**Searching:** Tap the search bar and type to filter the queue in real time. You can search by:

- Equipment type (e.g., "Cylinder")
- Customer name, company name, or job number
- Tech name (e.g., "Tony")
- Machine type or item description
- Service reason (e.g., "Seal")

**Filtering:** Tap the filter button to open a filter sheet with pickers for Equipment Type, Status (Checked In, Disassembly, In Progress, Tested), Assigned Tech, Machine Type (if enabled), and Reason for Service (multi-select).

The **Assigned Tech** picker shows every tech who currently has items in the queue, sorted alphabetically, plus an "Unassigned" option that filters to items no one has grabbed yet. This is handy when a supervisor wants to check a specific tech's workload, or when someone is covering for a colleague and wants to see just that person's items. The Assigned Tech filter is only available on the Tech Station — it does not appear on the Front Counter's filter sheet.

Active filters show as removable chips below the toolbar, same as the Front Counter. Tap **X** on a chip to remove it, or **Clear All** to reset everything.

If nothing matches, you'll see "No Matching Items" instead of the grid.

### Scanning a QR Tag (Tech Station)

Tap the **scan icon** in the toolbar, point the camera at the sticker on your bench equipment, and the app jumps straight to that item's detail view. Full details — including what to do if a scan fails or a sticker needs reprinting — are in the **Equipment Tags** section near the end of this manual.

### Adding Photos from the Tech Station

When you open an item detail, you'll see a grid of photo thumbnails at the top of the info card (if any photos exist) along with **Camera** and **Library** buttons. Techs can add photos at any point during the repair — before starting, during disassembly, after the fix, or whenever something is worth documenting. Tapping **Camera** opens the continuous camera: tap the shutter as many times as you need, watch the thumbnails appear at the bottom of the screen, then tap **Done** when you're finished. No need to reopen the camera between shots.

Tap any thumbnail to view the photo full-screen. If the item has multiple photos, **swipe left and right** to flip through all of them — a counter at the bottom shows your position (e.g., "2 / 5"). Tap the photo, tap the X, or drag down to close. Photos with markup show a small blue pencil badge on their thumbnail.

If you snap a bad photo while the camera is open, tap the **X** on its thumbnail in the camera strip to remove it right away. Once a photo is uploaded, only an admin can delete it (see "Deleting Photos" in the Front Counter section above).

To change which photo is the hero (the big square at the top), **press and hold** on any thumbnail and tap **Make Hero Image**. See "Reordering Photos (Make Hero Image)" in the Front Counter section above for full details.

#### Marking Up Photos (Tech Station)

Techs can mark up photos the same way the front counter does — tap a thumbnail to go full-screen, then tap **Markup** to open the Apple pencil editor. This is useful for writing the price on a photo, circling what was repaired, or noting anything the front counter should see.

The full markup toolbar is available: pens, markers, pencils, erasers, ruler, and all colors. Tap **Save** when done. Previous markup strokes are preserved for re-editing. See "Marking Up Photos" in the Front Counter section above for the full details on how markup, revert, and re-editing work.

### Adding Notes from the Tech Station

When you open an item detail from the tech queue, you'll see a **Notes** card between the item info and the test history. This works the same as on the front counter — type a note, tap the send arrow, and it's saved with your name and timestamp.

Use notes to document what you found during disassembly, anything unusual about the repair, or messages for the front counter ("customer needs to approve cost before we proceed"). Notes from both the front counter and the tech station show up in the same timeline, so everyone stays on the same page.

### Working on Warranty Items

When an item came back in because something failed from a previous repair, it shows up in your queue with a red **WARRANTY** badge in the item header. These are handled the same as any other item — grab it, repair it, test it — but there are a couple of things worth knowing.

#### The Previous Repair Card

When you open a warranty item, you'll see a red **"Previous Repair"** card near the top of the detail view, just below the header. This gives you context on what was done last time:

- The **original job number** so you can look it up if needed
- **Photos from the original repair** — the same photos the tech took when this item was first fixed. These load in a horizontal scroll strip so you can swipe through them.
- **Issues found** — the repair checklist items the previous tech checked off (Seal, Wiper, etc.)
- A **PASSED / FAILED** badge showing how the original test went

This is there so you're not going in blind. If the original tech noted something unusual or took a photo of the damage, you can see it right here without having to hunt down the old job.

#### Testing a Warranty Item

When you tap **Tested** and mark it as passed, the app automatically closes out the cost at $0 (no cost entry step — it's already locked). You'll see a brief **"Warranty Complete!"** confirmation and then the app takes you back to the queue. There's nothing extra to do.

If the warranty item *fails* the test, it goes back to In Progress for another repair round, same as any other item.

**Admin override:** If an admin is logged in and needs to charge for the warranty work (unusual, but it happens), the normal **Enter Cost** button appears instead of the auto-complete. The admin can enter a cost and go through the standard approval flow.

### No Warranty Flag (Tech Station)

If a repair doesn't carry a warranty — say, the customer's cylinder was drilled into, or the equipment came in already damaged beyond normal wear — you can flag it right from the tech detail view. Tapping the flag also moves the item to **Complete** in one shot, so you don't have to click through the tester / cost / approval steps separately. It's the fast lane for "this is done, no warranty on it, ship it to the front counter."

Look for the amber-orange **No Warranty on This Item** pill on the item detail card. The pill only appears on items that have been checked in — it's hidden during the intake stage, so you'll see it from **In Progress** onwards through **Tested** and **Complete**.

**Setting the flag (first time):**

1. Tap the amber-orange **No Warranty on This Item** pill.
2. A **Mark as No Warranty** sheet slides up with a cost field (or Parts + Labor fields if parts/labor split is enabled in admin settings). Underneath the title you'll see "Optionally enter a cost before sending to Front Counter." — the cost field is optional, you can leave it blank if you don't know the price yet.
3. Tap **Confirm**. If you entered a cost, you'll see the same **"Was that cost approved by a manager?"** popup that shows up on normal priced jobs. Tap **Yes** to finish, or **No — I'll confirm first** to back out without saving anything. If you left the cost blank (or entered $0), the popup is skipped entirely.
4. The item moves to **Complete** with the No Warranty flag on, and you'll see the amber pill fill in solid with white text.

**Editing the cost later (long-press):**

Change your mind on the price? Long-press (press and hold for about half a second) the amber pill on an item that's already flagged No Warranty. The **Edit No Warranty Cost** sheet opens with the current values pre-filled. Update them, tap **Save**, and you'll get the manager approval popup again if the new cost is non-zero. The item's status is **not** changed by this flow — it stays wherever it was, so this is safe to use even after an item has been closed.

**What the team sees:**

When the flag is on, you'll also see a dark **NO WARRANTY** pill next to the item reference in the header, and the front counter will see the same amber pill read-only on their side (unless an admin has turned on the Front Counter No Warranty setting — see the Admin section). The board tile shows a brown **COMPLETE • NO WARRANTY** badge instead of the usual green **COMPLETE** badge so everyone on the team can tell at a glance which items are going out without warranty.

If a tech on another station flagged the item first, you'll see the pill already on when you open the item. Long-press will still let you edit the cost.

### Mark Complete (No Warranty)

This is the other way to mark an item as No Warranty — same end result as tapping the pill, just in a different spot so you can find it from the main action button row.

Look for the brown button labelled **Mark Complete (No Warranty)** in the item action area — it appears on items that are **In Progress**, **Tested**, or already at **Complete** (as long as they aren't already flagged no-warranty). Tapping it opens the same **Mark as No Warranty** cost sheet the pill does. Optionally enter a cost, tap **Confirm**, and if the cost is non-zero you'll see the **"Was that cost approved by a manager?"** popup.

The net effect is identical to tapping the pill: the item flips to **Complete**, the No Warranty flag turns on, the cost (if any) is recorded, and the board tile gets the brown **COMPLETE • NO WARRANTY** badge. Use whichever entry point is closer to your thumb.

Any role can use this — it's a workflow shortcut, not a permission check.

### "Waiting" Flag (⏳) — Tech Station

When work on an item is blocked — you're waiting on parts, seals, customer approval, or an outside service — you can mark it **Waiting**. The item stays at its current status (Disassembly or In Progress), but gets an indigo visual treatment and sinks to the bottom of the queue so it's out of the way of active work.

**Marking an item as Waiting:**

1. Open the item detail view from the queue.
2. Tap the **Waiting** button (indigo, hourglass icon) in the action buttons area. It appears on any Disassembly or In Progress item that isn't already waiting.
3. A sheet pops up asking for a **reason** (dropdown — Waiting on Parts, Waiting on Seals, Waiting on Customer Approval, Waiting on Outside Service, or **Other**) and optional **notes** (free text, e.g., "ETA Friday, ordered from Parker"). If you pick **Other**, a required text field appears — describe what you're waiting on before you can confirm.
4. Pick a reason, optionally add notes, and tap **Confirm**.

The item immediately gets:
- An **indigo border** around the photo tile and an **⏳ badge in the bottom-left corner** on the queue card
- An **⏳ WAITING** capsule in the card header row
- An **indigo info card** at the top of the item detail showing the reason and notes
- The **Done button is disabled** — you can't mark repair as done while the item is waiting
- If the item was already **Ready for Testing** (repair done, waiting on a tester), you'll see **both** an orange **READY FOR TESTING** badge and an indigo **WAITING** badge stacked on the photo tile. This tells everyone "repair is done but we can't test yet."

**Where it sorts:** Waiting items drop to the **bottom** of the queue, below intake items and tested items — even if repair is done. A "Ready for Testing + Waiting" item stays at the bottom because there's no point putting it at the top of the test queue when you can't actually test it. If an item is both On Fire and Waiting (rare, but possible), On Fire wins — it stays at the top.

**Resuming work (clearing the flag):**

When the parts arrive or the hold is resolved:

1. Open the item detail view.
2. Tap the **Resume Work** button (green, play icon). It replaces the Waiting button when the flag is set.
3. A confirmation alert shows the reason text ("This will clear the Waiting flag (Waiting on Parts) and return the item to active repair.").
4. Tap **Resume**. The item returns to its normal position in the queue and the Done button re-enables.

**Filtering:** The filter sheet has a **"Show Waiting Items Only"** toggle. Flip it on to see just the blocked items. A "Waiting Only" chip appears below the toolbar.

**Who can set and clear:** Tech Station and Admin only. Front Counter sees the flag and its reason but can't change it.

**Important:**
- Both "Marked Waiting" and "Resumed Work" events appear in the item's **Repair History** timeline, so the front counter can see exactly when work was paused and why.
- The waiting flag works offline — set it even if the Wi-Fi is down and it'll sync when you're back.
- Admin can also manage the list of waiting reasons via **Admin Settings → Manage Lists → Waiting**.

### Editing Item Info from the Tech Station

When you open an item detail, you may see a small blue **Edit** link in the top-right corner of the item info card. This lets you change the intake fields — equipment type, machine type, service reasons, and description — without going back to the front counter.

The Edit button only appears when the item is in **Checked In** status (before anyone grabs it). Once the item is grabbed (Disassembly or In Progress), the intake fields lock and the Edit link disappears. An admin can still edit locked fields by elevating admin access.

Photos and notes are always editable regardless of item status (see "Adding Photos" and "Adding Notes" sections).

### Grabbing an Item

When a new item shows up in "Waiting for Tech," any tech can grab it — and multiple techs can grab it together:

1. Tap the item card to open it
2. Tap the **Grab** button (yellow, big and easy to hit)
3. A picker appears showing all available techs — tap one or more names to select them (checkmarks appear next to selected names)
4. A **"Grab"** (or **"Grab with 2 techs"**) button appears at the bottom — tap it to confirm
5. You'll see a quick **"Grabbed!"** confirmation, then the app automatically takes you back to the queue

**The first tech you tap becomes the lead tech.** If you're grabbing solo, just tap your name and hit Grab. If two techs are working together, tap both names — the order you tap them matters (first tapped = lead).

When multiple techs grab an item together, the item detail shows "Assigned to Carlos and Nate" and the Repair History shows a single "Grabbed by Carlos and Nate" event.

Whoever grabs it first gets it. If techs need to change later, see "Managing Techs" below.

**After grabbing, the item enters Disassembly status** — not In Progress. You need to complete the disassembly checklist before you can start the actual repair. See "Disassembly" below.

### Disassembly

After you grab an item, it goes into **Disassembly** status. The card tile shows an orange/yellow gradient **DISASSEMBLY** badge. When you open the item, instead of the normal repair checklist, you'll see a large orange **Disassembly** button.

Tap the button to open the **Disassembly Sheet**. It has two sections:

**Oil Sample:**
- Pick the oil condition: **Clean** or **Dirty** (segmented control)
- Optional notes (e.g., "metallic particles visible")
- Take photos of the oil sample — at least one photo is required when the section is not skipped
- Select who performed the sample from the employee list

**Disassembly Photos:**
- Take photos of the disassembled equipment before you start repairs
- Use the camera or pick from the photo library

**Skipping sections:** If the admin hasn't required a section (see Admin Settings → Shop Settings → Disassembly Step), you'll see a **Skip** button in the section header. Tap it to collapse the section to a "Skipped" row with an **Undo** button in case you change your mind.

**Two ways to finish:**

- **Save** (top-right nav bar) — Uploads your photos and oil sample, then closes the sheet. The item **stays in Disassembly** so you can come back and add more photos or start the repair later. When you reopen the sheet, you don't need to re-enter anything — previously uploaded photos and oil samples are already counted as complete.
- **Save & Start Repair** (green button at the bottom of the form) — Uploads everything AND moves the item to **In Progress**. The normal repair checklist becomes visible and you can start checking off work. Use this when you're done with disassembly and ready to repair.

**Canceling:** Tap **Cancel** at any time to close the sheet without saving. The item stays in Disassembly — nothing is lost.

### Managing Techs on an Item

Once an item is In Progress, you can add or remove techs at any time using the **Manage Techs** button (purple, with a people icon). This replaces the old separate "Reassign" and "Add Tech" buttons — everything is in one place now.

1. Open the item from the queue
2. Tap **Manage Techs**
3. A picker appears with all available techs — techs currently on the item are already checked
4. Tap names to add (check) or remove (uncheck) techs
5. The **"Update"** button at the bottom activates when you've made changes — tap it to confirm

All changes show up in the Repair History timeline — added techs show "[Name] added" and removed techs show "[Name] removed." If you remove the lead tech, the first remaining tech is automatically promoted.

Manage Techs is available on Tech Station and Admin devices, on any Disassembly or In Progress item.

### Repair Checklist

When you open an In Progress item, you'll see a **Repair Checklist** section with green pill-shaped buttons for each type of repair work: Wiper, Seal, Buffer Seal, Wear Bands, U Seal, Epoxy, Welding, Rod Damage, Oil Sample, Dented, and Other.

#### Materials Photo Required

**You need to take a photo of the materials used for the repair before you can mark the item Done.** This is so there's always a visual record of what parts and materials went into the job.

If the item doesn't have a materials photo yet, you'll see an orange **"Photo Required"** card above the Repair Checklist header with two buttons: a blue **"Camera"** button and a gray **"Library"** button. You can still tap checklist pills — the photo and the checklist can be done in any order.

- **Camera** — opens the camera so you can take a photo right now
- **Library** — opens your photo library so you can pick a photo you already took (e.g., from your camera roll)

Either way, the photo uploads and the orange card disappears.

The materials photo shows up in the item's photo grid like any other photo — there's no special badge or indicator. If you come back to the item later and a materials photo already exists, the prompt won't appear.

**Tap each pill to check off what you actually did.** Selected pills turn green; unselected ones stay outlined. You can tap a green pill again to uncheck it if you made a mistake.

If you select **Other**, a text field appears where you can describe the work that doesn't fit the standard categories.

**You must check at least one item on the repair checklist AND have a materials photo before you can tap Done.** You can do these in either order — check off work first and photograph materials later, or vice versa. If nothing is checked, the Done button is grayed out and you'll see an orange warning: "Check at least one before marking Done." This is so there's always a record of what was actually done to the item — same as the paper checklist Tony fills out today.

Your selections save to the server immediately as you tap them — no need to hit a save button.

After the item is marked Done or Tested, the checklist stays visible as a read-only record of what was done.

If an item fails a test and comes back for another round, the checklist resets to empty for the new round. You'll see a red **Round 2** badge next to the "Repair Checklist" header so you know which round you're on. The previous round's checklist is preserved in the history card below (see "Previous Round Checklists").

### Marking Repair as Done

Once you've finished repairing an item and checked off what you did on the repair checklist:

1. Open the item from the queue
2. Make sure you've taken a **Materials Photo** and checked at least one item on the **Repair Checklist** (see above)
3. Tap the **Done** button (green)
4. You'll see a **"Marked Done!"** confirmation, then the app takes you back to the queue
5. The item stays in the "In Progress" section but now shows an orange **READY** badge — this tells testers it's waiting on them

The repair end time is logged automatically.

### Testing an Item

Items with the READY badge need to be tested before they can leave the shop:

1. Open the item
2. Tap the **Tested** button (orange)
3. A picker appears — tap the name of whoever tested it (authorized testers only)
4. A **Pass/Fail sheet** appears with two big buttons: **PASSED** and **FAILED**

**If PASSED:**

- **Regular items:** The item moves to **Tested** status and the **Enter Cost** sheet opens automatically — no extra tap needed. Just type the cost and submit. If the tester dismisses the cost sheet or walks away without entering cost, the app will automatically return to the queue after the inactivity timeout (see "Auto-Return to Queue" below). The **Enter Cost** button stays visible on the item if they need to come back to it.
- **Warranty items:** The cost is already locked at $0, so there's no cost entry step. The app shows a brief **"Warranty Complete!"** confirmation and immediately returns to the queue. Done.

**If FAILED:**

The item goes back to **In Progress** and a new repair round begins. The same tech stays assigned — it's their job to fix whatever failed. No extra taps, no "are you sure?" — it just goes straight back. The app shows a brief "Sent Back — Round 2" confirmation and returns to the queue. The tech will see the item back in their queue with a red **Rd 2** badge, a fresh empty repair checklist, and the previous round's checklist preserved in the history card (see "Previous Round Checklists" below).

An item can fail and loop back as many times as needed. Each round is tracked separately.

If a different tech needs to take over after a failed test, use the **Manage Techs** button on the item to swap out who's assigned (see "Managing Techs on an Item" above).

### Oil Sample

You can record an oil sample on any item that's at the **Ready for Test** or **Tested** stage. This is optional — not every item needs one. But when you do record one, at least one photo is required.

1. Open the item
2. Tap the **Oil Sample** button (blue)
3. Pick the condition: **Clean** or **Dirty**
4. Add any notes in the text field (optional)
5. **Take at least one photo** — below the notes field you'll see **Camera** and **Library** buttons, same as the photo buttons used during intake. Tap Camera to snap a picture of the oil sample, or Library to pick one from the device. You can add multiple photos — each one appears as a thumbnail with an **X** to remove it if you change your mind. The Submit button stays disabled until you add a photo.
6. Select who performed the sample
7. Tap **Submit**

Photos upload automatically when you submit. Oil samples (with photos) show up in the Test & Sample History card on the item detail (see below). You can record multiple oil samples on the same item if needed.

### Repair History

Below the Notes card on the item detail, there's a **Repair History** card — a chronological timeline of everything that's happened to the item, in order. This is the same timeline Maria sees on the Front Counter, so both sides of the shop are always looking at the same story.

The timeline includes:

- **Tech assignment** — who grabbed it and when
- **Repair rounds** — each round's completed checklist items (Wiper, Seal, etc.). If the item failed a test and went back for another round, you'll see "Round 1: ..." and "Round 2: ..." entries separately, so the history of what was done in each round is always clear
- **Test results** — PASSED or FAILED with who tested it and when
- **Oil samples** — Clean or Dirty, who performed it, when, and any notes
- **Marked Waiting / Resumed Work** — if the item was flagged as waiting, the timeline shows when it was set (with the reason and notes) and when work resumed. Only the most recent waiting cycle is shown.
- **Customer Contacted** — on Totaled items, shows the contact outcome and timestamp after the "Customer Contacted" action was submitted
- **Cost** — total price with parts/labor/tax breakdown if applicable, plus manager approval status

This card only appears when there's something to show — brand-new items that haven't been touched yet won't have it.

On the old system, Tony had to flip through paper to see what was done in a previous round. Now it's right there on the screen.

#### Test & Sample History (Detail Sheet)

Below the Repair History card (or below the timeline in the right column on iPad), you'll see a **Test & Sample History** row if the item has any test attempts or oil samples. It shows the total count in a badge.

Tap it to open a sheet with the full detail — every test and oil sample in order, including:

- Test results with pass/fail, tester name, and timestamp
- Oil samples with condition (Clean/Dirty), performer, notes in italics, and photo thumbnails

This is handy when you need to see the full picture — the Repair History timeline only shows a quick summary per entry. Tap **Done** to close the sheet.

### Entering Cost

After testing, the item needs a cost before it can go back to the front counter. The cost entry sheet opens automatically right after a test passes — you don't need to tap anything extra. If you dismissed it or came back later:

1. Open the tested item
2. Tap **Enter Cost** (green)
3. Enter the cost — how this looks depends on your shop settings:
   - **Standard mode (default):** One field — type the total dollar amount
   - **Parts + Labor mode:** Two fields — **Parts ($)** and **Labor ($)**. The total calculates automatically as you type.
4. If the shop has **Sales Tax** enabled, you'll see a **"Taxable"** (or **"Taxable Parts"** in Parts + Labor mode) toggle. Turn it on if this item's parts are subject to sales tax. The sheet updates to show Subtotal, Tax, and Total so you can confirm the amount before submitting.
5. Tap **Submit**
6. You'll see a prompt: "Was that cost approved by a manager?" — tap **Yes** if a manager signed off, or **No** to go back and confirm first
7. A **Zone Assignment** modal appears — tap **Zone 1 (Front)** or **Zone 2 (Back)** to record where the physical item has been placed
8. You'll see a quick confirmation and the app takes you back to the queue

The zone tells the front counter exactly where to find the item when the customer comes to pick up. This step is required — you can't skip it.

For items with $0 cost, the manager approval step is skipped automatically, but zone assignment still fires.

**Where the zone shows up:**
- A small **Z1 (Front)** (blue) or **Z2 (Back)** (purple) badge appears on the item header in the detail view and on the job card in the Front Counter board
- The repair timeline shows "Zone 1 (Front) · assigned by [name]" with a timestamp

**Reassigning a zone (Admin only):** If an item gets moved after the fact, an admin can tap the zone badge on the item detail view to open the zone picker and reassign it.

*(Parts + Labor mode and Sales Tax are turned on and off by an admin in Admin Settings → Shop Settings.)*

### Totaling an Item

If an item is unfixable:

1. Open the item
2. Tap the **Totaled** button (black in light mode, white in dark mode)
3. Confirm — the item is now marked Totaled and shows a black TOTALED banner on the job card

**Adding a diagnostic cost (optional):** After marking an item Totaled, you'll see an **"Add Cost"** button. Tap it to enter the diagnostic cost — the same cost entry form you use for normal items. If the cost is more than $0, you'll see the manager approval prompt. If there's no charge, you can skip this entirely — cost entry is not required.

The item stays in Totaled status after cost entry (it does NOT move to Complete). The Front Counter handles closing Totaled items through the "Customer Contacted" flow.

### About the Action Buttons

All action buttons on the Tech Station (Grab, Done, Tested, Reassign, Enter Cost, Totaled, Close) are intentionally large. They're designed so techs can tap them quickly without fiddling around, even with dirty or gloved hands. On iPad, the buttons sit side by side in a row. On iPhone (used by admins), the buttons stack vertically and stretch full-width so they're still easy to tap on the smaller screen. After any "walk-away" action (anything where you're done with that item for now), the app shows a brief confirmation and automatically returns you to the repair queue.

### Auto-Return to Queue

If someone opens an item detail and walks away without doing anything for 2 minutes, the app automatically returns to the repair queue. This way the Tech Station iPad is always showing the queue when no one's actively using it — the next person who walks up sees the full list of items, not whatever the last tech was looking at.

The timer starts when you open an item. If you're actively working on the item (tapping Grab, checking repair items, entering cost), those actions either dismiss the view automatically or keep you engaged well within the timeout window. The timer is just a safety net for when someone walks away mid-screen.

The timeout is configurable by an admin (default is 2 minutes). Setting it to 0 disables it entirely.

### Role Switcher (Debug / TestFlight)

The role switcher is a developer tool for switching between Front Counter, Tech Station, and Admin views without resetting the device. It only appears in debug and TestFlight builds — it won't be in the App Store version.

**Enabling it:** Open the sidebar, scroll to the **Developer** section at the bottom, and tap the **Role Switcher** toggle. You'll be prompted to enter an admin PIN. Once confirmed, a small purple ladybug button appears in the bottom-left corner of every screen.

**Using it:** Tap the ladybug button to expand a menu showing the three device roles. Tap any role to switch to it instantly. A checkmark shows whichever role is currently active.

**Disabling it:** Flip the toggle back off in the sidebar — no PIN required to turn it off.

The toggle state persists across launches, so you don't have to re-enter your PIN every time you open the app. Only the initial enable requires a PIN.

---

## Admin

*This section will be filled in as Admin features are built.*

### Employee Management

Employee management is where you add, edit, and deactivate the people who use ShopTracker.

**Getting there:** Open Admin Settings and tap **Employees** under the "Shop" section.

#### Viewing Employees

You'll see a list of all active employees, each showing their name and colored capability badges for what they can do:

- **Admin** (purple) — full access to settings and admin features
- **Grab** (blue) — can be the lead tech on a job
- **Assist** (cyan) — can be added as an additional tech on a job
- **Test** (orange) — can appear in the tester picker
- **Oil Sample** (green) — can appear in the oil sample "Performed By" picker
- **FC** (indigo) — Front Counter staff

Admin employees also show a PIN status badge — green **"PIN Set"** if they have a PIN configured, or gray **"No PIN"** if they still need to set one up. Inactive employees appear in a separate section at the bottom with dimmed badges.

Pull down to refresh the list.

#### Adding an Employee

1. Tap the **+** button in the top right corner
2. Enter the employee's **name**
3. Turn on the **capabilities** this person needs:
   - **Can Grab Jobs** — they'll show up in the Grab picker as a lead tech
   - **Can Assist on Jobs** — they'll show up in the "Manage Techs" picker as an additional tech (lead techs can also assist, so you don't need both)
   - **Can Test** — they'll show up in the tester picker when marking items as tested
   - **Can Do Oil Samples** — they'll show up in the "Performed By" picker on oil samples
   - **Front Counter** — marks them as Front Counter staff
4. If this person needs admin access, turn on **Admin Access** in the Admin section below. They'll need a PIN.
5. Tap **Add**

The new employee will immediately appear in the pickers that match their capabilities. For example, if you only turn on "Can Assist" and "Can Do Oil Samples," they'll show up in the Manage Techs and oil sample pickers but never in the Grab or Testing pickers.

#### Editing an Employee

Tap any active employee in the list to open their edit form. You can change their name or toggle any of their capabilities on or off. Tap **Save** when done. Changes take effect immediately — if you turn off "Can Grab Jobs," that person disappears from the Grab picker right away.

#### Setting Up an Admin's PIN

If a new admin hasn't set up their PIN yet (they'll have a gray **No PIN** badge), another admin can kick off the setup for them:

1. Long-press the gray **No PIN** badge next to the admin's name
2. Enter your own admin PIN to authorize
3. Create and confirm a PIN for the new admin (4-8 digits)

The new admin can change their PIN later through the same process, or by having their PIN reset first (see below).

#### Resetting an Admin's PIN

If an admin forgets their PIN, another admin can reset it:

1. Swipe left on the admin employee's name in the list
2. Tap the orange **Reset PIN** button
3. Confirm in the popup

This clears their PIN entirely. The next time that person needs admin access, they'll use the **"Don't have a PIN yet?"** option on the PIN entry screen to set up a new one, or another admin can set it up for them by long-pressing the gray **No PIN** badge (see above). The resetting admin never sees or chooses the other person's PIN — it's always self-service.

#### Deactivating an Employee

If someone leaves the shop or no longer needs access:

1. Swipe left on their name in the employee list
2. Tap **Deactivate**
3. Confirm in the popup

The employee disappears from all pickers (they won't show up when assigning techs or testers) but their name still appears on any jobs, tests, or repairs they were involved in. Nothing is deleted — history stays intact.

#### Reactivating an Employee

If someone comes back or was deactivated by mistake, scroll down to the **Inactive** section and tap the **Reactivate** button next to their name. They'll immediately reappear in all pickers.

### Shop Settings

Shop Settings is where you control the optional fields and cost entry behavior for the whole shop. Changes take effect immediately — no save button.

**Getting there:** Open Admin Settings and tap **Shop Settings** under the "Shop" section.

#### Machine Type Field

The **Show Machine Type Field** toggle adds a "Machine Type" field to the job intake form — what the equipment came off of (Forklift, Excavator, Skid Steer, etc.).

- **Off by default.** Turn it on if your shop wants to track what machine the equipment belongs to.
- The options in the Machine Type dropdown are managed under **Manage Lists** (see below).
- When Machine Type is on, you can also make it **required** using the Required Fields toggles further down.

#### Machine Brand Field

The **Show Machine Brand Field** toggle adds a "Machine Brand" field to the job intake form — who made the machine the equipment came off of (Caterpillar, John Deere, Komatsu, etc.).

- **Off by default.** Turn it on if your shop wants to record the machine manufacturer at intake.
- The options in the Machine Brand dropdown are managed under **Manage Lists** (see below).
- When Machine Brand is on, you can also make it **required** using the Required Fields toggles further down.

#### Color Field

The **Show Color Field** toggle adds a color field to the job intake form for visual identification.

- **Off by default.** Turn it on if Maria needs to describe the equipment's color at intake.
- When Color is on, a second toggle — **Color Required** — appears. This controls whether techs and Maria *must* fill it in or whether it's just optional.
- If you turn Color off, Color Required turns off automatically.

#### Cost Entry — Parts + Labor Split

The **Parts + Labor Split** toggle changes how techs enter cost on completed items.

- **Off (default):** Techs see one field — "Total Cost" — and enter a single dollar amount.
- **On:** Techs see two separate fields — **Parts ($)** and **Labor ($)**. The sheet shows a running total as they type. Both get saved individually so you can pull them apart in reports later.

This setting affects the cost entry sheet for all items in the shop immediately after you toggle it.

#### Sales Tax

The **Charge Tax on Parts** toggle enables sales tax collection for the shop. When this is on:

- A **tax rate field** appears below the toggle. Type your local sales tax percentage (e.g., `7.5` for 7.5%). The rate saves automatically when you dismiss the keyboard.
- When techs enter cost on an item, a **"Taxable" toggle** appears in the cost entry sheet. They turn it on if that item's parts are subject to sales tax.
- The cost entry sheet shows a live breakdown: **Subtotal → Tax → Total** so the tech can see exactly what the customer will be charged before submitting.
- In Parts + Labor mode, tax is calculated on the parts amount only (labor is not taxed).
- In standard mode (single total), tax is calculated on the full cost amount.
- The tax amount is saved on the item alongside the cost and can be pulled into reports later.

**Off by default.** If your shop doesn't charge sales tax, leave this off and the taxable toggle won't appear anywhere in the cost entry flow.

#### Front Counter: No Warranty

The **Front Counter: No Warranty** toggle controls who can mark items as No Warranty.

- **Off (default):** Only Tech Station and Admin devices can see and use the **No Warranty on This Item** pill. The pill is completely hidden on Front Counter devices — even on items a tech has already flagged. This is the safer default: the call about whether a repair carries a warranty usually happens during the actual repair work, not at drop-off, so Tech Station is the natural place for it.
- **On:** Front Counter gets the same rules as Tech Station. Maria will see the amber-orange **No Warranty on This Item** pill on any item that's In Progress, Tested, or Complete, and she can tap it to set or clear the flag herself.

Flip this on if Maria is the one having the warranty conversation with the customer at check-in or pickup and needs to flag the item without waiting on a tech. Flip it back off if the shop wants to keep the decision tech-side.

This toggle only affects who can *set* the flag. The brown **COMPLETE • NO WARRANTY** badge on completed job tiles is visible to everyone no matter how this setting is configured.

#### Disassembly Step

These toggles control what techs must complete in the Disassembly Sheet before they can start repairs on a grabbed item.

- **Require Oil Sample** — Off by default. When on, techs must complete the oil sample section (select an employee, take at least one photo) before submitting. When off, a **Skip** button appears that lets them bypass the section.
- **Require Disassembly Photos** — Off by default. When on, techs must take at least one disassembly photo before submitting. When off, a **Skip** button appears.

Start with both off and flip them on once techs are comfortable with the disassembly flow. The sections are always *available* — these toggles just control whether they're *required* or *skippable*.

#### Required Fields

Required fields block job creation until they're filled in. Toggle each field on or off:

- **Customer** — on by default
- **Equipment Type** — on by default
- **Reason for Service** — off by default
- **Description** — off by default
- **Photos** — off by default
- **Machine Type** — only visible when the Machine Type field is turned on
- **Machine Brand** — only visible when the Machine Brand field is turned on
- **Color** — only visible when the Color field is turned on

If a required field is missing when Maria tries to create a job, the button stays on "Save as Draft" instead of "Create Work Order." The same enforcement applies when finalizing an existing draft — the Finalize button stays disabled until all required fields are filled in on every item. On drafts, items missing required fields are highlighted with an orange background and a "Complete Item Info" banner.

#### Category Labels

The app uses two billing categories throughout: one for labor (repairs that come out of the back), and one for the hose side of the shop (hoses, fittings, adapters, seals — the stuff that comes out of the front). Both of those labels are configurable here, because — it turns out — what things are *called* is apparently a deeply personal decision that is subject to change at any time and without notice.

Whatever you type into these fields shows up everywhere on the operator side: job cards, cost breakdowns, intake sheets, help text, settings footers, all of it. **Reports are the one exception** — those keep fixed "Labor" and "Hose" terminology no matter what you rename things to, so Jamie's bookkeeping doesn't break every time somebody decides they prefer "Service" or "Parts Counter" this quarter. The underlying data doesn't change either (a hose assembly is still a hose assembly, regardless of what we're calling it this week), so reports stay accurate in both label *and* content.

To update a label, just type the new value and save (tap away from the field, or hit return). It takes effect immediately. No developers were harmed in the making of this feature (this time).

### Manage Lists

Manage Lists is where you control the dropdown options used throughout the app. Accessible from Admin Settings → **Manage Lists** under the "Shop" section.

There are six lists you can manage:

- **Equipment** — what the item IS (Cylinder, Pump, Hose, Other...)
- **Mach Type** — what it came off of (Forklift, Excavator, Skid Steer...) — only shows up in job intake if Machine Type is turned on in Shop Settings
- **Brand** — who made the machine (Caterpillar, John Deere, Komatsu...) — only shows up in job intake if Machine Brand is turned on in Shop Settings
- **Service** — the Reason for Service pills on the intake form
- **Issues** — the repair checklist items techs check off when marking work done
- **Waiting** — the reasons shown in the Waiting flag picker on Tech Station (e.g., "Waiting on Parts", "Waiting on Seals"). Comes pre-seeded with 4 defaults

Switch between lists using the tabs at the top of the screen.

#### Adding an Option

1. Tap **+** in the top right corner
2. Type the option name and tap **Add**

It appears at the bottom of the list immediately and is active by default.

#### Renaming an Option

Tap the **pencil icon** next to any option to rename it. The new name applies going forward — existing jobs keep the original name they were created with.

#### Hiding an Option

Each option has an active toggle on the right. Turn it off to hide the option from the intake form and checklists without deleting it.

Hidden options don't show up for new jobs, but they still appear on any existing jobs that used them — your history stays intact.

#### Reordering

Tap the **Edit** button in the top right corner to enter reorder mode, then drag options into the order you want. The order is saved automatically as you drag.

### Device Management

Device Management is where you see every iPad and iPhone registered to this app, and where you can rename them, change their roles, or revoke access if a device is lost, stolen, or being retired.

**Getting there:** Open Admin Settings and tap **Devices** under the "Shop" section.

**Requires internet.** Device management won't work offline — if the connection is out, a banner will appear at the top of the list and changes will be disabled until you reconnect.

#### Viewing Devices

You'll see a list of all registered devices, each showing:

- The **device name** (e.g., "Front Counter iPad")
- A **role badge** — blue for Front Counter, teal for Tech Station, purple for Admin
- **Last seen** — roughly when the device last opened the app ("2 hours ago", "3 days ago")
- A **"this device"** label next to whichever device you're currently using

Active devices appear at the top. Any revoked devices appear in a separate **Revoked** section at the bottom.

Pull down to refresh the list.

#### Renaming a Device or Changing Its Role

Tap any device row to open its edit sheet.

- **Name** — type whatever makes sense for your shop (e.g., "Maria's iPad", "Back Shop Tech", "Bec's iPhone")
- **Role** — use the segmented picker to change the role: Front Counter, Tech Station, or Admin

Tap **Save** when done.

**Important:** Role changes on a device other than the one you're holding take effect the next time that device opens the app. You'll need to let whoever's on that device know to close and reopen it (or force-quit and relaunch). Role changes made to your *current* device take effect immediately.

#### Revoking a Device

Revoking removes a device's access until it goes through setup again. Use this if a device is lost, stolen, reassigned to someone new, or just needs a fresh start.

**To revoke by swiping:** Swipe left on the device row and tap **Revoke**. Confirm in the popup.

**To revoke from the detail sheet:** Tap the device row, scroll to the bottom, and tap **Revoke Device**.

When a revoked device is opened again, it will show the Device Setup screen and need to be configured from scratch. The device keeps the same underlying identity (so it doesn't create a duplicate entry), but it'll need a new name, role, and admin PIN before it can be used.

You **cannot revoke the device you're currently holding** — if you need to reassign your own device, do the reset from a different admin device, or use the **Reset Device** option in the Danger Zone at the bottom of Admin Settings.

#### Reactivating a Revoked Device

If a device was revoked by mistake, or it's back in service:

1. Scroll to the **Revoked** section at the bottom of the device list
2. Tap **Reactivate** next to the device name

The device is immediately active again. If it hasn't gone through setup yet since being revoked, it'll still need to complete setup on next launch. If it already went through setup (i.e., it was re-enrolled), reactivating is a no-op — it's already active.

### Managing Flags (Admin Only)

Anyone in the shop can flag a customer, company, or piece of equipment — but **only admins can remove flags.** This is intentional. The person at the counter or in the back can raise a concern immediately, but clearing it requires someone with admin access to review the situation first.

To remove a flag, navigate to the flagged customer's detail screen (or company detail, or equipment detail) and tap **Remove Flag**. You'll see a confirmation dialog. Once removed, the amber warning banner disappears from all views. The flag history is preserved — there's a record of when the flag was set, why, and when it was removed — so you always have a paper trail.

If you're reviewing flag history, the information is stored in the system even after flags are removed. This is useful if the same customer or company gets flagged again down the line.

### Editing Cost on a Complete Item

Once a tech submits a cost and the item reaches **Complete** status, the cost is normally locked — the front counter just reads it at pickup. But sometimes a price needs to change after the fact (a part came in cheaper, the customer negotiated, a mistake was caught). Admins can re-edit the cost directly from the job detail view.

**How to edit a cost:**

1. Open the job from the Job Board
2. Make sure admin access is active (admin-role device, or elevate with your PIN)
3. On the Complete item's card, you'll see an orange **Edit Cost** button in the action area
4. Tap it — the cost entry sheet opens pre-filled with the existing values
5. Change whatever needs changing (total cost, parts/labor split, taxable toggle)
6. Tap **Submit** → confirm manager approval
7. The item stays at Complete status — only the cost values update

This goes through the same manager approval prompt as the original cost entry. The updated cost appears immediately on the job detail and in the Close Job card total.

### Reports

**Getting there:** Tap **Reports** in the sidebar, or open Admin Settings and tap **Reports** under the "Shop" section.

Reports are admin-only. They pull live data from Supabase every time you open them — there's no offline mode for reports.

#### Picking a Date Range

At the top of the screen, pick a time period for the report:

- **Today** — midnight to now
- **This Week** — Monday to now
- **This Month** — first of the month to now
- **Month** — pick any month/year from a date picker (full calendar month)
- **Custom** — set a From and To date manually

All dates use Eastern Time. Changing the date range automatically refreshes the current report.

#### Choosing a Report

Below the date range, tap the **Report** dropdown to switch between:

1. **Revenue Summary** — Grand total, warranty item count, taxable vs non-taxable breakdown, tax collected, and parts vs labor split (if that setting is enabled in Shop Settings). Also shows total job and item counts for the period.
2. **Jobs Completed** — Every job where all items were closed in the selected period. Shows job number, customer name, date closed, item count, and total cost. Most recent first.
3. **Jobs Per Tech** — How many items each tech worked on and how many distinct jobs they touched. Based on when repair started, not when it finished.
4. **Repair Time Per Tech** — Average and total repair time for each tech. Only counts items where the tech started AND finished the repair. Displayed as hours and minutes.
5. **Parts vs. Labor** — Total parts cost, total labor cost, and grand total. Only available if the parts/labor split is turned on in Shop Settings — otherwise you'll see a message telling you to enable it.
6. **Warranty Summary** — Count of warranty jobs and items vs non-warranty jobs in the same period. Warranty work is always $0 but the volume is tracked.
7. **Repeat Customers** — Customers who've had more than one job, with at least one completed in the selected period. Shows lifetime job count, jobs in the selected range, and total lifetime spend. Sorted by most jobs first.
8. **Revenue by Company** — Revenue totals grouped by company. Shows each company's total revenue, job count, and item count for the selected period. "Walk-in / No Company" groups all jobs without a company. Sorted by highest revenue first.
9. **Jobs by Company** — Job history grouped by company. Shows every closed job under each company with job number, customer name, date, item count, and cost. Sorted by most jobs first.

#### Exporting to CSV

Each report has an **Export CSV** button at the bottom. Tap it to open the standard iOS share sheet — from there you can AirDrop the file, save it to Files, email it, or send it anywhere else iOS lets you share.

The file is named descriptively (e.g., `revenue-summary-2026-03-06-to-2026-04-06.csv`) and opens in Excel, Google Sheets, Numbers, or any spreadsheet app.

[screenshot: Reports screen showing Revenue Summary with date range selector and export button]

### Resetting a Device

If a device needs to be reassigned (different role, different name, or just starting fresh):

1. Open the Admin view on an admin-role device (or elevate admin access on the target device)
2. Tap **Reset Device** at the bottom of the Admin settings list
3. Confirm by tapping **Reset Device** again in the confirmation prompt
4. The device will forget its identity and show the setup screen again
4. Go through the setup process to assign a new name and role

---

### Training Mode & Local Test Mode

**Getting there:** Open Admin Settings. The **Testing & Training** section sits right under Device at the top of the screen.

Two toggles let you create fake test work orders without messing up the real job board. Pick whichever fits what you're doing:

#### Training Mode (shop-wide)

**Use this when:** Teaching the shop how to use the app — running a demo for Maria, walking a new tech through the queue, showing Lee a feature on his iPad while you have it open on yours.

When you flip **Training Mode** on:

- Every new work order created on **any device** is marked as a test job
- Test jobs show up on **every device's** Job Board and Work Queue, just like real ones
- Job numbers get a `TEST-` prefix (e.g., `TEST-20260409-1`) so they're obvious at a glance
- Every item tile gets a purple **TRAINING** badge in the top-left corner
- A small purple circle with a **graduation cap icon** floats at the top of every screen so nobody forgets they're in training

When you turn it back off, the test jobs **instantly disappear from every device** — they're not deleted, just hidden. If you turn Training Mode back on later, they reappear.

> Training Mode broadcasts across the whole shop. If you flip it on while Maria is using the Front Counter iPad, her board will start showing test jobs too. That's the point — but give her a heads-up first.

#### Local Test Mode (just this iPad)

**Use this when:** You want to poke at the app yourself — try out a new feature, test a workflow, see what a job card looks like with three items — without anyone else seeing your test jobs.

When you flip **Local Test Mode** on:

- Every new work order created on **this iPad** is marked as a test job AND scoped to this device only
- Other iPads (Front Counter, Tech Station, other admin iPads) **never see** these test jobs — not on the board, not in the queue, not anywhere
- Job numbers get the same `TEST-` prefix
- Tiles get a pink **TEST** badge instead of the purple TRAINING badge — so you can tell at a glance whether a test job came from Training Mode or Local Test Mode
- A small **pink circle** with a **test tube icon** floats at the top — visually distinct from Training Mode's purple graduation cap, so you always know which mode you're in
- **Existing training jobs stay visible** on this iPad — so if you were just demoing in Training Mode and now want to keep poking solo, you can pick up right where you left off without recreating anything. Only your own brand-new jobs (the ones you create after switching) are scoped to this device.

The setting is per-device, so it sticks across app restarts but doesn't follow you to a different iPad.

#### One at a time

Training Mode and Local Test Mode are mutually exclusive — you can have one on, the other on, or neither, but never both. If you try to turn one on while the other is already active, the app asks you to confirm the switch and then flips them for you.

#### Convert a Test Job to a Real Job

If a test job turns out to be something you actually want to keep — say you were demoing intake to Maria and she happened to be entering a real customer at the same time — you can promote it without recreating it from scratch.

1. Open the test job (any device, but you have to be in Admin or admin-elevated)
2. Tap the **Convert to Real Job** button (curved arrow icon) in the top-right toolbar
3. Confirm the dialog
4. The job gets a fresh real job number, drops the `TEST-` prefix, loses its TRAINING badge, and appears on every device's board as a normal live job

The original test job number is replaced — there's no way to undo the conversion, but the job's items, photos, notes, and customer all carry over untouched.

#### Clear All Test Jobs

When you're done with a training session or you've accumulated a pile of test jobs from poking at things, tap **Clear All Test Jobs** at the bottom of the Testing & Training section. The button shows a live count of how many test jobs currently exist (across all devices).

The confirmation dialog tells you exactly how many will be deleted ("Delete 7 test jobs?"). Confirming removes every test job along with its items, photos, notes, and history. **This cannot be undone.** Real jobs are completely untouched.

> The cleanup only deletes jobs flagged `is_test_job = true`. If you're nervous, you can spot-check the count against the test jobs you can see on the board before tapping Delete.

[screenshot: Admin Settings → Testing & Training section with both toggles, footer text, and Clear All Test Jobs button]

[screenshot: Job board with a TEST-prefixed card and the purple TRAINING badge on its photo tiles]

[screenshot: Purple "Training Mode" capsule centered at the top of the screen]

---

### Bug Reports (Admin)

**Getting there:** Open Admin Settings and tap **Bug Reports** under the "Diagnostics" section.

Admins can view all submitted reports in a newest-first list. Each row shows:

- **Manual** (blue) or **Auto** (amber) badge — Manual means someone tapped the ladybug button. Auto means the app detected a problem on its own.
- The trigger or short description
- Which device it came from
- How long ago it was submitted

Tap any report to see the full detail, which includes:

- **Screenshot** — The app automatically captures a picture of whatever was on screen at the moment the report was filed. Tap the screenshot to view it full-size with pinch-to-zoom.
- **Navigation Trail** — A breadcrumb trail showing the last screens the user visited before the report. This helps Bec figure out what path led to the problem (e.g., "Job Board → Job Detail → Item Detail → Ladybug Report").
- **Details** — Device info, trigger type, timestamps.
- **Description** — What the user typed (if anything).
- **Error Log** — Recent technical errors logged by the app.
- **App State** — A snapshot of what the app was doing at the time (sync status, which screen was open, etc.).

#### Auto-Reporting

The app monitors itself in the background. If it detects a serious problem — like changes that repeatedly fail to sync, a photo that won't upload, or the connection dropping unexpectedly — it files a report automatically without anyone having to do anything. Bec gets an email and a push notification on her iPhone and iPad.

Auto-reports appear in the Bug Reports list with an **Auto** badge. They fire at most once per problem type every 10 minutes, so you won't get flooded.

#### Notification Banners

When an auto-report fires, a brief amber banner appears at the top of the screen on admin devices. It shows a one-line summary of what happened. Tap it to go straight to Bug Reports, or wait 8 seconds and it dismisses on its own. If multiple alerts come in at once, they queue up and show one at a time.

The **Bug Reports** link in Admin Settings shows a badge count of unread notifications. It clears when you open the Bug Reports view.

---

## Reporting a Problem

If something looks wrong or the app does something unexpected, you can report it directly from any screen without having to explain it to Bec later.

### The Ladybug Button

There's a small ladybug icon (🐞) in the top-right corner of every screen, on every device. Tap it whenever something seems off.

A sheet slides up with:

- **Description** — Optional. Write a quick note about what you were doing when the problem happened. The more detail, the better, but it's not required.
- **Recent Errors** — A collapsible section showing the last few technical errors the app logged. You don't need to understand this — it's there automatically to help Bec diagnose the issue.
- **Device Info** — Your device name, role, and app version. Attached automatically.

Tap **Submit** and you're done. The report goes straight to Bec. You'll get a confirmation and the sheet closes.

When you submit, the app also automatically captures a screenshot of whatever was on screen and records which screens you visited recently. This gives Bec a visual snapshot and a breadcrumb trail to help figure out what happened — you don't need to explain where you were or try to recreate the problem.

**You don't need to be sure something is wrong to submit a report.** If something felt weird or slow, report it. Bec would rather get a false alarm than miss a real issue.

---

## Equipment Tags

ShopTracker supports QR sticker tags that permanently identify a physical piece of equipment. Once a sticker is on a cylinder or pump and linked in the app, anyone in the shop can scan it to jump straight to that item's current job — no searching, no scrolling.

Tags are stickers with a unique QR code printed on them. They don't mean anything until they're assigned to a piece of equipment in the app for the first time. After that, the sticker stays on the equipment forever, and the app always knows what it is.

---

### Getting Sticker Sheets

Sticker sheets are printed ahead of time and kept at the front counter, ready to use when equipment comes in. You generate and print them directly from the app — no browser or external files needed.

To print a batch:

1. Go to **Admin Settings** → **QR Stickers** → **Generate Stickers**.
2. Pick a **layout** from the dropdown (this controls sticker size, spacing, and how many fit on a page).
3. Set the **count** — it defaults to one full page based on your layout. Adjust up or down with the stepper.
4. Optionally add a **note** (e.g., "For front counter stock") to help identify this batch later.
5. Tap the yellow **Generate Batch** button.
6. You'll see a preview grid of all the stickers. Scroll through to verify they look right.
7. Tap **Export PDF** → the standard share sheet appears. Choose **Print**, **Save to Files**, or **AirDrop** — whatever works for your setup.
8. Cut out the stickers and you're good to go.

Each sticker has a unique code on it (looks like **SR-A3KX7N**). The codes are meaningless until assigned — you can generate as many sheets as you want and unused stickers don't need to be tracked.

If you don't like the codes that were generated, tap **Regenerate Codes** below the Export button to get a fresh set. The old batch stays in the system's history for record-keeping.

**If you're offline:** The app will still generate stickers and export the PDF. You'll see a small banner saying "Generated offline — collision check skipped." This just means the app couldn't verify the codes are unique against the database — with 729 million possible codes, duplicates are extremely unlikely.

**Managing layouts:** Go to **Admin Settings** → **QR Stickers** → **Sticker Layouts** to create, edit, or set a default layout. The default layout is pre-selected when you open the generator.

**Tip on placement:** Stick the tag somewhere that won't be removed or covered during repair. The barrel of a cylinder works well. Avoid end caps, fittings, or anywhere that gets disassembled. The tag needs to survive the job and still be readable when the customer brings the equipment back years later.

---

### Viewing Batch History

Every batch of stickers you generate is logged for record-keeping. To view past batches:

1. Go to **Admin Settings** → **QR Stickers** → **Sticker History**.
2. You'll see a list of all generated batches, newest first.

Each row shows:
- **Date and time** the batch was generated
- **Number of codes** and the grid size (e.g., "42 codes · 6×7")
- **Layout name** (e.g., "1″ Plain Paper")
- **Who generated it**
- **Notes**, if any were added during generation
- **Export status** — batches that have been exported to PDF show a green "Exported" badge. Batches that were generated but never exported appear dimmed.

**Viewing batch details:** Tap any row to see the full list of codes in that batch, along with all the summary info.

**Re-exporting a batch:** From the detail screen, tap **Re-Export PDF** to generate a fresh PDF with the same codes and layout. The standard share sheet appears so you can print, save, or AirDrop. If the batch hadn't been exported before, it's now marked as exported.

**Pull to refresh:** Pull down on the list to reload from the server.

**Offline:** If you're offline, the app shows cached batch data from the last time it connected. You can still view details and re-export PDFs (PDF generation is local).

---

### Assigning a Tag at Check-In (Front Counter)

When a customer brings in equipment that doesn't already have a tag:

1. Peel a sticker off the sheet and stick it on the equipment.
2. Create the new work order as normal. In the item form, tap **Scan Tag**.
3. The camera opens with a yellow scan frame — point it at the sticker.
4. The app reads the code and shows **"Tag Assigned ✓"** in green. The sticker is now permanently linked to that piece of equipment.
5. Finish filling in the rest of the item details and create the work order.

The link is saved when you create the work order. If you save as a draft, the tag assignment is saved with the draft too.

**Equipment you've seen before:** If the equipment already has a sticker from a previous visit, scan it during check-in the same way. The app recognizes it, links the new job to the same equipment record, and may pre-fill the equipment type if that field is still empty. A returning cylinder with a tag is faster to check in than one without.

---

### Scanning from the Job Board (Front Counter)

You can scan a sticker at any time — not just during check-in — to jump to an item's current job.

Tap the **scan icon** (QR viewfinder icon) in the toolbar on the Job Board. The camera opens. Scan the sticker.

- **Active job exists** — the app navigates straight to the item detail for that job. Useful when a customer calls and you want to pull it up quickly, or when a completed item is on the shelf and you need to check its status.
- **No active job** (item was closed or picked up) — the app asks **"Create a new job for this item?"** and shows the customer name and equipment type. Tap **Create Job** to open a new work order with the customer and equipment type already filled in and the tag already linked. This is the fastest way to check in a repeat customer — scan the sticker, confirm, and you're already halfway through intake.
- **Retired tag** — you'll see which item it used to be linked to.

---

### Scanning from the Work Queue (Tech Station)

Tap the **scan icon** in the toolbar on the Tech Station queue screen. The camera opens with a yellow scan frame — point it at the sticker on the equipment sitting on the bench. The app looks up the item and navigates directly to its detail view with all your normal action buttons ready.

No more hunting through the queue for the right item. Scan the cylinder, start working.

**If the scan doesn't find anything:** The sticker hasn't been assigned to any item yet. You can assign it right now from any item's detail view — see "Assigning a Tag After Check-In" below. If the tag was retired, the app will tell you — see "Scanning Old / Retired Tags" below. If the equipment has no active job (closed or totaled), you'll see "No active item found" — creating new jobs is a Front Counter task. If you accidentally scan a shipping label or other non-shop QR code, you'll see **"Not an SR-80 tag"** — the app knows it's not one of ours because shop tags always start with "SR-".

**If the sticker is too damaged to scan:** Tap **"Enter code manually"** below the viewfinder frame to type the code directly. The code is printed on the sticker label below the QR pattern. If the device has no camera or camera access is denied, manual entry is offered as the primary option.

---

### The QR Icon — What It Means

Every item has a QR button that tells you at a glance whether a tag is assigned. Where to find it:

- **Front Counter** — top-right corner of the item card header, next to the status badge.
- **Tech Station** — right side of the equipment name row (e.g., next to "Cylinder"), in the item detail view. Look for **⊡ Add Tag** in gray.

What the button looks like:

- **Gray "⊡ Add Tag"** — no tag assigned yet. Tap it to open the camera and scan a sticker onto this item right now.
- **Green QR icon** — a tag is assigned to this item. Tap it to see the full-size QR code for printing or sharing.

You can assign a tag at any point in the workflow — Checked In, In Progress, Tested, even Closed. You don't have to start the job over or ask an admin.

---

### Viewing and Reprinting a Tag

Tap the **green QR icon** on any item that already has a tag assigned. A large, clean QR code appears.

From that screen, tap the **Share** button to:
- AirDrop it to a Mac and print from Preview
- Save it as an image to Photos
- Send it via Messages or email

This is useful for reprinting a tag if a sticker gets damaged or falls off.

---

### Assigning a Tag After Check-In

If a tag wasn't scanned at check-in — or if the job was created before your shop started using stickers — you can assign one at any time without touching the original work order.

**From the Front Counter:**

1. Open the job and find the item card.
2. Look for the **gray viewfinder icon** in the top-right corner of the item card. That means no tag is assigned yet.
3. Tap it. The camera opens.
4. Point the camera at the sticker on the equipment.
5. The app links the tag and shows a **"Tag Assigned" confirmation** with a green checkmark and the QR code.

Next time you open that item, the icon will be **green** — tag is assigned.

**From the Tech Station:**

1. Open the item from the queue.
2. Look for **⊡ Add Tag** in gray, on the right side of the equipment name row (e.g., next to "Cylinder" or "Pump").
3. Tap it. The camera opens.
4. Scan the sticker on the equipment sitting on your bench.
5. The app saves the assignment and shows a **"Tag Assigned" confirmation** with a green checkmark and the QR code.

From that point on, the icon is green, and anyone can scan that sticker to navigate straight to this item.

**If the sticker is already used:** If you scan a sticker that's already assigned to another piece of equipment, the app will block the assignment and tell you which equipment and customer it belongs to. You'll need to scan a different sticker. To free up a used sticker, go to the item it's currently assigned to and use **Replace Tag** (see below).

---

### Replacing a Tag

If a sticker gets damaged, lost, or you need to move a sticker to a different piece of equipment, you can replace the tag on any item that already has one assigned.

1. Open the item (from the Job Board or Tech Station queue).
2. Scroll to the bottom of the item card. You'll see a small **🔄 Replace Tag** link in gray text.
3. Tap it. The camera opens.
4. Scan the **new** sticker you want to assign.
5. A confirmation dialog appears: **"Replace this item's tag?"** — explaining that the current tag will be deactivated.
6. Tap **Replace Tag** to confirm.

The old sticker is now retired. The new sticker is active. If anyone scans the old sticker later, they'll see a message that it was retired and which item it used to be linked to.

**What can go wrong:**

- **New sticker is already assigned to something else** — the app blocks it and tells you what it's assigned to. Scan a different sticker.
- **You accidentally scan the same sticker** — the app tells you it's already the tag on this item. No changes made.

**Replace Tag** is available to all roles (Front Counter, Tech Station, Admin) and at any item status.

[screenshot: Replace Tag button at bottom of item card]

---

### Scanning Old / Retired Tags

If you scan a sticker that was replaced (retired), the app shows a popup:

> **"This tag has been retired."**
> It was previously linked to Item [item number].
> [View Item] [Dismiss]

Tap **View Item** to navigate to the item it used to be on — useful for tracking down equipment history.

---

### Scanning Tags on Closed or Totaled Items

If you scan a sticker and the linked item has been closed (picked up) or totaled, the app offers to create a new job for that equipment — see "Scanning from the Job Board" above. The customer and equipment type are pre-filled so you can get straight to intake.

---

### When There's No Tag

The app works completely normally without a tag — tags are a convenience, not a requirement. Jobs with no tag assigned show the **gray viewfinder icon** on their item cards as a reminder, but everything else (photos, notes, status flow, cost entry) works exactly the same.

---

### Flagging Equipment

If a specific piece of equipment has a history of suspicious warranty claims or other issues, you can flag it. This requires the equipment to have a tag — you can only flag equipment that has a QR sticker record in the system.

**Setting a flag:** From an item detail view where equipment info is displayed (near the QR tag section), tap **Flag Equipment**. Type a reason (e.g., "3rd warranty claim — customer keeps swapping cylinders") and confirm. Any role can set equipment flags.

**What it looks like:** A flagged piece of equipment shows the amber warning banner on any item detail view where that equipment appears. If this cylinder comes back in six months under a new job, the banner will be there waiting.

**Removing a flag:** Admin only — tap **Remove Flag** and confirm. The flag history is preserved even after removal.

---

## Reference & Troubleshooting

### Troubleshooting

#### "Incorrect PIN"

Double-check that you're entering your personal admin PIN (4-8 digits). PINs are per-person, not per-device. If you've forgotten your PIN, another admin can reset your PIN from Admin Settings → Employees — swipe left on your name and tap Reset PIN.

#### The app shows "Connecting..." on launch

ShopTracker needs an internet connection on first launch to download your jobs and settings. After that, it caches everything locally so you can keep working even if Wi-Fi drops (see "Working Offline" below). If you're stuck on "Connecting..." with a good Wi-Fi signal, the issue may be on the server side — let Bec know.

---

### Working Offline

ShopTracker is designed to keep working when the shop Wi-Fi drops. Here's what you need to know:

#### What still works without internet

As long as you've opened the app at least once with a connection (so it can download your data), you can still:

- Browse the job board, work queue, customer list, and company list
- View photos that have been loaded before (they're saved on the iPad)
- **Create a brand new work order** — the job will save as a draft automatically and finalize when you're back online
- **Add a new customer** as part of a walk-in (even if you've never seen them before)
- **Add items and service reasons** to a new or existing work order (draft or finalized)
- **Capture photos** — they save to the iPad and upload when the connection returns
- Grab items, mark repairs done, move items through the status flow
- Add notes and check issue checklists
- Enter costs and close items

All of those changes are saved on the iPad and will automatically sync to the server as soon as the connection comes back. You don't have to do anything — the app handles it.

#### What doesn't work without internet

- **Finalizing a new work order** — offline intake always saves as a draft. When you reconnect, open the draft and tap Finalize to assign a real job number.
- **Warranty check-in** — warranty jobs are never drafts, so this path is disabled while you're offline. Wait until you're reconnected.
- Deleting a draft job (the photos are stored in the cloud)
- Any changes other people make on their devices won't show up until you're back online

#### When the connection comes back

The app detects when Wi-Fi returns and automatically sends any changes you made while offline. This usually takes a few seconds. On a bigger sync (new job + new customer + several photos), it may take up to a minute.

A few things happen automatically in the background on reconnect:

- **Drafts created offline** stay as drafts until you tap Finalize — that's when the job number gets assigned. Photos you took during intake sync on their own; you'll see them appear on the job card within seconds.
- **New customers** created offline get merged with any existing record automatically if the phone number already exists — the app figures it out and rewires the new job to the real customer without you lifting a finger.
- **Live updates** from other devices come back online — the job board, work queue, and any open detail view refetch fresh data a few seconds after reconnect to catch anything that happened during the outage. You don't need to pull to refresh.

If someone else made changes to the same item on a different device while you were offline, the app figures it out automatically. It compares what you changed against what the other device changed — if you edited different fields (e.g., you marked it Done while Maria added a note), both changes go through. If you both changed the same thing, the most recent change wins. You don't need to do anything — it just works.

If something goes wrong during sync (rare), Bec can see it in **Admin Settings → Sync Status**. The dashboard shows which changes are pending, which failed, and why. From there you can retry failed items, force a sync, or clear the queue entirely if needed.

#### Tips

- Don't worry about saving — everything saves automatically, online or off.
- If you're not sure whether you're online, look for the **offline banner** at the top of any view. It appears automatically when the iPad loses its connection and disappears when you're back online. On list views (Job Board, Work Queue), it also shows a count of pending changes — e.g., "Offline — 3 changes will sync when back online". The data on screen is still usable — it's just a snapshot from the last time you had a connection.
- When creating a new work order offline, the save button will read "Save as Draft" even if you've filled in every field. That's by design — the server assigns the real job number on reconnect.
- Photos you capture offline show up immediately in the job detail view with a slight delay badge. They'll replace themselves with the real cloud-hosted version automatically once the upload finishes.

#### A device is showing the wrong role

An admin will need to reset the device and set it up again with the correct role. See "Resetting a Device" above.

---

### Multiple Devices

#### Live Updates

When two people are looking at the same job at the same time on different iPads, their screens stay in sync automatically. You don't need to pull down to refresh or tap anything — status changes, new notes, and new photos appear on their own, usually within a second.

This works from any view where it matters:

- **Job Board (Front Counter)** — if Tony moves an item to Tested in the back, Maria's board updates automatically. The status dot changes color, and if all items are now Complete, the job card reflects that.
- **Job Detail** — if you have a job open and a tech updates an item's status or adds a note on their device, your view updates live. You don't need to close and reopen the job.
- **Tech Station Queue** — when an item becomes Ready for Test (tech marks repair done on another iPad), it floats to the top of the queue immediately. When a tech grabs an item, it updates on every device — so two techs can't accidentally grab the same one.
- **Item Detail (Tech Station)** — if you're looking at a specific item and it gets updated on another device, the status badge, repair history, notes, photos, and checklist all update in place.

#### If a sheet was open during an update

Occasionally, if you have a cost entry, test result, or similar action sheet open and someone else changes that item's status on a different device, ShopTracker will close your sheet automatically and show a brief message: **"This item was updated on another device."**

This just means the item moved to a different status while you had it open. Tap the appropriate action button again to continue from the current state.

#### Editing the same item at the same time

If two people are filling in the same item's details simultaneously (e.g., both editing equipment info), the last save wins on a field-by-field basis — not the whole record. So if Maria is typing in the Description field and Tony changes the Equipment Type on his device, Tony's Equipment Type change comes through without touching Maria's Description. Whatever Maria saves last is what sticks for the Description field.

---

*More sections will be added as features are built. This manual is a living document.*
