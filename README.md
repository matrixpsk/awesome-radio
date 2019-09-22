# Awesome Radio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome radio resources. Inspired by awesome-*.

This project is aimed at hackers who enjoy all aspects of radio communication.
While a lot of this technology isn't usable by citizens and is heavily regulated
by the FCC, just knowing anything about it is special. I've been interested in
learning the ins and outs of radio, as well as hearing stories, new and old.

## SDR (Software Defined Radio)

Software Defined Radio is a way to define components that are typically
hardware, such as filters and amplifiers, as software. It has been around for a
while, but with the cost of digital electronics needed to run SDR becoming
increasingly cheaper, we are seeing a rise in hacker folk playing and building
with SDR.

I would like contributors for this section.

### Links

* [Gqrx](http://gqrx.dk/)
* [sdrsharp on .NET](http://sdrsharp.com)

### Hardware
* __Recommended starter hardware__ On the low end,
  [RTL-SDR](http://sdr.osmocom.org/trac/wiki/rtl-sdr) is a super-cheap usb
  dongle, around which a thriving community has been founded.
* On the other side of the cost spectrum, [pervices](http://www.pervices.com/)
  makes some really high-throughput, PCIe devices for when you need to log all
  the traffic ever. The software and community support for this is less good,
  though (for which you can blame @outofculture).
* You can also browse through the [big
  list](https://gnuradio.org/redmine/projects/gnuradio/wiki/Hardware) of all
  compatible hardware.
* Antennas are their own body of options and tradeoffs, about which I know
  nothing.

### Software
Depending on the hardware you're using, it may ship with some demo software to
play around with. This is great for just getting a chance to see some waves and
start to get an idea of what's possible. Otherwise, [GNU
Radio](https://gnuradio.org/redmine/) is going to where you'll spend your time.
It's mainly just a library, but it also has a supporting gui for combining
processing blocks that then outputs python. Once you're more comfortable, you
can also just use GNURadio to do any device tuning, setup and i/o, and then use
numpy for the signal manipulation math.

Just visualizing and manually inspecting a signal is a valuable part of learning
how to work with them. [Baudline](http://www.baudline.com/) is a janky old
thing, but it's the best there is. Be forewarned that learning the UI won't come
easily to anyone.

## Amateur Radio (a.k.a Ham Radio)

The hobby of Amateur Radio has a long and proud tradition. The very first radio
amateurs were true pioneers of radio technology. Amateurs 'invented' and refined
much of the early radio technology and were the first to transmit music, radio
plays, and information to the handful of people who had the new fangled radio
receivers.

After World War II the hobby of amateur radio flourished. Radio clubs sprang up
in schools all over the world and kids went home each night to build some new
contraption, or have a chat with someone over the wireless. These young people
became the mainstay of the technical professions and developed much of the
modern technology we use today.
([WIA](http://www.wia.org.au/licenses/foundation/about/))

[What is Ham Radio?](http://www.arrl.org/what-is-ham-radio)

### Links

* American Radio Relay League - [ARRL](http://www.arrl.org/)
* The Wireless Institute of Australia [WIA](http://www.wia.org.au/)
* Radio Society of Great Britain - [RSGB](http://rsgb.org/)
* Pakistan Amateur Radio Society - [PARS](http://www.pakhams.com/)
* [The International Amateur Radio Union](http://www.iaru.org/)
* [Japanese asteroid mission](http://www.arrl.org/news/amateur-radio-transponder-will-accompany-japanese-asteroid-mission-into-deep-space)
* [Slow-scan Television](https://en.wikipedia.org/wiki/Slow-scan_television)
* [Portable SDR](http://hackaday.io/project/1538-PortableSDR)

I would like contributors for this section.

### Amateur Radio License

* In the [US](http://www.arrl.org/getting-licensed) there are three license
  classes—Technician, General and Extra.
* [The Foundation Licence](http://www.wia.org.au/licenses/foundation/about/) in
  Australia.
* [Foundation Licence]
  (http://rsgb.org/main/clubs-training/for-students/foundation/) in the UK.
* In
  [Pakistan](http://www.pakhams.com/index.php?option=com_content&view=article&id=75&Itemid=92)
  first you apply for SWL (Short Wave Listener) membership and then you are
  eligible to [apply for the HAM
  License](http://www.pta.gov.pk/index.php?option=com_content&view=article&id=466%3Aamateur-wireless-license&catid=138%3Aguidelines&Itemid=349).

## Public Health and Safety

Police and fire in the United States typically communicate over trunked radio.
This makes it hard to scan using normal reciever without trunk tracking
abilities. See more in the [trunking](#trunking) section.

### Trunking

While not strictly specific to public health and safety, it is usually the first
thing that comes to mind when talking about trunked radio.

Trunked radio is a form of digital-two-way communication where multiple
organizations can share a small spectrum of real frequencies without hearing
another organizations conversations. A user can choose a logical channel or
group and the base station will find an empty frequency to transmit on.

### Links

* [Project 25](http://www.project25.org/)
* [Project 25 wikipedia](http://en.wikipedia.org/wiki/Project_25)
* [Trunked Radio wikipedia](http://en.wikipedia.org/wiki/Trunked_radio_system)
