<div align="center">

<table>
<tr>
<td valign="top"><img src="./pratham-ascii.svg" width="370" alt="Pratham Ranka ASCII portrait" /></td>
<td valign="top"><img src="./pratham-info-card.svg" width="490" alt="Pratham Ranka profile card" /></td>
</tr>
</table>

# Pratham Ranka

Software Engineer · AI Engineer · Backend Engineer · Open Source Contributor

[![Portfolio](https://img.shields.io/badge/Portfolio-prathamranka.in-0d1117?style=for-the-badge&logo=vercel&logoColor=white)](https://prathamranka.in)
[![GitHub](https://img.shields.io/badge/GitHub-PrathamRanka-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PrathamRanka)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prathamranka06-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prathamranka06)
[![Email](https://img.shields.io/badge/Email-prathamworks06%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prathamworks06@gmail.com)

</div>

<img src="./pratham-heatmap.svg" width="860" alt="Pratham Ranka's GitHub contribution graph — auto-refreshed daily" />

## How To Use This Repo

If you want to reuse this profile layout for yourself, the flow is simple:

1. Replace the photo in [pratham-photo.jpeg](pratham-photo.jpeg) with your own image.
2. Update the details in [scripts/make_info_card.py](scripts/make_info_card.py) with your name, links, roles, projects, and skills.
3. Regenerate everything with one command:

```powershell
.\.venv\Scripts\python.exe scripts/build_profile.py
```

That command checks timestamps and only reruns the parts that are stale. Use `--all` if you want to force a full rebuild.

If you prefer the explicit steps, run:

```powershell
python scripts/prep_photo.py
python scripts/make_ascii_svg.py
python scripts/make_info_card.py
python scripts/fetch_contributions.py
python scripts/render_heatmap_svg.py
```

4. Commit the updated SVGs and README.

If you change any source file in `scripts/`, rerun the generator scripts above so the visible profile assets stay in sync.

## Cron Job

The GitHub Actions workflow in [.github/workflows/update-profile-art.yml](.github/workflows/update-profile-art.yml) runs on a cron schedule.

In this repo, the cron string `*/5 * * * *` means the workflow runs about every 5 minutes. GitHub can still delay scheduled jobs a bit, but this is the fastest standard cadence available. The workflow refreshes the contribution data and rebuilds [pratham-heatmap.svg](pratham-heatmap.svg), then commits the updated files back to the repository.

## Local Setup

Use the main virtual environment at `.venv/`. The extra `.venv-1/` directory is not needed.
