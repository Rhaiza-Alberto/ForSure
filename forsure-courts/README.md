# ForSure Courts

Pickleball court rental prototype (sample data, simulated SMS).

```
index.html         
css/
  tokens.css        colors, radii, light/dark themes
  base.css          reset, typography, layout utilities
  layout.css        header, nav, footer
  components.css    buttons, badges, cards, forms, stepper, modal, toast
  pages.css         hero, court cards, slot grid, tables, SMS phone mock
  admin.css         admin shell, KPIs, charts
  responsive.css    all breakpoints (1024 / 900 / 600 / 400)
js/                 load order matters (see index.html)
  utils.js          date, currency and escape helpers
  data.js           sample courts, bookings, availability logic
  sms.js            simulated SMS templates
  components.js     court SVG, phone mock, slot grid, date strip
  shell.js          header and footer
  pages-customer.js customer pages
  pages-admin.js    admin pages and modal
  app.js            render loop, events, validation, submit
```
