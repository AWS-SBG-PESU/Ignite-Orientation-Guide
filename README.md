# AWS Ignite Orientation — Meetup Guide

Short visual guide for **PES University AWS Student Builder Group (Ring Road Campus)**.

Students fill a Google Form (Name, SRN, Department), then follow 6 screenshot steps to RSVP on Meetup.

**Event:** [AWS IGNITE](https://www.meetup.com/aws-sbg-at-pes-university-ring-road-campus/events/316855505)  
**Meetup group:** [AWS SBG at PES University – Ring Road Campus](https://www.meetup.com/aws-sbg-at-pes-university-ring-road-campus/)

## Preview locally

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## GitHub Pages

1. Push to GitHub
2. **Settings → Pages → Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`

## Before sharing

1. Set the Google Form URL in `index.html`:

```js
var formUrl = "https://forms.gle/YOUR_FORM_ID";
```

2. Screenshots are already wired in `images/` as:

| File | Step |
|------|------|
| `01-meetup-home.jpg` | Open Meetup / sign up |
| `02-enable-location.jpg` | Allow location |
| `03-student-info.jpg` | Enter name & location |
| `04-meetup-setup.jpg` | Choose Attend events |
| `05-free-plan.png` | Continue with free plan |
| `06-click-attend.jpg` | Tap Attend on event |
| `07-click-submit.jpg` | Submit RSVP |
| `08-going.jpg` | Confirm Going |

## Credits

AWS and Meetup logos are trademarks of their respective owners. This is a student club guide, not an official AWS or Meetup product.
