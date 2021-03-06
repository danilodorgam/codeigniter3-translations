############################################
Translations for CodeIgniter System Messages
############################################

This project contains translations for the CodeIgniter
system messages folder, **system/language/english**.
A changelog has been added to the repository, so you can track updates
between official releases.

Copy the folder(s) for the idioms you are interested in,
from inside the **language** folder of this project to your
**application/language** folder.

You may then use the CodeIgniter Language class to reference the translations
directly, or you can set the default language in **application/config/config**
to the idiom appropriate for your webapp.

There have been several questions about RTL languages, but that is not
something addressed in CodeIgniter. The suggested approach is to keep any
translations in left-to-right order, and to deal with right-to-left
rendering through the "dir" attribute of an HTML element, or the "direction"
attribute in CSS.

**********************
Repository Information
**********************

Each language is maintained by a community member, per the table below:

=======================  ===========  =================  =========================
Idiom                    Status       User               Maintainer
=======================  ===========  =================  =========================
arabic                   3.1.4        daif               Daif Alotaibi
armenian                 3.1.4        tgrnmrdn           Tigran Muradyan
azerbaijani              3.1.4        Qarakom            Sübhan Cabbarov
bengali                  3.1.4        kabircse           Kabir Hossain
bulgarian                3.1.4        ivantcholakov      Ivan Tcholakov
catalan                  3.1.4        Ignasimg           Ignasi Molsosa
czech                    3.1.4        Ruplahlava         Štěpán Postránecký
dutch                    3.1.4        pkrul              Pieter Krul
filipino                 3.1.4        dzerium            Edzer Josh V. Padilla
french                   3.1.4        includebeer        Alain Rivest
german                   3.1.4        Rufnex             Johannes Gamperl 
greek                    3.1.4        xargr              Grigoris Charamidis
gujarati                 3.1.4        sajid19991         Sajid Mathupotra
hindi                    3.1.4        shindesushilkumar  Sushilkumar Shinde
hungarian                3.1.4        orionstar          László Bóra
indonesian               3.1.4        ridho1991          Mutasim Ridlo
italian                  3.1.4        ster               Stefano Mazzega
japanese                 3.1.4        tsukasa            Tsukasa Takao ???
khmer                    3.1.4        Chanthoeun         Chanthoeun Kim
latvian                  3.1.4        DavisMiculis       Davis Miculis
lithuanian               3.1.4        dgvirtual          Donatas Glodenis
korean                   3.1.4        KwonLatte          HyeongJoo Kwon
norwegian                3.1.4        yhoiseth           Yngve Hoiseth
persian                  3.1.4        MSDehghan          Mohammad Sadegh
polish                   3.1.4        michalsn           Michał Śniatała
portuguese               3.1.4        j38600             Júlio Sebastião
portuguese-brazilian     3.1.4        mateusfbi          Mateus Brandão
romanian                 3.1.4        CodefishRo         Cristian Robert Chiribuc
russian                  3.1.4        vadimyer           Vadim Yermolin
serbian                  3.1.4        novakurosevic      Novak Urosevic ???
simplified-chinese       3.1.4        denghongcai        Deng HongCai
slovak                   3.1.4        gadelat            Gabriel Potkány
slovenian                3.1.4        andrejflorjancic   Andrej Florjančič
spanish                  3.1.4        Razican            Iban Eguia
swedish                  3.1.4        peterdenk          Peter Denk
tamil                    3.1.4        karthik-code       Karthikeyan
thai                     3.1.4        karidoe            Anuchit Thiam-uan
traditional-chinese      3.1.4        appleboy           Bo-Yi Wu
turkish                  3.1.4        obozdag            Osman Bozdag
ukranian                 3.1.4        flybot             Sergiy Kosiy
urdu                     3.1.4        codeonion          Muhammad Ali
vietnamese               3.1.4        tinhphaistc        Trần Xuân Sâm ???
=======================  ===========  =================  =========================

************
Requirements
************

These translations are intended for use with CodeIgniter 3.x.

*******
License
*******

These translations are licensed under the `MIT license <license.txt>`_.

************
Contributing
************

If you have a translation or correction, please fork the repository, clone it
locally, and then create a new branch (from develop)
for each set of related changes or for
a complete language pack. Once your branch is complete, *then* create a pull
request to merge it into the main repository. Remember to "sign" your commits.

Pull requests to the repository will only be considered if they come from
the maintainer for any translations in the request, or if the maintainer
adds a comment indicating they approve of any changes.

If you would like provide a translation, please send me an email, with
your name, github account, and a brief explanation of your suitability.

`Jim Parry <jim_parry@bcit.ca>`_
