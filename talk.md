###What I learned learning programming

After working as a community manager for over 5 years I missed 'making stuff' and I started learning Rails and Ruby in August last year. Now that I'm confident with CSS, Less and Rails, I want to share my learnings when it comes to learning and teaching programming. As a newbie to programming I'm spending my weekends learning about technologies like CoffeeScript or Python, or about version control, libraries, gems and generally useful resources out there. I genuinely believe that teaching skyrockets one's own learning curve and I would encourage everyone to start coaching beginners to programming, even if you consider yourself to be a beginner still.
In my talk I'd like to share what I've learned, being confident with Rails after starting learning programming in the evening hours August last year. I'd like to offer you coders a different view on what is maybe too self-evident for you to adapt your vocabulary. I strongly believe teaching makes you a better programmer and (in my case) teaching makes your own learning curve go through the roof.

####Why?
Because it's awesome to help people  
Because teaching will accelerate your own learning. They will ask you things you'd otherwise take for granted. And you'll need to be able to actually explain it.  

Hi. My name is Floor Drees. Two years ago I exchanged Rotterdam for Vienna to work at a startup that does 'stuff' with reviews and is **not** called Yelp. I had worked as a community manager for agencies and startups for 5 years, and here I'd make a little step up, becoming head of community management (notice the 'head of'? That addition is not there for swag reasons alone, I actually managed a team). Partly because I had been doing more or less the same thing over and over for years, ie community management, because I wanted to 'make stuff' again (I have a background in design) and because I worked closely together with the developers there, I decided I wanted to pick up on something new. That something new was learning to program. As this startup's stack used Ruby on Rails, there was no real decision process here on what language I'd be learning. Cool thing is that many of my developer coworkers had coached at Rails Girls events, and I was familiar with their program. I started going though their courses, in August last year, supported by one of my coworkers. Little later my company supported me to work as a junior developer one day a week, mainly documenting bugs talking to marketing and communication, and actually fixing bugs. 

I organized Rails Girls Rotterdam in January, organizing [Rails Girls The Hague][4] in September, I co-organize the [Ruby user group meetups in Vienna][5] and the [PyLadies workshops in Vienna][6]. I currently work at [Usersnap][7] and spend the little time that is left coaching at Rails Girls events and helping out where I can when it comes to [Rails Girls Summer of Code][8].

I absolutely loved it, BUT... looking back on a year of learning I see things that could have been tackled better. Like:

#####Start with the basics
REALLY learning HTML, Markdown and CSS helps one to create a proper understanding of constructing decent syntax. 
Codecademy fucking rocks and so does Codeschool, so this really shouldn't be a problem. 

#####JavaScript will continue to be hard (better dig into it fast)
JavaScript is just hard, the syntax is weird and complicated and it doesn't 'read' like HTML or Ruby. 
It was also hard not be fooled by CoffeeScript's popularity and end up figuring out which failing CoffeeScript line corresponded with which JavaScript line. 

#####Don't get started with Bootstrap till you have a decent understanding of CSS (Inspect ALL the elements)
Being able to create a decent looking website or just know how a website is build up by looking at it, really boosts your confidence. Plus, playing around with HTML and CSS allows you to view your changes in the browser instantly, learning while you go. My mentor would let me inspect everything on a page, even if I was basically begging for the answer, after 3 hours of coding. Yes, it would upset me, but looking back it's one of the most valuable lessons I've learned. 
Notice that your student likes what he/she sees? Then it's time to dive into stuff like Less. Else, slap a bootstrap on that sucker. 

#####No such thing as the perfect beginners framework. It’s a workflow thing.
The day before my <a href="http://2013.eurucamp.org/">eurucamp</a> talk on the topic of this post, one of the attendees asked me what the perfect framework is for learning Rails (and Ruby). He named a few and I had only heard of one of them. Rails has great (beginner friendly) documentation, most other frameworks don't, so let's just stick to that. In the end I think it's really about teaching a good workflow (preferably test driven from the first moment on) with version control and documenting are fully integrated.

#####Nobody cares about your favorite editor. Or os.
Don't expect novice coders to have an opinion on what texteditor they use. If they have already worked with the one they just opened for a while, don't start to bash their software right away (unless it's something like Smultron of course). They're comfortable with using it and that's great. They need to feel comfortable, you want them to feel confident while writing code. Don't promote Emacs/Vim/Sublime/what-have-you as the best editor ever, cause it's not. The best editor ever is whatever you are comfortable with using. 
However, if your student has never installed a texteditor before, then go ahead and introduce them to your favorite as he/she won't be confused with the different layouts when you two are pair programming.

#####BDD rocks for beginners
During a Ruby beginners course I introduced working with cucumber and rspec and thus step definitions building your application up from the ground. Cucumber is great, because it reads like a sales pitch or a feature briefing from/to a client. Everyone that can read English can follow what you're doing there. 

#####Get to learn the lingo
I noticed that listening to RubyTapas, RubyRogues, and the likes - even though I understood fuck of what they're saying 80 percent of the time - really worked for me. I'd pause the podcast everytime I wouldn't know a certain term, look it up on Google and continue. After a while I'd need to pause a whole lot less. 

#####Don't let them fake it till they make it.
We WILL try and trick you into thinking we got it all figured out. Thing is, often times you'll just overwhelm us with your knowledge - and understandably so, you are after all psyched about this stuff - and if anything, that's demotivating. Rather than stopping the hands-on learning you got going on, they'll claim they know all about dependency injections. Now this requires some mind-reading, but if you have the feeling your student is fooling you, just say something like: "yeah and dependency injection in this particular case is great because ...". Else:

- Your student will feel stupid, and give up.
- Your student will Google stuff while you're having your toilet break, and get his or her ideas from questionable sites.
- Your student will starting putting even more evening hours in learning in an attempt to try to get to your level and will burn out as a result.

#####Know when to say: "but you can ignore this for now, we'll get back to it later"
Similar to my previous point, don't overfeed your student. Now I know how hard this is, and it requires getting to know your student and his or her level exactly. Coaching at Rails Girls workshops I often have girls in my group that vary greatly in level of experience. I found that explaining scaffolding, the MVC, how to build up a Gemfile, what gems are (see it as plugins for your WordPress blog) and generally the file structure of a Rails app are things that definitely need explaining. All else can wait. 

#####Learn a different language simultaneously (in the same language)
This might sound a bit controversial, but it isn't really. I started learning Java right after I started learning Ruby. Now bear with me. I started going through a Java reader in German. I figured that working in a German speaking country, it would help learning terminology in German. It obviously didn't. First: there is simply less documentation on bugs and error messages in German. Second: Java is hard enough as it is, just stick to English already! 
Still I'd plea for learning two languages. Later I picked up on Python and it really allowed by to remember the languages' specifics by recognizing the differences and similarities in syntax. 

#####Controlling everything from the Terminal makes you feel like you're in the fucking matrix
(this is a good thing)
Get your student(s) familiar with the terminal as soon as possible. As soon as I started using the terminal to create my folders even for non-programming related projects, I started using version control for basically everything and I wouldn't break my workflow anymore when I needed to test stuff or push changes. I'd be in the terminal already.

#####Find something they can teach you
You can't believe how great it feels for your student if they can do something in return for all the hours you put in. Maybe they are good at copywriting, or design, or cooking, and they can teach you something in return. 

#####Don’t use the words “it’s super easy” when it’s really not.
Developers saying that something is 'super easy' while to you it looks like the hardest thing in the world. I understand it though. It's probably the same with me telling my mum over the phone (while being in a busy tram with eager eavesdroppers) how to make something 'fat' in Word... Funny thing with my mum is that she's actually a vivid user of Twitter (follow her on @toosdreef) and Facebook. At one point I figured that explaining her how to open a link I had sent in an email was similar to crafting a new tweet on Tweetdeck. "Just select the link (she thinks clicking it will hide her email inbox forever), copy it, paste it in a new browser tab like you'd use a new tweet field, and hit enter!" Worked. 

###The downs

There is some nasty shit out there, waiting to hit novice coders. Fortunately you can help your student in dealing with this.

#####Help them ignore the people that hate on their parade
I wish I had known I'd need to be ready for lousy jokes from brogrammers. Whenever I shared a code snippet, an excerpt of a book or a ridiculous one-pager I had made, I'd hear hurtful stuff about focussing on 'what women are good at', how much of a hipster language Ruby supposedly is or how I should stick to social media stuff as I was too lightheaded to be a developer. I couldn't really tell these people how hurtful their comments were as they'd then claim they were just joking. Maybe they were, but they were certainly not funny.   

#####Imposter syndrom
If you read Ruby weekly newsletter, or lurk around on the Ruby channel on IRC, you’d assume that all open source projects are ruled by '[critical neckbeard overlords, and that submitting a bug fix or enhancement could possibly result in ego-crushing attack against your person if your code wasn’t good enough][3]'. This is unfortunate as it will make you question your code. Instead, browsing issues and pull requests on GitHub, I soon realized most open source projects aren’t like that, and that most people welcome your contributions, even if it only fixes a typo.

#####Frontend vs Backend
This age-old frontend vs backend discussion is everything but inviting or welcomy. Quit it. On company level (create feature teams!) and in other developer projects. Rather encourage your student or students to aim for a close to allround developer-ship and (only) then specialize in your tools of choice, be it CSS or C.

#####Same goes for PHP bashing

###The ups

Part of the solution in dealing with the ugly bits in out industry, is focussing on the good stuff. Like:   

#####People rock
I wasn't quite prepared to be amazed by people putting a lot of time in making kick-ass tutorials, organizing Rails Girls events and making conferences and user group meetups as inclusive as possible. And: by you guys, who geniunly want to teach us newbies everything you know. 

#####Through Ruby, I have developed a more logical and efficient way of problem solving
Through Ruby (and programming in general), I have developed a more logical and efficient way of problem solving, more of an understanding of folder structures and generally lost any fear to ask questions. If I couldn't figure something out or get something to work, my mentors would encourage me to talk them through the problem. Through what I later found out is called rubber duck debugging - I often got to the root of the problem myself (often I just wasn't in the right folder when running ```bundle install```), without having to turn to the internet for answers. 

#####It's not all dorm rooms and cold pizza
GitHub provides the social component might it otherwise be absent because you're studying by yourself, in the quiet of your bed room. Introducing GitHub as a 'social network for developers' proved to work with the Rails Girls attendees.It's soothing to know there are more people out there.

I hope this - rather personal - post will help you become a better teacher, and a better programmer as a result. 

Happy teaching!



[3]: https://medium.com/i-m-h-o/62a8eaa0ea9
[4]: http://railsgirls.com/thehague
[5]: http://vienna-rb.at
[6]: http://www.meetup.com/PyLadies-Vienna/
[7]: http://usersnap.com
[8]: http://railsgirlssummerofcode.org/