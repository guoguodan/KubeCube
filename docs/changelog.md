# v1.9.0

## Feature
- add a choice to create tenant project ns or not  [#349](https://github.com/kubecube-io/KubeCube/pull/349)
- update user belong to project info [#347](https://github.com/kubecube-io/KubeCube/pull/347)
- add warden gc work [#344](https://github.com/kubecube-io/KubeCube/pull/344)
- Feature cube k8s proxy [#343](https://github.com/kubecube-io/KubeCube/pull/343)
- optimize: add api for list cuberesourcequota[#342](https://github.com/kubecube-io/KubeCube/pull/342)
- chore: remove refs to deprecated io/ioutil [#341](https://github.com/kubecube-io/KubeCube/pull/341)
- Feat remove hnc  [#340](https://github.com/kubecube-io/KubeCube/pull/340)

## BugFix
- fix list cube resource quota [#346](https://github.com/kubecube-io/KubeCube/pull/346)

## Dependencies

- nginx-ingress v0.46.0
- helm 3.12
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.9

## BugFix
- Add switch for swag [#336](https://github.com/kubecube-io/KubeCube/pull/336)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.8

## BugFix
- fix log api [#335](https://github.com/kubecube-io/KubeCube/pull/335)
- fix proxy log stream [#334](https://github.com/kubecube-io/KubeCube/pull/334)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.7

## BugFix
- fix list deployment bug [#331](https://github.com/kubecube-io/KubeCube/pull/331)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.6

## BugFix
- fix warden delete sync bug [#329](https://github.com/kubecube-io/KubeCube/pull/329)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.5

## BugFix
- add pod status reason and fix deployment [#324](https://github.com/kubecube-io/KubeCube/pull/324)
- update containerd version [#322](https://github.com/kubecube-io/KubeCube/pull/322)
- fix watch request [#321](https://github.com/kubecube-io/KubeCube/pull/321)

## Feature
- Feat expose klog set [#305](https://github.com/kubecube-io/KubeCube/pull/318)
- add configmap history(alpha)  [#301](https://github.com/kubecube-io/KubeCube/pull/319)
- add pod reason for pvc and query pod in all namespace [#327](https://github.com/kubecube-io/KubeCube/pull/327)
- support to change log level when running [#326](https://github.com/kubecube-io/KubeCube/pull/326)
- optimize code lint [#328](https://github.com/kubecube-io/KubeCube/pull/328)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.4

## Bugfix
- ignore cluster init error and keep retry background [#305](https://github.com/kubecube-io/KubeCube/pull/305)
- fix gpu const [#301](https://github.com/kubecube-io/KubeCube/pull/301)
- add paginate for cluster infos [#298](https://github.com/kubecube-io/KubeCube/pull/298)
- move binding ctrls to warden [#307](https://github.com/kubecube-io/KubeCube/pull/307)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.3

## Bugfix
- Reverse time sort [#292](https://github.com/kubecube-io/KubeCube/pull/292)
- Fix string sort [#286](https://github.com/kubecube-io/KubeCube/pull/286)

## Feature
- support daemonsets level [#295](https://github.com/kubecube-io/KubeCube/pull/295)
- support multi yaml deploy  [#294](https://github.com/kubecube-io/KubeCube/pull/294)
- add fuzzy match for get subnamespace [#273](https://github.com/kubecube-io/KubeCube/pull/273)
- audit middleware support to config request headers who is recorded  [#291](https://github.com/kubecube-io/KubeCube/pull/291)
- optimize api errors [#288](https://github.com/kubecube-io/KubeCube/pull/288)
- add api sort [#287](https://github.com/kubecube-io/KubeCube/pull/287)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.2

## Bugfix
- fix hotplug [#277](https://github.com/kubecube-io/KubeCube/pull/277)
- fix multi cluster sdk delete problem [#276](https://github.com/kubecube-io/KubeCube/pull/276)
- support namespace fuzzy match [#274](https://github.com/kubecube-io/KubeCube/pull/274)
- fix create binding [#273](https://github.com/kubecube-io/KubeCube/pull/273)
- fix get projects [#272](https://github.com/kubecube-io/KubeCube/pull/272)
- fix binding ctrl [#271](https://github.com/kubecube-io/KubeCube/pull/271)
- fix scout nil ptr [#270](https://github.com/kubecube-io/KubeCube/pull/270)
- fix node gpu key [#269](https://github.com/kubecube-io/KubeCube/pull/269)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.1

## Bugfix
- Fix auth get permission [#256](https://github.com/kubecube-io/KubeCube/pull/256)
- fix node status filter [#258](https://github.com/kubecube-io/KubeCube/pull/258)
- fix fuzzy filter bug [#259](https://github.com/kubecube-io/KubeCube/pull/259)
- modify permission cm data [#260](https://github.com/kubecube-io/KubeCube/pull/260)
- modify node judgement [#262](https://github.com/kubecube-io/KubeCube/pull/262)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.8.0

## Feature
- add replicaset func [#250](https://github.com/kubecube-io/KubeCube/pull/250)
- feat: allowed to enable controllers by options [#241](https://github.com/kubecube-io/KubeCube/pull/241)
- modify svc controller log level to debug [#253](https://github.com/kubecube-io/KubeCube/pull/253)

## Bugfix
- fix heartbeat report and merge 1.7.7 back to main [#252](https://github.com/kubecube-io/KubeCube/pull/252)
- update proxy user [#249](https://github.com/kubecube-io/KubeCube/pull/249)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.7

## Bugfix
- fix auth new transport  [#247](https://github.com/kubecube-io/KubeCube/pull/247)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.6

## Bugfix
- add cache discovery [#240](https://github.com/kubecube-io/KubeCube/pull/240)
- Fix filter bug [#239](https://github.com/kubecube-io/KubeCube/pull/239)
- fix sort func [#238](https://github.com/kubecube-io/KubeCube/pull/238)
- update proxy identity [#237](https://github.com/kubecube-io/KubeCube/pull/238)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.5

## Bugfix
- Support delete hnc ns labels [#235](https://github.com/kubecube-io/KubeCube/pull/235)
- support customize ns labels [#234](https://github.com/kubecube-io/KubeCube/pull/234)
- fix resourcequota controller filter [#233](https://github.com/kubecube-io/KubeCube/pull/233)
- fix ns cluster judge [#232](https://github.com/kubecube-io/KubeCube/pull/232)
- fix resourcequota set [#231](https://github.com/kubecube-io/KubeCube/pull/231)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.4

## Bugfix
- fix node result [#227](https://github.com/kubecube-io/KubeCube/pull/227)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.3

## Feature
- Update filter method [#168](https://github.com/kubecube-io/KubeCube/pull/168)

## Bugfix
- fix warden sync [#220](https://github.com/kubecube-io/KubeCube/pull/220)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.2

## Bugfix
- fix cluster info abnormal return [#215](https://github.com/kubecube-io/KubeCube/pull/215)
- Add user raletionship [#214](https://github.com/kubecube-io/KubeCube/pull/214)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.1

## Bugfix
- fix proxy func label selector  [#212](https://github.com/kubecube-io/KubeCube/pull/212)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.7.0

## Feature
- Feat fieldmanager [#201](https://github.com/kubecube-io/KubeCube/pull/201)
- feature: add cluster livedata api [#199](https://github.com/kubecube-io/KubeCube/pull/199)
- Enhance: update wechat image[#198](https://github.com/kubecube-io/KubeCube/pull/198)

## Bugfix
- Fix service extend  [#209](https://github.com/kubecube-io/KubeCube/pull/209)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.6.2

## Bugfix
- Fix get ns apis [#203](https://github.com/kubecube-io/KubeCube/pull/203)
- in proxy filter, use label selector first [#202](https://github.com/kubecube-io/KubeCube/pull/202)
- Bugfix delete tenant [#200](https://github.com/kubecube-io/KubeCube/pull/200)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4
# v1.6.1

## Feature

- update warden resource sync [#194](https://github.com/kubecube-io/KubeCube/pull/194)

## Bugfix
- Fix: warden pivot url parse error [#194](https://github.com/kubecube-io/KubeCube/pull/194)
- Fix: query pod list [#196](https://github.com/kubecube-io/KubeCube/pull/196)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4


# v1.6.0

## Feature

- update proxy transport [#188](https://github.com/kubecube-io/KubeCube/pull/188)
- warden support special kubecube scheme [#186](https://github.com/kubecube-io/KubeCube/pull/186)
- widen the number of characters in the cluster name to 100 [#178](https://github.com/kubecube-io/KubeCube/pull/178)
- Feature delete tenant project [#177](https://github.com/kubecube-io/KubeCube/pull/177)


## Bugfix
- Fix: workflow error, missing build in makefile [#184](https://github.com/kubecube-io/KubeCube/pull/184)
- [typos] Fix the swag annotations for HealthyCheck [#183](https://github.com/kubecube-io/KubeCube/pull/183)
- feat: ci-lint [#181](https://github.com/kubecube-io/KubeCube/pull/181)
- fix audit eventTime and userIdentity field [#176](https://github.com/kubecube-io/KubeCube/pull/176)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4


# v1.5.2

## Bugfix

- optimize cluster info api and add query flag for simplify info [#187](https://github.com/kubecube-io/KubeCube/pull/187)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.5.1

## Bugfix

- if sorting is not required, return directly in the sorting method [#180](https://github.com/kubecube-io/KubeCube/pull/180)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.5.0

## Feature

- feat:<tenant> get namespaces and project by multi tenant [#175](https://github.com/kubecube-io/KubeCube/pull/175)
- feat:<ingress> optimized port check implementation [#173](https://github.com/kubecube-io/KubeCube/pull/173)
- create a NodePort Service to check whether ports conflict [#169](https://github.com/kubecube-io/KubeCube/pull/169)
- support list pod by owner uid like deployment uid [#166](https://github.com/kubecube-io/KubeCube/pull/166) 

## Bugfix

- fix namespace display abnormal [#170](https://github.com/kubecube-io/KubeCube/pull/170)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.4.2

## Bugfix

- get cluster resource support filter [#164](https://github.com/kubecube-io/KubeCube/pull/164)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.4.1

## Bugfix

- fix capacity memory back [#162](https://github.com/kubecube-io/KubeCube/pull/162)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.4.0

## Feature
- Support cluster cn name[#158](https://github.com/kubecube-io/KubeCube/pull/158)

## Bugfix

- version convert fix list bug [#160](https://github.com/kubecube-io/KubeCube/pull/160)
- fix auth access api [#159](https://github.com/kubecube-io/KubeCube/pull/159)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.4

# v1.3.1

## Bugfix
- fix multi cluster add error[#156](https://github.com/kubecube-io/KubeCube/pull/156)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v1.3.0

## Feature
- optimize multi cluster sync logic[#150](https://github.com/kubecube-io/KubeCube/pull/150)
- extend cluster info[#151](https://github.com/kubecube-io/KubeCube/pull/151) ,[#154](https://github.com/kubecube-io/KubeCube/pull/154)
- user spec add wechat[#146](https://github.com/kubecube-io/KubeCube/pull/146)

## Clean up
- move resourcequota process form webhook to controller[#152](https://github.com/kubecube-io/KubeCube/pull/152)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v1.2.5

## Feature
- support set cluster is writable[#148](https://github.com/kubecube-io/KubeCube/pull/148)
- add multi filter support[#144](https://github.com/kubecube-io/KubeCube/pull/144)
- user spec add wechat[#146](https://github.com/kubecube-io/KubeCube/pull/146)

## Bugfix
- Fix service nil [#147](https://github.com/kubecube-io/KubeCube/pull/147)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v1.2.4

## Feature
- Feature sign cluster iswritleable[#142](https://github.com/kubecube-io/KubeCube/pull/142)
- Feature support node selector[#141](https://github.com/kubecube-io/KubeCube/pull/141)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v1.2.3

## Feature
- get kubeconfig return file[#137](https://github.com/kubecube-io/KubeCube/pull/137)
- add auth access about readable and writable[#139](https://github.com/kubecube-io/KubeCube/pull/139)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v1.2.2

## Feature
- Feature enhance warden sync extend[#132](https://github.com/kubecube-io/KubeCube/pull/132)
- Feature support pvc mount and support filter by array value[#135](https://github.com/kubecube-io/KubeCube/pull/135)

## BugFix
- fix cluster nil pointor[#133](https://github.com/kubecube-io/KubeCube/pull/133)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.2

# v 1.2.1

## Feature
- Feature service extend [#130](https://github.com/kubecube-io/KubeCube/pull/130)
- Apis support multi auth [#127](https://github.com/kubecube-io/KubeCube/pull/127)
- Get user form context [#124](https://github.com/kubecube-io/KubeCube/pull/124) [#122](https://github.com/kubecube-io/KubeCube/pull/122)
- move crd controller to warden [#123](https://github.com/kubecube-io/KubeCube/pull/123)
- Support rbac for crds [#120](https://github.com/kubecube-io/KubeCube/pull/120)
- support retain resources in member cluster [#118](https://github.com/kubecube-io/KubeCube/pull/118)
- Move project tenant controller [#116](https://github.com/kubecube-io/KubeCube/pull/116)
- add swagger doc [#113](https://github.com/kubecube-io/KubeCube/pull/113)

## BugFix
- add repeat ingress domain suffix identification [#129](https://github.com/kubecube-io/KubeCube/pull/129)
- Fix get assigned resource [#128](Fix get assigned resource)
- Fix audit outbound [#125](https://github.com/kubecube-io/KubeCube/pull/125)
- Fix filter body [#121](https://github.com/kubecube-io/KubeCube/pull/121)
- fix resource quota populate [#117](https://github.com/kubecube-io/KubeCube/pull/117)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.1

# v1.2.0

## Feature
- move resource filter to util [#99](https://github.com/kubecube-io/KubeCube/pull/99)
- adapt hnc ga and use labels spread feature [#98](https://github.com/kubecube-io/KubeCube/pull/98)
- k8s version adaptive convert [#97](https://github.com/kubecube-io/KubeCube/pull/97)
- cluster info add cpu and mem used quota [#96](https://github.com/kubecube-io/KubeCube/pull/96)
- add the access to restapi [#92](https://github.com/kubecube-io/KubeCube/pull/92)
- add audit to yamldeploy, create key, service extend external access[#89](https://github.com/kubecube-io/KubeCube/pull/89)
- kubecube client interface add restful, restmappper, discovery clients [#87](https://github.com/kubecube-io/KubeCube/pull/87)
- yaml deploy change to restclient and use username to auth [#85](https://github.com/kubecube-io/KubeCube/pull/85)
- support set ingress domain suffix [#84](https://github.com/kubecube-io/KubeCube/pull/84)
- Support warden register [#83](https://github.com/kubecube-io/KubeCube/pull/83)
- enhance multi cluster manager pkg [#82](https://github.com/kubecube-io/KubeCube/pull/82)
- update local up script [#81](https://github.com/kubecube-io/KubeCube/pull/81)
- make audit report international [#80](https://github.com/kubecube-io/KubeCube/pull/80)

## BugFix
- Fix version conversion [#101](https://github.com/kubecube-io/KubeCube/pull/101)
- request to login makes error logs in audit middleware [#100](https://github.com/kubecube-io/KubeCube/pull/100)
- Rename clinet.go to client.go [#95](https://github.com/kubecube-io/KubeCube/pull/95)
- remove not exist subResourceQuota [#94](https://github.com/kubecube-io/KubeCube/pull/94)
- update jwt version to dodge attack [#91](https://github.com/kubecube-io/KubeCube/pull/91)
- fix audit middleware to a goroutine [#90](https://github.com/kubecube-io/KubeCube/pull/90)

## Dependencies

- hnc v1.0
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit v1.2.0
- kubecube-webconsole v1.2.0

# v1.1.0

## Feature
- auth-proxy in front of k8s-apiserver for proxying kubectl and restful access ([#73](https://github.com/kubecube-io/KubeCube/pull/73), [#67](https://github.com/kubecube-io/KubeCube/pull/67))
- change algorithm of quota [#72](https://github.com/kubecube-io/KubeCube/pull/72)
- add operation of e2e init and end [#68](https://github.com/kubecube-io/KubeCube/pull/68)
- clean up: implement jwt utils to interface ([#64](https://github.com/kubecube-io/KubeCube/pull/64), [#65](https://github.com/kubecube-io/KubeCube/pull/65))
- github login of oAuth2 support [#60](https://github.com/kubecube-io/KubeCube/pull/60)
- warden-init-container can use charts pkg offline or download it from remote [#57](https://github.com/kubecube-io/KubeCube/pull/57)

## BugFix
- fix that can not add customize ClusterRole [#71](https://github.com/kubecube-io/KubeCube/pull/71)
- hide user password when login [#66](https://github.com/kubecube-io/KubeCube/pull/66)
- close response body after do audit middlewares [#55](https://github.com/kubecube-io/KubeCube/pull/55/files)
- fix hotplug result status error && fix proxy http and https in kubecube [#52](https://github.com/kubecube-io/KubeCube/pull/52)

## Dependencies

- hnc v0.8.0-kubecube.1.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.1.0

# v1.0.3
## BugFix
- fix tenant namespace annotation

## Dependencies

- hnc v0.8.0-kubecube.1.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.0.0

# V1.0.2

## BugFix

- `KubeCube:` fix the problem of resource quota webhook since conformance test

## Dependencies

- hnc v0.8.0-kubecube.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.0.0

# V1.0.1

2021-8-19

## BugFix

- `KubeCube:`fix the bug that use old script to add memeber cluster
- `KubeCube:`fix delete cluster failed

## Dependencies

- hnc v0.8.0-kubecube.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.0.0

# V1.0.0

2021-8-6

## Feature

- `Observability:`add control plane component monitoring
- `Observability:`add administrator alert configuration

## BugFix

- `KubeCube:`decouple ClusterInfo api from metric server
- `Warden:`fix hotplug {{.cluster}} injected error in the member cluster
- `Warden:`added configmap to record components status for fron

## Optimization

- `Warden:`optimize performance of warden informer
- `Warden:`optimize status in the hotplug manifest
- `KubeCube:`optimize performance of cluster controller

## Dependencies

- hnc v0.8.0-kubecube.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.0.0

# V1.0.0-rc0

2021-7-16

## Feature

### Platform management

- Add account management
- Add tenant, project management, and support level-by-level transfer of permissions
- Support OpenAPI
- Add record the operation audit log, supporting KubeCube  and K8s API Server
- Support the component hotplug

### K8s cluster management

- Add permission management, based on K8s RBAC capability expansion
- Add K8s cluster management and resource synchronization between clusters
- Add tenant and namespace quota management

### K8s resource management

- Add workload management
- Add service and discovery management
- Add configuration management
- Add PVC management
- Add Yaml orchestration function

### Observable

- Add the prometheus monitoring function
- Add fail alarm function
- Add log collect and query function

### Online operation and maintenance tools

- Add terminal capabilities
- Provide K8s fault diagnosis tool

### Other non-functional


- Provide All-in-One lightweight deployment mode and provide high-availability deployment mode in production environment
- Provide usage documentation, link [kubecube.io](https://www.kubecube.io/)
- With single test and e2e test
- Conduct laboratory stability and performance tests

## Dependencies


- hnc v0.8.0-kubecube.1
- nginx-ingress v0.46.0
- helm 3.5
- metrics-server v0.4.1
- elasticsearch 7.8
- kubecube-monitoring 15.4.8
- thanos 3.18.0
- logseer v1.0.0
- logagent v1.0.0
- kubecube-audit 1.0.0-rc0
