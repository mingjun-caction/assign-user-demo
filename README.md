# Assign User dropdown (prototype)

Interactive prototype for the redesigned **Assign User** control on the job sidebar.

**Live demo:** https://mingjun-caction.github.io/assign-user-demo/

## What it shows

- The full-screen user-list popup is replaced by an inline searchable dropdown on the Assigned to row.
- Availability is resolved for the job's start/end window, so users already booked over that time are greyed out with the blocking job code and time.
- Hovering an unavailable row shows the blocking job, customer and overlap.
- One user per job — picking someone replaces the current assignee.
- Changing the job's start/end time re-checks availability; an assignee who is no longer available is flagged on the chip.
- Subtitle under each name is the user's account type (Admin, Sub Admin, Staff, Associate User, Basic), matching the current user list.

Static HTML, no build step. Open `index.html` to run it locally.

Sample data only — names and job codes are illustrative.
