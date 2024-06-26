# Leor Brenman's Profile

After graduating with a Master's in Electrical Engineering from [Rutgers University](https://www.rutgers.edu/), I worked as an Application Engineer and Field Application Engineer in the Semiconductor space. I worked for companies like [Texas Instruments](https://www.ti.com), [Conexant](https://en.wikipedia.org/wiki/Conexant) and startups Sierra Semiconductor and SmartLink focusing on digital signal processing (DSP) hardware and programming in assembler and C, modems, voice over IP (VOIP), pre-sales support, technical training and technical publishing.

More recently, I've worked as a Sales Engineer and Solution Architect in the Enterprise Software space working for companies like Vaultus (acquired by Antenna which was acquired by [Pega Systems](https://www.pega.com/)) and Appcelerator (acquired by [Axway](https://www.axway.com/en)). I've focused on cross device mobile app development, mobile backend as a service (MBaaS), API development and Integrations. In these roles I created numerous pre-sales and event demos, blog posts and training collateral as well as being the SME on several product areas.

Some of my projects can be found here:
* [**Github**](https://github.com/lbrenman?tab=repositories)
* [**DockerHub**](https://hub.docker.com/u/lbrenman)
* [**npm**](https://www.npmjs.com/settings/lbrenman/packages)
* [**Axway Blog Posts**](https://blog.axway.com/?s=leor+brenman)
* [**Featured Projects (LinkedIn)**](https://www.linkedin.com/in/leorbrenman/#Featured)
* [**Mobile Applications**](https://www.youtube.com/watch?v=dOfq4Vmq7Jg&list=PLrzsSWqqNjrkoPhryHTccJjbBp0fm2tWv)
* [**Texas Instruments Application Notes**](https://www.ti.com/sitesearch/en-us/docs/universalsearch.tsp?langPref=en-US#q=leor%20brenman)

## Some of the API’s I’ve built

* AWS Lambda and API Gateway - Created in JavaScript/NodeJS in Lambda and exposed via API Key in AWS API Gateway
    * [Comprehend](https://aws.amazon.com/comprehend/) - natural language processing (NLP) service that uses machine learning to analyze text and extract insights
        * Detect Dominant Language
        * Detect PII Entities
        * Detect Sentiment
        * Detect Toxic Content
    * [Medical Comprehend](https://aws.amazon.com/comprehend/medical/) - natural language processing (NLP) service that uses machine learning to extract health data from medical text
        * Detect Entities
        * Detect PHI
    * [Rekognition](https://aws.amazon.com/rekognition/) - image analysis service that makes it easy to add advanced computer vision capabilities to your applications
        * Detect Labels
        * Detect Moderation Labels
        * Detect PPE
        * Detect Text
    * [Translate](https://aws.amazon.com/translate/) - text translation service that uses advanced machine learning technologies to provide high-quality translations
    * [Google Gemini](https://gemini.google.com/app) - understand and generate text from a text prompt
        * Generate Text
    * Source code and OAS 3.0.1 docs can be found on [Github](https://github.com/lbrenman/my-lambda-javascript-apis)
* Amplify Integration - An integration platform (iPaaS) from Axway
    * [Stock](https://github.com/lbrenman/ai-stockquote) - based on [Yahoo Finance](https://financeapi.net/tutorial)
        * Quote - Returns a payload optimized quote
        * Watchlist - Returns a payload reduced array of stock quotes based on a comma separated list of US stock symbols
    * [Stock](https://github.com/lbrenman/ai-stockquote-fh) - based on [Finnhub](https://finnhub.io/)
        * Quote - Returns a payload optimized quote
        * Watchlist - Returns a payload reduced array of stock quotes based on a comma separated list of US stock symbols
* API Builder, an API Building framework from Axway based on JavaScript and NodeJS. All APIs use built API Key security
    * Watch List
        * Returns a payload reduced array of stock quotes based on a comma separated list of US stock symbols
        * Based on [Yahoo Finance](https://financeapi.net/tutorial)
        * Available on [Github](https://github.com/lbrenman/apib_watchlist) and on [DockerHub](https://hub.docker.com/repository/docker/lbrenman/watchlist/general) as a container
    * Detect Sentiment
        * Returns the sentiment of a string
        * Based on [AWS Comprehend](https://aws.amazon.com/comprehend/)
        * Available on [Github](https://github.com/lbrenman/apib_detectsentiment) and on [DockerHub](https://hub.docker.com/repository/docker/lbrenman/apib_detectsentiment/general) as a container
    * Detect Labels
        * Returns labels related to an image
        * Based on [AWS Rekognition](https://docs.aws.amazon.com/rekognition/)
        * Available on [Github](https://github.com/lbrenman/apib_detectlabels) and on [DockerHub](https://hub.docker.com/repository/docker/lbrenman/apib_detectlabels/general) as a container
    * Translate
        * Returns the translation of a string to a target language
        * Based on [AWS Translate](https://aws.amazon.com/translate/)
        * Available on [Github](https://github.com/lbrenman/apib_translate) and on [DockerHub](https://hub.docker.com/repository/docker/lbrenman/apib_translate/general) as a container
    * Other AWS Comprehend, Comprehend Medical and Rekognition APIs and Plugins for API Builder

## My Alexa Skills

All skills implemented in Lambda using JavaScript/NodeJS

* These are some of my Public Skills:
    * [MyAnimal](https://www.amazon.com/lbrenman-MyAnimal/dp/B06WRV2SMQ/ref=sr_1_1?crid=3RM8ELXLTCJUC&dib=eyJ2IjoiMSJ9.D-lrKSj9oI9Y2dYoFFteqw.tJVkvyrSXM0xsmgA2YPOQfogtdTTxGKD-xoCC8KAfNU&dib_tag=se&keywords=myanimal&qid=1719434017&s=digital-skills&sprefix=myanimal%2Calexa-skills%2C155&sr=1-1) - Play animal sounds
    * [Boston Bike](https://www.amazon.com/lbrenman-Boston-Bike/dp/B076HHMLL8/ref=sr_1_1?crid=1KQNRQA4B29KA&dib=eyJ2IjoiMSJ9.zFM9p_Q5_BW1ugjWYMK0bRc-5JhpXVoo99vcE8ZySCs.yufvIHu7EZcjWu3ImWGGG1Q1hgLICPoQZ0HLfZKNhpM&dib_tag=se&keywords=Boston+Bike&qid=1719434225&s=digital-skills&sprefix=boston+bike%2Calexa-skills%2C115&sr=1-1) - Find status of nearby Boston BlueBikes
    * [My Air Quality](https://www.amazon.com/lbrenman-My-Air-Quality/dp/B074TRFWLD/ref=sr_1_3?crid=3HR578GC1A2RF&dib=eyJ2IjoiMSJ9.izopGI2LXzcAdhE67DPv9A.fgStLtyVPLULo8fqkXBl6UGDo_7NnJMWnR-C5afiWts&dib_tag=se&keywords=my+air+quality&qid=1719434275&s=digital-skills&sprefix=my+air+quality%2Calexa-skills%2C100&sr=1-3) - Report air quality at your location
    * [StockLookup](https://www.amazon.com/lbrenman-StockLookup/dp/B06Y2JXPFF/ref=sr_1_1?crid=1J2VUJWXNT73K&dib=eyJ2IjoiMSJ9.TYJIXkzIN9Ngz6mkMnAnfQ.Pkarf991p4ycdO_UxmRceMhoUZF0dXsLE54_4R-IHP8&dib_tag=se&keywords=stock+lookup&qid=1719434322&s=digital-skills&sprefix=stocklookup%2Calexa-skills%2C89&sr=1-1) - Lookup stocks
    * Word Lookup - Random word, works of the day and word definitions
* Other demo skills related to work:
    * Griffin Healthcare - Check for relative’s medical adherence status
    * Imagine Bank - Check bank balances
    * My Shares - Check for new Syncplicity File Shares
    * MyApprovals - Check for new approvals and approve by voice
    * MyPO - Check Syncplicity watch folder for new PO’s and send via SMS
    * Sync Drive - read Syncplicity folders and files


<!--
**lbrenman/lbrenman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

### Hi there 👋
-->
