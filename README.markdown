# Rails Israel 2013 (or IsRails 2013) - Tel Aviv

Conference notes by [Andreas Finger](http://mediafinger.com) [@mediafinger](http://www.twitter.com/@mediafinger)

Below you will find links to the talks of [DevConTLV](https://github.com/mediafinger/RailsIsrael#devcontlv-october-2013) which happened on Thursday after RailsIsrael 2013

## The talks I listened to
*  9:10 [Chad Fowler - Disposable Components](https://github.com/mediafinger/RailsIsrael#chad-fowler-chadfowler)
*  9:40 [Yehuda Katz - Off the Menu: Building a Client-Side With Ember and Rails](https://github.com/mediafinger/RailsIsrael#yehuda-katz-wycats)
*  9:55 [Xavier Noria - Numerical Ruby](https://github.com/mediafinger/RailsIsrael#xavier-noria-fxn)
* 10:25 [Konstantin Haase - Sinatra in Six Lines or How to do Crazy Stuff in Ruby](https://github.com/mediafinger/RailsIsrael#konstantin-haase-konstantinhaase)
* 10:55 [Steve Klabnik - The Path to Rails 4.1](https://github.com/mediafinger/RailsIsrael#steve-klabnik-steveklabnik)
* 11:30 [Yehuda Katz - Off the Menu: Building a Client-Side With Ember and Rails](https://github.com/mediafinger/RailsIsrael#yehuda-katz-wycats)
* 12:30 [Case Taintor - Cooking an Omelette with Chef](https://github.com/mediafinger/RailsIsrael#case-taintor-ctaintor)
* 13:00 [Andre Arko - Deathmatch: Bundler vs. Rubygems.org](https://github.com/mediafinger/RailsIsrael#andre-arko-indirect)
* 13:30 [Yonatan Bergman - CREATE • LEARN • DEVELOP](https://github.com/mediafinger/RailsIsrael#yonatan-bergman-yonbergman)
* 14:40 [Emily Stolfo - CREATE • LEARN • DEVELOP](https://github.com/mediafinger/RailsIsrael#emily-stolfo-emstolfo)
* 15:15 [Vitaly Kushner - Cache me if you can](https://github.com/mediafinger/RailsIsrael#vitaly-kushner-vkushner)
* 15:50 [Benjamin Fleischer - YAML, what is it good for](https://github.com/mediafinger/RailsIsrael#benjamin-fleischer-hazula)
* 16:45 [Panel with Chad Fowler](https://github.com/mediafinger/RailsIsrael#panel)
* 17:25 [Lightning talks](https://github.com/mediafinger/RailsIsrael#lightning-talks)

<!--
* 14:40 [XNAME - XTITLE](https://github.com/mediafinger/RailsIsrael#XNAME-XTWITTER)

 -->

***

Before Rails Israel Raphael [@fogelmania](http://www.twitter.com/fogelmania) invited me to take part in the speaker's events (thanks a lot!) - apart from being able to meet some great people that are fun to talk to (and that do a lot of stuff for open source and therefore make life better for all of us), the best part was the surfing session at the beautiful beach of Tel Aviv. A web development conference with actual surfing. Wow :)

***

### Chad Fowler [@chadfowler](http://www.twitter.com/chadfowler)
#### [Disposable Components](http://railsisrael2013.events.co.il/presentations/852-disposable-components)

* How to write code that can become legacy code (in the sense of being used for decades)
* write tiny units/services - that are so tiny they don't need comments or (unit) tests
* never upgrade software or settings on an existing node - just replace the whole instance
* favor measurements over tests (tests as design smell)
* experience the worst case scenario as soon as possible (crash your system to learn)

***

### Yehuda Katz [@wycats](http://www.twitter.com/wycats)
#### [Off the Menu: Building a Client-Side With Ember and Rails](http://railsisrael2013.events.co.il/presentations/849-off-the-menu-building-a-client-side-with-ember-and-rails)

* 15 minutes long: how to not connect a ChromeBook to a projector
* second try: bootstrap a resource with Rails and Ember.js

***

### Xavier Noria [@fxn](http://www.twitter.com/fxn)
#### [Numerical Ruby](http://railsisrael2013.events.co.il/presentations/850-numerical-ruby)

* using rationals in the code and the database to avoid all the rounding issues of floats

***

### Konstantin Haase [@konstantinhaase](http://www.twitter.com/konstantinhaase)
#### [Sinatra in Six Lines or How to do Crazy Stuff in Ruby](http://railsisrael2013.events.co.il/presentations/851-sinatra-in-six-lines-or-how-to-do-crazy-stuff-in-ruby)

* some obfuscated code

***

### Steve Klabnik [@steveklabnik](http://www.twitter.com/steveklabnik)
#### [The Path to Rails 4.1](http://railsisrael2013.events.co.il/presentations/992-the-path-to-rails-41)

* about the Rails release process:
* * pick some features
* * write some code
* * random pull-requests get merged
* * magic release (on a not pre-determinded day)

***

### Case Taintor [@ctaintor](http://www.twitter.com/ctaintor)
#### [Cooking an Omelette with Chef](http://railsisrael2013.events.co.il/presentations/861-cooking-an-omelette-with-chef)

* chef-solo for simpler config - chef-client + chef-server for extra features
* for reliable versioning include exact versions in the cookbooks (e.g. with Berkshelf)

***

### Andre Arko [@indirect](http://www.twitter.com/indirect)
#### [Deathmatch: Bundler vs. Rubygems.org](http://railsisrael2013.events.co.il/presentations/865-deathmatch-bundler-vs-rubygemsorg)

* learnings from the unintentional DOS attack bundler 1.1 enacted on rubygems.org one VP
* measure intensively, in particular if you provide a service for large amounts of users
* get your application threaded (e.g. with puma) - also to avoid heroku's random access trizillin dyno usage
* monitor everything (e.g. librato > papertrail) to react on unusable behaviour, high load...
* measure response time from the outside - to get reliable numbers

***

### Yonatan Bergman [@yonbergman](http://www.twitter.com/yonbergman)
#### [CREATE • LEARN • DEVELOP](http://railsisrael2013.events.co.il/presentations/860-create--learn--develop)

* passion projects

***

### Emily Stolfo [@emstolfo](http://www.twitter.com/emstolfo)
#### [API Design for Gem Authors (and Users)](http://railsisrael2013.events.co.il/presentations/870-api-design-for-gem-authors-and-users)

* If you publish open source, you have to do keep DX in mind (API, documentation, clarity, good design)
* DX is UX for developers: Developers eXperience
* use semantic versioning
* keep an open conversation with your users
* Consistency
* Simplicity
* Mapping
* keep private things private - and keep as much private as possible

***

### Vitaly Kushner [@vkushner](http://www.twitter.com/vkushner)
#### [Cache me if you can](http://railsisrael2013.events.co.il/presentations/986-cache-me-if-you-can)

* First make sure your app is fast enough that nothing crashes without any caching
* Caching with Rails 4

***

### Benjamin Fleischer [@hazula](http://www.twitter.com/hazula)
#### [YAML, what is it good for?](http://railsisrael2013.events.co.il/presentations/868-yaml-what-is-it-good-for)

* comparison between JSON and YAML (JSON is included in YAML)
* YAML feature set
* YAML issues, in particular slow development of YAML 2.0

***

## Panel
with Erez Dickman, Uri Nativ, Dotan Nahum, Hadar Cohen and Chad Fowler

***

## Lightning talks

#### Andre Arko [@indirect](http://www.twitter.com/indirect)
[You don't know bundler](http://railsisrael2013.events.co.il/presentations/1039-you-dont-know-bundler)

#### Krzysztof Knapik [@knapo](http://www.twitter.com/knapo)
[mongodb + mail queue + rails ? Yes!](http://railsisrael2013.events.co.il/presentations/869-mongodb--mail-queue--rails--yes)

#### Assaf Feldman [@assaf_fel](http://www.twitter.com/assaf_fel)
[Heroku to EC2 : Notes From The Road](http://railsisrael2013.events.co.il/presentations/987-heroku-to-ec2--notes-from-the-road)

#### Boris Dinkevich [@BorisDinkevich](http://www.twitter.com/BorisDinkevich)
[Sharing the Environment with Vagrant]()

#### Amr Tamimi [@amrnt](http://www.twitter.com/amrnt)
[How do I Really Use Rails](http://railsisrael2013.events.co.il/presentations/1024-how-do-i-really-use-rails)

#### David Paluy [@dpaluy](http://www.twitter.com/dpaluy)
[Tools to help you better understand other/your code](http://railsisrael2013.events.co.il/presentations/988-tools-to-help-you-better-understand-otheryour-code)

#### Erez Dickman [@erezdickman](http://www.twitter.com/erezdickman)
[ok glass, now what?]()

#### Nitzan Aviram [@nitzanadsmarket](http://www.twitter.com/nitzanadsmarket)
[DRYing up Controllers and Views](http://railsisrael2013.events.co.il/presentations/1043-drying-up-controllers-and-views)

#### Susanne Dewein [@bibibienenstich](http://www.twitter.com/bibibienenstich)
[After Rails Girls Summer of Code - What Now?](http://railsisrael2013.events.co.il/presentations/1041-after-rails-girls-summer-of-code-what-now)

#### João M. D. Moura [@joaomdmoura](http://www.twitter.com/joaomdmoura)
[Rankings, You're Doing it Wrong](http://railsisrael2013.events.co.il/presentations/993-rankings-youre-doing-it-wrong)

#### Daniel Halabi [@halabidaniel](http://www.twitter.com/halabidaniel)
[A Web Developer's Branding Toolkit]()

***

***

## DevConTLV October 2013

### Konstantin Haase [@konstantinhaase](http://www.twitter.com/konstantinhaase)
#### [Death to Cookies](http://devcon-oct13.events.co.il/presentations/1007-death-to-cookies)

* about cookie (in)security and possible attacks
* about the self-written authentication system TravisCI uses (based on JavaScript)

***

### Vicent Marti [@vmg](http://www.twitter.com/vmg)
#### [My Mom Told Me That git Doesn't Scale](http://devcon-oct13.events.co.il/presentations/1042-my-mom-told-me-that-git-doesnt-scale)

* how to scale git to web-scale
* be a UNIX shop
* don't use Java
* start with Erlang, but remove it from the stack over time
* end up with a Ruby and C stack with 100.000 lines less than before
* don't use the language / technology of the week
* and don't mongo (as is not even a verb)
* just do the simplest thing as possible with the tools you really understand

***

### Alon Eizenman [@aloneiz](http://www.twitter.com/aloneiz)
#### [Continuous Application Delivery and Release Automation](http://devcon-oct13.events.co.il/presentations/1021-continuous-application-delivery-and-release-automation)

* release and publish often

***

### Ofer Ron [@oferron](http://www.twitter.com/oferron)
#### [Introduction to data science](http://devcon-oct13.events.co.il/presentations/1014-introduction-to-data-science)

* how to recommend something to your site's users - or how data scientists work
* examine the data (you might need to transform it into a usable form)
* perform basic analysis
* formulate a hypothesis
* validate your hypothesis
* productize

***

### Andre Arko [@indirect](http://www.twitter.com/indirect)
#### [The Iceberg of Webdev: Choices You Didn't Realize You Were Making](http://devcon-oct13.events.co.il/presentations/1037-the-iceberg-of-webdev-choices-you-didnt-realize-you-were-making)

* production is fundamentally systemically different from development
* measure, but choose the right metrics (e.g. don't rely on averages, at least add median and 95% percentile)
* add alerts to get notified when something changes
* if your routing or load balancing has issues - will you notice that (it's not in your app logs)
* request time is just a fraction of the end-to-end response time
* use a server in a differnt data-center to make requests to your app - measure them - alert on them
* is your data storage system perfectly configured - even for edge cases?
* trust no one - and check if the documentation is right

***

### Aviran Mordo [@aviranm](http://www.twitter.com/aviranm)
#### [Red Alert Or False Alarm - Lessons Learned Monitoring Production](http://devcon-oct13.events.co.il/presentations/1016-red-alert-or-false-alarm-lessons-learned-monitoring-production)

* pros and cons of different ways of monitoring your app and your servers
* logs and log collection
* self reporting system for business and system exception

***

### David Bonilla [@david_bonilla](http://www.twitter.com/david_bonilla)
#### [How To Do Kick-Ass Software Development](http://devcon-oct13.events.co.il/presentations/1013-how-to-do-kick-ass-software-development)

* how Atlassian works together

***

### Alex Koppel [@arsduo](http://www.twitter.com/arsduo)
#### [Designing for a Hostile Environment](http://devcon-oct13.events.co.il/presentations/1035-designing-for-a-hostile-environment)

* log everything and store it in a way that allows to extract information flexible and quickly (e.g. Graylog2)
* think about your update mechanism - and (non)-technical restrictions
* keep bad/no connectivity in mind
* develop for your audience - this may result in decisions towards smaller scale and specialized requirements

***

### João M. D. Moura [@joaomdmoura](http://www.twitter.com/joaomdmoura)
#### [Rankings, You're Doing it Wrong](http://devcon-oct13.events.co.il/presentations/1009-rankings-youre-doing-it-wrong)

* rankings are gamification
* ranking is ordering and distinguishing
* different ratings: elo, true skill (combination of skill and distrust)
* sigma gem

[Slides at Speaker Deck](https://speakerdeck.com/joaomdmoura/rankings-youre-doing-it-wrong) 


***

### Victor Trakhtenberg [@victortr75](http://www.twitter.com/victortr75)
#### [Swagger - make your REST APIs accessible](http://devcon-oct13.events.co.il/presentations/1010-swagger-make-your-rest-apis-accessible)

* a framework to produce, consume and visualize RESTful APIs
* and a methodology for documentation
* the spec is based on JSON

***

### Ori Hoch [@astupidog](http://www.twitter.com/astupidog)
#### [Optimizing Client-Side Performance in highly dynamic content websites](http://devcon-oct13.events.co.il/presentations/1030-optimizing-client-side-performance-in-highly-dynamic-content-websites)

* various issues of content display at the example of their specific CMS

***

### Yehuda Katz [@wycats](http://www.twitter.com/wycats)
#### [Ember talk]()

***

<!--
### XNAME [@XTWITTER](http://www.twitter.com/XTWITTER)
#### [XTITLE](http://railsisrael2013.events.co.il/presentations/870-api-design-for-gem-authors-and-users)

***
-->
