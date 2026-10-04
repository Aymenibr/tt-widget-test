# tt-widget-test

A deliberately empty page at `https://aymenibr.github.io/tt-widget-test/`, used as a
real HTTPS origin (not the portal) for TicketTech widget end-to-end tests.

- It contains no widget snippet. Tests inject the loader at runtime.
- Do not add content, analytics, or other scripts.
- It is listed as an allowed domain only on `cctest-*` test tenants.
