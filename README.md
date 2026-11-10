# ACF 3D Assemblies

Phone viewer for ACF shop drawings. Each QR code on an assembly drawing opens that piece in 3D:
`https://<site>/#<SM job>-<mark>`, for example `#26-141-c1`.

- `index.html`: the viewer. It works in any phone browser, with no app or login.
- `data/index.json`: the list of jobs. `data/<SM job>.json`: the assembly models for one job, built from the IFC issued with the release.
- `vendor/`: three.js r128 (MIT licence), kept here so the page loads nothing from other sites.

For viewing only. The shop drawing governs all dimensions.
Maintained by the ACF detailing office (Bharani). Claude adds each job's model file at release.
