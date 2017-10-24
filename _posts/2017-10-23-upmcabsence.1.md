---
featured: false
layout: post
title: UPMC Absence Management
subtitle: Improving the process for requesting a leave of absence
details: A user-friendly solution for requesting a leave of absence.
color: "#00BCD4"
brief: Increase the number of people who choose to file a leave request online and decrease call volume by redesigning the leave intake process. In addition, create a system for designing assessments that can be reused for various use cases. 
time: 12 months
contributions: [information design & user flow, requirements gathering, wireframing & prototyping, copy editing, visual design, user testing]
---
## The Opportunity
Filing a leave of absence from work to care for yourself or a family member is a right provided by the Family and Medical Leave Act of 1993. UPMC WorkPartners administrates absence management for clients, but their current online process was so difficult to understand that very few people chose to use it. They enlisted the help of Consumer Innovation to redesign their current intake process. In addition, they wanted to explore ways to better integrate and cross-promote their other service offerings, such as their Employee Assistance Program and Short Term Disability benefits.
<div markdown="block" class="break-out"> 

![hp-home]({{ "img/absence/current-home.png" | relative_url }}){:class="side-by"}
![hp-why]({{ "img/absence/current-why.png" | relative_url }}){:class="side-by"}

</div>

<div markdown="block" class="break-out"> 

![hp-type]({{ "img/absence/current-type.png" | relative_url }}){:class="side-by"}
![hp-calendar]({{ "img/absence/current-calendar.png" | relative_url }}){:class="side-by"}

</div>

## Early Validation
We began by looking at the current state of the intake process and consulted with subject matter experts to understand which questions were required by law, which questions were helpful for a leave specialist handling the request, and which questions were confusing or could be safely omitted. 

In addition to a dated design, and inconsistent UI controls, the assessment assumed a high level of subject matter expertise. For example, users generally do not have enough familiarity with the leave process to determine whether their leave request should be continuous or intermittent. 

We mapped out the flow and iterated until we felt we had a sequence of questions that both made sense to a user and allowed our business stakeholders to obtain necessary information to process the request. 
<div markdown="block" class="break-out"> 

![hp-flow]({{ "img/absence/UserFlow.png" | relative_url }}){:class="full-width"}

</div>

I also scheduled time to sit down with a leave specialist and observe as she answered intake calls. This helped me to get a better sense of how a request is handled and what questions were necessary to ask.

Although it was useful to have the assessment mapped out in a flow diagram, we soon found that stakeholders had trouble translating the flow into an actual experience. To help with that, we created a [lo-fi prototype in Axure]({{ "http://2b7an2.axshare.com/#g=1&p=0__about"| absolute_url }}){:target="_blank"}, to demonstrate the flow and wording of questions.

![hp-lofi]({{ "img/absence/lofi.png" | relative_url }}){:class="full-width"}

## Refinement and Testing
This proved to be a useful way of soliciting feedback, so we continued increasing the fidelity of the [Axure prototype]({{"http://k2vk6v.axshare.com/#g=1&p=i__who_needs_the_leave__you_employee_" | absolute_url }}){:target="_blank"} as the process continued. This ended up being our source of truth for the questionnaire flow, interactions, and branching logic; the developers worked directly from this prototype to understand the requirements (with visual specs provided through Sketch and Zeplin). Throughout the process, we shared this prototype with leave specialists and subject matter experts to ensure we were conforming to WorkPartners process capabilities and federal regulations around FMLA.
![hp-hifi]({{ "img/absence/hifi.png" | relative_url }}){:class="full-width"}

Near the end of the process, we had a chance to test our prototype with five users. During these moderated, in-person usability tests, we had users step through several scenarios, such as submitting a leave request as a result of their family member’s illness, or acting as a manager submitting a request on behalf of their employee. 

One requirement of this project was to switch from a fixed-width design to a responsive, mobile-friendly design. We were able to ensure that a user could complete all steps of the process on any screen size.
![hp-tablet]({{ "img/absence/tablet.png" | relative_url }}){:class="side-by"}
![hp-mobile]({{ "img/absence/mobile.png" | relative_url }}){:class="side-by"}

## Creating a System
As part of this project, we created a reusable system for designing assessments. The goal was to be able to expand the interaction patterns and code to other lines of business that contain similar intake assessments. This allowed several other assessment experiences to be updated and improved at low cost to WorkParnters, but with significant impact for their users. Additionally, we wanted to better guide people through the process by linking together relevant assessments and providing recommendations for resources and support that WorkPartners can provide, such as financial counseling or help finding childcare. 

The resuable modules created as part of this project have allowed our business stakeholders to easily create new assessments for other lines of business, and ensure they are usable and well-designed, without the need for our group to be involved at every step of the process. The system has been used in at least five assessments, and opportunities continue to present themselves across UPMC. This also laid the groundwork for our nascent design system which is currently in active development.

![hp-workerscomp]({{ "img/absence/workerscomp.png" | relative_url }}){:class="full-width"}
![hp-employeehealth]({{ "img/absence/employeehealth.png" | relative_url }}){:class="full-width"}



