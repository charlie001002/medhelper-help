---
layout: home
title: MedHelper — Help & FAQ (v1.3)
---

# MedHelper — Frequently Asked Questions

---

## Getting Started

### What does MedHelper do?
MedHelper helps you keep track of your medicines. It can remind you when a dose is due, alert you when you are running low on a medicine, and keep a record of what has been taken and when.

### Do I need to create an account?
No. Everything is stored on your device. MedHelper does not require an account and does not send your information anywhere.

### What are the two modes?
When you first set up MedHelper you choose between two modes, and you can switch at any time in **Settings**.

**Real-time mode** is for people managing their own medicines day-to-day. MedHelper sends notifications when a dose is due and again if it goes overdue. The app header turns red when action is needed.

**Offline mode** is for situations where notifications are not needed — for example, when helping someone else manage their medicines, or when you prefer to work from a printed schedule. There are no alerts; you update doses manually or let the app clear them for you automatically.

---

## Adding Medicines

### How do I add a medicine?
1. Go to the **Meds** tab
2. Tap **+ Add Prescription**
3. Start typing the medicine name — MedHelper will suggest matches from a built-in medicines list
4. Select the correct medicine, then fill in how many times a day you take it, the times, and how much you currently have
5. Tap **Save**

After saving, a brief message at the bottom of the screen will tell you when your first dose is due.

### What if my medicine isn't in the suggestions?
You can type any name you like and save it manually. The suggestions list covers most UK prescription medicines but may not include every product.

### What is the difference between a scheduled and an unscheduled medicine?
- **Scheduled** medicines are taken at fixed times each day — for example, a blood pressure tablet at 8 AM and 8 PM. MedHelper tracks each individual dose and can remind you when one is due.
- **Unscheduled** medicines are taken as needed — for example, a painkiller or an inhaler. MedHelper tracks how much you have left but does not set reminders. To record an unscheduled dose, go to the **Today** tab and tap the **+** button next to the medicine.

### How do I set up a medicine I take every few days (e.g. once a week)?
When adding or editing a prescription, set **Frequency** to *Every N days* and enter the number of days between doses (e.g. 7 for weekly). Set the start date to the date of the first dose — this is the anchor from which MedHelper calculates all future dose days.

For example, a weekly tablet starting on a Monday will be due every Monday. If you open the app on a Tuesday, no dose is shown — the next one is the following Monday.

Stock coverage is calculated correctly for period medicines: MedHelper works out how many doses you have left and multiplies by the interval to give you the days remaining.

### What happens if I change a prescription?
If you change only the schedule, frequency, or dose quantity — the same physical tablets — your stock count carries over unchanged.

If you change the **medicine name** (for example updating "Paracetamol 500mg" to "Paracetamol 1000mg" after a dose increase), the stock count is cleared, because the old tablets are a different product. Add the quantity of the new tablets after saving.

---

## Taking a Dose

### How do I record that I have taken a dose?
When a dose is due, the top bar turns red and shows **Take Medication**. Tap through to see which doses are due — each one has a green **Take** button. Tapping it records the dose and updates your stock automatically.

You can also record doses from the **Today** tab, which shows everything due today and lets you mark them off as you go.

### How do I take an as-required (unscheduled) medicine?
Go to the **Today** tab and tap the **+** button next to the medicine. Enter the quantity taken if it differs from the usual amount. The dose is recorded immediately and stock is updated.

### What if I took a dose but forgot to record it at the time?
Open the **Today** tab, find the dose, and tap **Take**. It will be recorded as taken.

### What happens if I miss a dose?
It stays listed on the Today screen and in your history. You can still mark it as taken or skip it.

---

## Pausing a Dose

### What does Pause do?
Pause lets you delay a dose for a short time without skipping it — for example, if you need to take a tablet with food and are not ready to eat yet. You choose how long to pause: 15 minutes, 30 minutes, 1 hour, 2 hours, or 4 hours.

### How do I pause a dose?
From the red alert screen or from the **Today** tab, tap **Pause** next to the dose and choose a duration. The dose will disappear from the alert screen and MedHelper will send you a fresh reminder when the pause time is up.

### What is the difference between pausing and skipping?
**Pausing** means "remind me again later" — the dose is still expected and you will get a new reminder. **Skipping** means "I am not taking this one" — it is recorded as skipped and no further reminder is sent for that dose.

---

## Notifications and Alerts

### Will I get a separate notification for every medicine?
No. If several medicines are due at the same time, MedHelper sends a single notification listing them all — for example, *"3 medications due: Aspirin, Lisinopril, Metformin"*.

### What is the overdue alert?
If you have not recorded a dose after a short grace period, MedHelper sends a second, more urgent notification — for example, *"⚠️ Aspirin is overdue — please take it now"*. The grace period is how long after the scheduled time before this second alert fires, and you can adjust it in **Settings**.

### What happens when I tap a notification?
Tapping a dose reminder or overdue notification opens MedHelper directly on the **Today** tab, wherever you are in the app. From there you can take, skip, or pause the dose.

### I took my doses but still received an overdue notification
If you recorded your doses after the grace period had already passed, the overdue notification may still arrive. You can dismiss it — your records are correct.

### What does the bell switch on the Today screen do?
The bell switch in the top corner of the Today tab turns notifications off temporarily without changing anything else — useful in a meeting or at the cinema. Doses still appear on the Today screen and the tab badges still update; you just won't receive alerts until you switch the bell back on.

This is different from **Offline mode** (in Settings), which turns off all real-time tracking — in Offline mode there are no alerts at all and the red "Take Medication" header never appears.

### Why did I get a notification saying "Open MedHelper to keep reminders running"?
iPhones only allow a limited number of scheduled reminders, so MedHelper sets up roughly the next week's worth each time you open the app. If the app has not been opened for several days, the scheduled reminders run out. This notification is MedHelper's way of telling you that — open the app and the next batch of reminders is set up automatically.

### My notifications are not appearing
- Check that MedHelper has permission to send notifications in your phone's Settings app
- Make sure you are in **Real-time** mode — look for the small chip in the top right of the app header. If it says **Offline**, notifications are turned off
- Check the bell switch on the Today tab is on (blue)
- On iPhone, try closing and reopening the app

---

## Tab Badges and App Icon

### What do the numbers on the tabs mean?
- **Today tab badge** — the number of doses still to take today (doses scheduled for today whose time has already passed and have not been taken or skipped). This does *not* include overdue doses from previous days.
- **Meds tab badge** — the number of medicines with stock below your low-stock threshold (medicines you need to reorder).

Both counts update instantly when you take a dose, pause a dose, top up stock, or mark a repeat prescription as ordered.

### What does the number on the app icon mean?
The app icon badge shows the combined total: doses still to take today plus medicines to reorder. It updates every time you take an action in the app. In Offline mode the dose count is always zero, but the Meds reorder count still appears so you know if you need to order more tablets.

---

## Running Low on Medicine

### How does MedHelper know when I am running low?
When you add a medicine, you enter how much you currently have — you can include the unit, for example "28 tablets" or "150 ml", and MedHelper will keep it. Each time you record a dose as taken, MedHelper deducts that amount automatically. When the remaining supply drops below your alert threshold, you will receive a low stock alert.

### When does the low stock alert appear?
- For medicines taken at fixed times: when you have fewer than a set number of days' supply left (you can change this in **Settings**)
- For medicines taken as needed: when you have fewer than a set number of doses left

### What should I do when I get a low stock alert?
Order your repeat prescription. Once you have done so, tap **Repeat Ordered** on the alert — MedHelper will hold off on reminding you again while you wait for it to arrive.

### Why has the Meds list changed order?
The Meds tab normally lists your medicines alphabetically. When any medicine is running low, the list automatically switches to **stock order** — the medicines that need reordering soonest move to the top. Once everything has been reordered or topped up, the list returns to alphabetical.

You can change the order yourself at any time with the **A–Z / Stock** buttons at the top of the Meds tab.

---

## Suspending a Medicine

### What does suspending a medicine do?
Suspending stops all reminders and tracking for a medicine without deleting it. Use it if you have been told to stop taking something temporarily — for example, before an operation, or while a side effect is being investigated.

When you suspend a medicine, all future scheduled doses are removed. This is intentional — a clinical hold means those doses should not happen, and keeping them would distort your history and stock count.

### How do I suspend a medicine?
Go to **Meds**, tap the three dots next to the medicine, and select **Suspend**. You can also tap the medicine to open it and use the **Active / Suspended** toggle near the top of the edit screen. The medicine will be greyed out and no further reminders will be sent.

### How do I start taking it again?
Go to **Meds**, find the suspended medicine, tap the three dots, then **Resume** — or open the medicine and toggle it back to **Active**. MedHelper will start scheduling doses from today, as if the medicine had just been added.

---

## Using Offline Mode

### When would I use Offline mode?
Offline mode is useful when:
- You are helping someone else manage their medicines and you don't want phone alerts
- You prefer to work from a printed daily or weekly schedule rather than receiving notifications
- You are setting up medicines in advance and do not want alerts until you are ready

### How do I switch to Offline mode?
Go to **Settings → App Mode** and move the toggle to **Offline**. The chip in the app header will change from **Real-time** to **Offline**.

### Can I print a medicine schedule in Offline mode?
Yes. Go to the **Reports** tab and open the **Doses** section. You can print or export a daily or weekly dose checklist — useful for carers, anyone who doesn't have a suitable phone, or anyone who prefers a paper record.

### What is "Auto-clear past doses"?
This is an Offline mode option found in **Settings**. When switched on, any doses that were due the previous day and were not recorded are automatically marked as taken when you open the app. This is useful when you are using a printed checklist and only want to update the app periodically, without having to manually clear a backlog of pending doses each time.

### Can I switch back to Real-time mode later?
Yes, at any time in **Settings → App Mode**. Your medicines and history are unchanged.

---

## Reports

### What is in the Reports tab?
The Reports tab has five sections:

**Doses** — a printable daily or weekly schedule of all your medicines and their dose times. Useful for tracking without a phone.

**Stock** — a summary of current stock levels for all your medicines, highlighting anything that is running low. Can be printed.

**Meds** — a list of all your current prescriptions with details including dose, frequency, and stock. Useful for sharing with your medical professional.

**History** — a timeline of changes to your prescriptions: when medicines were added, doses changed, or medicines suspended or stopped, along with any notes you have added about why.

**Stats** — adherence statistics showing how consistently you have been taking your medicines over time.

### Can I print or share a report?
Yes. Each section has a print or export button. On a phone this uses the standard print dialogue so you can send to a printer, save as a PDF, or share via email or another app.

---

## Moving to a New iPhone

### Will my medicines and history move to my new phone?
Yes. MedHelper's data is included in Apple's normal phone transfer — both the direct phone-to-phone transfer during new phone setup and an iCloud backup restore. Your medicines, dose history, and settings all come across.

### Is there anything I need to do after moving?
1. Make sure MedHelper is installed on the new phone
2. Open MedHelper once — this sets up your reminders again on the new phone
3. If asked, allow notifications — reminders cannot be delivered without this

### My reminders stopped after changing phone
Scheduled reminders do not transfer between phones — they are recreated the first time you open MedHelper on the new device. Open the app, check the chip in the top corner says **Real-time**, and confirm notifications are allowed in your phone's Settings app.

---

## Important Information

### Is MedHelper a medical device?
No. MedHelper is a personal organisation tool to help you keep track of your medicines. It does not provide medical advice and does not replace the instructions of your doctor, pharmacist, or other healthcare professional. Always follow your prescription label and any guidance you have been given.

### What if I am not sure whether I have taken a dose?
If you are unsure, do not take an extra dose. Contact your pharmacist or GP for advice. MedHelper's records can help you check what was recorded, but they depend on you having marked doses correctly.

### What should I do in an emergency?
MedHelper is not for emergencies. Call **999** or go to your nearest A&E immediately.

### Does MedHelper work without internet?
Yes. Everything is stored on your device and the app works fully without an internet connection.
