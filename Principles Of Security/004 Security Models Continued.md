Before discussing security models further, let's recall the three elements of the CIA triad: ==Confidentiality==, ==Integrity== and ==Availability==. We've previously outlined what these elements are and their importance. However, there is a formal way of achieving this.

According to a ==security model==, any ==system== or piece of technology storing information is called an ==information== system, which is how we will reference systems and devices in this task.

<h2 style="text-align:center">Bell La Padula Model</h2>
The Bell-La Padula Model is used to achieve ==confidentiality==. This model has a few assumptions, such as an organisation's hierarchical structure it is used in, where everyone's responsibilities/roles are well-defined.

<h3 style="text-align:center">Advantages</h3>
- Policies in this model can be replicated to real-life organisations hierarchies (and vice versa)
- Simple to implement and understand, and has been proven to be successful.
<h3 style="text-align:center">Disadvantages</h3>
- Even though a user may not have access to an object, they will know about its existence -- so it's not confidential in that aspect.
- The model relies on a large amount of trust within the organisation.


![[Pasted image 20220305164810.png]]

The Bell LaPadula Model is popular within organisations such as ==governmental== and ==military==. This is because members of the organisations are presumed to have already gone through a process called ==vetting==. Vetting is a screening process where applicant's backgrounds are examined to establish the ==risk== they pose to the organisation. Therefore, applicants who are successfully vetted are assumed to be trustworthy - which is where this model fits in.

<h2 style="text-align:center">Biba Model</h2>
The Biba model is arguably the equivalent of the Bell-La Padula model but for the ==integrity== of the CIA triad.

This model applies the rule to ==objects== (data) and ==subjects== (users) that can be summarised as "==no write up==, ==no read down==". This rule means that subjects **can** create or write content to objects at or below their level but **can only** read the contents of objects above the subject's level.

![[Pasted image 20220305165809.png]]

<h3 style="text-align:center">Advantages</h3>
- This model is ==simple== to implement
- Resolves the ==limitations== of the Bell-La Padula model by addressing both ==confidentiality== and ==data integrity==.

<h3 style="text-align:center">Disadvantages</h3>
- There will be many levels of access and objects. Things can be easily overlooked when applying security controls.
- Often results in delays within a business. For example, a doctor would not be able to read the notes made by a nurse in a hospital with this model.