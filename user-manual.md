# ShopTracker User Manual

**App:** ShopTracker (SR80)
**Version:** 1.0 (in development)
**Last Updated:** 2026-04-01 (Tax flag on parts + tax rate configuration)

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

If you're on the Front Counter or Tech Station iPad and need to do something that requires admin access (like changing settings), you don't have to go find an admin device. Any admin can temporarily unlock their access:

1. Navigate to the admin access option (gear icon or similar)
2. Enter your admin PIN
3. You'll have admin access for a limited time (configurable in settings — defaults to 5 minutes)
4. After the timer expires, the device automatically locks back to its assigned role

Admin-role devices stay unlocked permanently — the auto-lock only applies when you're elevating access on a non-admin device.

### Sidebar Navigation

The app has a sidebar menu that lets you switch between different views. The sidebar is hidden by default so it doesn't take up screen space — you open it when you need it.

**To open the sidebar:**

- **Swipe from the left edge** of the screen, or
- **Tap the back arrow button** in the top-left corner of the toolbar

The sidebar slides over the current view. Tap any item to switch to that view. The sidebar closes automatically when you make a selection, or you can swipe it away.

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

**To change the display size:**

1. Open the sidebar (swipe from the left, or tap the back arrow in the top-left)
2. At the bottom of the sidebar, under **This Device**, tap **Display Size**
3. A settings panel slides up from the bottom

**Text Size** — three options:
- **Default** — standard size, same as most apps
- **Large** — noticeably bigger, good for extended use or reading glasses situations
- **Extra Large** — significantly bigger, designed for arm's-length viewing or anyone who needs more visual breathing room

**Bold Text** — toggle this on to make all text heavier/darker throughout the app. Works independently from the size setting — you can have bold text at any size.

Changes take effect immediately and are saved to this device only. The front counter iPad, back shop station, and admin device each remember their own settings.

---

## Front Counter

### Job Board

When you open the app on a Front Counter device, you'll see the **Job Board** — a grid of cards showing all active work orders. Each card shows:

- **Item photos** — the top half of every card is a square photo area showing the equipment. If a job has one item, you see one big photo. Two items show stacked photos. Three or four items show a 2×2 grid. If there are more than four items with photos, the last tile shows a "+N" badge so you know there's more. Each photo has a small colored **status dot** in the top-right corner and an **equipment type label** (e.g., "Cylinder") in the bottom-right corner.
- **Job number** (e.g., 20260325-1) and **status dots** — one colored dot per item showing where it is in the repair process (blue = checked in, yellow = being worked on, orange = tested, green = ready for pickup)
- **Customer phone number** (tappable) and **name**
- **Equipment summary** (e.g., "Pump × 1 · Cylinder × 2") and the date/time the job was created

Photos load in the background — you'll see the cards appear right away with placeholder tiles, and the actual photos fill in a moment later.

**Draft work orders** appear at the top with an orange "DRAFT" badge and a warm-tinted background so they stand out as unfinished.

When all items on a job have been priced and approved, a green **"COMPLETE"** badge appears in the top-left corner of the card's photo area — slightly tilted, just like in V1. This is your at-a-glance signal that the job is ready for customer pickup and payment.

Jobs are sorted by urgency: green (ready for pickup) first, then orange (tested), then yellow (in progress), then blue (just checked in). Within each group, the oldest jobs appear first. This way the items closest to being done — the ones a customer might be waiting on — are always at the top.

Pull down on the job board to refresh and see the latest updates from the back shop.

Tap the **pencil icon** in the top right corner to create a new work order.

### Searching and Filtering Jobs

Next to the pencil icon in the toolbar, you'll see a **search bar** and a **filter button** (circle with three lines).

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

At the bottom of the Job Board, you'll see a **Closed** section with a count of how many jobs are fully closed or totaled. This section is collapsed by default so it doesn't clutter the active board.

Tap the **Closed** header to expand it. You'll see the same card grid as above, but for jobs that are done — all items either closed or totaled. The cards are slightly dimmed so they're easy to tell apart from active jobs.

Tap the header again to collapse the section back down.

Your search and filters work across both active and closed jobs. If you search for a customer name and they have a closed job that matches, you'll see it in the closed section (expand it to check).

This is useful for looking up past work — warranty questions, repeat customers, or just checking what was done on an old job. Tap any closed job card to see the full detail view with all items, photos, and notes.

### Creating a New Work Order

Tap the pencil icon from the Job Board to start a new work order. The form has two main sections: **Customer** and **Items**.

#### Finding or Adding a Customer

At the top of the form, start typing a customer's name or phone number. Matching customers will appear below the search field as you type. Tap a result to select them.

If the customer isn't in the system yet, tap **+ Add New Customer** to create one. The new customer form includes:

- **Name** (required) — if you type a business name (ending in Inc, LLC, Corp, etc.), the app will automatically move it to the Company field
- **Company** (optional) — use the **Swap** button if the name/company got put in the wrong field
- **Phone** (required, 10 digits) — formats automatically as you type. If the phone number is already on file for another customer, you'll be warned and can choose to use the existing customer instead
- **Email** (optional)
- **Tax Exempt** toggle

#### Adding Items

Each work order needs at least one item. For each item, fill in:

- **Equipment Type** — what the item is (Cylinder, Pump, Hose, or Other)
- **Reason(s) for Service** — tap the pill-shaped buttons to select why the customer brought it in (Leaking, Barrel Damage, Bushings, etc.). You can select multiple reasons.
- **Description / Notes** — any additional details about the item

Tap **+ Add Item** to add more items to the same work order (e.g., a customer drops off 3 cylinders at once).

To remove an item, tap the trash icon next to its header. You can't remove the last item.

#### Taking Photos During Intake

Each item has a **Photos** section at the bottom of the form. This is a great time to photograph the equipment as it comes in — document any existing damage, serial numbers, or anything else worth capturing before the tech starts work.

You have two options:

- **Camera** — tap the camera button to open the camera. The camera stays open between shots — tap the shutter button as many times as you need, and each photo appears in a strip at the bottom of the screen. When you're done, tap **Done** in the top-right corner to close the camera and return to the form. You can also tap **Cancel** to close the camera at any time — photos you already took are kept.
- **Library** — tap the library button to pick a photo already on the device (useful if someone snapped a picture before opening the app)

Photos appear as small thumbnails next to the buttons. To remove a photo before saving, tap the **X** on the thumbnail. Photos aren't uploaded until you tap "Create Work Order" or "Save as Draft" — you'll see a brief "Uploading..." indicator while they're sent to the server.

There's no limit on photos per item. Take as many as you need.

#### Saving

The button in the top right changes based on what you've filled in:

- **"Create Work Order"** — appears when all required fields are filled in (customer, equipment type, at least one reason for service). This creates the work order with a job number and makes it visible to the back shop.
- **"Save as Draft"** — appears when required fields are still missing. This saves your progress so you can come back to it later. Drafts appear at the top of your Job Board with an orange badge but are NOT visible to the Tech Station.

### Viewing a Job (Job Detail)

Tap any card on the Job Board to open the full job detail view. This shows everything about the work order in one place.

At the top you'll see a **header card** with:

- **DRAFT badge** (orange) or **job number** (e.g., 20260325-1)
- **Customer name, phone number, and company** (if applicable)
- **Status dots** — one colored dot per item, same colors as the Job Board
- **Item count** and **creation date/time**

Draft jobs have a warm amber-tinted header, just like on the Job Board.

Below the header, each **item** gets its own card showing:

- **Item number** and **status** (with a colored badge like "Checked In" in blue, "In Progress" in yellow, etc.)
- **Equipment Type** — what the item is
- **Machine Type** and **Color** — if those fields are turned on in admin settings
- **Reason(s) for Service** — shown as blue pill-shaped tags
- **Description / Notes** from intake
- **Assigned tech** — if a tech has grabbed the item, you'll see their name (e.g., "Assigned to Carlos")

If photos have been taken for an item, you'll see a row of **photo thumbnails** near the top of the item card. Tap any thumbnail to view it full-screen — tap the photo or swipe down to close the full-screen view. Photos that have been marked up show a small blue pencil badge on their thumbnail so you can tell at a glance which ones have annotations.

You can add more photos to any item at any time, regardless of its status. Next to the thumbnails you'll see **Camera** and **Library** buttons — same as during check-in. Tapping **Camera** opens the continuous camera: the shutter stays open so you can take multiple shots in one go, with a thumbnail strip at the bottom showing what you've captured. Tap **Done** when you're finished shooting. New photos upload immediately and appear in the thumbnail strip.

#### Marking Up Photos

This is the feature that replaces Apple Notes markup. Tap any photo thumbnail to open it full-screen, then tap the **Markup** button (pencil icon) in the top-right corner. This opens the Apple PencilKit editor with the full native toolbar — pens, markers, pencils, erasers, ruler, and the complete color palette.

Draw directly on the photo to circle damage, write prices, add arrows, or annotate anything worth calling out. When you're done, tap **Save**. The marked-up version becomes what everyone sees on the job — on cards, in the detail view, everywhere.

**Your original photo is always preserved.** Markup is non-destructive. If you need to redo it (say the price changed), tap the photo again, tap Markup, and your previous strokes are still there — you can erase specific marks, add new ones, or start fresh with the trash button. If you want to remove all markup entirely, tap the **revert button** (curved arrow) in the toolbar and the photo goes back to the untouched original.

Markup is available on every photo at every status — Front Counter intake photos, Tech Station repair photos, any of them. There are no restrictions on who can mark up or when.

#### Notes

Each item card has a **Notes** section where you can add timestamped notes at any point in the workflow — before repair, during, after, whenever.

To add a note, type in the "Add a note..." field and tap the blue **send arrow**. The note is saved immediately with your name and the time. Notes appear newest-first so the latest info is always at the top.

Notes are visible to both the front counter and the tech station. Maria can jot down customer instructions ("needs by Friday"), and Tony can document what he found during repair. Everyone sees the same timeline.

Below each item card, you may see **action buttons** depending on the item's status and your device role. On the Front Counter, you can close items that are ready for pickup. On the Tech Station, you'll see grab, done, tested, and cost entry buttons.

Use the **back arrow** to return to the Job Board.

### Editing a Draft Work Order

If you tapped "Save as Draft" when creating a work order and need to come back to finish it, tap the draft card on the Job Board to open it.

On a draft, you can **tap the customer section** in the header to assign or change the customer. If no customer has been assigned yet, you'll see "Tap to assign customer" with a small arrow. This opens a customer search sheet where you can look up an existing customer, add a new one, or remove the current customer. Tap **Save** to apply your changes.

You can also **tap any item card** to edit it. This opens an edit sheet where you can change the equipment type, service reasons, description, and any other fields. Tap **Save** when you're done — the changes save to the server immediately.

If an item is still missing required fields (like Equipment Type or Reason for Service), the item card will have a **light orange background** with a **"Complete Item Info" button** at the bottom. Tap anywhere on the card — or tap the button — to open the edit sheet and fill in what's missing. Items that are already complete show a normal white background.

#### Adding More Items to a Draft

Below the item cards on a draft, you'll see an **"+ Add Item"** button. Tap it to add another item to the work order — same form as when you created the original items (equipment type, service reasons, description, photos). The new item appears in the list immediately after you tap **Add**.

### Editing a Checked-In Item

After a work order is finalized (no longer a draft), you can still edit an item's intake information — equipment type, machine type, service reasons, and description — **as long as the item hasn't been grabbed by a tech yet**.

While the item is in **Checked In** status, you'll see a small **pencil icon** on the item card. Tap the card to open the edit sheet, make your changes, and tap **Save**.

Once a tech grabs the item (moves it to In Progress), the intake fields lock. The pencil icon disappears and tapping the card no longer opens the editor. This prevents accidental changes to information the tech is already working from.

**Photos and notes are never locked.** You can add photos and notes to any item at any status (except Totaled), even after the intake fields are locked.

**Admin override:** If an admin needs to correct intake fields on an item that's already In Progress or beyond, they can elevate admin access on the device (enter their PIN), and the edit option becomes available again regardless of status.

### Changing the Customer on a Job

You can change the customer assigned to a work order — not just on drafts, but on finalized jobs too.

**While all items are still Checked In:** Tap the customer name in the job header. You'll see a small **arrow** indicating it's tappable. This opens the customer search sheet where you can look up a different customer, add a new one, or remove the current customer. Tap **Save** to apply.

**Once any item has been grabbed by a tech** (moved to In Progress), the customer section locks and is no longer tappable. This prevents accidental customer changes on jobs that are actively being worked on.

**Admin override:** If an admin needs to reassign a customer on a job that's already in progress, they can elevate admin access (enter their PIN) and the customer section becomes tappable again regardless of item statuses.

This works the same way as editing a draft — the customer picker sheet is identical. The only difference is when it's available.

### Finalizing a Draft

Once all required fields are filled in on a draft, the **Finalize** button in the top right corner becomes active.

Tap **Finalize** to convert the draft into a real work order. The app will:

1. Generate a job number (e.g., 20260325-4)
2. Show a brief **"Finalized!"** confirmation with the new job number
3. Automatically return you to the Job Board

The job now appears as a regular work order card (no more DRAFT badge) and is visible to the Tech Station.

### Customer Check-In

Coming soon.

### Complete & Pickup

Coming soon.

---

## Customers

The Customers view is a browsable list of all your customers with a detail screen showing their full job history. It's available on Front Counter and Admin devices via the sidebar.

### Customer List

Open the sidebar and tap **Customers** to see the customer list. Every customer in the system is listed alphabetically, showing their name, company (if any), phone number, and a badge with their total number of jobs.

Customers marked as **Tax Exempt** have an orange badge next to their name.

**Searching:** Type in the search bar at the top to filter by name, company, or phone number. The list filters as you type. Tap the **X** to clear the search.

Pull down to refresh the list.

### Customer Detail

Tap any customer in the list to see their detail screen. At the top is a card with their contact info — phone number, company, email, and tax exempt status.

If a customer is tax exempt and has a certificate on file, you'll see a blue **View Certificate** link next to the orange "Tax Exempt" badge. Tap it to open the certificate image.

Below that, you'll see all of that customer's jobs split into two sections:

**Active Jobs** — any jobs that are still being worked on, shown as full cards with photos (same cards as the Job Board). If the customer has no active jobs, this section doesn't appear.

**Past Jobs** — closed and totaled jobs shown as compact rows with the job number, equipment summary (e.g., "Cylinder × 2 · Pump × 1"), date range (when it was created and when it was closed), item count, and status dots.

Tap any job — active or past — to open the full job detail view with all items, photos, notes, and history. Use the back arrow to return to the customer detail.

This is especially useful for warranty lookups ("didn't we just fix this customer's cylinder last month?") and getting context on repeat customers.

### Editing a Customer

Tap **Edit** in the top-right corner of any customer's detail screen to open the edit form. You can update:

- **Name** and **Company** — with the same smart swap button as the new customer form
- **Phone** and **Email**
- **Tax Exempt** toggle — turn on or off as needed

**Uploading a tax exemption certificate:** When Tax Exempt is toggled on, you'll see a certificate section. Tap **Upload Certificate** to choose a photo from your library. A preview appears once selected — tap the **×** to remove it if you picked the wrong one. The certificate uploads automatically when you tap **Save**. If a certificate is already on file, you'll see "Certificate on file" with a **Replace** option to swap it out.

**Toggling off Tax Exempt** automatically removes the certificate link from the customer's record.

Tap **Save** to apply your changes. Tap **Cancel** to discard them.

---

## Tech Station

The Tech Station iPad is the back shop's primary tool. It shows a queue of all items that need work — not grouped by job, but as individual items. Techs don't care that three cylinders came from the same customer; they care about the cylinder on the bench.

### Repair Queue

When you open the app on a Tech Station device, you see the **item queue** — a grid of cards showing all items that need work. The cards are sorted by status: In Progress items first, then items waiting for a tech to grab, then tested items that need a cost entered.

Each card shows:

- **Item photo** — the top half of every card is a large square photo of the equipment. The photo has a colored **status dot** in the top-right corner and an **equipment type label** in the bottom-right corner, same as the Front Counter cards. If no photo has been taken yet, you'll see a gray placeholder.
- **Status label** — text below the photo showing the item's current stage (e.g., "Checked In", "In Progress", "Ready for Test")
- **Equipment type** (e.g., Cylinder, Pump, Hose)
- **Customer name** and **job number**
- **Assigned tech's name** — if someone has grabbed it
- **READY badge** — orange badge on items where repair is done and it's waiting on testing

Photos load in the background, so cards appear instantly and photos fill in a moment later.

Items with the READY badge also have a warm orange tint on the card so they stand out.

Tap any card to open the item detail view with actions for whatever the item needs next.

Pull down to refresh the queue. The grid adapts automatically when you rotate the iPad between landscape and portrait.

### Searching and Filtering the Queue

The Tech Station toolbar has a **search bar** and a **filter button**, same as the Front Counter.

**Searching:** Tap the search bar and type to filter the queue in real time. You can search by:

- Equipment type (e.g., "Cylinder")
- Customer name or job number
- Tech name (e.g., "Tony")
- Machine type or item description
- Service reason (e.g., "Seal")

**Filtering:** Tap the filter button to open a filter sheet with pickers for Equipment Type, Status (Checked In, In Progress, Tested), Machine Type (if enabled), and Reason for Service (multi-select).

Active filters show as removable chips below the toolbar, same as the Front Counter. Tap **X** on a chip to remove it, or **Clear All** to reset everything.

If nothing matches, you'll see "No Matching Items" instead of the grid.

### Adding Photos from the Tech Station

When you open an item detail, you'll see a row of photo thumbnails at the top of the info card (if any photos exist) along with **Camera** and **Library** buttons. Techs can add photos at any point during the repair — before starting, during disassembly, after the fix, or whenever something is worth documenting. Tapping **Camera** opens the continuous camera: tap the shutter as many times as you need, watch the thumbnails appear at the bottom of the screen, then tap **Done** when you're finished. No need to reopen the camera between shots.

Tap any thumbnail to view the photo full-screen. Tap the photo or swipe down to close. Photos with markup show a small blue pencil badge on their thumbnail.

Photos are permanent — once uploaded, they can't be deleted. This is intentional so there's always a complete visual record of what happened with each item.

#### Marking Up Photos (Tech Station)

Techs can mark up photos the same way the front counter does — tap a thumbnail to go full-screen, then tap **Markup** to open the Apple pencil editor. This is useful for writing the price on a photo, circling what was repaired, or noting anything the front counter should see.

The full markup toolbar is available: pens, markers, pencils, erasers, ruler, and all colors. Tap **Save** when done. Previous markup strokes are preserved for re-editing. See "Marking Up Photos" in the Front Counter section above for the full details on how markup, revert, and re-editing work.

### Adding Notes from the Tech Station

When you open an item detail from the tech queue, you'll see a **Notes** card between the item info and the test history. This works the same as on the front counter — type a note, tap the send arrow, and it's saved with your name and timestamp.

Use notes to document what you found during disassembly, anything unusual about the repair, or messages for the front counter ("customer needs to approve cost before we proceed"). Notes from both the front counter and the tech station show up in the same timeline, so everyone stays on the same page.

### Editing Item Info from the Tech Station

When you open an item detail, you may see a small blue **Edit** link in the top-right corner of the item info card. This lets you change the intake fields — equipment type, machine type, service reasons, and description — without going back to the front counter.

The Edit button only appears when the item is in **Checked In** status (before anyone grabs it). Once the item is In Progress, the intake fields lock and the Edit link disappears. An admin can still edit locked fields by elevating admin access.

Photos and notes are always editable regardless of item status (see "Adding Photos" and "Adding Notes" sections).

### Grabbing an Item

When a new item shows up in "Waiting for Tech," any tech can grab it:

1. Tap the item card to open it
2. Tap the **Grab** button (yellow, big and easy to hit)
3. A picker appears — tap your name from the list
4. You'll see a quick **"Grabbed!"** confirmation, then the app automatically takes you back to the queue

Whoever grabs it first gets it. If it needs to be reassigned later (tech goes home sick, owner decides someone else should take over), see "Reassigning a Tech" below.

### Reassigning a Tech

Sometimes a job needs to go to a different tech — maybe someone went home sick, or the owner wants a specific person on it. You can reassign any item that's currently In Progress:

1. Open the item from the queue
2. Tap the **Reassign** button (purple)
3. A picker appears — tap the name of the tech who should take over
4. You'll see a quick **"Reassigned!"** confirmation, then the app takes you back to the queue

The new tech will see the item in their queue. The repair clock resets when you reassign — the new tech gets a fresh start time.

Reassign is available on Tech Station and Admin devices. It doesn't matter what stage of repair the item is in — as long as it's In Progress, you can reassign it.

### Repair Checklist

When you open an In Progress item, you'll see a **Repair Checklist** section with green pill-shaped buttons for each type of repair work: Wiper, Seal, Buffer Seal, Wear Bands, U Seal, Epoxy, Welding, Rod Damage, Oil Sample, Dented, and Other.

**Tap each pill to check off what you actually did.** Selected pills turn green; unselected ones stay outlined. You can tap a green pill again to uncheck it if you made a mistake.

If you select **Other**, a text field appears where you can describe the work that doesn't fit the standard categories.

**You must check at least one item on the repair checklist before you can tap Done.** If nothing is checked, the Done button is grayed out and you'll see an orange warning: "Check at least one before marking Done." This is so there's always a record of what was actually done to the item — same as the paper checklist Tony fills out today.

Your selections save to the server immediately as you tap them — no need to hit a save button.

After the item is marked Done or Tested, the checklist stays visible as a read-only record of what was done.

If an item fails a test and comes back for another round, the checklist resets to empty for the new round. You'll see a red **Round 2** badge next to the "Repair Checklist" header so you know which round you're on. The previous round's checklist is preserved in the history card below (see "Previous Round Checklists").

### Marking Repair as Done

Once you've finished repairing an item and checked off what you did on the repair checklist:

1. Open the item from the queue
2. Make sure you've checked at least one item on the **Repair Checklist** (see above)
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

The item moves to the **Tested** status and the detail screen stays open so the tester can enter cost right away (see next section). If the tester walks away without entering cost, the app will automatically return to the queue after the inactivity timeout (see "Auto-Return to Queue" below).

**If FAILED:**

The item goes back to **In Progress** and a new repair round begins. The same tech stays assigned — it's their job to fix whatever failed. No extra taps, no "are you sure?" — it just goes straight back. The app shows a brief "Sent Back — Round 2" confirmation and returns to the queue. The tech will see the item back in their queue with a red **Rd 2** badge, a fresh empty repair checklist, and the previous round's checklist preserved in the history card (see "Previous Round Checklists" below).

An item can fail and loop back as many times as needed. Each round is tracked separately.

If a different tech needs to take over after a failed test, use the **Reassign** button on the item (see "Reassigning a Tech" above).

### Oil Sample

You can record an oil sample on any item that's at the **Ready for Test** or **Tested** stage. This is optional — not every item needs one.

1. Open the item
2. Tap the **Oil Sample** button (blue)
3. Pick the condition: **Clean** or **Dirty**
4. Add any notes in the text field (optional)
5. **Take photos (optional)** — below the notes field you'll see **Camera** and **Library** buttons, same as the photo buttons used during intake. Tap Camera to snap a picture of the oil sample, or Library to pick one from the device. You can add multiple photos — each one appears as a thumbnail with an **X** to remove it if you change your mind.
6. Select who performed the sample
7. Tap **Submit**

Photos upload automatically when you submit. Oil samples (with any attached photos) show up in the Test & Sample History card on the item detail (see below). You can record multiple oil samples on the same item if needed.

### Previous Round Checklists

When an item fails a test and goes back for another repair round, the previous round's checklist doesn't disappear — it's preserved in the history card below the current repair checklist.

You'll see a section labeled **"Round 1 Checklist"** (or whichever round) with a comma-separated list of everything that was checked off during that round. If there have been multiple failed rounds, each one gets its own labeled list.

This way the tech on Round 2 can see exactly what was done in Round 1 without having to ask anyone.

### Test & Sample History

Below the repair checklist on the item detail, there's a **Test & Sample History** card that shows a chronological timeline of all test attempts and oil samples for the item. Each entry shows:

- **Test results** — PASSED or FAILED with the round number, who tested it, and when
- **Oil samples** — Clean or Dirty, who performed it, when, any notes, and photo thumbnails if photos were attached

This card only appears once there's at least one test or oil sample recorded.

### Entering Cost

After testing, the item needs a cost before it can go back to the front counter:

1. Open the tested item (or stay on it after testing)
2. Tap **Enter Cost** (green)
3. Enter the cost — how this looks depends on your shop settings:
   - **Standard mode (default):** One field — type the total dollar amount
   - **Parts + Labor mode:** Two fields — **Parts ($)** and **Labor ($)**. The total calculates automatically as you type.
4. If the shop has **Sales Tax** enabled, you'll see a **"Taxable"** (or **"Taxable Parts"** in Parts + Labor mode) toggle. Turn it on if this item's parts are subject to sales tax. The sheet updates to show Subtotal, Tax, and Total so you can confirm the amount before submitting.
5. Tap **Submit**
6. You'll see a prompt: "Was that cost approved by a manager?" — tap **Yes** if a manager signed off, or **No** to go back and confirm first
7. The item moves to **Complete** (green) and appears on the front counter for customer pickup

For totaled items with $0 cost, the manager approval step is skipped automatically.

*(Parts + Labor mode and Sales Tax are turned on and off by an admin in Admin Settings → Shop Settings.)*

### Totaling an Item

If an item is unfixable:

1. Open the item
2. Tap the **Totaled** button (black in light mode, white in dark mode)
3. Confirm — you'll see a **"Totaled"** confirmation and the app takes you back to the queue
4. If there's a diagnostic cost, enter it through the normal cost flow. If not, enter $0 and it moves straight to Complete.

### About the Action Buttons

All action buttons on the Tech Station (Grab, Done, Tested, Reassign, Enter Cost, Totaled, Close) are intentionally large. They're designed so techs can tap them quickly without fiddling around, even with dirty or gloved hands. On iPad, the buttons sit side by side in a row. On iPhone (used by admins), the buttons stack vertically and stretch full-width so they're still easy to tap on the smaller screen. After any "walk-away" action (anything where you're done with that item for now), the app shows a brief confirmation and automatically returns you to the repair queue.

### Auto-Return to Queue

If someone opens an item detail and walks away without doing anything for 2 minutes, the app automatically returns to the repair queue. This way the Tech Station iPad is always showing the queue when no one's actively using it — the next person who walks up sees the full list of items, not whatever the last tech was looking at.

Any touch on the screen (scrolling, tapping, typing) resets the 2-minute timer. You don't need to do anything special — just use the app normally and the timer stays out of your way. It only kicks in when nobody's touching the iPad at all.

The timeout is configurable by an admin (default is 2 minutes). Setting it to 0 disables it entirely.

### Role Switcher (Debug Only)

During development, you'll see a small purple **ladybug button** in the bottom-left corner. Tap it to switch between Front Counter, Tech Station, and Admin views without resetting the device. This only appears in debug/test builds — it won't be in the final app.

---

## Admin

*This section will be filled in as Admin features are built.*

### Employee Management

Employee management is where you add, edit, and deactivate the people who use ShopTracker.

**Getting there:** Open Admin Settings and tap **Employees** under the "Shop" section.

#### Viewing Employees

You'll see a list of all active employees, each showing their name, role badge (Tech, Admin, or Tester), and an "Authorized Tester" badge if they're allowed to test items. Inactive employees appear in a separate section at the bottom.

Pull down to refresh the list.

#### Adding an Employee

1. Tap the **+** button in the top right corner
2. Enter the employee's **name**
3. Pick their **role** using the segmented control:
   - **Tech** — can grab items, do repairs, and mark done
   - **Admin** — full access to all views and settings (will need a PIN)
   - **Tester** — dedicated tester role
4. Toggle **Authorized Tester** on if this person should be able to test items, regardless of their role (e.g., a tech who also tests)
5. Tap **Add**

The new employee will immediately appear in all relevant pickers across the app (tech assignment, tester selection, etc.).

#### Editing an Employee

Tap any active employee in the list to open their edit form. You can change their name, role, or tester authorization. Tap **Save** when done.

**Note:** PINs are not managed here. If an admin needs to set or change their PIN, they do it through the normal PIN entry flow during Device Setup.

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

If a required field is missing when Maria tries to create a job, the form won't let her save and the missing field gets highlighted.

### Manage Lists

Manage Lists is where you control the dropdown options used throughout the app. Accessible from Admin Settings → **Manage Lists** under the "Shop" section.

There are five lists you can manage:

- **Equipment** — what the item IS (Cylinder, Pump, Hose, Other...)
- **Mach Type** — what it came off of (Forklift, Excavator, Skid Steer...) — only shows up in job intake if Machine Type is turned on in Shop Settings
- **Brand** — who made the machine (Caterpillar, John Deere, Komatsu...) — only shows up in job intake if Machine Brand is turned on in Shop Settings
- **Service** — the Reason for Service pills on the intake form
- **Issues** — the repair checklist items techs check off when marking work done

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

### Reports

Coming soon.

### Resetting a Device

If a device needs to be reassigned (different role, different name, or just starting fresh):

1. Open the Admin view on an admin-role device (or elevate admin access on the target device)
2. Tap **Reset Device**
3. The device will forget its identity and show the setup screen again on next launch
4. Go through the setup process to assign a new name and role

---

## Troubleshooting

### "Incorrect PIN"

Double-check that you're entering your personal admin PIN (4-8 digits). PINs are per-person, not per-device. If you've forgotten your PIN, another admin will need to help you reset it. *(PIN reset feature coming in a future update.)*

### The app shows "Connecting..." on launch

ShopTracker needs an internet connection on first launch to download your jobs and settings. After that, it caches everything locally so you can keep working even if Wi-Fi drops (see "Working Offline" below). If you're stuck on "Connecting..." with a good Wi-Fi signal, the issue may be on the server side — let Bec know.

---

## Working Offline

ShopTracker is designed to keep working when the shop Wi-Fi drops. Here's what you need to know:

### What still works without internet

As long as you've opened the app at least once with a connection (so it can download your data), you can still:

- Browse the job board and see all your jobs, items, and customer info
- View photos that have been loaded before (they're saved on the iPad)
- Grab items, mark repairs done, move items through the status flow
- Add notes and check issue checklists
- Enter costs and close items

All of those changes are saved on the iPad and will automatically sync to the server as soon as the connection comes back. You don't have to do anything — the app handles it.

### What doesn't work without internet

- Creating brand new jobs (the server generates the job number)
- Uploading new photos
- Looking up customers you haven't seen before
- Any changes other people make on their devices won't show up until you're back online

### When the connection comes back

The app detects when Wi-Fi returns and automatically sends any changes you made while offline. This usually takes a few seconds.

If someone else made changes to the same item on a different device while you were offline, the app figures it out automatically. It compares what you changed against what the other device changed — if you edited different fields (e.g., you marked it Done while Maria added a note), both changes go through. If you both changed the same thing, the most recent change wins. You don't need to do anything — it just works.

If something goes wrong during sync (rare), Bec can see it in **Admin Settings → Sync Status**. The dashboard shows which changes are pending, which failed, and why. From there you can retry failed items, force a sync, or clear the queue entirely if needed.

### Tips

- Don't worry about saving — everything saves automatically, online or off
- If you're not sure whether you're online, look for the **offline banner** at the top of the Job Board or Work Queue. It appears automatically when the iPad loses its connection and disappears when you're back online. If you've made changes while offline, the banner will tell you how many are queued (e.g., "Offline — 3 changes will sync when back online"). The data on screen is still usable — it's just a snapshot from the last time you had a connection.

### A device is showing the wrong role

An admin will need to reset the device and set it up again with the correct role. See "Resetting a Device" above.

---

*More sections will be added as features are built. This manual is a living document.*

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

**To change the display size:**

1. Open the sidebar (swipe from the left, or tap the back arrow in the top-left)
2. At the bottom of the sidebar, under **This Device**, tap **Display Size**
3. A settings panel slides up from the bottom

**Text Size** — three options:
- **Default** — standard size, same as most apps
- **Large** — noticeably bigger, good for extended use or reading glasses situations
- **Extra Large** — significantly bigger, designed for arm's-length viewing or anyone who needs more visual breathing room

**Bold Text** — toggle this on to make all text heavier/darker throughout the app. Works independently from the size setting — you can have bold text at any size.

Changes take effect immediately and are saved to this device only. The front counter iPad, back shop station, and admin device each remember their own settings.

---

## Front Counter

### Job Board

When you open the app on a Front Counter device, you'll see the **Job Board** — a grid of cards showing all active work orders. Each card shows:

- **Item photos** — the top half of every card is a square photo area showing the equipment. If a job has one item, you see one big photo. Two items show stacked photos. Three or four items show a 2×2 grid. If there are more than four items with photos, the last tile shows a "+N" badge so you know there's more. Each photo has a small colored **status dot** in the top-right corner and an **equipment type label** (e.g., "Cylinder") in the bottom-right corner.
- **Job number** (e.g., 20260325-1) and **status dots** — one colored dot per item showing where it is in the repair process (blue = checked in, yellow = being worked on, orange = tested, green = ready for pickup)
- **Customer phone number** (tappable) and **name**
- **Equipment summary** (e.g., "Pump × 1 · Cylinder × 2") and the date/time the job was created

Photos load in the background — you'll see the cards appear right away with placeholder tiles, and the actual photos fill in a moment later.

**Draft work orders** appear at the top with an orange "DRAFT" badge and a warm-tinted background so they stand out as unfinished.

When all items on a job have been priced and approved, a green **"COMPLETE"** badge appears in the top-left corner of the card's photo area — slightly tilted, just like in V1. This is your at-a-glance signal that the job is ready for customer pickup and payment.

Jobs are sorted by urgency: green (ready for pickup) first, then orange (tested), then yellow (in progress), then blue (just checked in). Within each group, the oldest jobs appear first. This way the items closest to being done — the ones a customer might be waiting on — are always at the top.

Pull down on the job board to refresh and see the latest updates from the back shop.

Tap the **pencil icon** in the top right corner to create a new work order.

### Searching and Filtering Jobs

Next to the pencil icon in the toolbar, you'll see a **search bar** and a **filter button** (circle with three lines).

**Searching:** Tap the search bar and start typing. The board filters in real time as you type. You can search by:

- Customer name, phone number, or company
- Job number (e.g., "20260325")
- Equipment type (e.g., "Cylinder")
- Machine type or item description
- Service reason (e.g., "Leaking")

The search checks all items within each job, so searching "Pump" will show any job that has at least one pump in it. Tap the **X** in the search bar to clear your search and see all jobs again.

**Filtering:** Tap the filter button to open a filter sheet with dropdown pickers:

- **Equipment Type** — show only jobs with a specific type of equipment (Cylinder, Pump, etc.)
- **Status** — show only jobs with items at a specific stage (Checked In, In Progress, Tested, Complete)
- **Machine Type** — if machine types are turned on in admin settings, you can filter by those too
- **Reason for Service** — tap one or more service reasons to filter by why the equipment was brought in. If you select multiple reasons, the job must have an item with ALL of those reasons.

When filters are active, the filter button fills in blue and a row of **filter chips** appears below the toolbar. Each chip shows what's being filtered (e.g., "Type: Cylinder") with an **X** to remove that specific filter. Tap **Clear All** to remove all filters at once.

If your search or filters don't match any jobs, you'll see a "No Matching Jobs" message instead of the grid.

### Closed Jobs (Job History)

At the bottom of the Job Board, you'll see a **Closed** section with a count of how many jobs are fully closed or totaled. This section is collapsed by default so it doesn't clutter the active board.

Tap the **Closed** header to expand it. You'll see the same card grid as above, but for jobs that are done — all items either closed or totaled. The cards are slightly dimmed so they're easy to tell apart from active jobs.

Tap the header again to collapse the section back down.

Your search and filters work across both active and closed jobs. If you search for a customer name and they have a closed job that matches, you'll see it in the closed section (expand it to check).

This is useful for looking up past work — warranty questions, repeat customers, or just checking what was done on an old job. Tap any closed job card to see the full detail view with all items, photos, and notes.

### Creating a New Work Order

Tap the pencil icon from the Job Board to start a new work order. The form has two main sections: **Customer** and **Items**.

#### Finding or Adding a Customer

At the top of the form, start typing a customer's name or phone number. Matching customers will appear below the search field as you type. Tap a result to select them.

If the customer isn't in the system yet, tap **+ Add New Customer** to create one. The new customer form includes:

- **Name** (required) — if you type a business name (ending in Inc, LLC, Corp, etc.), the app will automatically move it to the Company field
- **Company** (optional) — use the **Swap** button if the name/company got put in the wrong field
- **Phone** (required, 10 digits) — formats automatically as you type. If the phone number is already on file for another customer, you'll be warned and can choose to use the existing customer instead
- **Email** (optional)
- **Tax Exempt** toggle

#### Adding Items

Each work order needs at least one item. For each item, fill in:

- **Equipment Type** — what the item is (Cylinder, Pump, Hose, or Other)
- **Reason(s) for Service** — tap the pill-shaped buttons to select why the customer brought it in (Leaking, Barrel Damage, Bushings, etc.). You can select multiple reasons.
- **Description / Notes** — any additional details about the item

Tap **+ Add Item** to add more items to the same work order (e.g., a customer drops off 3 cylinders at once).

To remove an item, tap the trash icon next to its header. You can't remove the last item.

#### Taking Photos During Intake

Each item has a **Photos** section at the bottom of the form. This is a great time to photograph the equipment as it comes in — document any existing damage, serial numbers, or anything else worth capturing before the tech starts work.

You have two options:

- **Camera** — tap the camera button to open the camera. The camera stays open between shots — tap the shutter button as many times as you need, and each photo appears in a strip at the bottom of the screen. When you're done, tap **Done** in the top-right corner to close the camera and return to the form. You can also tap **Cancel** to close the camera at any time — photos you already took are kept.
- **Library** — tap the library button to pick a photo already on the device (useful if someone snapped a picture before opening the app)

Photos appear as small thumbnails next to the buttons. To remove a photo before saving, tap the **X** on the thumbnail. Photos aren't uploaded until you tap "Create Work Order" or "Save as Draft" — you'll see a brief "Uploading..." indicator while they're sent to the server.

There's no limit on photos per item. Take as many as you need.

#### Saving

The button in the top right changes based on what you've filled in:

- **"Create Work Order"** — appears when all required fields are filled in (customer, equipment type, at least one reason for service). This creates the work order with a job number and makes it visible to the back shop.
- **"Save as Draft"** — appears when required fields are still missing. This saves your progress so you can come back to it later. Drafts appear at the top of your Job Board with an orange badge but are NOT visible to the Tech Station.

### Viewing a Job (Job Detail)

Tap any card on the Job Board to open the full job detail view. This shows everything about the work order in one place.

At the top you'll see a **header card** with:

- **DRAFT badge** (orange) or **job number** (e.g., 20260325-1)
- **Customer name, phone number, and company** (if applicable)
- **Status dots** — one colored dot per item, same colors as the Job Board
- **Item count** and **creation date/time**

Draft jobs have a warm amber-tinted header, just like on the Job Board.

Below the header, each **item** gets its own card showing:

- **Item number** and **status** (with a colored badge like "Checked In" in blue, "In Progress" in yellow, etc.)
- **Equipment Type** — what the item is
- **Machine Type** and **Color** — if those fields are turned on in admin settings
- **Reason(s) for Service** — shown as blue pill-shaped tags
- **Description / Notes** from intake
- **Assigned tech** — if a tech has grabbed the item, you'll see their name (e.g., "Assigned to Carlos")

If photos have been taken for an item, you'll see a row of **photo thumbnails** near the top of the item card. Tap any thumbnail to view it full-screen — tap the photo or swipe down to close the full-screen view. Photos that have been marked up show a small blue pencil badge on their thumbnail so you can tell at a glance which ones have annotations.

You can add more photos to any item at any time, regardless of its status. Next to the thumbnails you'll see **Camera** and **Library** buttons — same as during check-in. Tapping **Camera** opens the continuous camera: the shutter stays open so you can take multiple shots in one go, with a thumbnail strip at the bottom showing what you've captured. Tap **Done** when you're finished shooting. New photos upload immediately and appear in the thumbnail strip.

#### Marking Up Photos

This is the feature that replaces Apple Notes markup. Tap any photo thumbnail to open it full-screen, then tap the **Markup** button (pencil icon) in the top-right corner. This opens the Apple PencilKit editor with the full native toolbar — pens, markers, pencils, erasers, ruler, and the complete color palette.

Draw directly on the photo to circle damage, write prices, add arrows, or annotate anything worth calling out. When you're done, tap **Save**. The marked-up version becomes what everyone sees on the job — on cards, in the detail view, everywhere.

**Your original photo is always preserved.** Markup is non-destructive. If you need to redo it (say the price changed), tap the photo again, tap Markup, and your previous strokes are still there — you can erase specific marks, add new ones, or start fresh with the trash button. If you want to remove all markup entirely, tap the **revert button** (curved arrow) in the toolbar and the photo goes back to the untouched original.

Markup is available on every photo at every status — Front Counter intake photos, Tech Station repair photos, any of them. There are no restrictions on who can mark up or when.

#### Notes

Each item card has a **Notes** section where you can add timestamped notes at any point in the workflow — before repair, during, after, whenever.

To add a note, type in the "Add a note..." field and tap the blue **send arrow**. The note is saved immediately with your name and the time. Notes appear newest-first so the latest info is always at the top.

Notes are visible to both the front counter and the tech station. Maria can jot down customer instructions ("needs by Friday"), and Tony can document what he found during repair. Everyone sees the same timeline.

Below each item card, you may see **action buttons** depending on the item's status and your device role. On the Front Counter, you can close items that are ready for pickup. On the Tech Station, you'll see grab, done, tested, and cost entry buttons.

Use the **back arrow** to return to the Job Board.

### Editing a Draft Work Order

If you tapped "Save as Draft" when creating a work order and need to come back to finish it, tap the draft card on the Job Board to open it.

On a draft, you can **tap the customer section** in the header to assign or change the customer. If no customer has been assigned yet, you'll see "Tap to assign customer" with a small arrow. This opens a customer search sheet where you can look up an existing customer, add a new one, or remove the current customer. Tap **Save** to apply your changes.

You can also **tap any item card** to edit it. This opens an edit sheet where you can change the equipment type, service reasons, description, and any other fields. Tap **Save** when you're done — the changes save to the server immediately.

If an item is still missing required fields (like Equipment Type or Reason for Service), the item card will have a **light orange background** with a **"Complete Item Info" button** at the bottom. Tap anywhere on the card — or tap the button — to open the edit sheet and fill in what's missing. Items that are already complete show a normal white background.

#### Adding More Items to a Draft

Below the item cards on a draft, you'll see an **"+ Add Item"** button. Tap it to add another item to the work order — same form as when you created the original items (equipment type, service reasons, description, photos). The new item appears in the list immediately after you tap **Add**.

### Editing a Checked-In Item

After a work order is finalized (no longer a draft), you can still edit an item's intake information — equipment type, machine type, service reasons, and description — **as long as the item hasn't been grabbed by a tech yet**.

While the item is in **Checked In** status, you'll see a small **pencil icon** on the item card. Tap the card to open the edit sheet, make your changes, and tap **Save**.

Once a tech grabs the item (moves it to In Progress), the intake fields lock. The pencil icon disappears and tapping the card no longer opens the editor. This prevents accidental changes to information the tech is already working from.

**Photos and notes are never locked.** You can add photos and notes to any item at any status (except Totaled), even after the intake fields are locked.

**Admin override:** If an admin needs to correct intake fields on an item that's already In Progress or beyond, they can elevate admin access on the device (enter their PIN), and the edit option becomes available again regardless of status.

### Changing the Customer on a Job

You can change the customer assigned to a work order — not just on drafts, but on finalized jobs too.

**While all items are still Checked In:** Tap the customer name in the job header. You'll see a small **arrow** indicating it's tappable. This opens the customer search sheet where you can look up a different customer, add a new one, or remove the current customer. Tap **Save** to apply.

**Once any item has been grabbed by a tech** (moved to In Progress), the customer section locks and is no longer tappable. This prevents accidental customer changes on jobs that are actively being worked on.

**Admin override:** If an admin needs to reassign a customer on a job that's already in progress, they can elevate admin access (enter their PIN) and the customer section becomes tappable again regardless of item statuses.

This works the same way as editing a draft — the customer picker sheet is identical. The only difference is when it's available.

### Finalizing a Draft

Once all required fields are filled in on a draft, the **Finalize** button in the top right corner becomes active.

Tap **Finalize** to convert the draft into a real work order. The app will:

1. Generate a job number (e.g., 20260325-4)
2. Show a brief **"Finalized!"** confirmation with the new job number
3. Automatically return you to the Job Board

The job now appears as a regular work order card (no more DRAFT badge) and is visible to the Tech Station.

### Customer Check-In

Coming soon.

### Complete & Pickup

Coming soon.

---

## Customers

The Customers view is a browsable list of all your customers with a detail screen showing their full job history. It's available on Front Counter and Admin devices via the sidebar.

### Customer List

Open the sidebar and tap **Customers** to see the customer list. Every customer in the system is listed alphabetically, showing their name, company (if any), phone number, and a badge with their total number of jobs.

Customers marked as **Tax Exempt** have an orange badge next to their name.

**Searching:** Type in the search bar at the top to filter by name, company, or phone number. The list filters as you type. Tap the **X** to clear the search.

Pull down to refresh the list.

### Customer Detail

Tap any customer in the list to see their detail screen. At the top is a card with their contact info — phone number, company, email, and tax exempt status.

If a customer is tax exempt and has a certificate on file, you'll see a blue **View Certificate** link next to the orange "Tax Exempt" badge. Tap it to open the certificate image.

Below that, you'll see all of that customer's jobs split into two sections:

**Active Jobs** — any jobs that are still being worked on, shown as full cards with photos (same cards as the Job Board). If the customer has no active jobs, this section doesn't appear.

**Past Jobs** — closed and totaled jobs shown as compact rows with the job number, equipment summary (e.g., "Cylinder × 2 · Pump × 1"), date range (when it was created and when it was closed), item count, and status dots.

Tap any job — active or past — to open the full job detail view with all items, photos, notes, and history. Use the back arrow to return to the customer detail.

This is especially useful for warranty lookups ("didn't we just fix this customer's cylinder last month?") and getting context on repeat customers.

### Editing a Customer

Tap **Edit** in the top-right corner of any customer's detail screen to open the edit form. You can update:

- **Name** and **Company** — with the same smart swap button as the new customer form
- **Phone** and **Email**
- **Tax Exempt** toggle — turn on or off as needed

**Uploading a tax exemption certificate:** When Tax Exempt is toggled on, you'll see a certificate section. Tap **Upload Certificate** to choose a photo from your library. A preview appears once selected — tap the **×** to remove it if you picked the wrong one. The certificate uploads automatically when you tap **Save**. If a certificate is already on file, you'll see "Certificate on file" with a **Replace** option to swap it out.

**Toggling off Tax Exempt** automatically removes the certificate link from the customer's record.

Tap **Save** to apply your changes. Tap **Cancel** to discard them.

---

## Tech Station

The Tech Station iPad is the back shop's primary tool. It shows a queue of all items that need work — not grouped by job, but as individual items. Techs don't care that three cylinders came from the same customer; they care about the cylinder on the bench.

### Repair Queue

When you open the app on a Tech Station device, you see the **item queue** — a grid of cards showing all items that need work. The cards are sorted by status: In Progress items first, then items waiting for a tech to grab, then tested items that need a cost entered.

Each card shows:

- **Item photo** — the top half of every card is a large square photo of the equipment. The photo has a colored **status dot** in the top-right corner and an **equipment type label** in the bottom-right corner, same as the Front Counter cards. If no photo has been taken yet, you'll see a gray placeholder.
- **Status label** — text below the photo showing the item's current stage (e.g., "Checked In", "In Progress", "Ready for Test")
- **Equipment type** (e.g., Cylinder, Pump, Hose)
- **Customer name** and **job number**
- **Assigned tech's name** — if someone has grabbed it
- **READY badge** — orange badge on items where repair is done and it's waiting on testing

Photos load in the background, so cards appear instantly and photos fill in a moment later.

Items with the READY badge also have a warm orange tint on the card so they stand out.

Tap any card to open the item detail view with actions for whatever the item needs next.

Pull down to refresh the queue. The grid adapts automatically when you rotate the iPad between landscape and portrait.

### Searching and Filtering the Queue

The Tech Station toolbar has a **search bar** and a **filter button**, same as the Front Counter.

**Searching:** Tap the search bar and type to filter the queue in real time. You can search by:

- Equipment type (e.g., "Cylinder")
- Customer name or job number
- Tech name (e.g., "Tony")
- Machine type or item description
- Service reason (e.g., "Seal")

**Filtering:** Tap the filter button to open a filter sheet with pickers for Equipment Type, Status (Checked In, In Progress, Tested), Machine Type (if enabled), and Reason for Service (multi-select).

Active filters show as removable chips below the toolbar, same as the Front Counter. Tap **X** on a chip to remove it, or **Clear All** to reset everything.

If nothing matches, you'll see "No Matching Items" instead of the grid.

### Adding Photos from the Tech Station

When you open an item detail, you'll see a row of photo thumbnails at the top of the info card (if any photos exist) along with **Camera** and **Library** buttons. Techs can add photos at any point during the repair — before starting, during disassembly, after the fix, or whenever something is worth documenting. Tapping **Camera** opens the continuous camera: tap the shutter as many times as you need, watch the thumbnails appear at the bottom of the screen, then tap **Done** when you're finished. No need to reopen the camera between shots.

Tap any thumbnail to view the photo full-screen. Tap the photo or swipe down to close. Photos with markup show a small blue pencil badge on their thumbnail.

Photos are permanent — once uploaded, they can't be deleted. This is intentional so there's always a complete visual record of what happened with each item.

#### Marking Up Photos (Tech Station)

Techs can mark up photos the same way the front counter does — tap a thumbnail to go full-screen, then tap **Markup** to open the Apple pencil editor. This is useful for writing the price on a photo, circling what was repaired, or noting anything the front counter should see.

The full markup toolbar is available: pens, markers, pencils, erasers, ruler, and all colors. Tap **Save** when done. Previous markup strokes are preserved for re-editing. See "Marking Up Photos" in the Front Counter section above for the full details on how markup, revert, and re-editing work.

### Adding Notes from the Tech Station

When you open an item detail from the tech queue, you'll see a **Notes** card between the item info and the test history. This works the same as on the front counter — type a note, tap the send arrow, and it's saved with your name and timestamp.

Use notes to document what you found during disassembly, anything unusual about the repair, or messages for the front counter ("customer needs to approve cost before we proceed"). Notes from both the front counter and the tech station show up in the same timeline, so everyone stays on the same page.

### Editing Item Info from the Tech Station

When you open an item detail, you may see a small blue **Edit** link in the top-right corner of the item info card. This lets you change the intake fields — equipment type, machine type, service reasons, and description — without going back to the front counter.

The Edit button only appears when the item is in **Checked In** status (before anyone grabs it). Once the item is In Progress, the intake fields lock and the Edit link disappears. An admin can still edit locked fields by elevating admin access.

Photos and notes are always editable regardless of item status (see "Adding Photos" and "Adding Notes" sections).

### Grabbing an Item

When a new item shows up in "Waiting for Tech," any tech can grab it:

1. Tap the item card to open it
2. Tap the **Grab** button (yellow, big and easy to hit)
3. A picker appears — tap your name from the list
4. You'll see a quick **"Grabbed!"** confirmation, then the app automatically takes you back to the queue

Whoever grabs it first gets it. If it needs to be reassigned later (tech goes home sick, owner decides someone else should take over), see "Reassigning a Tech" below.

### Reassigning a Tech

Sometimes a job needs to go to a different tech — maybe someone went home sick, or the owner wants a specific person on it. You can reassign any item that's currently In Progress:

1. Open the item from the queue
2. Tap the **Reassign** button (purple)
3. A picker appears — tap the name of the tech who should take over
4. You'll see a quick **"Reassigned!"** confirmation, then the app takes you back to the queue

The new tech will see the item in their queue. The repair clock resets when you reassign — the new tech gets a fresh start time.

Reassign is available on Tech Station and Admin devices. It doesn't matter what stage of repair the item is in — as long as it's In Progress, you can reassign it.

### Repair Checklist

When you open an In Progress item, you'll see a **Repair Checklist** section with green pill-shaped buttons for each type of repair work: Wiper, Seal, Buffer Seal, Wear Bands, U Seal, Epoxy, Welding, Rod Damage, Oil Sample, Dented, and Other.

**Tap each pill to check off what you actually did.** Selected pills turn green; unselected ones stay outlined. You can tap a green pill again to uncheck it if you made a mistake.

If you select **Other**, a text field appears where you can describe the work that doesn't fit the standard categories.

**You must check at least one item on the repair checklist before you can tap Done.** If nothing is checked, the Done button is grayed out and you'll see an orange warning: "Check at least one before marking Done." This is so there's always a record of what was actually done to the item — same as the paper checklist Tony fills out today.

Your selections save to the server immediately as you tap them — no need to hit a save button.

After the item is marked Done or Tested, the checklist stays visible as a read-only record of what was done.

If an item fails a test and comes back for another round, the checklist resets to empty for the new round. You'll see a red **Round 2** badge next to the "Repair Checklist" header so you know which round you're on. The previous round's checklist is preserved in the history card below (see "Previous Round Checklists").

### Marking Repair as Done

Once you've finished repairing an item and checked off what you did on the repair checklist:

1. Open the item from the queue
2. Make sure you've checked at least one item on the **Repair Checklist** (see above)
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

The item moves to the **Tested** status and the detail screen stays open so the tester can enter cost right away (see next section). If the tester walks away without entering cost, the app will automatically return to the queue after the inactivity timeout (see "Auto-Return to Queue" below).

**If FAILED:**

The item goes back to **In Progress** and a new repair round begins. The same tech stays assigned — it's their job to fix whatever failed. No extra taps, no "are you sure?" — it just goes straight back. The app shows a brief "Sent Back — Round 2" confirmation and returns to the queue. The tech will see the item back in their queue with a red **Rd 2** badge, a fresh empty repair checklist, and the previous round's checklist preserved in the history card (see "Previous Round Checklists" below).

An item can fail and loop back as many times as needed. Each round is tracked separately.

If a different tech needs to take over after a failed test, use the **Reassign** button on the item (see "Reassigning a Tech" above).

### Oil Sample

You can record an oil sample on any item that's at the **Ready for Test** or **Tested** stage. This is optional — not every item needs one.

1. Open the item
2. Tap the **Oil Sample** button (blue)
3. Pick the condition: **Clean** or **Dirty**
4. Add any notes in the text field (optional)
5. **Take photos (optional)** — below the notes field you'll see **Camera** and **Library** buttons, same as the photo buttons used during intake. Tap Camera to snap a picture of the oil sample, or Library to pick one from the device. You can add multiple photos — each one appears as a thumbnail with an **X** to remove it if you change your mind.
6. Select who performed the sample
7. Tap **Submit**

Photos upload automatically when you submit. Oil samples (with any attached photos) show up in the Test & Sample History card on the item detail (see below). You can record multiple oil samples on the same item if needed.

### Previous Round Checklists

When an item fails a test and goes back for another repair round, the previous round's checklist doesn't disappear — it's preserved in the history card below the current repair checklist.

You'll see a section labeled **"Round 1 Checklist"** (or whichever round) with a comma-separated list of everything that was checked off during that round. If there have been multiple failed rounds, each one gets its own labeled list.

This way the tech on Round 2 can see exactly what was done in Round 1 without having to ask anyone.

### Test & Sample History

Below the repair checklist on the item detail, there's a **Test & Sample History** card that shows a chronological timeline of all test attempts and oil samples for the item. Each entry shows:

- **Test results** — PASSED or FAILED with the round number, who tested it, and when
- **Oil samples** — Clean or Dirty, who performed it, when, any notes, and photo thumbnails if photos were attached

This card only appears once there's at least one test or oil sample recorded.

### Entering Cost

After testing, the item needs a cost before it can go back to the front counter:

1. Open the tested item (or stay on it after testing)
2. Tap **Enter Cost** (green)
3. Enter the cost — how this looks depends on your shop settings:
   - **Standard mode (default):** One field — type the total dollar amount
   - **Parts + Labor mode:** Two fields — **Parts ($)** and **Labor ($)**. The total calculates automatically as you type.
4. If the shop has **Sales Tax** enabled, you'll see a **"Taxable"** (or **"Taxable Parts"** in Parts + Labor mode) toggle. Turn it on if this item's parts are subject to sales tax. The sheet updates to show Subtotal, Tax, and Total so you can confirm the amount before submitting.
5. Tap **Submit**
6. You'll see a prompt: "Was that cost approved by a manager?" — tap **Yes** if a manager signed off, or **No** to go back and confirm first
7. The item moves to **Complete** (green) and appears on the front counter for customer pickup

For totaled items with $0 cost, the manager approval step is skipped automatically.

*(Parts + Labor mode and Sales Tax are turned on and off by an admin in Admin Settings → Shop Settings.)*

### Totaling an Item

If an item is unfixable:

1. Open the item
2. Tap the **Totaled** button (black in light mode, white in dark mode)
3. Confirm — you'll see a **"Totaled"** confirmation and the app takes you back to the queue
4. If there's a diagnostic cost, enter it through the normal cost flow. If not, enter $0 and it moves straight to Complete.

### About the Action Buttons

All action buttons on the Tech Station (Grab, Done, Tested, Reassign, Enter Cost, Totaled, Close) are intentionally large. They're designed so techs can tap them quickly without fiddling around, even with dirty or gloved hands. On iPad, the buttons sit side by side in a row. On iPhone (used by admins), the buttons stack vertically and stretch full-width so they're still easy to tap on the smaller screen. After any "walk-away" action (anything where you're done with that item for now), the app shows a brief confirmation and automatically returns you to the repair queue.

### Auto-Return to Queue

If someone opens an item detail and walks away without doing anything for 2 minutes, the app automatically returns to the repair queue. This way the Tech Station iPad is always showing the queue when no one's actively using it — the next person who walks up sees the full list of items, not whatever the last tech was looking at.

Any touch on the screen (scrolling, tapping, typing) resets the 2-minute timer. You don't need to do anything special — just use the app normally and the timer stays out of your way. It only kicks in when nobody's touching the iPad at all.

The timeout is configurable by an admin (default is 2 minutes). Setting it to 0 disables it entirely.

### Role Switcher (Debug Only)

During development, you'll see a small purple **ladybug button** in the bottom-left corner. Tap it to switch between Front Counter, Tech Station, and Admin views without resetting the device. This only appears in debug/test builds — it won't be in the final app.

---

## Admin

*This section will be filled in as Admin features are built.*

### Employee Management

Employee management is where you add, edit, and deactivate the people who use ShopTracker.

**Getting there:** Open Admin Settings and tap **Employees** under the "Shop" section.

#### Viewing Employees

You'll see a list of all active employees, each showing their name, role badge (Tech, Admin, or Tester), and an "Authorized Tester" badge if they're allowed to test items. Inactive employees appear in a separate section at the bottom.

Pull down to refresh the list.

#### Adding an Employee

1. Tap the **+** button in the top right corner
2. Enter the employee's **name**
3. Pick their **role** using the segmented control:
   - **Tech** — can grab items, do repairs, and mark done
   - **Admin** — full access to all views and settings (will need a PIN)
   - **Tester** — dedicated tester role
4. Toggle **Authorized Tester** on if this person should be able to test items, regardless of their role (e.g., a tech who also tests)
5. Tap **Add**

The new employee will immediately appear in all relevant pickers across the app (tech assignment, tester selection, etc.).

#### Editing an Employee

Tap any active employee in the list to open their edit form. You can change their name, role, or tester authorization. Tap **Save** when done.

**Note:** PINs are not managed here. If an admin needs to set or change their PIN, they do it through the normal PIN entry flow during Device Setup.

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

If a required field is missing when Maria tries to create a job, the form won't let her save and the missing field gets highlighted.

### Manage Lists

Manage Lists is where you control the dropdown options used throughout the app. Accessible from Admin Settings → **Manage Lists** under the "Shop" section.

There are five lists you can manage:

- **Equipment** — what the item IS (Cylinder, Pump, Hose, Other...)
- **Mach Type** — what it came off of (Forklift, Excavator, Skid Steer...) — only shows up in job intake if Machine Type is turned on in Shop Settings
- **Brand** — who made the machine (Caterpillar, John Deere, Komatsu...) — only shows up in job intake if Machine Brand is turned on in Shop Settings
- **Service** — the Reason for Service pills on the intake form
- **Issues** — the repair checklist items techs check off when marking work done

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

### Reports

Coming soon.

### Resetting a Device

If a device needs to be reassigned (different role, different name, or just starting fresh):

1. Open the Admin view on an admin-role device (or elevate admin access on the target device)
2. Tap **Reset Device**
3. The device will forget its identity and show the setup screen again on next launch
4. Go through the setup process to assign a new name and role

---

## Troubleshooting

### "Incorrect PIN"

Double-check that you're entering your personal admin PIN (4-8 digits). PINs are per-person, not per-device. If you've forgotten your PIN, another admin will need to help you reset it. *(PIN reset feature coming in a future update.)*

### The app shows "Connecting..." on launch

ShopTracker needs an internet connection on first launch to download your jobs and settings. After that, it caches everything locally so you can keep working even if Wi-Fi drops (see "Working Offline" below). If you're stuck on "Connecting..." with a good Wi-Fi signal, the issue may be on the server side — let Bec know.

---

## Working Offline

ShopTracker is designed to keep working when the shop Wi-Fi drops. Here's what you need to know:

### What still works without internet

As long as you've opened the app at least once with a connection (so it can download your data), you can still:

- Browse the job board and see all your jobs, items, and customer info
- View photos that have been loaded before (they're saved on the iPad)
- Grab items, mark repairs done, move items through the status flow
- Add notes and check issue checklists
- Enter costs and close items

All of those changes are saved on the iPad and will automatically sync to the server as soon as the connection comes back. You don't have to do anything — the app handles it.

### What doesn't work without internet

- Creating brand new jobs (the server generates the job number)
- Uploading new photos
- Looking up customers you haven't seen before
- Any changes other people make on their devices won't show up until you're back online

### When the connection comes back

The app detects when Wi-Fi returns and automatically sends any changes you made while offline. This usually takes a few seconds.

If someone else made changes to the same item on a different device while you were offline, the app figures it out automatically. It compares what you changed against what the other device changed — if you edited different fields (e.g., you marked it Done while Maria added a note), both changes go through. If you both changed the same thing, the most recent change wins. You don't need to do anything — it just works.

If something goes wrong during sync (rare), Bec can see it in **Admin Settings → Sync Status**. The dashboard shows which changes are pending, which failed, and why. From there you can retry failed items, force a sync, or clear the queue entirely if needed.

### Tips

- Don't worry about saving — everything saves automatically, online or off
- If you're not sure whether you're online, look for the **offline banner** at the top of the Job Board or Work Queue. It appears automatically when the iPad loses its connection and disappears when you're back online. If you've made changes while offline, the banner will tell you how many are queued (e.g., "Offline — 3 changes will sync when back online"). The data on screen is still usable — it's just a snapshot from the last time you had a connection.

### A device is showing the wrong role

An admin will need to reset the device and set it up again with the correct role. See "Resetting a Device" above.

---

*More sections will be added as features are built. This manual is a living document.*
