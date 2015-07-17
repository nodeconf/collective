# How to run a ONE-SHOT

**ANYONE** can run a simple single day conference. We've collected documentation and best practices that make it even easier which you are free to adopt, with a few ground rules.

* ONE-SHOT is meant to be *accessible* in cost and in content. Content should be good for new users and ticket cost should remain relatively cheap so that the local community can afford to attend. We have a lot of advice in the documentation here that can help you keep your costs low so that the ticket price can remain accessible.
* ONE-SHOT conferences celebrate a **city** and its local community. For instance, there is a ONE-SHOT London, but not a ONE-SHOT England, ONE-SHOT UK, or ONE-SHOT Europe.
* Every ONE-SHOT must adopt a **Code of Conduct** and commit to enforcing it. The default template includes one that you can modify with your contact information. 

# Getting Started

First off, create a new issue in the organizers repository with the city you're in and any other organizers you have. We will then create a new a team in the oneshot organization for your city, add you to the oneshot organizers team, fork the oneshot repo template and add your team to it.

## Conference Repo

Your conference repo serves several functions.

* The `gh-pages` branch is a template for your conference's website. You'll need to edit it with your events information.
* The default README has instructions for your event's CFP (Call for Proposals) which encourages people to log new issues as proposals. You'll need to edit the README with a few of the specifics of your event.
* You can also use the issue tracker to start threads about the conference planning and organization which encourages participation not just from other organizers but also the community that is logging issues in order to speak.

Feel free to dramatically edit and entirely change the conference website. The template is only there to help you along but if you have front-end and design resources at your disposal it's even better for the site to more accurately reflect your city and community.

You can also change the CFP, although we do advise against it. Past ONE-SHOT organizers have been iterating on the CFP for a while and it includes a lot of best practices. Of course, this is your conference and you should feel free to change *anything* you like.

## How many talks do I need? How should I schedule them.

You should have between 9 and 12 talks of 20 minutes each. That may not sound like a lot but it's plenty. Attendees appreciate quick content and long breaks. We recommend you lay out the content in to 3 "acts."

* **10:00 - 12:00** Act 1
* **12:00 - 14:00** Lunch
* **14:00 - 15:30** Act 2
* **15:30 - 16:30** Break
* **16:30 - 18:00** Act 3

Each act should have 3 or 4 talks. Try to put talks related to each other next to one another and encourage those speakers to collaborate it possible so that each talk flows in to another.

Talks should be 20 minutes. If you're pressed for time and doing 4 talks per act make sure you're persistent about cutting speakers off when they go over.

**Do not post a full schedule publicly**. If talks go over or under time, if it takes longer than expected to wrangle people in from a break, you'll want to adjust the timing and a public schedule makes that too difficult. Let people know that talks will begin at 10:00 sharp and they'll be out by 18:00, that's all they need to know. Also, when attendees don't know which talks are on they will be more punctual in attending and when speakers lead in to one another this can be rather important because attendees will be lost if they attempt to pick and choose individual talks.

## Food, drink, parties.

First of all, you don't *have* to provide full meals for the attendees. In fact, it can be much better to allow attendees to use the 2 hour lunch break to explore the city and get a meal with new acquaintances.

It's best to provide coffee and a light snack when people arrive. Drinking water is the most important thing, have plenty around and don't forget to bring it ;)

Optionally, you can provide lunch, and a closing party with drinks. It's best to tie both of these items to a high level sponsorship and not commit to doing them until that sponsorship is secured.

## Speaker reimbursement

If you do bring in out of town speakers it's best to try and cover their travel expenses. If you have the infrastructure to purchase their travel and accommodations outright it is best to do that. Another option is to provide a stipend, this has the benefit of a known fixed cost per speaker which makes budgeting easier. 

If you're not confident you'll have enough money to cover these expenses you can offer to reimburse speakers after the conference *if* the event makes enough.

It's also a good idea to offer a low level sponsorship tier to your speaker's employer if they cover their travel costs.

Whatever you decide, make sure that you state the terms clearly in the README with the other CFP instructions.

## Ticketing 

Different ticketing platforms are available in different countries. What you want to look for is a platform that can get you the money you've collected in sales as soon as possible. Many event platforms and payment processors withold funds much longer than normal because events in general have a higher rate of credit card refunds (it is more typical for someone to request a refund from their credit card company on a charge for an event they did not attend than other types of purchases). 

For instance, Eventbrite won't pay out until **after** the event. Some ticketing platforms have their own payment processor and some allow you to hook up your own so you'll also need to look in to the payment processor and their terms. Avoid paypal if at all possible, they have been known to withhold funds from conferences indefinitely.

We strongly suggest using [tito](https://ti.to) for ticketing and [stripe](https://stripe.com) for payment processing if they are available in your country. Stripe pays out the money you've collected within a week and tito is a great ticketing platform built by an active conference organizer.
