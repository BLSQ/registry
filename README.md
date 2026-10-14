# Registry plugin

This IASO plugin is used to make the registry feature public.

It initially was part of the main IASO codebase, but was split in October 2026. 
The code should still work, but things are missing to make this plugin fully functional (see below).

# TODO
- add required files to turn this into a proper IASO plugin:
  - `plugin_settings.py`
  - `cron.yaml`
  - `docker-compose.prod.yaml`
  - `tsconfig.json`
- prepare dedicated CI pipeline for what happens in PRs/develop/main/...
