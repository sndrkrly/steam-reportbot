# steam-reportbot
👮🏻‍♀️ Reportbot for Steam.

<h1 align="left">
	✨ Docs
</h1>

Add to the `bots.txt` textfile accounts login data (`login:password:shared_secret` in the each line). If you want to use limited accounts (without $5 spent) use this formatting: `login:password:`.
In the `config.json` set steam id of needed player. You can get this in this site: https://steamdb.info/calculator/. Just put the link of needed steam profile.
Enter the `appid` parameter. For CSGO its 730.
Set the `perChunk` and `betweenChunks` parameters (stock values suitable for you).
If you want to use limited steam acconts enter this: `"limited": true`. If you want to use unlimited (with $5) type this: `"limited": false`.
Run the bot - type in the command prompt or PowerShell: `node index.js` or just `node index`

<h1 align="left">🔖 Legal information</h1>
<p align="left">
	Everything shown here is the property of <b>Sandor Kiraly</b>.
	Any theft, be it code or image, is  <b>legal theft
	consequences. </b>
</p>
