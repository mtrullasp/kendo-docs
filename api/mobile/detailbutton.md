---
title: kendo.mobile.ui.DetailButton
slug: mobile-kendo.mobile.ui.detailbutton
tags: api,mobile
publish: true
---

# kendo.mobile.ui.DetailButton

Represents the Kendo UI Mobile DetailButton widget. Inherits from [kendo.mobile.ui.Widget](/api/framework/mobilewidget).

## DetailButton

The DetailButton widget navigates to a mobile View when pressed.

#### Initialize Kendo mobile DetailButton based on role data attribute

    <a data-role="detailbutton">Foo</a>

#### Initialize Kendo mobile DetailButton using jQuery plugin syntax

    var button = $("#button").kendoMobileDetailButton();

## Events

### click

Fires when the user taps the button.

#### Event Data

##### e.target `jQuery`

The clicked DOM element

##### e.button `jQuery`

The button DOM element
