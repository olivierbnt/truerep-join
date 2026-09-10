# truerep-join

The web landing page for **texted TrueRep invites**.

`truerep://` links only work for people who already have the app, so invite
links shared by text point here instead:

    https://olivierbnt.github.io/truerep-join/?u=<handle>&r=<reps>

- `u` = the inviter's @handle (the app resolves it to connect you two)
- `r` = the inviter's best-day rep count (optional; drives the challenge line)

The page shows the challenge, then bounces into the app via `truerep://join?u=…`
so an installed copy opens and claims the invite. If the app isn't installed it
explains that TrueRep isn't on the App Store yet.

`index.html` is generated from `web/invite/` in the TrueRep app repo — that is
the source of truth; edit it there and re-run the sync script.
