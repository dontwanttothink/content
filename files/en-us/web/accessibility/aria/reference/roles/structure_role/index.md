---
title: "ARIA: structure role"
short-title: structure
slug: Web/Accessibility/ARIA/Reference/Roles/structure_role
page-type: aria-role
spec-urls: https://w3c.github.io/aria/#structure
sidebar: accessibilitysidebar
---

The `structure` role is for document structural elements.

> [!WARNING]
> The `structure` role is an [abstract role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles#6._abstract_roles). It is included here for completeness of documentation. It should not be used by web authors. Use HTML and subclass structure roles.

## Description

`Structure` is a superclass [abstract role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles#6._abstract_roles) for document structures, like as [`document`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/document_role),
[`rowgroup`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/rowgroup_role), and [`sectionhead`](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/sectionhead_role), that support the accessibility of dynamic web content by helping assistive technologies determine active content versus static document content. Some subclass roles, like
[`section` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/section_role), are in turn superclasses of other roles.

The `structure` role is the superclass for all document structure roles, which are used to provide a structural description for a section of content. Most structure roles should no longer be used as browsers now support semantic HTML element with the same meaning. The structure roles without HTML equivalents, such as the [`presentation` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/presentation_role) which means content is presentational only, provide information on the document structure to assistive technologies such as screen readers as equivalent native HTML tags are not available.

## Specifications

{{Specifications}}

## See also

- [ARIA: `roletype` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/roletype_role)
- [ARIA: `generic` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/generic_role)
- [ARIA: `presentation` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/presentation_role)
- [ARIA: `range` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/range_role)
- [ARIA: `section` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/section_role)
- [ARIA: `sectionhead` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/sectionhead_role)

<!-- these shouldn't be used so we shouldn't link to them
- [ARIA: `application` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/application_role)
- [ARIA: `document` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/document_role)
- [ARIA: `rowgroup` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/rowgroup_role)
- [ARIA: `separator` role](/en-US/docs/Web/Accessibility/ARIA/Reference/Roles/separator_role)
-->
