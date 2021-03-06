# CHANGELOG

## in develop

## 1.1.3

* Moved template load from templateService to .twig to speed up initial load and avoid multiple api calls.

## 1.1.2

* Fixed shared channel overview html.

## 1.1.1

* Made media upload buttons sticky.
* Fixed datetime pickers.
* Removed os2display requirements.

## 1.1.0

* Added itk-header to allow injections into pages for decoupled bundles.
* Made datepicker configurable.
* Moved BaseApiController to mainModule.
* Removed unused call to get all channels in slide create.
* Moved shared components from ikApp to the module ikShared, so it can be injected in other apps.

## 1.0.14

* Fixed issue with missing slide/screen templates.

## 1.0.13

* Fixed submenu code to activate sub menu based on first part of path.
* Fixed active-filter for admin/users and admin/groups.
* Updated npm packages.

## 1.0.12

* Fixed z-index for "continue" button in slide/channel create.
* Fixed styling for group filter in overviews.
* Hide groups in overviews when user is not in a group.

## 1.0.11

* Added access to tool config from json files, to allow configurable tools.

## 1.0.10

* Added ngSanitize.

## 1.0.9

* Minor style fixes.
* Fixed issue with change in group for user not being reflected in UI.
* Removed unnecessary call to get all slides in channelController.

## 1.0.8

* Fixed missing error message when trying to upload unsupported media files.

## 1.0.7

* Fixed bug with searching when on a page higher than the number of results,
where results are displayed as empty. Now pager is reset if text is changed.
* Added performance optimization where results are only loaded from the backend,
if the search ids are different than previous results.
