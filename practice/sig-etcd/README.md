<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# etcd Special Interest Group

etcd is a production-ready store for building cloud-native distributed systems and managing cloud-native infrastructure via orchestrators like Kubernetes.
Etcd should provide distributed system primitives** (such as distributed locking and leader election) that allow users to **create scalable, highly available and fault-tolerant systems.
Etcd is the place to store the infrastructure configuration, not only as part of Kubernetes, but also as a standalone solution.

The [charter](charter.md) defines the scope and governance of the etcd Special Interest Group.

## Meetings
*Joining the [mailing list](https://groups.google.com/g/etcd-dev) for the group will typically add invites for the following meetings to your calendar.*
* Regular SIG Meeting: [Thursdays at 11:00 PT (Pacific Time)](https://zoom.us/my/cncfetcdproject) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=11%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/16XEGyPBisZvmmoIHSZzv__LoyOeluC5a4x353CX0SIM/edit?usp=sharing).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PLRGL688DpO9rtufHbiunuCHddYY6MGkwW).
* Robustness Tests Meeting: [Wednesdays at 08:00 PT (Pacific Time)](https://zoom.us/my/cncfetcdproject) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=08%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1idZ_7tV6F18v223LyQ0WVUn9gXLSKyeLwYTdAgbjxpw/edit?usp=sharing).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PLRGL688DpO9oF-YEEfVXMzaOUzFYK74-I).
* Triage Meeting: [Thursdays at 11:00 PT (Pacific Time)](https://zoom.us/my/cncfetcdproject) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=11%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/16XEGyPBisZvmmoIHSZzv__LoyOeluC5a4x353CX0SIM/edit).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PLRGL688DpO9oz7rXy7ZwRS1hvgfEc7qOr).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* James Blair (**[@jmhbnz](https://github.com/jmhbnz)**), Red Hat
* Wenjia Zhang (**[@wenjiaswe](https://github.com/wenjiaswe)**), Google

### Technical Leads
The Technical Leads of the SIG establish new subprojects, decommission existing
subprojects, and resolve cross-subproject technical issues and decisions.

* Benjamin Wang (**[@ahrtr](https://github.com/ahrtr)**), VMware
* Marek Siarkowicz (**[@serathius](https://github.com/serathius)**), Google

## Contact
- Slack: [#sig-etcd](https://kubernetes.slack.com/messages/sig-etcd)
- [Mailing list](https://groups.google.com/g/etcd-dev)
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fetcd)
- GitHub Teams:
    - [@kubernetes/sig-etcd-leads](https://github.com/orgs/kubernetes/teams/sig-etcd-leads) - SIG Chairs and Tech Leads
- Steering Committee Liaison: Antonio Ojea (**[@aojea](https://github.com/aojea)**)

## Working Groups

The following [working groups][working-group-definition] are sponsored by sig-etcd:
* [WG etcd Operator](/wg-etcd-operator)


## Subprojects

The following [subprojects][subproject-definition] are owned by sig-etcd:
### auger
Directly access data objects stored in etcd by kubernetes.
- **Owners:**
  - [etcd-io/auger](https://github.com/etcd-io/auger/blob/master/OWNERS)
### bbolt
An embedded key/value database for Go.
- **Owners:**
  - [etcd-io/bbolt](https://github.com/etcd-io/bbolt/blob/main/OWNERS)
### cetcd
Serve Consul with etcd
- **Owners:**
  - [etcd-io/cetcd/MAINTAINERS](https://github.com/etcd-io/cetcd/blob/master/MAINTAINERS)
### dbtester
Distributed database benchmark tester
- **Owners:**
  - [etcd-io/dbtester/MAINTAINERS](https://github.com/etcd-io/dbtester/blob/master/MAINTAINERS)
### discovery.etcd.io
Kubernetes manifests powering discovery.etcd.io
- **Owners:**
  - [etcd-io/discovery.etcd.io](https://github.com/etcd-io/discovery.etcd.io/blob/master/OWNERS)
### discoveryserver
Public etcd Discovery Service
- **Owners:**
  - [etcd-io/discoveryserver](https://github.com/etcd-io/discoveryserver/blob/master/OWNERS)
### etcd
Distributed reliable key-value store for the most critical data of a distributed system
- **Owners:**
  - [etcd-io/etcd](https://github.com/etcd-io/etcd/blob/main/OWNERS)
### etcd-manager
etcd manager
- **Owners:**
  - [kubernetes-sigs/etcd-manager](https://github.com/kubernetes-sigs/etcd-manager/blob/main/OWNERS)
### etcd-play
etcd playground
- **Owners:**
  - [etcd-io/etcd-play/MAINTAINERS](https://github.com/etcd-io/etcd-play/blob/master/MAINTAINERS)
### etcdlabs
etcd playground
- **Owners:**
  - [etcd-io/etcdlabs/MAINTAINERS](https://github.com/etcd-io/etcdlabs/blob/master/MAINTAINERS)
### gofail
failpoints for go
- **Owners:**
  - [etcd-io/gofail](https://github.com/etcd-io/gofail/blob/master/OWNERS)
### govanityurls
Use a custom domain in your Go import path
- **Owners:**
  - [etcd-io/govanityurls](https://github.com/etcd-io/govanityurls/blob/master/OWNERS)
### jetcd
etcd java client
- **Owners:**
  - [etcd-io/jetcd](https://github.com/etcd-io/jetcd/blob/main/OWNERS)
### maintainers
issue tracking for project wide non-code concerns
- **Owners:**
  - [etcd-io/maintainers/MAINTAINERS](https://github.com/etcd-io/maintainers/blob/master/MAINTAINERS)
### protodoc
protodoc generates Protocol Buffer documentation.
- **Owners:**
  - [etcd-io/protodoc](https://github.com/etcd-io/protodoc/blob/master/OWNERS)
### raft
Raft library for maintaining a replicated state machine
- **Owners:**
  - [etcd-io/raft](https://github.com/etcd-io/raft/blob/main/OWNERS)
### website
etcd-io
- **Owners:**
  - [etcd-io/website](https://github.com/etcd-io/website/blob/main/OWNERS)
### zetcd
Serve the Apache Zookeeper API but back it with an etcd cluster
- **Owners:**
  - [etcd-io/zetcd/MAINTAINERS](https://github.com/etcd-io/zetcd/blob/master/MAINTAINERS)

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
[working-group-definition]: https://github.com/kubernetes/community/blob/master/governance.md#working-groups
<!-- BEGIN CUSTOM CONTENT -->

<!-- END CUSTOM CONTENT -->