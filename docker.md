

docker常用命令

docker --help



| 命令 | 解释   |
| -------------- | ---- |
| `docker —help` |   帮助   |
| `docker images` |  列出本机镜像  |
| `docker run -d -p 80:80 --name webserver nginx`  |  以别名webserver启动一个镜像 |


| 命令 | 解释   |
| -------------- | ---- |
| `docker ps`    |  列出本机的docker进程  |
| `docker exec -it webserver bash`   |  在webserver的基础上计入它的bash   |
| `cat /etc/issue` | 查询Linux发行版  |

