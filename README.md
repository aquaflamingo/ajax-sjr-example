# AJAX Server Generated JS Rails Example

This repository contains sample code for a Rails Server Generated JavaScript Response (SJR).

## Example

The `index` action contains a `_form` partial for submitting new notes remotely through an AJAX request. When the XHR request is submitted async the `NotesController` `create` action renders the `create.js.erb` template. This template searches the current HTML for an `id=notes_list` element, and appends to its HTML the newly saved note. Because this JavaScript is generated from the server and sent to the client, the client does not need to rerender the page or redirect it only needs to render the new note in its existing HTML.

## Licence
MIT

