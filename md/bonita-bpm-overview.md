# Bonita BPM overview

Bonita BPM 7 is a powerful BPM-based application platform for building highly engaging, personalized, process-based business applications that adapt to your business changes in real time. 

Bonita BPM has two parts: the development environment, Bonita BPM Studio, and the runtime environment, Bonita BPM Platform.

## Bonita BPM Studio

Bonita BPM Studio is a graphical environment for creating processes and application pages. It contains two major design tools: 

* the whiteboard, for drawing a process flow diagram and defining the detail of steps, transitions, decision points and other process elements
* the UI designer, which is used to create application pages and process forms

Bonita BPM Studio is the development tool for the Business Analyst and Application Developer.

You can [install Bonita BPM Studio](bonita-bpm-installation-overview.md) on your computer, then create and test processes. Bonita BPM Studio contains a **Bonita BPM Platform** (Tomcat, Bonita BPM Portal, Bonita BPM Engine, and an h2 database), suitable for testing a process that is in development.

In Bonita BPM Studio, once the process is ready, you can then [build](build-a-process-for-deployment.md) it and deploy it on your Bonita BPM production platform.

To build your completed process into a process-based application, you use the UI designer to create the application pages, then use the Bonita BPM Portal application builder to construct the application.

## Bonita BPM Platform

Bonita BPM Engine is the execution engine of Bonita BPM.

[Bonita BPM Portal](bonita-bpm-portal-interface-overview.md) is the part of Bonita BPM that is visible to process users, who use it to view tasks and take actions. Bonita BPM Portal is also the tool used by the process administrator to [install, deploy and manage processes](processes.md) and to [build applications](applications.md).

To install Bonita BPM Engine and Bonita BPM Portal, [install Bonita BPM Platform](bonita-bpm-installation-overview.md).

## Editions

Bonita BPM is provided in four different editions: Community, Teamwork, Efficiency, Performance.

## Getting started

**I'm currently using Bonita BPM 6.x. Will 7.x be a big change?**

Bonita BPM 7.x provides [new and improved features](new-features.md), including the UI designer for creating application pages and forms. 
You will also find lots of familiar features, which continue to work as they did in 6.x.

**Tell me about the documentation.**

We're continually updating the documentation. 
There are four main information categories: Application and process design, Installation, Administration, and Development. 

**Tell me about using Bonita BPM.** 

See [Lifecycle and profiles](lifecycle-and-profiles.md).

**Can I migrate an existing process into Bonita BPM 7.x?**

You can [import a process](import-and-export-a-process.md) from any earlier Bonita BPM release. You can also [migrate a process from Bonita Open Solution 5.9 or 5.10](migrate-a-process-from-bonita-open-solution-5-x.md) to this release. A 6.x process will continue to run unchanged in 7.x, but to take advantage of the new features, you will need to update the process and [migrate the forms](migrate-a-form-from-6-x.md).

**Tell me about creating an application.** 

An application is a collection of related processes, user interfaces, and shared data. See [design methodology](design-methodology.md).

**Tell me about creating a process.** 

A process can be included in an application or can be accessed through Bonita BPM Portal. See [design methodology](design-methodology.md).

**Tell me about creating a diagram.**

See [diagrams](diagram-overview.md).

**How can I get started?** 

Download and install Bonita BPM 7.x: see the [installation instructions](bonita-bpm-installation-overview.md).