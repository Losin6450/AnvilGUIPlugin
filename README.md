# AnvilGUIPlugin

Example:

```javascript
const AnvilGUI = Java.type('net.wesjd.anvilgui.AnvilGUI');
var player = server.getPlayerExact("Losin6450");
server.broadcastMessage(`${
    new AnvilGUI.Builder()
    .plugin(plugin)
    .onComplete((player, text) => {
        player.sendMessage(text);
    })
    .open(player)}`);
```
