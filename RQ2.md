## RQ2 - What are the main issues pertaining to code understandability in code review?

**Table of contents**
- [Incomplete or inadequate code documentation](#incomplete-or-inadequate-code-documentation)
- [Bad identifier](#bad-identifier)
- [Complex, long, or inadequate logic](#complex-long-or-inadequate-logic)
- [Unnecessary Code](#unnecessary-code)
- [Inconsistent or disrupted formatting](#inconsistent-or-disrupted-formatting)
- [Wrong, missing, or inadequate string expression or literal](#wrong-missing-or-inadequate-string-expression-or-literal)
- [Inadequate logging and monitoring](#inadequate-logging-and-monitoring)
- [Missing constant usage](#missing-constant-usage)

### Incomplete or inadequate code documentation
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Annotation|*@PublicAPI instead of @beta*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MzI2MzE1Ng==](https://codeupcrc.github.io/?key=839)|
|2|Annotation|*Add javadoc description*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4Mjc0Mjg4NQ==](https://codeupcrc.github.io/?key=1463)|
|3|Annotation|*We might need some clarity here. The javadoc gives the impression that INSTANCE_ID_TOKEN can be fetched from FIS SDK, which is incorrect. We can expli...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Mzc0MDIxNQ==](https://codeupcrc.github.io/?key=920)|
|4|Annotation|*No need to deprecate this constructor anymore, because authenticationCallback works with MSAL now.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTg3OTMyOA==](https://codeupcrc.github.io/?key=1471)|
|5|Attribute|*So this is the name of an environment variable whose value is a comma-separated list of environment variable names? That's far from obvious. At the ve...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTQ5MTk4Mg==](https://codeupcrc.github.io/?key=1762)|
|6|Attribute|*Specifies beans that won't be scanned in the GlobalTransactionScanner*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzMzMzI0MQ==](https://codeupcrc.github.io/?key=2008)|
|7|Attribute|*why ReplyWorkflowContext?  Looks like a comment would be helpful here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDcwMDUwNg==](https://codeupcrc.github.io/?key=2180)|
|8|Call|*does it allows to make log4j plugin management work with relocation ? If yes, it might be a good idea to add a comment to make it a bit more explicit.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTk0NzE5Mw==](https://codeupcrc.github.io/?key=824)|
|9|Call|*maybe a comment here to explain that getInstance() loads all the static providers*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODk3Mzk5NA==](https://codeupcrc.github.io/?key=1164)|
|10|Call|*I'm wondering why this method call always passes ignoreAttemptFailure=true (sorry, a bit too difficult for me 😅.) Could I ask you the followings?  Ad...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTY5MTcwMA==](https://codeupcrc.github.io/?key=2209)|
|11|Call|*typo - and*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDYyNzM4Mw==](https://codeupcrc.github.io/?key=926)|
|12|Class|*Change to 2020 in all new files*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTYxOTkzNg==](https://codeupcrc.github.io/?key=372)|
|13|Class|*Update date*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTYzOTA4OA==](https://codeupcrc.github.io/?key=803)|
|14|Class|*anc' -> 'and'*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NjY0OTk0NA==](https://codeupcrc.github.io/?key=1031)|
|15|Class|*Add @Immutable as other classes. Also our repo policy is to add a Javadoc for a public class. Can be a short one.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQyNjY1Mw==](https://codeupcrc.github.io/?key=1051)|
|16|Class|*Suggested change                                                                                                 * Copyright 202 Red Hat, Inc. and/or ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNzI1NTMwMA==](https://codeupcrc.github.io/?key=1298)|
|17|Class|*Can you make the link <a href ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTc1NDM3NA==](https://codeupcrc.github.io/?key=1732)|
|18|Class|*Same for the other lines                         Suggested change                                                                                     ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzQ1MA==](https://codeupcrc.github.io/?key=1818)|
|19|Class|*Do we need to update this right now and does it need to go from 2017 - 2020 as a combination of the original SdlSession and SdlSession2*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2Mzc3Mzg4MQ==](https://codeupcrc.github.io/?key=2049)|
|20|Class|*This is a new class that uses the canonicalization of the LSRV part of a locale identifier to verify correctness of the algorithm and test data.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTg3NzU1Ng==](https://codeupcrc.github.io/?key=2244)|
|21|Class|*Should add some minimal documentation here*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzEyOTQxOA==](https://codeupcrc.github.io/?key=500)|
|22|Class|*Can you be more specific about the usage of this class? It should mention log4j, Vertx context, Vertx vertx local data.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDQ5NjIxNA==](https://codeupcrc.github.io/?key=930)|
|23|Class|*It needs more detailed explanation but we can wait for next PR.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2MTE0MzgwMw==](https://codeupcrc.github.io/?key=935)|
|24|Class|*Suggested change                                                                                                 * along with MekHQ.  If not, see <htt...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMzE5MzEzNA==](https://codeupcrc.github.io/?key=1449)|
|25|Class|*SecurityTagsProperties*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTQ3NDA5MQ==](https://codeupcrc.github.io/?key=1565)|
|26|Class|*Suggested change                                                                                                 * LivingFallEvent is fired when an En...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxNzA0Mw==](https://codeupcrc.github.io/?key=1821)|
|27|Conditional|*What is the significance of depth 4? Could add to a comment.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDYzNTEyMg==](https://codeupcrc.github.io/?key=61)|
|28|Conditional|*Suggested change                                                                                                        // Get org-name               ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTEzMDk4OQ==](https://codeupcrc.github.io/?key=469)|
|29|Conditional|*nit: TODO*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTYxNjQ0MQ==](https://codeupcrc.github.io/?key=1032)|
|30|Conditional|*Think you may have intended to have the below comment here too, or only here since it's the first occurrence*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMzc5OTkzOQ==](https://codeupcrc.github.io/?key=1724)|
|31|Conditional|*Suggested change                                                                                                  // TODO: Some vanilla registry types...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njc0Mjc0Nw==](https://codeupcrc.github.io/?key=1815)|
|32|Conditional|*Minor point: this comment seems to be floating in space a bit*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzkxNzU5Nw==](https://codeupcrc.github.io/?key=1829)|
|33|Conditional|*IMHO, a more idiomatic way of specifying this is JavaScript would be this.activeColumn*|| "".|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODkxNjAzNA==](https://codeupcrc.github.io/?key=1970)|
|34|Conditional|*add a comment that explain the skipped char on windows system*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDUxOTk1Nw==](https://codeupcrc.github.io/?key=2119)|
|35|Conditional|*Please add a comment*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzEzMzA5NQ==](https://codeupcrc.github.io/?key=1655)|
|36|Interface|*why not "insert, delete or update" (alternatively, "insertion, deletion or updating")*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDk0NzIyMg==](https://codeupcrc.github.io/?key=1119)|
|37|Literal|*What does the comment mean? Or can it be removed?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjQ1NTAzMA==](https://codeupcrc.github.io/?key=321)|
|38|Loop|*Questionable comment*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTM5MDIzMA==](https://codeupcrc.github.io/?key=2273)|
|39|Method|*What should be defined by a setter?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjkzMDYyMA==](https://codeupcrc.github.io/?key=27)|
|40|Method|*usually added at the very top of a javadoc*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNjI3Njg5Ng==](https://codeupcrc.github.io/?key=138)|
|41|Method|*What is the task here? Please explain. This is for all javadocs. There is no harm in writing more lines :P*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjA3NjU4NA==](https://codeupcrc.github.io/?key=151)|
|42|Method|*Please add comments to explain the reason.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjcxMTIwOQ==](https://codeupcrc.github.io/?key=155)|
|43|Method|*Nit: Typo shake -> sake*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjU3Mzk0MA==](https://codeupcrc.github.io/?key=182)|
|44|Method|*@see should be placed after @return*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NzczMTM4Mg==](https://codeupcrc.github.io/?key=196)|
|45|Method|*Failure callback. @param failReason Exception caused a failure.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3ODExNDM5Nw==](https://codeupcrc.github.io/?key=197)|
|46|Method|*Anything here?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDkzMjg4Mw==](https://codeupcrc.github.io/?key=380)|
|47|Method|*NIT: add a comment. requirementMap is a groupId->requirement map*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjE3NDUxNg==](https://codeupcrc.github.io/?key=373)|
|48|Method|*This comment seems off, service suppressions is what's throwing me. Also, if "service" is supposed to be namespace, the precedence listed is incorrect...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNDIyMzEzNQ==](https://codeupcrc.github.io/?key=389)|
|49|Method|*assumed**|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODkxNDk2Nw==](https://codeupcrc.github.io/?key=388)|
|50|Method|*Suggested change                                                                                                     * @return The response object    ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODM5MDA5MQ==](https://codeupcrc.github.io/?key=428)|
|51|Method|*missing return*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTIxMzgyNg==](https://codeupcrc.github.io/?key=427)|
|52|Method|*Suggested change                                                                                                     * close the content.             ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzQ2NjE3Mg==](https://codeupcrc.github.io/?key=429)|
|53|Method|*It can sometimes be helpful to note given/when/then is the tests to enhance readability for other developers.         //given         String root = Pa...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDA5NDgzOA==](https://codeupcrc.github.io/?key=678)|
|54|Method|*Suggested change                                                                                                   * @throws java.lang.ClassCastExcept...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjI2MzA1NQ==](https://codeupcrc.github.io/?key=727)|
|55|Method|*No need to have a PR here. You should have a reference of what it was replaced by as a link to code. Take a look at other deprecate examples in the pr...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NDI2MTMzMg==](https://codeupcrc.github.io/?key=755)|
|56|Method|*One request, can you add a method doc similar to the one above method?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTMyNzEwNQ==](https://codeupcrc.github.io/?key=756)|
|57|Method|*the last known gateway id ?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MTY1OTkxNg==](https://codeupcrc.github.io/?key=766)|
|58|Method|*@link on this and the next line please*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMzA0MzU2Mg==](https://codeupcrc.github.io/?key=802)|
|59|Method|*no need to use quote marks here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NzUzMzkwNA==](https://codeupcrc.github.io/?key=1040)|
|60|Method|*As far as I can see this concept only exists in Spring and not in CDI (even if quarkus impl should be lazy by default). Why do you need it? Minor note...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODc0NzM2MQ==](https://codeupcrc.github.io/?key=1338)|
|61|Method|*HTTP methods - {@link #GET}, {@link #HEAD}, {@link #PUT} and {@link #DELETE}. ?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzQ5Mjc4Nw==](https://codeupcrc.github.io/?key=1380)|
|62|Method|*complete the java doc*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDY4MTA1OQ==](https://codeupcrc.github.io/?key=1385)|
|63|Method|*This is not necessarily AKV user principal ID. Please align the docs with ODBC connection property documentation.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU3NjE4Mg==](https://codeupcrc.github.io/?key=1476)|
|64|Method|*Add a short javadoc to this method including that it configure a Sandbox feature.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ5NTU0OA==](https://codeupcrc.github.io/?key=1720)|
|65|Method|*This javadoc will be the title of the section so maybe just "User interface" or "UI configuration" would be better.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMyMDY1OA==](https://codeupcrc.github.io/?key=1894)|
|66|Method|*Suggested change                                                                                                     * @param callback callback used w...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjY2OTI3Mw==](https://codeupcrc.github.io/?key=1934)|
|67|Method|*is node in this line referring to the input node or to nodes generally? The given text isn't clear.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTEzNDc5Ng==](https://codeupcrc.github.io/?key=2235)|
|68|Method|*Suggested change                                                                                                     */                               ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjAyMzYwNw==](https://codeupcrc.github.io/?key=2254)|
|69|Method|*This should be deprecated*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Njg1MjAwMA==](https://codeupcrc.github.io/?key=2263)|
|70|Method|*This should also say 'or {@code null} if the operation has no such parameter'.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc4ODQwMg==](https://codeupcrc.github.io/?key=2307)|
|71|Method|*Cancels a task. Cancellation means a task is obsolete from a business perspective an does not need to be completed anymore.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODY1MDc3Nw==](https://codeupcrc.github.io/?key=2127)|
|72|Method|*This seems to be done*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDkyMzYzMA==](https://codeupcrc.github.io/?key=2387)|
|73|Method|*{@link JobModel}*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzAwOTA3OA==](https://codeupcrc.github.io/?key=294)|
|74|Method|*This is why property descriptions must start with a verb in the singular tense.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0MjA5MQ==](https://codeupcrc.github.io/?key=558)|
|75|Method|*Would you mind applying this suggestion?                         Suggested change                                                                     ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTgxNDkyNA==](https://codeupcrc.github.io/?key=570)|
|76|Method|*Suggested change                                                                                                   * @param blockEntity  entity the bl...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzY1MjYxNw==](https://codeupcrc.github.io/?key=876)|
|77|Method|*Lets add why we do this? (something like: this is required because we trust the server to tell us which campaigns can be re-impressed to honor frequen...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI1MDc1OA==](https://codeupcrc.github.io/?key=922)|
|78|Method|*Should we should also add @Deprecated here?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTQzNjg1OA==](https://codeupcrc.github.io/?key=1113)|
|79|Method|*Minor: which is available...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQxOTAxNw==](https://codeupcrc.github.io/?key=1115)|
|80|Method|*we should say it is maximum number of reconnection be more clear here - for example if it is set to 2 then it tries to connect 3 times (i.e. reconnect...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MTc1MDgwMg==](https://codeupcrc.github.io/?key=1118)|
|81|Method|*We should probably rephrase this to talk about the "alias"*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjExODQwMg==](https://codeupcrc.github.io/?key=1183)|
|82|Method|*Be good to do as JavaDoc.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNTc1NTQ4Mg==](https://codeupcrc.github.io/?key=1625)|
|83|Method|*Add a comment indicating whether start/end are inclusive or exclusive*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzA2OTAxNA==](https://codeupcrc.github.io/?key=2020)|
|84|Variable|*I think a "why" comment would be more useful here. Explain why the commonSuperType logic above can fail and which cases are enabled here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NjMxNDU3Nw==](https://codeupcrc.github.io/?key=637)|
|85|Variable|*We usually don't include annotations like this. It should be okay for the warning to be there.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY5MjIzNQ==](https://codeupcrc.github.io/?key=2021)|
|86|Variable|*clean up comments*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNTM5MDUyMw==](https://codeupcrc.github.io/?key=1093)|

### Bad identifier
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Attribute|*Rename the field as well?  Since it's now an executor and not a handler...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzMwNTQxNw==](https://codeupcrc.github.io/?key=340)|
|2|Attribute|*Rename this field to active.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDc0NDA1Ng==](https://codeupcrc.github.io/?key=453)|
|3|Attribute|*Rename this variable*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NDM0MTc2Nw==](https://codeupcrc.github.io/?key=779)|
|4|Attribute|*These variables are getting confused. Some of them are property names and some of them are default property values. They should be visually separate i...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxODAxOTIxOQ==](https://codeupcrc.github.io/?key=902)|
|5|Attribute|*Nit: Can we use singular names in config -- i.e. SLOW_BROKERS_XXX -> SLOW_BROKER_XXX?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjUzNjgyNA==](https://codeupcrc.github.io/?key=1402)|
|6|Attribute|*Can we rename this to numberOfExercisesInExam*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0NzQ5Mw==](https://codeupcrc.github.io/?key=1419)|
|7|Attribute|*Let's rename it to DEFAULT_TIMESTAMP_FUNCTION*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDE3OTY4Ng==](https://codeupcrc.github.io/?key=1945)|
|8|Attribute|*could you please rename it?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2NzgyNTQ3OA==](https://codeupcrc.github.io/?key=2107)|
|9|Attribute|*Rename these to startWarehouseIdForShard and totalWarehousesAcrossShards*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDc5MDIzNw==](https://codeupcrc.github.io/?key=2376)|
|10|Attribute|*Suggested change                                                                                                    private boolean inAppDisplayhold =...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTAzOA==](https://codeupcrc.github.io/?key=1203)|
|11|Attribute|*ONE_WEEK_IN_SECONDS should be something more descriptive to what is it used. One week should be a comment instead.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMzI5MTM0Mg==](https://codeupcrc.github.io/?key=1577)|
|12|Attribute|*Suggested change                                                                                                  private static final String JAEGER_I...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NjI0NTEzNw==](https://codeupcrc.github.io/?key=1584)|
|13|Attribute|*In all other cases you have commandNormalizer. Please make the same here as well*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNDA0OTQxNA==](https://codeupcrc.github.io/?key=1586)|
|14|Attribute|*sourceParameter*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMTkzNjAzOQ==](https://codeupcrc.github.io/?key=2001)|
|15|Class|*It's better to rename JacksonSerialize to JsonSerializer*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjY5ODE5OQ==](https://codeupcrc.github.io/?key=115)|
|16|Class|*It might make sense to call this StatelessProvenanceRepository or perhaps RingBufferProvenanceRepository just to avoid confusion with the existing Vol...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDQ1OTkzOQ==](https://codeupcrc.github.io/?key=244)|
|17|Class|*As referred this name is confusing to me. Perhaps with a more detailed description I can help you find a better name.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODc2NjU1MA==](https://codeupcrc.github.io/?key=710)|
|18|Class|*Why not just "ImageButton"?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTIyNzA3OQ==](https://codeupcrc.github.io/?key=1233)|
|19|Class|*remove the Db and name attributes from the annotation*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDgyMTc3NA==](https://codeupcrc.github.io/?key=1772)|
|20|Class|*AppParameter is misleading, not just about the target app. InputVector would be closer to what it is.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2NTk2OTgzMQ==](https://codeupcrc.github.io/?key=2382)|
|21|Class|*Should this be ContainerLocation or something? HostLocality sounds wrong because the host doesn't have a location, it is the location.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NTAwNTcyNw==](https://codeupcrc.github.io/?key=293)|
|22|Class|*rename to BftConfigOptions*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1MTcwMDU1NA==](https://codeupcrc.github.io/?key=1152)|
|23|Class|*ValidationErrorType? + javadoc on class level*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDkzOTA1Mg==](https://codeupcrc.github.io/?key=1883)|
|24|Class|*@kostyaBoss I would keep the name as ShowConstantTbt on line 212.  Changing the name of the class is out of scope of the PR.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTMwNTAwMA==](https://codeupcrc.github.io/?key=2046)|
|25|Method|*Maybe parseOrigin is better?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTMyMTU1Nw==](https://codeupcrc.github.io/?key=19)|
|26|Method|*nit: The name of the function doesn't suggest to me the type. Maybe createClaimsJwt()?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTE1NTA1NQ==](https://codeupcrc.github.io/?key=31)|
|27|Method|*I'd prefer to just keep the (unfriendly) current names as well - as sort of an ecosystem compatibility thing. The names attached to the data are a bit...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjQxMTI4Ng==](https://codeupcrc.github.io/?key=40)|
|28|Method|*Minor: "generateViolation" read better.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzYyMjczMA==](https://codeupcrc.github.io/?key=211)|
|29|Method|*Do I read this right, that we're doing the exact same thing twice?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDY0NTk0MQ==](https://codeupcrc.github.io/?key=222)|
|30|Method|*@olenagerasimova guess there is typo and this method's name is supposed to be config, not configs, isn't it?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTY0NTUyMg==](https://codeupcrc.github.io/?key=352)|
|31|Method|*The method names on these are inconsistent: getOutputTokenMember -> getOutputTokenPath getItemsMember -> getItemsMemberPath Since the original names a...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNDUxOTQxOQ==](https://codeupcrc.github.io/?key=387)|
|32|Method|*This is not the parentLockContext() but the lockContext itself, please rename. Also, please rename the class to LockRequest.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODkzNzM4MA==](https://codeupcrc.github.io/?key=458)|
|33|Method|*I'd prefer we changed this as it reads strangely to me. So instead of "isLastCharWasEscapeChar" we could do "wasLastCharEscapeChar".*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMDU0MzMwNg==](https://codeupcrc.github.io/?key=486)|
|34|Method|*Tiny nit: "LSN" -> "Lsn" (this isn't done consistently across the code base yet, but it's the casing we want to converge on eventually for abbreviatio...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMjI0OTg5MA==](https://codeupcrc.github.io/?key=670)|
|35|Method|*Please drop the test prefix in the name.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MzkxMTg3Ng==](https://codeupcrc.github.io/?key=754)|
|36|Method|*nit: your method seems to be returning a date range, so getDateRange might be a better name.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzE3NDQxMQ==](https://codeupcrc.github.io/?key=1042)|
|37|Method|*typo                         Suggested change                                                                                                    publi...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTI5ODgxNg==](https://codeupcrc.github.io/?key=1308)|
|38|Method|*Suggested change                                                                                                    void testPrequalificationDMNExplan...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MjQ3MTkzMQ==](https://codeupcrc.github.io/?key=1328)|
|39|Method|*What do you mean with demo?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzM4MjM5Mw==](https://codeupcrc.github.io/?key=1336)|
|40|Method|*Suggested change                                                                                                    private boolean allChildsExported(...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjgyMjIyMA==](https://codeupcrc.github.io/?key=1349)|
|41|Method|*Should this test be named ..._jobNotCreated rather than ..._reportValidationError?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4ODkyNzAxOA==](https://codeupcrc.github.io/?key=1759)|
|42|Method|*Should probably be getDefaultCodecRegistry*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDgwNjcxNw==](https://codeupcrc.github.io/?key=1930)|
|43|Method|*maxListSize*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzY1MDIwNA==](https://codeupcrc.github.io/?key=1991)|
|44|Method|*The signature should likely be PropertySheetTask<T extends AbstractNode>. See the comment on computePropertyValue for more details.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MDUyMTgxMQ==](https://codeupcrc.github.io/?key=2033)|
|45|Method|*getSlots() seem rather un-intuitive. Think that name could be improved.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTEyNTQzOQ==](https://codeupcrc.github.io/?key=2038)|
|46|Method|*Suggested change                                                                                                        Builder setArgument(@Nullable ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODkyNzY1Nw==](https://codeupcrc.github.io/?key=2080)|
|47|Method|*Our code style is to name things in camel case where only the first letter is capitalized, including acronyms, so write this as getJsonPointer*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDYyNzA3OTUwNg==](https://codeupcrc.github.io/?key=2211)|
|48|Method|*Could you please add some comment or rename the load and set methods so we better know what they are doing. For future maintenance.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjY1MjgwMg==](https://codeupcrc.github.io/?key=2393)|
|49|Method|*nit:                         Suggested change                                                                                                  private...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzQzNDA5NQ==](https://codeupcrc.github.io/?key=257)|
|50|Method|*Why does findByEmailAddressAndProviderConfigId(...) return a List? Shouldn't it be an optional? I think what we want is a findByEmailAddressInAndProvi...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDY0NjgxOA==](https://codeupcrc.github.io/?key=478)|
|51|Method|*I don't like that this is called "collectCodeLocationNames" when it really "creates" code location names.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNTQxOTAwNA==](https://codeupcrc.github.io/?key=482)|
|52|Method|*Maybe we can call these arguments replyDelay, I think it'd be clearer*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODcxMjE0MA==](https://codeupcrc.github.io/?key=508)|
|53|Method|*This method actually returns the Requirements class, not the annotation, so better call it getArtifactRequirements()*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODIxMzQ4Mw==](https://codeupcrc.github.io/?key=535)|
|54|Method|*Taking a value out of a JWT token without validating the token can cause a security issue because anyone can spoof it. Such a value must be handled wi...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODYyODIyMg==](https://codeupcrc.github.io/?key=931)|
|55|Method|*How about getElementsSorted() --> getSortedElements()?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MDk2MjU2OQ==](https://codeupcrc.github.io/?key=1002)|
|56|Method|*Nit:                         Suggested change                                                                                                    void ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMDgzNjQ1OA==](https://codeupcrc.github.io/?key=1107)|
|57|Method|*Typo in MissMatch*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzY0NjA3MA==](https://codeupcrc.github.io/?key=1668)|
|58|Method|*create/generate not get, maybe?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MjYzOTc2MQ==](https://codeupcrc.github.io/?key=1717)|
|59|Parameter|*Also: this variable should be named identifierType.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MDc1ODE5Mg==](https://codeupcrc.github.io/?key=571)|
|60|Parameter|*Suggested change                                                                                                    public static Practitioner createP...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTgyNzc0OQ==](https://codeupcrc.github.io/?key=579)|
|61|Parameter|*is there a chance that infoCache could be confused by localInterfacesOnly since the key is always this class? I didn't go thorough all use cases, but ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3ODMzNjYwMA==](https://codeupcrc.github.io/?key=724)|
|62|Parameter|*Maybe we shouldn't call this streamsQuery?                         Suggested change                                                                   ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwODA3MjA2OA==](https://codeupcrc.github.io/?key=1066)|
|63|Parameter|*let's use requiredAttributes for consistency. We are following that in IDP, APP etc.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NjM0ODkyNA==](https://codeupcrc.github.io/?key=2346)|
|64|Parameter|*Unify the variable names txCancel and jpaTransactionCancel.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTYyMTI5Ng==](https://codeupcrc.github.io/?key=2359)|
|65|Parameter|*authToken instead of token*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MzEyOTQ2OA==](https://codeupcrc.github.io/?key=1205)|
|66|Parameter|*Suggested change                                                                                                    public void setInAppDisplayhold(bo...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjU5OTg0Mw==](https://codeupcrc.github.io/?key=1204)|
|67|Parameter|*Shouldn't we convert gName to tsName? I.e. removeBinding(gName + "_traversal");*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMTY2NjI0MA==](https://codeupcrc.github.io/?key=1215)|
|68|Variable|*nit, customizedStateName -> customizedStateType or type?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTQyODA4OA==](https://codeupcrc.github.io/?key=166)|
|69|Variable|*Did you mean interaction or intersection?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0OTUyMzc2Nw==](https://codeupcrc.github.io/?key=180)|
|70|Variable|*Lets rename to dataPacket ?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzMzMzc2OA==](https://codeupcrc.github.io/?key=189)|
|71|Variable|*Typo in variable name*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTIzNDU4NQ==](https://codeupcrc.github.io/?key=811)|
|72|Variable|*Suggested change                                                                                                    TransferManagerConfiguration tmCon...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MjI4NDY2Mg==](https://codeupcrc.github.io/?key=860)|
|73|Variable|*typo                         Suggested change                                                                                                         ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3NzMyNzc4MA==](https://codeupcrc.github.io/?key=1314)|
|74|Variable|*Nit: detectMetricAnomalies -> detectedMetricAnomalies?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTY3OTIyMg==](https://codeupcrc.github.io/?key=1401)|
|75|Variable|*I know it was like this but since you are touching it, could you please rename to timeStr to follow Java standard?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDI0MzE0Mg==](https://codeupcrc.github.io/?key=1753)|
|76|Variable|*please rename module_uuid to assembly_uuid*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NjQzODUwNQ==](https://codeupcrc.github.io/?key=1935)|
|77|Variable|*Suggested change                                                                                                        byte[] opReturnOutput = BtcTra...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NTgzNTI5Ng==](https://codeupcrc.github.io/?key=1963)|
|78|Variable|*Should be studentRows here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjc5MTE2NQ==](https://codeupcrc.github.io/?key=2133)|

### Complex, long, or inadequate logic
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Attribute|*Suggested change                                                                                                    private boolean cancelled;        ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTA5Njk5NQ==](https://codeupcrc.github.io/?key=854)|
|2|Attribute|*nit: JoinerConfig.JOIN_KEYS*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzUxNTI4NQ==](https://codeupcrc.github.io/?key=543)|
|3|Attribute|*Import TileSourceManager*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMTYyNDA2OA==](https://codeupcrc.github.io/?key=1779)|
|4|Call|*With a lambda, this would be slightly shorter:       Threads.createThread("Halt Thread", () -> {         sleepUninterruptibly(100, TimeUnit.MILLISECON...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjU4NDEyNw==](https://codeupcrc.github.io/?key=58)|
|5|Call|*Should use prefixAndClause.getValue().includesColumn(filteringColumn) — it's more semantically intentful and also the logic is slightly different.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAyMjI2Nw==](https://codeupcrc.github.io/?key=123)|
|6|Call|*@olenagerasimova as you are using java standard library in this method, I'd suggest to use HttpURLConnection.HTTP_OK instead of parsing RsStatus.OK va...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTAyNTE5OA==](https://codeupcrc.github.io/?key=350)|
|7|Call|*hasTrait?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTQ3MzE0OA==](https://codeupcrc.github.io/?key=391)|
|8|Call|*nit: same, can be replaced by returning Collections.singleton().*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTAwOTA3OA==](https://codeupcrc.github.io/?key=416)|
|9|Call|*On a second thought, this might be already added via options(). Could you please check?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODk2OTI0MA==](https://codeupcrc.github.io/?key=457)|
|10|Call|*I like the statement / query / {collector}? / execution API flow.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzMwNTQzOA==](https://codeupcrc.github.io/?key=737)|
|11|Call|*These urls can be converted into an array of strings and then we can use a loop for setting them here.. better than hardcoding*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzg0MDU0MQ==](https://codeupcrc.github.io/?key=777)|
|12|Call|*No need for Lists.newArrayList*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTk5MzQyNA==](https://codeupcrc.github.io/?key=812)|
|13|Call|*Collections.emptyList would do.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTQxMTA5Mw==](https://codeupcrc.github.io/?key=808)|
|14|Call|*I am sure we have a JSON string encoder somewhere in the code base Not sure off hand but I recall we do.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5ODM1ODU1Mw==](https://codeupcrc.github.io/?key=1060)|
|15|Call|*As the argument is optional, we should use the features of Optional and not have another "empty" case of an empty string. You can either just not spec...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MjE3MjQyOA==](https://codeupcrc.github.io/?key=1101)|
|16|Call|*It could may be possible to use peek method to putt all the actions perform upon the userData to update into one place and then collect it in a list i...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjEwMDY2OA==](https://codeupcrc.github.io/?key=1737)|
|17|Call|*Would be more pretty to wrtie PsseVersion.isSupported(rev) or maybe a PsseVersion.checkVersion(rev) method*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg1MTIxMg==](https://codeupcrc.github.io/?key=1846)|
|18|Call|*Please use AssertJ*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2OTc1NzcxOA==](https://codeupcrc.github.io/?key=1944)|
|19|Call|*update.getUpdatedObject().getValuesForAttribute(AttributeType.MNT_BY); is a bit cleaner?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNDUzOTIxMA==](https://codeupcrc.github.io/?key=1957)|
|20|Call|*You could probably just make this reverse() + limit + forEach(buildBox)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjM1OTE1MQ==](https://codeupcrc.github.io/?key=1984)|
|21|Call|*Looks like my suggestion was not that elegant. For me it will be more readable to use lambda.                         Suggested change                ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNTExMDU3Ng==](https://codeupcrc.github.io/?key=2053)|
|22|Call|*Pls use the assertThatThrownBy-pattern to be consistent with other tests*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NzY3NjMwNw==](https://codeupcrc.github.io/?key=2130)|
|23|Call|*Suggested change                                                                                                    assertThat(selectedAndClaimedTasks...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjY1Mjc3OA==](https://codeupcrc.github.io/?key=2123)|
|24|Call|*nit: static import assertFalse() like you've done for assertNotNull()*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTY0OTUxMg==](https://codeupcrc.github.io/?key=266)|
|25|Call|*Suggested change                                                                                                      CompletableFuture<String> errorF...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1Mjc0NjI1Mg==](https://codeupcrc.github.io/?key=899)|
|26|Call|*nit: Recommend always using assert4j assertThat() for cleaner approach, consistency with other code and ability to chain*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTc1Mjk1OA==](https://codeupcrc.github.io/?key=1110)|
|27|Call|*assertEquals(Boolean.TRUE, ...)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4NTI3MTU5Mg==](https://codeupcrc.github.io/?key=1562)|
|28|Call|*suggest to use exprValue.string() in future to get rid of the static getStringValue method.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3Njc2NDg4NA==](https://codeupcrc.github.io/?key=1616)|
|29|Call|*You could use  verifyZeroInteractions instead.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MDY4NjQyNQ==](https://codeupcrc.github.io/?key=1700)|
|30|Call|*Thoughts about using https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/format/DateTimeFormatter.html#ISO_LOCAL_DATE for date form...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDc5MDkxNw==](https://codeupcrc.github.io/?key=2225)|
|31|Class|*Why Boolean and not boolean?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyOTk2OTI5NQ==](https://codeupcrc.github.io/?key=1201)|
|32|Class|*Please return an unmodifiable List here (or even an Iterable<Issue>). We rarely use arrays in the codebase. You can write Collections.unmodifiableList...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcyMjU3Nw==](https://codeupcrc.github.io/?key=1839)|
|33|Conditional|*Plz try not to have duplicate code, it will be difficult to maintain*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjIzMDU3MQ==](https://codeupcrc.github.io/?key=14)|
|34|Conditional|*This would be easier to understand if you do: if (this.hidden != null) {     this.retrievable = !this.hidden; } Shouldn't the retrievable logic be don...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwOTAwMjcwOQ==](https://codeupcrc.github.io/?key=435)|
|35|Conditional|*Just use !secondaryIndexes.isEmpty()?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzI4NTI4MA==](https://codeupcrc.github.io/?key=626)|
|36|Conditional|*Even though tryNext() returns an enum, can we add a default case with a fallthough comment along the lines of "this should never happen"? Or even an e...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzY4NTg0MQ==](https://codeupcrc.github.io/?key=1029)|
|37|Conditional|*you could flip this comparison, as that makes it way easier to read*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMDA2OTUyNA==](https://codeupcrc.github.io/?key=1370)|
|38|Conditional|*Suggested change                                                                                                        }                             ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNjkwOTcyMQ==](https://codeupcrc.github.io/?key=1442)|
|39|Conditional|*why can we short circuit for non-structs?  is it because there will never be any subfields?  I think the shortcircuiting is more confusing.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MTEzODQ4NA==](https://codeupcrc.github.io/?key=1872)|
|40|Conditional|*This block reads quite confusing now. consider flipping it.. if (results.getJobComplete() && results.getSchema() != null) { schema = Schema.fromPb(res...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyMjQwNzQ3Mw==](https://codeupcrc.github.io/?key=1012)|
|41|Conditional|*@alex-fu Since we are diverging the DECISION block by so many lines of code. We can define a separate switch case for DO_WHILE task. And move common c...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MDcxOTM2MQ==](https://codeupcrc.github.io/?key=1523)|
|42|Import|*OMG, not sure how this slipped through but we don't want * imports, please get your IDE to expand these.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzOTI0MTU2Mg==](https://codeupcrc.github.io/?key=858)|
|43|Import|*please have a look at the intellij formatter inside the root folder: we don't use * imports.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNzA5NzQxMg==](https://codeupcrc.github.io/?key=1059)|
|44|Import|*Undo wildcard import.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MjQzMzM5Mg==](https://codeupcrc.github.io/?key=2203)|
|45|Loop|*I would replace the iterator with a normal for over categoriesList for (final String categoryId : categoriesList)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3OTQ2NTcyMQ==](https://codeupcrc.github.io/?key=702)|
|46|Method|*We can change this to Collections.singletonList(0L);*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMjE1ODU2OA==](https://codeupcrc.github.io/?key=4)|
|47|Method|*I would encapsulate this logic in a separate method on a separate class to make it more readeable an d shorter ie translation from request to QueueCon...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMzkxNTY5Ng==](https://codeupcrc.github.io/?key=66)|
|48|Method|*setup() for authentication and configure() for authorization - could we simply unify these and go with setup() for both? As long as the two methods ha...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjY1NTk3Mw==](https://codeupcrc.github.io/?key=332)|
|49|Method|*split it in 3 testcases?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODgyNjU5Mg==](https://codeupcrc.github.io/?key=1176)|
|50|Method|*Perhaps we may use Apache Commons Lang abbreviate method, adding 3 dots at the end, to indicate that it's trimmed. Notice that this method would throw...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNjUyOTIxOA==](https://codeupcrc.github.io/?key=1315)|
|51|Method|*Maybe you can refactor this logic into a different method, it makes this method quite large and I guess it might be useful elsewhere.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NDQ0MTY1Mw==](https://codeupcrc.github.io/?key=1413)|
|52|Method|*Suggested change                                                                                                            String text = ((String)val...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTY4OTc1Mg==](https://codeupcrc.github.io/?key=1690)|
|53|Method|*I think a better way to write this method is:         protected void addResponseCookie(ExternalContext externalContext) {             final boolean se...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTQ3NzA2NQ==](https://codeupcrc.github.io/?key=1878)|
|54|Method|*we need either to make it consistent with the above constructor or open a separate PR to swap the parameters of the above constructor, wdyt? (the late...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODkxMjk1Nw==](https://codeupcrc.github.io/?key=1923)|
|55|Method|*Reduce this whole method to:  public Command revertUnsavedChangesBeforeExitCommand(final Command onCompleted)    {       return () -> handleUnsavedCha...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDYwODY0Nw==](https://codeupcrc.github.io/?key=1971)|
|56|Method|*2 questions:  How are the changes in this file related to the title "NPE during producting flow dump"? What benefits do these changes bring? IMHO, 2 i...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTQxMDQ4MQ==](https://codeupcrc.github.io/?key=2171)|
|57|Method|*To make the controller method a bit explicit, I would recommend to create a controllerUtil class and move the private methods there.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0OTg5NDkzMQ==](https://codeupcrc.github.io/?key=945)|
|58|Method|*This check is made a few times. Might be easier to check it in the very beginning (line 111), and do not repeat it later.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzE2MDYwOQ==](https://codeupcrc.github.io/?key=1530)|
|59|Operation|*We could use symTag to check for BPackageSymbol and BAnnotationSymbol*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNzM5MTQzNA==](https://codeupcrc.github.io/?key=463)|
|60|Operation|*instead of this conditional you coul use the traversal api. It would yield cleaner, more concise code.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDU4NzQ3OQ==](https://codeupcrc.github.io/?key=1936)|
|61|Operation|*you can use StringUtils.isBlank in place of these two checks (the apache commons lang3 version)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5MTA1Mw==](https://codeupcrc.github.io/?key=2240)|
|62|Operation|*Why a LinkedList is used here and another constructor stores a passed ArrayList? If different implementations really behave better, it should be docum...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDU1OTM1Ng==](https://codeupcrc.github.io/?key=1089)|
|63|Package|*To be in package org.lfenergy.operatorfabric.cards.publication.configuration.kafka to be consistent with other configuration classes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNzE1MTM3NQ==](https://codeupcrc.github.io/?key=1735)|
|64|Parameter|*I think you can replace autodetectParser with parser == null and eliminate the three-args constructor.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMjMwNjQ0MQ==](https://codeupcrc.github.io/?key=85)|
|65|Try-Catch|*Looks like it could be simplified: Reader reader = new BufferedReader(new InputStreamReader(minioObject, StandardCharsets.UTF_8));*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzY5NTYwOQ==](https://codeupcrc.github.io/?key=83)|
|66|Try-Catch|*afaik you can just do SpliceUnitTest.rowContainsQuery(levels, query, "rows=10","MergeJoin"); which does the try/createStatement for you*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODM0Mjc2OA==](https://codeupcrc.github.io/?key=2064)|
|67|Variable|*I think you could get  consumerModel directly from invocation attributes*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzIxMzU4Nw==](https://codeupcrc.github.io/?key=125)|
|68|Variable|*I think you can use existing generatedAnnotation field*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU2MjE4MzMzNg==](https://codeupcrc.github.io/?key=1337)|
|69|Variable|*we can compute  started + timeoutSeconds * 1000 here (in both methods)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNDgwNjE4OA==](https://codeupcrc.github.io/?key=1517)|
|70|Variable|*extract this getHookPhasesForCurrentStepPhase(hookToBeExecuted, hookPhasesForCurrentStepPhase) to a variable*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzE1Mjc2OQ==](https://codeupcrc.github.io/?key=564)|

### Unnecessary Code
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Annotation|*path="" is redundant*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjM4NjgxMg==](https://codeupcrc.github.io/?key=2400)|
|2|Attribute|*unused constant.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDcwMA==](https://codeupcrc.github.io/?key=816)|
|3|Attribute|*Please remove KITS, CRASHLYTICS, ANSWER as well*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMzc3MjkzOA==](https://codeupcrc.github.io/?key=821)|
|4|Attribute|*Here and in other places, I'd remove the static nulls and just put null. I think the code is pretty clear without the need for static nulls*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzMyNjg4NQ==](https://codeupcrc.github.io/?key=949)|
|5|Attribute|*These are not used and already stored in TestDataHelper/TestConstants so please remove*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODIzNjE3Nw==](https://codeupcrc.github.io/?key=1044)|
|6|Attribute|*The value of AES_SECRET is not used. It looks like it should be removed.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODY2NjcxOA==](https://codeupcrc.github.io/?key=1770)|
|7|Attribute|*This descriptor is unused, right?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNTcxNjEzMA==](https://codeupcrc.github.io/?key=1838)|
|8|Attribute|*Remove this?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MTg1NjU4OA==](https://codeupcrc.github.io/?key=2065)|
|9|Attribute|*Suggested change                                                                                                            if (this.toString("UTF-8")...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDcyOTc0Mw==](https://codeupcrc.github.io/?key=1653)|
|10|Call|*might as well remove rather than commenting out*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTM4ODE4MQ==](https://codeupcrc.github.io/?key=41)|
|11|Call|*Can probably be safely removed*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTg1MTU4OA==](https://codeupcrc.github.io/?key=688)|
|12|Call|*The test about hasSemantic() is useful for checks that extends IssuableSubscriptionVisitor. But because AbstractMethodDetection already do this test, ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxODQ2Nzk3MQ==](https://codeupcrc.github.io/?key=2055)|
|13|Call|*You shouldn't need this throw, the fact that the repoObjLoader returns a work should trigger the expected exception*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwMTI2Njk3NQ==](https://codeupcrc.github.io/?key=2241)|
|14|Call|*inferrable type informations                         Suggested change                                                                                 ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyODU2NTU2NA==](https://codeupcrc.github.io/?key=236)|
|15|Call|*This sort can be removed since it's already sorted above.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NzA5NDI5MA==](https://codeupcrc.github.io/?key=1108)|
|16|Call|*reindexing datasets may not actually be needed here. (based on the instances where it is called ManageTemplates, Guestbook, etc.)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1OTAxNDY5OQ==](https://codeupcrc.github.io/?key=1192)|
|17|Call|*Boolean.valueOf() not necessary here:                        Suggested change                                                                         ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUyNjg5ODUwMA==](https://codeupcrc.github.io/?key=1992)|
|18|Class|*remove qualified name*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NDUzMTYzOA==](https://codeupcrc.github.io/?key=1943)|
|19|Class|*Then remove it.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTcxNTAzNg==](https://codeupcrc.github.io/?key=2073)|
|20|Conditional|*Code duplication*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2ODQ5MTY4Nw==](https://codeupcrc.github.io/?key=2202)|
|21|Conditional|*BTW, what is the point of this condition? Unconditional StringUtils.appendTwoDigits(output, hours) should produce the same result, or I'm missing some...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MzMwNzc3OQ==](https://codeupcrc.github.io/?key=1087)|
|22|Conditional|*Minor nitpick. The null check here isn't necessary since the copyFrom() methods already handle the null case. Can update this in the other usages as w...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NDc4NTMwOA==](https://codeupcrc.github.io/?key=1683)|
|23|Import|*Don't add new commented out imports, but clean up*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzOTcyMjQ2Ng==](https://codeupcrc.github.io/?key=128)|
|24|Import|*Unused import*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDUyNjg1Nw==](https://codeupcrc.github.io/?key=2074)|
|25|Import|*Were these imports missing in this class? I don't see you add their usage, maybe they are redundant?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MDg3NjA2OQ==](https://codeupcrc.github.io/?key=2105)|
|26|Import|*This import should be removed.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTU0OTg0OA==](https://codeupcrc.github.io/?key=1083)|
|27|Import|*Unused import*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzMDk5MDE4Mg==](https://codeupcrc.github.io/?key=1218)|
|28|Literal|*remove this line. Typo + duplicate from the one below*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NjU3MzIyMQ==](https://codeupcrc.github.io/?key=2140)|
|29|Loop|*this shouldn't come back, it's being set lower now (line 127)*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2ODA4ODUyMQ==](https://codeupcrc.github.io/?key=536)|
|30|Method|*Useless?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQ1NzYxMQ==](https://codeupcrc.github.io/?key=20)|
|31|Method|*Do we have to get rid of this?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4OTA5OTE0MA==](https://codeupcrc.github.io/?key=36)|
|32|Method|*Should these be removed?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2NTQxMDgzMw==](https://codeupcrc.github.io/?key=444)|
|33|Method|*The return is implicit for a void method, so you can just have an empty method body between the curly braces.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NDY2MDQ2OA==](https://codeupcrc.github.io/?key=644)|
|34|Method|*This doesn't seem to be used.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4NjQ3OTY1Ng==](https://codeupcrc.github.io/?key=771)|
|35|Method|*Shall we remove the method also?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NjUyMjkzNA==](https://codeupcrc.github.io/?key=780)|
|36|Method|*This and the previous method seem identical except for the input/output directories. Can we de-duplicate the logic?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4Njg2ODg2MA==](https://codeupcrc.github.io/?key=1411)|
|37|Method|*Is this necessary given that super.getDependencies does the same?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1OTk4NTYwMw==](https://codeupcrc.github.io/?key=1741)|
|38|Method|*this method isn't used*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODMyMTk3MQ==](https://codeupcrc.github.io/?key=2238)|
|39|Method|*unused method in class that is also a duplicate of the one in the server package.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjUyMjU1NQ==](https://codeupcrc.github.io/?key=2251)|
|40|Method|*it can be inlined*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDA4MDM2MQ==](https://codeupcrc.github.io/?key=2281)|
|41|Method|*What's the different between this and testConstraintSolverForceBacktrack*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4ODUzMjE0MQ==](https://codeupcrc.github.io/?key=325)|
|42|Method|*removal candidate?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDcyNzY0Mw==](https://codeupcrc.github.io/?key=1162)|
|43|Method|*You are using GSON anyway and could use it for serialization here which should be much simpler – basically just: String jsonString = gson.toJson(form)...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDI5MzM5MQ==](https://codeupcrc.github.io/?key=1601)|
|44|Method|*remove unused code?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MTY0NTEyNw==](https://codeupcrc.github.io/?key=1623)|
|45|Method|*Two questions:  Is this second constructor even needed, if it isn't even the recommended way to use this? If it is, it should not be copying all of th...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODc3ODk0Mw==](https://codeupcrc.github.io/?key=1662)|
|46|Method|*Maybe declared the constructor at the top. Also I am not sure if we need a constructor here. Any problem with just private BeanPropertyFactorySwitch b...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTkwNDcxOQ==](https://codeupcrc.github.io/?key=2275)|
|47|Object|*nit: this. is redundant here*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU1NjcwODAyNw==](https://codeupcrc.github.io/?key=1871)|
|48|Try-Catch|*commented code*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0Njc4NDIyOQ==](https://codeupcrc.github.io/?key=1074)|
|49|Variable|*Seems like this might be unused now that the loop it was in before is gone?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNDQyNjYwNg==](https://codeupcrc.github.io/?key=64)|
|50|Variable|*This seem not used later.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NjcwMTg1OA==](https://codeupcrc.github.io/?key=958)|
|51|Variable|*Could be better to have the full clientSession.newRequest()...execute() to avoid having loadCsv variable.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MDU2NDEyNQ==](https://codeupcrc.github.io/?key=1561)|

### Inconsistent or disrupted formatting
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Attribute|*Suggested change                                                                                                  private ReferenceQueue              ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwODc4OTY5Nw==](https://codeupcrc.github.io/?key=840)|
|2|Call|*I missed the whitespaces :(                         Suggested change                                                                                  ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5MDM2NzQyOA==](https://codeupcrc.github.io/?key=1754)|
|3|Call|*Space after comman.. Fix similar places.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU3NjgzMTU0Nw==](https://codeupcrc.github.io/?key=2348)|
|4|Call|*Suggested change                                                                                                    protected static List<String> fooF...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjcxODAyNg==](https://codeupcrc.github.io/?key=280)|
|5|Call|*Suggested change                                                                                                        BaArmor a = (BaArmor)campaign....*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMzA0ODY4NQ==](https://codeupcrc.github.io/?key=1450)|
|6|Class|*remove extra empty line*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4OTYwMjg1OA==](https://codeupcrc.github.io/?key=762)|
|7|Class|*nit: add new line.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDYxOTM0MA==](https://codeupcrc.github.io/?key=1694)|
|8|Class|*No separation between doc comments and the class.                         Suggested change*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzMxMzM0MA==](https://codeupcrc.github.io/?key=1817)|
|9|Class|*Method is not on his method call ordering position*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNDE0NDYzMg==](https://codeupcrc.github.io/?key=1860)|
|10|Class|*spacing is a bit off here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MDQyNjQ4Mg==](https://codeupcrc.github.io/?key=2204)|
|11|Class|*Suggested change                                                                                                    }                                 ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNDEyNTI2MQ==](https://codeupcrc.github.io/?key=493)|
|12|Class|*The indent is changed to 2 spaces in this file and some other files?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODIyMDEzNw==](https://codeupcrc.github.io/?key=1617)|
|13|Conditional|*Revert this change please.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNjEyMTMxMg==](https://codeupcrc.github.io/?key=1994)|
|14|Conditional|*This was an unnecessary line change.                         Suggested change                                                                         ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5OTM4NzU4Ng==](https://codeupcrc.github.io/?key=2026)|
|15|Conditional|*if (*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyOTQ3OTQwNA==](https://codeupcrc.github.io/?key=2264)|
|16|Conditional|*Suggested change                                                                                                        if (null == title) {          ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTkyNjA5Nw==](https://codeupcrc.github.io/?key=2152)|
|17|Conditional|*This could use the InfoItemsPage#emptyPage method, and to improve readability, add brackets and place the return in the next line.                    ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NTgwMjc1OQ==](https://codeupcrc.github.io/?key=2148)|
|18|Conditional|*IF statement should be on it's own line*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzI1NTc2NA==](https://codeupcrc.github.io/?key=2024)|
|19|Literal|*Suggested change                                                                                                                entry.getKey() + "')")...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3Mzc1MjYxMg==](https://codeupcrc.github.io/?key=1596)|
|20|Loop|*braces*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5Mjg1NjgyNw==](https://codeupcrc.github.io/?key=1078)|
|21|Loop|*Suggested change*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NTI1NTI1NQ==](https://codeupcrc.github.io/?key=1660)|
|22|Method|*indention seems off*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzQ5ODc3Mg==](https://codeupcrc.github.io/?key=317)|
|23|Method|*Suggested change*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwNzIxNDg0Mg==](https://codeupcrc.github.io/?key=1443)|
|24|Method|*Bracket should be on the next line*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MTc1OTE2Mw==](https://codeupcrc.github.io/?key=1487)|
|25|Method|*inline throws*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzQ5NTAwMg==](https://codeupcrc.github.io/?key=1866)|
|26|Method|*just cosmetic/convention changes (empty lines): FallbackMethod fallbackMethod = FallbackMethod             .create("fallbackMethod", testMethod, new O...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5Mjk4NDI4OQ==](https://codeupcrc.github.io/?key=1942)|
|27|Method|*Remove this newline*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MzAzNjQzNg==](https://codeupcrc.github.io/?key=1985)|
|28|Method|*For all Methods in this class, to be consistent, will you add a space before { to look like:  public void setStabilityControlsStatus(StabilityControls...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1ODMxMjA5OQ==](https://codeupcrc.github.io/?key=2050)|
|29|Method|*Do we need extra lines?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NzMxMzQyMQ==](https://codeupcrc.github.io/?key=2320)|
|30|Method|*format -add method description*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4Njg2MDE4Mw==](https://codeupcrc.github.io/?key=2325)|
|31|Method|*New line indent is 2. Here second line of a long line is 4.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzcyNjI3NQ==](https://codeupcrc.github.io/?key=247)|
|32|Method|*There should be a blank line here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNjk3OTU1NQ==](https://codeupcrc.github.io/?key=307)|
|33|Method|*I hope to god the next Eclipse version fixes this idiotic code formatting bug...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MDM2MTM0MQ==](https://codeupcrc.github.io/?key=490)|
|34|Method|*Indentation*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNDQ5NDcyNg==](https://codeupcrc.github.io/?key=964)|
|35|Method|*Bad formatting.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MjY3MzAzMQ==](https://codeupcrc.github.io/?key=1075)|
|36|Method|*this looks incorrectly indented*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4ODQ0NjIzMA==](https://codeupcrc.github.io/?key=1531)|
|37|Method|*Remove trailing whitespaces.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxOTkxNTA3MQ==](https://codeupcrc.github.io/?key=1538)|
|38|Method|*Remove empty line*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzODc5ODU0OA==](https://codeupcrc.github.io/?key=1575)|
|39|Operation|*more spaces please*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2OTA1MzcyMg==](https://codeupcrc.github.io/?key=683)|
|40|Operation|*A little too many parens here.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTMwMjQ3MA==](https://codeupcrc.github.io/?key=1446)|
|41|Operation|*Suggested change                                                                                                                .filter(u -> u.require...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMDU2MDg3Ng==](https://codeupcrc.github.io/?key=1453)|
|42|Try-Catch|*@pabender @rhwood Do we have a convention for braces in try-catch structures?  I'm used to to t.he previous } catch ().. { form, but if we're going to...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMTg1NjIwMQ==](https://codeupcrc.github.io/?key=1267)|

### Wrong, missing, or inadequate string expression or literal
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Call|*use simple concatenation. format makes it just obscure. Same goes to below places like that:         testRow(rowDecoder, generateRecord(initialSchema,...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMzM1MDM5MQ==](https://codeupcrc.github.io/?key=2212)|
|2|Literal|*I think our convention is like:                         Suggested change                                                                              ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NTAzMzk3NA==](https://codeupcrc.github.io/?key=39)|
|3|Literal|*Some of the deprecated properties have the following in their description.  I think this is nice for the generated documentation.                     ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5NzkwMzU0OA==](https://codeupcrc.github.io/?key=60)|
|4|Literal|*I'd add something to this exception stating that no parameters are expected for an aggregate's annotated methods. Should be careful with the wording t...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg1NzQ5MA==](https://codeupcrc.github.io/?key=407)|
|5|Literal|*In general, avoid this type of pattern where an exception is caught, logged, and then re-thrown. What ends up happening is that the error gets logged ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNjg2ODg4Ng==](https://codeupcrc.github.io/?key=542)|
|6|Literal|*For future, you don't have to say "it is ", the test runner will automatically say something like: "expected: potato" "actual: tomato"*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMTAzNzMyNQ==](https://codeupcrc.github.io/?key=692)|
|7|Literal|*Please change message to "Expected and actual values are not the same."*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDY2NTQ4Nw==](https://codeupcrc.github.io/?key=786)|
|8|Literal|*name should be course_enrollment.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NzIzNDYyOQ==](https://codeupcrc.github.io/?key=817)|
|9|Literal|*could we setBody to something else? I don't really understand what the string here means... maybe something straightforward such as "new body text"?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjM1OTQ3Mg==](https://codeupcrc.github.io/?key=1014)|
|10|Literal|*nit: "Unable" and ..."the generated parser**.** "*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1MTgxNTEzMQ==](https://codeupcrc.github.io/?key=1038)|
|11|Literal|*Suggested change                                                                                                    @Column(name = "END_TEXT")        ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNjM0MTE2OA==](https://codeupcrc.github.io/?key=1418)|
|12|Literal|*Suggested change                                                                                                    public static final Name CORE_GAME...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMjU0MDU5Ng==](https://codeupcrc.github.io/?key=1497)|
|13|Literal|*I think we may want to provide a different message if new duplicates appear vs when problems are fixed, or mention here that it's dangerous to have du...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2Mzg0ODgzNw==](https://codeupcrc.github.io/?key=1803)|
|14|Literal|*not supported sounds a bit better than "unsupported"*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzNzc4NzkwNA==](https://codeupcrc.github.io/?key=2287)|
|15|Literal|*Suggested change                                                                                                                    " will be used for...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3MTYyOTEwMg==](https://codeupcrc.github.io/?key=2317)|
|16|Literal|*Shall we add a colon before the parameters?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2MzE2MzEzNA==](https://codeupcrc.github.io/?key=2318)|
|17|Literal|*I feel it would be better to include what we expected to happen here. "Authentication request was not initiated after logout from sample. Possible log...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyNTY4MTc3NQ==](https://codeupcrc.github.io/?key=2350)|
|18|Literal|*@kokodyn iterable, not iterator :) same with the test name*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MTk0MjAyOA==](https://codeupcrc.github.io/?key=2365)|
|19|Literal|*nit: receive -> received ; And add  the log to indicate the message is ignored will be helpful Also can you show the log after you added remote? Is it...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NzAzOTQ1NA==](https://codeupcrc.github.io/?key=319)|
|20|Literal|*Suggested change                                                                                                          .name("broker_process_startu...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUwMzY4NzY1MA==](https://codeupcrc.github.io/?key=509)|
|21|Literal|*This change isn't much of an improvement, as either could be true. Given that GT doesn't necessarily support the full set of expressions, this distinc...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyODk2NzYwNw==](https://codeupcrc.github.io/?key=976)|
|22|Literal|*Suggested change                                                                                                                        String.format(...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5ODU1MDk0NA==](https://codeupcrc.github.io/?key=1072)|
|23|Literal|*Can't*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ5NjcxODY0NA==](https://codeupcrc.github.io/?key=1149)|
|24|Literal|*For consistency, better use the same error message as Status Bar plugin                         Suggested change                                      ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5MzYwMDQ0MQ==](https://codeupcrc.github.io/?key=1187)|
|25|Literal|*Suggested change                                                                                                    @Symbol("kubectl")                ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDE5MDcxOQ==](https://codeupcrc.github.io/?key=1246)|
|26|Literal|*external might be confusing as in the CI we are actually using localhost. Maybe we can just say "cluster url should be provided for security enabled t...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0Nzk2MjM4MA==](https://codeupcrc.github.io/?key=1604)|
|27|Literal|*How about we change to "Must set at least one profile type" to avoid confusion between empty profile types and wrong profile types which we don't supp...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQwNzkyNjAxMA==](https://codeupcrc.github.io/?key=1608)|
|28|Literal|*Suggested change                                                                                                    @Operation(operationId = "aproveIn...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUzMjQ1NjQzMA==](https://codeupcrc.github.io/?key=1642)|
|29|Literal|*@Name shouldn't have Is .*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ4MzM1MDEyNA==](https://codeupcrc.github.io/?key=2022)|
|30|Literal|*list of tile/block entities with block name as key and range as value*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMjM0OTI5Mw==](https://codeupcrc.github.io/?key=2068)|
|31|Try-Catch|*Maybe an explanation here would be nice?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ3MzY5NTgzNw==](https://codeupcrc.github.io/?key=1345)|

### Inadequate logging and monitoring
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Call|*This can potentially flood the log. Can we extract line 376-405 in existing code into a method and call that here?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQzNzAwODQzMA==](https://codeupcrc.github.io/?key=272)|
|2|Call|*We can remove this soft assert as well as this path will definitely get hit for someone using this functionality,*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MzcyNjQzOA==](https://codeupcrc.github.io/?key=691)|
|3|Call|*You can use Logger.warnAndDebug method instead*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3OTUxNTQyNg==](https://codeupcrc.github.io/?key=704)|
|4|Call|*Please remove the printlns. If they are needed then maybe convert them into log.trace() or debug()*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0MTE0NDIyOA==](https://codeupcrc.github.io/?key=1021)|
|5|Call|*This looks like a candidate for finest, not fine. Also when constructing a message in log levels lower than info, please use lambda: LOGGER.finest(() ...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3NDA1ODgzMg==](https://codeupcrc.github.io/?key=1751)|
|6|Call|*This looks very crude for info level. Is it some left over from debugging?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzM2NDU1Ng==](https://codeupcrc.github.io/?key=2104)|
|7|Call|*In my opinion, we do not need this log. WDYT?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzkwNjc1MQ==](https://codeupcrc.github.io/?key=2337)|
|8|Call|*log instead*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0NTQ5NjkxOQ==](https://codeupcrc.github.io/?key=267)|
|9|Call|*If I'm not mistaken the parameters have changed but the general logic behind this statement has not correct?  I ask because currently in the test envi...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3ODk3MTg4Mw==](https://codeupcrc.github.io/?key=573)|
|10|Call|*Same as above, this is currently logging every second in test.  Can this be changed to debug?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM3ODk3MjM2Mw==](https://codeupcrc.github.io/?key=574)|
|11|Call|*Same. Delete or set to fine.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDY2MjU3NDMyNw==](https://codeupcrc.github.io/?key=1189)|
|12|Literal|*from the request message*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM5OTQ3NjQ5Mw==](https://codeupcrc.github.io/?key=2094)|
|13|Method|*This whole feature is extraordinary error-prone. I'd say a warning must be added here when it is used.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxNTI3MDY3NA==](https://codeupcrc.github.io/?key=1286)|
|14|Method|*Would a log.warn make sense here?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU0MzM0MDI5NA==](https://codeupcrc.github.io/?key=865)|
|15|Method|*should we log this? just to make investigation easier*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQyMDc0NjczNw==](https://codeupcrc.github.io/?key=1135)|
|16|Try-Catch|*This is not a very good exception, let's tell the developer what is wrong in each case and how they could fix it.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjMzMzMxNw==](https://codeupcrc.github.io/?key=919)|
|17|Try-Catch|*I'd opt to re-throw here instead. If someone is calling encrypt I wouldn't expect it to silently fail and return a un-encrypted payload back.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ1NjU1NjQ4OA==](https://codeupcrc.github.io/?key=1678)|
|18|Variable|*isStale is always false*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDU5ODU0MTI5NQ==](https://codeupcrc.github.io/?key=1173)|

### Missing constant usage
| # | Where | Comment | ID (Link) |
|---|-------|---------|-----------|
|1|Literal|*A bit better way is StandardCharsets.UTF_8[.name()].*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NTM4MzA1MA==](https://codeupcrc.github.io/?key=242)|
|2|Literal|*I believe it's better to use the CATEGORY_PREFIX variable from CategoryClient here rather than hard coding the prefix.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxMjkyNzc5Mw==](https://codeupcrc.github.io/?key=590)|
|3|Literal|*The constant here should be shoved into the related (or new) Constants nested class.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM4MjQwMDc2NQ==](https://codeupcrc.github.io/?key=2071)|
|4|Literal|*It would be better to declare this Strings as constants.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQxMzgxNTk3OA==](https://codeupcrc.github.io/?key=2163)|
|5|Literal|*We already have constants for some defaults in this file. I would convert these to constants as well.*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MjUzNDE2Mw==](https://codeupcrc.github.io/?key=2179)|
|6|Literal|*Perhaps it would be worth using more informative variable names here, to emphasize the role they play in the constraint definition. You should also be...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ0NDg2NjYwMQ==](https://codeupcrc.github.io/?key=1687)|
|7|Literal|*Do we have the String op names anywhere? If not we should figure out how to add them to the generated ops so we don't have random string constants. cc...*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDQ2MzYxNzQxNA==](https://codeupcrc.github.io/?key=2187)|
|8|Method|*Just asking, wouldn't this be better as a static constant, instead of a local constant?*|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDUxNjAxNDY2OA==](https://codeupcrc.github.io/?key=1484)|
|9|Parameter|Should we define "MONTHS" and "WEEKS" as constants?|[MDI0OlB1bGxSZXF1ZXN0UmV2aWV3Q29tbWVudDM2NzYyMjcwNg==](https://codeupcrc.github.io/?key=277)|