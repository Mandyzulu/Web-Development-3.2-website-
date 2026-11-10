KASI & SUBURB RESTORATIONS

CLIENT WEBSITE
http://localhost/kasi-home/
Public browsing stays available; client actions require the client's own sign-in.

ADMIN LOGIN
http://localhost/kasi-home/admin/
Email: khumo@gmail.come
Password: khumo1234567
The email uses .come exactly as supplied. No signup or setup step is needed.
Admin sign-in opens the administrator workspace directly. Admin and client logins
use separate sessions, so signing out of one does not sign out of the other.
Direct access to admin.php requires the dedicated admin login.

UPDATE
Back up the existing kasi-home folder. Replace application files; preserve data/
and assets/uploads/ to keep existing accounts, properties, requests and photographs.
Start Apache in XAMPP. No MySQL is required. PHP 8+ recommended.

ADMIN FEATURES
Dashboard, add/edit properties and photos, availability/publication controls, viewing
requests, client enquiries/responses, client directory and activity history.
Catalogue changes appear across public/client pages after refresh. Client overview,
viewings and enquiries refresh when changes are detected at 15-second intervals.
Client responses are stored in Client Space; automatic email is not configured.

CHECK
1. Open /admin/ while logged out: administrator sign-in should appear.
2. Wrong credentials must fail; specified credentials open the workspace.
3. Open admin.php without admin sign-in: redirects to /admin/.
4. A normal client login must not grant administrator access.
5. Admin sign out returns to the admin login; the client's session stays unchanged.
6. Edit a listing and check Home, Properties and Client Space.

Verification: credential hash, route/session separation and asset-reference checks
completed. PHP runtime/browser testing remains required in XAMPP.
Long Sesotho content and verified property details remain outstanding content checks.
