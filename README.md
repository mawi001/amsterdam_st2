# StackStorm ChatOps ;-)

Basis chatops

StackStorm: Open Source IFTTT for Ops: event-driven automation, security responses, auto-remediation with workflow engine & ChatOps. StackStorm is a platform for integration and automation across services and tools. It ties together your existing infrastructure and application environment so you can more easily automate that environment -- with a particular focus on taking actions in response to events.

On the other hand, StackStorm provides the following key features:
Automations tie events to actions you’d like to take, using a rules engine and, if you want, comprehensive workflow. Automations are your operational patterns summarized as code.
StackStorm automations work either by starting with your existing scripts – just add simple meta data – or by authoring the automations within StackStorm.
Automations are the heart of StackStorm – they allow you to share operational patterns, boost productivity, and automate away the routine.
https://stackstorm.com/features/


https://keepingitclassless.net/2016/12/introduction-to-stackstorm/

One of the most important concepts in mature automation is autonomy; that is, a system that is more or less self-sufficent. Instead of relying on human beings for input, always try to provide that input with yet another automated piece of the system. There are several benefits to this approach:
Humans Make Mistakes - This is also a benefit of automation in general, but autonomy also means mistakes are lessened on the input as well as the output of an automation component.
Humans Are Slow - we have lives outside of work, and it’s important to be able to have a system that reacts quickly, instead of waiting for us to get to work. We need a system that is “programmed” by us, and is able to do work on our behalf.
Signal To Noise - Sometimes humans just don’t need to be involved. We’ve all been there - an inbox full of noisy alerts that don’t really mean much. Instead, configure specific triggers that act on your behalf when certain conditions are met
The reality is that we as operations teams are already event-driven by nature, we’re just doing it in our brains. Every operations shop works this way; there is a monitoring tool in place, and the ops folks watch for alerts and respond in some sort of planned way. This sort of event-driven activity is happening all the time without us thinking about it. As you explore the concepts below, note that the main focus here is to simply reproduce those reactions in an automated way with StackStorm.

Sensors and triggers

StackStorm was not designed to be a monitoring tool, so you’ll still want to use whatever monitoring you already have in place. Sensors can/should be used to get data out of a monitoring system and take action accordingly.


Why chatops?

https://docs.stackstorm.com/chatops/


INSTALL
https://docs.stackstorm.com/install/index.html?utm_source=ActiveCampaign&utm_medium=email&utm_content=%5BStackStorm%5D+Your+next+steps+%28quick-start+guide%29&utm_campaign=%5BStackStorm%5D+Your+next+steps+%28quick-start+guide%29


https://docs.stackstorm.com/install/docker.html



K8S

Kubernetes installation is available via Helm charts at https://docs.stackstorm.com/install/k8s_ha.html and provides High Availability deployment for both StackStorm Community and Enterprise editions.

Success Stories

https://www.bitovi.com/blog/stackstorm-solves-devops-automation-for-enterprise-client

https://medium.com/@nzlosh/automation-with-stackstorm-fighting-alert-fatigue-with-automated-remediation-d47d257f12cd
