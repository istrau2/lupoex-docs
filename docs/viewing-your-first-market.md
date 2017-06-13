##Viewing Your First Market

###What is a Stellar market
To explain what a stellar market is, it is better to start off with an explanation of stellar assets:

With the exception of XLM (stellar's native asset), stellar assets are basically securities issued by accounts (XLM has no issuing account since it is native to stellar).
Anyone with a stellar account can issue a stellar asset. Assets are defined by their asset code (e.g. USD, EUR, BTC) and asset issuer, which is just the public key of the issuing account.
This means that two accounts might issue an asset with the same asset code (USD for example), however these would be two seperate assets because their issuer is different.
Then, the asset issuer gives the asset value. At any point, you should be able to redeem the stellar asset for something in the real world via the issuer of the asset.
For example, a bank could issue a USD asset which it backs. Then, whenever any user sends it a USD Asset (issued by its account), the bank could give that user a real world dollar.

A stellar market is just the combination of two stellar assets, where users can buy asset A for asset B and vice versa. Since anyone on the stellar network can issue an asset, there is a ever-growing number of markets.

To learn more about stellar assets and markets, see the <a href="https://www.stellar.org/developers/guides/concepts/assets.html" target="_blank">Stellar Asset Concept Guide</a>

###Searching Stellar Assets
Lupoex makes it easy to search through the many markets on the stellar network. On the home screen, you can search for any selling and buying asset.
Just start typing in the code box and the dropdown will give you asset code suggestions (these suggestions are actual asset codes on the stellar network).
After you choose the asset code (USD or EUR etc.), you will need to choose an asset issuer (since, as we mentioned above multiple accounts can issue an asset with the same code).
The issuer box will give you suggestions of issuers that have issued an asset with the chosen code.

###Asset Verification
By now, if you have searched in the asset issuer box, you have probably noticed domain names next to the issuer addresses.
These domain names are website urls published by these accounts where you can learn more about that issuing account.
However, WAIT, any stellar account can claim to have any domain name they want. You could create a stellar account that claims google.com as its domain today!
That is where asset verification comes in to play.

Asset verification is a standard by which websites verify that they are indeed the ones that issued an asset.
So, for example, if you created an account that issued an asset and claimed google.com as its domain, that asset would not be verified.
It would be unverified unless you could go and get your asset (including your account's issuing address) listed on the real google.com.
In essence verification, is a process that allows the actual owners of websites verify that they are indeed the ones that own a stellar account that claims their domain.
Pay attention to the verification notifications that appear next to assets!

Once you have selected a buying asset code/issuer and a selling asset code/issuer, just click the 'Load button' to view that market on the Lupoex platform.