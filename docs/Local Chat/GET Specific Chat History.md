# GET Specific Chat History

Get chat history for a specific conversation  


Method: `GET`  
URL: `https://127.0.0.1:{lockfile port}/chat/v6/messages?cid={cid}`  
Headers:
 - `Authorization`: `Basic {base64 encoded "riot:{lockfile password}"}`

Variables:
 - `{lockfile password}` and `{lockfile port}`: Read [Common Components - Lockfile Data](../common-components.md#lockfile-data)
 - `{cid}`: Read [Common Components - Chat ID](../common-components.md#chat-id)
