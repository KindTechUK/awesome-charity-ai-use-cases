# Awesome charity AI use cases [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A carefully curated list of case studies on how the charity sector is utilising emerging AI technology like GenAI

We noticed that the charity sector is not utilising the power of GenAI to its full potential and in the private sector there are a lot of lists and examples that people can easily find.

Here we aim to curate a list of projects that can serve as inspiration for other charities and as cautious technolgoists, we would also highlight the risks and ethical considerations involved in such projects. Whenever possible, we ask the project owners and builders to clarify different aspects of the project.

## Contents

* [Data analysis](#data-analysis)
* [Data dashboarding](#data-dashboarding)
* [Chatbots](#chatbots)
* [Web applications](#web-applications)

***

## Data analysis

*Examples of how charities are using AI to analyse data.*

* [38D quantitative and qualitative analysis of the NHS survey](https://home.38degrees.org.uk/2025/01/29/nhs-10-year-plan-consultation-the-publics-view/)
  * **Challenge**: Analyzing 40,000 NHS service satisfaction surveys with free-text responses
  * **Solution**: Used Claude and ChatGPT for thematic analysis of qualitative data
  * **Key Learnings**: 
    - Models excel at high-level theme identification but need guidance for nuanced coding
    - Personal data protection is critical when sharing prompts with third-party AI
    - Success requires iteration, output review, and clear guidance (e.g., predefined topic categories)
  * **Bonus** 
    - Scorll to the end of the report and all the prompts they used are in the appendix.
    - [Tests of large and small language models on common evaluation tasks](https://merltech.org/event-recap-tests-of-large-and-small-language-models-on-common-evaluation-tasks/?utm_source=merltech&utm_medium=email&utm_campaign=nlp-cop-newsletter-21) is a great read on how to structure the qualitative text analysis better

## Data dashboarding

*Examples of how charities are using AI to create data dashboards.*

## Chatbots

*Examples of how charities are using AI to create chatbots.*

* [Citizen advice uses Caddy AI to help their advisors](https://github.com/Citizens-Advice-SORT/caddy-chatbot)
  * **Challenge**: Advisors spending excessive time searching through internal documentation for client queries
  * **Solution**: AI co-pilot that provides answers from verified sources, with supervisor review before client delivery
  * **Key Learnings**:
    - Human guardrails (supervisor review) effectively mitigate hallucination risks
    - Team training is crucial as prompt quality affects answer quality
    - **Risks**: Bias in answers and data privacy concerns
  * **Impact**: [Reduced phone waiting times by 50%](https://news.sky.com/story/phone-waiting-times-for-public-services-could-be-cut-in-half-after-successful-ai-trial-minister-suggests-13323464)

## Web applications

*Examples of how charities are using AI to create web applications.*

* [Chayn uses AI apps to help take down online content](https://tools.chayn.co/)
  * **Challenge**: Helping victims of image-based abuse create formal takedown letters
  * **Solution**: AI-powered web application that generates templated content based on user input
  * **Key Learnings**:
    - Built in just 7 days using AI-powered development tools (Cursor/Windsurf)
    - Rapid prototyping makes AI solutions more accessible to charities
    - **Risks**: Hallucinations (plausible but inaccurate information) and data protection concerns
  * **Bonus**
    - If your charity has any use cases on generating pre formatted letters or forms, this is a great example of how to do it.
