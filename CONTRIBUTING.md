# Production tracking contribution rules

- Never overwrite an approved media file. Add a new version (`V02`, `V03`, etc.).
- A queued job is not a rendered asset; only update status after retrieving the actual output.
- Only mark a version `APPROVED` after user review.
- Preserve rejected/superseded files and record why they were rejected.
- Keep Flow asset IDs exactly as reported. Mark them `Agent-reported` if not independently verified.
- Do not invent missing asset IDs, dialogue, narrator lines, file paths, credit costs or approvals.
- Update all affected registers in one commit.
- Scene duration totals must match the approved scene runtime.
- Keep actual dialogue and narration separate from voice direction/outline.
- Separate character master design from scene-specific props and costumes.
