dhtCrawler : a simple Mainline DHT Crawler
=============

These simple scripts allow a user to crawl the Mainline (bittorrent) DHT. This is not done in any intelligent way, nor are the scripts optimized. For now, only the node IDs (Session ID + IP + Port) are queried, the info hashes are generated randomly.

This simple DHT crawler is inspired by following defcon talk :<br>
<b>Crawling the DHT for fun and profit (Defcon 18)<br></b>
http://www.defcon.org/images/defcon-18/dc-18-presentations/Wolchok/DEFCON-18-Wolchok-Crawling-Bittorrent-DHTS.pdf

The basic modules, especially the bencode module, come from the <b>lightDHT</b> repo :<br>
https://github.com/drxzcl/lightdht
