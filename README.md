# b2c-hotel-portal-login

Azure AD B2C **custom UI page** for the Hilbertech **Hotel Portal**.

Single self-contained, CSS-only file (`index.html`) used for BOTH B2C pages:
- **sign-in** — B2C injects the login form into `#api`
- **MFA / OTP** — B2C injects the verification-code form into `#api`

Served via GitHub Pages for testing. In the B2C user flow, set this file's URL as the
**Custom page URI** for the sign-in and MFA page layouts.
