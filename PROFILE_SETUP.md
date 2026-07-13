# Profile Setup

This file is for anyone who wants to reuse or adapt this profile layout for their own GitHub README.

## Quick Start

1. Replace the photo in [pratham-photo.jpeg](pratham-photo.jpeg) with your own image.
2. Update the details in [scripts/make_info_card.py](scripts/make_info_card.py) with your own name, links, roles, projects, and skills.
3. Regenerate everything with one command:

```powershell
.\.venv\Scripts\python.exe scripts\build_profile.py
```

That command checks timestamps and only reruns the parts that are stale. Use `--all` to force a full rebuild.

## Explicit Rebuild Steps

If you want to run the generators one by one, use:

```powershell
python scripts/prep_photo.py
python scripts/make_ascii_svg.py
python scripts/make_info_card.py
python scripts/fetch_contributions.py
python scripts/render_heatmap_svg.py
```

## Cron Job

The workflow in [.github/workflows/update-profile-art.yml](.github/workflows/update-profile-art.yml) runs on a cron schedule.

In this repo, the cron string `*/5 * * * *` means the workflow runs about every 5 minutes. GitHub can still delay scheduled jobs a bit, but this is the fastest standard cadence available. The workflow refreshes the contribution data and rebuilds [pratham-heatmap.svg](pratham-heatmap.svg), then commits the updated files back to the repository.

## Local Setup

Use the main virtual environment at `.venv/`. The extra `.venv-1/` directory is not needed.