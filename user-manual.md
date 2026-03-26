# ShopTracker User Manual

**App:** ShopTracker (SR80)
**Version:** 1.0 (in development)
**Last Updated:** 2026-03-26

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
   - **Front Counter** — Check-in, job gallery, checkout workflow
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

- **Front Counter** — "Jobs" is available and selected by default. "Work Queue" and "Admin Settings" are visible but grayed out since those aren't part of the front counter workflow.
- **Tech Station** — "Work Queue" is available and selected by default. "Jobs" and "Admin Settings" are grayed out.
- **Admin** — all three options are available: Jobs, Work Queue, and Admin Settings. Jobs is selected by default.

If an admin temporarily unlocks a non-admin device (see "Admin Access on Non-Admin Devices" above), all sidebar items become available until the admin session expires.

The grayed-out items are there so everyone can see what the app can do — they just can't access views that aren't meant for their device's role.

---

## Front Counter

### Job Board

When you open the app on a Front Counter device, you'll see the **Job Board** — a grid of cards showing all active work orders. Each card shows:

- **Job number** (e.g., 20260325-1) in the top left
- **Status dots** in the top right — one colored dot per item showing where it is in the repair process (blue = checked in, yellow = being worked on, orange = tested, green = ready for pickup)
- **Customer name and phone number**
- **Item count** and the date/time the job was created

**Draft work orders** appear at the top with an orange "DRAFT" badge and a warm-tinted background so they stand out as unfinished.

Jobs are sorted by urgency: green (ready for pickup) first, then orange (tested), then yellow (in progress), then blue (just checked in). Within each group, the oldest jobs appear first. This way the items closest to being done — the ones a customer might be waiting on — are always at the top.

Pull down on the job board to refresh and see the latest updates from the back shop.

Tap the **pencil icon** in the top right corner to create a new work order.

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

- **Camera** — tap the camera button to take a photo right now
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

If photos have been taken for an item, you'll see a row of **photo thumbnails** near the top of the item card. Tap any thumbnail to view it full-screen — tap the photo or swipe down to close the full-screen view.

You can add more photos to any item at any time, regardless of its status. Next to the thumbnails you'll see **Camera** and **Library** buttons — same as during check-in. New photos upload immediately and appear in the thumbnail strip.

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

### Finalizing a Draft

Once all required fields are filled in on a draft, the **Finalize** button in the top right corner becomes active.

Tap **Finalize** to convert the draft into a real work order. The app will:

1. Generate a job number (e.g., 20260325-4)
2. Show a brief **"Finalized!"** confirmation with the new job number
3. Automatically return you to the Job Board

The job now appears as a regular work order card (no more DRAFT badge) and is visible to the Tech Station.

### Customer Check-In

Coming soon.

### Checkout & Pickup

Coming soon.

---

## Tech Station

The Tech Station iPad is the back shop's primary tool. It shows a queue of all items that need work — not grouped by job, but as individual items. Techs don't care that three cylinders came from the same customer; they care about the cylinder on the bench.

### Repair Queue

When you open the app on a Tech Station device, you see the **item queue** — a grid of cards showing all items that need work. The cards are sorted by status: In Progress items first, then items waiting for a tech to grab, then tested items that need a cost entered.

Each card shows:

- **Status dot and label** — color-coded so you can see at a glance what stage the item is at (blue = checked in, yellow = in progress, orange = tested)
- **Equipment type** (e.g., Cylinder, Pump, Hose)
- **Customer name** and **job number**
- **Assigned tech's name** — if someone has grabbed it
- **READY badge** — orange badge on items where repair is done and it's waiting on testing

Items with the READY badge also have a warm orange tint on the card so they stand out.

Tap any card to open the item detail view with actions for whatever the item needs next.

Pull down to refresh the queue. The grid adapts automatically when you rotate the iPad between landscape and portrait.

### Adding Photos from the Tech Station

When you open an item detail, you'll see a row of photo thumbnails at the top of the info card (if any photos exist) along with **Camera** and **Library** buttons. Techs can add photos at any point during the repair — before starting, during disassembly, after the fix, or whenever something is worth documenting.

Tap any thumbnail to view the photo full-screen. Tap the photo or swipe down to close.

Photos are permanent — once uploaded, they can't be deleted. This is intentional so there's always a complete visual record of what happened with each item.

### Adding Notes from the Tech Station

When you open an item detail from the tech queue, you'll see a **Notes** card between the item info and the test history. This works the same as on the front counter — type a note, tap the send arrow, and it's saved with your name and timestamp.

Use notes to document what you found during disassembly, anything unusual about the repair, or messages for the front counter ("customer needs to approve cost before we proceed"). Notes from both the front counter and the tech station show up in the same timeline, so everyone stays on the same page.

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

The item moves to the **Tested** status and the detail screen stays open so the tester can enter cost right away (see next section). If the tester walks away without entering cost, the app will automatically return to the queue after a few minutes.

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
3. Type the total cost and tap **Submit**
4. You'll see a prompt: "Was that cost approved by a manager?" — tap **Yes** if a manager signed off, or **No** to go back and confirm first
5. You'll see a **"Cost Submitted!"** confirmation, then the app takes you back to the queue
6. The item moves to **Checkout** (green) and appears on the front counter for customer pickup

For totaled items with $0 cost, the manager approval step is skipped automatically.

### Totaling an Item

If an item is unfixable:

1. Open the item
2. Tap the **Totaled** button (black in light mode, white in dark mode)
3. Confirm — you'll see a **"Totaled"** confirmation and the app takes you back to the queue
4. If there's a diagnostic cost, enter it through the normal cost flow. If not, enter $0 and it moves straight to Checkout.

### About the Action Buttons

All action buttons on the Tech Station (Grab, Done, Tested, Reassign, Enter Cost, Totaled, Close) are intentionally large. They're designed so techs can tap them quickly without fiddling around, even with dirty or gloved hands. On iPad, the buttons sit side by side in a row. On iPhone (used by admins), the buttons stack vertically and stretch full-width so they're still easy to tap on the smaller screen. After any "walk-away" action (anything where you're done with that item for now), the app shows a brief confirmation and automatically returns you to the repair queue.

### Role Switcher (Debug Only)

During development, you'll see a small purple **ladybug button** in the bottom-left corner. Tap it to switch between Front Counter, Tech Station, and Admin views without resetting the device. This only appears in debug/test builds — it won't be in the final app.

---

## Admin

*This section will be filled in as Admin features are built.*

### Employee Management

Coming soon.

### Settings

Coming soon.

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

Double-check that you're entering your personal admin PIN (4-8 digits). PINs are per-person, not per-device. If you've forgotten your PIN, another admin will need to reset it for you in the Admin settings. *(PIN reset feature coming soon.)*

### The app shows "Connecting..." on launch

ShopTracker needs an internet connection to talk to the server. Make sure the iPad is connected to Wi-Fi. If Wi-Fi is connected but the app still can't connect, the issue may be on the server side — let Bec know.

### A device is showing the wrong role

An admin will need to reset the device and set it up again with the correct role. See "Resetting a Device" above.

---

*More sections will be added as features are built. This manual is a living document.*
