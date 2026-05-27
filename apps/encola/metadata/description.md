Encola is a clean web interface for controlling aria2 downloads from Runtipi.

The app bundles Encola's static UI with an aria2 daemon in the same container. Runtipi publishes the UI through Traefik while aria2 JSON-RPC is exposed on port `6800` for the browser client.

Downloads are stored in `/downloads`; aria2 session data is stored in `/config`.
