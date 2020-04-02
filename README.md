----
# ansible-role-util-openjdk

## Purpose
Installs OpenJDK with a choice of JRE or full JDK

## Default variables
| Name | Type | Value | Purpose |
| ---- | ---- | ----- | ------- |
| openjdk_jdk_or_jre | string | jdk | or set to `jre` if that is all you need |
| openjdk_state | string | present | if `absent` will uninstall |
| openjdk_version | integer | 11 | major version of Java |

## Supported Distros
Ubuntu 16+

****
