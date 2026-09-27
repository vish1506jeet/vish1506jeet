# CRM Transformation — Salesforce to LeadSquared

**Company:** upGrad
**My role:** Owned the migration end to end — planning, data migration, training, and the actual cutover

## The problem, in plain terms

upGrad was running its entire sales operation on Salesforce CRM and CPQ. As the business grew, the sales and lead-management workload grew with it, and Salesforce wasn't really built for the way a high-volume education sales funnel actually moves — lots of leads, fast follow-up, a lot of hand-offs between teams. The decision was made to move the whole thing to LeadSquared instead.

That sounds simple written down. It wasn't. This meant moving live sales data, active leads mid-conversation with a sales rep, and every workflow that sales and operations teams relied on every single day, for over 1,250 people, without anything breaking or any lead getting lost in the move. Get this wrong and you don't just lose data, you lose actual revenue sitting in leads that go cold because nobody could see them for a week.

## What I did

I owned this from the planning stage right through to the day people were actually working in the new system.

- **Mapped everything first.** Before touching anything, I went through every object, workflow, automation, and integration running on Salesforce that the teams actually depended on. Missing something here doesn't show up until it's already broken in production, so this stage mattered more than people usually give it credit for.
- **Planned the migration properly.** Worked out exactly how leads, accounts, opportunities, and historical activity would move across, and agreed with the data team upfront on how we'd check that nothing got lost or corrupted along the way. Data migration is one of those things where you don't find out you got it wrong until someone downstream can't find a lead that used to be there.
- **Ran a full parallel run before going live.** Rather than a hard cutover, I ran both systems side by side, reconciled the record counts between them, and deliberately stress-tested the workflows people actually use every day — not just the obvious happy-path ones. This is the decision I'd call out as the one that mattered most.
- **Trained everyone before go-live, not after.** All 1,250+ users across sales, operations, and leadership were trained on LeadSquared before the switch happened. A CRM nobody knows how to use on day one is a CRM that fails in week one, no matter how well the migration itself went.
- **Managed a phased cutover and stayed close to it afterwards.** I didn't hand this off once it went live. I stayed embedded with the teams for the first few weeks specifically to catch anything that only shows up under real day-to-day use, and to fix it fast before it became a habit of working around the new system.
- **Tracked adoption after go-live**, not just whether the migration technically worked. The real test wasn't "did the data move," it was "are people actually working in LeadSquared, or quietly falling back to spreadsheets and old habits."

## What it actually achieved

- All 1,250+ users migrated with zero critical incidents
- Lead tracking time dropped 65% within 60 days of go-live
- The new system matched how the sales team actually worked day to day, so leads stopped sitting untouched in a tool that didn't fit the way people used it

## The decision I'd point to if you asked me what actually mattered here

Insisting on the full parallel run instead of a hard cutover. It takes longer, it's more work up front, and it would have been easy to skip it under time pressure. But it's exactly what caught the data issues while they were still fixable, before they ever touched a live sales conversation. A CRM migration doesn't fail because the software is wrong, it fails because something slipped through in the move and nobody caught it until a customer noticed. The parallel run is what stood between us and that.

---
[← Back to profile](../README.md)
