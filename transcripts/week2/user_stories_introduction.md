0
00:00:00,329 --> 00:00:03,310
So I'd say that ... the concept of the user story

1
00:00:03,310 --> 00:00:07,020
... is one of the key things that comes out of

2
00:00:07,020 --> 00:00:10,030
the ... Engineering Software as a Service course. I think it's a key

3
00:00:10,030 --> 00:00:13,410
Software Engineering concept and ... I think it's

4
00:00:13,410 --> 00:00:16,449
important to start with it first so here it is first ...

5
00:00:16,449 --> 00:00:20,539
so what is a user story ... the idea, and you'll be familiar with these

6
00:00:20,539 --> 00:00:24,199
... as they you know occurred in the main MOOC

7
00:00:24,199 --> 00:00:27,960
... but the idea you know for ... to recap; is that they should be short,

8
00:00:27,960 --> 00:00:31,060
simple, people-focused, on stakeholders as we also call them,

9
00:00:31,060 --> 00:00:34,649
and business focused, so for example as a manager of a consulting company

10
00:00:34,649 --> 00:00:39,149
in order to bill my clients accurately I want to track employee time

11
00:00:39,149 --> 00:00:42,260
it's broken up into a ... this is a very standard sort of thing

12
00:00:42,260 --> 00:00:45,550
and ... why do we need the user stories um

13
00:00:45,550 --> 00:00:49,600
partly because you know ... we need to encourage participation among stakeholders

14
00:00:50,129 --> 00:00:53,160
... I see, ... I think there are some people who feel

15
00:00:53,160 --> 00:00:57,690
the value of these ... well I guess it's not so much the argument  with ... I think that some people

16
00:00:57,690 --> 00:00:58,350
argue

17
00:00:58,350 --> 00:01:01,449
... with with things like ...

18
00:01:01,449 --> 00:01:04,909
... Cucumber which then takes the stories and breaks them into

19
00:01:04,909 --> 00:01:08,100
the scenarios and there's an argument to say that the …

20
00:01:08,100 --> 00:01:11,610
you know, the client's never going to read those but I think the clients are often

21
00:01:11,610 --> 00:01:15,060
quite interested in getting involved at this level of the user story ...

22
00:01:15,060 --> 00:01:19,229
having this ... you know ... having the different kinds of stakeholders

23
00:01:19,740 --> 00:01:23,049
involved in writing out these user stories. Really ... I mean the

24
00:01:23,680 --> 00:01:27,689
the key thing for any project before you write any sort of code or even

25
00:01:27,689 --> 00:01:30,750
choose your framework or what have you, is you work out what are the needs

26
00:01:30,750 --> 00:01:34,340
... for the system that you're building ... and if you haven't

27
00:01:34,340 --> 00:01:37,390
worked that out and you haven't got that straight then

28
00:01:37,390 --> 00:01:40,790
you know there's just you know you're sort of ...

29
00:01:40,790 --> 00:01:43,840
running round in the dark really ... so you know

30
00:01:43,840 --> 00:01:46,950
closely tying the you know the requirements to the business needs

31
00:01:46,950 --> 00:01:50,770
absolutely essential and they may end up forming the basis for the

32
00:01:50,770 --> 00:01:51,549
acceptance testing ...

33
00:01:51,549 --> 00:01:55,079
as we'll see ... shortly ... when we talk about ...

34
00:01:55,079 --> 00:01:58,170
Cucumber and RSpec and so on. The

35
00:01:58,170 --> 00:02:02,009
again ... I think the particular value

36
00:02:02,009 --> 00:02:05,479
that we see for these ... I think whether for centralized or decentralized

37
00:02:06,180 --> 00:02:09,209
... distributed teams is having an

38
00:02:09,209 --> 00:02:13,640
English language description of the high level user story

39
00:02:13,640 --> 00:02:16,709
as something so, you know when we're working, understanding

40
00:02:16,709 --> 00:02:21,520
who it is, what wants what, and why it has business value is just absolutely

41
00:02:21,520 --> 00:02:23,239
critical for getting everyone on the same page

42
00:02:23,239 --> 00:02:26,500
and I think particularly in ... a

43
00:02:27,160 --> 00:02:30,260
you know many different developers from all over the world, different backgrounds

44
00:02:30,260 --> 00:02:34,480
coming in; having those acceptance tests well written out based on the

45
00:02:34,480 --> 00:02:35,930
user stories and so that you then have

46
00:02:35,930 --> 00:02:40,950
ideally a declarative Cucumber story describing

47
00:02:40,950 --> 00:02:45,010
you know what - what's going on even if you never show those to the customer

48
00:02:45,010 --> 00:02:48,190
... the you know between the developers who

49
00:02:48,190 --> 00:02:51,400
will have different levels of experience with you know with whatever low level coding

50
00:02:51,400 --> 00:02:54,430
it's just nice for them to have an English language description

51
00:02:54,430 --> 00:02:57,849
so that they can all be clear that they're on the same page

52
00:02:57,849 --> 00:03:01,620
... so you know - there's this Connextra format

53
00:03:01,620 --> 00:03:05,050
as Dave and Armando presented in the main course you know

54
00:03:05,050 --> 00:03:08,099
as some stakeholder so that I can you know

55
00:03:08,099 --> 00:03:11,950
achieve some business need I want to be able to you know do this particular kind of thing

56
00:03:11,950 --> 00:03:15,590
and that in your kind of feature request that you have ... the

57
00:03:15,590 --> 00:03:18,909
you know ideally the the user stories are SMART

58
00:03:18,909 --> 00:03:22,250
... we've got some good coverage of that in the textbook

59
00:03:22,250 --> 00:03:25,549
with ... you know being, them being

60
00:03:25,549 --> 00:03:28,849
specific ... achievable, relevant

61
00:03:28,849 --> 00:03:32,069
... we've got, what's the other thing we've got,

62
00:03:32,580 --> 00:03:35,700
 ... they've got them in a different ..., S. M. A., relevant and time boxed

63
00:03:35,700 --> 00:03:40,310
... so you know this is, I mean this is another sort of knack that comes over time

64
00:03:40,310 --> 00:03:43,730
is sort of working out these - these user stories I think ...

65
00:03:43,730 --> 00:03:47,260
... often we have a particular trouble in our projects with ... time boxing

66
00:03:47,260 --> 00:03:47,580
them

67
00:03:47,580 --> 00:03:50,650
things often do get a bit ... a bit open-ended

68
00:03:50,650 --> 00:03:54,090
... but yes, definitely do read chapter seven

69
00:03:54,090 --> 00:03:57,870
again ... particularly ... I think ... in some ways I would almost argue that this is -

70
00:03:57,870 --> 00:04:01,180
this is sort of the entry point. I mean there's ...

71
00:04:01,180 --> 00:04:04,409
in some ways to understand Cucumber perhaps you needs...

72
00:04:04,409 --> 00:04:08,349
you know a degree of understanding of you know different kinds of testing and

73
00:04:08,349 --> 00:04:12,080
Ruby and so on but whenever you're sort of starting a new project this is - this is the

74
00:04:12,080 --> 00:04:13,080
place where you come in.

75
00:04:13,080 --> 00:04:17,209
You come in with the user stories ... you don't come in with writing some Ruby code, you come

76
00:04:17,209 --> 00:04:17,709
in with

77
00:04:17,709 --> 00:04:21,150
some smart user stories and so that's you know at the top level

78
00:04:21,150 --> 00:04:25,410
... that's why we're starting - that's why we're starting here ... so

79
00:04:25,410 --> 00:04:28,419
you know what's ... not a user story you've got

80
00:04:28,419 --> 00:04:31,479
... little technical issues and chores I'd be tempted to wrap those two together

81
00:04:31,990 --> 00:04:35,389
you've got bugs, getting documentation done although

82
00:04:35,389 --> 00:04:38,410
you know self documenting code that's important and

83
00:04:38,970 --> 00:04:42,979
... features without business needs I mean that this is you know ... the key thing

84
00:04:42,979 --> 00:04:45,810
you know and there's many things that have to be done to move forward and get

85
00:04:45,810 --> 00:04:46,360
something out

86
00:04:46,360 --> 00:04:50,979
the key thing is that you ... you know you have to work out which are those

87
00:04:50,979 --> 00:04:54,970
... small set of things that are going to really meet business needs ...

88
00:04:54,970 --> 00:04:58,720
and then work out from those the even smaller set that's going to be your MVP or your

89
00:04:58,720 --> 00:04:59,300
Minimum

90
00:04:59,300 --> 00:05:02,960
Viable Product but so the ...

91
00:05:04,229 --> 00:05:07,759
the five whys there's a technique that I think Dave already presented to you, this is a little bit of a

92
00:05:07,759 --> 00:05:08,750
refresher

93
00:05:08,750 --> 00:05:13,060
for - for - for everyone ... you know the user stories should be able to reach a

94
00:05:13,060 --> 00:05:16,610
you know a solid business value in five whys.  So for example we've got a different user story here

95
00:05:16,610 --> 00:05:20,639
in order to display my products as an online retailer I want to have a catalog

96
00:05:20,639 --> 00:05:25,410
on my website and so we might ask ... why do you want to include the catalogue on your web

97
00:05:25,410 --> 00:05:26,080
site

98
00:05:26,080 --> 00:05:29,770
... and the answer is so we can - this customer can see all the varieties of the products.

99
00:05:29,770 --> 00:05:33,160
... and why should the customer see all the varieties of the products?

100
00:05:33,160 --> 00:05:37,400
... and if we move down there it's to have a bigger choice and why do you want them to have a bigger choice?

101
00:05:37,930 --> 00:05:41,020
They're more likely to buy if they .. if they find what they want

102
00:05:41,020 --> 00:05:44,320
and what do you want them to buy ... why do you want them to buy anything? So I can make money.

103
00:05:44,320 --> 00:05:47,870
Why do you want to make money? Then anyone should be able to answer this.  Although of course you know that that

104
00:05:47,870 --> 00:05:48,430
the …

105
00:05:48,430 --> 00:05:51,720
we shouldn't exclude the idea: is money the root of all evil? I'm not sure

106
00:05:51,720 --> 00:05:55,160
... it maybe that you know the project that you're working on is not specifically

107
00:05:55,160 --> 00:05:58,300
you know about commercial goals but being clear about all the different levels

108
00:05:58,300 --> 00:05:58,940
here

109
00:05:58,940 --> 00:06:02,030
and also all the implicit assumptions here ...

110
00:06:02,030 --> 00:06:05,960
is it the case that necessarily an extraordinarily wide choice

111
00:06:05,960 --> 00:06:09,039
... you know ... it makes people more likely to buy? In some cases

112
00:06:09,039 --> 00:06:12,509
actually narrowing the choice ... you know I think there's some evidence to show ...

113
00:06:12,509 --> 00:06:16,319
that ... depending upon how you know if you present some people with the

114
00:06:16,319 --> 00:06:20,310
three options ... they're more likely to ... choose one than if you present them

115
00:06:20,310 --> 00:06:23,910
with twenty five options they may just run away in fear like woo oo oo .. anyhow

116
00:06:23,910 --> 00:06:27,810
but ... the important thing with any of, with this whole process of generating user

117
00:06:27,810 --> 00:06:29,660
stories and using three by

118
00:06:29,660 --> 00:06:32,889
five cards which are mentioned in the course are to uncover the assumptions

119
00:06:32,889 --> 00:06:36,530
about what's needed and why do we think ... things are the case

120
00:06:36,530 --> 00:06:39,580
and you know whether you ... the I guess ...

121
00:06:39,580 --> 00:06:42,789
you know ... with the team in a single office or you know in relative

122
00:06:43,580 --> 00:06:47,389
good physical proximity ... there are more chances

123
00:06:47,389 --> 00:06:50,389
for meeting over the water cooler to - or in main

124
00:06:50,389 --> 00:06:53,949
meetings - to work out what's what's going on it becomes

125
00:06:53,949 --> 00:06:57,110
even more important in a distributed team to

126
00:06:57,110 --> 00:07:00,560
uncover the different assumptions about why you're

127
00:07:00,560 --> 00:07:04,650
developing anything that you think is gonna - you know - have some value to the

128
00:07:04,650 --> 00:07:07,949
end users of your system ... so

129
00:07:07,949 --> 00:07:10,960
simplicity is just I mean it's so important

130
00:07:10,960 --> 00:07:14,419
up and down every level from the user story to the unit test

131
00:07:14,419 --> 00:07:18,039
... you know everywhere you can inject simplicity and remove complexity

132
00:07:18,039 --> 00:07:21,690
that's the way to go so if you've got sort of a higher more complex feature

133
00:07:21,690 --> 00:07:26,289
break that into individual stories - and be very specific and avoid

134
00:07:26,289 --> 00:07:29,419
vague business needs ... they've got some good examples there of ....

135
00:07:30,889 --> 00:07:34,830
... you know ... someone being unspecific you know - from - from Dave and Armando

136
00:07:34,830 --> 00:07:37,900
the you know the feature the user can search for movie is rather vague

137
00:07:37,900 --> 00:07:41,599
but the user can search for movie by title is more specific.  A simple example there.

138
00:07:42,110 --> 00:07:45,460
... so you know there are gonna be sometimes

139
00:07:45,460 --> 00:07:49,349
... just difficult things that you don't know how to turn into a

140
00:07:49,349 --> 00:07:52,770
user story. Every situation is different ... just

141
00:07:52,770 --> 00:07:55,940
you know break it down into components ... and

142
00:07:55,940 --> 00:07:59,069
keep asking yourself is this addressing some - some key level

143
00:07:59,069 --> 00:08:02,900
business need and you know what are the assumptions that we're making here and

144
00:08:02,900 --> 00:08:05,560
ideally this should be a dialogue between you

145
00:08:05,560 --> 00:08:09,169
and everybody involved in the project; all the different stakeholders ... and you know

146
00:08:09,169 --> 00:08:10,220
we'll talk more

147
00:08:10,220 --> 00:08:13,430
... next - next week about the different kinds of

148
00:08:13,430 --> 00:08:17,310
online frameworks that you can use to help manage development of user stories

149
00:08:17,310 --> 00:08:21,349
in ... the distributed team, but this YAGNI principle

150
00:08:21,349 --> 00:08:24,430
which I often have trouble remembering. You Ain't Gonna Need It. I mean this is this is the key thing

151
00:08:24,430 --> 00:08:26,919
that can often happen when you get a group of developers together and they say "wouldn't this be cool"

152
00:08:26,919 --> 00:08:28,910
and "this would be cool" and - you know a lot of things

153
00:08:28,910 --> 00:08:32,140
get created and the problem is

154
00:08:32,140 --> 00:08:35,760
really that complexity is the killer for every additional feature

155
00:08:35,760 --> 00:08:39,300
there's an additional ... kind of "N" plus one interactions with

156
00:08:39,300 --> 00:08:43,099
all of the other existing features and ... you know so you'd like simplicity

157
00:08:43,099 --> 00:08:44,290
modularity

158
00:08:44,290 --> 00:08:47,970
only building the very very very very smallest subset of the things that you

159
00:08:47,970 --> 00:08:48,580
need

160
00:08:48,580 --> 00:08:52,750
really is the way forward ... so that's user stories and ... we'll see them

161
00:08:52,750 --> 00:08:56,130
connecting up ... with ...

162
00:08:56,130 --> 00:08:59,950
acceptance tests ... very shortly after we've had a quick detour into chores

163
00:08:59,950 --> 00:09:00,589
alright bye for now

