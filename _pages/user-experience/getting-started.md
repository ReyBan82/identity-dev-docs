---
title: User Experience
lead: >
  Create a simple and consistent experience for your Login.gov users
sidenav:
  - text: Getting started
    href: "user-experience/getting-started/"
  - text: Sign-in and sign-out buttons
    href: "user-experience/sign-in-sign-out/"
  - text: Your agency logo
    href: "user-experience/agency-logo/"
  - text: Cancel URL
    href: "user-experience/cancel-url/"
  - text: Failure to proof URL
    href: "user-experience/failure-proof/"
  - text: Knowledge articles
    href: "user-experience/knowledge-articles/"
  - text: FAQ content 
    href: "user-experience/faq-content/"

---

##  Getting started
There are several decisions during the integration process that affect how your users experience Login.gov. In this User Experience guide, we will outline what options you have available to your application, and the configurations in Login.gov [dashboard](https://dashboard.int.identitysandbox.gov/) that impact users.

{% capture button_ux %}
[Design your application's sign-in and sign-out buttons]({{site.baseurl}}/user-experience/sign-in-sign-out/). This will include a [global sign-in button]({{site.baseurl}}/user-experience/sign-in-sign-out/), and optionally, [a sign-in page]({{site.baseurl}}/user-experience/sign-in-sign-out/) before the user is directed to Login.gov.
{% endcapture %}

{% capture failure_to_proof_ux %}
All partners with identity verification will [create a Failure to Proof URL]({{site.baseurl}}/user-experience/failure-proof/) for users who cannot pass identity proofing with Login.gov. This URL is configured in the sandbox dashboard, but may require designing a new page or process on your agency's website or application.
{% endcapture %}

{% capture faq_ux %}
Optional: [Add FAQ content to inform users about Login.gov]({{site.baseurl}}/user-experience/faq-content/)
{% endcapture %}

{% capture logo_ux %}
[Add your agency logo]({{site.baseurl}}/user-experience/agency-logo/) to help users understand the partnership between Login.gov and your agency.
{% endcapture %}

{% capture cancel_url_ux %}
[Determine your application’s Cancel URL]({{site.baseurl}}/user-experience/cancel-url/)
{% endcapture %}

{% capture dashboard_failure_to_proof %}
[Identity Verification: Create a Failure to Proof URL]({{site.baseurl}}/user-experience/failure-proof/)
{% endcapture %}


### Add to your agency's application or website

<ul class="usa-icon-list padding-top-2">
  <li class="usa-icon-list__item">
    {% include green_icon.html content=button_ux %}       
  </li>
  <li class="usa-icon-list__item">
    {% include green_icon.html content=failure_to_proof_ux %}
  </li>
  <li class="usa-icon-list__item">
    {% include green_icon.html content=faq_ux %}
  </li>
</ul>

### Configure in the [dashboard](https://dashboard.int.identitysandbox.gov/)

<ul class="usa-icon-list padding-bottom-4 padding-top-2">
 <li class="usa-icon-list__item">
    {% include green_icon.html content=logo_ux %}
 </li>
 <li class="usa-icon-list__item">
    {% include green_icon.html content=cancel_url_ux %}
 </li>
 <li class="usa-icon-list__item">
    {% include green_icon.html content=dashboard_failure_to_proof %}
 </li>
</ul>

[Next step: Design your application's sign-in and sign-out buttons]({{site.baseurl}}/user-experience/sign-in-sign-out/)

