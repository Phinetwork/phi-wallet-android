[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/PHIWallet/PHI-wallet-android)

# PHIWallet - Advanced, Open Source PHI Mobile Wallet & dApp Browser for Android

[![Lint](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/lint.yml/badge.svg?branch=master)](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/lint.yml)
[![Unit test](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/ci.yml)
[![E2E Test](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/e2e.yml/badge.svg?branch=master)](https://github.com/PHIWallet/PHI-wallet-android/actions/workflows/e2e.yml)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg )](https://github.com/PHIWallet/PHI-wallet-android/graphs/commit-activity)
![GitHub contributors](https://img.shields.io/github/contributors/PHIWallet/PHI-wallet-android.svg)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PHIWallet/PHI-wallet-android/blob/master/LICENSE)
[![codecov](https://codecov.io/gh/PHIWallet/PHI-wallet-android/branch/master/graph/badge.svg?token=IkoEb30CXq)](https://codecov.io/gh/PHIWallet/PHI-wallet-android)

PHIWallet is an open source programmable blockchain apps platform. It's compatible with tokenisation framework TokenScript, offering businesses and their users in-depth token interaction, a clean white label user experience and advanced security options. Supports all PHI based networks.

PHIWallet and TokenScript have been used by tokenisation projects like FIFA and UEFA’s [blockchain tickets](https://apps.apple.com/au/app/shankai/id1492559481), Bartercard’s [Qoin ecommerce ecosystem](https://apps.apple.com/au/app/qoin-wallet/id1483718254), several Automobiles’ [car ownership portal](https://github.com/PHIWallet/TokenScript-Examples/tree/master/examples/Karma) and many more.

⭐ Star us on GitHub — it helps!

[![PHIwallet open source wallet android preview](dmz/src/main/resources/static/readme/PHIwallet-open-source-PHI-wallet.jpg)](https://PHIwallet.com/)
<a href='https://play.google.com/store/apps/details?id=io.stormbird.wallet&hl=en&utm_source=github-readme&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get PHIWallet Open Source Wallet on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height="100"/></a>

## About PHIWallet - Features

Easy to use and secure open source PHI wallet for Android and iOS, with native ERC20, ERC721, ERC1155 and ERC875 support. PHIWallet supports all PHI based networks: PHI, xDai, PHI Classic, Artis, POA, Binance Smart Chain, Heco, Polygon, Avalanche, Fantom, L2 chains Optimistic and Arbitrum, and Palm.
TestChains: Ropsten, Goerli, Kovan, Rinkeby, Sokol, Binance Test, Heco Test, Fuji (Avalanche test), Fantom Test, Polygon Test, Optimistic and Arbitrum Test, Cronos Test and Palm test.

- Beginner Friendly
- Secure Enclave Security
- Web3 dApp Browser
- TokenScript Enabled
- Interact with DeFi, DAO and Games with SmartTokens
- No hidden fees or tech background needed

### AlphaWallet Is A Token Wallet

AlphaWallet's focus is to provide an interface to interact with Ethereum Tokens in an intuitive, simple and full featured manner. This is what sets us aside from other open source ethereum wallets.

### Select Use Cases

- [Bartercard Qoin](https://play.google.com/store/apps/details?id=com.qoin.wallet&hl=en)
- [FIFA and UEFA’s blockchain tickets](https://apps.apple.com/au/app/shankai/id1492559481)
- [Car Ownership portal](https://github.com/AlphaWallet/TokenScript-Examples/tree/master/examples/Karma)

### TokenScript Support

With TokenScript, you can extend your Token’s capabilities to become "smart" and secure, enabling a mobile-native user experience :iphone:

“SmartTokens” are traditional fungible and non fungible tokens that are extended with business logic, run natively inside the app and come with signed code to prevent tampering or phishing. It allows you to realise rich functions that Dapps previously struggled to implement. With SmartTokens you can get your token on iOS and Android in real time without the need to build your own ethereum wallet.

AlphaWallet is the “browser” for users to access these SmartTokens. You can get the most out of your use case implementation... without leaving the wallet.

Visit [TokenScript Documentation](https://github.com/AlphaWallet/TokenScript) or see [TokenScript Examples](https://github.com/AlphaWallet/TokenScript-Examples) to learn what you can do with it.

### Philosophy

AlphaWallet is founded by blockchain geeks, business professionals who believe blockchain technology will have a massive impact on the future and change the landscape of technology in general.

We are committed to connecting businesses and consumers with the new digital economic infrastructure through tokenisation. Tokenised rights can be traded on the market and integrated across systems, forming a Frictionless Market and allowing limitless integration with the web.

We want to give businesses the whitelabel tools they need to develop their ethereum wallets, and join the tokenised economy.

# Getting Started

1. [Download](https://developer.android.com/studio/) Android Studio.
2. Clone this repository
3. Obtain a free Infura API key and replace the one in build.gradle
4. Generate a GitHub [Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) with `read:packages, read:user` permission
5. Edit `~/.gradle/gradle.properties` add blow properties:
```properties
gpr.user=Your GitHub Email
gpr.key=The GitHub Personal Access Token you created in previous step
```
6. Build the project in AndroidStudio or Run `./gradlew build` to install tools and dependencies. See [BUILD.md](BUILD.md) for more details.

You can also build it from the commandline just like other Android apps. Note that JDK 8 and 11 are the versions supported by Android.

Find more information in our available [documentation](https://github.com/AlphaWallet/alpha-wallet-android/blob/master/docs/overview.md).

### Add your token to AlphaWallet

If you’d like to include TokenScript and extend your token functionalities, please refer to [TokenScript](https://github.com/AlphaWallet/TokenScript).

### Add dApp to the “Discover dApps” section in the browser

Submit a PR to the following file:
https://github.com/AlphaWallet/alpha-wallet-android/blob/master/app/src/main/assets/dapps_list.json

## How to Contribute

You can submit feedback and report bugs as Github issues. Please be sure to include your operating system, device, version number, and steps to reproduce reported bugs.

## How to customise the appearance of your wallet fork

If you are forking AlphaWallet, and have a token that you want to be locked visible this can now be done easily. Let's say we want to only show Ethereum Mainnet, and always show the USDC stablecoin.

```
class CustomViewSettings
{
```
...
```
    private static final List<TokenInfo> lockedTokens = Arrays.asList(
            // new TokenInfo(String TokenAddress, String TokenName, String TokenSymbol, int TokenDecimals, boolean isEnabled, long ChainId)
            new TokenInfo("0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48", "USD Coin", "USDC", 6, true, EthereumNetworkBase.MAINNET_ID)
    );
    
    private static final List<Integer> lockedChains = Arrays.asList(
            EthereumNetworkBase.MAINNET_ID
    );
```
Further, you may have your own Dapp that sells or uses the USDC that you want your users to use.
```
public static boolean minimiseBrowserURLBar() { return true; } //this removes the ability to enter URL's directly (they can be clicked on within your dapp)
```
```
public abstract class EthereumNetworkBase ...
{
    private static final String DEFAULT_HOMEPAGE = "https://my-awesome-nfts.com/usdc/";
```
If you are forking AlphaWallet and you have a cool Token, please consider donating a small amount of said Token to `alphawallet.eth` to help fund continuing development of the main repo.

### Request or submit a feature :postbox:

Would you like to request a feature? Please get in touch with us [Telegram](https://t.me/AlphaWalletGroup), [Discord](https://discord.gg/mx23YWRTYf), [Twitter](https://twitter.com/AlphaWallet) or through our [community forums](https://community.tokenscript.org/).

If you’d like to contribute code with a Pull Request, please make sure to follow code submission guidelines.

### Spread the word :hatched_chick:

We want to connect businesses and consumers with the new digital economic infrastructure, where everyone can benefit from technology-enabled free markets. Help us spread the word:

<a href="http://www.linkedin.com/shareArticle?mini=true&amp;url=https://github.com/AlphaWallet/alpha-wallet-android"><img src=dmz/src/main/resources/static/readme/share_linkedin-btn.svg height="35" alt="share on linkedin"></a>
<a href="https://twitter.com/share?url=https://github.com/AlphaWallet/alpha-wallet-android&amp;text=Open%20Source%20Wallet%20for%20Android&amp;hashtags=alphawallet"><img src=dmz/src/main/resources/static/readme/share_tweet-btn.svg height="35" alt="share on twitter"></a>
<a href="https://t.me/share/url?url=https://github.com/AlphaWallet/alpha-wallet-android&text=Check%20this%20out!"><img src=dmz/src/main/resources/static/readme/share_telegram-btn.svg height="35" alt="share on telegram"></a>
<a href="mailto:?Subject=open source alphawallet for android&amp;Body=Found%20this%20one,%20check%20it%20out!%20 https://github.com/AlphaWallet/alpha-wallet-android"><img src=dmz/src/main/resources/static/readme/share_mail-btn.svg height="35" alt="send via email"></a>
<a href="http://reddit.com/submit?url=https://github.com/AlphaWallet/alpha-wallet-android&amp;title=Open%20Source%20AlphaWallet%20for%20Android"><img src=dmz/src/main/resources/static/readme/share_reddit-btn.svg height="35" alt="share on reddit"></a>
<a href="http://www.facebook.com/sharer.php?u=https://github.com/AlphaWallet/alpha-wallet-android"><img src=dmz/src/main/resources/static/readme/share_facebook-btn.svg height="35" alt="share on facebook"></a>

To learn more about us, please check our Blog or join the conversation:
- [Blog](https://medium.com/alphawallet)
- [Telegram](https://t.me/AlphaWalletGroup)
- [Twitter](https://twitter.com/AlphaWallet)
- [Facebook](https://www.facebook.com/AlphaWallet)
- [LinkedIn](https://www.linkedin.com/company/alphawallet/)
- [Community forum](https://community.tokenscript.org/)

##license
AlphaWallet Android is available under the [MIT license](https://github.com/AlphaWallet/alpha-wallet-android/blob/master/LICENSE). Free for commercial and non-commercial use.
