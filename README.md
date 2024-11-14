# Github Action VPS

Open tunneling to github action vps with ngrok.

Require two secrets:

- `SSH_PUBLIC_KEY`: public key to connect to the server
- `NGROK_AUTH_TOKEN`: ngrok auth token (create new free account)

> [!WARNING]
> This will keep github server continuously running, so it will consume
> github action minutes. Additional charges may apply if out of free minutes.
> Manually turn the workflow on or off to save minutes.
