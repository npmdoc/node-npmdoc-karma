# api documentation for  [karma (v1.5.0)](http://karma-runner.github.io/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma)
#### Spectacular Test Runner for JavaScript.

[![NPM](https://nodei.co/npm/karma.png?downloads=true)](https://www.npmjs.com/package/karma)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-karma_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-karma/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jína",
        "email": "vojta.jina@gmail.com"
    },
    "bin": {
        "karma": "./bin/karma"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma/issues"
    },
    "contributors": [
        {
            "name": "Friedel Ziegelmayer",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "dignifiedquire",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "greenkeeperio-bot",
            "email": "support@greenkeeper.io"
        },
        {
            "name": "Karma Bot",
            "email": "karmarunnerbot@gmail.com"
        },
        {
            "name": "Maksim Ryzhikov",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "Christian Budde Christensen",
            "email": "budde377@gmail.com"
        },
        {
            "name": "taichi",
            "email": "ryushi@gmail.com"
        },
        {
            "name": "Liam Newman",
            "email": "bitwiseman@gmail.com"
        },
        {
            "name": "Wesley Cho",
            "email": "wesley.cho@gmail.com"
        },
        {
            "name": "Todd Wolfson",
            "email": "todd@twolfson.com"
        },
        {
            "name": "Ciro Nunes",
            "email": "ciroanunes@gmail.com"
        },
        {
            "name": "Robo",
            "email": "hop2deep@gmail.com"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Shyam Seshadri",
            "email": "shyamseshadri@gmail.com"
        },
        {
            "name": "Tim Cuthbertson",
            "email": "tim@gfxmonk.net"
        },
        {
            "name": "Pawel Kozlowski",
            "email": "pkozlowski.opensource@gmail.com"
        },
        {
            "name": "Christian Budde Christensen",
            "email": "christi@n-bud.de"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Mourad",
            "email": "mourad@elmaouchi.com"
        },
        {
            "name": "vivganes",
            "email": "vivek@vivekganesan.com"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        },
        {
            "name": "Daniel Compton",
            "email": "desk@danielcompton.net"
        },
        {
            "name": "joshjb84",
            "email": "joshjb84@hotmail.com"
        },
        {
            "name": "Kim Joar Bekkelund",
            "email": "kjbekkelund@gmail.com"
        },
        {
            "name": "Michał Gołębiowski",
            "email": "m.goleb@gmail.com"
        },
        {
            "name": "Andrew Martin",
            "email": "sublimino@gmail.com"
        },
        {
            "name": "Jérémy Judéaux",
            "email": "jeremy.judeaux@volune.net"
        },
        {
            "name": "Brian Ford",
            "email": "btford@umich.edu"
        },
        {
            "name": "Aymeric Beaumet",
            "email": "aymeric@beaumet.me"
        },
        {
            "name": "pavelgj",
            "email": "pavelgj@gmail.com"
        },
        {
            "name": "Marcello Nuccio",
            "email": "marcello.nuccio@gmail.com"
        },
        {
            "name": "sylvain-hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "David Souther",
            "email": "davidsouther@gmail.com"
        },
        {
            "name": "Ilya Volodin",
            "email": "ivolodin@vistaprint.com"
        },
        {
            "name": "Jeff Jewiss",
            "email": "jeffjewiss@gmail.com"
        },
        {
            "name": "Iristyle",
            "email": "Iristyle@github"
        },
        {
            "name": "Daniel Aleksandersen",
            "email": "code@daniel.priv.no"
        },
        {
            "name": "Jonathan Freeman",
            "email": "freethejazz@gmail.com"
        },
        {
            "name": "ngiebel",
            "email": "ngiebel@starkinvestments.com"
        },
        {
            "name": "rdodev",
            "email": "rubenoz@gmail.com"
        },
        {
            "name": "DarthCharles",
            "email": "carlos.darth@gmail.com"
        },
        {
            "name": "Hugues Malphettes",
            "email": "hmalphettes@gmail.com"
        },
        {
            "name": "Sammy Jelin",
            "email": "sjelin@gmail.com"
        },
        {
            "name": "KJ Tsanaktsidis",
            "email": "kjtsanaktsidis@gmail.com"
        },
        {
            "name": "Igor Minar",
            "email": "igor@angularjs.org"
        },
        {
            "name": "Shane Russell",
            "email": "shane1337@gmail.com"
        },
        {
            "name": "Igor Minar",
            "email": "iiminar@gmail.com"
        },
        {
            "name": "Stefan Dragnev",
            "email": "dragnev@telerik.com"
        },
        {
            "name": "Steve Mao",
            "email": "maochenyan@gmail.com"
        },
        {
            "name": "Steve Mao",
            "email": "steve.mao@healthinteract.com.au"
        },
        {
            "name": "Steve Van Opstal",
            "email": "stevevanopstal@gmail.com"
        },
        {
            "name": "Sylvain Hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "Aseem Bansal",
            "email": "aseembansal@live.com"
        },
        {
            "name": "David Pärsson",
            "email": "david@parsson.se"
        },
        {
            "name": "Kevin Huang",
            "email": "kevinziwenhuang@gmail.com"
        },
        {
            "name": "Ethan J. Brown",
            "email": "ethan_j_brown@hotmail.com"
        },
        {
            "name": "Kevin WENNER",
            "email": "kevin.wenner@massmotionmedia.com"
        },
        {
            "name": "Thomas Parisot",
            "email": "thomas@oncle-tom.net"
        },
        {
            "name": "Tom Erik Støwer",
            "email": "tomerik@getkahoot.com"
        },
        {
            "name": "James Ford",
            "email": "jford@psyked.co.uk"
        },
        {
            "name": "Filipe Guerra",
            "email": "alias.mac@gmail.com"
        },
        {
            "name": "Parashuram",
            "email": "code@r.nparashuram.com"
        },
        {
            "name": "James Talmage",
            "email": "james@talmage.io"
        },
        {
            "name": "Pat Tullmann",
            "email": "pt@bebop.co"
        },
        {
            "name": "Luke Page",
            "email": "luke.a.page@gmail.com"
        },
        {
            "name": "Vladimir Starkov",
            "email": "iamstarkov@users.noreply.github.com"
        },
        {
            "name": "PatrickJS",
            "email": "github@gdi2290.com"
        },
        {
            "name": "ChangZhuo Chen",
            "email": "czchen@gmail.com",
            "url": "陳昌倬"
        },
        {
            "name": "comdiv",
            "email": "fagim.sadykov@gmail.com"
        },
        {
            "name": "Bryan Smith",
            "email": "bryanrsmith@gmail.com"
        },
        {
            "name": "Richard Harrington",
            "email": "rwharrington87@gmail.com"
        },
        {
            "name": "Bulat Shakirzyanov",
            "email": "mallluhuct@gmail.com"
        },
        {
            "name": "Roarke Gaskill",
            "email": "roarke.gaskill@gmail.com"
        },
        {
            "name": "Greenkeeper",
            "email": "support@greenkeeper.io"
        },
        {
            "name": "Matt Lewis",
            "email": "matthew.lewis@socialsignin.co.uk"
        },
        {
            "name": "Robin Liang",
            "email": "robin.gnail@gmail.com"
        },
        {
            "name": "Ruben Bridgewater",
            "email": "ruben.bridgewater@fintura.de"
        },
        {
            "name": "johnjbarton",
            "email": "johnjbarton@johnjbarton.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        },
        {
            "name": "Jonas Pommerening",
            "email": "jonas.pommerening@aixigo.de"
        },
        {
            "name": "Jon Bretman",
            "email": "jon.bretman@gmail.com"
        },
        {
            "name": "Jonathan ES Lin",
            "email": "ernsheong@gmail.com"
        },
        {
            "name": "Julian Connor",
            "email": "julian.connor@venmo.com"
        },
        {
            "name": "Jurko Gospodnetić",
            "email": "jurko.gospodnetic@pke.hr"
        },
        {
            "name": "Justin Ridgewell",
            "email": "jridgewell@users.noreply.github.com"
        },
        {
            "name": "KahWee Teng",
            "email": "t@kw.sg"
        },
        {
            "name": "Karl Lindmark",
            "email": "karl.lindmark@ninetwozero.com"
        },
        {
            "name": "Karol Fabjańczuk",
            "email": "karol.fabjanczuk@lemondemon.pl"
        },
        {
            "name": "Karolis Narkevicius",
            "email": "karolis.n@gmail.com"
        },
        {
            "name": "Keats",
            "email": "balthek@gmail.com"
        },
        {
            "name": "Keith Cirkel",
            "email": "github@keithcirkel.co.uk"
        },
        {
            "name": "Kent C. Dodds",
            "email": "kent@doddsfamily.us"
        },
        {
            "name": "Kevin Ortman",
            "email": "kevin_ortman@msn.com"
        },
        {
            "name": "Kostiantyn Kahanskyi",
            "email": "kostiantyn.kahanskyi@googlemail.com"
        },
        {
            "name": "Lenny Urbanowski",
            "email": "lenny@itslennysfault.com"
        },
        {
            "name": "Levi Thomason",
            "email": "me@levithomason.com"
        },
        {
            "name": "Lucas Theisen",
            "email": "lucastheisen@pastdev.com"
        },
        {
            "name": "Lukasz Zatorski",
            "email": "lzatorski@gmail.com"
        },
        {
            "name": "M1xA",
            "email": "AnyCPU@users.noreply.github.com"
        },
        {
            "name": "Magnus Markling",
            "email": "github@markling.com"
        },
        {
            "name": "Manfred Stock",
            "email": "m@nfred.ch"
        },
        {
            "name": "Marko Anastasov",
            "email": "marko@renderedtext.com"
        },
        {
            "name": "Martin Geisler",
            "email": "martin@geisler.net"
        },
        {
            "name": "Martin Jul",
            "email": "martin@mjul.com"
        },
        {
            "name": "Martin Lemanski",
            "email": "martin.lemanski@gmx.at"
        },
        {
            "name": "Martin Probst",
            "email": "martin@probst.io"
        },
        {
            "name": "Matias Niemelä",
            "email": "matias@yearofmoo.com"
        },
        {
            "name": "Matthew Amato",
            "email": "matt.amato@gmail.com"
        },
        {
            "name": "Matthew Machuga",
            "email": "machuga@gmail.com"
        },
        {
            "name": "Matti Paksula",
            "email": "matti.paksula@iki.fi"
        },
        {
            "name": "Mattijs Kneppers",
            "email": "mattijs@arttech.nl"
        },
        {
            "name": "Merott Movahedi",
            "email": "merott@merott.com"
        },
        {
            "name": "Merrick Christensen",
            "email": "merrick.christensen@gmail.com"
        },
        {
            "name": "Michał Gołębiowski",
            "email": "m.goleb@gmail.com"
        },
        {
            "name": "Michał Siwek",
            "email": "mike21@aol.pl"
        },
        {
            "name": "Milan Aleksic",
            "email": "milanaleksic@gmail.com"
        },
        {
            "name": "Milana Stojadinov",
            "email": "mstojadinov@renderedtext.com"
        },
        {
            "name": "Mohamed Eltuhamy",
            "email": "tuhamy@gmail.com"
        },
        {
            "name": "Nathan Hunzaker",
            "email": "nate.hunzaker@gmail.com"
        },
        {
            "name": "Nick Carter",
            "email": "thynctank@thynctank.com"
        },
        {
            "name": "Nick Payne",
            "email": "nick@kurai.co.uk"
        },
        {
            "name": "Nick Williams",
            "email": "mr.nicksta@gmail.com"
        },
        {
            "name": "Nico Jansen",
            "email": "jansennico@gmail.com"
        },
        {
            "name": "Nicolas Artman",
            "email": "nicolasartman@users.noreply.github.com"
        },
        {
            "name": "Nicolas Ferrero",
            "email": "ferrero.nicolas@gmail.com"
        },
        {
            "name": "Nish",
            "email": "nishantpatel611@gmail.com"
        },
        {
            "name": "Nuno Job",
            "email": "nunojobpinto@gmail.com"
        },
        {
            "name": "Oleg Gomozov",
            "email": "blackswanny@gmail.com"
        },
        {
            "name": "Olivier Yiptong",
            "email": "olivier@olivieryiptong.com"
        },
        {
            "name": "OniOni",
            "email": "mathieu.c.sabourin@gmail.com"
        },
        {
            "name": "OpenShift guest",
            "email": "mrpatan@gmail.com"
        },
        {
            "name": "Parashuram",
            "email": "code@nparashuram.com"
        },
        {
            "name": "Pascal Hartig",
            "email": "phartig@rdrei.net"
        },
        {
            "name": "Patrick Lussan",
            "email": "patrick.lussan@componize.com"
        },
        {
            "name": "Patrick Neschkudla",
            "email": "neschkudla@gmail.com"
        },
        {
            "name": "Patrik Henningsson",
            "email": "patrik.henningsson@gmail.com"
        },
        {
            "name": "Pedro Araujo",
            "email": "pedrotcaraujo@gmail.com"
        },
        {
            "name": "Pete Bacon Darwin",
            "email": "pete@bacondarwin.com"
        },
        {
            "name": "Pete Swan",
            "email": "pete@indabamusic.com"
        },
        {
            "name": "Peter Halliday",
            "email": "pghalliday@gmail.com"
        },
        {
            "name": "Peter McAlpine",
            "email": "peter.mcalpine@arcticwolf.com"
        },
        {
            "name": "Peter Yates",
            "email": "pd.yates@gmail.com"
        },
        {
            "name": "Philip Harrison",
            "email": "philip@mailharrison.com"
        },
        {
            "name": "Rafal Lindemann",
            "email": "rl@stamina.pl"
        },
        {
            "name": "Remy Sharp",
            "email": "remy@remysharp.com"
        },
        {
            "name": "Richard Herrera",
            "email": "richard.herrera@nfl.com"
        },
        {
            "name": "Roarke Gaskill",
            "email": "rgaskill@nexvex.com"
        },
        {
            "name": "Rob Cherry",
            "email": "rcherry@reverbnation.com"
        },
        {
            "name": "Rob Dodson",
            "email": "lets.email.rob@gmail.com"
        },
        {
            "name": "Rémi",
            "email": "r3mi@users.sourceforge.net"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        },
        {
            "name": "Sam Rawlins",
            "email": "sam.rawlins@gmail.com"
        },
        {
            "name": "Sam Rawlins",
            "email": "srawlins@google.com"
        },
        {
            "name": "Samuel Marks",
            "email": "samuelmarks@gmail.com"
        },
        {
            "name": "Saugat Acharya",
            "email": "mesaugat@gmail.com"
        },
        {
            "name": "Schmulik Raskin",
            "email": "schmuli@gmail.com"
        },
        {
            "name": "Sergey Kruk",
            "email": "sergey.kruk@gmail.com"
        },
        {
            "name": "Sergey Simonchik",
            "email": "sergey.simonchik@jetbrains.com"
        },
        {
            "name": "Seth Rhodes",
            "email": "seth@thinkpixbit.com"
        },
        {
            "name": "Shahar Mor",
            "email": "shaharmor1@gmail.com"
        },
        {
            "name": "Shane Osbourne",
            "email": "shane.osbourne8@gmail.com"
        },
        {
            "name": "Simen Bekkhus",
            "email": "sbekkhus91@gmail.com"
        },
        {
            "name": "Simone Gentili",
            "email": "sensorario@gmail.com"
        },
        {
            "name": "Slava Kotiya",
            "email": "sk@nexttuesday.de"
        },
        {
            "name": "Sophie Cooper",
            "email": "scooper91@users.noreply.github.com"
        },
        {
            "name": "Stephen Hazleton",
            "email": "shazleto@gmail.com"
        },
        {
            "name": "Stuart Memo",
            "email": "stuartmemo@gmail.com"
        },
        {
            "name": "Taylor Buley",
            "email": "buley@outlook.com"
        },
        {
            "name": "Taylor Hakes",
            "email": "taylor.hakes@gmail.com"
        },
        {
            "name": "Terin Stock",
            "email": "terinjokes@gmail.com"
        },
        {
            "name": "Thai Pangsakulyanont @ Taskworld",
            "email": "thai.p@taskworld.com"
        },
        {
            "name": "Thomas Parisot",
            "email": "thomas.parisot@bbc.co.uk"
        },
        {
            "name": "Tim Olshansky",
            "email": "tim.olshansky@gmail.com"
        },
        {
            "name": "Timo Tijhof",
            "email": "krinklemail@gmail.com"
        },
        {
            "name": "Tom MacWright",
            "email": "tom@macwright.org"
        },
        {
            "name": "TrevDev",
            "email": "trevor@kareo.com"
        },
        {
            "name": "Tyler Akins",
            "email": "fidian@rumkin.com"
        },
        {
            "name": "Vasily Ostanin",
            "email": "bazilio91@gmail.com"
        },
        {
            "name": "Veronica Lynn",
            "email": "veronica.lynn@redjack.com"
        },
        {
            "name": "Vincent Taverna",
            "email": "vinnymac@gmail.com"
        },
        {
            "name": "Vitor Buzinaro",
            "email": "funny.hc@gmail.com"
        },
        {
            "name": "Vivek Ganesan",
            "email": "caliberoviv@gmail.com"
        },
        {
            "name": "Volune",
            "email": "jeremy.judeaux@volune.net"
        },
        {
            "name": "Vova Bilonenko",
            "email": "bilonenko.v@gmail.com"
        },
        {
            "name": "Wizek",
            "email": "123.wizek@gmail.com"
        },
        {
            "name": "Yaniv Efraim",
            "email": "yaniv.efraim@gmail.com"
        },
        {
            "name": "Yi Wang",
            "email": "e@yi-wang.me"
        },
        {
            "name": "u812",
            "email": "0u812@github.com"
        },
        {
            "name": "Zhang zhengzheng",
            "email": "code@tychio.net"
        },
        {
            "name": "adamnation",
            "email": "arowe@illumina.com"
        },
        {
            "name": "ahaurw01",
            "email": "ahaurwitz@gmail.com"
        },
        {
            "name": "ashaffer",
            "email": "darawk@gmail.com"
        },
        {
            "name": "coderaiser",
            "email": "mnemonic.enemy@gmail.com"
        },
        {
            "name": "compact",
            "email": "compact@users.noreply.github.com"
        },
        {
            "name": "coridrew",
            "email": "coridrew@gmail.com"
        },
        {
            "name": "cy6erskunk",
            "email": "cyberskunk@gmail.com"
        },
        {
            "name": "david-garcia-nete",
            "email": "david.garcia.nete@gmail.com"
        },
        {
            "name": "deepak1556",
            "email": "hop2deep@gmail.com"
        },
        {
            "name": "dorey",
            "email": "dorey415@gmail.com"
        },
        {
            "name": "grifball",
            "email": "scottgriffy@gmail.com"
        },
        {
            "name": "hrgdavor",
            "email": "hrgdavor@gmail.com"
        },
        {
            "name": "ianjobling",
            "email": "ijobling@codio.com"
        },
        {
            "name": "inf3rno",
            "email": "laszlo.janszky@gmail.com"
        },
        {
            "name": "jjoos",
            "email": "jan@deelstra.org"
        },
        {
            "name": "lanshunfang",
            "email": "lanshunfang@gmail.com"
        },
        {
            "name": "maik",
            "email": "mauk@gulli.com"
        },
        {
            "name": "mdemo",
            "email": "mengdesen09@qq.com"
        },
        {
            "name": "nathanfaucett",
            "email": "nathanfaucett@gmail.com"
        },
        {
            "name": "pardoman",
            "email": "pardo.medina@gmail.com"
        },
        {
            "name": "thetrevdev",
            "email": "thetrevdev@gmail.com"
        },
        {
            "name": "thorn0",
            "email": "thorn.mailbox@gmail.com"
        },
        {
            "name": "toran billups",
            "email": "toranb@gmail.com"
        },
        {
            "name": "Yvonne Yip",
            "email": "ykyyip@google.com"
        },
        {
            "name": "Aaron Powell",
            "email": "me@aaron-powell.com"
        },
        {
            "name": "Alejandro Mantecon Guillen",
            "email": "alemangui@gmail.com"
        },
        {
            "name": "Alexander Shtuchkin",
            "email": "ashtuchkin@gmail.com"
        },
        {
            "name": "Anders Ekdahl",
            "email": "anders.ekdahl@gmail.com"
        },
        {
            "name": "Anders Janmyr",
            "email": "anders.janmyr@sonymobile.com"
        },
        {
            "name": "Andreas Krummsdorf",
            "email": "a.krummsdorf@litixsoft.de"
        },
        {
            "name": "Andrew Fischer",
            "email": "afischer@shutterfly.com"
        },
        {
            "name": "Andrew Marcinkevičius",
            "email": "andrew.web@ifdattic.com"
        },
        {
            "name": "Andrew Morris",
            "email": "voltrevo@gmail.com"
        },
        {
            "name": "Andy Joslin",
            "email": "andytjoslin@gmail.com"
        },
        {
            "name": "Anton Usmansky",
            "email": "cody0@yandex-team.ru"
        },
        {
            "name": "AugustinLF",
            "email": "augustin.public@gmail.com"
        },
        {
            "name": "AvnerCohen",
            "email": "israbirding@gmail.com"
        },
        {
            "name": "Awad Mackie",
            "email": "firesock.serwalek@gmail.com"
        },
        {
            "name": "Basemm",
            "email": "BAsM.Egy@gmail.com"
        },
        {
            "name": "Benoit Charbonnier",
            "email": "benoit.charbonnier@gmail.com"
        },
        {
            "name": "Bhavesh Kakadiya",
            "email": "bhavesh@superhuman.com"
        },
        {
            "name": "Brady Wied",
            "email": "brady@bswtechconsulting.com"
        },
        {
            "name": "Breno Calazans",
            "email": "breno@vtex.com.br"
        },
        {
            "name": "Brian Donovan",
            "email": "donovan@squareup.com"
        },
        {
            "name": "Brian Donovan",
            "email": "me@brian-donovan.com"
        },
        {
            "name": "Brian M Hunt",
            "email": "brianmhunt@gmail.com"
        },
        {
            "name": "Cagdas Bayram",
            "email": "cbayram@cloudera.com"
        },
        {
            "name": "Carl Goldberg",
            "email": "carlgoldberg1236@gmail.com"
        },
        {
            "name": "Chad Smith",
            "email": "chad@configit.com"
        },
        {
            "name": "Chris",
            "email": "camargo.cac@gmail.com"
        },
        {
            "name": "Chris Chua",
            "email": "chris.sirhc@gmail.com"
        },
        {
            "name": "Chris Dawson",
            "email": "xrdawson@gmail.com"
        },
        {
            "name": "Christian Weiss",
            "email": "cweiss@stripe.com"
        },
        {
            "name": "Christopher Hiller",
            "email": "chiller@badwing.com"
        },
        {
            "name": "Ciro S. Costa",
            "email": "ciro.costa@usp.br"
        },
        {
            "name": "Cyrus Chan",
            "email": "chan1cyrus2@gmail.com"
        },
        {
            "name": "Damien Choizit",
            "email": "damien.choizit@gmail.com"
        },
        {
            "name": "Dan Siwiec",
            "email": "daniel.siwiec@gmail.com"
        },
        {
            "name": "Dan Thareja",
            "email": "danthareja@gmail.com"
        },
        {
            "name": "Danny Croft",
            "email": "danny.croft@yahoo.co.uk"
        },
        {
            "name": "Danny Tuppeny",
            "email": "danny@tuppeny.com"
        },
        {
            "name": "David Jensen",
            "email": "david@frode.(none)",
            "url": "none"
        },
        {
            "name": "David M. Karr",
            "email": "dk068x@att.com"
        },
        {
            "name": "Derek Gould",
            "email": "dgould@birst.com"
        },
        {
            "name": "Derek Schaller",
            "email": "dschaller@lyft.com"
        },
        {
            "name": "Dillon",
            "email": "mdillon@reachmail.com"
        },
        {
            "name": "Dmitrii Abramov",
            "email": "dabramov@yahoo-inc.com"
        },
        {
            "name": "Dmitriy Ryajov",
            "email": "dryajov@gmail.com"
        },
        {
            "name": "Douglas Blumeyer",
            "email": "DougBlumeyer@users.noreply.github.com"
        },
        {
            "name": "Douglas Blumeyer",
            "email": "pair+dblumeyer@vmware.com"
        },
        {
            "name": "Dunja Radulov",
            "email": "dradulov@renderedtext.com"
        },
        {
            "name": "ERt",
            "email": "ert.wroc@gmail.com"
        },
        {
            "name": "Ed Rooth",
            "email": "ed.rooth@rackspace.com"
        },
        {
            "name": "Eddie Monge",
            "email": "eddie@eddiemonge.com"
        },
        {
            "name": "Edward Hutchins",
            "email": "eahutchins@gmail.com"
        },
        {
            "name": "Eldar Jafarov",
            "email": "djkojb@gmail.com"
        },
        {
            "name": "Eric Baer",
            "email": "me@ericbaer.com"
        },
        {
            "name": "Fabian Beuke",
            "email": "mail@beuke.org"
        },
        {
            "name": "Franck Garcia",
            "email": "garcia.franck@gmail.com"
        },
        {
            "name": "Fred Sauer",
            "email": "fredsa@google.com"
        },
        {
            "name": "Frederic Hemberger",
            "email": "mail@frederic-hemberger.de"
        },
        {
            "name": "Fredrik Bonander",
            "email": "carl.fredrik.bonander@gmail.com"
        },
        {
            "name": "Gavin Aiken",
            "email": "gavin@aiken.org.uk"
        },
        {
            "name": "Geert Van Laethem",
            "email": "geert.van.laethem@pandora.be"
        },
        {
            "name": "Georgii Dolzhykov",
            "email": "thorn.mailbox@gmail.com"
        },
        {
            "name": "Greg Thornton",
            "email": "xdissent@me.com"
        },
        {
            "name": "Gregory Cowan",
            "email": "g.cowan@amnzero.nl"
        },
        {
            "name": "Hendrik Purmann",
            "email": "h.purmann@googlemail.com"
        },
        {
            "name": "Homa Wong",
            "email": "homawong@gmail.com"
        },
        {
            "name": "Igor Lima",
            "email": "lima.igorribeiro@gmail.com"
        },
        {
            "name": "Islam Sharabash",
            "email": "islam.sharabash@gmail.com"
        },
        {
            "name": "Jack Tarantino",
            "email": "jacopo.tarantino@gmail.com"
        },
        {
            "name": "Jacob Trimble",
            "email": "modmaker@google.com"
        },
        {
            "name": "Jakub Z",
            "email": "jakzale@gmail.com"
        },
        {
            "name": "James Shore",
            "email": "jshore@jamesshore.com"
        },
        {
            "name": "Jan Molak",
            "email": "jan.molak@smartcodeltd.co.uk"
        },
        {
            "name": "Jeff Froom",
            "email": "jeff@jfroom.com"
        },
        {
            "name": "Jeff Lage",
            "email": "jefflage@me.com"
        },
        {
            "name": "Jeff Yates",
            "email": "jeff.yates@alumni.manchester.ac.uk"
        },
        {
            "name": "Jeremy Axelrod",
            "email": "axelrod.jeremy@gmail.com"
        },
        {
            "name": "Jerry Reptak",
            "email": "jreptak@gmail.com"
        },
        {
            "name": "Jesse M. Holmes",
            "email": "wolfhoundjesse@gmail.com"
        },
        {
            "name": "Joe Lencioni",
            "email": "joe.lencioni@brigade.com"
        },
        {
            "name": "Johannes Gorset",
            "email": "jgorset@gmail.com"
        }
    ],
    "dependencies": {
        "bluebird": "^3.3.0",
        "body-parser": "^1.16.1",
        "chokidar": "^1.4.1",
        "colors": "^1.1.0",
        "combine-lists": "^1.0.0",
        "connect": "^3.6.0",
        "core-js": "^2.2.0",
        "di": "^0.0.1",
        "dom-serialize": "^2.2.0",
        "expand-braces": "^0.1.1",
        "glob": "^7.1.1",
        "graceful-fs": "^4.1.2",
        "http-proxy": "^1.13.0",
        "isbinaryfile": "^3.0.0",
        "lodash": "^3.8.0",
        "log4js": "^0.6.31",
        "mime": "^1.3.4",
        "minimatch": "^3.0.0",
        "optimist": "^0.6.1",
        "qjobs": "^1.1.4",
        "range-parser": "^1.2.0",
        "rimraf": "^2.6.0",
        "safe-buffer": "^5.0.1",
        "socket.io": "1.7.3",
        "source-map": "^0.5.3",
        "tmp": "0.0.31",
        "useragent": "^2.1.12"
    },
    "description": "Spectacular Test Runner for JavaScript.",
    "devDependencies": {
        "LiveScript": "^1.3.0",
        "babel": "^6.23.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-register": "^6.23.0",
        "chai": "^3.3.0",
        "chai-as-promised": "^6.0.0",
        "chai-subset": "^1.2.2",
        "coffee-script": "^1.12.4",
        "cucumber": "^1.2.0",
        "eslint": "^3.15.0",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.2",
        "eslint-plugin-react": "^6.10.0",
        "eslint-plugin-standard": "^2.0.1",
        "grunt": "^1.0.0",
        "grunt-auto-release": "^0.0.7",
        "grunt-browserify": "^5.0.0",
        "grunt-bump": "^0.8.0",
        "grunt-cli": "^1.1.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-conventional-changelog": "^6.0.1",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-cucumberjs": "^0.10.2",
        "grunt-mocha-test": "^0.13.2",
        "grunt-npm": "0.0.2",
        "http2": "^3.3.6",
        "husky": "^0.13.1",
        "jasmine-core": "^2.3.4",
        "json3": "^3.3.2",
        "karma-browserify": "^5.0.1",
        "karma-browserstack-launcher": "^1.0.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "*",
        "karma-coffee-preprocessor": "*",
        "karma-commonjs": "*",
        "karma-coverage": "*",
        "karma-firefox-launcher": "*",
        "karma-growl-reporter": "*",
        "karma-html2js-preprocessor": "*",
        "karma-jasmine": "^1.0.2",
        "karma-junit-reporter": "*",
        "karma-live-preprocessor": "*",
        "karma-mocha": "^1.0.1",
        "karma-mocha-reporter": "^2.0.0",
        "karma-ng-scenario": "*",
        "karma-phantomjs-launcher": "*",
        "karma-qunit": "*",
        "karma-requirejs": "*",
        "karma-sauce-launcher": "*",
        "karma-script-launcher": "^1.0.0",
        "load-grunt-tasks": "^3.1.0",
        "mkdirp": "^0.5.0",
        "mocha": "^3.2.0",
        "mocks": "^0.0.15",
        "phantomjs-prebuilt": "^2.1.3",
        "proxyquire": "^1.7.11",
        "qunitjs": "^2.1.1",
        "requirejs": "^2.1.20",
        "sinon": "^1.17.5",
        "sinon-chai": "^2.7.0",
        "supertest": "^3.0.0",
        "timer-shim": "^0.3.0",
        "validate-commit-msg": "^2.11.1",
        "which": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9c4c14f0400bef2c04c8e8e6bff59371025cc009",
        "tarball": "https://registry.npmjs.org/karma/-/karma-1.5.0.tgz"
    },
    "engines": {
        "node": "0.10 || 0.12 || 4 || 5 || 6 || 7"
    },
    "gitHead": "cc6accd415510c95f62ec254fc7e65900a72f94a",
    "homepage": "http://karma-runner.github.io/",
    "keywords": [
        "karma",
        "spectacular",
        "runner",
        "karma",
        "js",
        "javascript",
        "testing",
        "test",
        "remote",
        "execution"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        }
    ],
    "name": "karma",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma.git"
    },
    "scripts": {
        "appveyor": "npm run build && npm run test:appveyor",
        "build": "grunt build",
        "commitmsg": "validate-commit-msg",
        "init": "rm -rf node_modules/karma && cd node_modules && ln -nsf ../ karma && cd ../",
        "init:windows": "(IF EXIST node_modules\\karma (rmdir node_modules\\karma /S /q)) && npm run link",
        "link": "node --eval \"path=require('path'); require('fs').symlinkSync(path.resolve(__dirname), path.resolve(__dirname, 'node_modules', 'karma'), 'junction')\"",
        "lint": "eslint client/**/*.js common/**/*.js context/**/*.js gruntfile.js wallaby.js lib/**/*.js test/**/*.js static/debug.js",
        "precommit": "npm run lint",
        "test": "grunt test",
        "test:appveyor": "grunt test-appveyor",
        "test:integration": "./scripts/integration-tests.sh",
        "travis": "npm run build && npm test && npm run test:integration",
        "unlink": "node --eval \"require('fs').unlinkSync(require('path').resolve(__dirname, 'node_modules', 'karma'))\""
    },
    "version": "1.5.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma](#apidoc.module.karma)
1.  [function <span class="apidocSignatureSpan">karma.</span>Server (cliOptions, done)](#apidoc.element.karma.Server)
1.  [function <span class="apidocSignatureSpan">karma.</span>Server.super_ ()](#apidoc.element.karma.Server.super_)
1.  [function <span class="apidocSignatureSpan">karma.</span>emitter_wrapper (emitter)](#apidoc.element.karma.emitter_wrapper)
1.  [function <span class="apidocSignatureSpan">karma.</span>file (path, mtime, doNotCache)](#apidoc.element.karma.file)
1.  [function <span class="apidocSignatureSpan">karma.</span>file_list (patterns, excludes, emitter, preprocess, batchInterval)](#apidoc.element.karma.file_list)
1.  [function <span class="apidocSignatureSpan">karma.</span>launcher.Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher)
1.  [function <span class="apidocSignatureSpan">karma.</span>url (path)](#apidoc.element.karma.url)
1.  object <span class="apidocSignatureSpan">karma.</span>Server.prototype
1.  object <span class="apidocSignatureSpan">karma.</span>cli
1.  object <span class="apidocSignatureSpan">karma.</span>completion
1.  object <span class="apidocSignatureSpan">karma.</span>config
1.  object <span class="apidocSignatureSpan">karma.</span>constants
1.  object <span class="apidocSignatureSpan">karma.</span>emitter_wrapper.prototype
1.  object <span class="apidocSignatureSpan">karma.</span>events
1.  object <span class="apidocSignatureSpan">karma.</span>file.prototype
1.  object <span class="apidocSignatureSpan">karma.</span>file_list.prototype
1.  object <span class="apidocSignatureSpan">karma.</span>helper
1.  object <span class="apidocSignatureSpan">karma.</span>init
1.  object <span class="apidocSignatureSpan">karma.</span>launcher
1.  object <span class="apidocSignatureSpan">karma.</span>logger
1.  object <span class="apidocSignatureSpan">karma.</span>plugin
1.  object <span class="apidocSignatureSpan">karma.</span>preprocessor
1.  object <span class="apidocSignatureSpan">karma.</span>reporter
1.  object <span class="apidocSignatureSpan">karma.</span>runner
1.  object <span class="apidocSignatureSpan">karma.</span>server
1.  object <span class="apidocSignatureSpan">karma.</span>stopper
1.  object <span class="apidocSignatureSpan">karma.</span>temp_dir
1.  object <span class="apidocSignatureSpan">karma.</span>url.prototype
1.  object <span class="apidocSignatureSpan">karma.</span>watcher
1.  object <span class="apidocSignatureSpan">karma.</span>web_server
1.  string <span class="apidocSignatureSpan">karma.</span>VERSION

#### [module karma.Server](#apidoc.module.karma.Server)
1.  [function <span class="apidocSignatureSpan">karma.</span>Server (cliOptions, done)](#apidoc.element.karma.Server.Server)
1.  [function <span class="apidocSignatureSpan">karma.Server.</span>start (cliOptions, done)](#apidoc.element.karma.Server.start)
1.  [function <span class="apidocSignatureSpan">karma.Server.</span>super_ ()](#apidoc.element.karma.Server.super_)

#### [module karma.Server.prototype](#apidoc.module.karma.Server.prototype)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_detach (config, done)](#apidoc.element.karma.Server.prototype._detach)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_setUpLoadErrorListener ()](#apidoc.element.karma.Server.prototype._setUpLoadErrorListener)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_start (config, launcher, preprocess, fileList, capturedBrowsers, executor, done)](#apidoc.element.karma.Server.prototype._start)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>get (token)](#apidoc.element.karma.Server.prototype.get)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>refreshFiles ()](#apidoc.element.karma.Server.prototype.refreshFiles)
1.  [function <span class="apidocSignatureSpan">karma.Server.prototype.</span>start ()](#apidoc.element.karma.Server.prototype.start)

#### [module karma.Server.super_](#apidoc.module.karma.Server.super_)
1.  [function <span class="apidocSignatureSpan">karma.Server.</span>super_ ()](#apidoc.element.karma.Server.super_.super_)

#### [module karma.cli](#apidoc.module.karma.cli)
1.  [function <span class="apidocSignatureSpan">karma.cli.</span>argsBeforeDoubleDash (argv)](#apidoc.element.karma.cli.argsBeforeDoubleDash)
1.  [function <span class="apidocSignatureSpan">karma.cli.</span>parseClientArgs (argv)](#apidoc.element.karma.cli.parseClientArgs)
1.  [function <span class="apidocSignatureSpan">karma.cli.</span>process ()](#apidoc.element.karma.cli.process)
1.  [function <span class="apidocSignatureSpan">karma.cli.</span>processArgs (argv, options, fs, path)](#apidoc.element.karma.cli.processArgs)
1.  [function <span class="apidocSignatureSpan">karma.cli.</span>run ()](#apidoc.element.karma.cli.run)

#### [module karma.completion](#apidoc.module.karma.completion)
1.  [function <span class="apidocSignatureSpan">karma.</span>completion ()](#apidoc.element.karma.completion.completion)
1.  [function <span class="apidocSignatureSpan">karma.completion.</span>complete (env)](#apidoc.element.karma.completion.complete)
1.  [function <span class="apidocSignatureSpan">karma.completion.</span>opositeWord (word)](#apidoc.element.karma.completion.opositeWord)
1.  [function <span class="apidocSignatureSpan">karma.completion.</span>sendCompletion (possibleWords, env)](#apidoc.element.karma.completion.sendCompletion)

#### [module karma.config](#apidoc.module.karma.config)
1.  [function <span class="apidocSignatureSpan">karma.config.</span>parseConfig (configFilePath, cliOptions)](#apidoc.element.karma.config.parseConfig)

#### [module karma.emitter_wrapper](#apidoc.module.karma.emitter_wrapper)
1.  [function <span class="apidocSignatureSpan">karma.</span>emitter_wrapper (emitter)](#apidoc.element.karma.emitter_wrapper.emitter_wrapper)

#### [module karma.emitter_wrapper.prototype](#apidoc.module.karma.emitter_wrapper.prototype)
1.  [function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>addListener (event, listener)](#apidoc.element.karma.emitter_wrapper.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>on (event, listener)](#apidoc.element.karma.emitter_wrapper.prototype.on)
1.  [function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>removeAllListeners (event)](#apidoc.element.karma.emitter_wrapper.prototype.removeAllListeners)

#### [module karma.events](#apidoc.module.karma.events)
1.  [function <span class="apidocSignatureSpan">karma.events.</span>EventEmitter ()](#apidoc.element.karma.events.EventEmitter)
1.  [function <span class="apidocSignatureSpan">karma.events.</span>bindAll (object, context)](#apidoc.element.karma.events.bindAll)
1.  [function <span class="apidocSignatureSpan">karma.events.</span>bufferEvents (emitter, eventsToBuffer)](#apidoc.element.karma.events.bufferEvents)

#### [module karma.file](#apidoc.module.karma.file)
1.  [function <span class="apidocSignatureSpan">karma.</span>file (path, mtime, doNotCache)](#apidoc.element.karma.file.file)

#### [module karma.file.prototype](#apidoc.module.karma.file.prototype)
1.  [function <span class="apidocSignatureSpan">karma.file.prototype.</span>toString ()](#apidoc.element.karma.file.prototype.toString)

#### [module karma.file_list](#apidoc.module.karma.file_list)
1.  [function <span class="apidocSignatureSpan">karma.</span>file_list (patterns, excludes, emitter, preprocess, batchInterval)](#apidoc.element.karma.file_list.file_list)

#### [module karma.file_list.prototype](#apidoc.module.karma.file_list.prototype)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_exists (path)](#apidoc.element.karma.file_list.prototype._exists)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_findFile (path, pattern)](#apidoc.element.karma.file_list.prototype._findFile)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isExcluded (path)](#apidoc.element.karma.file_list.prototype._isExcluded)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isIncluded (path)](#apidoc.element.karma.file_list.prototype._isIncluded)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isRefreshing ()](#apidoc.element.karma.file_list.prototype._isRefreshing)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_refresh ()](#apidoc.element.karma.file_list.prototype._refresh)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>addFile (path)](#apidoc.element.karma.file_list.prototype.addFile)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>changeFile (path)](#apidoc.element.karma.file_list.prototype.changeFile)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>refresh ()](#apidoc.element.karma.file_list.prototype.refresh)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>reload (patterns, excludes)](#apidoc.element.karma.file_list.prototype.reload)
1.  [function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>removeFile (path)](#apidoc.element.karma.file_list.prototype.removeFile)

#### [module karma.helper](#apidoc.module.karma.helper)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>arrayRemove (collection, item)](#apidoc.element.karma.helper.arrayRemove)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>browserFullNameToShort (fullName)](#apidoc.element.karma.helper.browserFullNameToShort)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>camelToSnake (camelCase)](#apidoc.element.karma.helper.camelToSnake)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>dashToCamel (dash)](#apidoc.element.karma.helper.dashToCamel)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>defer ()](#apidoc.element.karma.helper.defer)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>formatTimeInterval (time)](#apidoc.element.karma.helper.formatTimeInterval)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isArray ()](#apidoc.element.karma.helper.isArray)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isDefined (value)](#apidoc.element.karma.helper.isDefined)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isFunction (value)](#apidoc.element.karma.helper.isFunction)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isNumber (value)](#apidoc.element.karma.helper.isNumber)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isObject (value)](#apidoc.element.karma.helper.isObject)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isString (value)](#apidoc.element.karma.helper.isString)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>isUrlAbsolute (url)](#apidoc.element.karma.helper.isUrlAbsolute)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>merge ()](#apidoc.element.karma.helper.merge)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>mkdirIfNotExists (directory, done)](#apidoc.element.karma.helper.mkdirIfNotExists)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>mmComparePatternWeights (weight1, weight2)](#apidoc.element.karma.helper.mmComparePatternWeights)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>mmPatternWeight (pattern)](#apidoc.element.karma.helper.mmPatternWeight)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>normalizeWinPath (value)](#apidoc.element.karma.helper.normalizeWinPath)
1.  [function <span class="apidocSignatureSpan">karma.helper.</span>ucFirst (word)](#apidoc.element.karma.helper.ucFirst)

#### [module karma.init](#apidoc.module.karma.init)
1.  [function <span class="apidocSignatureSpan">karma.</span>init (config)](#apidoc.element.karma.init.init)

#### [module karma.launcher](#apidoc.module.karma.launcher)
1.  [function <span class="apidocSignatureSpan">karma.launcher.</span>Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher)

#### [module karma.launcher.Launcher](#apidoc.module.karma.launcher.Launcher)
1.  [function <span class="apidocSignatureSpan">karma.launcher.</span>Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher.Launcher)
1.  [function <span class="apidocSignatureSpan">karma.launcher.Launcher.</span>generateId ()](#apidoc.element.karma.launcher.Launcher.generateId)

#### [module karma.logger](#apidoc.module.karma.logger)
1.  [function <span class="apidocSignatureSpan">karma.logger.</span>create (name, level)](#apidoc.element.karma.logger.create)
1.  [function <span class="apidocSignatureSpan">karma.logger.</span>setup (level, colors, appenders)](#apidoc.element.karma.logger.setup)
1.  [function <span class="apidocSignatureSpan">karma.logger.</span>setupFromConfig (config, appenders)](#apidoc.element.karma.logger.setupFromConfig)

#### [module karma.plugin](#apidoc.module.karma.plugin)
1.  [function <span class="apidocSignatureSpan">karma.plugin.</span>resolve (plugins, emitter)](#apidoc.element.karma.plugin.resolve)

#### [module karma.preprocessor](#apidoc.module.karma.preprocessor)
1.  [function <span class="apidocSignatureSpan">karma.preprocessor.</span>createPreprocessor (config, basePath, injector)](#apidoc.element.karma.preprocessor.createPreprocessor)

#### [module karma.reporter](#apidoc.module.karma.reporter)
1.  [function <span class="apidocSignatureSpan">karma.reporter.</span>createReporters (names, config, emitter, injector)](#apidoc.element.karma.reporter.createReporters)

#### [module karma.runner](#apidoc.module.karma.runner)
1.  [function <span class="apidocSignatureSpan">karma.runner.</span>run (config, done)](#apidoc.element.karma.runner.run)

#### [module karma.server](#apidoc.module.karma.server)
1.  [function <span class="apidocSignatureSpan">karma.server.</span>start (cliOptions, done)](#apidoc.element.karma.server.start)

#### [module karma.stopper](#apidoc.module.karma.stopper)
1.  [function <span class="apidocSignatureSpan">karma.stopper.</span>stop (config, done)](#apidoc.element.karma.stopper.stop)

#### [module karma.temp_dir](#apidoc.module.karma.temp_dir)
1.  [function <span class="apidocSignatureSpan">karma.temp_dir.</span>create (path)](#apidoc.element.karma.temp_dir.create)
1.  [function <span class="apidocSignatureSpan">karma.temp_dir.</span>getPath (suffix)](#apidoc.element.karma.temp_dir.getPath)
1.  [function <span class="apidocSignatureSpan">karma.temp_dir.</span>remove (path, done)](#apidoc.element.karma.temp_dir.remove)

#### [module karma.url](#apidoc.module.karma.url)
1.  [function <span class="apidocSignatureSpan">karma.</span>url (path)](#apidoc.element.karma.url.url)

#### [module karma.url.prototype](#apidoc.module.karma.url.prototype)
1.  [function <span class="apidocSignatureSpan">karma.url.prototype.</span>toString ()](#apidoc.element.karma.url.prototype.toString)

#### [module karma.watcher](#apidoc.module.karma.watcher)
1.  [function <span class="apidocSignatureSpan">karma.watcher.</span>watch (patterns, excludes, fileList, usePolling, emitter)](#apidoc.element.karma.watcher.watch)

#### [module karma.web_server](#apidoc.module.karma.web_server)
1.  [function <span class="apidocSignatureSpan">karma.web_server.</span>create (injector, emitter, fileList)](#apidoc.element.karma.web_server.create)



# <a name="apidoc.module.karma"></a>[module karma](#apidoc.module.karma)

#### <a name="apidoc.element.karma.Server"></a>[function <span class="apidocSignatureSpan">karma.</span>Server (cliOptions, done)](#apidoc.element.karma.Server)
- description and source-code
```javascript
Server = function (cliOptions, done) {
  EventEmitter.call(this)

  logger.setupFromConfig(cliOptions)

  this.log = logger.create()

  this.loadErrors = []

  var config = cfg.parseConfig(cliOptions.configFile, cliOptions)

  var modules = [{
    helper: ['value', helper],
    logger: ['value', logger],
    done: ['value', done || process.exit],
    emitter: ['value', this],
    server: ['value', this],
    launcher: ['type', Launcher],
    config: ['value', config],
    preprocess: ['factory', preprocessor.createPreprocessor],
    fileList: ['type', FileList],
    webServer: ['factory', ws.create],
    socketServer: ['factory', createSocketIoServer],
    executor: ['type', Executor],
    // TODO(vojta): remove
    customFileHandlers: ['value', []],
    // TODO(vojta): remove, once karma-dart does not rely on it
    customScriptTypes: ['value', []],
    reporter: ['factory', reporter.createReporters],
    capturedBrowsers: ['type', BrowserCollection],
    args: ['value', {}],
    timer: ['value', {
      setTimeout: function () {
        return setTimeout.apply(root, arguments)
      },
      clearTimeout: function (timeoutId) {
        clearTimeout(timeoutId)
      }
    }]
  }]

  this._setUpLoadErrorListener()
  // Load the plugins
  modules = modules.concat(plugin.resolve(config.plugins, this))

  this._injector = new di.Injector(modules)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.super_"></a>[function <span class="apidocSignatureSpan">karma.</span>Server.super_ ()](#apidoc.element.karma.Server.super_)
- description and source-code
```javascript
Server.super_ = function () {
  this.bind = bindAllEvents

  this.emitAsync = function (name) {
    // TODO(vojta): allow passing args
    // TODO(vojta): ignore/throw if listener call done() multiple times
    var pending = this.listeners(name).length
    var deferred = helper.defer()
    var done = function () {
      if (!--pending) {
        deferred.resolve()
      }
    }

    this.emit(name, done)

    if (!pending) {
      deferred.resolve()
    }

    return deferred.promise
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.emitter_wrapper"></a>[function <span class="apidocSignatureSpan">karma.</span>emitter_wrapper (emitter)](#apidoc.element.karma.emitter_wrapper)
- description and source-code
```javascript
function EmitterWrapper(emitter) {
  this.listeners = {}
  this.emitter = emitter
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file"></a>[function <span class="apidocSignatureSpan">karma.</span>file (path, mtime, doNotCache)](#apidoc.element.karma.file)
- description and source-code
```javascript
file = function (path, mtime, doNotCache) {
  // used for serving (processed path, eg some/file.coffee -> some/file.coffee.js)
  this.path = path

  // original absolute path, id of the file
  this.originalPath = path

  // where the content is stored (processed)
  this.contentPath = path

  this.mtime = mtime
  this.isUrl = false

  this.doNotCache = _.isUndefined(doNotCache) ? false : doNotCache
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file_list"></a>[function <span class="apidocSignatureSpan">karma.</span>file_list (patterns, excludes, emitter, preprocess, batchInterval)](#apidoc.element.karma.file_list)
- description and source-code
```javascript
file_list = function (patterns, excludes, emitter, preprocess, batchInterval) {
  // Store options
  this._patterns = patterns
  this._excludes = excludes
  this._emitter = emitter
  this._preprocess = Promise.promisify(preprocess)
  this._batchInterval = batchInterval

  // The actual list of files
  this.buckets = new Map()

  // Internal tracker if we are refreshing.
  // When a refresh is triggered this gets set
  // to the promise that 'this._refresh' returns.
  // So we know we are refreshing when this promise
  // is still pending, and we are done when it's either
  // resolved or rejected.
  this._refreshing = Promise.resolve()

  var self = this

  // Emit the 'file_list_modified' event.
  // This function is throttled to the value of 'batchInterval'
  // to avoid spamming the listener.
  function emit () {
    self._emitter.emit('file_list_modified', self.files)
  }
  var throttledEmit = _.throttle(emit, self._batchInterval, {leading: false})
  self._emitModified = function (immediate) {
    immediate ? emit() : throttledEmit()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.launcher.Launcher"></a>[function <span class="apidocSignatureSpan">karma.</span>launcher.Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher)
- description and source-code
```javascript
launcher.Launcher = function (server, emitter, injector) {
  this._browsers = []
  var lastStartTime
  var self = this

  var getBrowserById = function (id) {
    for (var i = 0; i < self._browsers.length; i++) {
      if (self._browsers[i].id === id) {
        return self._browsers[i]
      }
    }

    return null
  }

  this.launchSingle = function (protocol, hostname, port, urlRoot, upstreamProxy, processKillTimeout) {
    var self = this
    return function (name) {
      if (upstreamProxy) {
        protocol = upstreamProxy.protocol
        hostname = upstreamProxy.hostname
        port = upstreamProxy.port
        urlRoot = upstreamProxy.path + urlRoot.substr(1)
      }
      var url = protocol + '//' + hostname + ':' + port + urlRoot

      var locals = {
        id: ['value', Launcher.generateId()],
        name: ['value', name],
        processKillTimeout: ['value', processKillTimeout],
        baseLauncherDecorator: ['factory', baseDecorator],
        captureTimeoutLauncherDecorator: ['factory', captureTimeoutDecorator],
        retryLauncherDecorator: ['factory', retryDecorator],
        processLauncherDecorator: ['factory', processDecorator],
        baseBrowserDecorator: ['factory', baseBrowserDecoratorFactory]
      }

      // TODO(vojta): determine script from name
      if (name.indexOf('/') !== -1) {
        name = 'Script'
      }

      try {
        var browser = injector.createChild([locals], ['launcher:' + name]).get('launcher:' + name)
      } catch (e) {
        if (e.message.indexOf('No provider for "launcher:' + name + '"') !== -1) {
          log.error('Cannot load browser "%s": it is not registered! ' +
            'Perhaps you are missing some plugin?', name)
        } else {
          log.error('Cannot load browser "%s"!\n  ' + e.stack, name)
        }

        emitter.emit('load_error', 'launcher', name)
        return
      }

      // TODO(vojta): remove in v1.0 (BC for old launchers)
      if (!browser.forceKill) {
        browser.forceKill = function () {
          var me = this
          return new Promise(function (resolve) {
            me.kill(resolve)
          })
        }

        browser.restart = function () {
          var me = this
          this.kill(function () {
            me.start(url)
          })
        }
      }

      self.jobs.add(function (args, done) {
        log.info('Starting browser %s', helper.isDefined(browser.displayName) ? browser.displayName : browser.name)

        browser.on('browser_process_failure', function () {
          done(browser.error)
        })

        browser.on('done', function () {
          // We are not done if there was an error as first the retry takes
          // place which we catch with 'browser_process_failure' if it fails
          if (browser.error || browser.state === browser.STATE_RESTARTING) return

          done(null, browser)
        })

        browser.start(url)
      }, [])

      self.jobs.run()
      self._browsers.push(browser)
    }
  }

  this.launch = function (names, concurrency) {
    log.info(
      'Launching browser%s %s with %s',
      names.length > 1 ? 's' : '',
      names.join(', '),
      concurrency === Infinity ? 'unlimited concurrency' : 'concurrency ' + concurrency
    )
    this.jobs = new Jobs({maxConcurrency: concurrency})

    var self = this
    lastStartTime = Date.now()

    if (server.loadErrors.length === 0) {
      names.forEach(function (name) {
        injector.invoke(self.launchSingle, self)(name)
      })
    } else {
      // Empty task to ensure 'end' is emitted
      this.jobs.add(function (args, done) {
        done()
      }, [])
    }

    this.jobs.on('end', function (err) {
      log.debug('Finished all browsers')

      if (err) {
        log.error(err)
      }
    })

    this.jobs.run()

    return self._browsers
  }

  this.launch.$inject = [
    'config.browsers',
    'config.concurrency',
    'config.processKillTimeout'
  ]

  this.launchSingle.$inject = [
    'config.protocol',
    'config.hostname',
    'config.port',
    'config.urlRoot',
    'config.upstreamProxy',
    'config.proces ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.url"></a>[function <span class="apidocSignatureSpan">karma.</span>url (path)](#apidoc.element.karma.url)
- description and source-code
```javascript
url = function (path) {
  this.path = path
  this.isUrl = true
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.Server"></a>[module karma.Server](#apidoc.module.karma.Server)

#### <a name="apidoc.element.karma.Server.Server"></a>[function <span class="apidocSignatureSpan">karma.</span>Server (cliOptions, done)](#apidoc.element.karma.Server.Server)
- description and source-code
```javascript
Server = function (cliOptions, done) {
  EventEmitter.call(this)

  logger.setupFromConfig(cliOptions)

  this.log = logger.create()

  this.loadErrors = []

  var config = cfg.parseConfig(cliOptions.configFile, cliOptions)

  var modules = [{
    helper: ['value', helper],
    logger: ['value', logger],
    done: ['value', done || process.exit],
    emitter: ['value', this],
    server: ['value', this],
    launcher: ['type', Launcher],
    config: ['value', config],
    preprocess: ['factory', preprocessor.createPreprocessor],
    fileList: ['type', FileList],
    webServer: ['factory', ws.create],
    socketServer: ['factory', createSocketIoServer],
    executor: ['type', Executor],
    // TODO(vojta): remove
    customFileHandlers: ['value', []],
    // TODO(vojta): remove, once karma-dart does not rely on it
    customScriptTypes: ['value', []],
    reporter: ['factory', reporter.createReporters],
    capturedBrowsers: ['type', BrowserCollection],
    args: ['value', {}],
    timer: ['value', {
      setTimeout: function () {
        return setTimeout.apply(root, arguments)
      },
      clearTimeout: function (timeoutId) {
        clearTimeout(timeoutId)
      }
    }]
  }]

  this._setUpLoadErrorListener()
  // Load the plugins
  modules = modules.concat(plugin.resolve(config.plugins, this))

  this._injector = new di.Injector(modules)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.start"></a>[function <span class="apidocSignatureSpan">karma.Server.</span>start (cliOptions, done)](#apidoc.element.karma.Server.start)
- description and source-code
```javascript
start = function (cliOptions, done) {
  var server = new Server(cliOptions, done)
  server.start()
}
```
- example usage
```shell
...
}

exports.run = function () {
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
    break
  case 'stop':
    require('./stopper').stop(config)
    break
...
```

#### <a name="apidoc.element.karma.Server.super_"></a>[function <span class="apidocSignatureSpan">karma.Server.</span>super_ ()](#apidoc.element.karma.Server.super_)
- description and source-code
```javascript
super_ = function () {
  this.bind = bindAllEvents

  this.emitAsync = function (name) {
    // TODO(vojta): allow passing args
    // TODO(vojta): ignore/throw if listener call done() multiple times
    var pending = this.listeners(name).length
    var deferred = helper.defer()
    var done = function () {
      if (!--pending) {
        deferred.resolve()
      }
    }

    this.emit(name, done)

    if (!pending) {
      deferred.resolve()
    }

    return deferred.promise
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.Server.prototype"></a>[module karma.Server.prototype](#apidoc.module.karma.Server.prototype)

#### <a name="apidoc.element.karma.Server.prototype._detach"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_detach (config, done)](#apidoc.element.karma.Server.prototype._detach)
- description and source-code
```javascript
_detach = function (config, done) {
  var log = this.log
  var tmpFile = tmp.fileSync({keep: true})
  log.info('Starting karma detached')
  log.info('Run "karma stop" to stop the server.')
  log.debug('Writing config to tmp-file %s', tmpFile.name)
  config.detached = false
  try {
    fs.writeFileSync(tmpFile.name, JSON.stringify(config), 'utf8')
  } catch (e) {
    log.error("Couldn't write temporary configuration file")
    done(1)
    return
  }
  var child = spawn(process.argv[0], [path.resolve(__dirname, '../lib/detached.js'), tmpFile.name], {
    detached: true,
    stdio: 'ignore'
  })
  child.unref()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.prototype._setUpLoadErrorListener"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_setUpLoadErrorListener ()](#apidoc.element.karma.Server.prototype._setUpLoadErrorListener)
- description and source-code
```javascript
_setUpLoadErrorListener = function () {
  var self = this
  self.on('load_error', function (type, name) {
    self.log.debug('Registered a load error of type %s with name %s', type, name)
    self.loadErrors.push([type, name])
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.prototype._start"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>_start (config, launcher, preprocess, fileList, capturedBrowsers, executor, done)](#apidoc.element.karma.Server.prototype._start)
- description and source-code
```javascript
_start = function (config, launcher, preprocess, fileList, capturedBrowsers, executor, done) {
  var self = this
  if (config.detached) {
    this._detach(config, done)
    return
  }

  self._fileList = fileList

  config.frameworks.forEach(function (framework) {
    self._injector.get('framework:' + framework)
  })

  var webServer = self._injector.get('webServer')
  var socketServer = self._injector.get('socketServer')

  // A map of launched browsers.
  var singleRunDoneBrowsers = Object.create(null)

  // Passing fake event emitter, so that it does not emit on the global,
  // we don't care about these changes.
  var singleRunBrowsers = new BrowserCollection(new EventEmitter())

  // Some browsers did not get captured.
  var singleRunBrowserNotCaptured = false

  webServer.on('error', function (e) {
    if (e.code === 'EADDRINUSE') {
      self.log.warn('Port %d in use', config.port)
      config.port++
      webServer.listen(config.port, config.listenAddress)
    } else {
      throw e
    }
  })

  var afterPreprocess = function () {
    if (config.autoWatch) {
      self._injector.invoke(watcher.watch)
    }

    webServer.listen(config.port, config.listenAddress, function () {
      self.log.info('Karma v%s server started at %s//%s:%s%s', constant.VERSION,
        config.protocol, config.listenAddress, config.port, config.urlRoot)

      self.emit('listening', config.port)
      if (config.browsers && config.browsers.length) {
        self._injector.invoke(launcher.launch, launcher).forEach(function (browserLauncher) {
          singleRunDoneBrowsers[browserLauncher.id] = false
        })
      }
      var noLoadErrors = self.loadErrors.length
      if (noLoadErrors > 0) {
        self.log.error('Found %d load error%s', noLoadErrors, noLoadErrors === 1 ? '' : 's')
        process.exitCode = 1
        process.kill(process.pid, 'SIGINT')
      }
    })
  }

  fileList.refresh().then(afterPreprocess, afterPreprocess)

  self.on('browsers_change', function () {
    // TODO(vojta): send only to interested browsers
    socketServer.sockets.emit('info', capturedBrowsers.serialize())
  })

  self.on('browser_register', function (browser) {
    launcher.markCaptured(browser.id)

    // TODO(vojta): This is lame, browser can get captured and then
    // crash (before other browsers get captured).
    if (launcher.areAllCaptured()) {
      self.emit('browsers_ready')

      if (config.autoWatch) {
        executor.schedule()
      }
    }
  })

  if (config.browserConsoleLogOptions && config.browserConsoleLogOptions.path) {
    var configLevel = config.browserConsoleLogOptions.level || 'debug'
    var configFormat = config.browserConsoleLogOptions.format || '%b %T: %m'
    var configPath = config.browserConsoleLogOptions.path
    self.log.info('Writing browser console to file: %s', configPath)
    var browserLogFile = fs.openSync(configPath, 'w+')
    var levels = ['log', 'error', 'warn', 'info', 'debug']
    self.on('browser_log', function (browser, message, level) {
      if (levels.indexOf(level.toLowerCase()) > levels.indexOf(configLevel)) return
      if (!helper.isString(message)) {
        message = util.inspect(message, {showHidden: false, colors: false})
      }
      var logMap = {'%m': message, '%t': level.toLowerCase(), '%T': level.toUpperCase(), '%b': browser}
      var logString = configFormat.replace(/%[mtTb]/g, function (m) {
        return logMap[m]
      })
      self.log.debug('Writing browser console line: %s', logString)
      fs.write(browserLogFile, logString + '\n')
    })
  }

  var EVENTS_TO_REPLY = ['start', 'info', 'karma_error', 'result', 'complete']
  socketServer.sockets.on('connection', function (socket) {
    self.log.debug('A browser has connected on socket ' + socket.id)

    var replySocketEvents = events.bufferEvents(socket, EVENTS_TO_REPLY)

    socket.on('complete', function (data, ack) {
      ack()
    })

    socket.on('register', function (info) {
      var newBrowser
      var isRestart

      if (info.id) {
        newBrowser = capturedBrowsers.getById ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.prototype.get"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>get (token)](#apidoc.element.karma.Server.prototype.get)
- description and source-code
```javascript
get = function (token) {
  return this._injector.get(token)
}
```
- example usage
```shell
...

  var token = type + ':' + definition.base
  var locals = {
    args: ['value', definition]
  }

  module[type + ':' + name] = ['factory', function (injector) {
    var plugin = injector.createChild([locals], [token]).get(token)
    if (type === 'launcher' && helper.isDefined(definition.displayName)) {
      plugin.displayName = definition.displayName
    }
    return plugin
  }]
  hasSomeInlinedPlugin = true
})
...
```

#### <a name="apidoc.element.karma.Server.prototype.refreshFiles"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>refreshFiles ()](#apidoc.element.karma.Server.prototype.refreshFiles)
- description and source-code
```javascript
refreshFiles = function () {
  if (!this._fileList) return Promise.resolve()

  return this._fileList.refresh()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.Server.prototype.start"></a>[function <span class="apidocSignatureSpan">karma.Server.prototype.</span>start ()](#apidoc.element.karma.Server.prototype.start)
- description and source-code
```javascript
start = function () {
  this._injector.invoke(this._start, this)
}
```
- example usage
```shell
...
}

exports.run = function () {
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
    break
  case 'stop':
    require('./stopper').stop(config)
    break
...
```



# <a name="apidoc.module.karma.Server.super_"></a>[module karma.Server.super_](#apidoc.module.karma.Server.super_)

#### <a name="apidoc.element.karma.Server.super_.super_"></a>[function <span class="apidocSignatureSpan">karma.Server.</span>super_ ()](#apidoc.element.karma.Server.super_.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.cli"></a>[module karma.cli](#apidoc.module.karma.cli)

#### <a name="apidoc.element.karma.cli.argsBeforeDoubleDash"></a>[function <span class="apidocSignatureSpan">karma.cli.</span>argsBeforeDoubleDash (argv)](#apidoc.element.karma.cli.argsBeforeDoubleDash)
- description and source-code
```javascript
argsBeforeDoubleDash = function (argv) {
  var idx = argv.indexOf('--')

  return idx === -1 ? argv : argv.slice(0, idx)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.cli.parseClientArgs"></a>[function <span class="apidocSignatureSpan">karma.cli.</span>parseClientArgs (argv)](#apidoc.element.karma.cli.parseClientArgs)
- description and source-code
```javascript
parseClientArgs = function (argv) {
  // extract any args after '--' as clientArgs
  var clientArgs = []
  argv = argv.slice(2)
  var idx = argv.indexOf('--')
  if (idx !== -1) {
    clientArgs = argv.slice(idx + 1)
  }
  return clientArgs
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.cli.process"></a>[function <span class="apidocSignatureSpan">karma.cli.</span>process ()](#apidoc.element.karma.cli.process)
- description and source-code
```javascript
process = function () {
  var argv = optimist.parse(argsBeforeDoubleDash(process.argv.slice(2)))
  var options = {
    cmd: argv._.shift()
  }

  switch (options.cmd) {
    case 'start':
      describeStart()
      break

    case 'run':
      describeRun()
      options.clientArgs = parseClientArgs(process.argv)
      break

    case 'stop':
      describeStop()
      break

    case 'init':
      describeInit()
      break

    case 'completion':
      describeCompletion()
      break

    default:
      describeShared()
      if (!options.cmd) {
        processArgs(argv, options, fs, path)
        console.error('Command not specified.')
      } else {
        console.error('Unknown command "' + options.cmd + '".')
      }
      optimist.showHelp()
      process.exit(1)
  }

  return processArgs(argv, options, fs, path)
}
```
- example usage
```shell
...
    process.exit(1)
}

return processArgs(argv, options, fs, path)
}

exports.run = function () {
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
...
```

#### <a name="apidoc.element.karma.cli.processArgs"></a>[function <span class="apidocSignatureSpan">karma.cli.</span>processArgs (argv, options, fs, path)](#apidoc.element.karma.cli.processArgs)
- description and source-code
```javascript
processArgs = function (argv, options, fs, path) {
  if (argv.help) {
    console.log(optimist.help())
    process.exit(0)
  }

  if (argv.version) {
    console.log('Karma version: ' + constant.VERSION)
    process.exit(0)
  }

  // TODO(vojta): warn/throw when unknown argument (probably mispelled)
  Object.getOwnPropertyNames(argv).forEach(function (name) {
    var argumentValue = argv[name]
    if (name !== '_' && name !== '$0') {
      if (Array.isArray(argumentValue)) {
        // If the same argument is defined multiple times, override.
        argumentValue = argumentValue.pop()
      }
      options[helper.dashToCamel(name)] = argumentValue
    }
  })

  if (helper.isString(options.autoWatch)) {
    options.autoWatch = options.autoWatch === 'true'
  }

  if (helper.isString(options.colors)) {
    options.colors = options.colors === 'true'
  }

  if (helper.isString(options.failOnEmptyTestSuite)) {
    options.failOnEmptyTestSuite = options.failOnEmptyTestSuite === 'true'
  }

  if (helper.isString(options.formatError)) {
    try {
      var required = require(options.formatError)
    } catch (err) {
      console.error('Could not require formatError: ' + options.formatError, err)
    }
    // support exports.formatError and module.exports = function
    options.formatError = required.formatError || required
    if (!helper.isFunction(options.formatError)) {
      console.error('Format error must be a function, got: ' + typeof options.formatError)
      process.exit(1)
    }
  }

  if (helper.isString(options.logLevel)) {
    var logConstant = constant['LOG_' + options.logLevel.toUpperCase()]
    if (helper.isDefined(logConstant)) {
      options.logLevel = logConstant
    } else {
      console.error('Log level must be one of disable, error, warn, info, or debug.')
      process.exit(1)
    }
  } else if (helper.isDefined(options.logLevel)) {
    console.error('Log level must be one of disable, error, warn, info, or debug.')
    process.exit(1)
  }

  if (helper.isString(options.singleRun)) {
    options.singleRun = options.singleRun === 'true'
  }

  if (helper.isString(options.browsers)) {
    options.browsers = options.browsers.split(',')
  }

  if (options.reportSlowerThan === false) {
    options.reportSlowerThan = 0
  }

  if (helper.isString(options.reporters)) {
    options.reporters = options.reporters.split(',')
  }

  if (helper.isString(options.removedFiles)) {
    options.removedFiles = options.removedFiles.split(',')
  }

  if (helper.isString(options.addedFiles)) {
    options.addedFiles = options.addedFiles.split(',')
  }

  if (helper.isString(options.changedFiles)) {
    options.changedFiles = options.changedFiles.split(',')
  }

  if (helper.isString(options.refresh)) {
    options.refresh = options.refresh === 'true'
  }

  var configFile = argv._.shift()

  if (!configFile) {
    // default config file (if exists)
    if (fs.existsSync('./karma.conf.js')) {
      configFile = './karma.conf.js'
    } else if (fs.existsSync('./karma.conf.coffee')) {
      configFile = './karma.conf.coffee'
    } else if (fs.existsSync('./karma.conf.ts')) {
      configFile = './karma.conf.ts'
    } else if (fs.existsSync('./.config/karma.conf.js')) {
      configFile = './.config/karma.conf.js'
    } else if (fs.existsSync('./.config/karma.conf.coffee')) {
      configFile = './.config/karma.conf.coffee'
    } else if (fs.existsSync('./.config/karma.conf.ts')) {
      configFile = './.config/karma.conf.ts'
    }
  }

  options.configFile = configFile ? path.resolve(configFile) : null

  return options
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.cli.run"></a>[function <span class="apidocSignatureSpan">karma.cli.</span>run ()](#apidoc.element.karma.cli.run)
- description and source-code
```javascript
run = function () {
  var config = exports.process()

  switch (config.cmd) {
    case 'start':
      new Server(config).start()
      break
    case 'run':
      require('./runner').run(config)
      break
    case 'stop':
      require('./stopper').stop(config)
      break
    case 'init':
      require('./init').init(config)
      break
    case 'completion':
      require('./completion').completion(config)
      break
  }
}
```
- example usage
```shell
...
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
    break
  case 'stop':
    require('./stopper').stop(config)
    break
  case 'init':
    require('./init').init(config)
    break
...
```



# <a name="apidoc.module.karma.completion"></a>[module karma.completion](#apidoc.module.karma.completion)

#### <a name="apidoc.element.karma.completion.completion"></a>[function <span class="apidocSignatureSpan">karma.</span>completion ()](#apidoc.element.karma.completion.completion)
- description and source-code
```javascript
completion = function () {
  if (process.argv[3] === '--') {
    return complete(parseEnv(process.argv, process.env))
  }

  // just print out the karma-completion.sh
  var fs = require('graceful-fs')
  var path = require('path')

  fs.readFile(path.resolve(__dirname, '../scripts/karma-completion.sh'), 'utf8', function (err, data) {
    if (err) return console.error(err)

    process.stdout.write(data)
    process.stdout.on('error', function (error) {
      // Darwin is a real dick sometimes.
      //
      // This is necessary because the "source" or "." program in
      // bash on OS X closes its file argument before reading
      // from it, meaning that you get exactly 1 write, which will
      // work most of the time, and will always raise an EPIPE.
      //
      // Really, one should not be tossing away EPIPE errors, or any
      // errors, so casually.  But, without this, '. <(karma completion)'
      // can never ever work on OS X.
      if (error.errno === 'EPIPE') {
        error = null
      }
    })
  })
}
```
- example usage
```shell
...
    case 'stop':
      require('./stopper').stop(config)
      break
    case 'init':
      require('./init').init(config)
      break
    case 'completion':
      require('./completion').completion(config)
      break
  }
}

// just for testing
exports.processArgs = processArgs
exports.parseClientArgs = parseClientArgs
...
```

#### <a name="apidoc.element.karma.completion.complete"></a>[function <span class="apidocSignatureSpan">karma.completion.</span>complete (env)](#apidoc.element.karma.completion.complete)
- description and source-code
```javascript
complete = function (env) {
  if (env.count === 1) {
    if (env.words[0].charAt(0) === '-') {
      return sendCompletion(['--help', '--version'], env)
    }

    return sendCompletion(Object.keys(options), env)
  }

  if (env.count === 2 && env.words[1].charAt(0) !== '-') {
    // complete files (probably karma.conf.js)
    return sendCompletionFiles(env)
  }

  var cmdOptions = options[env.words[0]]
  var previousOption = cmdOptions[env.prev]

  if (!cmdOptions) {
    // no completion, wrong command
    return sendCompletionNoOptions()
  }

  if (previousOption === CUSTOM && env.last) {
    // custom value with already filled something
    return sendCompletionConfirmLast(env)
  }

  if (previousOption) {
    // custom options
    return sendCompletion(previousOption, env)
  }

  return sendCompletion(Object.keys(cmdOptions), env)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.completion.opositeWord"></a>[function <span class="apidocSignatureSpan">karma.completion.</span>opositeWord (word)](#apidoc.element.karma.completion.opositeWord)
- description and source-code
```javascript
opositeWord = function (word) {
  if (word.charAt(0) !== '-') {
    return null
  }

  return word.substr(0, 5) === '--no-' ? '--' + word.substr(5) : '--no-' + word.substr(2)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.completion.sendCompletion"></a>[function <span class="apidocSignatureSpan">karma.completion.</span>sendCompletion (possibleWords, env)](#apidoc.element.karma.completion.sendCompletion)
- description and source-code
```javascript
sendCompletion = function (possibleWords, env) {
  var regexp = new RegExp('^' + env.last)
  var filteredWords = possibleWords.filter(function (word) {
    return regexp.test(word) && env.words.indexOf(word) === -1 &&
      env.words.indexOf(opositeWord(word)) === -1
  })

  if (!filteredWords.length) {
    return sendCompletionNoOptions(env)
  }

  filteredWords.forEach(function (word) {
    console.log(word)
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.config"></a>[module karma.config](#apidoc.module.karma.config)

#### <a name="apidoc.element.karma.config.parseConfig"></a>[function <span class="apidocSignatureSpan">karma.config.</span>parseConfig (configFilePath, cliOptions)](#apidoc.element.karma.config.parseConfig)
- description and source-code
```javascript
parseConfig = function (configFilePath, cliOptions) {
  var configModule
  if (configFilePath) {
    log.debug('Loading config %s', configFilePath)

    try {
      configModule = require(configFilePath)
      if (typeof configModule === 'object' && typeof configModule.default !== 'undefined') {
        configModule = configModule.default
      }
    } catch (e) {
      if (e.code === 'MODULE_NOT_FOUND' && e.message.indexOf(configFilePath) !== -1) {
        log.error('File %s does not exist!', configFilePath)
      } else {
        log.error('Invalid config file!\n  ' + e.stack)

        var extension = path.extname(configFilePath)
        if (extension === '.coffee' && !COFFEE_SCRIPT_AVAILABLE) {
          log.error('You need to install CoffeeScript.\n' +
            '  npm install coffee-script --save-dev')
        } else if (extension === '.ls' && !LIVE_SCRIPT_AVAILABLE) {
          log.error('You need to install LiveScript.\n' +
            '  npm install LiveScript --save-dev')
        } else if (extension === '.ts' && !TYPE_SCRIPT_AVAILABLE) {
          log.error('You need to install TypeScript.\n' +
            '  npm install typescript ts-node --save-dev')
        }
      }
      return process.exit(1)
    }
    if (!helper.isFunction(configModule)) {
      log.error('Config file must export a function!\n' + CONFIG_SYNTAX_HELP)
      return process.exit(1)
    }
  } else {
    log.debug('No config file specified.')
    // if no config file path is passed, we define a dummy config module.
    configModule = function () {}
  }

  var config = new Config()

  // save and reset hostname and listenAddress so we can detect if the user
  // changed them
  var defaultHostname = config.hostname
  config.hostname = null
  var defaultListenAddress = config.listenAddress
  config.listenAddress = null

  // add the user's configuration in
  config.set(cliOptions)

  try {
    configModule(config)
  } catch (e) {
    log.error('Error in config file!\n', e)
    return process.exit(1)
  }

  // merge the config from config file and cliOptions (precedence)
  config.set(cliOptions)

  // if the user changed listenAddress, but didn't set a hostname, warn them
  if (config.hostname === null && config.listenAddress !== null) {
    log.warn('ListenAddress was set to %s but hostname was left as the default: ' +
      '%s. If your browsers fail to connect, consider changing the hostname option.',
      config.listenAddress, defaultHostname)
  }
  // restore values that weren't overwritten by the user
  if (config.hostname === null) {
    config.hostname = defaultHostname
  }
  if (config.listenAddress === null) {
    config.listenAddress = defaultListenAddress
  }

  // configure the logger as soon as we can
  logger.setup(config.logLevel, config.colors, config.loggers)

  return normalizeConfig(config, configFilePath)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.emitter_wrapper"></a>[module karma.emitter_wrapper](#apidoc.module.karma.emitter_wrapper)

#### <a name="apidoc.element.karma.emitter_wrapper.emitter_wrapper"></a>[function <span class="apidocSignatureSpan">karma.</span>emitter_wrapper (emitter)](#apidoc.element.karma.emitter_wrapper.emitter_wrapper)
- description and source-code
```javascript
function EmitterWrapper(emitter) {
  this.listeners = {}
  this.emitter = emitter
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.emitter_wrapper.prototype"></a>[module karma.emitter_wrapper.prototype](#apidoc.module.karma.emitter_wrapper.prototype)

#### <a name="apidoc.element.karma.emitter_wrapper.prototype.addListener"></a>[function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>addListener (event, listener)](#apidoc.element.karma.emitter_wrapper.prototype.addListener)
- description and source-code
```javascript
addListener = function (event, listener) {
  this.emitter.addListener(event, listener)

  if (!this.listeners.hasOwnProperty(event)) {
    this.listeners[event] = []
  }

  this.listeners[event].push(listener)

  return this
}
```
- example usage
```shell
...

function EmitterWrapper (emitter) {
this.listeners = {}
this.emitter = emitter
}

EmitterWrapper.prototype.addListener = EmitterWrapper.prototype.on = function (event, listener) {
this.emitter.addListener(event, listener)

if (!this.listeners.hasOwnProperty(event)) {
  this.listeners[event] = []
}

this.listeners[event].push(listener)
...
```

#### <a name="apidoc.element.karma.emitter_wrapper.prototype.on"></a>[function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>on (event, listener)](#apidoc.element.karma.emitter_wrapper.prototype.on)
- description and source-code
```javascript
on = function (event, listener) {
  this.emitter.addListener(event, listener)

  if (!this.listeners.hasOwnProperty(event)) {
    this.listeners[event] = []
  }

  this.listeners[event].push(listener)

  return this
}
```
- example usage
```shell
...
  var fs = require('graceful-fs')
  var path = require('path')

  fs.readFile(path.resolve(__dirname, '../scripts/karma-completion.sh'), 'utf8', function (err, data) {
if (err) return console.error(err)

process.stdout.write(data)
process.stdout.on('error', function (error) {
  // Darwin is a real dick sometimes.
  //
  // This is necessary because the "source" or "." program in
  // bash on OS X closes its file argument before reading
  // from it, meaning that you get exactly 1 write, which will
  // work most of the time, and will always raise an EPIPE.
  //
...
```

#### <a name="apidoc.element.karma.emitter_wrapper.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">karma.emitter_wrapper.prototype.</span>removeAllListeners (event)](#apidoc.element.karma.emitter_wrapper.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function (event) {
  var events = event ? [event] : Object.keys(this.listeners)
  var self = this
  events.forEach(function (event) {
    self.listeners[event].forEach(function (listener) {
      self.emitter.removeListener(event, listener)
    })
    delete self.listeners[event]
  })

  return this
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.events"></a>[module karma.events](#apidoc.module.karma.events)

#### <a name="apidoc.element.karma.events.EventEmitter"></a>[function <span class="apidocSignatureSpan">karma.events.</span>EventEmitter ()](#apidoc.element.karma.events.EventEmitter)
- description and source-code
```javascript
EventEmitter = function () {
  this.bind = bindAllEvents

  this.emitAsync = function (name) {
    // TODO(vojta): allow passing args
    // TODO(vojta): ignore/throw if listener call done() multiple times
    var pending = this.listeners(name).length
    var deferred = helper.defer()
    var done = function () {
      if (!--pending) {
        deferred.resolve()
      }
    }

    this.emit(name, done)

    if (!pending) {
      deferred.resolve()
    }

    return deferred.promise
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.events.bindAll"></a>[function <span class="apidocSignatureSpan">karma.events.</span>bindAll (object, context)](#apidoc.element.karma.events.bindAll)
- description and source-code
```javascript
bindAll = function (object, context) {
  context = context || this

  var bindMethod = function (method) {
    context.on(helper.camelToSnake(method.substr(2)), function () {
      var args = Array.prototype.slice.call(arguments, 0)
      args.push(context)
      object[method].apply(object, args)
    })
  }

  for (var method in object) {
    if (helper.isFunction(object[method]) && method.substr(0, 2) === 'on') {
      bindMethod(method)
    }
  }
}
```
- example usage
```shell
...
  this.state = READY
  this.lastResult = new Result()
  this.disconnectsCount = 0

  this.init = function () {
collection.add(this)

events.bindAll(this, socket)

log.info('Connected on socket %s with id %s', socket.id, id)

// TODO(vojta): move to collection
emitter.emit('browsers_change', collection)

emitter.emit('browser_register', this)
...
```

#### <a name="apidoc.element.karma.events.bufferEvents"></a>[function <span class="apidocSignatureSpan">karma.events.</span>bufferEvents (emitter, eventsToBuffer)](#apidoc.element.karma.events.bufferEvents)
- description and source-code
```javascript
bufferEvents = function (emitter, eventsToBuffer) {
  var listeners = []
  var eventsToReply = []
  var genericListener = function () {
    eventsToReply.push(Array.prototype.slice.call(arguments))
  }

  eventsToBuffer.forEach(function (eventName) {
    var listener = genericListener.bind(null, eventName)
    listeners.push(listener)
    emitter.on(eventName, listener)
  })

  return function () {
    if (!eventsToReply) {
      return
    }

    // remove all buffering listeners
    listeners.forEach(function (listener, i) {
      emitter.removeListener(eventsToBuffer[i], listener)
    })

    // reply
    eventsToReply.forEach(function (args) {
      events.EventEmitter.prototype.emit.apply(emitter, args)
    })

    // free-up
    listeners = eventsToReply = null
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.file"></a>[module karma.file](#apidoc.module.karma.file)

#### <a name="apidoc.element.karma.file.file"></a>[function <span class="apidocSignatureSpan">karma.</span>file (path, mtime, doNotCache)](#apidoc.element.karma.file.file)
- description and source-code
```javascript
file = function (path, mtime, doNotCache) {
  // used for serving (processed path, eg some/file.coffee -> some/file.coffee.js)
  this.path = path

  // original absolute path, id of the file
  this.originalPath = path

  // where the content is stored (processed)
  this.contentPath = path

  this.mtime = mtime
  this.isUrl = false

  this.doNotCache = _.isUndefined(doNotCache) ? false : doNotCache
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.file.prototype"></a>[module karma.file.prototype](#apidoc.module.karma.file.prototype)

#### <a name="apidoc.element.karma.file.prototype.toString"></a>[function <span class="apidocSignatureSpan">karma.file.prototype.</span>toString ()](#apidoc.element.karma.file.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return this.path
}
```
- example usage
```shell
...




var fs = require('graceful-fs')
var path = require('path')

var pkg = JSON.parse(fs.readFileSync(path.join(__dirname, '/../package.json')).toString())

exports.VERSION = pkg.version

exports.DEFAULT_PORT = process.env.PORT || 9876
exports.DEFAULT_HOSTNAME = process.env.IP || 'localhost'
exports.DEFAULT_LISTEN_ADDR = process.env.LISTEN_ADDR || '0.0.0.0'
...
```



# <a name="apidoc.module.karma.file_list"></a>[module karma.file_list](#apidoc.module.karma.file_list)

#### <a name="apidoc.element.karma.file_list.file_list"></a>[function <span class="apidocSignatureSpan">karma.</span>file_list (patterns, excludes, emitter, preprocess, batchInterval)](#apidoc.element.karma.file_list.file_list)
- description and source-code
```javascript
file_list = function (patterns, excludes, emitter, preprocess, batchInterval) {
  // Store options
  this._patterns = patterns
  this._excludes = excludes
  this._emitter = emitter
  this._preprocess = Promise.promisify(preprocess)
  this._batchInterval = batchInterval

  // The actual list of files
  this.buckets = new Map()

  // Internal tracker if we are refreshing.
  // When a refresh is triggered this gets set
  // to the promise that 'this._refresh' returns.
  // So we know we are refreshing when this promise
  // is still pending, and we are done when it's either
  // resolved or rejected.
  this._refreshing = Promise.resolve()

  var self = this

  // Emit the 'file_list_modified' event.
  // This function is throttled to the value of 'batchInterval'
  // to avoid spamming the listener.
  function emit () {
    self._emitter.emit('file_list_modified', self.files)
  }
  var throttledEmit = _.throttle(emit, self._batchInterval, {leading: false})
  self._emitModified = function (immediate) {
    immediate ? emit() : throttledEmit()
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.file_list.prototype"></a>[module karma.file_list.prototype](#apidoc.module.karma.file_list.prototype)

#### <a name="apidoc.element.karma.file_list.prototype._exists"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_exists (path)](#apidoc.element.karma.file_list.prototype._exists)
- description and source-code
```javascript
_exists = function (path) {
  var self = this

  var patterns = this._patterns.filter(function (pattern) {
    return mm(path, pattern.pattern)
  })

  return !!_.find(patterns, function (pattern) {
    return self._findFile(path, pattern)
  })
}
```
- example usage
```shell
...
var pattern = this._isIncluded(path)

if (!pattern) {
  log.debug('Add file "%s" ignored. Does not match any pattern.', path)
  return Promise.resolve(this.files)
}

if (this._exists(path)) {
  log.debug('Add file "%s" ignored. Already in the list.', path)
  return Promise.resolve(this.files)
}

var file = new File(path)
this.buckets.get(pattern.pattern).add(file)
...
```

#### <a name="apidoc.element.karma.file_list.prototype._findFile"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_findFile (path, pattern)](#apidoc.element.karma.file_list.prototype._findFile)
- description and source-code
```javascript
_findFile = function (path, pattern) {
  if (!path || !pattern) return
  if (!this.buckets.has(pattern.pattern)) return

  return _.find(from(this.buckets.get(pattern.pattern)), function (file) {
    return file.originalPath === path
  })
}
```
- example usage
```shell
...
  var self = this

  var patterns = this._patterns.filter(function (pattern) {
    return mm(path, pattern.pattern)
  })

  return !!_.find(patterns, function (pattern) {
    return self._findFile(path, pattern)
  })
}

// Check if we are currently refreshing
List.prototype._isRefreshing = function () {
  return this._refreshing.isPending()
}
...
```

#### <a name="apidoc.element.karma.file_list.prototype._isExcluded"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isExcluded (path)](#apidoc.element.karma.file_list.prototype._isExcluded)
- description and source-code
```javascript
_isExcluded = function (path) {
  return _.find(this._excludes, function (pattern) {
    return mm(path, pattern)
  })
}
```
- example usage
```shell
...

    if (_.isEmpty(files)) {
log.warn('Pattern "%s" does not match any file.', pattern)
return
    }

    return Promise.map(files, function (path) {
if (self._isExcluded(path)) {
  log.debug('Excluded file "%s"', path)
  return Promise.resolve()
}

var mtime = mg.statCache[path].mtime
var doNotCache = patternObject.nocache
var file = new File(path, mtime, doNotCache)
...
```

#### <a name="apidoc.element.karma.file_list.prototype._isIncluded"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isIncluded (path)](#apidoc.element.karma.file_list.prototype._isIncluded)
- description and source-code
```javascript
_isIncluded = function (path) {
  return _.find(this._patterns, function (pattern) {
    return mm(path, pattern.pattern)
  })
}
```
- example usage
```shell
...
var excluded = this._isExcluded(path)
if (excluded) {
  log.debug('Add file "%s" ignored. Excluded by "%s".', path, excluded)

  return Promise.resolve(this.files)
}

var pattern = this._isIncluded(path)

if (!pattern) {
  log.debug('Add file "%s" ignored. Does not match any pattern.', path)
  return Promise.resolve(this.files)
}

if (this._exists(path)) {
...
```

#### <a name="apidoc.element.karma.file_list.prototype._isRefreshing"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_isRefreshing ()](#apidoc.element.karma.file_list.prototype._isRefreshing)
- description and source-code
```javascript
_isRefreshing = function () {
  return this._refreshing.isPending()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file_list.prototype._refresh"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>_refresh ()](#apidoc.element.karma.file_list.prototype._refresh)
- description and source-code
```javascript
_refresh = function () {
  var self = this
  var buckets = this.buckets

  var promise = Promise.map(this._patterns, function (patternObject) {
    var pattern = patternObject.pattern

    if (helper.isUrlAbsolute(pattern)) {
      buckets.set(pattern, new Set([new Url(pattern)]))
      return Promise.resolve()
    }

    var mg = new Glob(pathLib.normalize(pattern), GLOB_OPTS)
    var files = mg.found
    buckets.set(pattern, new Set())

    if (_.isEmpty(files)) {
      log.warn('Pattern "%s" does not match any file.', pattern)
      return
    }

    return Promise.map(files, function (path) {
      if (self._isExcluded(path)) {
        log.debug('Excluded file "%s"', path)
        return Promise.resolve()
      }

      var mtime = mg.statCache[path].mtime
      var doNotCache = patternObject.nocache
      var file = new File(path, mtime, doNotCache)

      if (file.doNotCache) {
        log.debug('Not preprocessing "%s" due to nocache')
        return Promise.resolve(file)
      }

      return self._preprocess(file).then(function () {
        return file
      })
    })
    .then(function (files) {
      files = _.compact(files)

      if (_.isEmpty(files)) {
        log.warn('All files matched by "%s" were excluded.', pattern)
      } else {
        buckets.set(pattern, new Set(files))
      }
    })
  })
  .then(function () {
    if (self._refreshing !== promise) {
      return self._refreshing
    }
    self.buckets = buckets
    self._emitModified(true)
    return self.files
  })

  return promise
}
```
- example usage
```shell
...
})

// Reglob all patterns to update the list.
//
// Returns a promise that is resolved when the refresh
// is completed.
List.prototype.refresh = function () {
  this._refreshing = this._refresh()
  return this._refreshing
}

// Set new patterns and excludes and update
// the list accordingly
//
// patterns - Array, the new patterns.
...
```

#### <a name="apidoc.element.karma.file_list.prototype.addFile"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>addFile (path)](#apidoc.element.karma.file_list.prototype.addFile)
- description and source-code
```javascript
addFile = function (path) {
  var self = this

  // Ensure we are not adding a file that should be excluded
  var excluded = this._isExcluded(path)
  if (excluded) {
    log.debug('Add file "%s" ignored. Excluded by "%s".', path, excluded)

    return Promise.resolve(this.files)
  }

  var pattern = this._isIncluded(path)

  if (!pattern) {
    log.debug('Add file "%s" ignored. Does not match any pattern.', path)
    return Promise.resolve(this.files)
  }

  if (this._exists(path)) {
    log.debug('Add file "%s" ignored. Already in the list.', path)
    return Promise.resolve(this.files)
  }

  var file = new File(path)
  this.buckets.get(pattern.pattern).add(file)

  return Promise.all([
    fs.statAsync(path),
    this._refreshing
  ]).spread(function (stat) {
    file.mtime = stat.mtime
    return self._preprocess(file)
  })
  .then(function () {
    log.info('Added file "%s".', path)
    self._emitModified()
    return self.files
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file_list.prototype.changeFile"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>changeFile (path)](#apidoc.element.karma.file_list.prototype.changeFile)
- description and source-code
```javascript
changeFile = function (path) {
  var self = this

  var pattern = this._isIncluded(path)
  var file = this._findFile(path, pattern)

  if (!pattern || !file) {
    log.debug('Changed file "%s" ignored. Does not match any file in the list.', path)
    return Promise.resolve(this.files)
  }

  return Promise.all([
    fs.statAsync(path),
    this._refreshing
  ]).spread(function (stat) {
    if (stat.mtime <= file.mtime) throw new Promise.CancellationError()

    file.mtime = stat.mtime
    return self._preprocess(file)
  })
  .then(function () {
    log.info('Changed file "%s".', path)
    self._emitModified()
    return self.files
  })
  .catch(Promise.CancellationError, function () {
    return self.files
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file_list.prototype.refresh"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>refresh ()](#apidoc.element.karma.file_list.prototype.refresh)
- description and source-code
```javascript
refresh = function () {
  this._refreshing = this._refresh()
  return this._refreshing
}
```
- example usage
```shell
...
// is completed.
List.prototype.reload = function (patterns, excludes) {
  this._patterns = patterns
  this._excludes = excludes

  // Wait until the current refresh is done and then do a
  // refresh to ensure a refresh actually happens
  return this.refresh()
}

// Add a new file from the list.
// This is called by the watcher
//
// path - String, the path of the file to update.
//
...
```

#### <a name="apidoc.element.karma.file_list.prototype.reload"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>reload (patterns, excludes)](#apidoc.element.karma.file_list.prototype.reload)
- description and source-code
```javascript
reload = function (patterns, excludes) {
  this._patterns = patterns
  this._excludes = excludes

  // Wait until the current refresh is done and then do a
  // refresh to ensure a refresh actually happens
  return this.refresh()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.file_list.prototype.removeFile"></a>[function <span class="apidocSignatureSpan">karma.file_list.prototype.</span>removeFile (path)](#apidoc.element.karma.file_list.prototype.removeFile)
- description and source-code
```javascript
removeFile = function (path) {
  var self = this

  return Promise.try(function () {
    var pattern = self._isIncluded(path)
    var file = self._findFile(path, pattern)

    if (!pattern || !file) {
      log.debug('Removed file "%s" ignored. Does not match any file in the list.', path)
      return self.files
    }

    self.buckets.get(pattern.pattern).delete(file)

    log.info('Removed file "%s".', path)
    self._emitModified()
    return self.files
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.helper"></a>[module karma.helper](#apidoc.module.karma.helper)

#### <a name="apidoc.element.karma.helper.arrayRemove"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>arrayRemove (collection, item)](#apidoc.element.karma.helper.arrayRemove)
- description and source-code
```javascript
arrayRemove = function (collection, item) {
  var idx = collection.indexOf(item)

  if (idx !== -1) {
    collection.splice(idx, 1)
    return true
  }

  return false
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.helper.browserFullNameToShort"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>browserFullNameToShort (fullName)](#apidoc.element.karma.helper.browserFullNameToShort)
- description and source-code
```javascript
browserFullNameToShort = function (fullName) {
  var agent = useragent.parse(fullName)
  var isKnown = agent.family !== 'Other' && agent.os.family !== 'Other'
  return isKnown ? agent.toAgent() + ' (' + agent.os + ')' : fullName
}
```
- example usage
```shell
...

// The browser got permanently disconnected (being removed from the collection and destroyed).
var DISCONNECTED = 5

var Browser = function (id, fullName, /* capturedBrowsers */ collection, emitter, socket, timer,
/* config.browserDisconnectTimeout */ disconnectDelay,
/* config.browserNoActivityTimeout */ noActivityTimeout) {
var name = helper.browserFullNameToShort(fullName)
var log = logger.create(name)
var activeSockets = [socket]
var activeSocketsIds = function () {
  return activeSockets.map(function (s) {
    return s.id
  }).join(', ')
}
...
```

#### <a name="apidoc.element.karma.helper.camelToSnake"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>camelToSnake (camelCase)](#apidoc.element.karma.helper.camelToSnake)
- description and source-code
```javascript
camelToSnake = function (camelCase) {
  return camelCase.replace(/[A-Z]/g, function (match, pos) {
    return (pos > 0 ? '_' : '') + match.toLowerCase()
  })
}
```
- example usage
```shell
...

var helper = require('./helper')

var bindAllEvents = function (object, context) {
context = context || this

var bindMethod = function (method) {
  context.on(helper.camelToSnake(method.substr(2)), function () {
    var args = Array.prototype.slice.call(arguments, 0)
    args.push(context)
    object[method].apply(object, args)
  })
}

for (var method in object) {
...
```

#### <a name="apidoc.element.karma.helper.dashToCamel"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>dashToCamel (dash)](#apidoc.element.karma.helper.dashToCamel)
- description and source-code
```javascript
dashToCamel = function (dash) {
  var words = dash.split('-')
  return words.shift() + words.map(exports.ucFirst).join('')
}
```
- example usage
```shell
...
Object.getOwnPropertyNames(argv).forEach(function (name) {
  var argumentValue = argv[name]
  if (name !== '_' && name !== '$0') {
    if (Array.isArray(argumentValue)) {
      // If the same argument is defined multiple times, override.
      argumentValue = argumentValue.pop()
    }
    options[helper.dashToCamel(name)] = argumentValue
  }
})

if (helper.isString(options.autoWatch)) {
  options.autoWatch = options.autoWatch === 'true'
}
...
```

#### <a name="apidoc.element.karma.helper.defer"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>defer ()](#apidoc.element.karma.helper.defer)
- description and source-code
```javascript
defer = function () {
  var resolve
  var reject
  var promise = new Promise(function () {
    resolve = arguments[0]
    reject = arguments[1]
  })

  return {
    resolve: resolve,
    reject: reject,
    promise: promise
  }
}
```
- example usage
```shell
...
var EventEmitter = function () {
  this.bind = bindAllEvents

  this.emitAsync = function (name) {
// TODO(vojta): allow passing args
// TODO(vojta): ignore/throw if listener call done() multiple times
var pending = this.listeners(name).length
var deferred = helper.defer()
var done = function () {
  if (!--pending) {
    deferred.resolve()
  }
}

this.emit(name, done)
...
```

#### <a name="apidoc.element.karma.helper.formatTimeInterval"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>formatTimeInterval (time)](#apidoc.element.karma.helper.formatTimeInterval)
- description and source-code
```javascript
formatTimeInterval = function (time) {
  var mins = Math.floor(time / 60000)
  var secs = (time - mins * 60000) / 1000
  var str = secs + (secs === 1 ? ' sec' : ' secs')

  if (mins) {
    str = mins + (mins === 1 ? ' min ' : ' mins ') + str
  }

  return str
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.helper.isArray"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isArray ()](#apidoc.element.karma.helper.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
...
  process.exit(0)
}

// TODO(vojta): warn/throw when unknown argument (probably mispelled)
Object.getOwnPropertyNames(argv).forEach(function (name) {
  var argumentValue = argv[name]
  if (name !== '_' && name !== '$0') {
    if (Array.isArray(argumentValue)) {
      // If the same argument is defined multiple times, override.
      argumentValue = argumentValue.pop()
    }
    options[helper.dashToCamel(name)] = argumentValue
  }
})
...
```

#### <a name="apidoc.element.karma.helper.isDefined"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isDefined (value)](#apidoc.element.karma.helper.isDefined)
- description and source-code
```javascript
isDefined = function (value) {
  return !_.isUndefined(value)
}
```
- example usage
```shell
...

  this.onInfo = function (info) {
if (this.isReady()) {
  return
}

// TODO(vojta): remove
if (helper.isDefined(info.dump)) {
  emitter.emit('browser_log', this, info.dump, 'dump')
}

if (helper.isDefined(info.log)) {
  emitter.emit('browser_log', this, info.log, info.type)
}
...
```

#### <a name="apidoc.element.karma.helper.isFunction"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isFunction (value)](#apidoc.element.karma.helper.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  // The use of 'Object#toString' avoids issues with the 'typeof' operator
  // in older versions of Chrome and Safari which return 'function' for regexes
  // and Safari 8 equivalents which return 'object' for typed array constructors.
  return isObject(value) && objToString.call(value) == funcTag;
}
```
- example usage
```shell
...
  try {
    var required = require(options.formatError)
  } catch (err) {
    console.error('Could not require formatError: ' + options.formatError, err)
  }
  // support exports.formatError and module.exports = function
  options.formatError = required.formatError || required
  if (!helper.isFunction(options.formatError)) {
    console.error('Format error must be a function, got: ' + typeof options.formatError)
    process.exit(1)
  }
}

if (helper.isString(options.logLevel)) {
  var logConstant = constant['LOG_' + options.logLevel.toUpperCase()]
...
```

#### <a name="apidoc.element.karma.helper.isNumber"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isNumber (value)](#apidoc.element.karma.helper.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' || (isObjectLike(value) && objToString.call(value) == numberTag);
}
```
- example usage
```shell
...
  throw new TypeError('Invalid configuration: browsers option must be an array')
}

if (config.formatError && !helper.isFunction(config.formatError)) {
  throw new TypeError('Invalid configuration: formatError option must be a function.')
}

if (config.processKillTimeout && !helper.isNumber(config.processKillTimeout)) {
  throw new TypeError('Invalid configuration: processKillTimeout option must be a number.')
}

var defaultClient = config.defaultClient || {}
Object.keys(defaultClient).forEach(function (key) {
  var option = config.client[key]
  config.client[key] = helper.isDefined(option) ? option : defaultClient[key]
...
```

#### <a name="apidoc.element.karma.helper.isObject"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isObject (value)](#apidoc.element.karma.helper.isObject)
- description and source-code
```javascript
function isObject(value) {
  // Avoid a V8 JIT bug in Chrome 19-20.
  // See https://code.google.com/p/v8/issues/detail?id=2291 for more details.
  var type = typeof value;
  return !!value && (type == 'object' || type == 'function');
}
```
- example usage
```shell
...
}

var createPatternObject = function (pattern) {
if (pattern && helper.isString(pattern)) {
  return helper.isUrlAbsolute(pattern) ? new UrlPattern(pattern) : new Pattern(pattern)
}

if (helper.isObject(pattern)) {
  if (pattern.pattern && helper.isString(pattern.pattern)) {
    return helper.isUrlAbsolute(pattern.pattern)
      ? new UrlPattern(pattern.pattern)
      : new Pattern(
        pattern.pattern,
        pattern.served,
        pattern.included,
...
```

#### <a name="apidoc.element.karma.helper.isString"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isString (value)](#apidoc.element.karma.helper.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' || (isObjectLike(value) && objToString.call(value) == stringTag);
}
```
- example usage
```shell
...
      // If the same argument is defined multiple times, override.
      argumentValue = argumentValue.pop()
    }
    options[helper.dashToCamel(name)] = argumentValue
  }
})

if (helper.isString(options.autoWatch)) {
  options.autoWatch = options.autoWatch === 'true'
}

if (helper.isString(options.colors)) {
  options.colors = options.colors === 'true'
}
...
```

#### <a name="apidoc.element.karma.helper.isUrlAbsolute"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>isUrlAbsolute (url)](#apidoc.element.karma.helper.isUrlAbsolute)
- description and source-code
```javascript
isUrlAbsolute = function (url) {
  return ABS_URL.test(url)
}
```
- example usage
```shell
...

var UrlPattern = function (url) {
Pattern.call(this, url, false, true, false, false)
}

var createPatternObject = function (pattern) {
if (pattern && helper.isString(pattern)) {
  return helper.isUrlAbsolute(pattern) ? new UrlPattern(pattern) : new Pattern(pattern)
}

if (helper.isObject(pattern)) {
  if (pattern.pattern && helper.isString(pattern.pattern)) {
    return helper.isUrlAbsolute(pattern.pattern)
      ? new UrlPattern(pattern.pattern)
      : new Pattern(
...
```

#### <a name="apidoc.element.karma.helper.merge"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>merge ()](#apidoc.element.karma.helper.merge)
- description and source-code
```javascript
merge = function () {
  var args = Array.prototype.slice.call(arguments, 0)
  args.unshift({})
  return _.merge.apply({}, args)
}
```
- example usage
```shell
...
this.LOG_DISABLE = constant.LOG_DISABLE
this.LOG_ERROR = constant.LOG_ERROR
this.LOG_WARN = constant.LOG_WARN
this.LOG_INFO = constant.LOG_INFO
this.LOG_DEBUG = constant.LOG_DEBUG

this.set = function (newConfig) {
  _.merge(config, newConfig, function (obj, src) {
    // Overwrite arrays to keep consistent with #283
    if (_.isArray(src)) {
      return src
    }
  })
}
...
```

#### <a name="apidoc.element.karma.helper.mkdirIfNotExists"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>mkdirIfNotExists (directory, done)](#apidoc.element.karma.helper.mkdirIfNotExists)
- description and source-code
```javascript
function mkdir(directory, done) {
  // TODO(vojta): handle if it's a file
<span class="apidocCodeCommentSpan">  /* eslint-disable handle-callback-err */
</span>  fs.stat(directory, function (err, stat) {
    if (stat && stat.isDirectory()) {
      done()
    } else {
      mkdir(path.dirname(directory), function () {
        fs.mkdir(directory, done)
      })
    }
  })
  /* eslint-enable handle-callback-err */
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.helper.mmComparePatternWeights"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>mmComparePatternWeights (weight1, weight2)](#apidoc.element.karma.helper.mmComparePatternWeights)
- description and source-code
```javascript
mmComparePatternWeights = function (weight1, weight2) {
  var n1, n2, diff
  n1 = weight1[0]
  n2 = weight2[0]
  diff = n1 - n2
  if (diff !== 0) return diff / Math.abs(diff)
  return weight1.length > 1 ? exports.mmComparePatternWeights(weight1.slice(1), weight2.slice(1)) : 0
}
```
- example usage
```shell
...
  this.included = helper.isDefined(included) ? included : true
  this.watched = helper.isDefined(watched) ? watched : true
  this.nocache = helper.isDefined(nocache) ? nocache : false
  this.weight = helper.mmPatternWeight(pattern)
}

Pattern.prototype.compare = function (other) {
  return helper.mmComparePatternWeights(this.weight, other.weight)
}

var UrlPattern = function (url) {
  Pattern.call(this, url, false, true, false, false)
}

var createPatternObject = function (pattern) {
...
```

#### <a name="apidoc.element.karma.helper.mmPatternWeight"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>mmPatternWeight (pattern)](#apidoc.element.karma.helper.mmPatternWeight)
- description and source-code
```javascript
mmPatternWeight = function (pattern) {
  var m = new mm.Minimatch(pattern)
  if (!m.globParts) return [0, 0, 0, 0, 0, 0]
  var result = m.globParts.reduce(function (prev, p) {
    var r = p.reduce(function (prev, p) {
      return gsParser(p, prev)
    }, {glob_star: 0, ext_glob: 0, word: 0, star: 0, optional: 0, range: 0})
    if (prev === undefined) return r
    return compareWeightObject(r, prev) > 0 ? r : prev
  }, undefined)
  result.glob_sets = m.set.length
  return [result.glob_sets, result.glob_star, result.star, result.ext_glob, result.range, result.optional]
}
```
- example usage
```shell
...

var Pattern = function (pattern, served, included, watched, nocache) {
  this.pattern = pattern
  this.served = helper.isDefined(served) ? served : true
  this.included = helper.isDefined(included) ? included : true
  this.watched = helper.isDefined(watched) ? watched : true
  this.nocache = helper.isDefined(nocache) ? nocache : false
  this.weight = helper.mmPatternWeight(pattern)
}

Pattern.prototype.compare = function (other) {
  return helper.mmComparePatternWeights(this.weight, other.weight)
}

var UrlPattern = function (url) {
...
```

#### <a name="apidoc.element.karma.helper.normalizeWinPath"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>normalizeWinPath (value)](#apidoc.element.karma.helper.normalizeWinPath)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
...
config.files = config.files.map(createPatternObject).map(createPatternMapper(basePathResolve))
config.exclude = config.exclude.map(basePathResolve)
config.customContextFile = config.customContextFile && basePathResolve(config.customContextFile)
config.customDebugFile = config.customDebugFile && basePathResolve(config.customDebugFile)
config.customClientContextFile = config.customClientContextFile && basePathResolve(config.customClientContextFile)

// normalize paths on windows
config.basePath = helper.normalizeWinPath(config.basePath)
config.files = config.files.map(createPatternMapper(helper.normalizeWinPath))
config.exclude = config.exclude.map(helper.normalizeWinPath)
config.customContextFile = helper.normalizeWinPath(config.customContextFile)
config.customDebugFile = helper.normalizeWinPath(config.customDebugFile)
config.customClientContextFile = helper.normalizeWinPath(config.customClientContextFile)

// normalize urlRoot
...
```

#### <a name="apidoc.element.karma.helper.ucFirst"></a>[function <span class="apidocSignatureSpan">karma.helper.</span>ucFirst (word)](#apidoc.element.karma.helper.ucFirst)
- description and source-code
```javascript
ucFirst = function (word) {
  return word.charAt(0).toUpperCase() + word.substr(1)
}
```
- example usage
```shell
...

  // define custom launchers/preprocessors/reporters - create an inlined plugin
  var module = Object.create(null)
  var hasSomeInlinedPlugin = false
  var types = ['launcher', 'preprocessor', 'reporter']

  types.forEach(function (type) {
    var definitions = config['custom' + helper.ucFirst(type) + 's'] || {}

    Object.keys(definitions).forEach(function (name) {
var definition = definitions[name]

if (!helper.isObject(definition)) {
  return log.warn('Can not define %s %s. Definition has to be an object.', type, name)
}
...
```



# <a name="apidoc.module.karma.init"></a>[module karma.init](#apidoc.module.karma.init)

#### <a name="apidoc.element.karma.init.init"></a>[function <span class="apidocSignatureSpan">karma.</span>init (config)](#apidoc.element.karma.init.init)
- description and source-code
```javascript
init = function (config) {
  logger.setupFromConfig(config)

  var colorScheme = COLOR_SCHEME.ON

  if (helper.isDefined(config.colors)) {
    colorScheme = config.colors ? COLOR_SCHEME.ON : COLOR_SCHEME.OFF
  }
  // need to be registered before creating readlineInterface
  process.stdin.on('keypress', function (s, key) {
    sm.onKeypress(key)
  })

  var rli = readline.createInterface(process.stdin, process.stdout)
  var sm = new StateMachine(rli, colorScheme)

  rli.on('line', sm.onLine.bind(sm))

  // clean colors
  rli.on('SIGINT', function () {
    sm.kill()
    process.exit(0)
  })

  sm.on('next_question', printLogQueue)

  sm.process(questions, function (answers) {
    var cwd = process.cwd()
    var configFile = config.configFile || 'karma.conf.js'
    var isCoffee = path.extname(configFile) === '.coffee'
    var testMainFile = isCoffee ? 'test-main.coffee' : 'test-main.js'
    var formatter = formatters.createForPath(configFile)
    var processedAnswers = processAnswers(answers, getBasePath(configFile, cwd), testMainFile)
    var configFilePath = path.resolve(cwd, configFile)
    var testMainFilePath = path.resolve(cwd, testMainFile)

    if (isCoffee) {
      installPackage('coffee-script')
    }

    if (processedAnswers.generateTestMain) {
      formatter.writeRequirejsConfigFile(testMainFilePath)
      console.log(colorScheme.success(
        'RequireJS bootstrap file generated at "' + testMainFilePath + '".\n'
      ))
    }

    formatter.writeConfigFile(configFilePath, processedAnswers)
    console.log(colorScheme.success('Config file generated at "' + configFilePath + '".\n'))
  })
}
```
- example usage
```shell
...
    case 'run':
      require('./runner').run(config)
      break
    case 'stop':
      require('./stopper').stop(config)
      break
    case 'init':
      require('./init').init(config)
      break
    case 'completion':
      require('./completion').completion(config)
      break
  }
}
...
```



# <a name="apidoc.module.karma.launcher"></a>[module karma.launcher](#apidoc.module.karma.launcher)

#### <a name="apidoc.element.karma.launcher.Launcher"></a>[function <span class="apidocSignatureSpan">karma.launcher.</span>Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher)
- description and source-code
```javascript
Launcher = function (server, emitter, injector) {
  this._browsers = []
  var lastStartTime
  var self = this

  var getBrowserById = function (id) {
    for (var i = 0; i < self._browsers.length; i++) {
      if (self._browsers[i].id === id) {
        return self._browsers[i]
      }
    }

    return null
  }

  this.launchSingle = function (protocol, hostname, port, urlRoot, upstreamProxy, processKillTimeout) {
    var self = this
    return function (name) {
      if (upstreamProxy) {
        protocol = upstreamProxy.protocol
        hostname = upstreamProxy.hostname
        port = upstreamProxy.port
        urlRoot = upstreamProxy.path + urlRoot.substr(1)
      }
      var url = protocol + '//' + hostname + ':' + port + urlRoot

      var locals = {
        id: ['value', Launcher.generateId()],
        name: ['value', name],
        processKillTimeout: ['value', processKillTimeout],
        baseLauncherDecorator: ['factory', baseDecorator],
        captureTimeoutLauncherDecorator: ['factory', captureTimeoutDecorator],
        retryLauncherDecorator: ['factory', retryDecorator],
        processLauncherDecorator: ['factory', processDecorator],
        baseBrowserDecorator: ['factory', baseBrowserDecoratorFactory]
      }

      // TODO(vojta): determine script from name
      if (name.indexOf('/') !== -1) {
        name = 'Script'
      }

      try {
        var browser = injector.createChild([locals], ['launcher:' + name]).get('launcher:' + name)
      } catch (e) {
        if (e.message.indexOf('No provider for "launcher:' + name + '"') !== -1) {
          log.error('Cannot load browser "%s": it is not registered! ' +
            'Perhaps you are missing some plugin?', name)
        } else {
          log.error('Cannot load browser "%s"!\n  ' + e.stack, name)
        }

        emitter.emit('load_error', 'launcher', name)
        return
      }

      // TODO(vojta): remove in v1.0 (BC for old launchers)
      if (!browser.forceKill) {
        browser.forceKill = function () {
          var me = this
          return new Promise(function (resolve) {
            me.kill(resolve)
          })
        }

        browser.restart = function () {
          var me = this
          this.kill(function () {
            me.start(url)
          })
        }
      }

      self.jobs.add(function (args, done) {
        log.info('Starting browser %s', helper.isDefined(browser.displayName) ? browser.displayName : browser.name)

        browser.on('browser_process_failure', function () {
          done(browser.error)
        })

        browser.on('done', function () {
          // We are not done if there was an error as first the retry takes
          // place which we catch with 'browser_process_failure' if it fails
          if (browser.error || browser.state === browser.STATE_RESTARTING) return

          done(null, browser)
        })

        browser.start(url)
      }, [])

      self.jobs.run()
      self._browsers.push(browser)
    }
  }

  this.launch = function (names, concurrency) {
    log.info(
      'Launching browser%s %s with %s',
      names.length > 1 ? 's' : '',
      names.join(', '),
      concurrency === Infinity ? 'unlimited concurrency' : 'concurrency ' + concurrency
    )
    this.jobs = new Jobs({maxConcurrency: concurrency})

    var self = this
    lastStartTime = Date.now()

    if (server.loadErrors.length === 0) {
      names.forEach(function (name) {
        injector.invoke(self.launchSingle, self)(name)
      })
    } else {
      // Empty task to ensure 'end' is emitted
      this.jobs.add(function (args, done) {
        done()
      }, [])
    }

    this.jobs.on('end', function (err) {
      log.debug('Finished all browsers')

      if (err) {
        log.error(err)
      }
    })

    this.jobs.run()

    return self._browsers
  }

  this.launch.$inject = [
    'config.browsers',
    'config.concurrency',
    'config.processKillTimeout'
  ]

  this.launchSingle.$inject = [
    'config.protocol',
    'config.hostname',
    'config.port',
    'config.urlRoot',
    'config.upstreamProxy',
    'config.proces ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.launcher.Launcher"></a>[module karma.launcher.Launcher](#apidoc.module.karma.launcher.Launcher)

#### <a name="apidoc.element.karma.launcher.Launcher.Launcher"></a>[function <span class="apidocSignatureSpan">karma.launcher.</span>Launcher (server, emitter, injector)](#apidoc.element.karma.launcher.Launcher.Launcher)
- description and source-code
```javascript
Launcher = function (server, emitter, injector) {
  this._browsers = []
  var lastStartTime
  var self = this

  var getBrowserById = function (id) {
    for (var i = 0; i < self._browsers.length; i++) {
      if (self._browsers[i].id === id) {
        return self._browsers[i]
      }
    }

    return null
  }

  this.launchSingle = function (protocol, hostname, port, urlRoot, upstreamProxy, processKillTimeout) {
    var self = this
    return function (name) {
      if (upstreamProxy) {
        protocol = upstreamProxy.protocol
        hostname = upstreamProxy.hostname
        port = upstreamProxy.port
        urlRoot = upstreamProxy.path + urlRoot.substr(1)
      }
      var url = protocol + '//' + hostname + ':' + port + urlRoot

      var locals = {
        id: ['value', Launcher.generateId()],
        name: ['value', name],
        processKillTimeout: ['value', processKillTimeout],
        baseLauncherDecorator: ['factory', baseDecorator],
        captureTimeoutLauncherDecorator: ['factory', captureTimeoutDecorator],
        retryLauncherDecorator: ['factory', retryDecorator],
        processLauncherDecorator: ['factory', processDecorator],
        baseBrowserDecorator: ['factory', baseBrowserDecoratorFactory]
      }

      // TODO(vojta): determine script from name
      if (name.indexOf('/') !== -1) {
        name = 'Script'
      }

      try {
        var browser = injector.createChild([locals], ['launcher:' + name]).get('launcher:' + name)
      } catch (e) {
        if (e.message.indexOf('No provider for "launcher:' + name + '"') !== -1) {
          log.error('Cannot load browser "%s": it is not registered! ' +
            'Perhaps you are missing some plugin?', name)
        } else {
          log.error('Cannot load browser "%s"!\n  ' + e.stack, name)
        }

        emitter.emit('load_error', 'launcher', name)
        return
      }

      // TODO(vojta): remove in v1.0 (BC for old launchers)
      if (!browser.forceKill) {
        browser.forceKill = function () {
          var me = this
          return new Promise(function (resolve) {
            me.kill(resolve)
          })
        }

        browser.restart = function () {
          var me = this
          this.kill(function () {
            me.start(url)
          })
        }
      }

      self.jobs.add(function (args, done) {
        log.info('Starting browser %s', helper.isDefined(browser.displayName) ? browser.displayName : browser.name)

        browser.on('browser_process_failure', function () {
          done(browser.error)
        })

        browser.on('done', function () {
          // We are not done if there was an error as first the retry takes
          // place which we catch with 'browser_process_failure' if it fails
          if (browser.error || browser.state === browser.STATE_RESTARTING) return

          done(null, browser)
        })

        browser.start(url)
      }, [])

      self.jobs.run()
      self._browsers.push(browser)
    }
  }

  this.launch = function (names, concurrency) {
    log.info(
      'Launching browser%s %s with %s',
      names.length > 1 ? 's' : '',
      names.join(', '),
      concurrency === Infinity ? 'unlimited concurrency' : 'concurrency ' + concurrency
    )
    this.jobs = new Jobs({maxConcurrency: concurrency})

    var self = this
    lastStartTime = Date.now()

    if (server.loadErrors.length === 0) {
      names.forEach(function (name) {
        injector.invoke(self.launchSingle, self)(name)
      })
    } else {
      // Empty task to ensure 'end' is emitted
      this.jobs.add(function (args, done) {
        done()
      }, [])
    }

    this.jobs.on('end', function (err) {
      log.debug('Finished all browsers')

      if (err) {
        log.error(err)
      }
    })

    this.jobs.run()

    return self._browsers
  }

  this.launch.$inject = [
    'config.browsers',
    'config.concurrency',
    'config.processKillTimeout'
  ]

  this.launchSingle.$inject = [
    'config.protocol',
    'config.hostname',
    'config.port',
    'config.urlRoot',
    'config.upstreamProxy',
    'config.proces ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.launcher.Launcher.generateId"></a>[function <span class="apidocSignatureSpan">karma.launcher.Launcher.</span>generateId ()](#apidoc.element.karma.launcher.Launcher.generateId)
- description and source-code
```javascript
generateId = function () {
  return '' + Math.floor(Math.random() * 100000000)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.logger"></a>[module karma.logger](#apidoc.module.karma.logger)

#### <a name="apidoc.element.karma.logger.create"></a>[function <span class="apidocSignatureSpan">karma.logger.</span>create (name, level)](#apidoc.element.karma.logger.create)
- description and source-code
```javascript
create = function (name, level) {
  var logger = log4js.getLogger(name || 'karma')
  if (helper.isDefined(level)) {
    logger.setLevel(level)
  }
  return logger
}
```
- example usage
```shell
...
// The browser got permanently disconnected (being removed from the collection and destroyed).
var DISCONNECTED = 5

var Browser = function (id, fullName, /* capturedBrowsers */ collection, emitter, socket, timer,
/* config.browserDisconnectTimeout */ disconnectDelay,
/* config.browserNoActivityTimeout */ noActivityTimeout) {
var name = helper.browserFullNameToShort(fullName)
var log = logger.create(name)
var activeSockets = [socket]
var activeSocketsIds = function () {
  return activeSockets.map(function (s) {
    return s.id
  }).join(', ')
}
...
```

#### <a name="apidoc.element.karma.logger.setup"></a>[function <span class="apidocSignatureSpan">karma.logger.</span>setup (level, colors, appenders)](#apidoc.element.karma.logger.setup)
- description and source-code
```javascript
setup = function (level, colors, appenders) {
  // Turn color on/off on the console appenders with pattern layout
  var pattern = colors ? constant.COLOR_PATTERN : constant.NO_COLOR_PATTERN

  // If there are no appenders use the default one
  appenders = helper.isDefined(appenders) ? appenders : [constant.CONSOLE_APPENDER]

  appenders = appenders.map(function (appender) {
    if (appender.type === 'console') {
      if (helper.isDefined(appender.layout) && appender.layout.type === 'pattern') {
        appender.layout.pattern = pattern
      }
    }
    return appender
  })

  // Pass the values to log4js
  log4js.setGlobalLogLevel(level)
  log4js.configure({
    appenders: appenders
  })
}
```
- example usage
```shell
...
    config.hostname = defaultHostname
  }
  if (config.listenAddress === null) {
    config.listenAddress = defaultListenAddress
  }

  // configure the logger as soon as we can
  logger.setup(config.logLevel, config.colors, config.loggers)

  return normalizeConfig(config, configFilePath)
}

// PUBLIC API
exports.parseConfig = parseConfig
exports.Pattern = Pattern
...
```

#### <a name="apidoc.element.karma.logger.setupFromConfig"></a>[function <span class="apidocSignatureSpan">karma.logger.</span>setupFromConfig (config, appenders)](#apidoc.element.karma.logger.setupFromConfig)
- description and source-code
```javascript
setupFromConfig = function (config, appenders) {
  var useColors = true
  var logLevel = constant.LOG_INFO

  if (helper.isDefined(config.colors)) {
    useColors = config.colors
  }

  if (helper.isDefined(config.logLevel)) {
    logLevel = config.logLevel
  }
  setup(logLevel, useColors, appenders)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.plugin"></a>[module karma.plugin](#apidoc.module.karma.plugin)

#### <a name="apidoc.element.karma.plugin.resolve"></a>[function <span class="apidocSignatureSpan">karma.plugin.</span>resolve (plugins, emitter)](#apidoc.element.karma.plugin.resolve)
- description and source-code
```javascript
resolve = function (plugins, emitter) {
  var modules = []

  var requirePlugin = function (name) {
    log.debug('Loading plugin %s.', name)
    try {
      modules.push(require(name))
    } catch (e) {
      if (e.code === 'MODULE_NOT_FOUND' && e.message.indexOf(name) !== -1) {
        log.error('Cannot find plugin "%s".\n  Did you forget to install it?\n' +
          '  npm install %s --save-dev', name, name)
      } else {
        log.error('Error during loading "%s" plugin:\n  %s', name, e.message)
      }
      emitter.emit('load_error', 'plug_in', name)
    }
  }

  plugins.forEach(function (plugin) {
    if (helper.isString(plugin)) {
      if (plugin.indexOf('*') === -1) {
        requirePlugin(plugin)
        return
      }
      var pluginDirectory = path.normalize(path.join(__dirname, '/../..'))
      var regexp = new RegExp('^' + plugin.replace('*', '.*'))

      log.debug('Loading %s from %s', plugin, pluginDirectory)
      fs.readdirSync(pluginDirectory).filter(function (pluginName) {
        return IGNORED_PACKAGES.indexOf(pluginName) === -1 && regexp.test(pluginName)
      }).forEach(function (pluginName) {
        requirePlugin(pluginDirectory + '/' + pluginName)
      })
      return
    }
    if (helper.isObject(plugin)) {
      log.debug('Loading inlined plugin (defining %s).', Object.keys(plugin).join(', '))
      modules.push(plugin)
      return
    }
    log.error('Invalid plugin %s', plugin)
    emitter.emit('load_error', 'plug_in', plugin)
  })

  return modules
}
```
- example usage
```shell
...
  } else if (fs.existsSync('./.config/karma.conf.coffee')) {
    configFile = './.config/karma.conf.coffee'
  } else if (fs.existsSync('./.config/karma.conf.ts')) {
    configFile = './.config/karma.conf.ts'
  }
}

options.configFile = configFile ? path.resolve(configFile) : null

return options
}

var parseClientArgs = function (argv) {
// extract any args after '--' as clientArgs
var clientArgs = []
...
```



# <a name="apidoc.module.karma.preprocessor"></a>[module karma.preprocessor](#apidoc.module.karma.preprocessor)

#### <a name="apidoc.element.karma.preprocessor.createPreprocessor"></a>[function <span class="apidocSignatureSpan">karma.preprocessor.</span>createPreprocessor (config, basePath, injector)](#apidoc.element.karma.preprocessor.createPreprocessor)
- description and source-code
```javascript
createPreprocessor = function (config, basePath, injector) {
  var alreadyDisplayedErrors = {}
  var instances = {}
  var patterns = Object.keys(config)

  var emitter = injector.get('emitter')

  var instantiatePreprocessor = function (name) {
    if (alreadyDisplayedErrors[name]) {
      return
    }

    var p

    try {
      p = injector.get('preprocessor:' + name)
    } catch (e) {
      if (e.message.indexOf('No provider for "preprocessor:' + name + '"') !== -1) {
        log.error('Can not load "%s", it is not registered!\n  ' +
          'Perhaps you are missing some plugin?', name)
      } else {
        log.error('Can not load "%s"!\n  ' + e.stack, name)
      }
      alreadyDisplayedErrors[name] = true
      emitter.emit('load_error', 'preprocessor', name)
    }

    return p
  }

  var allPreprocessors = []
  patterns.forEach(function (pattern) {
    allPreprocessors = combineLists(allPreprocessors, config[pattern])
  })
  allPreprocessors.forEach(instantiatePreprocessor)

  return function preprocess (file, done) {
    patterns = Object.keys(config)

    return fs.readFile(file.originalPath, function (err, buffer) {
      if (err) {
        throw err
      }

      isBinaryFile(buffer, buffer.length, function (err, thisFileIsBinary) {
        if (err) {
          throw err
        }

        var preprocessorNames = []
        for (var i = 0; i < patterns.length; i++) {
          if (mm(file.originalPath, patterns[i], {dot: true})) {
            if (thisFileIsBinary) {
              log.warn('Ignoring preprocessing (%s) %s because it is a binary file.',
                config[patterns[i]].join(', '), file.originalPath)
            } else {
              preprocessorNames = combineLists(preprocessorNames, config[patterns[i]])
            }
          }
        }

        var preprocessors = []
        var nextPreprocessor = createNextProcessor(preprocessors, file, done)
        preprocessorNames.forEach(function (name) {
          var p = instances[name]
          if (p == null) {
            p = instantiatePreprocessor(name)
          }

          if (p == null) {
            if (!alreadyDisplayedErrors[name]) {
              alreadyDisplayedErrors[name] = true
              log.error('Failed to instantiate preprocessor %s', name)
              emitter.emit('load_error', 'preprocessor', name)
            }
            return
          }

          instances[name] = p
          preprocessors.push(p)
        })

        nextPreprocessor(null, thisFileIsBinary ? buffer : buffer.toString())
      })
    })
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.reporter"></a>[module karma.reporter](#apidoc.module.karma.reporter)

#### <a name="apidoc.element.karma.reporter.createReporters"></a>[function <span class="apidocSignatureSpan">karma.reporter.</span>createReporters (names, config, emitter, injector)](#apidoc.element.karma.reporter.createReporters)
- description and source-code
```javascript
createReporters = function (names, config, emitter, injector) {
  var errorFormatter = createErrorFormatter(config, emitter, SourceMapConsumer)
  var reporters = []

  // TODO(vojta): instantiate all reporters through DI
  names.forEach(function (name) {
    if (['dots', 'progress'].indexOf(name) !== -1) {
      var Cls = require('./reporters/' + name)
      var ClsColor = require('./reporters/' + name + '_color')
      reporters.push(new Cls(errorFormatter, config.reportSlowerThan, config.colors, config.browserConsoleLogOptions))
      return reporters.push(new ClsColor(errorFormatter, config.reportSlowerThan, config.colors, config.browserConsoleLogOptions
))
    }

    var locals = {
      baseReporterDecorator: ['factory', baseReporterDecoratorFactory],
      formatError: ['value', errorFormatter]
    }

    try {
      log.debug('Trying to load reporter: %s', name)
      reporters.push(injector.createChild([locals], ['reporter:' + name]).get('reporter:' + name))
    } catch (e) {
      if (e.message.indexOf('No provider for "reporter:' + name + '"') !== -1) {
        log.error('Can not load reporter "%s", it is not registered!\n  ' +
          'Perhaps you are missing some plugin?', name)
      } else {
        log.error('Can not load "%s"!\n  ' + e.stack, name)
      }
      emitter.emit('load_error', 'reporter', name)
      return
    }
    var colorName = name + '_color'
    if (names.indexOf(colorName) !== -1) {
      return
    }
    try {
      log.debug('Trying to load color-version of reporter: %s (%s)', name, colorName)
      reporters.push(injector.createChild([locals], ['reporter:' + name + '_color']).get('reporter:' + name))
    } catch (e) {
      log.debug('Couldn\'t load color-version.')
    }
  })

  // bind all reporters
  reporters.forEach(function (reporter) {
    emitter.bind(reporter)
  })

  return new MultiReporter(reporters)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.runner"></a>[module karma.runner](#apidoc.module.karma.runner)

#### <a name="apidoc.element.karma.runner.run"></a>[function <span class="apidocSignatureSpan">karma.runner.</span>run (config, done)](#apidoc.element.karma.runner.run)
- description and source-code
```javascript
run = function (config, done) {
  config = config || {}

  logger.setupFromConfig(config)

  done = helper.isFunction(done) ? done : process.exit
  config = cfg.parseConfig(config.configFile, config)

  var exitCode = 1
  var options = {
    hostname: config.hostname,
    path: config.urlRoot + 'run',
    port: config.port,
    method: 'POST',
    headers: {
      'Content-Type': 'application/json'
    }
  }

  var request = http.request(options, function (response) {
    response.on('data', function (buffer) {
      var parsedResult = parseExitCode(buffer, exitCode, config.failOnEmptyTestSuite)
      exitCode = parsedResult.exitCode
      process.stdout.write(parsedResult.buffer)
    })

    response.on('end', function () {
      done(exitCode)
    })
  })

  request.on('error', function (e) {
    if (e.code === 'ECONNREFUSED') {
      log.error('There is no server listening on port %d', options.port)
      done(1, e.code)
    } else {
      throw e
    }
  })

  request.end(JSON.stringify({
    args: config.clientArgs,
    removedFiles: config.removedFiles,
    changedFiles: config.changedFiles,
    addedFiles: config.addedFiles,
    refresh: config.refresh,
    colors: config.colors
  }))
}
```
- example usage
```shell
...
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
    break
  case 'stop':
    require('./stopper').stop(config)
    break
  case 'init':
    require('./init').init(config)
    break
...
```



# <a name="apidoc.module.karma.server"></a>[module karma.server](#apidoc.module.karma.server)

#### <a name="apidoc.element.karma.server.start"></a>[function <span class="apidocSignatureSpan">karma.server.</span>start (cliOptions, done)](#apidoc.element.karma.server.start)
- description and source-code
```javascript
start = function (cliOptions, done) {
  console.error('WARN 'start' method is deprecated since 0.13. It will be removed in 0.14. Please use \n' +
    '  server = new Server(config, [done])\n' +
    '  server.start()\n' +
    'instead.')
  var server = new Server(cliOptions, done)
  server.start()
}
```
- example usage
```shell
...
}

exports.run = function () {
var config = exports.process()

switch (config.cmd) {
  case 'start':
    new Server(config).start()
    break
  case 'run':
    require('./runner').run(config)
    break
  case 'stop':
    require('./stopper').stop(config)
    break
...
```



# <a name="apidoc.module.karma.stopper"></a>[module karma.stopper](#apidoc.module.karma.stopper)

#### <a name="apidoc.element.karma.stopper.stop"></a>[function <span class="apidocSignatureSpan">karma.stopper.</span>stop (config, done)](#apidoc.element.karma.stopper.stop)
- description and source-code
```javascript
stop = function (config, done) {
  config = config || {}
  logger.setupFromConfig(config)
  done = helper.isFunction(done) ? done : process.exit
  var log = logger.create('stopper')
  config = cfg.parseConfig(config.configFile, config)

  var options = {
    hostname: config.hostname,
    path: config.urlRoot + 'stop',
    port: config.port,
    method: 'GET'
  }

  var request = http.request(options)

  request.on('response', function (response) {
    if (response.statusCode !== 200) {
      log.error('Server returned status code: ' + response.statusCode)
      done(1)
      return
    }

    log.info('Server stopped.')
    done(0)
  })

  request.on('error', function (e) {
    if (e.code === 'ECONNREFUSED') {
      log.error('There is no server listening on port %d', options.port)
      done(1, e.code)
    } else {
      throw e
    }
  })
  request.end()
}
```
- example usage
```shell
...
case 'start':
  new Server(config).start()
  break
case 'run':
  require('./runner').run(config)
  break
case 'stop':
  require('./stopper').stop(config)
  break
case 'init':
  require('./init').init(config)
  break
case 'completion':
  require('./completion').completion(config)
  break
...
```



# <a name="apidoc.module.karma.temp_dir"></a>[module karma.temp_dir](#apidoc.module.karma.temp_dir)

#### <a name="apidoc.element.karma.temp_dir.create"></a>[function <span class="apidocSignatureSpan">karma.temp_dir.</span>create (path)](#apidoc.element.karma.temp_dir.create)
- description and source-code
```javascript
create = function (path) {
  log.debug('Creating temp dir at %s', path)

  try {
    fs.mkdirSync(path)
  } catch (e) {
    log.warn('Failed to create a temp dir at %s', path)
  }

  return path
}
```
- example usage
```shell
...
// The browser got permanently disconnected (being removed from the collection and destroyed).
var DISCONNECTED = 5

var Browser = function (id, fullName, /* capturedBrowsers */ collection, emitter, socket, timer,
/* config.browserDisconnectTimeout */ disconnectDelay,
/* config.browserNoActivityTimeout */ noActivityTimeout) {
var name = helper.browserFullNameToShort(fullName)
var log = logger.create(name)
var activeSockets = [socket]
var activeSocketsIds = function () {
  return activeSockets.map(function (s) {
    return s.id
  }).join(', ')
}
...
```

#### <a name="apidoc.element.karma.temp_dir.getPath"></a>[function <span class="apidocSignatureSpan">karma.temp_dir.</span>getPath (suffix)](#apidoc.element.karma.temp_dir.getPath)
- description and source-code
```javascript
getPath = function (suffix) {
  return path.normalize(TEMP_DIR + suffix)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma.temp_dir.remove"></a>[function <span class="apidocSignatureSpan">karma.temp_dir.</span>remove (path, done)](#apidoc.element.karma.temp_dir.remove)
- description and source-code
```javascript
remove = function (path, done) {
  log.debug('Cleaning temp dir %s', path)
  rimraf(path, done)
}
```
- example usage
```shell
...
var self = this
var pendingDisconnect
var disconnect = function (reason) {
  self.state = DISCONNECTED
  self.disconnectsCount++
  log.warn('Disconnected (%d times)' + (reason || ''), self.disconnectsCount)
  emitter.emit('browser_error', self, 'Disconnected' + reason)
  collection.remove(self)
}

var noActivityTimeoutId
var refreshNoActivityTimeout = noActivityTimeout ? function () {
  clearNoActivityTimeout()
  noActivityTimeoutId = timer.setTimeout(function () {
    self.lastResult.totalTimeEnd()
...
```



# <a name="apidoc.module.karma.url"></a>[module karma.url](#apidoc.module.karma.url)

#### <a name="apidoc.element.karma.url.url"></a>[function <span class="apidocSignatureSpan">karma.</span>url (path)](#apidoc.element.karma.url.url)
- description and source-code
```javascript
url = function (path) {
  this.path = path
  this.isUrl = true
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.url.prototype"></a>[module karma.url.prototype](#apidoc.module.karma.url.prototype)

#### <a name="apidoc.element.karma.url.prototype.toString"></a>[function <span class="apidocSignatureSpan">karma.url.prototype.</span>toString ()](#apidoc.element.karma.url.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return this.path
}
```
- example usage
```shell
...




var fs = require('graceful-fs')
var path = require('path')

var pkg = JSON.parse(fs.readFileSync(path.join(__dirname, '/../package.json')).toString())

exports.VERSION = pkg.version

exports.DEFAULT_PORT = process.env.PORT || 9876
exports.DEFAULT_HOSTNAME = process.env.IP || 'localhost'
exports.DEFAULT_LISTEN_ADDR = process.env.LISTEN_ADDR || '0.0.0.0'
...
```



# <a name="apidoc.module.karma.watcher"></a>[module karma.watcher](#apidoc.module.karma.watcher)

#### <a name="apidoc.element.karma.watcher.watch"></a>[function <span class="apidocSignatureSpan">karma.watcher.</span>watch (patterns, excludes, fileList, usePolling, emitter)](#apidoc.element.karma.watcher.watch)
- description and source-code
```javascript
watch = function (patterns, excludes, fileList, usePolling, emitter) {
  var watchedPatterns = getWatchedPatterns(patterns)
  var options = {
    usePolling: usePolling,
    ignorePermissionErrors: true,
    ignoreInitial: true,
    ignored: createIgnore(watchedPatterns, excludes)
  }
  var chokidarWatcher = new chokidar.FSWatcher(options)

  watchPatterns(watchedPatterns, chokidarWatcher)

  var bind = function (fn) {
    return function (path) {
      return fn.call(fileList, helper.normalizeWinPath(path))
    }
  }

  // register events
  chokidarWatcher.on('add', bind(fileList.addFile))
    .on('change', bind(fileList.changeFile))
    .on('unlink', bind(fileList.removeFile))
    // If we don't subscribe; unhandled errors from Chokidar will bring Karma down
    // (see GH Issue #959)
    .on('error', function (e) {
      log.debug(e)
    })

  emitter.on('exit', function (done) {
    chokidarWatcher.close()
    done()
  })

  return chokidarWatcher
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma.web_server"></a>[module karma.web_server](#apidoc.module.karma.web_server)

#### <a name="apidoc.element.karma.web_server.create"></a>[function <span class="apidocSignatureSpan">karma.web_server.</span>create (injector, emitter, fileList)](#apidoc.element.karma.web_server.create)
- description and source-code
```javascript
create = function (injector, emitter, fileList) {
  var config = injector.get('config')
  common.initializeMimeTypes(config)
  var serveStaticFile = common.createServeFile(fs, path.normalize(path.join(__dirname, '/../static')), config)
  var serveFile = common.createServeFile(fs, null, config)
  var filesPromise = new common.PromiseContainer()

  // Set an empty list of files to avoid race issues with
  // file_list_modified not having been emitted yet
  filesPromise.set(Promise.resolve(fileList.files))

  emitter.on('file_list_modified', function (files) {
    filesPromise.set(Promise.resolve(files))
  })

  // locals for webserver module
  // NOTE(vojta): figure out how to do this with DI
  injector = injector.createChild([{
    serveFile: ['value', serveFile],
    serveStaticFile: ['value', serveStaticFile],
    filesPromise: ['value', filesPromise]
  }])

  var proxyMiddlewareInstance = injector.invoke(proxyMiddleware.create)

  log.debug('Instantiating middleware')
  var handler = connect()

  if (config.beforeMiddleware) {
    config.beforeMiddleware.forEach(function (middleware) {
      handler.use(injector.get('middleware:' + middleware))
    })
  }

  handler.use(injector.invoke(runnerMiddleware.create))
  handler.use(injector.invoke(stopperMiddleware.create))
  handler.use(injector.invoke(stripHostMiddleware.create))
  handler.use(injector.invoke(karmaMiddleware.create))
  handler.use(injector.invoke(sourceFilesMiddleware.create))
  // TODO(vojta): extract the proxy into a plugin
  handler.use(proxyMiddlewareInstance)
  // TODO(vojta): remove, this is only here because of karma-dart
  // we need a better way of custom handlers
  handler.use(injector.invoke(createCustomHandler))

  if (config.middleware) {
    config.middleware.forEach(function (middleware) {
      handler.use(injector.get('middleware:' + middleware))
    })
  }

  handler.use(function (request, response) {
    common.serve404(response, request.url)
  })

  var serverClass = http
  var serverArguments = [handler]

  if (config.protocol === 'https:') {
    serverClass = https
    serverArguments.unshift(config.httpsServerOptions || {})
  }

  if (config.httpModule) {
    serverClass = config.httpModule
  }

  var server = serverClass.createServer.apply(null, serverArguments)

  server.on('upgrade', function (req, socket, head) {
    log.debug('upgrade %s', req.url)
    proxyMiddlewareInstance.upgrade(req, socket, head)
  })

  return server
}
```
- example usage
```shell
...
// The browser got permanently disconnected (being removed from the collection and destroyed).
var DISCONNECTED = 5

var Browser = function (id, fullName, /* capturedBrowsers */ collection, emitter, socket, timer,
/* config.browserDisconnectTimeout */ disconnectDelay,
/* config.browserNoActivityTimeout */ noActivityTimeout) {
var name = helper.browserFullNameToShort(fullName)
var log = logger.create(name)
var activeSockets = [socket]
var activeSocketsIds = function () {
  return activeSockets.map(function (s) {
    return s.id
  }).join(', ')
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
