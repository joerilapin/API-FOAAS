# API-FOAAS
API Fuck Off As A Service


FOAAS
Fuck Off As A Service

v2.1.0
Introduction

FOAAS (Fuck Off As A Service) provides a modern, RESTful, scalable solution to the common problem of telling people to fuck off.
API
Content Negotiation

FOAAS will respond to the following 'Accept:' values with appropriate content

    text/plain - Content will be returned as a plain string.
    application/json - Content will be returned as a JSON object { message: 'message', subtitle: 'subtitle' }
        Supports jsonp by including ?callback=?
    text/html - Content will be returned as an HTML page with a twitter bootstrap hero unit, containing the message and the subtitle.
    application/xml - Content will be returned as a XML document.

Operations
Path 	Description
/version 	Will return content with the current FOAAS version number.
/operations 	Will return a JSON list of operations with names and fields. Note: JSON Only
/anyway/:company/:from	Will return content of the form 'Who the fuck are you anyway, :company, why are you stirring up so much trouble, and, who pays you? - :from'
/asshole/:from	Will return content of the form 'Fuck you, asshole. - :from'
/awesome/:from	Will return content of the form 'This is Fucking Awesome. - :from'
/back/:name/:from	Will return content of the form ':name, back the fuck off. - :from'
/bag/:from	Will return content of the form 'Eat a bag of fucking dicks. - :from'
/ballmer/:name/:company/:from	Will return content of the form 'Fucking :name is a fucking pussy. I'm going to fucking bury that guy, I have done it before, and I will do it again. I'm going to fucking kill :company. - :from'
/bday/:name/:from	Will return content of the form 'Happy Fucking Birthday, :name. - :from'
/because/:from	Will return content of the form 'Why? Because fuck you, that's why. - :from'
/blackadder/:name/:from	Will return content of the form ':name, your head is as empty as a eunuch’s underpants. Fuck off! - :from'
/bm/:name/:from	Will return content of the form 'Bravo mike, :name. - :from'
/bucket/:from	Will return content of the form 'Please choke on a bucket of cocks. - :from'
/bus/:name/:from	Will return content of the form 'Christ on a bendy-bus, :name, don't be such a fucking faff-arse. - :from'
/bye/:from	Will return content of the form 'Fuckity bye! - :from'
/caniuse/:tool/:from	Will return content of the form 'Can you use :tool? Fuck no! - :from'
/chainsaw/:name/:from	Will return content of the form 'Fuck me gently with a chainsaw, :name. Do I look like Mother Teresa? - :from'
/cocksplat/:name/:from	Will return content of the form 'Fuck off :name, you worthless cocksplat - :from'
/cool/:from	Will return content of the form 'Cool story, bro. - :from'
/cup/:from	Will return content of the form 'How about a nice cup of shut the fuck up? - :from'
/dalton/:name/:from	Will return content of the form ':name: A fucking problem solving super-hero. - :from'
/deraadt/:name/:from	Will return content of the form ':name you are being the usual slimy hypocritical asshole... You may have had value ten years ago, but people will see that you don't anymore. - :from'
/diabetes/:from	Will return content of the form 'I'd love to stop and chat to you but I'd rather have type 2 diabetes. - :from'
/donut/:name/:from	Will return content of the form ':name, go and take a flying fuck at a rolling donut. - :from'
/dosomething/:do/:something/:from	Will return content of the form ':do the fucking :something! - :from'
/equity/:name/:from	Will return content of the form 'Equity only? Long hours? Zero Pay? Well :name, just sign me right the fuck up. - :from'
/even/:from	Will return content of the form 'I can't fuckin' even. - :from'
/everyone/:from	Will return content of the form 'Everyone can go and fuck off. - :from'
/everything/:from	Will return content of the form 'Fuck everything. - :from'
/family/:from	Will return content of the form 'Fuck you, your whole family, your pets, and your feces. - :from'
/fascinating/:from	Will return content of the form 'Fascinating story, in what chapter do you shut the fuck up? - :from'
/fewer/:name/:from	Will return content of the form 'Go fuck yourself :name, you'll disappoint fewer people. - :from'
/field/:name/:from/:reference	Will return content of the form 'And :name said unto :from, 'Verily, cast thine eyes upon the field in which I grow my fucks', and :from gave witness unto the field, and saw that it was barren. - :reference'
/flying/:from	Will return content of the form 'I don't give a flying fuck. - :from'
/ftfy/:from	Will return content of the form 'Fuck That, Fuck You - :from'
/fts/:name/:from	Will return content of the form 'Fuck that shit, :name. - :from'
/fyyff/:from	Will return content of the form 'Fuck you, you fucking fuck. - :from'
/gfy/:name/:from	Will return content of the form 'Golf foxtrot yankee, :name. - :from'
/give/:from	Will return content of the form 'I give zero fucks. - :from'
/greed/:noun/:from	Will return content of the form 'The point is, ladies and gentleman, that :noun -- for lack of a better word -- is good. :noun is right. :noun works. :noun clarifies, cuts through, and captures the essence of the evolutionary spirit. :noun, in all of its forms -- :noun for life, for money, for love, knowledge -- has marked the upward surge of mankind. - :from'
/holygrail/:from	Will return content of the form 'I don't want to talk to you, no more, you empty-headed animal, food trough wiper. I fart in your general direction. Your mother was a hamster and your father smelt of elderberries. Now go away or I shall taunt you a second time. - :from'
/horse/:from	Will return content of the form 'Fuck you and the horse you rode in on. - :from'
/idea/:from	Will return content of the form 'That sounds like a fucking great idea! - :from'
/immensity/:from	Will return content of the form 'You can not imagine the immensity of the FUCK I do not give. - :from'
/ing/:name/:from	Will return content of the form 'Fucking fuck off, :name. - :from'
/jinglebells/:from	Will return content of the form 'Fuck you, fuck me, fuck your family. Fuck your father, fuck your mother, fuck you and me. - :from'
/keep/:name/:from	Will return content of the form ':name: Fuck off. And when you get there, fuck off from there too. Then fuck off some more. Keep fucking off until you get back here. Then fuck off again. - :from'
/keepcalm/:reaction/:from	Will return content of the form 'Keep the fuck calm and :reaction! - :from'
/king/:name/:from	Will return content of the form 'Oh fuck off, just really fuck off you total dickface. Christ, :name, you are fucking thick. - :from'
/legend/:name/:from	Will return content of the form ':name, you're a fucking legend. - :from'
/life/:from	Will return content of the form 'Fuck my life. - :from'
/linus/:name/:from	Will return content of the form ':name, there aren't enough swear-words in the English language, so now I'll have to call you perkeleen vittupää just to express my disgust and frustration with this crap. - :from'
/logs/:from	Will return content of the form 'Check your fucking logs! - :from'
/look/:name/:from	Will return content of the form ':name, do I look like I give a fuck? - :from'
/looking/:from	Will return content of the form 'Looking for a fuck to give. - :from'
/madison/:name/:from	Will return content of the form 'What you've just said is one of the most insanely idiotic things I have ever heard, :name. At no point in your rambling, incoherent response were you even close to anything that could be considered a rational thought. Everyone in this room is now dumber for having listened to it. I award you no points :name, and may God have mercy on your soul. - :from'
/maybe/:from	Will return content of the form 'Maybe. Maybe not. Maybe fuck yourself. - :from'
/me/:from	Will return content of the form 'Fuck me. - :from'
/mornin/:from	Will return content of the form 'Happy fuckin' mornin'! - :from'
/no/:from	Will return content of the form 'No fucks given. - :from'
/nugget/:name/:from	Will return content of the form 'Well :name, aren't you a shining example of a rancid fuck-nugget. - :from'
/off/:name/:from	Will return content of the form 'Fuck off, :name. - :from'
/off-with/:behavior/:from	Will return content of the form 'Fuck off with :behavior - :from'
/outside/:name/:from	Will return content of the form ':name, why don't you go outside and play hide-and-go-fuck-yourself? - :from'
/particular/:thing/:from	Will return content of the form 'Fuck this :thing in particular. - :from'
/pink/:from	Will return content of the form 'Well, fuck me pink. - :from'
/problem/:name/:from	Will return content of the form 'What the fuck is your problem :name? - :from'
/programmer/:from	Will return content of the form 'Fuck you, I'm a programmer, bitch! - :from'
/pulp/:language/:from	Will return content of the form ':language, motherfucker, do you speak it? - :from'
/question/:from	Will return content of the form 'To fuck off, or to fuck off (that is not a question) - :from'
/ratsarse/:from	Will return content of the form 'I don't give a rat's arse. - :from'
/retard/:from	Will return content of the form 'You Fucktard! - :from'
/ridiculous/:from	Will return content of the form 'That's fucking ridiculous - :from'
/rockstar/:name/:from	Will return content of the form ':name, you're a fucking Rock Star! - :from'
/rtfm/:from	Will return content of the form 'Read the fucking manual! - :from'
/sake/:from	Will return content of the form 'For Fuck's sake! - :from'
/shakespeare/:name/:from	Will return content of the form ':name, Thou clay-brained guts, thou knotty-pated fool, thou whoreson obscene greasy tallow-catch! - :from'
/shit/:from	Will return content of the form 'Fuck this shit! - :from'
/shutup/:name/:from	Will return content of the form ':name, shut the fuck up. - :from'
/single/:from	Will return content of the form 'Not a single fuck was given. - :from'
/thanks/:from	Will return content of the form 'Fuck you very much. - :from'
/that/:from	Will return content of the form 'Fuck that. - :from'
/think/:name/:from	Will return content of the form ':name, you think I give a fuck? - :from'
/thinking/:name/:from	Will return content of the form ':name, what the fuck were you actually thinking? - :from'
/this/:from	Will return content of the form 'Fuck this. - :from'
/thumbs/:name/:from	Will return content of the form 'Who has two thumbs and doesn't give a fuck? :name. - :from'
/too/:from	Will return content of the form 'Thanks, fuck you too. - :from'
/tucker/:from	Will return content of the form 'Come the fuck in or fuck the fuck off. - :from'
/version	Will return content of the form 'Version 2.1.0 FOAAS'
/waste/:name/:from	Will return content of the form 'I don't waste my fucking time with your bullshit :name! - :from'
/what/:from	Will return content of the form 'What the fuck‽ - :from'
/xmas/:name/:from	Will return content of the form 'Merry Fucking Christmas, :name. - :from'
/yoda/:name/:from	Will return content of the form 'Fuck off, you must, :name. - :from'
/you/:name/:from	Will return content of the form 'Fuck you, :name. - :from'
/zayn/:from	Will return content of the form 'Ask me if I give a motherfuck ?!! - :from'
/zero/:from	Will return content of the form 'Zero, that's the number of fucks I give. - :from'
Filters

Filters are optional output modifiers, and are specified by adding the filter name as query to the HTTP request, e.g. http://foaas.com/off/Tom/Everyone?shoutcloud.

Caveat: All filters internally call the stated external services, and as such the latency and availability of API calls using these features cannot be guaranteed.
Name 	Description
shoutcloud 	Integration with the ShoutCloud service. Please see shoutcloud.io for details.
i18n 	Translation provided by mymemory.translated.net. Specifying ?i18n on its own will attempt to detect your browser language, or you can specify the language to translate to using the ISO 639-1 language code, i.e. ?i18n=es

Filters can be used in combinations, e.g. http://foaas.com/off/Tom/Everyone?shoutcloud&i18n=de
Roadmap

FOAAS will be extended to include the following functionality:

    Random fuck offs (or Fuck Off of the Day), without having to specify the operation (off, you, everyone, donut etc) explicitly

All contributions are very welcome.

Follow @foaas on twitter!

Fork me on github

Created by @TomDionysus

Maintained with loving Profanity by @philip2156, @chris_beckett
