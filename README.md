# AEGateLog
Because of COVID-19 we have to log all entries to our Athletics Track. This is a QR Code based Blazor WebAssembly app. 

Only mockup at this stage. 
Demo: [On Azure](https://bit.ly/3fnzHij)
- Does not retain data: Is retained but not in a database yet.
  - Do not persist real phone numbers
  - There is a clear data button.
- Not all pages show on sidebar.
  - Want users to accept before getting to page
  - Admin login wil also be similarly hidden, notat the moment
  - Magic numbers are in the path for these pages which is checked.
- Pseudo Admin mode.
  - Login from Management tab
  - App then enables the QR Code page and FetchData page.
  - Logout on FetchData page.
  - Login and out may need the page to be refreshed.
 -Next add a database, probably SQLite.
