# prophet-challenge
You’re a growth analyst at Mercado LibreLinks to an external site.. With over 200 million users, Mercado Libre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

The instructions for this Challenge are divided into four steps, as follows:

Step 1: Find unusual patterns in hourly Google search traffic.

Step 2: Mine the search traffic data for seasonality.

Step 3: Relate the search traffic to stock price patterns.

Step 4: Create a time series model with Prophet.
## Code Considerations
- "#daily_search_data = df_mercado_trends.groupby(df_mercado_trends.index.isocalendar().day).mean().plot()" is code that was provided by the tutor. It helped me to identify that my own code was missing ".mean()"
- "mercado_prophet_df.columns = ['ds', 'y']" was code provided by the tutor to help me identify why my method of renaming the columns was not working on the index.

