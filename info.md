# Home Casa Theme

### Requirements

- Add *custom fonts* as Stylesheet resources in dashboard "Manage Resources":
    - `https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Major+Mono+Display&display=swap`
    - `https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap`
- Install `card-mod` via HACS.
    - add the following to your `configuration.yaml` file:
      ```yaml
        frontend: 
          extra_module_url:
            - /hacsfiles/lovelace-card-mod/card-mod.js
      ```
