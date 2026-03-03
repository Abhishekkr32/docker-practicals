PRACTICALS ACCORDING TO SYLLABUS
PRACTICAL 1 – Basics of Containers

Aim:

Understand container runtime, namespaces, cgroups.

Commands:
docker version
docker info
docker run -it ubuntu bash

Check namespaces:

lsns

Check cgroups:

cat /proc/self/cgroup
Git Maintain:

Inside folder:
README.md
screenshots/

Commit:

git add .
git commit -m "Added container basics practical"
git push