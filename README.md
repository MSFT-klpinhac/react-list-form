# React List Form WebPart

## Summary
This is a fork of the `React List Form web part`, which is available at https://github.com/pnp/sp-dev-fx-webparts/tree/main/samples/react-list-form.
This web part has a german localization available and is intended to be used with SharePoint 2019.
This web part is for adding a list form to any page. It provides a working example of implementing generic SharePoint list forms using the **SharePoint Framework (SPFx)** and the *React* and *Office UI Fabric* libraries.

The web part allows configuring which list to use and if a form for adding a new item, editing or displaying an existing item should be shown. When selecting display or edit form the ID can be defined either as a fixed number or as a query string parameter name. The form fields can be added, ordered using drag-and-drop or removed visually in the web part. A URL including placeholder for the ID can be provided to redirect to after successfully saving the form.

![Demo](./assets/React-ListForm-Overview.gif)

## Used SharePoint Framework Version 
![drop](https://img.shields.io/badge/version-GA-green.svg)

## Applies to

* [SharePoint Framework](https:/dev.office.com/sharepoint)


## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- in the command line run:
  - `npm install`
  - `gulp serve`

## Features

This Web Part illustrates the following concepts on top of the SharePoint Framework:

- Using React for building SharePoint Framework client-side web parts.
- Using React controlled components for SharePoint form fields.
- Using SharePoint REST services to retrieve and update schema and data for lists and fields.
- Using Office UI Fabric React components and styles for building user experience consistent with SharePoint and Office.
- Integrating drag and drop to provide better user experience for configuring web parts visually.
- Using custom drop down property editors in the property pane.

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/react-list-form" />