# autofill

> A Chrome extension for saving form profiles and filling supported fields.

## Overview

AutoFill stores reusable profiles in the browser and can fill forms on demand. The extension also includes record, import/export, and optional encryption features described in its project documentation.

## What’s in this repo

- Multiple profiles and supported text, email, date, phone, select, and number fields
- Manual fill and field-recording workflows
- JSON import/export and optional CryptoJS-based protection

## Stack

JavaScript, Chrome Extension APIs, HTML, CSS, and CryptoJS.

## Getting started

1. Open `chrome://extensions` and turn on Developer mode.
2. Choose Load unpacked and select this repository’s folder.
3. Create a profile in the extension popup and test it on a page you control.

## Notes

Saved form data can be sensitive. Review how local storage and the optional encryption key work before saving personal information; never test autofill on forms without permission.
