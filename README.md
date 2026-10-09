# withings-callback

Public OAuth callback for a private, tailnet-only health app. Withings requires a publicly reachable callback URL; this page forwards the browser (with `code` and `state`) to the app's fixed callback on the tailnet. No secrets here.
