---
layout: post
title: "How To Drive a Project - Mindset"
---

# Driving a Project

## Ownership

Facebook's focus on "impact" often gets mocked in some dev communities for its ambiguity, but I don't think it's a buzzword that can be taken lightly. I believe it represents a virtue that any strong engineer should possess.  

It's easier to grasp the idea if you imagine yourself as the owner of a product. As the owner, you wouldn't want your money-making product to crash, slow down or lose users, etc. Your product should be reliable and scaled. Your development cycle should be fast, automated, and foolproof. Otherwise, you're just sitting there losing money that you could've made by ensuring all the above. 

Now think of an ideal state of the product based on the concerns you have and where the product is now. Once you've identified where the gaps are, it's easier to tackle them. For example :

1. Dev process is slow, it should be 1 sec from push to deploy! → I need to create a fast e2e code deployment
2. Prod breaks too often e2e testing.→ unit tests should be enforced upon push and block deployment when it fails!
3. User experience is bad due to slow and laggy products → We should revamp the backend to be more scalable and efficient!
4. I want to check real-time metrics to quickly address any issues! → I need to create a real-time dashboard to track metrics easily and set up an alert system.

You know, all the common stuff that we see at any company. But these are still valid things to do at a more micro level - a feature or a microservice you own.

## Delivery

### Execution

Delivering is a whole new story from identifying problems. You should be able to execute well. In my opinion, in order to execute well you need to

1. Understand the whole stack end-to-end. This helps you identify where issue is (could be) arising if it were to ever occur. Also when scaling up, you already know where the bottleneck is.
    1. For this reason, it is worth looking underneath the multiple layers of abstractions. Especially at a big corporate, there are abstractions to make everyone's life easier - this oftentimes could make you too comfortable and myopic.
2.  Unblock yourself; unblock your colleagues
    1. Everyone is here to help each other. Everyone is part of a team with the same objective - benefit the product. If you are struggling to push stuff out, formulate your question, post it, ask around. Be the most productive version of yourself.
    2. This applies to your colleagues as well. If they are struggling, you should help out fast. Technically, their work is yours and your work is also theirs (remember "nothing at Facebook is somebody else's problem"?)

### De-risk : Why communicating is important

Communicating often and efficiently is important for two reasons

1. For managers to ask for or allocate more resources to you. He/she can also unblock you by helping out with XFN alignment. Not to mention adjusting expectations and delivery timeline based on your status is crucial in a project involving multiple teams.
2. For other engineers with different context to identify risks on your approach. You don't want to turn back and rewrite the entire stack just because it's missing some crucial feature that you weren't aware of.
3. For your teammates to understand the context. Having a larger surface area to answer questions from other team's engineers reduces bottleneck in unblocking them.