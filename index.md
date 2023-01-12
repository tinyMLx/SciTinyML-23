---
title: false
---
<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/cover.png" alt="advertisement for the workshops" class="vid-fluid rounded center">
  </center>
</figure>

# Welcome!

>SciTinyML: Scientific Use of Machine Learning on Low-Power Devices will be run remotely in English for 2023 from April 17-21.

<div class="message">
  To view the materials and videos from past years SciTinyML workshops and TinyML4D seminars please visit the <a href="https://tinyml.seas.harvard.edu/4D/pastEvents">TinyML4D Past Events</a> page.
</div>

SciTinyML is an ICTP Virtual Meeting supported by the [TinyML4D Academic Network](https://tinymledu.org/4D/AcademicNetwork) and open to all.

**TinyML is a subfield of Machine Learning focused on developing models that can be executed on small, realtime, low-power, and low-cost embedded devices. This allows for new scientific applications to be developed at an extremely low cost and at large scale.**

The TinyML process starts with collecting data from IoT devices, then training the collected dataset to extract knowledge patterns; these patterns are then packaged into a TinyML model that considers the target microprocessor’s limited resources such as memory and processing power. The resulting model is then deployed on embedded devices where it is used to evaluate new sensor data in real-time. Typically, power requirements are in the mW range and below which enables a variety of use-cases targeting battery operated devices. TinyML represents a collaborative effort between the embedded power systems and Machine Learning communities, which traditionally have operated independently.

**Workshop Topics:**
+ ML general concepts
+ Introduction to TinyML
+ Getting started with the TinyML training kit
+ Examples of TinyML applications
+ Scientific Applications of ML
+ Recent Research and Applications in TinyML

### Schedule

<div id = "LOCAL_TIME"></div><br/>

Full Schedule Table Coming Soon!

<!-- {% include schedule_table table_data = site.data.schedule %} -->

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
We would like to thank [**ICTP**](https://www.ictp.it/), [**Harvard SEAS**](https://www.seas.harvard.edu/), [**Barnard College**](https://cs.barnard.edu/), and the [**tinyML Foundation**](https://www.tinyml.org/) for their continued leadership and support of all of our TinyML educational content!