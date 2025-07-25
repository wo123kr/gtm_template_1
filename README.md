# Thinking Engine GTM Template

This repository contains the Google Tag Manager Custom Template for the Thinking Engine SDK.

## Template: Thinking Engine - Initialization and Auto-Collection

This tag template safely injects and initializes the official Thinking Engine (TE) JavaScript SDK into your website and enables basic automatic event collection.

This template corresponds to the `te-init-sdk.tpl` file.

### Features
- Injects the Thinking Engine JavaScript SDK.
- Initializes the SDK with your App ID and Server URL.
- Optionally enables auto-tracking for page views (`ta_pageview`).
- Optionally enables auto-tracking for page show/hide events (`ta_page_show`, `ta_page_hide`).
- Allows specifying a custom SDK URL for self-hosting.
- Allows enabling/disabling SDK debug logs.
- Supports multiple SDK instances.

## How to use in GTM

1.  In Google Tag Manager, navigate to the "Templates" section of your container.
2.  Click the "New" button in the "Tag Templates" box.
3.  Click the three-dots menu in the top-right corner and select "Import".
4.  Select the `template.tpl` file from this repository.
5.  Save the template. You can now use it as a new tag.

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.
