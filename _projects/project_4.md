---
layout: page
title: pocdoc application
description: Eye Doctor in Pocket
img: assets/img/pocdoc.jpg
redirect:
importance: 4
category: research & development
---

PocDoc (Eye Doctor in Pocket) is an easy to use application to address the unmet need for comprehensive out-of-hospital monitoring of eye disease progression and treatment response. The application is based on a modular design that allows the common user interface (UI) to deliver different test modules. The common framework will provide the runtime for execution of the test and will be responsible for storing, reporting and analysing the test results.

A hardware setup was ideated and developed under the mentorship of <a href="https://rupeshagrawal.info/">Dr. Rupesh Agrawal</a>. The contribution included the ideation of various visual tests, to help enhance the user experience.
Initially the test is performed on a Tablet that is mounted on a tabletop stand at a fixed distance from the patient. The patient is given a gaming controller to perform the various tests using the joystick keys.
After careful consideration and as per the feedback from both the patients and medical experts, the hardware setup was designed based on the Raspberry Pi platform.   

First prototype – The patient is given a gaming controller to key in the inputs, the tablet is mounted on a table-top stand and an external light indicator system lights up green if the patient is in the test range; the external light indicator system remains red outside the range.
Second prototype – To overcome the external lighting conditions which could lead to impaired results and to maintain a fixed distance from the screen, we developed a stand-alone hardware setup to perform the tests in a dark environment. The setup is fabricated and installed with a Raspberry Pi board and display and is distance adjustable according to the need of the test. The patient looks through the pinholes and enters the response using the controller in hand.

Associated project with this competition includes the follow


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
      {% include figure.html path="assets/img/nus_intern/pocdoc_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nus_intern/pocdoc_3.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nus_intern/pocdoc_2.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Integration of PocDoc application with hardware setup.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nus_intern/megic_nus.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>
