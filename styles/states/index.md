---
layout: component
title:  "Focus states"
category: styles
parent: styles
thispage: style.states
#summary: ""
---

When a user moves through a web page by jumping between things like the page’s links, buttons or form fields, it needs to be clear to the user which part of the page they’re on.

Components and patterns in this Design System provide styles to make these things clear. If you use a component or pattern from the Design System, you do not need to do anything extra with the focus states within it.

Focus states in the Design System use a high-contrast combination of yellow and dark grey. This combination meets colour contrast requirements in <abbr title="Web Content Accessibility Guidelines ">WCAG</abbr> 2.1 AA ([non-text contrast](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html)) against any background colour used by the Design System.


## Link focus state

Links are given a yellow background and dark grey bottom border when they have focus. This combination ensures a good contrast.

<figure class="example__content">
<img alt="Image showing a focussed link against a number of background colours" src="/assets/images/focus-link.svg">
<figcaption>A focussed link against a number of background colours</figcaption>
</figure>

Other components that look or behave like links use the same style for consistency. For example, [accordion headers](/components/accordion) or [sequential navigation](/components/sequential-navigation).

<div class="ds_inset-text">For developers, there is a mixin called <code>blocklink</code> that you can include in the style rules of components. The mixin provides the majority of focus state styling, which means that you do not have to write it from scratch.</div>

## Button focus state

Similar to links, buttons are given a yellow background with a dark grey bottom border when they are in focus. This focus style is applied to all types of button. For example, primary, secondary, and cancel.

<figure class="example__content">
<img style="max-height: 224px" alt="Image showing normal and focussed buttons" src="/assets/images/focus-buttons.png">
<figcaption>Normal and focussed buttons</figcaption>
</figure>

## Form field focus state

Focus on form fields is shown by a yellow outline and a thicker dark border.

<figure class="example__content">
<img style="max-height: 240px" alt="Image showing normal and focussed text inputs" src="/assets/images/focus-text.png">
<figcaption>Normal and focussed text inputs</figcaption>
</figure>

This concept is applied across all types of form field for a consistent user experience.

<figure class="example__content">
<img style="max-height: 128px" alt="Image showing normal and focussed radio buttons" src="/assets/images/focus-radio.png">
<figcaption>Normal and focussed radio buttons</figcaption>
</figure>

Look at the component pages for form fields, such as [text input](/components/text-input/) and [radio buttons](t/components/radio-buttons/) for interactive examples.
