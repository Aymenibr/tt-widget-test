# tt-widget-test

A deliberately minimal page at `https://aymenibr.github.io/tt-widget-test/`, used as a real
HTTPS origin (not the portal) for TicketTech widget end-to-end tests.

- It contains ONLY the one-line widget loader for the `cctest-3` test tenant, plus a plain
  link and a button that the click-through test uses.
- Do not add content, analytics, or other scripts.
- The origin is listed as an allowed domain only on `cctest-*` test tenants.
