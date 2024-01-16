Trading
This repository was created to provide a solution for embedding TradingView widgets into Notion. Existing solutions are limited and often require a subscription.

Here is the suggested solution, totally free for personal usage:

1. Create the necessary widgets from TradingView's widget page (https://www.tradingview.com/widget/) and obtain the HTML code for each widget.
2. Create separage pages on GitHub to host each widget.
3. Use the githack service to obtain a "live" page for each widget. To do this, open the widget file on GitHub, click on the "Raw" button, and replace "githubusercontent" with "githack" in the URL. The new link will render the required widget in the browser.
4. Copy the new link and use it with the /embed function in Notion to embed the widget.

According to githack's policy (https://raw.githack.com/faq), the widget should remain live and cached for around one year. The resource is free to use.

Please note that the author of githack asks not to use it in live products or for commercial usage. However, it should be suitable for personal use in your trading book on Notion.
