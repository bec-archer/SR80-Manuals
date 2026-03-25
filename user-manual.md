# ShopTracker User Manual

**App:** ShopTracker (SR80)
**Version:** 1.0 (in development)
**Last Updated:** 2026-03-25

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

---

## Front Counter

### Job Board

When you open the app on a Front Counter device, you'll see the **Job Board** — a grid of cards showing all active work orders. Each card shows:

- **Job number** (e.g., 20260325-1) in the top left
- **Status dots** in the top right — one colored dot per item showing where it is in the repair process (blue = just checked in, yellow = being worked on, orange = tested, green = ready for pickup)
- **Customer name and phone number**
- **Item count** and the date/time the job was created

**Draft work orders** appear at the top with an orange "DRAFT" badge and a warm-tinted background so they stand out as unfinished.

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

#### Saving

The button in the top right changes based on what you've filled in:

- **"Create Work Order"** — appears when all required fields are filled in (customer, equipment type, at least one reason for service). This creates the work order with a job number and makes it visible to the back shop.
- **"Save as Draft"** — appears when required fields are still missing. This saves your progress so you can come back to it later. Drafts appear at the top of your Job Board with an orange badge but are NOT visible to the Tech Station.

### Customer Check-In

Coming soon.

### Checkout & Pickup

Coming soon.

---

## Tech Station

*This section will be filled in as Tech Station features are built.*

### Repair Queue

Coming soon.

### Working on an Item

Coming soon.

### Marking Items as Tested

Coming soon.

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
