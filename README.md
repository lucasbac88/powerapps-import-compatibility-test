# Power Apps import compatibility test

This repository contains a disposable Microsoft Power Apps canvas app ZIP import-package test. The source is the **Focus Sessions** sample in the Microsoft 365 community [PnP Power Apps samples repository](https://github.com/pnp/powerapps-samples/tree/main/samples/focus_sessions).

This ZIP is a reconstructed package using the upstream sample manifest, app metadata, sample `.msapp` file and icons, with an internal file name corrected to match the app metadata's referenced document filename. Its structural layout has been checked, but **it has not been tested by importing it into a Power Apps environment**. It might still be rejected because of age or packaging compatibility.

## Steps

1. Download `TTC_PowerApps_ZIP_Import_Test.zip` without unpacking it.
2. In Microsoft Power Apps: Apps > Import app > From package (.zip).
3. Select the ZIP, choose **Create as new** (if available), and give it a clearly labelled test name.
4. Check whether the import succeeded and whether the new app appears under Apps. Do not publish or share it.

This sample contains no TTC records, secrets or credentials and declares no external data connections. It is **not** a custom ER dashboard and does not test SharePoint integration.

Source and licensing: copyright (c) 2021 Microsoft 365 Community; MIT License. See LICENSE.
