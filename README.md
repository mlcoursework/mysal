# MySAL
My Somewhat Awesome List


### TOC
+ [Pandas](https://github.com/mlcoursework/mysal/blob/master/README.md#pandas)
+ [JoyPlots w/ Python](https://github.com/mlcoursework/mysal/blob/master/README.md#joyplots-w-python)
+ [Networks](https://github.com/mlcoursework/mysal/blob/master/README.md#netowrks)
+ [EDA](https://github.com/mlcoursework/mysal/blob/master/README.md#eda)
+ [SQL](https://github.com/mlcoursework/mysal/blob/master/README.md#sql)
+ [Deep Learning](https://github.com/mlcoursework/mysal/blob/master/README.md#deep-learning)
+ [A/B testing](https://github.com/mlcoursework/mysal/blob/master/README.md#ab-testing)
+ [Raspberry Pi](https://github.com/mlcoursework/mysal/blob/master/README.md#raspberry-pi)
+ [Misc](https://github.com/mlcoursework/mysal/blob/master/README.md#misc)

---

#### Pandas
+ Optimizing Pandas Code for Speed and Efficiency - Sofia Heisler. [Video](https://www.youtube.com/watch?v=HN5d490_KKk), [Repo](https://github.com/sversh/pycon2017-optimizing-pandas), [Slides](https://github.com/sversh/pycon2017-optimizing-pandas/blob/master/PyCon%20presentation.pdf)


#### JoyPlots w/ Python
+ [**JoyPy** - Best one yet](https://github.com/sbebo/joypy)
+ [Another option](https://github.com/daguiam/pyjoyplot)


#### Netowrks

+ Full book for download: [_Networks, Crowds, and Markets: Reasoning About a Highly Connected World_](http://www.cs.cornell.edu/home/kleinber/networks-book/) by David Easley and Jon Kleinberg.
+ Lada Adamic - SNA course materials (Coursera). [(github repo)](https://github.com/ladamalina/coursera-sna)


#### EDA
+ [Facets: An Open Source Visualization Tool for Machine Learning Training Data (from Google)](https://research.googleblog.com/2017/07/facets-open-source-visualization-tool.html)
+ [glueviz](http://glueviz.org/)


#### SQL
+ [Thread](https://news.ycombinator.com/item?id=14300038) on hackernews with links in comments to visual/browser platforms to run SQL queries and explore data.
+ [SQL Window Functions Tutorial for Business Analysis](https://blog.statsbot.co/sql-window-functions-tutorial-b5075b87d129)
+ [Set Yourself Apart from you Peers — Learn CTE’s](https://www.essentialsql.com/introduction-common-table-expressions-ctes/)
+ [ElephantSQL - PostgreSQL hosting, including free plan for testing](https://www.elephantsql.com/)

#### Deep Learning
+ [Guide - Deep Learning With Jupyter Notebooks In The Cloud](https://www.datacamp.com/community/tutorials/deep-learning-jupyter-aws)


#### Raspberry Pi
+ Installing PhantomJS: [tutorial](https://webanalyticsfordevelopers.com/2017/03/07/automating-tests/) (search for the PhantomJS bit), and a [github repo](https://github.com/fg2it/phantomjs-on-raspberry/releases/) to look for a release (you'll have to change the link in the tutorial accordingly). [Official Download](http://phantomjs.org/download.html).
+ RPi headlesss Firefox - [link](https://stackoverflow.com/a/25726038/5056689).
+ Crontab for noobs [link](https://thepihut.com/blogs/raspberry-pi-tutorials/34930820-running-things-regularly-cron).
+ Booting Raspsberry Pi Without Monitor [link](https://www.raspberrypi.org/forums/viewtopic.php?t=144926).
+ Benchmarking performance. [link](https://www.howtoforge.com/how-to-benchmark-your-system-cpu-file-io-mysql-with-sysbench).<br>Essentially:
    > apt-get install sysbench <br>
    > sysbench --test=cpu --cpu-max-prime=20000 run
+ VNC - direct and clout connection set up - [link](https://www.raspberrypi.org/documentation/remote-access/vnc/). Download [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/) from realvnc.


#### A/B Testing
+ [Evan Miller - How Not To Run an A/B Test](https://www.evanmiller.org/how-not-to-run-an-ab-test.html)
+ [Evan Miller - Formulas for Bayesian A/B Testing](https://www.evanmiller.org/bayesian-ab-testing.html)
+ [A/B Testing Tech Note: determining sample size](https://signalvnoise.com/posts/3004-ab-testing-tech-note-determining-sample-size)
+ Read: [A Smart Bear - Easy statistics for AdWords A/B testing, and hamsters](https://blog.asmartbear.com/easy-statistics-for-adwords-ab-testing-and-hamsters.html)
+ [12 A/B Split Testing Mistakes I See Businesses Make All The Time](https://conversionxl.com/blog/12-ab-split-testing-mistakes-i-see-businesses-make-all-the-time/)


#### Misc
+ [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
+ [How to import a python file from within another python file](https://stackoverflow.com/a/20749411/5056689)
+ [Selenium with Firefox](https://raspberrypi.stackexchange.com/a/39915)
+ Edit the hosts file to effectively block time wasting websites (tried on Mac, RPi):

> `sudo nano /etc/hosts`

add new IP and domain name like so:

> `0.0.0.0      www.distracting-website.com`

save, exit.

You might need to flush the DNS cache, like so (terminal, of course):

> `dscacheutil -flushcache`

Make sure you redirect to 0.0.0.0. See [here](https://www.webnots.com/how-to-edit-hosts-file-in-mac-os-x/), for example, for more.
