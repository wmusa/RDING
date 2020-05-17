
Nice courses:
--------------
- http://web.stanford.edu/class/ee360/resources.html
- https://courses.engr.illinois.edu/ece498rc3/
- https://github.com/bendrucker/columbia

Nice projects:
-----------
- http://cpslab.cs.mcgill.ca/#people
- http://people.csail.mit.edu/szym/rawofdm/README.html
- http://www.ccs-labs.org/software/gr-ieee802-11/
- http://www.asp.eurasipjournals.com/content/2011/1/135
- https://sites.google.com/a/vt.edu/amp_lab/projects/active-projects
- https://www.microsoft.com/en-us/research/project/microsoft-research-software-radio-sora/

Articles:
---------
- http://www.wireshark.ch/download/Sharkfest10_A10_WLAN-802-11n-MIMO-Analysis.pdf
- http://airmagnet.flukenetworks.com/assets/whitepaper/WP-802.11nPrimer.pdf
- http://www.cs.tut.fi/kurssit/TLT-6556/Slides/2-802.11n.pdf

Wireless Comm., mobile computing, MIMO, etc
-----------
- http://web.stanford.edu/class/ee360/resources.html

CAN
----
- https://github.com/linux-can/can-utils
- https://bitbucket.org/DataspeedInc/dataspeed_can
- candump ubuntu

Python
--------------
- https://docs.python.org/3/tutorial/index.html


Goog progects
-------------
- https://www.google.com/?gws_rd=ssl#q=google+project+soli

Error correction coding
-----
- https://courses.cs.washington.edu/courses/cse466/11au/calendar/11-ErrorControlCodes-posted3.pdf

Misc
----------
- [Human rights] (http://www.human-rights-in-islam.co.uk/index.php?option=com_content&view=article&id=184:congress-secularism-and-mumbais-season-of-arson-by-ghulam-muhammed&catid=35:political)
- [Al-Isla](https://www.al-islam.org/voice-human-justice-sautul-adalatil-insaniyah-george-jordac/ruler-one-people)

- https://www.yahosein.com/vb/showthread.php?t=131456
- http://www.yahosein.com/vb/showthread.php?t=131457
- http://ar.lib.eshia.ir/

RT Linux
-----
- https://rt.wiki.kernel.org/index.php/Frequently_Asked_Questions
- https://packages.debian.org/stretch/kernel/
- http://wiki.ros.org/melodic/Installation/Debian
- https://wiki.ubuntu.com/KernelTeam/GitKernelBuild
- https://linuxmusicians.com/viewtopic.php?f=19&t=18536
- https://wiki.ubuntu.com/RealTime


Tech repor CSE
----
- http://www.cse.msu.edu/publications/tech/TR/


PHP Practice
-----
- Laravel
- https://www.youtube.com/watch?v=xevIxUQ1SH4
- https://askubuntu.com/questions/925072/unable-to-execute-the-laravel-command-laravel-new-myapp
- https://getcomposer.org/download/
- https://code.visualstudio.com/docs/?dv=linux64_deb
- https://laravel.com/docs/7.x/installation
- https://stackoverflow.com/questions/33767605/new-laravel-project-in-netbeans
- https://computingforgeeks.com/how-to-install-java-14-on-ubuntu-debian/
- https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-lemp-on-ubuntu-18-04

Software Design Pattrens
-----
- Question: Isn't MVC anti OOP?
- https://softwareengineering.stackexchange.com/questions/168316/isnt-mvc-anti-oop
- MVC works at a much higher level of abstraction than single objects, and in fact each of the three (model, view and controller) will typically consists of many objects that each have both data and behavior. That objects which encapsulate data and behavior are a good fundamental building block for programs in general doesn't mean it's the best pattern at all levels of abstraction and for all purposes.

- OOP does not restrict interactions among objects that each have their own data and their own behavior. Think of an ant and an ant colony analogy: behavior of an individual ant (run around all day, bringing food) is different from behavior of the overall colony (find the most desirable place, make more ants). The MVC pattern describes the desired social structure of an ant colony, while OOP guides the design of individual ants.

MySQL Workbench vs MariaDB
-----
- https://stackoverflow.com/questions/22616861/can-i-use-mysql-workbench-to-create-mariadb
- So my experiences are, yes you can use MySQL Workbench for MariaDB database designs.

However I needed to change the "Default Target MySQL Version" to 5.7.

This can be done by going to: Edit->Preferences in the menu. And finally to Modeling->MySQL.

Since the latest MySQL version, v8.x, the SQL statements are not compatible with MariaDB statements (like creating an index). MariabDB creating an index on a table:

INDEX `fk_rsg_sub_level_rsg_top_level1_idx` (`rgs_top_level_id` ASC)

vs

MySQL:

INDEX `fk_rsg_sub_level_rsg_top_level1_idx` (`rgs_top_level_id` ASC) VISIBLE

MariaDB can't handle this VISIBLE keyword in this example. Using an old MySQL Version, MySQL Workbench will forward engineer a compatible MariaDB SQL file.

Currently (Oct 2019) the generated SQL_MODE output is still compatible with MariaDB. Just like InnoDB, which is also preferred when using MariaDB in most cases.

Laravel
----
- What is URI?
URI stands for Uniform Resource Identifier. URI is a text which is used to identify any resource or name on Internet. URI has two specializations in the form of URL (Uniform Resource Locator) and URN (Uniform Resource Name) to identify resource and name. We mostly see examples of URL and URN in the real word. If you are working on JSP and familiar with using tag library e.g. display tag and JSTL core tag library, then you may remember the use of URI to locate binary corresponding to a tag library.

Read more: https://www.java67.com/2013/01/difference-between-url-uri-and-urn.html#ixzz6MFlF9ptZ

A URI (Uniform Resource Identifier) is a string that refers to a resource. The most common are URLs, which identify the resource by giving its location on the Web. URNs, by contrast, refer to a resource by a name, in a given namespace, such as the ISBN of a book.


- See: (https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL)
- What is URL?
URL standards for Uniform resource locator and it is a subset of URI or Uniform Resource Identifier. URL includes location as well as the protocol to retrieve the resource e.g. in http://java67.blogspot.sg/2012/09/what-is-new-in-java-7-top-5-jdk-7.html, HTTP is a protocol which can be used to retrieve resource what-is-new-in-java-7-top-5-jdk-7.html available in location http://java67.blogspot.com directory. It's not necessary that URL always include HTTP as protocol, it can use any protocol e.g. ftp://, https:// or ldap://.

The most common form of URI is the Uniform Resource Locator (URL), which is known as the web address.

Read more: https://www.java67.com/2013/01/difference-between-url-uri-and-urn.html#ixzz6MFkosq66
Read more: https://skorks.com/2010/05/what-every-developer-should-know-about-urls/
Read more: https://launchschool.com/books/http/read/what_is_a_url

- What is URN
URN stands for Uniform Resource Name. URN is also the subset of URI. One of the best examples of URN is ISBN number which is used to uniquely identify a book. URN is completely different than URL as it doesn't include any protocol.

Read more: https://www.java67.com/2013/01/difference-between-url-uri-and-urn.html#ixzz6MFlzCHDJ


- Query parameters: https://howto.caspio.com/parameters/parameters-as-query-string-values/
- HTTP Request: https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods

- HTTP
HTTP defines a set of request methods to indicate the desired action to be performed for a given resource. Although they can also be nouns, these request methods are sometimes referred to as HTTP verbs. Each of them implements a different semantic, but some common features are shared by a group of them: e.g. a request method can be safe, idempotent, or cacheable.


![Query Parameters](https://github.com/myreadings1/RDING/blob/master/img/creating_query_strings1.png)

View in Laravel
--
- Read here: https://laravel.com/docs/7.x/views
Views may also be nested within subdirectories of the resources/views directory. "Dot" notation may be used to reference nested views. For example, if your view is stored at resources/views/admin/profile.blade.php, you may reference it like so:

return view('admin.profile', $data);

Multiple role-based authentication in Laravel
----
- See (https://dev.to/kaperskyguru/multiple-role-based-authentication-in-laravel-30pc)

شعر امير المؤمنين
--
- http://www.elibrary4arab.com/viewtopic.php?f=6&t=420
- 80211 reciver based on RF funnel. reuse the same channel and save bandwidth. 
- many ideas are there about multiple receivers
- book about prob. with a better description. ;)
- Is there any system that keeps analog signal in a circuit for a while? how to benefit from this capability?
- Multi-standard receiver, like BT, Wi, Zig, GSM ... This radio is based on RF-Funn
