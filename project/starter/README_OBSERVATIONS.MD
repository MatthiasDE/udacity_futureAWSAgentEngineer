# Observations for "Project: Customer Support Chatbot with Amazon Bedrock AgentCore"

The change requests from the review team of the first submission have been implemented.

* Redirect the Uncovered Question was now implemented with improving the system prompt in `system_prompt.txt` assuring a polite Out-of-Scope Hand-Off
* If FAQ lacks an answer, the transcript hands-off to human support with clear information about the phone number as requested what was also done with improving the system prompt in `system_prompt.txt`.
* The completed evaluation screenshot was already added before and is saved with the following file name `screenshot_amazonBedrockEvaluations_completedJob`. In this screenshot you can see that the job `support-chatbot-eval-run-1` was completed successful. Anyhow I added another file that shows the correctness of the run on the job's detail page. The successful results of the evaluation run can be seen also in the file `screenshot_amazonBedrockEvaluations_completedJobDetails.png`
* Due to the positive evaluation score of 1.0 there is seen no need to further improve the system prompt for this specific use case. A second evaluation run with additional test case in `harness-tests.json` in the background also resultet in a strong rating of 1.0.