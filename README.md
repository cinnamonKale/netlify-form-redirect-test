Netlify form submission test.

This tests how Netlify redirects affect the form action.

[Test site](https://confident-lamport-0d13a6.netlify.app)

If the form action goes to `/#test` the form data is saved to Netlify.

If the form action goes to `/test` the form data is **not** saved.
