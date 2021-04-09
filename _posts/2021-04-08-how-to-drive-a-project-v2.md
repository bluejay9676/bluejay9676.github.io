---
layout: post
title: "How To Drive a Project - Mindset"
---
# **Driving a Project**

I've been at Facebook for almost two years, with more context than ever. With growing responsibility and scope, I now realize that Facebook slogans they throw at you during orientation aren't gibberish, instead very condensed advice that is based on the "behavior" of a strong engineer. Let me elaborate.

## *Focus on Impact*

Facebook's emphasis on "impact" often gets mocked in dev communities for its ambiguity, but I don't think it's a buzzword that should be taken lightly. I believe it represents a virtue that any strong engineer should possess.

It's easier to grasp the idea if you imagine yourself as the owner of a product with real clients. As the owner, you wouldn't want your product to crash, slow down or lose users, give a bad user experience, etc. Your product should be reliable, scaled, and support all the users' needs. The development cycle should be painless - fast, automated, and foolproof. Otherwise, you're just sitting there losing money that you could've made by ensuring all the above. 

Now think of an ideal state of the product based on the concerns you have and where the product is now. Once you've identified where the gaps are (having a strong Data Scientist and metrics really help to figure this out), it's easier to tackle them. For example :

1. Dev process is slow, it should be 1 sec from push to deploy → I need to create a fast e2e code deployment

2. Prod breaks too often e2e testing.→ unit tests should be enforced upon push and block deployment when it fails!

3. User experience is bad due to slow and laggy products → We should revamp the backend to be more scalable and efficient!

4. I want to check real-time metrics to quickly address any issues! → I need to create a real-time dashboard to track metrics easily and set up an alert system.

You know, all the common stuff that we see at any company. But these are still valid things to do at a more micro level - a feature or a microservice you own.

5. Request for this specific feature has grown / This feature will improve the user experience greatly and will increase user engagement. → Quickly implement this and roll it out!

## *Move Fast && Nothing at Facebook is somebody else's problem*

Delivering a reliable and scalable product fast has its set of prerequisites. In order to deliver fast, you first need to execute well. This means you :

1. Understand the whole stack end-to-end. This helps you identify where the issue is or could be arising if it were to ever occur. When scaling up, you already know where the bottleneck is.
    - For this reason, it is worth looking underneath the multiple layers of abstractions. Especially at a big corporate, there are abstractions to make everyone's life easier - this oftentimes makes you too comfortable and myopic. You need to have a full picture.
2. Proactively unblock yourself ; unblock your colleagues
    - Everyone is here to help each other. Everyone is part of a team (even if one's in a different team than yours) with a common objective to improve things and ship good products. If you are struggling to push stuff out, formulate your question, post it for visibility, and ask around. Be the most productive version of yourself. The same applies to your colleagues. If they are struggling, that means you should jump in to help them out. Technically, their work is yours and your work is also theirs. Truly, nothing at Facebook is somebody else's problem.

 

### **Appendix : Why communicating is important**

Communicating often and efficiently is SO important (more than good execution in my opinion). Because this is the only way to remove risks in delivering a product. Especially in a large scoped project with multiple teams working on it, there should be zero bottlenecks blocking engineers. This is very hard to do, but communicating helps. Here's how:

1. Your manager can request or allocate more resources to you. He/she can unblock you by helping out with XFN alignment. Adjusting expectations and delivery timeline is crucial in a project involving multiple teams.
2. Other engineers with different context can identify risks in your approach. You don't want to turn back and rewrite the entire stack just because it's missing some crucial piece that you weren't aware of. Leverage that collective intelligence.
3. More of your teammates will understand what you are doing. Having a larger surface area to answer questions from other team's engineers can unblock them even when you're out of office, etc.