# Automated Checkout Bot for Shopify Checkout Pages

This bot reads information from a CSV file and uses the information to automatically place orders on the Shopify default checkout pages.
Orders are executed in a similar fashion to humans, minimizing the risk of bot detection.
The point of this bot is to allow e-commerce dropshippers to space out their order fulfillment to prevent companies from knowing that they are dropshipping their products.

## Run Instructions: 

1. Create a new environment on Anaconda Navigator. Name it buying_bot
2. Open terminal and type in the following:

```bash
conda activate buying_bot
conda install selenium
conda install -c conda-forge python-chromedriver-binary
```   
3. Run the program in JupyterLab


