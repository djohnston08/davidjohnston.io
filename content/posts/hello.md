---
title: "Hello"
date: "2017-11-23T21:18:25-05:00"
description: "Hello, a little intro about me."
author: "David Johnston"
slug: "hello"
---

Hello, I'm David Johnston.

Over the course of my career so far, I've worked at various companies doing various things.  Kentucky isn't really known for big tech, so options have always been a bit limited.  After finishing college I took a web development position.  Started working in PHP and had a short stint at a small startup, helping them get off the ground.  Then I moved on to Ruby, .NET, Java, and back to .NET.  This ranged from small startups to large enterprise organizations.  Somewhere in the middle of all this I took a few years and took a sysadmin position managing very large Microsoft deployment and a mid-sized AIX deployment.  Over the course of these experiences I have learned a lot about myself, but I do know I haven't quite found my dream development yet.

A couple of years ago I received a call from a recruiter that I believed would result in an instant no, but turned out to be a great experience to help me explore what I loved more.  He talked me into at least hearing them out and taking an interview.  When I arrived I found out their whole system was one giant PHP application written in PHP 4 and barely upgraded to 5.4.  The whole system was running on a single VPS by a vendor who I can now say is horrible.  The problems they had were endless.  The site would crash and become unresponsive if a very small number of concurrent users visited the site (read: < 100).  The VPS provider would randomly update the VM without notification and the whole site would completely go down because the server configs would get wiped.  Communications provided by our service were only being delivered rarely, but at this time no one knew that because there was no logging.  THE ENTIRE APPLICATION HAD ZERO LOGGING!!  Finally, the best part, the whole technical staff consisted of a few web design contracting firms that they were planning to stop using to build an internal staff, so I would be the only one at this time.

I realize this is the point you might be saying, "How did you not walk out?"   However that is not what happened.  This company is a small payment comapny who catered to niche groups of member based organizations.  They were already processing about 60 million in payments a year, so the company seemed viable.  I was told that the goal was to build a team and turn this into a manageable project that we could expand and grow with.  I was told that I could call the shots as far as how that worked, but there was really only one requirement.  They wanted to remain with PHP being the primary language, because they felt it would be simpler to get more developers later on.  In Lexington, KY they are probably right.  I wasn't thrilled about this at first, but so far it hasn't been too bad.

Since that time we have moved the core of our logic to a REST api, split out the frontend client applications to multiple Angular applications.  Our REST api is powering 3 companies.  I have a team of 4.  We are going to process over 100 million this year.  Our subscription revenue has more than doubled and we can now handle all the traffic we receive from our customers with ease.

This is where the fun has begun.  Now I have the opportunity to mostly choose the work I'm doing and that is ranging from exploring performance across the application, improving our development workflows, exploring scalability for our newly launched ventures and better automation to streamline everything we do.  This has finally let me have the opportunity to begin exploring Kubernetes and get to start writing additional services in Go.

We will see where it goes from here.