---
title: "ARIA: aria-rowindextext attribute"
short-title: aria-rowindextext
slug: Web/Accessibility/ARIA/Reference/Attributes/aria-rowindextext
page-type: aria-attribute
spec-urls: https://w3c.github.io/aria/#aria-rowindextext
sidebar: accessibilitysidebar
---

The `aria-rowindextext` attribute defines a human-readable text alternative of `aria-rowindex`.

## Description

When you have a very long table or when you purposefully want to display just a section of a table, not all rows may be present in the DOM. When this happens, we use the [`aria-rowcount`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowcount) with an integer value to define how many rows the table (or grid) would have if all the rows were present and add the [`aria-rowindex`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowindex) property on each row and spanning cell to provide information on the row index within that larger table. When the value of `aria-rowindex` is not meaningful or does not reflect the displayed index, we can also add the `aria-rowindextext` to provide a human-readable text alternative to the `aria-rowindex` integer value.

The `aria-rowindextext` should only be included **in addition to**, not as a replacement of, the `aria-rowindex`. Some assistive technologies use the numeric row index for the purpose of keeping track of the user's position or providing alternative table navigation. The `aria-rowindextext` is useful if that integer value isn't meaningful or does not reflect the displayed index, such as a game of Chess or Battleship.

The `aria-rowindextext` is added to each {{HTMLElement('tr')}} or to elements with the `row` role. It can also be addition to cells or owned elements of each row.

## Values

- `<string>`
  - The human-readable text alternative of the numeric [`aria-rowindex`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowindex)

## Associated interfaces

- {{domxref("Element.ariaRowIndexText")}}
  - : The [`ariaRowIndexText`](/en-US/docs/Web/API/Element/ariaRowIndexText) property, part of the {{domxref("Element")}} interface, reflects the value of the `aria-rowindextext` attribute.
- {{domxref("ElementInternals.ariaRowIndexText")}}
  - : The [`ariaRowIndexText`](/en-US/docs/Web/API/ElementInternals/ariaRowIndexText) property, part of the {{domxref("ElementInternals")}} interface, reflects the value of the `aria-rowindextext` attribute.

## Associated roles

Used in roles:

- [`cell`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/cell_role)
- [`row`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/row_role)

Inherited into roles:

- [`columnheader`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/columnheader_role)
- [`gridcell`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/gridcell_role)
- [`rowheader`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/rowheader_role)

## Specifications

{{Specifications}}

## See also

- [`aria-rowindex`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowindex)
- [`aria-rowcount`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowcount)
- [`aria-rowspan`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-rowspan)
- [`aria-colindextext`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-colindextext)
- [`aria-colindex`](/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-colindex)
