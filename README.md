# [MilkyWay -  Microservices Infrastructure](https://joshdanielwalker.github.io/MilkyWay-Microservices-Infrastructure/index.html)


## Checkout
git clone --recurse-submodules  git@github.com:JoshDanielWalker/MilkyWay.git

Update
git submodule update --remote

git submodule foreach --recursive git checkout master

git submodule foreach -q --recursive 'git checkout $(git config -f $toplevel/.gitmodules submodule.$name.branch || echo master)'

git submodule update --recursive --remote


Part of the MilkyWay,
Microservices Infrastructure Project
By LUNA - Joshua Daniel Walker


## Branch Template <br/>
### Gitflow <br/>
master <br/>
develop <br/>
feature/ <br/>
release/ <br/>
hotfix/ <br/>

## Version Tag Template <br/>
major - minor - Patch <br/>
v-0.0.0 <br/>

## Commit Template <br/>
Project Name - Ticket Number -  Status  -   Time	 -  Commit Message <br/>
MilkyWay     -     1         - #resolve - #time 2h - #comment Message <br/>
