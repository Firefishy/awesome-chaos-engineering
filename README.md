# Awesome Chaos Engineering

Testing in production (TiP) is gaining steam as an accepted practice in DevOps and testing communities, but no amount of preproduction QA testing can foresee all the possible scenarios in your real production deployment.

The prevailing wisdom is that you will see failures in production; the only question is whether you'll be surprised by them or inflict them intentionally to test system resilience and learn from the experience.

The latter approach is chaos engineering.

> To understand all this knowledge is very important have a good background in Chaos Engineering, containers, fault injection, monitoring and observability.

## Principles of chaos engineering

A chaos experiment is defined as the following five points by the Principles of chaos engineering

 * Build a Hypothesis around Steady State Behavior
 * Vary Real-world Events
 * Run Experiments in Production
 * Automate Experiments to Run Continuously
 * Minimize Blast Radius

More details in the following link ;-)

 * [PRINCIPLES OF CHAOS ENGINEERING](https://principlesofchaos.org/?lang=ENcontent)

## Tools & Frameworks

 * [The Simian Army](https://github.com/Netflix/SimianArmy) - A suite of tools for keeping your cloud operating in top form.
 * [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - A resiliency tool that helps applications tolerate random instance failures.
 * [Chaos Monkey for Spring Boot](https://codecentric.github.io/chaos-monkey-spring-boot/) - Injects latencies, exceptions, and terminations into Spring Boot applications
 * [Chaos Toolkit](https://github.com/chaostoolkit/chaostoolkit) - A chaos engineering toolkit to help you build confidence in your software system.
 * [Chaos Toolkit Turbulence](https://github.com/tmobile/chaostoolkit-turbulence) - This is an extension for Chaos Toolkit which adds support for Turbulence attacks.
 * [Monarch](https://github.com/tmobile/monarch) - This is a series of tools for Chaos Toolkit
 * [Chaos Hub](https://github.com/chaostoolkit/chaoshub-archive) - Chaos Hub stands on the shoulders of the Chaos Toolkit to provide a complete, user-friendly, platform to automate and collaborate on your Chaos Engineering and Resiliency efforts.
 * [Muxy](https://github.com/mefellows/muxy/) - A chaos testing tool for simulating a real-world distributed system failures.
 * [ChaosBlade](https://github.com/chaosblade-io/chaosblade) - Chaosblade is an experimental tool that follows the principles of Chaos Engineering and is used to simulate common fault scenarios, helping to improve the recoverability of faulty systems and the fault tolerance of faults.
 * [Cthulhu](https://github.com/xmatters/cthulhu-chaos-testing) - Chaos Engineering tool that helps evaluating the resiliency of microservice systems simulating various disaster scenarios against a target infrastructure in a data-driven manner.
 * [Orchestrator](https://github.com/github/orchestrator) - MySQL replication topology management and HA.
 * [Namazu](https://github.com/osrg/namazu) - Programmable fuzzy scheduler for testing distributed systems.
 * [Toxiproxy](https://github.com/Shopify/toxiproxy) - A TCP proxy to simulate network and system conditions for chaos and resiliency testing.
 * [React Chaos](https://github.com/jchiatt/react-chaos) - Chaos Engineering for your React apps.
 * [Chaos QoaLa](https://github.com/oslabs-beta/ChaosQoaLa) - ChaosQoaLa is a chaos engineering tool for injecting failure into JavaScript backed GraphQL end points.
 * [Royal Chaos](https://github.com/KTH/royal-chaos) - This repository contains the chaos engineering systems invented at KTH Royal Institute of Technology.
 * [Chaos Platform](https://github.com/chaostoolkit/chaosplatform) - Chaos Engineering Platform for Everyone
 * [CHAOS GOPHER](https://github.com/chaostesting/chaosgopher) - A collection of unix style tools in GO to do chaos engineering or testing.
 * [Chaos Reverse-engineering](https://github.com/pcoppens/chaos-re) - Chaos engineering approach by Reverse-engineering.
 * [Chaos Scimmia](https://github.com/joshuamckenty/chaos-scimmia) - Chaos Engineering for Redis
 * [ChaosCat](https://github.com/Torvaney/chaoscat) - Chaos engineering for Pull Requests - Taking a not-even-good joke a bit too far
 * [Controlled Chaos](https://github.com/DylanCauwels/ControlledChaos) - An all-in-one application that allows teams to create, execute, and analyze chaos engineering experiments with no previous DevOps experience or additional infrastructure setup.
 * [HavocLeopard](https://github.com/jonfast565/HavocLeopard) - A set of simple chaos engineering apps that can be used to royally screw up your on-prem servers
 * [Banjaxed](https://github.com/intercom-archive/banjaxed) - Open source incident management tool
 * [Cyphon](https://github.com/dunbarcyber/cyphon) - Open source incident management and response platform
 * [Arcdata](https://github.com/redcross/arcdata) - Open source incident management and volunteer scheduling application for Red Cross Disaster Services

### Chaos in the JVM

 * [Byteman](https://byteman.jboss.org/) - A Swiss Army Knife for Byte Code Manipulation.
 * [Byte-Monkey](https://github.com/mrwilson/byte-monkey) - Bytecode-level fault injection for the JVM. It works by instrumenting application code on the fly to deliberately introduce faults like exceptions and latency.
 * [Perses](https://github.com/nicolasmanic/perses) - A project to cause (controlled) destruction to a JVM application.
 * [Chaos Engineeing Demo](https://github.com/fazdevils/chaos-engineeing-demo) - Simple project demonstrating chaos engineering with Chaos Monkey and Resiliance4J

## API Chaos

 * [Wiremock](http://wiremock.org/) - API mocking (Service Virtualization) which enables modeling real world faults and delays
 * [MockLab](http://get.mocklab.io/) - API mocking (Service Virtualization) as a service which enables modeling real world faults and delays.
 * [Flaw](https://github.com/GaruGaru/flaw) - Inject failures on api calls for local chaos engineering

## Chaos for Docker

 * [Pumba](https://github.com/gaia-adm/pumba) - Chaos testing and network emulation for Docker containers (and clusters).
 * [Blockade](https://github.com/worstcase/blockade) - Docker-based utility for testing network failures and partitions in distributed applications.
 * [Chaos Engineering for docker](https://github.com/cloudchaos/docker) - Chaos Engineering for docker
 * [Chaos Engineering with Docker EE](https://github.com/sameerkasi200x/docker-chaos-engineering) - Chaos Engineering with Docker EE
 * [Chaos Util](https://github.com/abnamrocoesd/chaos-util) - Docker image with utilities for Chaos Engineering

## Security Chaos

 * [ChaoSlingr](https://github.com/Optum/ChaoSlingr) - Introducing Security Chaos Engineering. ChaoSlingr focuses primarily on the experimentation on AWS Infrastructure to proactively instrument system security failure through experimentation.
 * [What is security chaos engineering and why is it important?](https://hub.packtpub.com/what-is-security-chaos-engineering-and-why-is-it-important/)
 * [Security Chaos Engineering: A new paradigm for cybersecurity](https://opensource.com/article/18/1/new-paradigm-cybersecurity)
 * [Injecting chaos experiments into security log pipelines](https://opensource.com/article/18/9/injecting-chaos-experiments-security-log-pipelines)
 * [Purple testing and chaos engineering in securityexperimentation](https://opensource.com/article/18/6/security-experimentation)
 * [A new approach to security instrumentation](https://opensource.com/article/18/4/new-approach-security-instrumentation)

## Failure as a Service

 * [Gremlin Inc.](https://www.gremlin.com/) - Failure as a Service.
 * [Chaos Engineering Experiment Automation](https://chaostoolkit.org/) - Chaos Engineering Experiment Automation
 * [Pystol.org](https://www.pystol.org/) - THE CLOUD CHAOS ENGINEERING TOOLBOX

## Public, Private and Hybrid Cloud Services

 * [VMware Mangle](https://vmware.github.io/mangle/) - Orchestrating Chaos Engineering.
 * [Glooshot](https://github.com/solo-io/glooshot) - Chaos engineering framework to help you Immunize your service mesh
 * [Turbulence](https://github.com/cppforlife/turbulence-release) - Tool focused on BOSH environments capable of stressing VMs, manipulating network traffic, and more. It is very simmilar to Gremlin.
 * [Drax](https://github.com/dcos-labs/drax) -  DC/OS Resilience Automated Xenodiagnosis tool. It helps to test DC/OS deployments by applying a Chaos Monkey-inspired, proactive and invasive testing approach.
 * [Pod-Reaper](https://github.com/target/pod-reaper) - A rules based pod killing container. Pod-Reaper was designed to kill pods that meet specific conditions that can be used for Chaos testing in Kubernetes.
 * [kube-monkey](https://github.com/asobti/kube-monkey) - An implementation of Netflix's Chaos Monkey for Kubernetes clusters.
 * [ChaosKube](https://github.com/linki/chaoskube) - chaoskube periodically kills random pods in your Kubernetes cluster.
 * [Powerful Seal](https://github.com/bloomberg/powerfulseal) - PowerfulSeal adds chaos to your Kubernetes clusters, so that you can detect problems in your systems as early as possible. It kills targeted pods and takes VMs up and down.
 * [Litmus](https://github.com/litmuschaos/litmus) - Framework for Kubernetes environments that enables users to run test suites, capture logs, generate reports and perform chaos tests.
 * [KubeInvaders](https://github.com/lucky-sideburn/KubeInvaders) - Gamfied Chaos engineering tool for Kubernetes Clusters
 * [Testing Amazon Aurora Using Fault Injection Queries](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/AuroraMySQL.Managing.html#AuroraMySQL.Managing.FaultInjectionQueries)
 * [Azure Fault Analysis Service](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-testability-overview), see also [Include controlled Chaos in Service Fabric clusters](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-controlled-chaos)
 * [Chaos Lambda](https://github.com/bbc/chaos-lambda) - Randomly terminate ASG instances during business hours.
 * [GomJabbar](https://github.com/outbrain/GomJabbar) - ChaosMonkey for your private cloud
 * [Chaos Operator](https://github.com/litmuschaos/chaos-operator) - Chaos engineering via kubernetes operator
 * [Kube Entropy](https://github.com/alexlokshin/kube-entropy) - A little chaos engineering application for kubernetes resilience testing.
 * [Chaos Coordinator](https://github.com/UtheMan/chaoscoordinator) - Chaos Coordinator is a set of tools that allow for chaos testing of the infrastructure used by Kubernetes clusters on Azure.
 * [Havoc](https://github.com/bchavez/Havoc) - Havoc is a collection of dangerous code that wreck havoc in .NET applications and the operating system for chaos-engineering.
 * [Chaos Engineering Demo](https://github.com/ericwyles/chaos-engineering-demo) - resilience4j + chaos toolkit + wiremock + chaos monkey for spring boot sample application
 * [Utilities for frontend chaos engineering](https://github.com/jchiatt/chaos) - Utilities for frontend chaos engineering.
 * [Chaos Engineering on Google Cloud Platform](https://github.com/cloudchaos/google-cloud-platform) - Chaos Engineering on Google Cloud Platform
 * [Chaos SSM Documents](https://github.com/adhorn/chaos-ssm-documents) - Collection of AWS SSM Documents to perform Chaos Engineering experiments
 * [kubernetes-chaos-lab](https://github.com/matthewbrahms/kubernetes-chaos-lab) - A brief guide to setting up your first chaos engineering lab on Kubernetes!
 * [How to Create a Kubernetes Cluster on Ubuntu 16.04 with kudeadm and Weave Net](https://www.gremlin.com/community/tutorials/how-to-create-a-kubernetes-cluster-on-ubuntu-16-04-with-kudeadm-and-weave-net/)

## Examples

 * [A Chaos Engineering Bootcamp](https://github.com/tammybutow/chaosengineeringbootcamp) - A Chaos Engineering Bootcamp
 * [HW4](https://github.com/kbalakr/Chaos-Engineering---DevOps-Demo) - Express servers were used to implement service topologies
 * [Serverless Chaos Engineering Demo](https://github.com/gunnargrosch/serverless-chaos-demo) - This example demonstrates how to use Adrian Hornsby's Failure Injection Layer (https://github.com/adhorn/FailureInjectionLayer) to perform chaos engineering experiments on a serverless environment.

## Cost of SEVs

 * [Availability Calculator](https://github.com/dastergon/availability-calculator) - Calculate how much downtime should be permitted in your SLA

## References

 * https://techbeacon.com/app-dev-testing/chaos-engineering-testing-34-tools-tutorials
 * https://raw.githubusercontent.com/dastergon/awesome-chaos-engineering/master/README.md
 * https://www.techrepublic.com/article/chaos-engineering-a-cheat-sheet/
 * https://thenewstack.io/gremlins-tammy-butow-on-the-business-side-of-chaos-engineering/
 * https://learnk8s.io/blog/kubernetes-chaos-engineering-lessons-learned
 * https://gocardless.com/blog/game-days-at-gc/
 * https://engineering.grab.com/chaos-engineering
 * https://blog.newrelic.com/engineering/chaos-engineering-explained/
 * https://slack.engineering/disasterpiece-theater-slacks-process-for-approachable-chaos-engineering-3434422afb54
 * https://www.usenix.org/system/files/osdi18-veeraraghavan.pdf
 * https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-yuan.pdf
 * https://people.ucsc.edu/~palvaro/fit-ldfi.pdf
 * https://landing.google.com/sre/book.html
 * http://the-cloud-book.com/
 * https://www.infoq.com/minibooks/emag-chaos-engineering
 * https://www.pagerduty.com/blog/failure-fridays-four-years/
 * https://www.slideshare.net/zgrinch/monkeys-lemurs-and-locusts-oh-my
 * https://www.cloudreach.com/fr/blog/training-cloud-operations-teams-met-office/
 * https://softwareengineeringdaily.com/2018/02/02/chaos-engineering-with-kolton-andrus/
 * https://blog.codeship.com/embracing-the-chaos-of-chaos-engineering/
 * https://sharpend.io/chaos-monkey-for-fun-and-profit/
 * https://queue.acm.org/detail.cfm?id=2353017
 * https://dl.acm.org/citation.cfm?id=3177123.3158134
 * https://dl.acm.org/citation.cfm?id=2723711
 * https://azure.microsoft.com/en-us/blog/inside-azure-search-chaos-engineering/
 * https://devops.com/netflix-the-simian-army-and-the-culture-of-freedom-and-responsibility/
 * http://www.oreilly.com/webops-perf/free/chaos-engineering.csp
 * http://www.oreilly.com/webops-perf/free/antifragile-systems-and-teams.csp
 * http://shop.oreilly.com/product/0636920251897.do
 * https://www.gremlin.com/community/tutorials/chaos-engineering-the-history-principles-and-practice/
 * https://www.gremlin.com/blog/the-discipline-of-chaos-engineering/
 * https://arxiv.org/abs/1404.3056
 * https://arxiv.org/abs/1702.05843
 * https://arxiv.org/abs/1702.05849
 * https://arxiv.org/abs/1805.05246
 * https://arxiv.org/abs/1812.10706
 * https://medium.com/@bbideep/why-should-chaos-be-part-of-your-distributed-systems-engineering-5bcb21497660
 * https://medium.com/@njones_18523/chaos-engineering-traps-e3486c526059
 * https://medium.com/@adhorn/chaos-engineering-ab0cc9fbd12a
 * https://medium.com/netflix-techblog/fit-failure-injection-testing-35d8e2a9bb2
 * https://medium.com/netflix-techblog/the-netflix-simian-army-16e57fbab116
 * https://medium.com/netflix-techblog/automated-failure-testing-86c1b8bc841f
 * https://medium.com/netflix-techblog/chaos-engineering-upgraded-878d341f15fa
 * https://medium.com/netflix-techblog/chap-chaos-automation-platform-53e6d528371f
 * https://medium.com/@crochefolle/how-to-convince-your-boss-to-make-them-say-yes-to-chaos-engineering-796ba119bd7
 * https://medium.com/chaosiq/cloud-native-and-chaos-engineering-20842ee2fa8a
 * https://www.wired.com/story/netflix-ddos-attack/
 * https://github.com/gremlin/chaos-engineering-tools
 * https://github.com/greenlearner01/Chaos-Engineering/blob/master/Chaos-Engineering.md

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

## Contributing

 Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

 Feel free to [open an issue](https://github.com/adriannovegil/awesome-observability/issues) or [create a pull request](https://github.com/adriannovegil/awesome-observability/pulls) with your additions.

 Thank you!
