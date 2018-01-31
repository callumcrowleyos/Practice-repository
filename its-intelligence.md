
# ` It's intelligence, Jim, but not as we know it. `
________________________
**October 11, 2017
|** ** James Dadd **

![its intelligence](its intelligence.jpg)

 William Gibson said _"The future is here, just not evenly distributed yet"._ Amazon plans on changing that, with a mission to democratize access to Artificial Intelligence (AI) services. The good news is that this means it will be a lot easier to consume AI related services, and not requiring a PhD in Maths to get started!

**fourTheorem** recently attended an AI day at the AWS Loft in NYC, and the following is a brief summary of the material covered.

The day was kicked off with a high level overview of the services offered by Amazon. They have a simple definition of AI: _“A system or service that performs tasks that usually require human intelligence”_

Amazon have been working on AI systems since the ‘90s, and have thousands of engineers focused in this area. Fulfillment and logistics for Amazon.com, for example, makes use of AI in areas such as routing and delivery of packages. There are a large number of robots in warehouses, grabbing appropriate racks of products and taking them to packers. Search and Discovery on Amazon.com is also driven by AI.

New products you may have heard of, such as Amazon Go and Amazon Echo, incorporate AI through the underlying technology (Polly, Lex, etc). If you’re not aware, Amazon Go is a physical store (think corner grocery store like 7-11 or Tescos Express) where no money changes hands, and you are charged directly to your Amazon Prime account via some sort of  smartphone app hookup.

AI services currently offered by AWS include:
- Apache MXNet (Deep learning framework)
- AWS Polly (Text-to-speech engine)
- AWS Rekognition (Computer Vision)
- AWS Lex (ASR and NLU)

Apache MXNet is a highly programmable deep learning (DL) framework, that is portable (it can run on low end devices such as Raspberry Pi), high performing (near linear scaling across hundreds of GPUs), and open source within Apache incubator. It is the DL framework of choice for AWS, and provides optimized DL on AWS that integrates with other AWS services. Poly, Lex, and Rekognition all use MXNet under the covers.

Amazon Polly is a lifelike fully managed Text-to-Speech service, currently with 47 voices in 24 languages. It provides low latency and works in real time. Voice quality and pronunciation are automatic and accurate, providing the proper use of the same word in different situations (semantic meaning). You can also customize pronunciation if required. The use cases for Polly are many, including IOT, Education (language training, training videos), voiced media, chat bots, and gaming (Avatars, Amazon Lumberyard). Amazon has joined the #VoiceFirst Movement, which is a joint effort with Google and Apple to increase use of voiced apps for new applications.

Amazon Rekognition is an image analysis service. It can perform object and scene detection, identifying  objects in pictures; facial analysis, inferring characteristics (eg. smiling, happy, sad) as well as gender and other features (eg beard, moustache, glasses). Perhaps the cooler capabilities that unlock the true potential of this technology are Facial Comparison and Facial Recognition. Use cases include best photo identification (eyes open versus closed), demographic detection (age and gender in retail stores), sentiment capture (happy, sad),  A/B tuning (best image to use), smart filtering (inappropriate material), facial verification (security), and protected images (trademarks, logos).

Amazon Lex allows you to build voice and chat bots, and deploy them to different platforms like Slack or Facebook Messenger. Lex uses the same DL technology as Alexa, and offers interactions on mobile, web and other devices. Lex also offers enterprise SaaS connectors (Zendesk, HubSpot, Salesforce, Quickbooks, MS Dynamics). Use cases include Info bots, Application bots, Enterprise productivity bots (Check sales numbers, Marketing performance, Inventory status), and IOT (Wearables, Appliances, Autos). Lex uses Lambda, and is not HiPPA compliant yet.

The second session of the day was a workshop on how to build better chatbots with Lex and Polly. What's the business value of bots, you might ask? They can help answer questions, perform tasks on behalf of users, increase efficiency and/or user experience, offer easier access to relevant data, help users make more informed decisions, and streamline business processes. If you’re interested in completing the workshop yourself, the steps can be found here
(https://s3.amazonaws.com/shared-files-kls/CoffeeBotCreationInstructions.html)
![information bot](information bot .jpg)

The post-lunch schedule featured a session on DL. One of the key arguments made for implementing AI and DL is around the sheer quantity of data being generated every second of every day. Like a fly-wheel with its own momentum, more data means better analytics which, in turn creates better products and services, which in turn attracts more users who create more data…..and so the virtuous cycle continues.

From a high level, deep learning is a subfield of machine learning which is a subfield of artificial intelligence. The beauty of DL models is that you can throw so much more data at them, and have faster results than any other solutions out there. With more data, you get better accuracy. With speed you can throw more raw data at your model.  Amazon are using DL internally in areas such as applied research, core research, Alexa, demand forecasting, risk analytics, search, recommendations, AI services, Q+A systems, and supply chain.

AWS provide a DL machine image (AMI) that utilizes GPUs. It supports up to 40,000 CUDA cores, and comes pre-installed with common DL libraries (TensorFlow, Apache MXNet, Kaffe, and others) as well as Python3. A typical DL deployment model has the training and heavy number crunching taking place on elastic and scalable cloud resources, with models stored in S3. The models are then run on Edge devices (eg phone, drone).

As you can see, Amazon is doing a LOT within the AI space and we barely scratched the surface. I’d highly recommend you check out their offerings and, if you get a chance, attend one of their workshops. The market is maturing around artificial intelligence, machine learning, and deep learning. Businesses are starting to explore the possibilities and opportunities. Are you?

________________________
