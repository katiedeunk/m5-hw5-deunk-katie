# m5-hw5-deunk-katie
# Accessibility Audit

## Initial Audit

I used Google Lighthouse to audit the website for accessibility issues. The initial audit found issues with color contrast, heading order, and the page structure.

## Accessibility Issues Found

### 1. Color Contrast

The navigation links did not have enough contrast between the text and the background. Lighthouse reported a contrast ratio of 1.69, which did not meet the recommended 4.5:1 ratio.

### 2. Heading Order

The "About Me" heading was using an `<h3>` heading without following the correct heading order. Headings should follow a logical order so that screen reader users can better understand the structure of the page.

### 3. Main Landmark

The page did not have a `<main>` landmark. A main landmark helps screen reader users identify and navigate to the primary content of the page.

## Accessibility Fixes

### 1. Fixed Color Contrast

I changed the navigation text color so that there is more contrast between the text and the navigation background. This makes the navigation easier to read and improves accessibility for users with low vision.

### 2. Fixed Heading Order

I changed the "About Me" heading to use the correct heading level so that the headings follow a logical order.

### 3. Added Main Landmark

I added a `<main>` element around the primary content of the page. This gives the page a clear main landmark for screen readers and other assistive technologies.

## Final Audit

After making these changes, I ran the Lighthouse accessibility audit again to check that the issues were corrected. The goal was to improve the site's accessibility while keeping the original content and overall design of the website.
