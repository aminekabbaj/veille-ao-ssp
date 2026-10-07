# SSP drive sync

Copies of the SSP veille artifacts held in the online OneDrive (not only the local drive).
`sync-manifest.json` maps each repo file to its OneDrive item id, the sync direction, and what is not yet synced.
Re-sync by asking Claude (Microsoft 365 connector) to pull/push using the item ids in the manifest.
