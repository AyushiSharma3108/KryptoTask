# KryptoTask
Create a price alert application that triggers an email when the user’s target price is
achieved.
Say, the current price of BTC is $28,000, a user sets an alert for BTC at a price of 33,000$.
The application should send an email to the user when the price of BTC reaches 33,000$.
Similarly, say, the current price of BTC is 35,000$, a user sets an alert for BTC at a price of
33,000$. The application should send an email when the price of BTC reaches 33,000$.
Things to do for the assignment
- Create a rest API endpoint for the user’s to create an alert `alerts/create/`
- Create a rest API endpoint for the user’s to delete an alert `alerts/delete/`
- Create a rest API endpoint to fetch all the alerts that the user has created.
- The response should also include the status of the alerts
(created/deleted/triggered/.. or any other status you feel needs to be included)
- Paginate the response.
- Include filter options based on the status of the alerts. Eg: if the user wanted
only the alerts that were triggered, then the endpoint should provide just that)
- Add user authentication to the endpoints. Use JWT tokens.
- There is no need to add tests.
- You can use Binance's WebSocket connection to get real-time price updates
