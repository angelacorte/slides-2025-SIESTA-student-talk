+++

title = "SIESTA 2025 - Student Talk"
description = "Angela Cortecchia - SIESTA 2025 - Student Talk"
outputs = ["Reveal"]

+++

# Towards Collective Operating Systems through Aggregate Computing
#### Student Talk @ SIESTA 2025

[Angela Cortecchia](mailto:angela.cortecchia@unibo.it) - PhD Student @ University of Bologna

<div style="text-align: center; width: 100%;">
<img src="example-background.svg" style="width: 30%" />
</div>

--- 

{{< slide background-image="./images/smartcity.webp" background-opacity="0.55">}}

{{< rectdiv >}}

# Potential Application

<div class="fragment">

In smart cities applications, e.g. _crowd management_ and _surveillance_, 
many **heterogeneous sensors** and **devices** can be employed to:
- *Detect* crowd;
- *Steer* the crowd *to prevent* hazardous situation;
- Potentially, let law enforcement *intervene*.
</div>

{{< /rectdiv >}}

--- 

{{< slide background-image="./images/wearables.jpg" background-opacity="0.55">}}

{{< rectdiv >}}
# Challenges

Common approaches usually consist of _programming each single device_.

**Non-scalable** when thousands of different devices are involved.

<div class="fragment">

- *Different* way to implement *programs on different devices*;
- Some devices do *not support all functionalities*;
- *Time expensive* to program each single device;
- Devices have a *limited vision of the system*;
- *Non-friendly programming* for the developer.
</div>

<!-- - Not all devices support the same functionalities; -->
{{< /rectdiv >}}

---

{{< slide background-image="./images/smartstation.png" background-opacity="0.55">}}

{{< rectdiv style="max-width: 90%;" >}}

# What do we need?

{{% multicol %}}

{{% col %}}

### Crowd Management scenario

<ul>
    <li class="fragment" data-fragment-index=0>Drones and sensors <em>observe and send data</em> to the system;</li>
    <li class="fragment" data-fragment-index=1>Crowd <em>steering based on data</em> evaluation;</li>
    <li class="fragment" data-fragment-index=2><em>Coordination</em> between devices;</li>
    <li class="fragment" data-fragment-index=3>Law enforcement <em>intervention</em>;</li>
</ul>
{{% /col %}}

{{% col %}}
### Effective technologies

<ul>
    <li class="fragment" data-fragment-index=0><em>Distributed</em> sensors and actuators able to <em>execute multiple programs</em>;</li>
    <li class="fragment" data-fragment-index=1>Communication between <em>different processes</em>;</li>
    <li class="fragment" data-fragment-index=2><em>Intra-process</em> communication;</li>
    <li class="fragment" data-fragment-index=3>Third-party entities able to <em>interrupt, pause, or add processes at runtime</em>.</li>
    <!-- <li>Interoperability between different devices.</li> -->
</ul>

{{% /col %}}

{{% /multicol %}}

{{< /rectdiv >}}

--- 

{{< slide background-image="./images/world.svg" background-opacity="0.55">}}

{{< rectdiv >}}

# Meet Aggregate Computing

A programming paradigm to **define the behavior of a collective of heterogeneous devices**.

Every device runs the same program and *adapts to dynamic changes in the environment*.
<img src="./images/acDevices.svg" width=70%>

<div class="fragment">

### Current limitations:

- Aggregate systems **run just one program**;
- *Can not* be modified, added, or interrupted *at runtime without affecting other devices*.

</div>

{{< /rectdiv >}}

---

{{< slide background-image="./images/collective.svg" background-opacity="0.55">}}

{{< rectdiv style="max-width: 80%;" >}}

# Idea: *Collective* Operating Systems

{{% multicol %}}

{{< col class="col-8">}}

Aim to *parallel the main functionalities of modern OSs*,
from a **collective** point of view:

<!-- Closing the gap of the current technologies: -->

- Runtime program injection;
- Users and permissions;
- Signal and interrupts;
- Multiple processes able to communicate;
- Distributed sensors and actuators;
- Intra-process communication.

{{< /col >}}

{{% col %}}

<img src="./images/devs.png" width=90%>

{{% /col %}}

{{% /multicol %}}

{{< /rectdiv >}}

--- 

{{< slide background-image="./images/crowd.png" background-opacity="0.55">}}

{{< rectdiv style="max-width: 90%;" >}}

# What I've done so far

<!-- sviluppo di Collektive, integrazione con Alchemist, primi test con android -->
<!-- ricerca: algoritmo di morfogenesi per la gestione delle risorse distribuite -->

{{% multicol %}}

{{% col %}}

Development of **Collektive**: a framework for Aggregate Computing in _Kotlin Multiplatform_;

Integration of the tool with the Alchemist Simulator;

<img src="./images/collektive-logo-white-no-background.svg" width=30%>

{{% /col %}}

{{% col %}}

Implementation of a morphogenesis algorithm with _Collektive_, for the management of distributed resources;

First testings on Android and iOS devices;

<img src="./images/oneroot.gif" width=40%>

{{% /col %}}
{{% /multicol %}}
{{< /rectdiv >}}

---

{{< slide background-image="./images/question.svg" background-opacity="0.55">}}
{{< rectdiv style="max-width: 90%;" >}}

# What's next?

{{% multicol %}}

{{% col %}}

**Short term**:
 - Implementation of self-stabilizing Gossip and Gradient algorithms, reducing communication overhead while preserving accuracy.
 - Extension of the Collective OS model with *users, permissions, signals, and inter-process communication*.
 - Validation on reference scenarios: crowd management, autonomous navigation, smart cities.

{{% /col %}}

{{% col %}}

**Long term vision**:
 - Development of a full prototype of a **Collective Operating System**, open-source and deployable on heterogeneous devices.
 - Towards resilient, adaptive collective systems with tangible impact on safety, sustainability, and coordination at scale.

<!-- working on a gossip and gradient algorithm that will reduce the communication -->
<!-- test of the architecture on real systems eg. notte dei ricercatori -->

{{% /col %}}
{{% /multicol %}}

## Also, **suggestions**?

{{< /rectdiv >}}

<!-- 
What excites you in your field
Your current research focus
What you’ve done so far
But — most importantly — what you plan to do next! 
-->
