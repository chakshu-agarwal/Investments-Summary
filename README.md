WIP - Currently writes a summary of your stock portfolio and gains on Robinhood to a spreadsheet in Google Drive

# How to use it:
1. Open the notebook in Google Colab (Colab does not cost anything; all you need is a google account)
2. Run each block of code
3. In Block 3, replace MFA Key, Email and Password with the ones associated with your Robinhood account. You can retrieve the MFA key from your app if you have 2FA enabled - this is the same key that you enter in authenticator apps like Google Authenticator.
4. The code also has the capability to push the transaction summary to a google spreadsheet

# Next Steps:
1. Account for stock splits and acquisitions in stock price
2. Account for options
3. Account for wash sale
4. Tag investments by category (long terms - growth stocks, etf, short term - gambling money) to identify future investment split
5. Account for fees
6. Add other accounts (schwab)
7. Add UI layer
