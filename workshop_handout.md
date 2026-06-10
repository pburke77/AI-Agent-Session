# **Build an AI App in Dify**

## **Greater Cincinnati Community Services Navigator Workshop Handout**

## Overview

In this activity, you will build a simple AI assistant in Dify called **Greater Cincinnati Community Services Navigator**.

The assistant will:

- ask clarifying questions
- use a trusted knowledge source
- recommend relevant community services
- explain why the recommendation fits
- suggest next steps

By the end of the activity, you will have a reusable AI app that can help people find support in the Greater Cincinnati region.

## What You Will Build

You will create a chatbot that helps users identify the right community service based on their situation.

Your chatbot will:

- greet the user
- ask a few follow-up questions
- use a Greater Cincinnati community services guide as its knowledge source
- recommend the best resource
- explain why it fits
- provide next steps

## Step 1: Sign In to Dify

- Open \*\*<https://dify.ai>\*\*
- Create a free account or sign in
- Open your workspace/dashboard

## Step 2: Create the Knowledge Source

Before building the chatbot, upload the document it will use.

- Open the **Knowledge** or **Dataset** section
- Click **Create Knowledge** or **Create Dataset**
- Name the dataset:

**Greater Cincinnati Community Services Guide**

- Upload the provided resource document
- Wait for the file to finish processing
- Leave the default retrieval settings unless instructed otherwise

You will connect this knowledge source to your chatbot in the next steps.

## Step 3: Create a New App

- Click **Create App**
- Choose **Chatbot**
- Enter the app name:

**Greater Cincinnati Community Services Navigator**

- Enter this description:

**Helps users identify relevant community services in the Greater Cincinnati region based on their needs.**

- Click **Create**

## Step 4: Attach the Knowledge Source

- In your chatbot settings, locate the **Knowledge** section
- Attach the dataset named:

**Greater Cincinnati Community Services Guide**

- Confirm that the chatbot can use this dataset when responding

## Step 5: Add the System Instructions

Locate the main instruction or prompt area in your app and paste the text below.

**System Instructions**

_text_

You are the Greater Cincinnati Community Services Navigator.  
<br/>Your role is to help users identify the most appropriate community service or support option in the Greater Cincinnati region based on their situation.  
<br/>Instructions:  
1\. Ask 2 or 3 clarifying questions before making a recommendation unless the user has already provided enough detail.  
2\. Use the knowledge base as your primary source.  
3\. Recommend the best matching service or the top 2 options.  
4\. Explain why each option matches the user's need.  
5\. Provide clear next steps, including what to do first when that information is available.  
6\. If the knowledge base does not contain enough information, clearly say so.  
7\. Keep the tone supportive, concise, and easy to understand.  
8\. If the issue involves immediate danger, advise the user to call 911.  
9\. If the issue involves suicide, severe emotional distress, or a mental health crisis, advise the user to contact 988 or an appropriate crisis resource.  
10\. Do not invent hours, phone numbers, eligibility rules, deadlines, or service details that are not in the knowledge base.  
11\. End by asking whether the user wants a short summary they can save.

## Step 6: Turn On and Edit the Conversation Opener

In Dify, the welcome message is managed through the **Features Enabled** area.

- Look below the chat area for **Features Enabled**
- Click **Manage**
- In the Features panel, turn on **Conversation Opener**
- Click into the Conversation Opener text area to edit it
- Paste this message:

**Conversation Opener**

_text_

Hi - I can help you find community services in the Greater Cincinnati region. Tell me what kind of help you're looking for, and I'll ask a couple of quick questions before recommending a next step.

**Optional:** Leave **Citations and Attributions** turned on so users can see the source of retrieved answers.

## Step 7: Test Your App

Try one or more of the prompts below.

**Test Prompt 1**

_text_

I need help paying my utility bills.

**Test Prompt 2**

_text_

I'm not sure where to start, but I need food assistance.

**Test Prompt 3**

_text_

I'm worried I may lose my housing soon.

**Test Prompt 4**

_text_

I need help finding mental health support.

**Test Prompt 5**

_text_

I need job help and I don't know what programs are available.

**Test Prompt 6**

_text_

I'm overwhelmed and I'm not sure what kind of help I need.

## Step 8: Check the Results

As you test the chatbot, ask yourself:

- Did it ask clarifying questions?
- Did it recommend a relevant service or starting point?
- Did it explain why the recommendation fits?
- Did it give next steps?
- Did it avoid making up information?
- Did it handle urgent or crisis situations appropriately?

## Step 9: Improve the App

Choose **one** improvement from the list below and add it to your system instructions.

**Option A: Use a Structured Response Format**

Add:

_text_

When giving a recommendation, format the answer with these headings:  
\- Best option  
\- Why it fits  
\- Next steps  
\- Another possible option

**Option B: Ask Fewer Questions**

Change:

_text_

Ask 2 or 3 clarifying questions before making a recommendation

to:

_text_

Ask no more than 2 clarifying questions before making a recommendation

**Option C: Add a Summary Mode**

Add:

_text_

If the user asks for a summary, provide a short 3-bullet version they can save or copy.

**Option D: Be More Careful with Uncertainty**

Add:

_text_

If you are unsure between two services, say so and explain the difference.

## Step 10: Test Again

After making an improvement, test your app again with one of the prompts below.

_text_

I need food support and transportation help.

_text_

I may be evicted and I don't know what to do first.

_text_

I need legal help with a housing issue.

_text_

I need help, but I'm not sure if I should call 211 or another service.

## Optional Challenge

If you finish early, customize your app for a more specific audience or service area.

Examples:

- Hamilton County Housing Support Navigator
- Family Services Navigator
- Food and Utility Assistance Navigator
- Northern Kentucky Community Services Guide
- Crisis and Support Resource Navigator

Use the same design pattern:

- ask questions
- use a knowledge source
- recommend the best option
- explain why
- provide next steps

## Reflection Questions

Discuss these questions with a partner or small group.

- What made this more useful than a general chatbot?
- When did the app ask helpful follow-up questions?
- Did the knowledge source improve trust?
- Where did the app still feel limited?
- What would you add next: better knowledge, workflow logic, tools, or human handoff?

## Key Takeaway

This activity shows how an AI app can move beyond a simple one-shot response.

Your app is more useful because it:

- asks clarifying questions
- uses trusted information
- recommends a resource based on context
- explains its reasoning
- supports next steps

This is a practical starting point for building agent-like AI systems.
