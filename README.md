# oauth-replay

Static relay page for the GoTrust OMS Pipedrive OAuth callback. Pipedrive requires a publicly reachable callback URL; this page only forwards the one-time authorization code to the internal OMS (`oms.gotrustid.com`, reachable inside the company network/tailnet only). It stores nothing and holds no secrets; the code is useless without the client secret kept on the OMS server.
