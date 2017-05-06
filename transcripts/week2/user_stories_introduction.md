So I'd say that ... the concept of the user story
... is one of the key things that comes out of
the ... Engineering Software as a Service course. I think it's a key
Software Engineering concept and ... I think it's
important to start with is first so here it is first ...
so what is a user story ... the idea, and you'll be familiar with these
... as they you know occurred in the main MOOC
... but the idea you know for ... to recap; is that they should be short,
simple, people-focused, or stakeholders as we also call them,
and business focused, so for example as a manager of a consulting company
in order to bill my clients accurately I want to track employee time
it's broken up into a ... this is a very standard sort of thing
and ... why do we need the user stories um
partly because you know ... we need to encourage participation among stakeholders
... I see, ... I think there are some people who feel
the value of these ... well I guess it's not so much the argument with ... I think that some people
argue
... with with things like ...
... cucumber which then takes the stories and break them into
the scenarios and there's an argument to say that the
you know, the client's never going to read those but I think the clients are often
quite interested in getting involved at this level at the user story ...
having this ... you know ... having the different kinds of stakeholders
involved in writing out these user stories. Really ... I mean the
the key thing for any project before you write any sort of code or even
choose your framework or what have you, is you work out what are the needs
... for the system that you're building ... and if you haven't
worked that out and you haven't got that straight then
you know there's just you know you're sort of ...
running round in the dark really ... so you know
closely tying the you know the requirements to the business needs
absolutely essential and they may end up forming the basis for the
acceptance testing ...
as we'll see ... shortly ... when we talk about ...
Cucumber and RSpec and so on. The
again ... I think the particular value
that we see for these ... I think whether for centralized or decentralized
... distributed teams is having an
English language description of the high level user story
as something so, you know when we're working, understanding
who it is what wants what and why it has business value is just absolutely
critical for getting everyone on the same page
and I think particularly in ... a
you know many different developers from all over the world, different backgrounds
coming in; having those acceptance tests well written out based on the
user stories and so that you then have
ideally a declarative cucumber stories describing
you know what what what's going on even if you never show those to the customer
... the you know between the developers who
will have different levels of experience with you know with whatever low level coding
it's just nice for them to have an English language description
so that they can all be clear that they're on the same page
... so you know there there's this Connextra format
as Dave and Armando presented in the main course you know
as some stakeholder so that I can you know
achieve some business need I want to be able to you know do this particular kind of thing
and that in your kind of feature request that you have ... the
you know ideally the the user stories are SMART
... we've got some good coverage of that in the textbook
with ... you know being, them being
specific ... achievable, relevant
... we've got, what's the other thing we've got
, ... they've got them in a different ..., S. M. A., relevant and time boxed
... so you know this is, I mean this is another sort of knack that comes over time
is sort of working out these these user stories I think ...
... often we have a particular trouble in our projects with ... time boxing
them
things often to get a bit ... a bit open-ended
... but yes, definitely do read chapter seven
again ... particularly ... I think ... in some ways I would almost argue that this is
this is sort of the entry point. I mean there's ...
in some ways to understand Cucumber perhaps you needs ...
you know a degree of understanding of you know different kinds of testing and
Ruby and so on but whenever you're sort of starting a new project this is this is the
place where you come in.
You come in with the user stories ... you don't come in with writing some Ruby code, you come
in with
some smart user stories and so that's you know at the top level
... that's why we're starting that's why we're starting here ... so
you know what's ... not a user story you've got
... little technical issues and chores I'd be tempted to wrap those two together
you've got bugs, getting documentation done although
you know self documenting code that's important and
... features without business needs I mean that this is you know ... the key thing
you know and there's many things that have to be done to move forward and get
something out
the key thing is that you ... you know you have to work out which are those
... small set of things that are going to really meet business needs ...
and then work out from those the even smaller set that's going to be your MVP or your
Minimum
Viable Product but so the ...
the five whys there's a technique that I think Dave already presented to you, this is a little bit of a
refresher
for for everyone ... you know the user stories should be able to reach a
you know a solid business value in five whys. So for example we've got a different user story here
in order to display my products as an online retailer I want have a catalog
on my website and so we might ask ... why do you want to include the catalogue on your web
site
... and the answer is so we, my customer can see all the varieties of the products.
... and why should the customer see all the varieties of the products?
... and if we move down there it's to have a bigger choice and why d'you want them to have a bigger choice?
They're more likely to buy if they .. if they find what they want
and what do you want them to buy ... why do you want them to buy anything? So I can make money.
Why do you want to make money? Then anyone should be able to answer this. Although of course you know that that
that
we shouldn't exclude the idea: that is money the root of all evil? I'm not sure
... it maybe that you know the project that you're working on is not specifically
you know about commercial goal but being clear about all the different levels
here
and also all the implicit assumptions here ...
is it the case that necessarily an extraordinarily wide choice
... you know ... it makes people more likely to buy? In some cases
actually narrowing the choice ... you know I think there's some evidence to show ...
that ... depending upon how you know if you present some people with the
three options ... they're more likely to ... choose one than if you present them
with twenty five options they may just run away in fear like woo oo oo .. anyhow
but ... the important thing with any of, with this whole process of generating user
stories and using three by
five cards which are mentioned in the course are to uncover the assumptions
about what's needed and why do we think ... things are the case
and you know whether you ... the I guess ...
you know ... with the team in a single office or you know in relative
good physical proximity ... there are more chances
meeting over the water cooler to or in main
meetings to work out what's what's going on it becomes
even more important in a distributed team to
uncover the different assumptions about why you're
developing anything that you think is gonna you know have some value to the
end users of your system ... so
simplicity is just I mean it's so important
up and down every level from the user story to the unit test
... you know everywhere you can inject simplicity and remove complexity
that's the way to go so if you've got sort of a higher more complex feature
break that into individual stories and and be very specific and avoid
vague business needs ... they've got some good examples there of ....
... you know ... someone being unspecific you know from from Dave and Armando
the you know the feature the user can search for movie is rather vague
but the user can search for movie by title is more specific. A simple example there.
... so you know there are gonna be sometimes
... just difficult things that you don't know how to turn into a
user story. Every situation is different ... just
you know break it down into components ... and
keep asking yourself is this addressing some some key level
business need and you know what are the assumptions that we're making here and
ideally this should be a dialogue between you
and everybody involved in the project; all the different stakeholders ... and you know
we'll talk more
... next next week about the different kinds of
online frameworks that you can use to help manage development of user stories
in ... the distributed team, but this YAGNI principle
which I often have trouble remembering. You Ain't Gonna Need It. I mean this is this is the key thing
that can often happen when you get a group of developers together and they say wouldn't this be cool
and this would be cool and and you know a lot of things
get created and the problem is
really that complexity is the killer for every additional feature
there's an additional ... kind of "N" plus one interactions with
all of the other existing features and ... you know so you'd like simplicity
modularity
only building the very very very very smallest subset of the things that you
need
really is the way forward ... so that's user stories and ... we'll see them
connecting up ... with ...
acceptance tests ... very shortly after we've had a quick detour into chores
alright bye for now
