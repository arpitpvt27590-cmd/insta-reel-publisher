# Smoke tests

Run these after deployment:
1. Open the Worker URL; the login screen should appear.
2. Wrong dashboard password should be rejected.
3. Correct password should open the dashboard.
4. `/api/session` should return `{"authenticated":true}` while signed in.
5. Connect an authorized professional Instagram account.
6. Upload an MP4 under 95 MB and publish to a test account.
7. Verify a successful result has a real Meta media ID and appears on Instagram.
8. Verify a failed attempt is shown as failed and includes a message.
9. Verify history survives a page reload.
10. Confirm no access token or app secret is visible in browser DevTools or GitHub.
