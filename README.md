# n8n_render_v2

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


### How to install n8n on Render

Follow these steps :

1. Click on the render button above
2. Choose a blueprint name, for exemple "n8n"
3. Click on "Create New Ressources"
4. Apply
5. Go to Dashboard > n8n (your service name) > Environment
6. Copy your URL (purple link in header).
7. Past your URL as value for WEBHOOK_URL
8. Wait a minute for your instance to update
9. Enjoy !


This instance will be free for 90d, then you need to pay 7$/mo for the database.



To make it run just open Render Dashboard and use this git as Blueprint.

Important note if using disk on Render: Keep the mountPath as is, otherwise n8n won't change the data.

The .env file contain examples of lines that can be added manually on Environment Variables on Render after install.

To change the webhook URL from localhost to your domain, for example, just add the var WEBHOOK_URL followed by the full URL.
