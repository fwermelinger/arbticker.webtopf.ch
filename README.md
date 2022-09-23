# arbticker.webtopf.ch

**Update:** 
https://arbticker-sls.webtopf.ch/ is a small side project to keep track of historical arbitrage rate between two exchanges.
I built the new version using only Azure serverless functions using React and the serverless framework. (cost currently at 2-3$ per month)

The purpose of this tool is to show current and recent arbitrage data between a Korean and foreign exchange. I chose Bithumb and Kraken because they're the ones I used the most. Data is fetched every few minutes and then aggregated into hourly data points.

This whole site is a constant work in progress. I do not guarantee the correctness of the data.

## Legacy version
Previous version written as a Node.js app running on a DigitalOcean VM (cost fixed at 5$ per months). Currently not working because Bithumb removed LTC from their API and I haven't found the time or motivation to fix that.
http://arbticker.webtopf.ch 
