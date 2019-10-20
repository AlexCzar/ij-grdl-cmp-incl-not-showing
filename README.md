# ij-grdl-cmp-incl-not-showing
Repro of IntelliJ problem with gradle composite project

**What steps will reproduce the issue?**

1. Clone the repository: `git@github.com:AlexCzar/ij-grdl-cmp-incl-not-showing.git`
2. In IntelliJ open `ij-grdl-cmp-incl-not-showing/app-multi-module/build.gradle.kts` as project
3. wait for everything to be imported, maybe sync manually to be sure


**What is the expected result?**

`lib-multi-module` and its modules should be shown in the Project view.

**What happens instead?**

Only app-multi-module modules are shown in the Project view.

Additional: idea.log is in the archive in the repository root.

### Environment
```text
Gradle: 5.6.3
JDK: OpenJDK 11
OS: Linux (OpenSuse Tumbleweed Latest, 64bit)

IntelliJ IDEA 2019.2.3 (Ultimate Edition)
Build #IU-192.6817.14, built on September 24, 2019
Licensed to Alex Czar
Subscription is active until April 6, 2020
Runtime version: 11.0.4+10-b304.69 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o
Linux 5.3.4-1-default
GC: ParNew, ConcurrentMarkSweep
Memory: 1979M
Cores: 16
Registry: external.system.substitute.library.dependencies=true, editor.breadcrumbs.highlight.on.hover=true, ide.tree.ui.experimental=false, ide.balloon.shadow.size=0
Non-Bundled Plugins: CheckStyle-IDEA, GrepConsole, IvyIDEA, LogSupport2, Lombook Plugin, YAML/Ansible support, com.robohorse.robopojogenerator, detekt, com.atlassian.bitbucket.references, ideanginx9, jms-messenger, mobi.hsz.idea.gitignore, net.tweakers.intellij.thesaurus, org.asciidoctor.intellij.asciidoc, com.alivanov.intellij.plugins.liquigen, BashSupport, org.jetbrains.kotlin, no.tornado.tornadofx.idea, com.chrisrm.idea.MaterialThemeUI, com.intellij.plugins.html.instantEditing, com.intellij.plugins.webcomponents, Pythonid, com.google.gct.core, org.apache.camel, org.jetbrains.spek.spek-idea-plugin, org.zalando.intellij.swagger
```
