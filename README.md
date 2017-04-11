# test coverage for  [highlight.js (v9.10.0)](https://highlightjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-highlight.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-highlight.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-highlight.js.svg)](https://travis-ci.org/npmtest/node-npmtest-highlight.js)
#### Syntax highlighting with language autodetection.

[![NPM](https://nodei.co/npm/highlight.js.png?downloads=true)](https://www.npmjs.com/package/highlight.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-highlight.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-highlight.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-highlight.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-highlight.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-highlight.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-highlight.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-highlight.js/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-highlight.js/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-highlight.js/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-highlight.js/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-highlight.js%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-highlight.js/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-highlight.js%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highlight.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-highlight.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-highlight.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Sagalaev",
        "email": "maniac@softwaremaniacs.org"
    },
    "bugs": {
        "url": "https://github.com/isagalaev/highlight.js/issues"
    },
    "contributors": [
        {
            "name": "Ivan Sagalaev",
            "email": "maniac@softwaremaniacs.org",
            "url": "original author"
        },
        {
            "name": "Jeremy Hull",
            "email": "sourdrums@gmail.com"
        },
        {
            "name": "Oleg Efimov",
            "email": "efimovov@gmail.com"
        },
        {
            "name": "Peter Leonov",
            "email": "gojpeg@gmail.com"
        },
        {
            "name": "Victor Karamzin",
            "email": "Victor.Karamzin@enterra-inc.com"
        },
        {
            "name": "Vsevolod Solovyov",
            "email": "vsevolod.solovyov@gmail.com"
        },
        {
            "name": "Anton Kovalyov",
            "email": "anton@kovalyov.net"
        },
        {
            "name": "Nikita Ledyaev",
            "email": "lenikita@yandex.ru"
        },
        {
            "name": "Konstantin Evdokimenko",
            "email": "qewerty@gmail.com"
        },
        {
            "name": "Dmitri Roudakov",
            "email": "dmitri@roudakov.ru"
        },
        {
            "name": "Yuri Ivanov",
            "email": "ivanov@supersoft.ru"
        },
        {
            "name": "Vladimir Ermakov",
            "email": "vooon341@mail.ru"
        },
        {
            "name": "Vladimir Gubarkov",
            "email": "xonixx@gmail.com"
        },
        {
            "name": "Brian Beck",
            "email": "exogen@gmail.com"
        },
        {
            "name": "MajestiC",
            "email": "majestic2k@gmail.com"
        },
        {
            "name": "Vasily Polovnyov",
            "email": "vast@whiteants.net"
        },
        {
            "name": "Vladimir Epifanov",
            "email": "voldmar@voldmar.ru"
        },
        {
            "name": "Alexander Makarov",
            "email": "sam@rmcreative.ru"
        },
        {
            "name": "Vah",
            "email": "vahtenberg@gmail.com"
        },
        {
            "name": "Shuen-Huei Guan",
            "email": "drake.guan@gmail.com"
        },
        {
            "name": "Jason Diamond",
            "email": "jason@diamond.name"
        },
        {
            "name": "Michal Gabrukiewicz",
            "email": "mgabru@gmail.com"
        },
        {
            "name": "Ruslan Keba",
            "email": "rukeba@gmail.com"
        },
        {
            "name": "Sergey Baranov",
            "email": "segyrn@yandex.ru"
        },
        {
            "name": "Zaripov Yura",
            "email": "yur4ik7@ukr.net"
        },
        {
            "name": "Oleg Volchkov",
            "email": "oleg@volchkov.net"
        },
        {
            "name": "Vasily Mikhailitchenko",
            "email": "vaskas@programica.ru"
        },
        {
            "name": "Jan Berkel",
            "email": "jan.berkel@gmail.com"
        },
        {
            "name": "Vladimir Moskva",
            "email": "vladmos@gmail.com"
        },
        {
            "name": "Loren Segal",
            "email": "lsegal@soen.ca"
        },
        {
            "name": "Andrew Fedorov",
            "email": "dmmdrs@mail.ru"
        },
        {
            "name": "Igor Kalnitsky",
            "email": "igor@kalnitsky.org"
        },
        {
            "name": "Valerii Hiora",
            "email": "valerii.hiora@gmail.com"
        },
        {
            "name": "Nikolay Zakharov",
            "email": "nikolay.desh@gmail.com"
        },
        {
            "name": "Dmitry Kovega",
            "email": "arhibot@gmail.com"
        },
        {
            "name": "Sergey Ignatov",
            "email": "sergey@ignatov.spb.su"
        },
        {
            "name": "Antono Vasiljev",
            "email": "self@antono.info"
        },
        {
            "name": "Stephan Kountso",
            "email": "steplg@gmail.com"
        },
        {
            "name": "pumbur",
            "email": "pumbur@pumbur.net"
        },
        {
            "name": "John Crepezzi",
            "email": "john.crepezzi@gmail.com"
        },
        {
            "name": "Andrey Vlasovskikh",
            "email": "andrey.vlasovskikh@gmail.com"
        },
        {
            "name": "Alexander Myadzel",
            "email": "myadzel@gmail.com"
        },
        {
            "name": "Evgeny Stepanischev",
            "email": "imbolk@gmail.com"
        },
        {
            "name": "Dmytrii Nagirniak",
            "email": "dnagir@gmail.com"
        },
        {
            "name": "Luigi Maselli",
            "email": "grigio.org@gmail.com"
        },
        {
            "name": "Denis Bardadym",
            "email": "bardadymchik@gmail.com"
        },
        {
            "name": "Aahan Krish",
            "email": "geekpanth3r@gmail.com"
        },
        {
            "name": "Ilya Baryshev",
            "email": "baryshev@gmail.com"
        },
        {
            "name": "Aleksandar Ruzicic",
            "email": "aleksandar@ruzicic.info"
        },
        {
            "name": "Joe Cheng",
            "email": "joe@rstudio.org"
        },
        {
            "name": "Angel G. Olloqui",
            "email": "angelgarcia.mail@gmail.com"
        },
        {
            "name": "Jason Tate",
            "email": "adminz@web-cms-designs.com"
        },
        {
            "name": "Sergey Tikhomirov",
            "email": "sergey@tikhomirov.io"
        },
        {
            "name": "Marc Fornos",
            "email": "marc.fornos@gmail.com"
        },
        {
            "name": "Yoshihide Jimbo",
            "email": "yjimbo@gmail.com"
        },
        {
            "name": "Casey Duncan",
            "email": "casey.duncan@gmail.com"
        },
        {
            "name": "Eugene Nizhibitsky",
            "email": "nizhibitsky@gmail.com"
        },
        {
            "name": "Alberto Gimeno",
            "email": "gimenete@gmail.com"
        },
        {
            "name": "Kirk Kimmel",
            "email": "kimmel.k.programmer@gmail.com"
        },
        {
            "name": "Nathan Grigg",
            "email": "nathan@nathanamy.org"
        },
        {
            "name": "Dr. Drang",
            "email": "drdrang@gmail.com"
        },
        {
            "name": "Robin Ward",
            "email": "robin.ward@gmail.com"
        },
        {
            "name": "Dmitry Medvinsky",
            "email": "me@dmedvinsky.name"
        },
        {
            "name": "Jason Jacobson",
            "email": "jason.a.jacobson@gmail.com"
        },
        {
            "name": "Jonas Follesø",
            "email": "jonas@follesoe.no"
        },
        {
            "name": "Dan Allen",
            "email": "dan.j.allen@gmail.com"
        },
        {
            "name": "noformnocontent",
            "email": "i@noformnocontent.com"
        },
        {
            "name": "Damien White",
            "email": "damien.white@visoftinc.com"
        },
        {
            "name": "Alexander Marenin",
            "email": "great_muchacho@mail.ru"
        },
        {
            "name": "Cédric Néhémie",
            "email": "cedric.nehemie@gmail.com"
        },
        {
            "name": "Simon Madine",
            "email": "simon@angryrobotzombie.com"
        },
        {
            "name": "Benjamin Pannell",
            "email": "contact@sierrasoftworks.com"
        },
        {
            "name": "Eric Knibbe",
            "email": "eric@lassosoft.com"
        },
        {
            "name": "Poren Chiang",
            "email": "ren.chiang@gmail.com"
        },
        {
            "name": "Kelley van Evert",
            "email": "kelleyvanevert@gmail.com"
        },
        {
            "name": "Kurt Emch",
            "email": "kurt@kurtemch.com"
        },
        {
            "name": "Mehdi Dogguy",
            "email": "mehdi@dogguy.org"
        },
        {
            "name": "Nicolas Braud-Santoni",
            "email": "nicolas.braud-santoni@ens-cachan.fr"
        },
        {
            "name": "Ralf Bitter",
            "email": "rabit@revigniter.com"
        },
        {
            "name": "Sylvestre Ledru",
            "email": "sylvestre.ledru@scilab-enterprises.com"
        },
        {
            "name": "Troy Kershaw",
            "email": "hello@troykershaw.com"
        },
        {
            "name": "Zena Treep",
            "email": "zena.treep@gmail.com"
        },
        {
            "name": "Daniel Kvasnicka",
            "email": "dkvasnicka@vendavo.com"
        },
        {
            "name": "Carlo Kok",
            "email": "ck@remobjects.com"
        },
        {
            "name": "Bram de Haan",
            "email": "info@atelierbramdehaan.nl"
        },
        {
            "name": "Seongwon Lee",
            "email": "dlimpid@gmail.com"
        },
        {
            "name": "Zaven Muradyan",
            "email": "megalivoithos@gmail.com"
        },
        {
            "name": "Jan T. Sott",
            "email": "git@idleberg.com"
        },
        {
            "name": "Brent Bradbury",
            "email": "brent@brentium.com"
        },
        {
            "name": "Martin Dilling-Hansen",
            "email": "martindlling@gmail.com"
        },
        {
            "name": "Ilya Vassilevsky",
            "email": "vassilevsky@gmail.com"
        },
        {
            "name": "Josh Adams",
            "email": "josh@isotope11.com"
        },
        {
            "name": "Dan Tao",
            "email": "daniel.tao@gmail.com"
        },
        {
            "name": "Jeff Escalante",
            "email": "hello@jenius.me"
        },
        {
            "name": "Jun Yang",
            "email": "yangjvn@126.com"
        },
        {
            "name": "Nikolay Lisienko",
            "email": "info@neor.ru"
        },
        {
            "name": "Heiko August",
            "email": "post@auge8472.de"
        },
        {
            "name": "Domen Kožar",
            "email": "domen@dev.si"
        },
        {
            "name": "Travis Odom",
            "email": "travis.a.odom@gmail.com"
        },
        {
            "name": "innocenat",
            "email": "innocenat@gmail.com"
        },
        {
            "name": "Arthur Bikmullin",
            "email": "devolonter@gmail.com"
        },
        {
            "name": "Pascal Hurni",
            "email": "phi@ruby-reactive.org"
        },
        {
            "name": "Roman Shmatov",
            "email": "romanshmatov@gmail.com"
        },
        {
            "name": "Nic West",
            "email": "nic@letolab.com"
        },
        {
            "name": "Panu Horsmalahti",
            "email": "panu.horsmalahti@iki.fi"
        },
        {
            "name": "Flaviu Tamas",
            "email": "tamas.flaviu@gmail.com"
        },
        {
            "name": "Damian Mee",
            "email": "mee.damian@gmail.com"
        },
        {
            "name": "Christopher Kaster",
            "email": "ikasoki@gmail.com"
        },
        {
            "name": "Chris Eidhof",
            "email": "chris@eidhof.nl"
        },
        {
            "name": "Nate Cook",
            "email": "natecook@gmail.com"
        },
        {
            "name": "Matt Diephouse",
            "email": "matt@diephouse.com"
        },
        {
            "name": "Erik Osheim",
            "email": "d_m@plastic-idolatry.com"
        },
        {
            "name": "Guillaume Laforge",
            "email": "glaforge@gmail.com"
        },
        {
            "name": "Lucas Mazza",
            "email": "lucastmazza@gmail.com"
        },
        {
            "name": "Maxim Dikun",
            "email": "dikmax@gmail.com"
        },
        {
            "name": "Henrik Feldt",
            "email": "henrik@haf.se"
        },
        {
            "name": "Anton Kochkov",
            "email": "anton.kochkov@gmail.com"
        },
        {
            "name": "Michael Allen",
            "email": "Michael.Allen@benefitfocus.com"
        },
        {
            "name": "JP Verkamp",
            "email": "me@jverkamp.com"
        },
        {
            "name": "Adam Joseph Cook",
            "email": "adam.joseph.cook@gmail.com"
        },
        {
            "name": "Sergey Vidyuk",
            "email": "svidyuk@gmail.com"
        },
        {
            "name": "Radek Liska",
            "email": "radekliska@gmail.com"
        },
        {
            "name": "Jose Molina Colmenero",
            "email": "gaudy41@gmail.com"
        },
        {
            "name": "Max Mikhailov",
            "email": "seven.phases.max@gmail.com"
        },
        {
            "name": "Bryant Williams",
            "email": "b.n.williams@gmail.com"
        },
        {
            "name": "Erik Paluka",
            "email": "erik.paluka@gmail.com"
        },
        {
            "name": "Luke Holder",
            "email": "lukemh@gmail.com"
        },
        {
            "name": "David Mohundro",
            "email": "david@mohundro.com"
        },
        {
            "name": "Nicholas Blumhardt",
            "email": "nblumhardt@nblumhardt.com"
        },
        {
            "name": "Christophe de Dinechin",
            "email": "christophe@taodyne.com"
        },
        {
            "name": "Taneli Vatanen",
            "email": "taneli.vatanen@gmail.com"
        },
        {
            "name": "Jen Evers-Corvina",
            "email": "jen@sevvie.net"
        },
        {
            "name": "Kassio Borges",
            "email": "kassioborgesm@gmail.com"
        },
        {
            "name": "Cedric Sohrauer",
            "email": "sohrauer@googlemail.com"
        },
        {
            "name": "Mickaël Delahaye",
            "email": "mickael.delahaye@gmail.com"
        },
        {
            "name": "Hakan Özler",
            "email": "ozler.hakan@gmail.com"
        },
        {
            "name": "Trey Shugart",
            "email": "treshugart@gmail.com"
        },
        {
            "name": "Vincent Zurczak",
            "email": "vzurczak@linagora.com"
        },
        {
            "name": "Adam Joseph Cook",
            "email": "adam.joseph.cook@gmail.com"
        },
        {
            "name": "Edwin Dalorzo",
            "email": "edwin@dalorzo.org"
        },
        {
            "name": "mucaho",
            "email": "mkucko@gmail.com"
        },
        {
            "name": "Dennis Titze",
            "email": "dennis.titze@gmail.com"
        },
        {
            "name": "Jon Evans",
            "email": "jon@craftyjon.com"
        },
        {
            "name": "Brian Quistorff",
            "email": "bquistorff@gmail.com"
        },
        {
            "name": "Jonathan Suever",
            "email": "suever@gmail.com"
        },
        {
            "name": "Alexis Hénaut",
            "email": "alexis@henaut.net"
        },
        {
            "name": "Chris Kiehl",
            "email": "audionautic@gmail.com"
        },
        {
            "name": "Peter Piwowarski",
            "email": "oldlaptop654@aol.com"
        },
        {
            "name": "Kenta Sato",
            "email": "bicycle1885@gmail.com"
        },
        {
            "name": "Anthony Scemama",
            "email": "scemama@irsamc.ups-tlse.fr"
        },
        {
            "name": "Taufik Nurrohman",
            "email": "latitudu.latitudu@gmail.com"
        },
        {
            "name": "Pedro Oliveira",
            "email": "kanytu@gmail.com"
        },
        {
            "name": "Gu Yiling",
            "email": "justice360@gmail.com"
        },
        {
            "name": "Thomas Applencourt",
            "email": "thomas.applencourt@irsamc.ups-tlse.fr"
        },
        {
            "name": "Andrew Farmer",
            "email": "ahfarmer@gmail.com"
        },
        {
            "name": "Sergey Mashkov",
            "email": "cy6erGn0m@gmail.com"
        },
        {
            "name": "Raivo Laanemets",
            "email": "raivo@infdot.com"
        },
        {
            "name": "Kenneth Fuglsang",
            "email": "kfuglsang@gmail.com"
        },
        {
            "name": "David Anson",
            "email": "david@dlaa.me"
        },
        {
            "name": "Louis Barranqueiro",
            "email": "louis.barranqueiro@gmail.com"
        },
        {
            "name": "Tim Schumacher",
            "email": "tim@datenknoten.me"
        },
        {
            "name": "Lucas Werkmeister",
            "email": "mail@lucaswerkmeister.de"
        },
        {
            "name": "Dan Panzarella",
            "email": "alsoelp@gmail.com"
        },
        {
            "name": "Bruno Dias",
            "email": "bruno.r.dias@gmail.com"
        },
        {
            "name": "Jay Strybis",
            "email": "jay.strybis@gmail.com"
        },
        {
            "name": "Guillaume Gomez",
            "email": "guillaume1.gomez@gmail.com"
        },
        {
            "name": "Janis Voigtländer",
            "email": "janis.voigtlaender@gmail.com"
        },
        {
            "name": "Dirk Kirsten",
            "email": "dk@basex.org"
        },
        {
            "name": "MY Sun",
            "email": "simonmysun@gmail.com"
        },
        {
            "name": "Vadimtro",
            "email": "vadimtro@yahoo.com"
        },
        {
            "name": "Benjamin Auder",
            "email": "benjamin.auder@gmail.com"
        },
        {
            "name": "Dotan Dimet",
            "email": "dotan@corky.net"
        },
        {
            "name": "Manh Tuan",
            "email": "junookyo@gmail.com"
        },
        {
            "name": "Philippe Charrière",
            "email": "ph.charriere@gmail.com"
        },
        {
            "name": "Stefan Bechert",
            "email": "stefan.bechert@gmx.net"
        },
        {
            "name": "Samuel Reed",
            "email": "sam@bitmex.com"
        },
        {
            "name": "Yury Selivanov",
            "email": "yselivanov@gmail.com"
        },
        {
            "name": "Tsuyusato Kitsune",
            "email": "make.just.on@gmail.com"
        },
        {
            "name": "Mick MacCallum",
            "email": "micksmaccallum@gmail.com"
        },
        {
            "name": "Kristoffer Gronlund",
            "email": "kgronlund@suse.com"
        },
        {
            "name": "Søren Enevoldsen",
            "email": "senevoldsen90@gmail.com"
        },
        {
            "name": "Daniel Rosenwasser",
            "email": "DanielRosenwasser@users.noreply.github.com"
        },
        {
            "name": "Ladislav Prskavec",
            "email": "ladislav@prskavec.net"
        },
        {
            "name": "Jan Kühle",
            "email": "jkuehle90@gmail.com"
        },
        {
            "name": "Stefan Wienert",
            "email": "stwienert@gmail.com"
        },
        {
            "name": "Nikita Savchenko",
            "email": "zitros.lab@gmail.com"
        },
        {
            "name": "Stefania Mellai",
            "email": "s.mellai@arduino.cc"
        },
        {
            "name": "Nebuleon Fumika",
            "email": "nebuleon.fumika@gmail.com"
        },
        {
            "name": "prince",
            "email": "MC.prince.0203@gmail.com"
        },
        {
            "name": "Brendan Rocks",
            "email": "rocks.brendan@gmail.com"
        },
        {
            "name": "Raphaël Assénat",
            "email": "raph@raphnet.net"
        },
        {
            "name": "Matt Evans",
            "email": "matt@aptech.com"
        },
        {
            "name": "Martin Braun",
            "email": "martin.braun@ettus.com"
        },
        {
            "name": "Boris Cherny",
            "email": "boris@performancejs.com"
        },
        {
            "name": "John Foster",
            "email": "jfoster@esri.com"
        },
        {
            "name": "Robert Dodier",
            "email": "robert.dodier@gmail.com"
        },
        {
            "name": "Anthony Dugois",
            "email": "dev.anthonydugois@gmail.com"
        },
        {
            "name": "Qeole",
            "email": "qeole@outlook.com"
        },
        {
            "name": "Denis Ciccale",
            "email": "dciccale@gmail.com"
        },
        {
            "name": "Michael Johnston",
            "email": "lastobelus@gmail.com"
        },
        {
            "name": "Taras",
            "email": "oxdef@oxdef.info"
        },
        {
            "name": "Philipp Wolfer",
            "email": "ph.wolfer@gmail.com"
        },
        {
            "name": "Mikko Kouhia",
            "email": "mikko.kouhia@iki.fi"
        },
        {
            "name": "Billy Quith",
            "email": "chinbillybilbo@gmail.com"
        },
        {
            "name": "Herbert Shin",
            "email": "initbar@protonmail.ch"
        },
        {
            "name": "Tristano Ajmone",
            "email": "tajmone@gmail.com"
        },
        {
            "name": "Taisuke Fujimoto",
            "email": "temp-impl@users.noreply.github.com"
        },
        {
            "name": "Boone Severson",
            "email": "boone.severson@gmail.com"
        },
        {
            "name": "Victor Zhou",
            "email": "OiCMudkips@users.noreply.github.com"
        },
        {
            "name": "Lars Schulna",
            "email": "kartoffelbrei.mit.muskatnuss@gmail.org"
        },
        {
            "name": "Jacob Childress",
            "email": "jacobc@gmail.com"
        },
        {
            "name": "Gavin Siu",
            "email": "gavsiu@gmail.com"
        },
        {
            "name": "Builder's Brewery",
            "email": "buildersbrewery@gmail.com"
        },
        {
            "name": "Sergey Bronnikov",
            "email": "sergeyb@bronevichok.ru"
        },
        {
            "name": "Joe Eli McIlvain",
            "email": "joe.eli.mac@gmail.org"
        },
        {
            "name": "Stephan Boyer",
            "email": "stephan@stephanboyer.com"
        },
        {
            "name": "Alex McKibben",
            "email": "alex@nullscope.net"
        },
        {
            "name": "Daniel Gamage",
            "email": "hellodanielgamage@gmail.com"
        },
        {
            "name": "Matthew Daly",
            "email": "matthewbdaly@gmail.com"
        },
        {
            "name": "Magnus Madsen",
            "email": "mmadsen@uwaterloo.ca"
        },
        {
            "name": "Camil Staps",
            "email": "info@camilstaps.nl"
        },
        {
            "name": "Alexander Lichter",
            "email": "manniL@gmx.net"
        },
        {
            "name": "Nicolas Le Gall",
            "email": "contact@nlegall.fr"
        },
        {
            "name": "Kenton Hamaluik",
            "email": "kentonh@gmail.com"
        },
        {
            "name": "Marvin Saignat",
            "email": "contact@zgmrvn.com"
        },
        {
            "name": "Michael Rodler",
            "email": "contact@f0rki.at"
        },
        {
            "name": "Sergey Sobko",
            "email": "s.sobko@profitware.ru"
        },
        {
            "name": "Hale Chan",
            "email": "halechan@qq.com"
        },
        {
            "name": "Matt Evans",
            "email": "syrius3@gmail.com"
        },
        {
            "name": "Kasper Andersen",
            "email": "kma_untrusted@protonmail.com"
        },
        {
            "name": "Philipp A.",
            "email": "flying-sheep@web.de"
        },
        {
            "name": "Guannan Wei",
            "email": "guannanwei@outlook.com"
        },
        {
            "name": "Sam Wu",
            "email": "samsam2310@gmail.com"
        },
        {
            "name": "Ike Ku",
            "email": "dempfi@yahoo.com"
        },
        {
            "name": "Andres Täht",
            "email": "andres.taht@gmail.com"
        },
        {
            "name": "Rene Saarsoo",
            "email": "nene@triin.net"
        }
    ],
    "dependencies": {},
    "description": "Syntax highlighting with language autodetection.",
    "devDependencies": {
        "bluebird": "^3.0.1",
        "commander": "^2.3.0",
        "del": "^2.0.2",
        "gear": "^0.9.4",
        "gear-lib": "^0.9.2",
        "glob": "^7.0.3",
        "js-beautify": "^1.5.10",
        "jsdom": "^9.2.1",
        "lodash": "^4.0.0",
        "mocha": "^2.0.1",
        "should": "^9.0.2",
        "tiny-worker": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f9f0b14c0be00f0e4fb1e577b749fed9e6f52f55",
        "tarball": "https://registry.npmjs.org/highlight.js/-/highlight.js-9.10.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://highlightjs.org/",
    "keywords": [
        "highlight",
        "syntax"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "jga",
            "email": "me@jga.me"
        },
        {
            "name": "isagalaev",
            "email": "maniac@softwaremaniacs.org"
        }
    ],
    "name": "highlight.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/isagalaev/highlight.js.git"
    },
    "scripts": {
        "test": "mocha test/",
        "test-browser": "mocha test/browser/"
    },
    "version": "9.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
