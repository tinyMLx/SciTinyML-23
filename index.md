---
title: false
---
<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/cover.png" alt="advertisement for the workshops" class="vid-fluid rounded center">
  </center>
</figure>

# Welcome!

>SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run remotely in English for 2023 from April 17-21.<br>Register to attend for free by **Friday, April 7, 2023** on the [ICTP website](https://indico.ictp.it/event/10166)!<br><b>We are also actively soliciting submissions for short talks during our Show and Tell day! Please <a href="https://tinymledu.org/SciTinyML-23/cfp/">follow this link</a> to learn more!</b>

<!-- <br/>Submit your talk abstracts by **Friday, March 31, 2023 (23:59 AoE)** on this **[Google Form](https://docs.google.com/forms/d/e/1FAIpQLSebPUpNPnkG2dOHA1Pc6-jLr_-wM0rLVMQnwN2jfEwVXVawVQ/viewform)**. -->


<div class="message">
  To view the materials and videos from past years SciTinyML workshops and TinyML4D seminars please visit the <a href="https://tinyml.seas.harvard.edu/4D/pastEvents">TinyML4D Past Events</a> page.
</div>

This year's theme is **Applications and Advanced Topics**. We'll still begin the workshop with our usual open introduction to TinyML through Hands-on Labs on Days 1 and 2 to get everyone up to speed and then will transition toward more application focused and advanced topics (see the schedule below for more details).

SciTinyML is an ICTP Virtual Meeting supported by the [TinyML4D Academic Network](https://tinymledu.org/4D/AcademicNetwork) and open to all.

TinyML is a subfield of Machine Learning focused on developing models that can be executed on small, real-time, low-power, and low-cost embedded devices. This allows for new scientific applications to be developed at an extremely low cost and at large scale.

TinyML represents a collaborative effort between the embedded power systems and Machine Learning communities, which traditionally have operated independently. TinyML has a significant role to play in achieving the SDGs and facilitating scientific research in areas such as environmental monitoring, physics of complex systems and energy management.

The TinyML process starts with collecting data from IoT devices, then training the collected dataset to extract knowledge patterns; these patterns are then packaged into a TinyML model that considers the target microprocessor’s limited resources such as memory, processing power, and energy.

Through hands-on examples, this workshop will focus on both introductory and advanced topics in TinyML to pave the way to the development of real-world applications.

**Workshop Topics:**
+ Introduction to TinyML
+ Getting Started with the TinyML Kit
+ Examples of TinyML Applications
+ The TinyML Development Workflow
+ Scientific Applications of ML
+ Recent Research and Advanced Topics in TinyML

### Schedule

<div id = "LOCAL_TIME"></div><br/>

Full Schedule Table Coming Soon!

{% include schedule_table table_data = site.data.schedule %}

<script>
  // top time
  var start = new Date('10/18/2021 1:00:00 PM UTC');
  var end = new Date('10/18/2021 4:00:00 PM UTC');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from <b>1:00 PM to 4:00 PM GMT which is "
  var endString = " in your local timezone</b> (according to your computer system time). Times below adjusted to that time zone. Exact timing and topics subject to change."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
  
  // all times
  var timeElements = document.getElementsByClassName("GMT_TIME");
  for (var i = 0; i < timeElements.length; i++) {
    dateStr = '10/18/2021 ' + timeElements[i].innerHTML + ' UTC'
    var gmt_time = new Date(dateStr);
    timeElements[i].innerHTML = gmt_time.toLocaleTimeString([], {timeStyle: 'short'})
  }
</script>

### Questions?
Contact [edu@tinyml.org](mailto:edu@tinyml.org) with any questions regarding this workshop.

### Supporters
We would like to thank [**ICTP**](https://www.ictp.it/), [**Harvard SEAS**](https://www.seas.harvard.edu/), [**Barnard College**](https://cs.barnard.edu/), the [**Universidade Federal de Itajubá**](https://unifei.edu.br/), and the [**tinyML Foundation**](https://www.tinyml.org/) for their continued leadership and support of all of our TinyML educational content!