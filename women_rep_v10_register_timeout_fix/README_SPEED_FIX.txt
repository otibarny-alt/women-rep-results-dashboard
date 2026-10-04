WOMEN REPRESENTATIVE LIVE DATA SPEED NOTES

- Dashboard HTML opens immediately.
- Dashboard upstream timeout defaults to 30 seconds to allow a sleeping Render voting service to wake.
- Automatic refreshes do not overlap.
- The dashboard reuses its cached Women Representative feed during normal page reads.
- A short upstream cache is recommended to reduce duplicate PostgreSQL aggregation.
- Completed simulation votes are still mirrored at final /cast.
