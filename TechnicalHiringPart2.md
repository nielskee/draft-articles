# Technical Hiring Part 2

- What they _say_ they can do : CV, cover letter

- What they _show_ they can do : technical interviews

- What they _actually_ do : how it all translates into real
  development work on your codebase.

You can build confidence in the first two things by asking questions
and running technical interviews. To some extent you can also predict
the third, if you get the interviews right.

## CV and Cover Letter

Talking about hiring is really difficult without context. Like
software development, you can't give definite advice that

- (1) You're in a company which needs to move into a new technical
  domain.

- (2) Your organisation


There's only question that needs answering at this stage "Can I
picture this person working as part of our team?"

We have a CV, a cover letter, possible some links to portfolio
work. Probably a bunch of them, from multiple candidates.

At this stage, I'm trying to decide whether you want to have a
conversation with the person - that's all, just a conversation. A
phone screen takes about 15-20 minutes, so I'm not going to spend 30
minutes agonising over that decision.

You might have quite exacting requirements - specific experience you
need, or specific tech skills that can't easily be picked up. You
might be hiring someone specifically to help you bootstrap you into a
new technology. Whatever the situation, you're going to know in about
5 minutes with a CV and cover letter whether you're looking at someone
who you can picture working in your team.

Putting aside your tech specifics, here are some things I view as
positives in a CV, that might make me want to have a conversation with
them.

- Self-improver

- Breadth and depth

- Evidence of personal or open-source projects, attendance at meetups
  and conferences, and engaged in their community.

- Some signs that they help other people : coaching, mentoring,
  helping kids or adults learn to code.

Although it's great to see evidence of personal projects, remember
that this can be a lot easier for some people than others. People with
a lot of discretionary time can work on personal projects, and attend
meetups and conferences. People with childcare or eldercare
commitments often can't.

Where candidates do have these projects and activities, sure, view
them as positives, but always remember that personal circumstances
play a part.

## Phone / Video Screens

They used to be a big thing, phone screens : Technical Interview Lite,
effectively. Like all screening, the idea was to go forward to the
next stage with the candidates you think are the best prospects. You'd
have a list of tried and tested questions, that would (in theory at
least), help you divide the candidates into two camps, making a
go/no-go decision on each.

I've used them that way in the past in Q&A mode, but always found them
stilted, awkward and ineffective, and I think candidates did too. It's
a strange sort of conversation, barking questions apropos of nothing
into a mouthpiece.

I do them differently now. I use a much more conversational style, and
tend to base questions around a candidate's stated experience rather
than a list of requirements for a role. I use that as a jump-off into
some technical discussion. With this approach, you follow the trail of
the discussion, and spot opportunities to ask some technical questions
along the way. It's more natural, tends to flow better, and you get a
more accurate impression of the candidate to base decisions on.

What I'm looking for at this stage is consistency rather than probing
for deep knowledge and experience. For example, if someone has said
they do test-driven development, I'd expect to get some quite
confident discussion around the test framework they're using. I'd
expect them to have some examples from their work that they can talk
about.

I'll usually ask a mix of open and closed questions. I want to see how
the candidate communicates - and not just in terms of technical
accuracy, but whether there's any genuine passion and enthusiasm for
the subject.

- Use a phone screen as a chance to introduce yourself to each other,
  and to make sure the candidate is on board with the process.

- Focus on what candidates say they know, rather than what you
  need. Remember : trajectory.

- Use a conversational style based around the experience on their
  CV. Follow the trail, and improvise. Get in some technical questions
  that are relevant to the context as the conversation develops.

- It doesn't need to be deep : you're going to have some other, better
  screening mechanism. It's an introduction and a consistency check
  above all.

- Non-sequitur technical questions are just awkward. Good candidates
  experience brain-freeze, and less good candidates will have
  memorised every Google search result for "technical interview phone
  screen questions".

- Keep these to 15-20 minutes. Experienced interviewers tend to know
  quite quickly if a candidate is a go or a no-go, often in the first
  few minutes.

Some people afind this a harder format to run than having a set
question list. You certainly need to think on your feet, but I think
you get a better feel for the candidate.

## Online Technical Test Platorms

Online technical assessment tools like HackerRank and Codility are
becoming more widespread in hiring. I think I understand why companies
are using them, although I think they're used wrongly (or excessively)
more often than not.

TODO: mechanisms and measures

Superficially, these platforms seem to provide an objective measure of
capability. After all, the intent of HackerRank is to Rank your
Hackers, is it not? I see this all the time in software development,
and not just in hiring - this urge to reduce something complex,
nuanced and difficult to understand down to a dashboard
metric. Numbers are seductive - they promise simple answers and
absolute truths.

In reality, though, these tools are an example of the Streetlight
Effect in action:

> A policeman sees a drunk man searching for something under a
> streetlight and asks what the drunk has lost. He says he lost his
> keys and they both look under the streetlight together. After a few
> minutes the policeman asks if he is sure he lost them here, and the
> drunk replies, no, and that he lost them in the park. The policeman
> asks why he is searching here, and the drunk replies, "this is where
> the light is."

Just because there's light to see by, it doesn't mean you're looking
in the right place. HackerRank and Codility measure that which can be
measured, not necessarily what's important.

More fundamentally - and a thought that seems to occur to virtually
no-one who uses these tools - 

Here's where we really want to look:

- Changeability and maintainability of code.

- Clean code and simple design.

- Ability to find a solution by working collaboratively in pairs, and
  in teams.

- Working in small increments, driven by tests.

- Readability and naming in the code.

TODO: "it's just a screen". Refer back to first post.

Platforms where developers code against a clock is no way of assessing
these important skills and character traits. They assess the
characteristics of _code_, not of people. They're a proxy measure at
best, and not even a particularly useful one.

- If timed code challenges are important to you, because you want
  people continually "delivering against tight deadlines", you're
  probably horrible people. Think about the signal this is sending.

- If you need to run a coding assessment remotely, look to use the
  excellent CyberDojo instead : a platform that emphasises Test-Driven
  and small steps.

- If algorithmic problem-solving is vital to the sort of work you do,
  there are better ways of running algo and data structures interviews
  : more in the next post on that.

- Don't sleepwalk into outsourcing your technical interview to an
  online platform. Some aspects of hiring are _just hard work_, and
  you need to be prepared to put in the personal effort with
  candidates for the more challenging parts of your tech selection.

## Coding Assignments

If you need to scale up your technical screening, I propose that this
is a better way of doing it than the online route. It has many
benefits

- Relevant

- Tests as well as code

- Style and expressiveness

- Used the tools well - Git especially

- Navigable

## How to run

- Set up a GitHub repository and ask your candidates to fork the
  repostitory.

- Ask candidates to commit regulary

- Ask candidates to narrate how they're doing in the README

- Great springboard for f2f

- Be clear about your own coding values

- Submit via a pull request (the pull will never be merged)

## Hackathons

I know a lot of companies use these as a talent-spotting mechanism,
especially for early careers. They're fun, and largely harmless.

I think they're more a mechanism for talent acquisition (not my field)
rather than technical selection.

## Balance

So now we have a CV, annotated with some notes from a phone
conversation, and an assignment that's been reviewed by a developer.

Balance matters.
