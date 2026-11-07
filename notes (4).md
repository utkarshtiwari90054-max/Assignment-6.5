# Assignment 6.5 - Profile card notes

**Component:** profile card with image, name, role, description, skills and a contact button (placeholder details; replace with your own).

- **Box model:** padding on `.profile-card__body`, `box-sizing: border-box`, 2px border, margins/gaps between elements, `max-width: 360px` with `width: 100%`.
- **Background, border, radius:** white surface, soft blue-grey border, `border-radius: 16px`, pill-shaped skill tags and badge.
- **Positioning:** `.profile-card` is `position: relative`; `.profile-card__badge` is `position: absolute` in the top-right corner of the image.
- **Class names:** BEM style (`profile-card__image`, `profile-card__button`, `skill-tag`) so each class says what it styles.
- **Responsive:** under 640px the image sits on top; at 640px and wider the card becomes a horizontal layout with the image on the left.

## Testing and screenshot (to do yourself)
Open `index.html` in Chrome, press F12, toggle the device toolbar and check ~375px (phone), ~768px (tablet) and a full desktop width. Take a screenshot at one or two sizes for your submission.
