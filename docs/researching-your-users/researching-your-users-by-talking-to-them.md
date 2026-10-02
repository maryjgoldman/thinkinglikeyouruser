# Researching your users by talking to them

Remember that users are generally happy to talk to you. The tool you are building will ultimately help them do something they want to do, so they are typically motivated to help you. If you're meeting in person, you can offer to pay for a coffee or bring snacks to show your appreciation, but it's not necessary.

## Notes on talking to users

* They will be cautious to not offend you. They sympathize with the effort needed to build a tool and so will not want to outright say what they really think. This means that they may consciously or unconsciously lie to you to not hurt your feelings.
* Their memory is biased. This means they don't remember things exactly as they happened. They may feel like they are always spending time doing a task, when really they don't spend that much time doing it. It is best to always ask about the last time they did a task instead of asking about the task generally.
* It is useful to ask not only about your tool but also about what they do now without your tool or even with your competitors. This will help you to understand their pain points in general.
* Don't ask users if they like your idea, design, etc. Users will inevitably say they do, even if they wouldn't use your tool in real life.
* Don't ask leading questions. If you ask 'Would you rather use the old version or this improved version of the website?' users will inevitably say they want the new version when really they would prefer the older version. Asking non-leading questions is a skill that can take some time to develop.
* Ask open-ended questions. To get the most out of the interview, focus on questions that cannot be answered with only a 'yes' or 'no'. If you find most of your questions are yes/no questions, a [survey](researching-your-users-without-talking-to-them.md#surveys) may be a better option.
* Note the language and terminology they use when talking about the data, tool, etc. Developers often have different words for data and concepts than the users of a tool. For instance, developers might call it metadata, while users call it clinical data. Note the terminology they use so that you can use it in your tool's UI.
* While you can talk about your tool and what it does, postpone this as far into the conversation as you can. You can talk about your tool abstractly at first and then in more detail later on in the conversation. This will help prevent biasing your feedback.&#x20;
* Remember that if they ask for a feature, your job is to understand why they are asking for the feature and what they're hoping to accomplish with it. While you may end up implementing the feature they request, you may also end up realizing that their issue could be better solved with a different feature that they haven't requested.

## Methods to talk to your users

### Talk to folks in the hall and collaborators

A good place to start physically talking to folks is at your institution. It may be that there is no one at your institution that is actually your target user for your tool, but there is likely someone who is closer than you are. Find these folks and talk to them at lunch or ask to chat with them for 20 min about the tool (see [meet with users](researching-your-users-by-talking-to-them.md#meet-with-users) for tips).

Talking to collaborators who are also users or potential users of your tool can be useful, especially if you try to learn as much as you can from them before sharing any results. While they are motivated to work with you since they are collaborating with you, you run the risk of developing a tool that only works for them if you aren't getting information from other folks.&#x20;

### User-facing conferences and poster sessions

Conferences and, in particular, poster sessions where your users will be present are a great way to talk to folks. Start by asking users about their research, what tools they currently use, and what they like and dislike about those tools. If they are already users, ask them what they use your tool for. Only after listening to them should you tell them about your poster and tool.

In addition to talking to users at your own poster, you can also go to posters or booths of your competitors. Talk to them about what their tool is doing and who they're targeting. If their poster or booth is especially busy, you may even be able to talk to other folks around you, again asking the same questions you would have asked if they were at your poster.

### Meet with users

This is a great method for understanding users’ mental models and running new designs by them. This is typically called 'interviewing' users but the term 'interview' can deter both the interviewer and the interviewee. It's better to think of this as meeting with users and asking them a few questions.&#x20;

I recommend asking to meet for an hour, but even as little as 20 min can be helpful if you think that's all you can get or is all the time you have.

Don't worry about getting a lot of folks to talk to. Talking to even one person is better than talking to no users. Ideally, you would speak to 3-5 users since [speaking to more than 5 users has diminishing returns](https://www.nngroup.com/articles/why-you-only-need-to-test-with-5-users/).

{% hint style="info" %}
AI note (August 2026): AI can help you transcribe a Zoom meeting afterwards, but ensure that you are using a model that isn't learning from your data so that you preserve user confidentiality.&#x20;
{% endhint %}

Watching users use the tool or a design can give you important feedback on not only minor things such as colors, button placement, etc, but also on big things like their thought process and their workflow.

* The best way to test something is to give them an example task that is representative of a use case they might have, and then watch them use the design.
* As difficult as it might be, do not tell them what to do. Remember that you will not be alongside your future users to tell them how to accomplish a task. If they get stuck, the best thing you can do is to be quiet and say things like, 'I know it feels like you are doing something wrong, but you are helping me to understand how to design this better.'
* It may be very painful to watch someone use the interface and not be able to help them. If they have been stuck for a few minutes or if it is one of the first tasks (and hence if they don't make it through this they won't make it to any of the other testing), you can offer a small hint. Otherwise, refrain from helping them.
* Memorize a few sentences like 'tell me more about that' to get folks to start talking again in a way that doesn't bias your user if they get quiet.

Here are some great resources for interviewing folks for scientific software:

* [User testing on a shoestring](https://www.readwriterachel.com/opinions/hacks/presentations/2026/08/26/usertesting-on-a-shoestring.html)&#x20;
* [Rapid usability testing workshop](https://carpentries-incubator.github.io/rapid-usability-tutorial/)

#### Do I need IRB approval?

Typically you do not need IRB approval to conduct UX interviews. UX interviews are conducted primarily to improve a tool, and the insights that you will gain are typically not generalizable beyond that tool. Even if you do intend to [publish your UX work](../bringing-ux-to-your-organization.md#publish-papers-and-present-at-conferences), UX interviews are typically exempted as they involve standard interview or survey procedures where the data is recorded in a way that the identity of the users cannot be readily ascertained and any accidental disclosure of the user's responses outside the study would not reasonably place them at risk of harm.

If you are hoping to publish generalizable information about your interviews, such as [user personas](../thinking-like-your-user.md#create-personas-archetypes), it would be good to contact your local IRB to see if you need approval.

#### Do I need to pay users?

Typically, in industry, users are offered some small token of appreciation like a gift card. However, for scientific environments, you generally don't have to. Most researchers are in research because they want to, not because of the money, and researchers in general are motivated to make the tool they use better. That said, most users expect a behind-the-scenes glimpse at a new feature, or the ability to ask for one-on-one help with an issue.
