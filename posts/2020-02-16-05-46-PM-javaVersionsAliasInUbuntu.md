---
preview: Firts step
title: Java Versions Aliases
tags: java, -----post-locked-by:rrLero
author: rrLero
date: 2020-02-16 19:41:00
---
add to `etc/bash.bashrc` such lines

```
# Java Alias
alias java8='source /opt/java/switch/java8.sh'
alias java11='source /opt/java/switch/java11.sh'
```

create those files in opt/java/switch

and add

```
export JAVA_HOME=/usr/lib/jvm/{path-to-needed-java-version}/
export PATH=$PATH:$JAVA_HOME
```

to switch simple type `java11` or `java8` in the terminal