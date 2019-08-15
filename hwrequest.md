---
layout: single
header:
  image: /assets/images/ESA_LimeSDR_Mini_2.jpg
---

# Developer Kit

The SDR Satcom Developer Kit is comprised of:

* ESA [LimeSDR Mini][1] in Aluminium Enclosure
* 2x SMA antennas

# Criteria

Hardware is being made available in support of open source development and it is
expected that applications will be published under a licence which meets the
[Open Source Definition][2]. While not mandatory, it is hoped that the project
or maintainer will also distribute these via the [SDR Satcom app store][3].

Inviduals, open source projects and organisations may qualify to receive free
developer hardware as part of the European Space Agency sponsored SDR Satcom
initiative. Projects which have previously received support are also invited to
apply, where this will enable new contributors and further development.

Please note that where applicants are not formally associated with a relevant
project or organisation, some evidence of experience developing software
defined radio applications will be required. In such cases please include a link
to a GitHub/GitLab or similar profile/repository which will provide this, along
with a suitably detailed description of the proposed project.

Finally, if you have no relevant prior experience, but are keen to contribute,
we recommend that you contact an existing project and have them make an
application on your behalf. 

# Process

Requests will be reviewed every two weeks and hardware provided on a
first-come-first-served basis. There are presently no plans to make further
hardware available once this allocation is exhausted.

# Support

General support etc. questions should be directed to the [MyriadRF forum][4].

# Request Form

<form name="hwrequest" method="POST" netlify-honeypot="pretend"
data-netlify-recaptcha="true" data-netlify="true">
  <p class="hidden">
    <label>This is only for pretend beings: <input name="pretend" /></label>
  </p>
  <p>
    <label>Name: <input type="text" name="name" required /></label>   
  </p>
  <p>
    <label>Email: <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Organisation: <input type="text" name="organisation" /></label>
  </p>
  <p>
    <label>URL (org/project/GitHub): <input type="url" name="url" required /></label>
  </p>
  <p>
    <label>Description: <textarea name="description" required></textarea></label>
  </p>
  <p>
    <label>I consent to my data being stored <input type="checkbox" name="consent"
required /></label>
  </p>
  <div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

# Terms and Conditions 

The [MyriadRF Competions Terms & Conditions][4] apply.

[1]:https://myriadrf.org/projects/component/limesdr-mini/
[2]:https://opensource.org/osd
[3]:/#app-store
[4]:https://discourse.myriadrf.org/c/projects/sdr-satcom
[5]:https://myriadrf.org/terms-conditions/competitions/
