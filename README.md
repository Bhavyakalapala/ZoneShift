# ZoneShift — Azure Availability Set versus Availability Zone Migration

ZoneShift is a front-end educational simulation showing an application moving from an Availability Set layout to instances spread across Availability Zones. It includes a migration runbook, simulated load-balancer status, and VM failure/recovery controls.

## Important scope note
This is a **simulation**. It does not provision or modify Azure resources and does not perform a real VM migration. Real migration requires planning, target resource deployment, application/data migration, validation, and controlled traffic cutover.

## Run locally
Open `index.html` in a browser. No build step or dependencies are required.

## Deploy with Azure Static Web Apps
1. Push this repository to GitHub.
2. In the Azure Portal, create an **Azure Static Web App**.
3. Connect the GitHub repository and `main` branch.
4. For a plain static site, set **App location** to `/`, **API location** blank, and **Output location** blank.
5. Create the resource and wait for the GitHub Actions deployment to finish.
6. Open the generated Azure URL.

## Files
- `index.html` — dashboard structure
- `style.css` — responsive styling
- `script.js` — migration and failure simulation logic

## Project team
- 2400033366_BHAVYA CHOWDARY KALAPALA
- 2400040164_HARITHA VIDYA SRIKARI SANNIDHANAM
- 2400033040_Paida vls chandan
- 2400033161 Nithin Tirumalasetty
