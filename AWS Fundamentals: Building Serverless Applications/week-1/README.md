
Welcome to "AWS Fundamentails: Building Serverless Applications"! This is our second class in our AWS Fundamentals series on Coursera. This course, will focus on what you need to know to help you build serverless applications. We strongly recommend that you complete the prior class, Going Cloud Native before starting this class.

"Serverless" is designed to run over four weeks, though all of the content will be available from the start, and you can proceed at your own pace.

Throughout this class there will additional reading and other resources.

As part of the course, there are hands-on exercises where you will have the opportunity to use AWS services to build upon the content that we cover in the presentations. You will do this using your own AWS account. The exercises are designed to run within the AWS Free Tier. If you don't alreay have an AWS account. You can find instructions here to create one. If you already have an account, you should be good to go.

So, welcome to "Building Serverless Applications on AWS" as we say at Amazon, "Work hard. Have fun. Make history"


## Amazon Lex

[Amazon Lex](https://docs.aws.amazon.com/lex/latest/dg/what-is.html) is a service for building conversational interfaces into any application using voice and text. Amazon Lex provides the advanced deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text, to enable you to build applications with highly engaging user experiences and lifelike conversational interactions. With Amazon Lex, the same deep learning technologies that power Amazon Alexa are now available to any developer, enabling you to quickly and easily build sophisticated, natural language, conversational bots (“[chatbots](https://aws.amazon.com/what-is-a-chatbot/)”).


## Amazon Lex pricing

With Amazon Lex, you pay only for what you use. You are charged based on the number of text or voice requests processed by your bot. Please see the [pricing page](https://aws.amazon.com/lex/pricing/) for current information.


# What is Serverless?

[Serverless](https://aws.amazon.com/serverless/) is the native architecture of the cloud that enables you to shift more of your operational responsibilities to AWS, increasing your agility and innovation. Serverless allows you to build and run applications and services without thinking about servers. It eliminates infrastructure management tasks such as server or cluster provisioning, patching, operating system maintenance, and capacity provisioning. You can build them for [nearly any type of application](https://aws.amazon.com/serverless/#Serverless_Application_Use_Cases) or backend service, and everything required to run and scale your application with high availability is handled for you.

In this class, we will build a serverless application that uses Amazon S3, host a static serverless website. [Amazon Cloudfront](https://aws.amazon.com/cloudfront/) to securily cost-effectively distrubute our content. [Amazon Lex](https://aws.amazon.com/lex/), to create serverless [chatbot](https://aws.amazon.com/what-is-a-chatbot/). Amazon [API Gateway](https://aws.amazon.com/api-gateway/), to create a test endpoint before we integrate the front and backend of your application. Amazon DynamoDB, will provide a serverless database service behind [AWS Lambda](https://aws.amazon.com/lambda/), our serverless compute service.