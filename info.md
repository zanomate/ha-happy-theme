# Home Casa Theme

### Requirements

- Add *custom fonts* as Stylesheet resources in dashboard "Manage Resources":
  - `https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap`
  - `https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Rubik+Mono+One&display=swap`
- Install `card-mod` via HACS.
  - add the following to your `configuration.yaml` file:
    ```yaml
      frontend: 
        extra_module_url:
          - /hacsfiles/lovelace-card-mod/card-mod.js
    ```
