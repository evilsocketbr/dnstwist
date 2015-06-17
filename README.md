dnstwist
========
See what sort of trouble users can get in trying to type your domain name. Look for registered domains similar to your own, only distinguished by [typos](https://en.wikipedia.org/wiki/Typosquatting) (or cosmic ray). Useful as additional source of targeted threat intelligence. Can detect fraud, phishing attacks and corporate espionage.

Required modules
----------------
If you want *dnstwist* to develop full power, please make sure the following Python modules are present on your system. If missing, *dnstwist* will still work, but without some cool features.

* [Python GeoIP](https://pypi.python.org/pypi/GeoIP/)
* [A DNS toolkit for Python](http://www.dnspython.org/)

Further reading
---------------
* [Security List Network: DNSTWIST - Generate and resolve domain variation to detect typo squatting, phising and corporate espionage](http://seclist.us/dnstwist-generate-and-resolve-domain-variations-to-detect-typo-squatting-phishing-and-corporate-espionage.html)
* [Heise-Online: Dnstwist variiert und testet Domainnamen](http://www.heise.de/newsticker/meldung/Dnstwist-variiert-und-testet-Domainnamen-2690418.html)
* [Newday International: dnstwist varies and tests domain name](https://www.newday.mk/dnstwist-varies-and-tests-domain-name/)
* [ISC StormCast for Tuesday, June 16th 2015](https://isc.sans.edu/podcastdetail.html?id=4529)

Special thanks
--------------
* Patricia Lipp
* Steve Steiner
* Christopher Schmidt

Contact
-------
To send questions, comments or a chocolate, just drop an e-mail at [marcin@ulikowski.pl](mailto:marcin@ulikowski.pl)

* LinkedIn: [Marcin Ulikowski](https://pl.linkedin.com/in/elceef)
* Twitter: [@elceef](https://twitter.com/elceef)

Example report
--------------
```
$ ./dnstwist.py github.com
dnstwist (20150617) by marcin@ulikowski.pl
Processing 128 domains !!!!!!!.!..!!!..!!.!..!...!!!!!!!!!.!!!.!!!!!!.!!!!..!!!!.!!!!.!!.!!!.!!.!.!!!!!...!....!!.....!..!.!...!!....!...!....!..!!....

Bitsquatting    fithub.com      4.35.164.141/United States MX:aspmx2.googlemail.com
Bitsquatting    eithub.com      174.136.12.111/United States MX:eithub.com
Bitsquatting    cithub.com      14.63.216.242/Korea, Republic of
Bitsquatting    oithub.com      54.68.76.21/United States
Bitsquatting    withub.com      121.121.12.1/Malaysia
Bitsquatting    ghthub.com      88.198.49.109/Germany MX:ghthub.com
Bitsquatting    gkthub.com      141.8.224.183/Switzerland MX:mail.mxproc.com
Bitsquatting    gmthub.com      -
Bitsquatting    gathub.com      74.208.30.209/United States 2607:f1c0:1000:a0:cba:6ae5:8d8:d002 MX:mx00.1and1.com
Bitsquatting    gythub.com      -
Bitsquatting    giuhub.com      -
Bitsquatting    givhub.com      185.53.177.7/Germany MX:mail.h-email.net
Bitsquatting    giphub.com      182.92.191.220/China MX:smtp.giphub.com
Bitsquatting    gidhub.com      173.239.2.182/United States MX:mx7.gidhub.com
Bitsquatting    gi4hub.com      -
Bitsquatting    gitiub.com      -
Bitsquatting    gitjub.com      72.52.4.120/United States MX:mail.nickstel.com
Bitsquatting    gitlub.com      166.78.103.6/United States
Bitsquatting    gitxub.com      -
Bitsquatting    githtb.com      103.224.182.250/Australia MX:mail.post-host.net
Bitsquatting    githwb.com      -
Bitsquatting    githqb.com      -
Bitsquatting    githeb.com      166.78.145.36/United States
Bitsquatting    gith5b.com      -
Bitsquatting    githuc.com      -
Bitsquatting    githuf.com      -
Bitsquatting    githuj.com      108.45.93.78/United States
Bitsquatting    githur.com      104.27.140.182/United States
Homoglyph       glthub.com      202.214.8.82/Japan MX:glthub.com
Repetition      ggithub.com     199.59.243.120/United States
Repetition      giithub.com     199.59.243.120/United States
Repetition      gitthub.com     23.253.37.82/United States MX:gitthub.com
Repetition      githhub.com     72.172.89.185/United States MX:mx7.githhub.com
Repetition      githuub.com     199.59.243.120/United States
Repetition      githubb.com     199.59.243.120/United States
Transposition   igthub.com      -
Transposition   gtihub.com      199.59.243.120/United States
Transposition   gihtub.com      216.40.47.17/Canada MX:inbound.homesteadmail.com
Transposition   gituhb.com      208.73.211.178/United States
Transposition   githbu.com      -
Replacement     yithub.com      72.52.4.90/United States MX:mailgw.ns36.de
Replacement     hithub.com      72.52.4.120/United States MX:mail.nickstel.com
Replacement     bithub.com      173.230.136.135/United States MX:in1-smtp.messagingengine.com
Replacement     vithub.com      78.46.90.242/Germany MX:mail.vithub.com
Replacement     fithub.com      4.35.164.141/United States MX:alt2.aspmx.l.google.com
Replacement     tithub.com      69.172.201.208/United States
Replacement     g9thub.com      -
Replacement     gothub.com      184.168.47.225/United States MX:smtp.secureserver.net
Replacement     gkthub.com      141.8.224.183/Switzerland MX:mail.mxproc.com
Replacement     gjthub.com      72.52.4.90/United States MX:mailgw.ns36.de
Replacement     guthub.com      216.146.46.11/United States
Replacement     g8thub.com      -
Replacement     gi6hub.com      -
Replacement     giyhub.com      103.224.182.250/Australia MX:mail.post-host.net
Replacement     gighub.com      192.254.131.221/United States MX:gighub.com
Replacement     gifhub.com      185.53.177.8/Germany MX:mail.h-email.net
Replacement     girhub.com      72.172.89.185/United States MX:mx7.girhub.com
Replacement     gi5hub.com      -
Replacement     gituub.com      72.52.4.90/United States MX:mailgw.ns36.de
Replacement     gitjub.com      72.52.4.120/United States MX:mail.nickstel.com
Replacement     gitnub.com      209.20.74.249/United States
Replacement     gitbub.com      199.59.243.120/United States
Replacement     gitgub.com      -
Replacement     gityub.com      72.52.4.90/United States MX:mailgw.ns36.de
Replacement     gith8b.com      141.8.224.183/Switzerland MX:mail.mxproc.com
Replacement     githib.com      -
Replacement     githjb.com      72.52.4.120/United States MX:mail.nickstel.com
Replacement     githhb.com      72.52.4.90/United States MX:mailgw.ns36.de
Replacement     githyb.com      72.52.4.120/United States MX:mail.nickstel.com
Replacement     gith7b.com      -
Replacement     githuv.com      194.63.248.52/Norway
Replacement     githug.com      74.124.210.249/United States MX:githug.com
Replacement     githuh.com      -
Replacement     githun.com      54.72.11.253/Ireland MX:mail.h-email.net
Omission        ithub.com       -
Omission        gthub.com       208.113.199.104/United States MX:fltr-in2.mail.dreamhost.com
Omission        gihub.com       208.73.210.214/United States
Omission        gitub.com       141.8.224.239/Switzerland MX:mail.mxproc.com
Omission        githb.com       103.224.182.250/Australia MX:mail.post-host.net
Omission        githu.com       72.52.4.120/United States MX:mail.nickstel.com
Insertion       g9ithub.com     -
Insertion       gi9thub.com     -
Insertion       goithub.com     -
Insertion       giothub.com     54.72.9.51/Ireland
Insertion       gkithub.com     -
Insertion       gikthub.com     -
Insertion       gjithub.com     -
Insertion       gijthub.com     -
Insertion       guithub.com     95.211.117.206/Netherlands
Insertion       giuthub.com     95.211.117.206/Netherlands
Insertion       g8ithub.com     -
Insertion       gi8thub.com     -
Insertion       gi6thub.com     -
Insertion       git6hub.com     -
Insertion       giythub.com     -
Insertion       gityhub.com     75.119.192.209/United States MX:mx1.sub5.homie.mail.dreamhost.com
Insertion       gigthub.com     -
Insertion       gitghub.com     -
Insertion       gifthub.com     69.172.201.208/United States
Insertion       gitfhub.com     -
Insertion       girthub.com     141.8.224.169/Switzerland MX:mail.mxproc.com
Insertion       gitrhub.com     -
Insertion       gi5thub.com     -
Insertion       git5hub.com     -
Insertion       gituhub.com     95.211.117.206/Netherlands
Insertion       githuub.com     199.59.243.120/United States
Insertion       gitjhub.com     -
Insertion       githjub.com     -
Insertion       gitnhub.com     -
Insertion       githnub.com     -
Insertion       gitbhub.com     72.172.89.185/United States MX:mx7.gitbhub.com
Insertion       githbub.com     -
Insertion       gitghub.com     -
Insertion       githgub.com     -
Insertion       gityhub.com     75.119.192.209/United States MX:mx1.sub5.homie.mail.dreamhost.com
Insertion       githyub.com     -
Insertion       gith8ub.com     -
Insertion       githu8b.com     -
Insertion       githiub.com     -
Insertion       githuib.com     141.22.27.142/Germany
Insertion       githjub.com     -
Insertion       githujb.com     -
Insertion       githhub.com     72.172.89.185/United States MX:mx7.githhub.com
Insertion       githuhb.com     141.8.224.93/Switzerland MX:mail.mxproc.com
Insertion       githyub.com     -
Insertion       githuyb.com     -
Insertion       gith7ub.com     -
Insertion       githu7b.com     -
```
