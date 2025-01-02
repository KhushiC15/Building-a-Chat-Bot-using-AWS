# Building-a-Chat-Bot-using-AWS
Explore various service such as Amazon Lex, Lambda, etc. while creating a chat bot named "Banker Bot": a chat bot that helps customers check their balance and make transfers.

- Part 1 (WelcomeIntent, FallbackIntent), focuses on:
  > Defining a basic intent.
  > Creating lists of utterances.
  > Handling failures i.e. FallbackIntent.
  > Defining a MessageGroup to provide a semi-random response.
  > Building and testing my bot using text and speech.

- Part 2 (CheckBalance), focuses on:
  > Defining a custom slot type.
  > Associating custom and built-in slots to my intent.
  > Parsing slot values from the initial utterance.

- Part 3 (Lambda function), focuses on:
  > Seting up a Lambda function
  > Integrating the Lambda function with my chatbot's alias.
  > Using code hooks to perform the final fulfilment step of the intent.

- Part 4 (FollowupCheckBalance), focuses on:
  > Seting up context carryover of slot values from one intent to the next.

- Part 5 focuses on:
  > Configuring multiple slots with a shared slot type.
  > Implementing a confirmation prompt.
  > Using the conversation flow and visual builder.
  > Automating bot deployment with CloudFormation.

