## RQ5 - To what extent are accepted code understandability improvements reverted? 

**Table of contents**
- [Patch merged](#patch-merged)
- [Patch reverted in the pull request](#patch-reverted-in-the-pull-request)
- [Patch in the last version of the file](#patch-in-the-last-version-of-the-file)
- [Patch reverted in the codebase history](#patch-reverted-in-the-codebase-history)

### Patch merged
| # | Understandability Smell | Improvement | Answer | ID (Link) |
|---|-------------------------|-------------|--------|-----------|
|1|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTgyNzc0OQ==](https://codeupcrc.github.io/?key=579)|
|2|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMjI0OTg5MA==](https://codeupcrc.github.io/?key=670)|
|3|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDI0MzE0Mg==](https://codeupcrc.github.io/?key=1753)|
|4|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDYyNzA3OTUwNg==](https://codeupcrc.github.io/?key=2211)|
|5|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDA0OTQxNA==](https://codeupcrc.github.io/?key=1586)|
|6|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTMwNTAwMA==](https://codeupcrc.github.io/?key=2046)|
|7|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNDUxOTQxOQ==](https://codeupcrc.github.io/?key=387)|
|8|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDc0NDA1Ng==](https://codeupcrc.github.io/?key=453)|
|9|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MzkxMTg3Ng==](https://codeupcrc.github.io/?key=754)|
|10|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NjM0ODkyNA==](https://codeupcrc.github.io/?key=2346)|
|11|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTMyMTU1Nw==](https://codeupcrc.github.io/?key=19)|
|12|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTE1NTA1NQ==](https://codeupcrc.github.io/?key=31)|
|13|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjQxMTI4Ng==](https://codeupcrc.github.io/?key=40)|
|14|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjY5ODE5OQ==](https://codeupcrc.github.io/?key=115)|
|15|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTQyODA4OA==](https://codeupcrc.github.io/?key=166)|
|16|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTUyMzc2Nw==](https://codeupcrc.github.io/?key=180)|
|17|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzMzMzc2OA==](https://codeupcrc.github.io/?key=189)|
|18|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzYyMjczMA==](https://codeupcrc.github.io/?key=211)|
|19|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDY0NTk0MQ==](https://codeupcrc.github.io/?key=222)|
|20|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDQ1OTkzOQ==](https://codeupcrc.github.io/?key=244)|
|21|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzMwNTQxNw==](https://codeupcrc.github.io/?key=340)|
|22|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODkzNzM4MA==](https://codeupcrc.github.io/?key=458)|
|23|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU0MzMwNg==](https://codeupcrc.github.io/?key=486)|
|24|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MDc1ODE5Mg==](https://codeupcrc.github.io/?key=571)|
|25|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODc2NjU1MA==](https://codeupcrc.github.io/?key=710)|
|26|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NDM0MTc2Nw==](https://codeupcrc.github.io/?key=779)|
|27|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjI4NDY2Mg==](https://codeupcrc.github.io/?key=860)|
|28|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODAxOTIxOQ==](https://codeupcrc.github.io/?key=902)|
|29|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzE3NDQxMQ==](https://codeupcrc.github.io/?key=1042)|
|30|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODA3MjA2OA==](https://codeupcrc.github.io/?key=1066)|
|31|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzM4MjM5Mw==](https://codeupcrc.github.io/?key=1336)|
|32|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTY3OTIyMg==](https://codeupcrc.github.io/?key=1401)|
|33|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0NzQ5Mw==](https://codeupcrc.github.io/?key=1419)|
|34|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODkyNzAxOA==](https://codeupcrc.github.io/?key=1759)|
|35|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDgwNjcxNw==](https://codeupcrc.github.io/?key=1930)|
|36|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjQzODUwNQ==](https://codeupcrc.github.io/?key=1935)|
|37|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDE3OTY4Ng==](https://codeupcrc.github.io/?key=1945)|
|38|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NTgzNTI5Ng==](https://codeupcrc.github.io/?key=1963)|
|39|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzY1MDIwNA==](https://codeupcrc.github.io/?key=1991)|
|40|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDUyMTgxMQ==](https://codeupcrc.github.io/?key=2033)|
|41|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTEyNTQzOQ==](https://codeupcrc.github.io/?key=2038)|
|42|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODkyNzY1Nw==](https://codeupcrc.github.io/?key=2080)|
|43|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2NzgyNTQ3OA==](https://codeupcrc.github.io/?key=2107)|
|44|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjc5MTE2NQ==](https://codeupcrc.github.io/?key=2133)|
|45|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTYyMTI5Ng==](https://codeupcrc.github.io/?key=2359)|
|46|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDc5MDIzNw==](https://codeupcrc.github.io/?key=2376)|
|47|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2NTk2OTgzMQ==](https://codeupcrc.github.io/?key=2382)|
|48|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjY1MjgwMg==](https://codeupcrc.github.io/?key=2393)|
|49|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTAwNTcyNw==](https://codeupcrc.github.io/?key=293)|
|50|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDY0NjgxOA==](https://codeupcrc.github.io/?key=478)|
|51|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTQxOTAwNA==](https://codeupcrc.github.io/?key=482)|
|52|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODcxMjE0MA==](https://codeupcrc.github.io/?key=508)|
|53|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODIxMzQ4Mw==](https://codeupcrc.github.io/?key=535)|
|54|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODYyODIyMg==](https://codeupcrc.github.io/?key=931)|
|55|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzEyOTQ2OA==](https://codeupcrc.github.io/?key=1205)|
|56|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTg0Mw==](https://codeupcrc.github.io/?key=1204)|
|57|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzI5MTM0Mg==](https://codeupcrc.github.io/?key=1577)|
|58|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NjI0NTEzNw==](https://codeupcrc.github.io/?key=1584)|
|59|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDkzOTA1Mg==](https://codeupcrc.github.io/?key=1883)|
|60|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY0NTUyMg==](https://codeupcrc.github.io/?key=352)|
|61|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTIzNDU4NQ==](https://codeupcrc.github.io/?key=811)|
|62|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTI5ODgxNg==](https://codeupcrc.github.io/?key=1308)|
|63|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzMyNzc4MA==](https://codeupcrc.github.io/?key=1314)|
|64|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MjQ3MTkzMQ==](https://codeupcrc.github.io/?key=1328)|
|65|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjgyMjIyMA==](https://codeupcrc.github.io/?key=1349)|
|66|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjUzNjgyNA==](https://codeupcrc.github.io/?key=1402)|
|67|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMDgzNjQ1OA==](https://codeupcrc.github.io/?key=1107)|
|68|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1MTcwMDU1NA==](https://codeupcrc.github.io/?key=1152)|
|69|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzY0NjA3MA==](https://codeupcrc.github.io/?key=1668)|
|70|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMTkzNjAzOQ==](https://codeupcrc.github.io/?key=2001)|
|71|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTI0MTU2Mg==](https://codeupcrc.github.io/?key=858)|
|72|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNzA5NzQxMg==](https://codeupcrc.github.io/?key=1059)|
|73|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjQzMzM5Mg==](https://codeupcrc.github.io/?key=2203)|
|74|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjIzMDU3MQ==](https://codeupcrc.github.io/?key=14)|
|75|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMzkxNTY5Ng==](https://codeupcrc.github.io/?key=66)|
|76|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjY1NTk3Mw==](https://codeupcrc.github.io/?key=332)|
|77|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODgyNjU5Mg==](https://codeupcrc.github.io/?key=1176)|
|78|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDQ0MTY1Mw==](https://codeupcrc.github.io/?key=1413)|
|79|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTg5NDkzMQ==](https://codeupcrc.github.io/?key=945)|
|80|Complex, long, or inadequate logic|Extract variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzE1Mjc2OQ==](https://codeupcrc.github.io/?key=564)|
|81|Complex, long, or inadequate logic|Invert the boolean expression to simplify it|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMjQwNzQ3Mw==](https://codeupcrc.github.io/?key=1012)|
|82|Complex, long, or inadequate logic|Move the code element to consistent place|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzE1MTM3NQ==](https://codeupcrc.github.io/?key=1735)|
|83|Complex, long, or inadequate logic|Remove the library name reference in fully qualifier name|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTY0OTUxMg==](https://codeupcrc.github.io/?key=266)|
|84|Complex, long, or inadequate logic|Remove the library name reference in fully qualifier name|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMTYyNDA2OA==](https://codeupcrc.github.io/?key=1779)|
|85|Complex, long, or inadequate logic|Replace a set of statements by direct method in existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1Mjc0NjI1Mg==](https://codeupcrc.github.io/?key=899)|
|86|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjE1ODU2OA==](https://codeupcrc.github.io/?key=4)|
|87|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAyMjI2Nw==](https://codeupcrc.github.io/?key=123)|
|88|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MjE3MjQyOA==](https://codeupcrc.github.io/?key=1101)|
|89|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDgwNjE4OA==](https://codeupcrc.github.io/?key=1517)|
|90|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg1MTIxMg==](https://codeupcrc.github.io/?key=1846)|
|91|Complex, long, or inadequate logic|Replace an expression that creates object by existing attribute|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2MjE4MzMzNg==](https://codeupcrc.github.io/?key=1337)|
|92|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjEwMDY2OA==](https://codeupcrc.github.io/?key=1737)|
|93|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjM1OTE1MQ==](https://codeupcrc.github.io/?key=1984)|
|94|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzY3NjMwNw==](https://codeupcrc.github.io/?key=2130)|
|95|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjU4NDEyNw==](https://codeupcrc.github.io/?key=58)|
|96|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDYwODY0Nw==](https://codeupcrc.github.io/?key=1971)|
|97|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNTExMDU3Ng==](https://codeupcrc.github.io/?key=2053)|
|98|Complex, long, or inadequate logic|Replace boolean expression by an alternative direct method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzI4NTI4MA==](https://codeupcrc.github.io/?key=626)|
|99|Complex, long, or inadequate logic|Replace boolean expression by an alternative direct method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5MTA1Mw==](https://codeupcrc.github.io/?key=2240)|
|100|Complex, long, or inadequate logic|Replace call to static method by instance method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzIxMzU4Nw==](https://codeupcrc.github.io/?key=125)|
|101|Complex, long, or inadequate logic|Replace call to static method by instance method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzUxNTI4NQ==](https://codeupcrc.github.io/?key=543)|
|102|Complex, long, or inadequate logic|Replace call to static method by instance method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3Njc2NDg4NA==](https://codeupcrc.github.io/?key=1616)|
|103|Complex, long, or inadequate logic|Replace indirect expression in parameter by direct value|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzY5NTYwOQ==](https://codeupcrc.github.io/?key=83)|
|104|Complex, long, or inadequate logic|Replace Lists.newArrayList by Arrays.asList|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTk5MzQyNA==](https://codeupcrc.github.io/?key=812)|
|105|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTQ3MzE0OA==](https://codeupcrc.github.io/?key=391)|
|106|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTQxMTA5Mw==](https://codeupcrc.github.io/?key=808)|
|107|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDU4NzQ3OQ==](https://codeupcrc.github.io/?key=1936)|
|108|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjY1Mjc3OA==](https://codeupcrc.github.io/?key=2123)|
|109|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTI3MTU5Mg==](https://codeupcrc.github.io/?key=1562)|
|110|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDY4NjQyNQ==](https://codeupcrc.github.io/?key=1700)|
|111|Complex, long, or inadequate logic|Replace short-circuit in stream by an alternative reducing operation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MTEzODQ4NA==](https://codeupcrc.github.io/?key=1872)|
|112|Complex, long, or inadequate logic|Replace the use of a parameter by an expression with another parameter|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjMwNjQ0MQ==](https://codeupcrc.github.io/?key=85)|
|113|Complex, long, or inadequate logic|Replace the while and switch structure by an alternative switch with default|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzY4NTg0MQ==](https://codeupcrc.github.io/?key=1029)|
|114|Complex, long, or inadequate logic|Replace usage of an external API by an internal one|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzM5MTQzNA==](https://codeupcrc.github.io/?key=463)|
|115|Complex, long, or inadequate logic|Replace usage of an external API by an internal one|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODM1ODU1Mw==](https://codeupcrc.github.io/?key=1060)|
|116|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzg0MDU0MQ==](https://codeupcrc.github.io/?key=777)|
|117|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ3NzA2NQ==](https://codeupcrc.github.io/?key=1878)|
|118|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzE2MDYwOQ==](https://codeupcrc.github.io/?key=1530)|
|119|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTAyNTE5OA==](https://codeupcrc.github.io/?key=350)|
|120|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyOTk2OTI5NQ==](https://codeupcrc.github.io/?key=1201)|
|121|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcyMjU3Nw==](https://codeupcrc.github.io/?key=1839)|
|122|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTc1NzcxOA==](https://codeupcrc.github.io/?key=1944)|
|123|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDU1OTM1Ng==](https://codeupcrc.github.io/?key=1089)|
|124|Inadequate logging and monitoring|Add logging code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzM0MDI5NA==](https://codeupcrc.github.io/?key=865)|
|125|Inadequate logging and monitoring|Add logging code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDc0NjczNw==](https://codeupcrc.github.io/?key=1135)|
|126|Inadequate logging and monitoring|Change generic exception to a specific|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjMzMzMxNw==](https://codeupcrc.github.io/?key=919)|
|127|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzAwODQzMA==](https://codeupcrc.github.io/?key=272)|
|128|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTUxNTQyNg==](https://codeupcrc.github.io/?key=704)|
|129|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU5ODU0MTI5NQ==](https://codeupcrc.github.io/?key=1173)|
|130|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDA1ODgzMg==](https://codeupcrc.github.io/?key=1751)|
|131|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQ3NjQ5Mw==](https://codeupcrc.github.io/?key=2094)|
|132|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MzcyNjQzOA==](https://codeupcrc.github.io/?key=691)|
|133|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTE0NDIyOA==](https://codeupcrc.github.io/?key=1021)|
|134|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzM2NDU1Ng==](https://codeupcrc.github.io/?key=2104)|
|135|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzkwNjc1MQ==](https://codeupcrc.github.io/?key=2337)|
|136|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2MjU3NDMyNw==](https://codeupcrc.github.io/?key=1189)|
|137|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NjU1NjQ4OA==](https://codeupcrc.github.io/?key=1678)|
|138|Incomplete or inadequate code documentation|Add code comment to explain an expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDYzNTEyMg==](https://codeupcrc.github.io/?key=61)|
|139|Incomplete or inadequate code documentation|Add code comment to explain an expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTk0NzE5Mw==](https://codeupcrc.github.io/?key=824)|
|140|Incomplete or inadequate code documentation|Add code comment to explain an expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzEzMzA5NQ==](https://codeupcrc.github.io/?key=1655)|
|141|Incomplete or inadequate code documentation|Add code comment to explain each part of a test|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDA5NDgzOA==](https://codeupcrc.github.io/?key=678)|
|142|Incomplete or inadequate code documentation|Add code comment to explain each part of a test|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTY5MTcwMA==](https://codeupcrc.github.io/?key=2209)|
|143|Incomplete or inadequate code documentation|Add code comment to explain the type of an attribute|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDcwMDUwNg==](https://codeupcrc.github.io/?key=2180)|
|144|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjE3NDUxNg==](https://codeupcrc.github.io/?key=373)|
|145|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTMyNzEwNQ==](https://codeupcrc.github.io/?key=756)|
|146|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQyNjY1Mw==](https://codeupcrc.github.io/?key=1051)|
|147|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ5NTU0OA==](https://codeupcrc.github.io/?key=1720)|
|148|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTQ5MTk4Mg==](https://codeupcrc.github.io/?key=1762)|
|149|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTg3NzU1Ng==](https://codeupcrc.github.io/?key=2244)|
|150|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzEyOTQxOA==](https://codeupcrc.github.io/?key=500)|
|151|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzA2OTAxNA==](https://codeupcrc.github.io/?key=2020)|
|152|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTc1NDM3NA==](https://codeupcrc.github.io/?key=1732)|
|153|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzAwOTA3OA==](https://codeupcrc.github.io/?key=294)|
|154|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxNzA0Mw==](https://codeupcrc.github.io/?key=1821)|
|155|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY5MjIzNQ==](https://codeupcrc.github.io/?key=2021)|
|156|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njg1MjAwMA==](https://codeupcrc.github.io/?key=2263)|
|157|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTQzNjg1OA==](https://codeupcrc.github.io/?key=1113)|
|158|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTg3OTMyOA==](https://codeupcrc.github.io/?key=1471)|
|159|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain internal implementation details of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI1MDc1OA==](https://codeupcrc.github.io/?key=922)|
|160|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain internal implementation details of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MTc1MDgwMg==](https://codeupcrc.github.io/?key=1118)|
|161|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain reason for deprecation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjcxMTIwOQ==](https://codeupcrc.github.io/?key=155)|
|162|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTIxMzgyNg==](https://codeupcrc.github.io/?key=427)|
|163|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzQ5Mjc4Nw==](https://codeupcrc.github.io/?key=1380)|
|164|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDY4MTA1OQ==](https://codeupcrc.github.io/?key=1385)|
|165|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc4ODQwMg==](https://codeupcrc.github.io/?key=2307)|
|166|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODY1MDc3Nw==](https://codeupcrc.github.io/?key=2127)|
|167|Incomplete or inadequate code documentation|Add text to existing Javadoc to improve explanation about code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTgxNDkyNA==](https://codeupcrc.github.io/?key=570)|
|168|Incomplete or inadequate code documentation|Add text to existing Javadoc to improve explanation about code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQ5NjIxNA==](https://codeupcrc.github.io/?key=930)|
|169|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjkzMDYyMA==](https://codeupcrc.github.io/?key=27)|
|170|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDkzMjg4Mw==](https://codeupcrc.github.io/?key=380)|
|171|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njc0Mjc0Nw==](https://codeupcrc.github.io/?key=1815)|
|172|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODkxNjAzNA==](https://codeupcrc.github.io/?key=1970)|
|173|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjQ1NTAzMA==](https://codeupcrc.github.io/?key=321)|
|174|Incomplete or inadequate code documentation|Change text in existing Javadoc to better explain the purpose of an annotation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Mzc0MDIxNQ==](https://codeupcrc.github.io/?key=920)|
|175|Incomplete or inadequate code documentation|Change text in existing Javadoc to fix the name of a code element to which it refers|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTQ3NDA5MQ==](https://codeupcrc.github.io/?key=1565)|
|176|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjA3NjU4NA==](https://codeupcrc.github.io/?key=151)|
|177|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjI2MzA1NQ==](https://codeupcrc.github.io/?key=727)|
|178|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MTY1OTkxNg==](https://codeupcrc.github.io/?key=766)|
|179|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU3NjE4Mg==](https://codeupcrc.github.io/?key=1476)|
|180|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTEzNDc5Ng==](https://codeupcrc.github.io/?key=2235)|
|181|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjExODQwMg==](https://codeupcrc.github.io/?key=1183)|
|182|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODkxNDk2Nw==](https://codeupcrc.github.io/?key=388)|
|183|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODM5MDA5MQ==](https://codeupcrc.github.io/?key=428)|
|184|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzQ2NjE3Mg==](https://codeupcrc.github.io/?key=429)|
|185|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NDI2MTMzMg==](https://codeupcrc.github.io/?key=755)|
|186|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NjY0OTk0NA==](https://codeupcrc.github.io/?key=1031)|
|187|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNzI1NTMwMA==](https://codeupcrc.github.io/?key=1298)|
|188|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzQ1MA==](https://codeupcrc.github.io/?key=1818)|
|189|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjY2OTI3Mw==](https://codeupcrc.github.io/?key=1934)|
|190|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzMzMzI0MQ==](https://codeupcrc.github.io/?key=2008)|
|191|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0MjA5MQ==](https://codeupcrc.github.io/?key=558)|
|192|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzY1MjYxNw==](https://codeupcrc.github.io/?key=876)|
|193|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDYyNzM4Mw==](https://codeupcrc.github.io/?key=926)|
|194|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQxOTAxNw==](https://codeupcrc.github.io/?key=1115)|
|195|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDk0NzIyMg==](https://codeupcrc.github.io/?key=1119)|
|196|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMzE5MzEzNA==](https://codeupcrc.github.io/?key=1449)|
|197|Incomplete or inadequate code documentation|Change text in existing Javadoc to make it more concise|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMyMDY1OA==](https://codeupcrc.github.io/?key=1894)|
|198|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTYxOTkzNg==](https://codeupcrc.github.io/?key=372)|
|199|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTYzOTA4OA==](https://codeupcrc.github.io/?key=803)|
|200|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2Mzc3Mzg4MQ==](https://codeupcrc.github.io/?key=2049)|
|201|Incomplete or inadequate code documentation|Move a tag of documentation to the conventional place|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NzczMTM4Mg==](https://codeupcrc.github.io/?key=196)|
|202|Incomplete or inadequate code documentation|Remove a useless code comment|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzkxNzU5Nw==](https://codeupcrc.github.io/?key=1829)|
|203|Incomplete or inadequate code documentation|Remove a useless code comment|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTM5MDIzMA==](https://codeupcrc.github.io/?key=2273)|
|204|Incomplete or inadequate code documentation|Remove TODO code comment for tasks that have already been performed|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTYxNjQ0MQ==](https://codeupcrc.github.io/?key=1032)|
|205|Incomplete or inadequate code documentation|Remove TODO code comment for tasks that have already been performed|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDkyMzYzMA==](https://codeupcrc.github.io/?key=2387)|
|206|Incomplete or inadequate code documentation|Transform a code comment into Javadoc documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc1NTQ4Mg==](https://codeupcrc.github.io/?key=1625)|
|207|Inconsistent or disrupted formatting|Add braces in a single statement block|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5Mjg1NjgyNw==](https://codeupcrc.github.io/?key=1078)|
|208|Inconsistent or disrupted formatting|Add line break to a long statement line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4Njg2MDE4Mw==](https://codeupcrc.github.io/?key=2325)|
|209|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzQ5ODc3Mg==](https://codeupcrc.github.io/?key=317)|
|210|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTA1MzcyMg==](https://codeupcrc.github.io/?key=683)|
|211|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDM2NzQyOA==](https://codeupcrc.github.io/?key=1754)|
|212|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMxMjA5OQ==](https://codeupcrc.github.io/?key=2050)|
|213|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDQyNjQ4Mg==](https://codeupcrc.github.io/?key=2204)|
|214|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTQ3OTQwNA==](https://codeupcrc.github.io/?key=2264)|
|215|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU3NjgzMTU0Nw==](https://codeupcrc.github.io/?key=2348)|
|216|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjcxODAyNg==](https://codeupcrc.github.io/?key=280)|
|217|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MDM2MTM0MQ==](https://codeupcrc.github.io/?key=490)|
|218|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNDQ5NDcyNg==](https://codeupcrc.github.io/?key=964)|
|219|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MjY3MzAzMQ==](https://codeupcrc.github.io/?key=1075)|
|220|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzA0ODY4NQ==](https://codeupcrc.github.io/?key=1450)|
|221|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTkxNTA3MQ==](https://codeupcrc.github.io/?key=1538)|
|222|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4OTYwMjg1OA==](https://codeupcrc.github.io/?key=762)|
|223|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzIxNDg0Mg==](https://codeupcrc.github.io/?key=1443)|
|224|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDYxOTM0MA==](https://codeupcrc.github.io/?key=1694)|
|225|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzM0MA==](https://codeupcrc.github.io/?key=1817)|
|226|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5NTAwMg==](https://codeupcrc.github.io/?key=1866)|
|227|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5Mjk4NDI4OQ==](https://codeupcrc.github.io/?key=1942)|
|228|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzAzNjQzNg==](https://codeupcrc.github.io/?key=1985)|
|229|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjEyMTMxMg==](https://codeupcrc.github.io/?key=1994)|
|230|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTM4NzU4Ng==](https://codeupcrc.github.io/?key=2026)|
|231|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNjk3OTU1NQ==](https://codeupcrc.github.io/?key=307)|
|232|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDEyNTI2MQ==](https://codeupcrc.github.io/?key=493)|
|233|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODc5ODU0OA==](https://codeupcrc.github.io/?key=1575)|
|234|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NTI1NTI1NQ==](https://codeupcrc.github.io/?key=1660)|
|235|Inconsistent or disrupted formatting|Add parentheses to compound logical expressions|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMDU2MDg3Ng==](https://codeupcrc.github.io/?key=1453)|
|236|Inconsistent or disrupted formatting|Change order of boolean expression operands to make null the second one|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTkyNjA5Nw==](https://codeupcrc.github.io/?key=2152)|
|237|Inconsistent or disrupted formatting|Move catch declaration to the same line of its associated try's closing block brace|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMTg1NjIwMQ==](https://codeupcrc.github.io/?key=1267)|
|238|Inconsistent or disrupted formatting|Move code elements to their own line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODc4OTY5Nw==](https://codeupcrc.github.io/?key=840)|
|239|Inconsistent or disrupted formatting|Move code elements to their own line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MTc1OTE2Mw==](https://codeupcrc.github.io/?key=1487)|
|240|Inconsistent or disrupted formatting|Move methods to be in call ordering|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0NDYzMg==](https://codeupcrc.github.io/?key=1860)|
|241|Inconsistent or disrupted formatting|Remove parentheses in logical expression operands and move them to separated lines|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTMwMjQ3MA==](https://codeupcrc.github.io/?key=1446)|
|242|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzYyMjcwNg==](https://codeupcrc.github.io/?key=277)|
|243|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MjQwMDc2NQ==](https://codeupcrc.github.io/?key=2071)|
|244|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzgxNTk3OA==](https://codeupcrc.github.io/?key=2163)|
|245|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjUzNDE2Mw==](https://codeupcrc.github.io/?key=2179)|
|246|Missing constant usage|Use a constant from a library|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjkyNzc5Mw==](https://codeupcrc.github.io/?key=590)|
|247|Missing constant usage|Use a constant from a library|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg2NjYwMQ==](https://codeupcrc.github.io/?key=1687)|
|248|Unnecessary Code|Inline temporary|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDU2NDEyNQ==](https://codeupcrc.github.io/?key=1561)|
|249|Unnecessary Code|Inline temporary|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDcyOTc0Mw==](https://codeupcrc.github.io/?key=1653)|
|250|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQxMDgzMw==](https://codeupcrc.github.io/?key=444)|
|251|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0Njc4NDIyOQ==](https://codeupcrc.github.io/?key=1074)|
|252|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDcyNzY0Mw==](https://codeupcrc.github.io/?key=1162)|
|253|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTY0NTEyNw==](https://codeupcrc.github.io/?key=1623)|
|254|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTg1MTU4OA==](https://codeupcrc.github.io/?key=688)|
|255|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4Njg2ODg2MA==](https://codeupcrc.github.io/?key=1411)|
|256|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1OTk4NTYwMw==](https://codeupcrc.github.io/?key=1741)|
|257|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODQ2Nzk3MQ==](https://codeupcrc.github.io/?key=2055)|
|258|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2ODQ5MTY4Nw==](https://codeupcrc.github.io/?key=2202)|
|259|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI2Njk3NQ==](https://codeupcrc.github.io/?key=2241)|
|260|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjU3MzIyMQ==](https://codeupcrc.github.io/?key=2140)|
|261|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4ODUzMjE0MQ==](https://codeupcrc.github.io/?key=325)|
|262|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODA4ODUyMQ==](https://codeupcrc.github.io/?key=536)|
|263|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MzMwNzc3OQ==](https://codeupcrc.github.io/?key=1087)|
|264|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzA5NDI5MA==](https://codeupcrc.github.io/?key=1108)|
|265|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NDc4NTMwOA==](https://codeupcrc.github.io/?key=1683)|
|266|Unnecessary Code|Remove imported type from fully qualified names|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDUzMTYzOA==](https://codeupcrc.github.io/?key=1943)|
|267|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQ1NzYxMQ==](https://codeupcrc.github.io/?key=20)|
|268|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4OTA5OTE0MA==](https://codeupcrc.github.io/?key=36)|
|269|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDQyNjYwNg==](https://codeupcrc.github.io/?key=64)|
|270|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzOTcyMjQ2Ng==](https://codeupcrc.github.io/?key=128)|
|271|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjUyMjkzNA==](https://codeupcrc.github.io/?key=780)|
|272|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDcwMA==](https://codeupcrc.github.io/?key=816)|
|273|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzc3MjkzOA==](https://codeupcrc.github.io/?key=821)|
|274|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODIzNjE3Nw==](https://codeupcrc.github.io/?key=1044)|
|275|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODY2NjcxOA==](https://codeupcrc.github.io/?key=1770)|
|276|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcxNjEzMA==](https://codeupcrc.github.io/?key=1838)|
|277|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDUyNjg1Nw==](https://codeupcrc.github.io/?key=2074)|
|278|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDg3NjA2OQ==](https://codeupcrc.github.io/?key=2105)|
|279|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODMyMTk3MQ==](https://codeupcrc.github.io/?key=2238)|
|280|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjUyMjU1NQ==](https://codeupcrc.github.io/?key=2251)|
|281|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjcwMTg1OA==](https://codeupcrc.github.io/?key=958)|
|282|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTU0OTg0OA==](https://codeupcrc.github.io/?key=1083)|
|283|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDk5MDE4Mg==](https://codeupcrc.github.io/?key=1218)|
|284|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTcxNTAzNg==](https://codeupcrc.github.io/?key=2073)|
|285|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTkwNDcxOQ==](https://codeupcrc.github.io/?key=2275)|
|286|Unnecessary Code|Remove null constants|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzMyNjg4NQ==](https://codeupcrc.github.io/?key=949)|
|287|Unnecessary Code|Remove this|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjcwODAyNw==](https://codeupcrc.github.io/?key=1871)|
|288|Unnecessary Code|Remove type parameter for inferrable type|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODU2NTU2NA==](https://codeupcrc.github.io/?key=236)|
|289|Wrong, missing, or inadequate string expression or literal|Add a message to an exception|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MzY5NTgzNw==](https://codeupcrc.github.io/?key=1345)|
|290|Wrong, missing, or inadequate string expression or literal|Add a message to an exception|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2Mzg0ODgzNw==](https://codeupcrc.github.io/?key=1803)|
|291|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTgxNTEzMQ==](https://codeupcrc.github.io/?key=1038)|
|292|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2MzE2MzEzNA==](https://codeupcrc.github.io/?key=2318)|
|293|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzYwMDQ0MQ==](https://codeupcrc.github.io/?key=1187)|
|294|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAzMzk3NA==](https://codeupcrc.github.io/?key=39)|
|295|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDYyOQ==](https://codeupcrc.github.io/?key=817)|
|296|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0MTE2OA==](https://codeupcrc.github.io/?key=1418)|
|297|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzkwMzU0OA==](https://codeupcrc.github.io/?key=60)|
|298|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg1NzQ5MA==](https://codeupcrc.github.io/?key=407)|
|299|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNTY4MTc3NQ==](https://codeupcrc.github.io/?key=2350)|
|300|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MTYyOTEwMg==](https://codeupcrc.github.io/?key=2317)|
|301|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTk0MjAyOA==](https://codeupcrc.github.io/?key=2365)|
|302|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NzAzOTQ1NA==](https://codeupcrc.github.io/?key=319)|
|303|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODk2NzYwNw==](https://codeupcrc.github.io/?key=976)|
|304|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjcxODY0NA==](https://codeupcrc.github.io/?key=1149)|
|305|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Nzk2MjM4MA==](https://codeupcrc.github.io/?key=1604)|
|306|Wrong, missing, or inadequate string expression or literal|Fix an incorrect value|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDE5MDcxOQ==](https://codeupcrc.github.io/?key=1246)|
|307|Wrong, missing, or inadequate string expression or literal|Fix an incorrect value|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjQ1NjQzMA==](https://codeupcrc.github.io/?key=1642)|
|308|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjg2ODg4Ng==](https://codeupcrc.github.io/?key=542)|
|309|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDY2NTQ4Nw==](https://codeupcrc.github.io/?key=786)|
|310|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNzc4NzkwNA==](https://codeupcrc.github.io/?key=2287)|
|311|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzY4NzY1MA==](https://codeupcrc.github.io/?key=509)|
|312|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODU1MDk0NA==](https://codeupcrc.github.io/?key=1072)|
|313|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMjM0OTI5Mw==](https://codeupcrc.github.io/?key=2068)|
|314|Wrong, missing, or inadequate string expression or literal|Replace the use of the format method with string concatenation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzM1MDM5MQ==](https://codeupcrc.github.io/?key=2212)|
|315|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTAzOA==](https://codeupcrc.github.io/?key=1203)|
|316|Complex, long, or inadequate logic|Replace a set of statements by direct method in existing API|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTAwOTA3OA==](https://codeupcrc.github.io/?key=416)|
|317|Inadequate logging and monitoring|Add logging code|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNTI3MDY3NA==](https://codeupcrc.github.io/?key=1286)|
|318|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODc0NzM2MQ==](https://codeupcrc.github.io/?key=1338)|
|319|Incomplete or inadequate code documentation|Change text in code comment to fix typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjU3Mzk0MA==](https://codeupcrc.github.io/?key=182)|
|320|Inconsistent or disrupted formatting|Add braces in a single statement block|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTgwMjc1OQ==](https://codeupcrc.github.io/?key=2148)|
|321|Inconsistent or disrupted formatting|Move code elements to their own line|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzI1NTc2NA==](https://codeupcrc.github.io/?key=2024)|
|322|Unnecessary Code|Remove commented out code statements|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTg1NjU4OA==](https://codeupcrc.github.io/?key=2065)|
|323|Unnecessary Code|Remove duplicated code or processing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg5ODUwMA==](https://codeupcrc.github.io/?key=1992)|

### Patch reverted in the pull request
| # | Understandability Smell | Improvement | Answer | ID (Link) |
|---|-------------------------|-------------|--------|-----------|
|1|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTAzOA==](https://codeupcrc.github.io/?key=1203)|
|2|Complex, long, or inadequate logic|Replace a set of statements by direct method in existing API|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTAwOTA3OA==](https://codeupcrc.github.io/?key=416)|
|3|Inadequate logging and monitoring|Add logging code|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNTI3MDY3NA==](https://codeupcrc.github.io/?key=1286)|
|4|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODc0NzM2MQ==](https://codeupcrc.github.io/?key=1338)|
|5|Incomplete or inadequate code documentation|Change text in code comment to fix typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjU3Mzk0MA==](https://codeupcrc.github.io/?key=182)|
|6|Inconsistent or disrupted formatting|Add braces in a single statement block|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTgwMjc1OQ==](https://codeupcrc.github.io/?key=2148)|
|7|Inconsistent or disrupted formatting|Move code elements to their own line|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzI1NTc2NA==](https://codeupcrc.github.io/?key=2024)|
|8|Unnecessary Code|Remove commented out code statements|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTg1NjU4OA==](https://codeupcrc.github.io/?key=2065)|
|9|Unnecessary Code|Remove duplicated code or processing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg5ODUwMA==](https://codeupcrc.github.io/?key=1992)|

### Patch in the last version of the file
| # | Understandability Smell | Improvement | Answer | ID (Link) |
|---|-------------------------|-------------|--------|-----------|
|1|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTgyNzc0OQ==](https://codeupcrc.github.io/?key=579)|
|2|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDI0MzE0Mg==](https://codeupcrc.github.io/?key=1753)|
|3|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDYyNzA3OTUwNg==](https://codeupcrc.github.io/?key=2211)|
|4|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDA0OTQxNA==](https://codeupcrc.github.io/?key=1586)|
|5|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTMwNTAwMA==](https://codeupcrc.github.io/?key=2046)|
|6|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNDUxOTQxOQ==](https://codeupcrc.github.io/?key=387)|
|7|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDc0NDA1Ng==](https://codeupcrc.github.io/?key=453)|
|8|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MzkxMTg3Ng==](https://codeupcrc.github.io/?key=754)|
|9|Bad identifier|Modify an identifier to be consistent with a convention|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NjM0ODkyNA==](https://codeupcrc.github.io/?key=2346)|
|10|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTMyMTU1Nw==](https://codeupcrc.github.io/?key=19)|
|11|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTE1NTA1NQ==](https://codeupcrc.github.io/?key=31)|
|12|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTQyODA4OA==](https://codeupcrc.github.io/?key=166)|
|13|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTUyMzc2Nw==](https://codeupcrc.github.io/?key=180)|
|14|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzMzMzc2OA==](https://codeupcrc.github.io/?key=189)|
|15|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzYyMjczMA==](https://codeupcrc.github.io/?key=211)|
|16|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDY0NTk0MQ==](https://codeupcrc.github.io/?key=222)|
|17|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDQ1OTkzOQ==](https://codeupcrc.github.io/?key=244)|
|18|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODkzNzM4MA==](https://codeupcrc.github.io/?key=458)|
|19|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MDc1ODE5Mg==](https://codeupcrc.github.io/?key=571)|
|20|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODc2NjU1MA==](https://codeupcrc.github.io/?key=710)|
|21|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NDM0MTc2Nw==](https://codeupcrc.github.io/?key=779)|
|22|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjI4NDY2Mg==](https://codeupcrc.github.io/?key=860)|
|23|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODAxOTIxOQ==](https://codeupcrc.github.io/?key=902)|
|24|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzE3NDQxMQ==](https://codeupcrc.github.io/?key=1042)|
|25|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODA3MjA2OA==](https://codeupcrc.github.io/?key=1066)|
|26|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzM4MjM5Mw==](https://codeupcrc.github.io/?key=1336)|
|27|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTY3OTIyMg==](https://codeupcrc.github.io/?key=1401)|
|28|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0NzQ5Mw==](https://codeupcrc.github.io/?key=1419)|
|29|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDgwNjcxNw==](https://codeupcrc.github.io/?key=1930)|
|30|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDE3OTY4Ng==](https://codeupcrc.github.io/?key=1945)|
|31|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NTgzNTI5Ng==](https://codeupcrc.github.io/?key=1963)|
|32|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzY1MDIwNA==](https://codeupcrc.github.io/?key=1991)|
|33|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDUyMTgxMQ==](https://codeupcrc.github.io/?key=2033)|
|34|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODkyNzY1Nw==](https://codeupcrc.github.io/?key=2080)|
|35|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjc5MTE2NQ==](https://codeupcrc.github.io/?key=2133)|
|36|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTYyMTI5Ng==](https://codeupcrc.github.io/?key=2359)|
|37|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDc5MDIzNw==](https://codeupcrc.github.io/?key=2376)|
|38|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2NTk2OTgzMQ==](https://codeupcrc.github.io/?key=2382)|
|39|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjY1MjgwMg==](https://codeupcrc.github.io/?key=2393)|
|40|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTAwNTcyNw==](https://codeupcrc.github.io/?key=293)|
|41|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDY0NjgxOA==](https://codeupcrc.github.io/?key=478)|
|42|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODcxMjE0MA==](https://codeupcrc.github.io/?key=508)|
|43|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODIxMzQ4Mw==](https://codeupcrc.github.io/?key=535)|
|44|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODYyODIyMg==](https://codeupcrc.github.io/?key=931)|
|45|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzEyOTQ2OA==](https://codeupcrc.github.io/?key=1205)|
|46|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTg0Mw==](https://codeupcrc.github.io/?key=1204)|
|47|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NjI0NTEzNw==](https://codeupcrc.github.io/?key=1584)|
|48|Bad identifier|Modify an identifier to express the meaning or type of an element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDkzOTA1Mg==](https://codeupcrc.github.io/?key=1883)|
|49|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTIzNDU4NQ==](https://codeupcrc.github.io/?key=811)|
|50|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTI5ODgxNg==](https://codeupcrc.github.io/?key=1308)|
|51|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzMyNzc4MA==](https://codeupcrc.github.io/?key=1314)|
|52|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MjQ3MTkzMQ==](https://codeupcrc.github.io/?key=1328)|
|53|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjUzNjgyNA==](https://codeupcrc.github.io/?key=1402)|
|54|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMDgzNjQ1OA==](https://codeupcrc.github.io/?key=1107)|
|55|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1MTcwMDU1NA==](https://codeupcrc.github.io/?key=1152)|
|56|Bad identifier|Modify an identifier to fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMTkzNjAzOQ==](https://codeupcrc.github.io/?key=2001)|
|57|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTI0MTU2Mg==](https://codeupcrc.github.io/?key=858)|
|58|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNzA5NzQxMg==](https://codeupcrc.github.io/?key=1059)|
|59|Complex, long, or inadequate logic|Expand the imports|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjQzMzM5Mg==](https://codeupcrc.github.io/?key=2203)|
|60|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjIzMDU3MQ==](https://codeupcrc.github.io/?key=14)|
|61|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMzkxNTY5Ng==](https://codeupcrc.github.io/?key=66)|
|62|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjY1NTk3Mw==](https://codeupcrc.github.io/?key=332)|
|63|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODgyNjU5Mg==](https://codeupcrc.github.io/?key=1176)|
|64|Complex, long, or inadequate logic|Extract method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTg5NDkzMQ==](https://codeupcrc.github.io/?key=945)|
|65|Complex, long, or inadequate logic|Extract variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzE1Mjc2OQ==](https://codeupcrc.github.io/?key=564)|
|66|Complex, long, or inadequate logic|Invert the boolean expression to simplify it|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMjQwNzQ3Mw==](https://codeupcrc.github.io/?key=1012)|
|67|Complex, long, or inadequate logic|Move the code element to consistent place|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzE1MTM3NQ==](https://codeupcrc.github.io/?key=1735)|
|68|Complex, long, or inadequate logic|Remove the library name reference in fully qualifier name|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTY0OTUxMg==](https://codeupcrc.github.io/?key=266)|
|69|Complex, long, or inadequate logic|Remove the library name reference in fully qualifier name|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMTYyNDA2OA==](https://codeupcrc.github.io/?key=1779)|
|70|Complex, long, or inadequate logic|Replace a set of statements by direct method in existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1Mjc0NjI1Mg==](https://codeupcrc.github.io/?key=899)|
|71|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjE1ODU2OA==](https://codeupcrc.github.io/?key=4)|
|72|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MjE3MjQyOA==](https://codeupcrc.github.io/?key=1101)|
|73|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDgwNjE4OA==](https://codeupcrc.github.io/?key=1517)|
|74|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg1MTIxMg==](https://codeupcrc.github.io/?key=1846)|
|75|Complex, long, or inadequate logic|Replace an expression that creates object by existing attribute|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2MjE4MzMzNg==](https://codeupcrc.github.io/?key=1337)|
|76|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjEwMDY2OA==](https://codeupcrc.github.io/?key=1737)|
|77|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjM1OTE1MQ==](https://codeupcrc.github.io/?key=1984)|
|78|Complex, long, or inadequate logic|Replace an imperative logic by functional|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzY3NjMwNw==](https://codeupcrc.github.io/?key=2130)|
|79|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjU4NDEyNw==](https://codeupcrc.github.io/?key=58)|
|80|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDYwODY0Nw==](https://codeupcrc.github.io/?key=1971)|
|81|Complex, long, or inadequate logic|Replace boolean expression by an alternative direct method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzI4NTI4MA==](https://codeupcrc.github.io/?key=626)|
|82|Complex, long, or inadequate logic|Replace boolean expression by an alternative direct method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5MTA1Mw==](https://codeupcrc.github.io/?key=2240)|
|83|Complex, long, or inadequate logic|Replace call to static method by instance method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzIxMzU4Nw==](https://codeupcrc.github.io/?key=125)|
|84|Complex, long, or inadequate logic|Replace call to static method by instance method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3Njc2NDg4NA==](https://codeupcrc.github.io/?key=1616)|
|85|Complex, long, or inadequate logic|Replace Lists.newArrayList by Arrays.asList|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTk5MzQyNA==](https://codeupcrc.github.io/?key=812)|
|86|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTQ3MzE0OA==](https://codeupcrc.github.io/?key=391)|
|87|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTQxMTA5Mw==](https://codeupcrc.github.io/?key=808)|
|88|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjY1Mjc3OA==](https://codeupcrc.github.io/?key=2123)|
|89|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTI3MTU5Mg==](https://codeupcrc.github.io/?key=1562)|
|90|Complex, long, or inadequate logic|Replace method calling chain by existing API|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDY4NjQyNQ==](https://codeupcrc.github.io/?key=1700)|
|91|Complex, long, or inadequate logic|Replace short-circuit in stream by an alternative reducing operation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MTEzODQ4NA==](https://codeupcrc.github.io/?key=1872)|
|92|Complex, long, or inadequate logic|Replace the use of a parameter by an expression with another parameter|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjMwNjQ0MQ==](https://codeupcrc.github.io/?key=85)|
|93|Complex, long, or inadequate logic|Replace the while and switch structure by an alternative switch with default|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzY4NTg0MQ==](https://codeupcrc.github.io/?key=1029)|
|94|Complex, long, or inadequate logic|Replace usage of an external API by an internal one|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzM5MTQzNA==](https://codeupcrc.github.io/?key=463)|
|95|Complex, long, or inadequate logic|Replace usage of an external API by an internal one|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODM1ODU1Mw==](https://codeupcrc.github.io/?key=1060)|
|96|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzg0MDU0MQ==](https://codeupcrc.github.io/?key=777)|
|97|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzE2MDYwOQ==](https://codeupcrc.github.io/?key=1530)|
|98|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyOTk2OTI5NQ==](https://codeupcrc.github.io/?key=1201)|
|99|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcyMjU3Nw==](https://codeupcrc.github.io/?key=1839)|
|100|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTc1NzcxOA==](https://codeupcrc.github.io/?key=1944)|
|101|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDU1OTM1Ng==](https://codeupcrc.github.io/?key=1089)|
|102|Inadequate logging and monitoring|Add logging code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzM0MDI5NA==](https://codeupcrc.github.io/?key=865)|
|103|Inadequate logging and monitoring|Add logging code|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDc0NjczNw==](https://codeupcrc.github.io/?key=1135)|
|104|Inadequate logging and monitoring|Change generic exception to a specific|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjMzMzMxNw==](https://codeupcrc.github.io/?key=919)|
|105|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTUxNTQyNg==](https://codeupcrc.github.io/?key=704)|
|106|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU5ODU0MTI5NQ==](https://codeupcrc.github.io/?key=1173)|
|107|Inadequate logging and monitoring|Change log settings|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQ3NjQ5Mw==](https://codeupcrc.github.io/?key=2094)|
|108|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTE0NDIyOA==](https://codeupcrc.github.io/?key=1021)|
|109|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzM2NDU1Ng==](https://codeupcrc.github.io/?key=2104)|
|110|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2MjU3NDMyNw==](https://codeupcrc.github.io/?key=1189)|
|111|Inadequate logging and monitoring|Remove log|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NjU1NjQ4OA==](https://codeupcrc.github.io/?key=1678)|
|112|Incomplete or inadequate code documentation|Add code comment to explain an expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDYzNTEyMg==](https://codeupcrc.github.io/?key=61)|
|113|Incomplete or inadequate code documentation|Add code comment to explain an expression|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzEzMzA5NQ==](https://codeupcrc.github.io/?key=1655)|
|114|Incomplete or inadequate code documentation|Add code comment to explain each part of a test|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDA5NDgzOA==](https://codeupcrc.github.io/?key=678)|
|115|Incomplete or inadequate code documentation|Add code comment to explain each part of a test|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTY5MTcwMA==](https://codeupcrc.github.io/?key=2209)|
|116|Incomplete or inadequate code documentation|Add code comment to explain the type of an attribute|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDcwMDUwNg==](https://codeupcrc.github.io/?key=2180)|
|117|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjE3NDUxNg==](https://codeupcrc.github.io/?key=373)|
|118|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTMyNzEwNQ==](https://codeupcrc.github.io/?key=756)|
|119|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQyNjY1Mw==](https://codeupcrc.github.io/?key=1051)|
|120|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ5NTU0OA==](https://codeupcrc.github.io/?key=1720)|
|121|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTQ5MTk4Mg==](https://codeupcrc.github.io/?key=1762)|
|122|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzEyOTQxOA==](https://codeupcrc.github.io/?key=500)|
|123|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzA2OTAxNA==](https://codeupcrc.github.io/?key=2020)|
|124|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTc1NDM3NA==](https://codeupcrc.github.io/?key=1732)|
|125|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzAwOTA3OA==](https://codeupcrc.github.io/?key=294)|
|126|Incomplete or inadequate code documentation|Add new tag and hyperlink to existing Javadoc|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxNzA0Mw==](https://codeupcrc.github.io/?key=1821)|
|127|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY5MjIzNQ==](https://codeupcrc.github.io/?key=2021)|
|128|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTQzNjg1OA==](https://codeupcrc.github.io/?key=1113)|
|129|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain internal implementation details of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI1MDc1OA==](https://codeupcrc.github.io/?key=922)|
|130|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain reason for deprecation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjcxMTIwOQ==](https://codeupcrc.github.io/?key=155)|
|131|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzQ5Mjc4Nw==](https://codeupcrc.github.io/?key=1380)|
|132|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDY4MTA1OQ==](https://codeupcrc.github.io/?key=1385)|
|133|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc4ODQwMg==](https://codeupcrc.github.io/?key=2307)|
|134|Incomplete or inadequate code documentation|Add text to existing Javadoc to improve explanation about code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQ5NjIxNA==](https://codeupcrc.github.io/?key=930)|
|135|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjkzMDYyMA==](https://codeupcrc.github.io/?key=27)|
|136|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDkzMjg4Mw==](https://codeupcrc.github.io/?key=380)|
|137|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njc0Mjc0Nw==](https://codeupcrc.github.io/?key=1815)|
|138|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODkxNjAzNA==](https://codeupcrc.github.io/?key=1970)|
|139|Incomplete or inadequate code documentation|Change text in existing Javadoc to better explain the purpose of an annotation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Mzc0MDIxNQ==](https://codeupcrc.github.io/?key=920)|
|140|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjI2MzA1NQ==](https://codeupcrc.github.io/?key=727)|
|141|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MTY1OTkxNg==](https://codeupcrc.github.io/?key=766)|
|142|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU3NjE4Mg==](https://codeupcrc.github.io/?key=1476)|
|143|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTEzNDc5Ng==](https://codeupcrc.github.io/?key=2235)|
|144|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjExODQwMg==](https://codeupcrc.github.io/?key=1183)|
|145|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODkxNDk2Nw==](https://codeupcrc.github.io/?key=388)|
|146|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NDI2MTMzMg==](https://codeupcrc.github.io/?key=755)|
|147|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NjY0OTk0NA==](https://codeupcrc.github.io/?key=1031)|
|148|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNzI1NTMwMA==](https://codeupcrc.github.io/?key=1298)|
|149|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzQ1MA==](https://codeupcrc.github.io/?key=1818)|
|150|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjY2OTI3Mw==](https://codeupcrc.github.io/?key=1934)|
|151|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzMzMzI0MQ==](https://codeupcrc.github.io/?key=2008)|
|152|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0MjA5MQ==](https://codeupcrc.github.io/?key=558)|
|153|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzY1MjYxNw==](https://codeupcrc.github.io/?key=876)|
|154|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDYyNzM4Mw==](https://codeupcrc.github.io/?key=926)|
|155|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDk0NzIyMg==](https://codeupcrc.github.io/?key=1119)|
|156|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMzE5MzEzNA==](https://codeupcrc.github.io/?key=1449)|
|157|Incomplete or inadequate code documentation|Change text in existing Javadoc to make it more concise|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMyMDY1OA==](https://codeupcrc.github.io/?key=1894)|
|158|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTYxOTkzNg==](https://codeupcrc.github.io/?key=372)|
|159|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTYzOTA4OA==](https://codeupcrc.github.io/?key=803)|
|160|Incomplete or inadequate code documentation|Change text in existing Javadoc to update copyright|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2Mzc3Mzg4MQ==](https://codeupcrc.github.io/?key=2049)|
|161|Incomplete or inadequate code documentation|Move a tag of documentation to the conventional place|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NzczMTM4Mg==](https://codeupcrc.github.io/?key=196)|
|162|Incomplete or inadequate code documentation|Remove a useless code comment|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTM5MDIzMA==](https://codeupcrc.github.io/?key=2273)|
|163|Incomplete or inadequate code documentation|Remove TODO code comment for tasks that have already been performed|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTYxNjQ0MQ==](https://codeupcrc.github.io/?key=1032)|
|164|Incomplete or inadequate code documentation|Remove TODO code comment for tasks that have already been performed|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDkyMzYzMA==](https://codeupcrc.github.io/?key=2387)|
|165|Incomplete or inadequate code documentation|Transform a code comment into Javadoc documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc1NTQ4Mg==](https://codeupcrc.github.io/?key=1625)|
|166|Inconsistent or disrupted formatting|Add braces in a single statement block|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5Mjg1NjgyNw==](https://codeupcrc.github.io/?key=1078)|
|167|Inconsistent or disrupted formatting|Add line break to a long statement line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4Njg2MDE4Mw==](https://codeupcrc.github.io/?key=2325)|
|168|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzQ5ODc3Mg==](https://codeupcrc.github.io/?key=317)|
|169|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTA1MzcyMg==](https://codeupcrc.github.io/?key=683)|
|170|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDM2NzQyOA==](https://codeupcrc.github.io/?key=1754)|
|171|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMxMjA5OQ==](https://codeupcrc.github.io/?key=2050)|
|172|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDQyNjQ4Mg==](https://codeupcrc.github.io/?key=2204)|
|173|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTQ3OTQwNA==](https://codeupcrc.github.io/?key=2264)|
|174|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU3NjgzMTU0Nw==](https://codeupcrc.github.io/?key=2348)|
|175|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MDM2MTM0MQ==](https://codeupcrc.github.io/?key=490)|
|176|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNDQ5NDcyNg==](https://codeupcrc.github.io/?key=964)|
|177|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MjY3MzAzMQ==](https://codeupcrc.github.io/?key=1075)|
|178|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzA0ODY4NQ==](https://codeupcrc.github.io/?key=1450)|
|179|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTkxNTA3MQ==](https://codeupcrc.github.io/?key=1538)|
|180|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4OTYwMjg1OA==](https://codeupcrc.github.io/?key=762)|
|181|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDYxOTM0MA==](https://codeupcrc.github.io/?key=1694)|
|182|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzM0MA==](https://codeupcrc.github.io/?key=1817)|
|183|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5NTAwMg==](https://codeupcrc.github.io/?key=1866)|
|184|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5Mjk4NDI4OQ==](https://codeupcrc.github.io/?key=1942)|
|185|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzAzNjQzNg==](https://codeupcrc.github.io/?key=1985)|
|186|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjEyMTMxMg==](https://codeupcrc.github.io/?key=1994)|
|187|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTM4NzU4Ng==](https://codeupcrc.github.io/?key=2026)|
|188|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDEyNTI2MQ==](https://codeupcrc.github.io/?key=493)|
|189|Inconsistent or disrupted formatting|Add or remove vertical spacing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NTI1NTI1NQ==](https://codeupcrc.github.io/?key=1660)|
|190|Inconsistent or disrupted formatting|Move catch declaration to the same line of its associated try's closing block brace|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMTg1NjIwMQ==](https://codeupcrc.github.io/?key=1267)|
|191|Inconsistent or disrupted formatting|Move code elements to their own line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODc4OTY5Nw==](https://codeupcrc.github.io/?key=840)|
|192|Inconsistent or disrupted formatting|Move code elements to their own line|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MTc1OTE2Mw==](https://codeupcrc.github.io/?key=1487)|
|193|Inconsistent or disrupted formatting|Remove parentheses in logical expression operands and move them to separated lines|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTMwMjQ3MA==](https://codeupcrc.github.io/?key=1446)|
|194|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzYyMjcwNg==](https://codeupcrc.github.io/?key=277)|
|195|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MjQwMDc2NQ==](https://codeupcrc.github.io/?key=2071)|
|196|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzgxNTk3OA==](https://codeupcrc.github.io/?key=2163)|
|197|Missing constant usage|Replace hardcoded value by a new constant|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjUzNDE2Mw==](https://codeupcrc.github.io/?key=2179)|
|198|Missing constant usage|Use a constant from a library|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjkyNzc5Mw==](https://codeupcrc.github.io/?key=590)|
|199|Missing constant usage|Use a constant from a library|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg2NjYwMQ==](https://codeupcrc.github.io/?key=1687)|
|200|Unnecessary Code|Inline temporary|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDU2NDEyNQ==](https://codeupcrc.github.io/?key=1561)|
|201|Unnecessary Code|Inline temporary|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDcyOTc0Mw==](https://codeupcrc.github.io/?key=1653)|
|202|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQxMDgzMw==](https://codeupcrc.github.io/?key=444)|
|203|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0Njc4NDIyOQ==](https://codeupcrc.github.io/?key=1074)|
|204|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDcyNzY0Mw==](https://codeupcrc.github.io/?key=1162)|
|205|Unnecessary Code|Remove commented out code statements|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTY0NTEyNw==](https://codeupcrc.github.io/?key=1623)|
|206|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTg1MTU4OA==](https://codeupcrc.github.io/?key=688)|
|207|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4Njg2ODg2MA==](https://codeupcrc.github.io/?key=1411)|
|208|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1OTk4NTYwMw==](https://codeupcrc.github.io/?key=1741)|
|209|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODQ2Nzk3MQ==](https://codeupcrc.github.io/?key=2055)|
|210|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2ODQ5MTY4Nw==](https://codeupcrc.github.io/?key=2202)|
|211|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI2Njk3NQ==](https://codeupcrc.github.io/?key=2241)|
|212|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjU3MzIyMQ==](https://codeupcrc.github.io/?key=2140)|
|213|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4ODUzMjE0MQ==](https://codeupcrc.github.io/?key=325)|
|214|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODA4ODUyMQ==](https://codeupcrc.github.io/?key=536)|
|215|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MzMwNzc3OQ==](https://codeupcrc.github.io/?key=1087)|
|216|Unnecessary Code|Remove duplicated code or processing|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NDc4NTMwOA==](https://codeupcrc.github.io/?key=1683)|
|217|Unnecessary Code|Remove imported type from fully qualified names|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDUzMTYzOA==](https://codeupcrc.github.io/?key=1943)|
|218|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQ1NzYxMQ==](https://codeupcrc.github.io/?key=20)|
|219|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4OTA5OTE0MA==](https://codeupcrc.github.io/?key=36)|
|220|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDQyNjYwNg==](https://codeupcrc.github.io/?key=64)|
|221|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzOTcyMjQ2Ng==](https://codeupcrc.github.io/?key=128)|
|222|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjUyMjkzNA==](https://codeupcrc.github.io/?key=780)|
|223|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDcwMA==](https://codeupcrc.github.io/?key=816)|
|224|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzc3MjkzOA==](https://codeupcrc.github.io/?key=821)|
|225|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODIzNjE3Nw==](https://codeupcrc.github.io/?key=1044)|
|226|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODY2NjcxOA==](https://codeupcrc.github.io/?key=1770)|
|227|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcxNjEzMA==](https://codeupcrc.github.io/?key=1838)|
|228|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDUyNjg1Nw==](https://codeupcrc.github.io/?key=2074)|
|229|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDg3NjA2OQ==](https://codeupcrc.github.io/?key=2105)|
|230|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODMyMTk3MQ==](https://codeupcrc.github.io/?key=2238)|
|231|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjUyMjU1NQ==](https://codeupcrc.github.io/?key=2251)|
|232|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjcwMTg1OA==](https://codeupcrc.github.io/?key=958)|
|233|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTU0OTg0OA==](https://codeupcrc.github.io/?key=1083)|
|234|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDk5MDE4Mg==](https://codeupcrc.github.io/?key=1218)|
|235|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTkwNDcxOQ==](https://codeupcrc.github.io/?key=2275)|
|236|Unnecessary Code|Remove null constants|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzMyNjg4NQ==](https://codeupcrc.github.io/?key=949)|
|237|Unnecessary Code|Remove this|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjcwODAyNw==](https://codeupcrc.github.io/?key=1871)|
|238|Unnecessary Code|Remove type parameter for inferrable type|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODU2NTU2NA==](https://codeupcrc.github.io/?key=236)|
|239|Wrong, missing, or inadequate string expression or literal|Add a message to an exception|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MzY5NTgzNw==](https://codeupcrc.github.io/?key=1345)|
|240|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTgxNTEzMQ==](https://codeupcrc.github.io/?key=1038)|
|241|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2MzE2MzEzNA==](https://codeupcrc.github.io/?key=2318)|
|242|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAzMzk3NA==](https://codeupcrc.github.io/?key=39)|
|243|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDYyOQ==](https://codeupcrc.github.io/?key=817)|
|244|Wrong, missing, or inadequate string expression or literal|Change magic value to adhere to project standards|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0MTE2OA==](https://codeupcrc.github.io/?key=1418)|
|245|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzkwMzU0OA==](https://codeupcrc.github.io/?key=60)|
|246|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg1NzQ5MA==](https://codeupcrc.github.io/?key=407)|
|247|Wrong, missing, or inadequate string expression or literal|Extend a string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNTY4MTc3NQ==](https://codeupcrc.github.io/?key=2350)|
|248|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MTYyOTEwMg==](https://codeupcrc.github.io/?key=2317)|
|249|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTk0MjAyOA==](https://codeupcrc.github.io/?key=2365)|
|250|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NzAzOTQ1NA==](https://codeupcrc.github.io/?key=319)|
|251|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODk2NzYwNw==](https://codeupcrc.github.io/?key=976)|
|252|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjcxODY0NA==](https://codeupcrc.github.io/?key=1149)|
|253|Wrong, missing, or inadequate string expression or literal|Fix an incorrect string literal|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Nzk2MjM4MA==](https://codeupcrc.github.io/?key=1604)|
|254|Wrong, missing, or inadequate string expression or literal|Fix an incorrect value|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDE5MDcxOQ==](https://codeupcrc.github.io/?key=1246)|
|255|Wrong, missing, or inadequate string expression or literal|Fix an incorrect value|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjQ1NjQzMA==](https://codeupcrc.github.io/?key=1642)|
|256|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDY2NTQ4Nw==](https://codeupcrc.github.io/?key=786)|
|257|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNzc4NzkwNA==](https://codeupcrc.github.io/?key=2287)|
|258|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzY4NzY1MA==](https://codeupcrc.github.io/?key=509)|
|259|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODU1MDk0NA==](https://codeupcrc.github.io/?key=1072)|
|260|Wrong, missing, or inadequate string expression or literal|Replace the use of the format method with string concatenation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzM1MDM5MQ==](https://codeupcrc.github.io/?key=2212)|
|261|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMjI0OTg5MA==](https://codeupcrc.github.io/?key=670)|
|262|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjQxMTI4Ng==](https://codeupcrc.github.io/?key=40)|
|263|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjY5ODE5OQ==](https://codeupcrc.github.io/?key=115)|
|264|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzMwNTQxNw==](https://codeupcrc.github.io/?key=340)|
|265|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU0MzMwNg==](https://codeupcrc.github.io/?key=486)|
|266|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODkyNzAxOA==](https://codeupcrc.github.io/?key=1759)|
|267|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjQzODUwNQ==](https://codeupcrc.github.io/?key=1935)|
|268|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTEyNTQzOQ==](https://codeupcrc.github.io/?key=2038)|
|269|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2NzgyNTQ3OA==](https://codeupcrc.github.io/?key=2107)|
|270|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTQxOTAwNA==](https://codeupcrc.github.io/?key=482)|
|271|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzI5MTM0Mg==](https://codeupcrc.github.io/?key=1577)|
|272|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY0NTUyMg==](https://codeupcrc.github.io/?key=352)|
|273|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjgyMjIyMA==](https://codeupcrc.github.io/?key=1349)|
|274|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzY0NjA3MA==](https://codeupcrc.github.io/?key=1668)|
|275|Complex, long, or inadequate logic|Extract method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDQ0MTY1Mw==](https://codeupcrc.github.io/?key=1413)|
|276|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAyMjI2Nw==](https://codeupcrc.github.io/?key=123)|
|277|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNTExMDU3Ng==](https://codeupcrc.github.io/?key=2053)|
|278|Complex, long, or inadequate logic|Replace call to static method by instance method call|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzUxNTI4NQ==](https://codeupcrc.github.io/?key=543)|
|279|Complex, long, or inadequate logic|Replace indirect expression in parameter by direct value|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzY5NTYwOQ==](https://codeupcrc.github.io/?key=83)|
|280|Complex, long, or inadequate logic|Replace method calling chain by existing API|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDU4NzQ3OQ==](https://codeupcrc.github.io/?key=1936)|
|281|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ3NzA2NQ==](https://codeupcrc.github.io/?key=1878)|
|282|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTAyNTE5OA==](https://codeupcrc.github.io/?key=350)|
|283|Inadequate logging and monitoring|Change log settings|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzAwODQzMA==](https://codeupcrc.github.io/?key=272)|
|284|Inadequate logging and monitoring|Change log settings|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDA1ODgzMg==](https://codeupcrc.github.io/?key=1751)|
|285|Inadequate logging and monitoring|Remove log|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MzcyNjQzOA==](https://codeupcrc.github.io/?key=691)|
|286|Inadequate logging and monitoring|Remove log|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzkwNjc1MQ==](https://codeupcrc.github.io/?key=2337)|
|287|Incomplete or inadequate code documentation|Add code comment to explain an expression|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTk0NzE5Mw==](https://codeupcrc.github.io/?key=824)|
|288|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTg3NzU1Ng==](https://codeupcrc.github.io/?key=2244)|
|289|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njg1MjAwMA==](https://codeupcrc.github.io/?key=2263)|
|290|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTg3OTMyOA==](https://codeupcrc.github.io/?key=1471)|
|291|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain internal implementation details of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MTc1MDgwMg==](https://codeupcrc.github.io/?key=1118)|
|292|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTIxMzgyNg==](https://codeupcrc.github.io/?key=427)|
|293|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODY1MDc3Nw==](https://codeupcrc.github.io/?key=2127)|
|294|Incomplete or inadequate code documentation|Add text to existing Javadoc to improve explanation about code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTgxNDkyNA==](https://codeupcrc.github.io/?key=570)|
|295|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjQ1NTAzMA==](https://codeupcrc.github.io/?key=321)|
|296|Incomplete or inadequate code documentation|Change text in existing Javadoc to fix the name of a code element to which it refers|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTQ3NDA5MQ==](https://codeupcrc.github.io/?key=1565)|
|297|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjA3NjU4NA==](https://codeupcrc.github.io/?key=151)|
|298|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODM5MDA5MQ==](https://codeupcrc.github.io/?key=428)|
|299|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzQ2NjE3Mg==](https://codeupcrc.github.io/?key=429)|
|300|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQxOTAxNw==](https://codeupcrc.github.io/?key=1115)|
|301|Incomplete or inadequate code documentation|Remove a useless code comment|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzkxNzU5Nw==](https://codeupcrc.github.io/?key=1829)|
|302|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjcxODAyNg==](https://codeupcrc.github.io/?key=280)|
|303|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzIxNDg0Mg==](https://codeupcrc.github.io/?key=1443)|
|304|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNjk3OTU1NQ==](https://codeupcrc.github.io/?key=307)|
|305|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODc5ODU0OA==](https://codeupcrc.github.io/?key=1575)|
|306|Inconsistent or disrupted formatting|Add parentheses to compound logical expressions|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMDU2MDg3Ng==](https://codeupcrc.github.io/?key=1453)|
|307|Inconsistent or disrupted formatting|Change order of boolean expression operands to make null the second one|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTkyNjA5Nw==](https://codeupcrc.github.io/?key=2152)|
|308|Inconsistent or disrupted formatting|Move methods to be in call ordering|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0NDYzMg==](https://codeupcrc.github.io/?key=1860)|
|309|Unnecessary Code|Remove duplicated code or processing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzA5NDI5MA==](https://codeupcrc.github.io/?key=1108)|
|310|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTcxNTAzNg==](https://codeupcrc.github.io/?key=2073)|
|311|Wrong, missing, or inadequate string expression or literal|Add a message to an exception|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2Mzg0ODgzNw==](https://codeupcrc.github.io/?key=1803)|
|312|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzYwMDQ0MQ==](https://codeupcrc.github.io/?key=1187)|
|313|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjg2ODg4Ng==](https://codeupcrc.github.io/?key=542)|
|314|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMjM0OTI5Mw==](https://codeupcrc.github.io/?key=2068)|

### Patch reverted in the codebase history
| # | Understandability Smell | Improvement | Answer | ID (Link) |
|---|-------------------------|-------------|--------|-----------|
|1|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTg3OTMyOA==](https://codeupcrc.github.io/?key=1471)|
|2|Unnecessary Code|Remove non-referred constant, import, class, method, or variable|*Yes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTcxNTAzNg==](https://codeupcrc.github.io/?key=2073)|
|3|Bad identifier|Change the style of an identifier to be camelCase, capitalized, or lowercase|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMjI0OTg5MA==](https://codeupcrc.github.io/?key=670)|
|4|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjQxMTI4Ng==](https://codeupcrc.github.io/?key=40)|
|5|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjY5ODE5OQ==](https://codeupcrc.github.io/?key=115)|
|6|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzMwNTQxNw==](https://codeupcrc.github.io/?key=340)|
|7|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU0MzMwNg==](https://codeupcrc.github.io/?key=486)|
|8|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODkyNzAxOA==](https://codeupcrc.github.io/?key=1759)|
|9|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjQzODUwNQ==](https://codeupcrc.github.io/?key=1935)|
|10|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTEyNTQzOQ==](https://codeupcrc.github.io/?key=2038)|
|11|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2NzgyNTQ3OA==](https://codeupcrc.github.io/?key=2107)|
|12|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTQxOTAwNA==](https://codeupcrc.github.io/?key=482)|
|13|Bad identifier|Modify an identifier to express the meaning or type of an element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzI5MTM0Mg==](https://codeupcrc.github.io/?key=1577)|
|14|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY0NTUyMg==](https://codeupcrc.github.io/?key=352)|
|15|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjgyMjIyMA==](https://codeupcrc.github.io/?key=1349)|
|16|Bad identifier|Modify an identifier to fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzY0NjA3MA==](https://codeupcrc.github.io/?key=1668)|
|17|Complex, long, or inadequate logic|Extract method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDQ0MTY1Mw==](https://codeupcrc.github.io/?key=1413)|
|18|Complex, long, or inadequate logic|Replace an expression by an alternative expression|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAyMjI2Nw==](https://codeupcrc.github.io/?key=123)|
|19|Complex, long, or inadequate logic|Replace anonymous inner class or method calling chain by lambda|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNTExMDU3Ng==](https://codeupcrc.github.io/?key=2053)|
|20|Complex, long, or inadequate logic|Replace call to static method by instance method call|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzUxNTI4NQ==](https://codeupcrc.github.io/?key=543)|
|21|Complex, long, or inadequate logic|Replace indirect expression in parameter by direct value|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzY5NTYwOQ==](https://codeupcrc.github.io/?key=83)|
|22|Complex, long, or inadequate logic|Replace method calling chain by existing API|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDU4NzQ3OQ==](https://codeupcrc.github.io/?key=1936)|
|23|Complex, long, or inadequate logic|Rewrite the code to avoid semantic duplicate method call|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ3NzA2NQ==](https://codeupcrc.github.io/?key=1878)|
|24|Complex, long, or inadequate logic|Use a different type to be consistent with other parts of the code|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTAyNTE5OA==](https://codeupcrc.github.io/?key=350)|
|25|Inadequate logging and monitoring|Change log settings|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzAwODQzMA==](https://codeupcrc.github.io/?key=272)|
|26|Inadequate logging and monitoring|Change log settings|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDA1ODgzMg==](https://codeupcrc.github.io/?key=1751)|
|27|Inadequate logging and monitoring|Remove log|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MzcyNjQzOA==](https://codeupcrc.github.io/?key=691)|
|28|Inadequate logging and monitoring|Remove log|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzkwNjc1MQ==](https://codeupcrc.github.io/?key=2337)|
|29|Incomplete or inadequate code documentation|Add code comment to explain an expression|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTk0NzE5Mw==](https://codeupcrc.github.io/?key=824)|
|30|Incomplete or inadequate code documentation|Add new Javadoc block to describe the functionality of a code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTg3NzU1Ng==](https://codeupcrc.github.io/?key=2244)|
|31|Incomplete or inadequate code documentation|Add or remove annotation related to documentation|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njg1MjAwMA==](https://codeupcrc.github.io/?key=2263)|
|32|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain internal implementation details of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MTc1MDgwMg==](https://codeupcrc.github.io/?key=1118)|
|33|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTIxMzgyNg==](https://codeupcrc.github.io/?key=427)|
|34|Incomplete or inadequate code documentation|Add text to existing Javadoc to explain the functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODY1MDc3Nw==](https://codeupcrc.github.io/?key=2127)|
|35|Incomplete or inadequate code documentation|Add text to existing Javadoc to improve explanation about code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTgxNDkyNA==](https://codeupcrc.github.io/?key=570)|
|36|Incomplete or inadequate code documentation|Change code comment to better explain the associated code element|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjQ1NTAzMA==](https://codeupcrc.github.io/?key=321)|
|37|Incomplete or inadequate code documentation|Change text in existing Javadoc to fix the name of a code element to which it refers|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTQ3NDA5MQ==](https://codeupcrc.github.io/?key=1565)|
|38|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve explanation about functionality of a method|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjA3NjU4NA==](https://codeupcrc.github.io/?key=151)|
|39|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODM5MDA5MQ==](https://codeupcrc.github.io/?key=428)|
|40|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzQ2NjE3Mg==](https://codeupcrc.github.io/?key=429)|
|41|Incomplete or inadequate code documentation|Change text in existing Javadoc to improve grammar or fix a typo|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQxOTAxNw==](https://codeupcrc.github.io/?key=1115)|
|42|Incomplete or inadequate code documentation|Remove a useless code comment|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzkxNzU5Nw==](https://codeupcrc.github.io/?key=1829)|
|43|Inconsistent or disrupted formatting|Add or remove horizontal spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjcxODAyNg==](https://codeupcrc.github.io/?key=280)|
|44|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzIxNDg0Mg==](https://codeupcrc.github.io/?key=1443)|
|45|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNjk3OTU1NQ==](https://codeupcrc.github.io/?key=307)|
|46|Inconsistent or disrupted formatting|Add or remove vertical spacing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODc5ODU0OA==](https://codeupcrc.github.io/?key=1575)|
|47|Inconsistent or disrupted formatting|Add parentheses to compound logical expressions|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMDU2MDg3Ng==](https://codeupcrc.github.io/?key=1453)|
|48|Inconsistent or disrupted formatting|Change order of boolean expression operands to make null the second one|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTkyNjA5Nw==](https://codeupcrc.github.io/?key=2152)|
|49|Inconsistent or disrupted formatting|Move methods to be in call ordering|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0NDYzMg==](https://codeupcrc.github.io/?key=1860)|
|50|Unnecessary Code|Remove duplicated code or processing|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzA5NDI5MA==](https://codeupcrc.github.io/?key=1108)|
|51|Wrong, missing, or inadequate string expression or literal|Add a message to an exception|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2Mzg0ODgzNw==](https://codeupcrc.github.io/?key=1803)|
|52|Wrong, missing, or inadequate string expression or literal|Change literal to adhere to project standards|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzYwMDQ0MQ==](https://codeupcrc.github.io/?key=1187)|
|53|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjg2ODg4Ng==](https://codeupcrc.github.io/?key=542)|
|54|Wrong, missing, or inadequate string expression or literal|Replace a string literal by a different meaning or a synonymous|*No*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMjM0OTI5Mw==](https://codeupcrc.github.io/?key=2068)|