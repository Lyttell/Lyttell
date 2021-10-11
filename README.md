- 👋 Hi, I’m @Lyttell
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Lyttell/Lyttell is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
"2021-07-26T13:04:04.7235773Z Found online and idle hosted runner(s) in the current repository's organization account that matches the required labels: 'ubuntu-latest'
2021-07-26T13:04:04.7235840Z Waiting for a hosted runner in 'organization' to pick this job...
2021-07-26T13:04:12.1820232Z Current runner version: '2.278.0'
2021-07-26T13:04:12.1845641Z ##[group]Operating System
2021-07-26T13:04:12.1846578Z Ubuntu
2021-07-26T13:04:12.1847077Z 20.04.2
2021-07-26T13:04:12.1847472Z LTS
2021-07-26T13:04:12.1847977Z ##[endgroup]
2021-07-26T13:04:12.1848546Z ##[group]Virtual Environment
2021-07-26T13:04:12.1849154Z Environment: ubuntu-20.04
2021-07-26T13:04:12.1849725Z Version: 20210718.1
2021-07-26T13:04:12.1850668Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu20/20210718.1/images/linux/Ubuntu2004-README.md
2021-07-26T13:04:12.1851985Z Image Release: https://github.com/actions/virtual-environments/releases/tag/ubuntu20%2F20210718.1
2021-07-26T13:04:12.1852805Z ##[endgroup]
2021-07-26T13:04:12.1854684Z ##[group]GITHUB_TOKEN Permissions
2021-07-26T13:04:12.1855881Z Actions: read
2021-07-26T13:04:12.1856339Z Checks: read
2021-07-26T13:04:12.1856845Z Contents: read
2021-07-26T13:04:12.1857342Z Deployments: read
2021-07-26T13:04:12.1857967Z Discussions: read
2021-07-26T13:04:12.1858564Z Issues: read
2021-07-26T13:04:12.1859016Z Metadata: read
2021-07-26T13:04:12.1859541Z Packages: read
2021-07-26T13:04:12.1860032Z PullRequests: read
2021-07-26T13:04:12.1860674Z RepositoryProjects: read
2021-07-26T13:04:12.1861258Z SecurityEvents: read
2021-07-26T13:04:12.1861834Z Statuses: read
2021-07-26T13:04:12.1862395Z ##[endgroup]
2021-07-26T13:04:12.1865408Z Prepare workflow directory
2021-07-26T13:04:12.2453619Z Prepare all required actions
2021-07-26T13:04:12.2464402Z Getting action download info
2021-07-26T13:04:12.7034575Z Download action repository 'actions/checkout@master'
2021-07-26T13:04:14.3683529Z Download action repository 'actions/setup-node@v2.3.0'
2021-07-26T13:04:14.5667647Z Download action repository 'actions/upload-artifact@v2.2.3'
2021-07-26T13:04:14.8377651Z ##[group]Run actions/checkout@master
2021-07-26T13:04:14.8378346Z with:
2021-07-26T13:04:14.8378849Z   repository: devlynnsingley/i18n
2021-07-26T13:04:14.8379852Z   token: ***
2021-07-26T13:04:14.8380289Z   ssh-strict: true
2021-07-26T13:04:14.8380852Z   persist-credentials: true
2021-07-26T13:04:14.8381362Z   clean: true
2021-07-26T13:04:14.8381808Z   fetch-depth: 1
2021-07-26T13:04:14.8382239Z   lfs: false
2021-07-26T13:04:14.8382680Z   submodules: false
2021-07-26T13:04:14.8383126Z ##[endgroup]
2021-07-26T13:04:15.3784369Z Syncing repository: devlynnsingley/i18n
2021-07-26T13:04:15.3785431Z ##[group]Getting Git version info
2021-07-26T13:04:15.3786411Z Working directory is '/home/runner/work/i18n/i18n'
2021-07-26T13:04:15.3787043Z [command]/usr/bin/git version
2021-07-26T13:04:15.3787637Z git version 2.32.0
2021-07-26T13:04:15.3788493Z ##[endgroup]
2021-07-26T13:04:15.3789221Z Deleting the contents of '/home/runner/work/i18n/i18n'
2021-07-26T13:04:15.3792950Z ##[group]Initializing the repository
2021-07-26T13:04:15.3793762Z [command]/usr/bin/git init /home/runner/work/i18n/i18n
2021-07-26T13:04:15.3794815Z hint: Using 'master' as the name for the initial branch. This default branch name
2021-07-26T13:04:15.3795747Z hint: is subject to change. To configure the initial branch name to use in all
2021-07-26T13:04:15.3796693Z hint: of your new repositories, which will suppress this warning, call:
2021-07-26T13:04:15.3797409Z hint: 
2021-07-26T13:04:15.3798262Z hint: 	git config --global init.defaultBranch <name>
2021-07-26T13:04:15.3798935Z hint: 
2021-07-26T13:04:15.3799798Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2021-07-26T13:04:15.3800882Z hint: 'development'. The just-created branch can be renamed via this command:
2021-07-26T13:04:15.3801629Z hint: 
2021-07-26T13:04:15.3802316Z hint: 	git branch -m <name>
2021-07-26T13:04:15.3803069Z Initialized empty Git repository in /home/runner/work/i18n/i18n/.git/
2021-07-26T13:04:15.3804069Z [command]/usr/bin/git remote add origin https://github.com/devlynnsingley/i18n
2021-07-26T13:04:15.3804897Z ##[endgroup]
2021-07-26T13:04:15.3805583Z ##[group]Disabling automatic garbage collection
2021-07-26T13:04:15.3806509Z [command]/usr/bin/git config --local gc.auto 0
2021-07-26T13:04:15.3807534Z ##[endgroup]
2021-07-26T13:04:15.3809375Z ##[group]Setting up auth
2021-07-26T13:04:15.3810405Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2021-07-26T13:04:15.3811924Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2021-07-26T13:04:15.3813469Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2021-07-26T13:04:15.3815358Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2021-07-26T13:04:15.3817175Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2021-07-26T13:04:15.3818129Z ##[endgroup]
2021-07-26T13:04:15.3818767Z ##[group]Fetching the repository
2021-07-26T13:04:15.3820800Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +31cdfed25009ae59eb8fd9c90490bf081ae2b0d4:refs/remotes/pull/1176/merge
2021-07-26T13:04:15.4067229Z remote: Enumerating objects: 2312, done.        
2021-07-26T13:04:15.4068978Z remote: Counting objects:   0% (1/2312)        
2021-07-26T13:04:15.4073914Z remote: Counting objects:   1% (24/2312)        
2021-07-26T13:04:15.4074517Z remote: Counting objects:   2% (47/2312)        
2021-07-26T13:04:15.4075090Z remote: Counting objects:   3% (70/2312)        
2021-07-26T13:04:15.4075649Z remote: Counting objects:   4% (93/2312)        
2021-07-26T13:04:15.4076226Z remote: Counting objects:   5% (116/2312)        
2021-07-26T13:04:15.4077113Z remote: Counting objects:   6% (139/2312)        
2021-07-26T13:04:15.4077696Z remote: Counting objects:   7% (162/2312)        
2021-07-26T13:04:15.4078248Z remote: Counting objects:   8% (185/2312)        
2021-07-26T13:04:15.4085367Z remote: Counting objects:   9% (209/2312)        
2021-07-26T13:04:15.4085941Z remote: Counting objects:  10% (232/2312)        
2021-07-26T13:04:15.4086512Z remote: Counting objects:  11% (255/2312)        
2021-07-26T13:04:15.4087075Z remote: Counting objects:  12% (278/2312)        
2021-07-26T13:04:15.4087626Z remote: Counting objects:  13% (301/2312)        
2021-07-26T13:04:15.4088193Z remote: Counting objects:  14% (324/2312)        
2021-07-26T13:04:15.4093883Z remote: Counting objects:  15% (347/2312)        
2021-07-26T13:04:15.4094466Z remote: Counting objects:  16% (370/2312)        
2021-07-26T13:04:15.4095019Z remote: Counting objects:  17% (394/2312)        
2021-07-26T13:04:15.4095585Z remote: Counting objects:  18% (417/2312)        
2021-07-26T13:04:15.4096162Z remote: Counting objects:  19% (440/2312)        
2021-07-26T13:04:15.4096715Z remote: Counting objects:  20% (463/2312)        
2021-07-26T13:04:15.4097277Z remote: Counting objects:  21% (486/2312)        
2021-07-26T13:04:15.4097839Z remote: Counting objects:  22% (509/2312)        
2021-07-26T13:04:15.4098401Z remote: Counting objects:  23% (532/2312)        
2021-07-26T13:04:15.4098949Z remote: Counting objects:  24% (555/2312)        
2021-07-26T13:04:15.4103863Z remote: Counting objects:  25% (578/2312)        
2021-07-26T13:04:15.4104447Z remote: Counting objects:  26% (602/2312)        
2021-07-26T13:04:15.4104998Z remote: Counting objects:  27% (625/2312)        
2021-07-26T13:04:15.4105560Z remote: Counting objects:  28% (648/2312)        
2021-07-26T13:04:15.4106110Z remote: Counting objects:  29% (671/2312)        
2021-07-26T13:04:15.4106676Z remote: Counting objects:  30% (694/2312)        
2021-07-26T13:04:15.4107653Z remote: Counting objects:  31% (717/2312)        
2021-07-26T13:04:15.4108228Z remote: Counting objects:  32% (740/2312)        
2021-07-26T13:04:15.4108775Z remote: Counting objects:  33% (763/2312)        
2021-07-26T13:04:15.4109385Z remote: Counting objects:  34% (787/2312)        
2021-07-26T13:04:15.4110112Z remote: Counting objects:  35% (810/2312)        
2021-07-26T13:04:15.4110663Z remote: Counting objects:  36% (833/2312)        
2021-07-26T13:04:15.4111229Z remote: Counting objects:  37% (856/2312)        
2021-07-26T13:04:15.4111778Z remote: Counting objects:  38% (879/2312)        
2021-07-26T13:04:15.4112810Z remote: Counting objects:  39% (902/2312)        
2021-07-26T13:04:15.4113419Z remote: Counting objects:  40% (925/2312)        
2021-07-26T13:04:15.4114266Z remote: Counting objects:  41% (948/2312)        
2021-07-26T13:04:15.4114834Z remote: Counting objects:  42% (972/2312)        
2021-07-26T13:04:15.4115484Z remote: Counting objects:  43% (995/2312)        
2021-07-26T13:04:15.4116061Z remote: Counting objects:  44% (1018/2312)        
2021-07-26T13:04:15.4116621Z remote: Counting objects:  45% (1041/2312)        
2021-07-26T13:04:15.4117227Z remote: Counting objects:  46% (1064/2312)        
2021-07-26T13:04:15.4117790Z remote: Counting objects:  47% (1087/2312)        
2021-07-26T13:04:15.4118520Z remote: Counting objects:  48% (1110/2312)        
2021-07-26T13:04:15.4119187Z remote: Counting objects:  49% (1133/2312)        
2021-07-26T13:04:15.4119870Z remote: Counting objects:  50% (1156/2312)        
2021-07-26T13:04:15.4120601Z remote: Counting objects:  51% (1180/2312)        
2021-07-26T13:04:15.4121262Z remote: Counting objects:  52% (1203/2312)        
2021-07-26T13:04:15.4121909Z remote: Counting objects:  53% (1226/2312)        
2021-07-26T13:04:15.4122890Z remote: Counting objects:  54% (1249/2312)        
2021-07-26T13:04:15.4123557Z remote: Counting objects:  55% (1272/2312)        
2021-07-26T13:04:15.4124164Z remote: Counting objects:  56% (1295/2312)        
2021-07-26T13:04:15.4125351Z remote: Counting objects:  57% (1318/2312)        
2021-07-26T13:04:15.4125932Z remote: Counting objects:  58% (1341/2312)        
2021-07-26T13:04:15.4126618Z remote: Counting objects:  59% (1365/2312)        
2021-07-26T13:04:15.4127280Z remote: Counting objects:  60% (1388/2312)        
2021-07-26T13:04:15.4127964Z remote: Counting objects:  61% (1411/2312)        
2021-07-26T13:04:15.4128880Z remote: Counting objects:  62% (1434/2312)        
2021-07-26T13:04:15.4130631Z remote: Counting objects:  63% (1457/2312)        
2021-07-26T13:04:15.4131205Z remote: Counting objects:  64% (1480/2312)        
2021-07-26T13:04:15.4131874Z remote: Counting objects:  65% (1503/2312)        
2021-07-26T13:04:15.4132543Z remote: Counting objects:  66% (1526/2312)        
2021-07-26T13:04:15.4133213Z remote: Counting objects:  67% (1550/2312)        
2021-07-26T13:04:15.4133858Z remote: Counting objects:  68% (1573/2312)        
2021-07-26T13:04:15.4134708Z remote: Counting objects:  69% (1596/2312)        
2021-07-26T13:04:15.4137854Z remote: Counting objects:  70% (1619/2312)        
2021-07-26T13:04:15.4138553Z remote: Counting objects:  71% (1642/2312)        
2021-07-26T13:04:15.4139224Z remote: Counting objects:  72% (1665/2312)        
2021-07-26T13:04:15.4140777Z remote: Counting objects:  73% (1688/2312)        
2021-07-26T13:04:15.4141605Z remote: Counting objects:  74% (1711/2312)        
2021-07-26T13:04:15.4148414Z remote: Counting objects:  75% (1734/2312)        
2021-07-26T13:04:15.4149501Z remote: Counting objects:  76% (1758/2312)        
2021-07-26T13:04:15.4151087Z remote: Counting objects:  77% (1781/2312)        
2021-07-26T13:04:15.4153700Z remote: Counting objects:  78% (1804/2312)        
2021-07-26T13:04:15.4154837Z remote: Counting objects:  79% (1827/2312)        
2021-07-26T13:04:15.4158242Z remote: Counting objects:  80% (1850/2312)        
2021-07-26T13:04:15.4158874Z remote: Counting objects:  81% (1873/2312)        
2021-07-26T13:04:15.4159441Z remote: Counting objects:  82% (1896/2312)        
2021-07-26T13:04:15.4162171Z remote: Counting objects:  83% (1919/2312)        
2021-07-26T13:04:15.4162867Z remote: Counting objects:  84% (1943/2312)        04:15.4163530Z remote: Counting objects:  85% (1966/2312)        
2021-07-26T13:04:15.4164132Z remote: Counting objects:  86% (1989/2312)        
2021-07-26T13:04:15.4164937Z remote: Counting objects:  87% (2012/2312)        
2021-07-26T13:04:15.4169926Z remote: Counting objects:  88% (2035/2312)        
2021-07-26T13:04:15.4172465Z remote: Counting objects:  89% (2058/2312)        
2021-07-26T13:04:15.4173144Z remote: Counting objects:  90% (2081/2312)        
2021-07-26T13:04:15.4173813Z remote: Counting objects:  91% (2104/2312)        
2021-07-26T13:04:15.4174483Z remote: Counting objects:  92% (2128/2312)        
2021-07-26T13:04:15.4177540Z remote: Counting objects:  93% (2151/2312)        
2021-07-26T13:04:15.4178225Z remote: Counting objects:  94% (2174/2312)        
2021-07-26T13:04:15.4178898Z remote: Counting objects:  95% (2197/2312)        
2021-07-26T13:04:15.4179575Z remote: Counting objects:  96% (2220/2312)        
2021-07-26T13:04:15.4180244Z remote: Counting objects:  97% (2243/2312)        
2021-07-26T13:04:15.4183340Z remote: Counting objects:  98% (2266/2312)        
2021-07-26T13:04:15.4184049Z remote: Counting objects:  99% (2289/2312)        
2021-07-26T13:04:15.4184709Z remote: Counting objects: 100% (2312/2312)        
2021-07-26T13:04:15.4185375Z remote: Counting objects: 100% (2312/2312), done.        
2021-07-26T13:04:15.4194276Z remote: Compressing objects:   0% (1/2019)        
2021-07-26T13:04:15.4513892Z remote: Compressing objects:   1% (21/2019)        
2021-07-26T13:04:15.4587674Z remote: Compressing objects:   2% (41/2019)        
2021-07-26T13:04:15.4765446Z remote: Compressing objects:   3% (61/2019)        
2021-07-26T13:04:15.4784428Z remote: Compressing objects:   4% (81/2019)        
2021-07-26T13:04:15.4975593Z remote: Compressing objects:   5% (101/2019)        
2021-07-26T13:04:15.5234944Z remote: Compressing objects:   6% (122/2019)        
2021-07-26T13:04:15.5261544Z remote: Compressing objects:   7% (142/2019)        
2021-07-26T13:04:15.5267801Z remote: Compressing objects:   8% (162/2019)        
2021-07-26T13:04:15.5301538Z remote: Compressing objects:   9% (182/2019)        
2021-07-26T13:04:15.5329039Z remote: Compressing objects:  10% (202/2019)        
2021-07-26T13:04:15.5406300Z remote: Compressing objects:  11% (223/2019)        
2021-07-26T13:04:15.5462327Z remote: Compressing objects:  12% (243/2019)        
2021-07-26T13:04:15.5502311Z remote: Compressing objects:  13% (263/2019)        
2021-07-26T13:04:15.5551598Z remote: Compressing objects:  14% (283/2019)        
2021-07-26T13:04:15.5607184Z remote: Compressing objects:  15% (303/2019)        
2021-07-26T13:04:15.5816871Z remote: Compressing objects:  16% (324/2019)        
2021-07-26T13:04:15.5932415Z remote: Compressing objects:  17% (344/2019)        
2021-07-26T13:04:15.6026763Z remote: Compressing objects:  18% (364/2019)        
2021-07-26T13:04:15.6049929Z remote: Compressing objects:  19% (384/2019)        
2021-07-26T13:04:15.6061679Z remote: Compressing objects:  20% (404/2019)        
2021-07-26T13:04:15.6071228Z remote: Compressing objects:  21% (424/2019)        
2021-07-26T13:04:15.6073193Z remote: Compressing objects:  22% (445/2019)        
2021-07-26T13:04:15.6084126Z remote: Compressing objects:  23% (465/2019)        
2021-07-26T13:04:15.6100121Z remote: Compressing objects:  24% (485/2019)        
2021-07-26T13:04:15.6100873Z remote: Compressing objects:  25% (505/2019)        
2021-07-26T13:04:15.6145374Z remote: Compressing objects:  26% (525/2019)        
2021-07-26T13:04:15.6207178Z remote: Compressing objects:  27% (546/2019)        
2021-07-26T13:04:15.6263496Z remote: Compressing objects:  28% (566/2019)        
2021-07-26T13:04:15.6300105Z remote: Compressing objects:  29% (586/2019)        
2021-07-26T13:04:15.6302571Z remote: Compressing objects:  30% (606/2019)        
2021-07-26T13:04:15.6328775Z remote: Compressing objects:  31% (626/2019)        
2021-07-26T13:04:15.6442457Z remote: Compressing objects:  32% (647/2019)        
2021-07-26T13:04:15.6487972Z remote: Compressing objects:  33% (667/2019)        
2021-07-26T13:04:15.6542845Z remote: Compressing objects:  34% (687/2019)        
2021-07-26T13:04:15.6593150Z remote: Compressing objects:  35% (707/2019)        
2021-07-26T13:04:15.6660290Z remote: Compressing objects:  36% (727/2019)        
2021-07-26T13:04:15.6676144Z remote: Compressing objects:  37% (748/2019)        
2021-07-26T13:04:15.6759110Z remote: Compressing objects:  38% (768/2019)        
2021-07-26T13:04:15.6811802Z remote: Compressing objects:  39% (788/2019)        
2021-07-26T13:04:15.6991364Z remote: Compressing objects:  40% (808/2019)        
2021-07-26T13:04:15.7101901Z remote: Compressing objects:  41% (828/2019)        
2021-07-26T13:04:15.7188928Z remote: Compressing objects:  42% (848/2019)        
2021-07-26T13:04:15.7290469Z remote: Compressing objects:  43% (869/2019)        
2021-07-26T13:04:15.7326099Z remote: Compressing objects:  44% (889/2019)        
2021-07-26T13:04:15.7391895Z remote: Compressing objects:  45% (909/2019)        
2021-07-26T13:04:15.7428759Z remote: Compressing objects:  46% (929/2019)        
2021-07-26T13:04:15.7468555Z remote: Compressing objects:  47% (949/2019)        
2021-07-26T13:04:15.7478333Z remote: Compressing objects:  48% (970/2019)        
2021-07-26T13:04:15.7566631Z remote: Compressing objects:  49% (990/2019)        
2021-07-26T13:04:15.7754625Z remote: Compressing objects:  50% (1010/2019)        
2021-07-26T13:04:15.7811907Z remote: Compressing objects:  51% (1030/2019)        
2021-07-26T13:04:15.7902405Z remote: Compressing objects:  52% (1050/2019)        
2021-07-26T13:04:15.7943680Z remote: Compressing objects:  53% (1071/2019)        
2021-07-26T13:04:15.7969753Z remote: Compressing objects:  54% (1091/2019)        
2021-07-26T13:04:15.8026940Z remote: Compressing objects:  55% (1111/2019)        
2021-07-26T13:04:15.8071575Z remote: Compressing objects:  56% (1131/2019)        
2021-07-26T13:04:15.8145431Z remote: Compressing objects:  57% (1151/2019)        
2021-07-26T13:04:15.8158736Z remote: Compressing objects:  58% (1172/2019)        
2021-07-26T13:04:15.8164985Z remote: Compressing objects:  59% (1192/2019)        
2021-07-26T13:04:15.8209393Z remote: Compressing objects:  60% (1212/2019)        
2021-07-26T13:04:15.8277863Z remote: Compressing objects:  61% (1232/2019)        
2021-07-26T13:04:15.8352410Z remote: Compressing objects:  62% (1252/2019)        
2021-07-26T13:04:15.8365154Z remote: Compressing objects:  63% (1272/2019)        
2021-07-26T13:04:15.8408359Z remote: Compressing objects:  64% (1293/2019)        
2021-07-26T13:04:15.8430411Z remote: Compressing objects:  65% (1313/2019)        
2021-07-26T13:04:15.8463917Z remote: Compressing objects:  66% (1333/2019)        
2021-07-26T13:04:15.8469414Z remote: Compressing objects:  67% (1353/2019)        
2021-07-26T13:04:15.8520248Z remote: Compressing objects:  68% (1373/2019)        
2021-07-26T13:04:15.8527400Z remote: Compressing objects:  69% (1394/2019)        
2021-07-26T13:04:15.8621941Z remote: Compressing objects:  70% (1414/2019)        
2021-07-26T13:04:15.8751854Z remote: Compressing objects:  71% (1434/2019)        
2021-07-26T13:04:15.8824685Z remote: Compressing objects:  72% (1454/2019)        
2021-07-26T13:04:15.8856628Z remote: Compressing objects:  73% (1474/2019)        
2021-07-26T13:04:15.8879186Z remote: Compressing objects:  74% (1495/2019)        
2021-07-26T13:04:15.8904472Z remote: Compressing objects:  75% (1515/2019)        
2021-07-26T13:04:15.8993289Z remote: Compressing objects:  76% (1535/2019)        
2021-07-26T13:04:15.9001485Z remote: Compressing objects:  77% (1555/2019)        
2021-07-26T13:04:15.9046950Z remote: Compressing objects:  78% (1575/2019)        
2021-07-26T13:04:15.9061234Z remote: Compressing objects:  79% (1596/2019)        
2021-07-26T13:04:15.9099891Z remote: Compressing objects:  80% (1616/2019)        
2021-07-26T13:04:15.9121710Z remote: Compressing objects:  81% (1636/2019)        
2021-07-26T13:04:15.9142015Z remote: Compressing objects:  82% (1656/2019)        
2021-07-26T13:04:15.9199484Z remote: Compressing objects:  83% (1676/2019)        
2021-07-26T13:04:15.9300869Z remote: Compressing objects:  84% (1696/2019)        
2021-07-26T13:04:15.9433793Z remote: Compressing objects:  85% (1717/2019)        
2021-07-26T13:04:15.9529293Z remote: Compressing objects:  86% (1737/2019)        
2021-07-26T13:04:15.9529903Z remote: Compressing objects:  87% (1757/2019)        
2021-07-26T13:04:15.9541668Z remote: Compressing objects:  88% (1777/2019)        
2021-07-26T13:04:15.9584746Z remote: Compressing objects:  89% (1797/2019)        
2021-07-26T13:04:15.9593396Z remote: Compressing objects:  90% (1818/2019)        
2021-07-26T13:04:15.9618468Z remote: Compressing objects:  91% (1838/2019)        
2021-07-26T13:04:15.9700000Z remote: Compressing objects:  92% (1858/2019)        
2021-07-26T13:04:15.9784062Z remote: Compressing objects:  93% (1878/2019)        
2021-07-26T13:04:15.9863969Z remote: Compressing objects:  94% (1898/2019)        
2021-07-26T13:04:15.9952245Z remote: Compressing objects:  95% (1919/2019)        
2021-07-26T13:04:16.0001148Z remote: Compressing objects:  96% (1939/2019)        
2021-07-26T13:04:16.0020359Z remote: Compressing objects:  97% (1959/2019)        
2021-07-26T13:04:16.0077156Z remote: Compressing objects:  98% (1979/2019)        
2021-07-26T13:04:16.0077764Z remote: Compressing objects:  99% (1999/2019)        
2021-07-26T13:04:16.0078308Z remote: Compressing objects: 100% (2019/2019)        
2021-07-26T13:04:16.0083706Z remote: Compressing objects: 100% (2019/2019), done.        
2021-07-26T13:04:16.0297184Z Receiving objects:   0% (1/2312)
2021-07-26T13:04:16.0418224Z Receiving objects:   1% (24/2312)
2021-07-26T13:04:16.0436476Z Receiving objects:   2% (47/2312)
2021-07-26T13:04:16.0462722Z Receiving objects:   3% (70/2312)
2021-07-26T13:04:16.0498076Z Receiving objects:   4% (93/2312)
2021-07-26T13:04:16.0536169Z Receiving objects:   5% (116/2312)
2021-07-26T13:04:16.0552710Z Receiving objects:   6% (139/2312)
2021-07-26T13:04:16.0560492Z Receiving objects:   7% (162/2312)
2021-07-26T13:04:16.0575775Z Receiving objects:   8% (185/2312)
2021-07-26T13:04:16.0592056Z Receiving objects:   9% (209/2312)
2021-07-26T13:04:16.0611014Z Receiving objects:  10% (232/2312)
2021-07-26T13:04:16.0672513Z Receiving objects:  11% (255/2312)
2021-07-26T13:04:16.0702273Z Receiving objects:  12% (278/2312)
2021-07-26T13:04:16.0709315Z Receiving objects:  13% (301/2312)
2021-07-26T13:04:16.0734435Z Receiving objects:  14% (324/2312)
2021-07-26T13:04:16.0760355Z Receiving objects:  15% (347/2312)
2021-07-26T13:04:16.0790914Z Receiving objects:  16% (370/2312)
2021-07-26T13:04:16.0824226Z Receiving objects:  17% (394/2312)
2021-07-26T13:04:16.0855000Z Receiving objects:  18% (417/2312)
2021-07-26T13:04:16.0879746Z Receiving objects:  19% (440/2312)
2021-07-26T13:04:16.0898566Z Receiving objects:  20% (463/2312)
2021-07-26T13:04:16.0951641Z Receiving objects:  21% (486/2312)
2021-07-26T13:04:16.0956963Z Receiving objects:  22% (509/2312)
2021-07-26T13:04:16.0972580Z Receiving objects:  23% (532/2312)
2021-07-26T13:04:16.0981594Z Receiving objects:  24% (555/2312)
2021-07-26T13:04:16.0982089Z Receiving objects:  25% (578/2312)
2021-07-26T13:04:16.1015413Z Receiving objects:  26% (602/2312)
2021-07-26T13:04:16.1039361Z Receiving objects:  27% (625/2312)
2021-07-26T13:04:16.1073860Z Receiving objects:  28% (648/2312)
2021-07-26T13:04:16.1507045Z Receiving objects:  29% (671/2312)
2021-07-26T13:04:16.1518222Z Receiving objects:  30% (694/2312)
2021-07-26T13:04:16.1534271Z Receiving objects:  31% (717/2312)
2021-07-26T13:04:16.1548526Z Receiving objects:  32% (740/2312)
2021-07-26T13:04:16.1579549Z Receiving objects:  33% (763/2312)
2021-07-26T13:04:16.1593174Z Receiving objects:  34% (787/2312)
2021-07-26T13:04:16.1601733Z Receiving objects:  35% (810/2312)
2021-07-26T13:04:16.1612692Z Receiving objects:  36% (833/2312)
2021-07-26T13:04:16.1620861Z Receiving objects:  37% (856/2312)
2021-07-26T13:04:16.1696840Z Receiving objects:  38% (879/2312)
2021-07-26T13:04:16.1719685Z Receiving objects:  39% (902/2312)
2021-07-26T13:04:16.1747384Z Receiving objects:  40% (925/2312)
2021-07-26T13:04:16.1794068Z Receiving objects:  41% (948/2312)
2021-07-26T13:04:16.1824188Z Receiving objects:  42% (972/2312)
2021-07-26T13:04:16.1869413Z Receiving objects:  43% (995/2312)
2021-07-26T13:04:16.1870229Z Receiving objects:  44% (1018/2312)
2021-07-26T13:04:16.1963746Z Receiving objects:  45% (1041/2312)
2021-07-26T13:04:16.1977323Z Receiving objects:  46% (1064/2312)
2021-07-26T13:04:16.1981324Z Receiving objects:  47% (1087/2312)
2021-07-26T13:04:16.1991993Z Receiving objects:  48% (1110/2312)
2021-07-26T13:04:16.2022597Z Receiving objects:  49% (1133/2312)
2021-07-26T13:04:16.2049498Z Receiving objects:  50% (1156/2312)
2021-07-26T13:04:16.2100225Z Receiving objects:  51% (1180/2312)
2021-07-26T13:04:16.2127698Z Receiving objects:  52% (1203/2312)
2021-07-26T13:04:16.2146753Z Receiving objects:  53% (1226/2312)
2021-07-26T13:04:16.2162609Z Receiving objects:  54% (1249/2312)
2021-07-26T13:04:16.2207949Z Receiving objects:  55% (1272/2312)
2021-07-26T13:04:16.2311134Z Receiving objects:  56% (1295/2312)
2021-07-26T13:04:16.2348332Z Receiving objects:  57% (1318/2312)
2021-07-26T13:04:16.2355402Z Receiving objects:  58% (1341/2312)
2021-07-26T13:04:16.2374937Z Receiving objects:  59% (1365/2312)
2021-07-26T13:04:16.2381076Z Receiving objects:  60% (1388/2312)
2021-07-26T13:04:16.2473714Z Receiving objects:  61% (1411/2312)
2021-07-26T13:04:16.2503875Z Receiving objects:  62% (1434/2312)
2021-07-26T13:04:16.2554379Z Receiving objects:  63% (1457/2312)
2021-07-26T13:04:16.2607694Z Receiving objects:  64% (1480/2312)
2021-07-26T13:04:16.2638584Z Receiving objects:  65% (1503/2312)
2021-07-26T13:04:16.2696204Z Receiving objects:  66% (1526/2312)
2021-07-26T13:04:16.2757203Z Receiving objects:  67% (1550/2312)
2021-07-26T13:04:16.2785744Z Receiving objects:  68% (1573/2312)
2021-07-26T13:04:16.2799680Z Receiving objects:  69% (1596/2312)
2021-07-26T13:04:16.2801551Z Receiving objects:  70% (1619/2312)
2021-07-26T13:04:16.2805110Z Receiving objects:  71% (1642/2312)
2021-07-26T13:04:16.2826592Z Receiving objects:  72% (1665/2312)
2021-07-26T13:04:16.2882703Z Receiving objects:  73% (1688/2312)
2021-07-26T13:04:16.2916524Z Receiving objects:  74% (1711/2312)
2021-07-26T13:04:16.2941605Z Receiving objects:  75% (1734/2312)
2021-07-26T13:04:16.2958125Z Receiving objects:  76% (1758/2312)
2021-07-26T13:04:16.2995413Z Receiving objects:  77% (1781/2312)
2021-07-26T13:04:16.3048170Z Receiving objects:  78% (1804/2312)
2021-07-26T13:04:16.3055824Z Receiving objects:  79% (1827/2312)
2021-07-26T13:04:16.3070420Z Receiving objects:  80% (1850/2312)
2021-07-26T13:04:16.3098841Z Receiving objects:  81% (1873/2312)
2021-07-26T13:04:16.3172031Z Receiving objects:  82% (1896/2312)
2021-07-26T13:04:16.3198003Z Receiving objects:  83% (1919/2312)
2021-07-26T13:04:16.3226071Z Receiving objects:  84% (1943/2312)
2021-07-26T13:04:16.3250821Z Receiving objects:  85% (1966/2312)
2021-07-26T13:04:16.3293498Z Receiving objects:  86% (1989/2312)
2021-07-26T13:04:16.3311509Z Receiving objects:  87% (2012/2312)
2021-07-26T13:04:16.3328488Z Receiving objects:  88% (2035/2312)
2021-07-26T13:04:16.3339006Z Receiving objects:  89% (2058/2312)
2021-07-26T13:04:16.3361392Z Receiving objects:  90% (2081/2312)
2021-07-26T13:04:16.3374092Z Receiving objects:  91% (2104/2312)
2021-07-26T13:04:16.3387151Z Receiving objects:  92% (2128/2312)
2021-07-26T13:04:16.3415771Z Receiving objects:  93% (2151/2312)
2021-07-26T13:04:16.3453378Z Receiving objects:  94% (2174/2312)
2021-07-26T13:04:16.3475364Z Receiving objects:  95% (2197/2312)
2021-07-26T13:04:16.3503328Z Receiving objects:  96% (2220/2312)
2021-07-26T13:04:16.3517199Z Receiving objects:  97% (2243/2312)
2021-07-26T13:04:16.3676056Z Receiving objects:  98% (2266/2312)
2021-07-26T13:04:16.3717267Z Receiving objects:  99% (2289/2312)
2021-07-26T13:04:16.3718831Z remote: Total 2312 (delta 596), reused 830 (delta 285), pack-reused 0        
2021-07-26T13:04:16.3742705Z Receiving objects: 100% (2312/2312)
2021-07-26T13:04:16.3743333Z Receiving objects: 100% (2312/2312), 3.93 MiB | 11.40 MiB/s, done.
2021-07-26T13:04:16.4194970Z Resolving deltas:   0% (0/596)
2021-07-26T13:04:16.4200061Z Resolving deltas:   1% (6/596)
2021-07-26T13:04:16.4213527Z Resolving deltas:   2% (12/596)
2021-07-26T13:04:16.4222319Z Resolving deltas:   3% (18/596)
2021-07-26T13:04:16.4227155Z Resolving deltas:   4% (24/596)
2021-07-26T13:04:16.4230600Z Resolving deltas:   5% (30/596)
2021-07-26T13:04:16.4234831Z Resolving deltas:   6% (36/596)
2021-07-26T13:04:16.4238267Z Resolving deltas:   7% (42/596)
2021-07-26T13:04:16.4242103Z Resolving deltas:   8% (48/596)
2021-07-26T13:04:16.4244853Z Resolving deltas:   9% (54/596)
2021-07-26T13:04:16.4247975Z Resolving deltas:  10% (60/596)
2021-07-26T13:04:16.4251315Z Resolving deltas:  11% (66/596)
2021-07-26T13:04:16.4254615Z Resolving deltas:  12% (72/596)
2021-07-26T13:04:16.4257341Z Resolving deltas:  13% (78/596)
2021-07-26T13:04:16.4260368Z Resolving deltas:  14% (84/596)
2021-07-26T13:04:16.4263936Z Resolving deltas:  15% (90/596)
2021-07-26T13:04:16.4267264Z Resolving deltas:  16% (96/596)
2021-07-26T13:04:16.4273949Z Resolving deltas:  17% (102/596)
2021-07-26T13:04:16.4274413Z Resolving deltas:  18% (108/596)
2021-07-26T13:04:16.4274828Z Resolving deltas:  19% (114/596)
2021-07-26T13:04:16.4277602Z Resolving deltas:  20% (120/596)
2021-07-26T13:04:16.4280679Z Resolving deltas:  21% (126/596)
2021-07-26T13:04:16.4282927Z Resolving deltas:  22% (132/596)
2021-07-26T13:04:16.4285997Z Resolving deltas:  23% (138/596)
2021-07-26T13:04:16.4287823Z Resolving deltas:  24% (144/596)
2021-07-26T13:04:16.4290174Z Resolving deltas:  25% (149/596)
2021-07-26T13:04:16.4293121Z Resolving deltas:  26% (155/596)
2021-07-26T13:04:16.4296367Z Resolving deltas:  27% (161/596)
2021-07-26T13:04:16.4299209Z Resolving deltas:  28% (167/596)
2021-07-26T13:04:16.4302292Z Resolving deltas:  29% (173/596)
2021-07-26T13:04:16.4305077Z Resolving deltas:  30% (179/596)
2021-07-26T13:04:16.4311747Z Resolving deltas:  31% (185/596)
2021-07-26T13:04:16.4314037Z Resolving deltas:  32% (191/596)
2021-07-26T13:04:16.4315256Z Resolving deltas:  33% (197/596)
2021-07-26T13:04:16.4316410Z Resolving deltas:  34% (203/596)
2021-07-26T13:04:16.4317516Z Resolving deltas:  35% (209/596)
2021-07-26T13:04:16.4318634Z Resolving deltas:  36% (215/596)
2021-07-26T13:04:16.4319750Z Resolving deltas:  37% (221/596)
2021-07-26T13:04:16.4321182Z Resolving deltas:  38% (227/596)
2021-07-26T13:04:16.4324648Z Resolving deltas:  39% (233/596)
2021-07-26T13:04:16.4326370Z Resolving deltas:  40% (239/596)
2021-07-26T13:04:16.4327926Z Resolving deltas:  41% (245/596)
2021-07-26T13:04:16.4329309Z Resolving deltas:  42% (251/596)
2021-07-26T13:04:16.4330783Z Resolving deltas:  43% (257/596)
2021-07-26T13:04:16.4332861Z Resolving deltas:  44% (263/596)
2021-07-26T13:04:16.4334720Z Resolving deltas:  45% (269/596)
2021-07-26T13:04:16.4336231Z Resolving deltas:  46% (275/596)
2021-07-26T13:04:16.4337879Z Resolving deltas:  47% (281/596)
2021-07-26T13:04:16.4340287Z Resolving deltas:  48% (287/596)
2021-07-26T13:04:16.4343218Z Resolving deltas:  49% (293/596)
2021-07-26T13:04:16.4346587Z Resolving deltas:  50% (298/596)
2021-07-26T13:04:16.4351528Z Resolving deltas:  51% (304/596)
2021-07-26T13:04:16.4357236Z Resolving deltas:  52% (310/596)
2021-07-26T13:04:16.4363413Z Resolving deltas:  53% (316/596)
2021-07-26T13:04:16.4367132Z Resolving deltas:  54% (322/596)
2021-07-26T13:04:16.4371410Z Resolving deltas:  55% (328/596)
2021-07-26T13:04:16.4375295Z Resolving deltas:  56% (334/596)
2021-07-26T13:04:16.4381746Z Resolving deltas:  57% (340/596)
2021-07-26T13:04:16.4385432Z Resolving deltas:  58% (346/596)
2021-07-26T13:04:16.4387088Z Resolving deltas:  59% (352/596)
2021-07-26T13:04:16.4389591Z Resolving deltas:  60% (358/596)
2021-07-26T13:04:16.4391485Z Resolving deltas:  61% (364/596)
2021-07-26T13:04:16.4393720Z Resolving deltas:  62% (370/596)
2021-07-26T13:04:16.4396212Z Resolving deltas:  63% (376/596)
2021-07-26T13:04:16.4398218Z Resolving deltas:  64% (382/596)
2021-07-26T13:04:16.4400311Z Resolving deltas:  65% (388/596)
2021-07-26T13:04:16.4402519Z Resolving deltas:  66% (394/596)
2021-07-26T13:04:16.4404892Z Resolving deltas:  67% (400/596)
2021-07-26T13:04:16.4407225Z Resolving deltas:  68% (406/596)
2021-07-26T13:04:16.4409947Z Resolving deltas:  69% (412/596)
2021-07-26T13:04:16.4412262Z Resolving deltas:  70% (418/596)
2021-07-26T13:04:16.4414450Z Resolving deltas:  71% (424/596)
2021-07-26T13:04:16.4416625Z Resolving deltas:  72% (430/596)
2021-07-26T13:04:16.4419121Z Resolving deltas:  73% (436/596)
2021-07-26T13:04:16.4420903Z Resolving deltas:  74% (442/596)
2021-07-26T13:04:16.4423723Z Resolving deltas:  75% (447/596)
2021-07-26T13:04:16.4426576Z Resolving deltas:  76% (453/596)
2021-07-26T13:04:16.4428959Z Resolving deltas:  77% (459/596)
2021-07-26T13:04:16.4431243Z Resolving deltas:  78% (465/596)
2021-07-26T13:04:16.4433824Z Resolving deltas:  79% (471/596)
2021-07-26T13:04:16.4436782Z Resolving deltas:  80% (478/596)
2021-07-26T13:04:16.4440601Z Resolving deltas:  81% (483/596)
2021-07-26T13:04:16.4443216Z Resolving deltas:  82% (489/596)
2021-07-26T13:04:16.4446367Z Resolving deltas:  83% (495/596)
2021-07-26T13:04:16.4448734Z Resolving deltas:  84% (501/596)
2021-07-26T13:04:16.4451876Z Resolving deltas:  85% (507/596)
2021-07-26T13:04:16.4454394Z Resolving deltas:  86% (513/596)
2021-07-26T13:04:16.4457036Z Resolving deltas:  87% (519/596)
2021-07-26T13:04:16.4459233Z Resolving deltas:  88% (525/596)
2021-07-26T13:04:16.4460916Z Resolving deltas:  89% (531/596)
2021-07-26T13:04:16.4462089Z Resolving deltas:  90% (537/596)
2021-07-26T13:04:16.4463479Z Resolving deltas:  91% (543/596)
2021-07-26T13:04:16.4465899Z Resolving deltas:  92% (549/596)
2021-07-26T13:04:16.4469460Z Resolving deltas:  93% (555/596)
2021-07-26T13:04:16.4580443Z Resolving deltas:  94% (561/596)
2021-07-26T13:04:16.4581263Z Resolving deltas:  95% (567/596)
2021-07-26T13:04:16.4581812Z Resolving deltas:  96% (573/596)
2021-07-26T13:04:16.4582344Z Resolving deltas:  97% (579/596)
2021-07-26T13:04:16.4582842Z Resolving deltas:  98% (585/596)
2021-07-26T13:04:16.4583362Z Resolving deltas:  99% (591/596)
2021-07-26T13:04:16.4583860Z Resolving deltas: 100% (596/596)
2021-07-26T13:04:16.4584388Z Resolving deltas: 100% (596/596), done.
2021-07-26T13:04:16.4647621Z From https://github.com/devlynnsingley/i18n
2021-07-26T13:04:16.4649132Z  * [new ref]         31cdfed25009ae59eb8fd9c90490bf081ae2b0d4 -> pull/1176/merge
2021-07-26T13:04:16.4668028Z ##[endgroup]
2021-07-26T13:04:16.4668695Z ##[group]Determining the checkout info
2021-07-26T13:04:16.4675202Z ##[endgroup]
2021-07-26T13:04:16.4675782Z ##[group]Checking out the ref
2021-07-26T13:04:16.4676852Z [command]/usr/bin/git checkout --progress --force refs/remotes/pull/1176/merge
2021-07-26T13:04:16.6018802Z Note: switching to 'refs/remotes/pull/1176/merge'.
2021-07-26T13:04:16.6019267Z 
2021-07-26T13:04:16.6020084Z You are in 'detached HEAD' state. You can look around, make experimental
2021-07-26T13:04:16.6020935Z changes and commit them, and you can discard any commits you make in this
2021-07-26T13:04:16.6021737Z state without impacting any branches by switching back to a branch.
2021-07-26T13:04:16.6022225Z 
2021-07-26T13:04:16.6022767Z If you want to create a new branch to retain commits you create, you may
2021-07-26T13:04:16.6028435Z do so (now or later) by using -c with the switch command. Example:
2021-07-26T13:04:16.6028900Z 
2021-07-26T13:04:16.6029496Z   git switch -c <new-branch-name>
2021-07-26T13:04:16.6029872Z 
2021-07-26T13:04:16.6030294Z Or undo this operation with:
2021-07-26T13:04:16.6030623Z 
2021-07-26T13:04:16.6031088Z   git switch -
2021-07-26T13:04:16.6031364Z 
2021-07-26T13:04:16.6032013Z Turn off this advice by setting config variable advice.detachedHead to false
2021-07-26T13:04:16.6032580Z 
2021-07-26T13:04:16.6033541Z HEAD is now at 31cdfed Merge 7cad2da8df979981827c0554d1357dee9939ee8f into cb882bde753c54767d6f668bdf9db601594e2daf
2021-07-26T13:04:16.6035047Z ##[endgroup]
2021-07-26T13:04:16.6044845Z [command]/usr/bin/git log -1 --format='%H'
2021-07-26T13:04:16.6069069Z '31cdfed25009ae59eb8fd9c90490bf081ae2b0d4'
2021-07-26T13:04:16.6271077Z ##[group]Run actions/setup-node@v2.3.0
2021-07-26T13:04:16.6271508Z with:
2021-07-26T13:04:16.6271869Z   node-version: 12.x
2021-07-26T13:04:16.6272267Z   always-auth: false
2021-07-26T13:04:16.6272682Z   check-latest: false
2021-07-26T13:04:16.6273524Z   token: ***
2021-07-26T13:04:16.6273869Z ##[endgroup]
2021-07-26T13:04:16.7974857Z Found in cache @ /opt/hostedtoolcache/node/12.22.3/x64
2021-07-26T13:04:16.8180163Z ##[group]Run npm ci
2021-07-26T13:04:16.8180599Z [36;1mnpm ci[0m
2021-07-26T13:04:16.8222789Z shell: /usr/bin/bash -e {0}
2021-07-26T13:04:16.8223204Z ##[endgroup]
2021-07-26T13:04:33.4784197Z added 707 packages in 8.019s
2021-07-26T13:04:33.4957115Z ##[group]Run npm test
2021-07-26T13:04:33.4957558Z [36;1mnpm test[0m
2021-07-26T13:04:33.4996541Z shell: /usr/bin/bash -e {0}
2021-07-26T13:04:33.4996921Z env:
2021-07-26T13:04:33.4997346Z   NODE_OPTIONS: --max_old_space_size=4096
2021-07-26T13:04:33.4997763Z ##[endgroup]
2021-07-26T13:04:33.8174613Z 
2021-07-26T13:04:33.8176673Z > electron-i18n@0.0.0-development pretest /home/runner/work/i18n/i18n
2021-07-26T13:04:33.8177432Z > npm run build
2021-07-26T13:04:33.8177769Z 
2021-07-26T13:04:34.0936937Z 
2021-07-26T13:04:34.0939116Z > electron-i18n@0.0.0-development build /home/runner/work/i18n/i18n
2021-07-26T13:04:34.0940037Z > npm-run-all build:*
2021-07-26T13:04:34.0940449Z 
2021-07-26T13:04:34.4721643Z 
2021-07-26T13:04:34.4723972Z > electron-i18n@0.0.0-development build:stats /home/runner/work/i18n/i18n
2021-07-26T13:04:34.4725124Z > ts-node script/stats.ts
2021-07-26T13:04:34.4725631Z 
2021-07-26T13:04:38.2329872Z 
2021-07-26T13:04:38.2332621Z > electron-i18n@0.0.0-development build:module /home/runner/work/i18n/i18n
2021-07-26T13:04:38.2333648Z > ts-node script/build-module.ts
2021-07-26T13:04:38.2334021Z 
2021-07-26T13:04:40.5484395Z processing 584 blog files in 8 locales
2021-07-26T13:04:40.6462147Z parsed blogs in: 122.705ms
2021-07-26T13:04:40.9013515Z processing 1648 docs files in 8 locales
2021-07-26T13:04:59.1461096Z parsed docs in: 18259.957ms
2021-07-26T13:04:59.7396239Z 
2021-07-26T13:04:59.7398538Z > electron-i18n@0.0.0-development build:readme /home/runner/work/i18n/i18n
2021-07-26T13:04:59.7399467Z > ts-node script/readme.ts
2021-07-26T13:04:59.7399788Z 
2021-07-26T13:05:02.2113681Z Updated language list in readme.md
2021-07-26T13:05:02.4748557Z 
2021-07-26T13:05:02.4750844Z > electron-i18n@0.0.0-development build:wordcount /home/runner/work/i18n/i18n
2021-07-26T13:05:02.4752239Z > ts-node script/wordcount.ts > wordcount.md
2021-07-26T13:05:02.4752979Z 
2021-07-26T13:05:05.8104451Z 
2021-07-26T13:05:05.8106739Z > electron-i18n@0.0.0-development test /home/runner/work/i18n/i18n
2021-07-26T13:05:05.8108145Z > npm run test-only
2021-07-26T13:05:05.8108644Z 
2021-07-26T13:05:06.0582123Z 
2021-07-26T13:05:06.0584897Z > electron-i18n@0.0.0-development test-only /home/runner/work/i18n/i18n
2021-07-26T13:05:06.0586532Z > tsc && mocha && prettier --check "./**/*.{ts,js}" --write
2021-07-26T13:05:06.0587165Z 
2021-07-26T13:05:11.3531294Z 
2021-07-26T13:05:11.3535441Z 
2021-07-26T13:05:11.3542728Z   i18n.docs
2021-07-26T13:05:11.3564169Z     âœ“ is an object with locales as keys
2021-07-26T13:05:11.3568385Z     âœ“ is an object with docs objects as values
2021-07-26T13:05:11.3570844Z     âœ“ sets githubUrl on every doc
2021-07-26T13:05:11.3577374Z     âœ“ does not contain <html>, <head>, or <body> tag in compiled html
2021-07-26T13:05:11.3579115Z 
2021-07-26T13:05:11.3581409Z   i18n.blogs
2021-07-26T13:05:11.3586077Z     âœ“ is an object with locales as keys
2021-07-26T13:05:11.3589650Z     âœ“ is an object with blogs objects as values
2021-07-26T13:05:11.3590315Z 
2021-07-26T13:05:11.3591005Z   i18n.glossary
2021-07-26T13:05:11.3595048Z     âœ“ is an object with locales as keys
2021-07-26T13:05:11.3597783Z     âœ“ contains localized glossary objects
2021-07-26T13:05:11.3602386Z     âœ“ sets expected properties on every entry
2021-07-26T13:05:11.3604161Z 
2021-07-26T13:05:11.3605860Z   i18n.website
2021-07-26T13:05:11.3608264Z     âœ“ is an object with locales as keys
2021-07-26T13:05:11.3611775Z     âœ“ contains localized strings
2021-07-26T13:05:11.3612148Z 
2021-07-26T13:05:11.3612506Z   API Docs
2021-07-26T13:05:11.3625166Z     âœ“ has a title for every doc
2021-07-26T13:05:11.3626251Z     âœ“ derives title from the first H1 or H2
2021-07-26T13:05:11.3632227Z     âœ“ includes all expected properties
2021-07-26T13:05:11.3635286Z     âœ“ trims API descriptions
2021-07-26T13:05:11.3663948Z     âœ“ sorts docs by slug per locale
2021-07-26T13:05:11.4678649Z     âœ“ fixes relative links in docs (101ms)
2021-07-26T13:05:11.4778366Z     âœ“ fixes relative images in docs
2021-07-26T13:05:11.9513954Z     âœ“ contains no empty links (473ms)
2021-07-26T13:05:11.9515090Z 
2021-07-26T13:05:11.9515662Z   API Structures
2021-07-26T13:05:11.9516676Z     âœ“ includes all expected properties
2021-07-26T13:05:11.9532071Z     1) sets expected crowdinFileId
2021-07-26T13:05:11.9532740Z 
2021-07-26T13:05:11.9533272Z   i18n.locales
2021-07-26T13:05:11.9536410Z     âœ“ is an object with locales as keys
2021-07-26T13:05:11.9540678Z     âœ“ includes countryCode for every locale
2021-07-26T13:05:11.9546381Z     âœ“ includes countryName for every locale
2021-07-26T13:05:11.9550789Z     âœ“ includes languageCode for every locale
2021-07-26T13:05:11.9554964Z     âœ“ includes languageName for every locale
2021-07-26T13:05:11.9556605Z     âœ“ sets some custom language names
2021-07-26T13:05:11.9576443Z     âœ“ includes languageNativeName for every locale
2021-07-26T13:05:11.9577531Z     âœ“ includes stats for every locale
2021-07-26T13:05:11.9578460Z     âœ“ sorts locales by translation progress
2021-07-26T13:05:11.9578988Z 
2021-07-26T13:05:11.9579726Z   i18n.electronLatestStableTag
2021-07-26T13:05:11.9581673Z     âœ“ exists
2021-07-26T13:05:11.9582368Z     âœ“ is a tag name
2021-07-26T13:05:11.9582743Z 
2021-07-26T13:05:11.9583179Z   i18n.date
2021-07-26T13:05:11.9583770Z     âœ“ exists
2021-07-26T13:05:11.9584378Z     âœ“ is a date
2021-07-26T13:05:11.9584938Z 
2021-07-26T13:05:11.9587130Z 
2021-07-26T13:05:11.9588151Z   33 passing (606ms)
2021-07-26T13:05:11.9588655Z   1 failing
2021-07-26T13:05:11.9588990Z 
2021-07-26T13:05:11.9604071Z   1) API Structures
2021-07-26T13:05:11.9604802Z        sets expected crowdinFileId:
2021-07-26T13:05:11.9605269Z 
2021-07-26T13:05:11.9606225Z       AssertionError: expected '256439' to equal '250646'
2021-07-26T13:05:11.9607040Z       + expected - actual
2021-07-26T13:05:11.9607433Z 
2021-07-26T13:05:11.9607967Z       -256439
2021-07-26T13:05:11.9608385Z       +250646
2021-07-26T13:05:11.9608789Z       
2021-07-26T13:05:11.9609355Z       at Context.<anonymous> (test/index.js:208:30)
2021-07-26T13:05:11.9610179Z       at processImmediate (internal/timers.js:461:21)
2021-07-26T13:05:11.9610692Z 
2021-07-26T13:05:11.9610996Z 
2021-07-26T13:05:11.9611287Z 
2021-07-26T13:05:11.9759453Z npm ERR! code ELIFECYCLE
2021-07-26T13:05:11.9760463Z npm ERR! errno 1
2021-07-26T13:05:11.9792120Z npm ERR! electron-i18n@0.0.0-development test-only: `tsc && mocha && prettier --check "./**/*.{ts,js}" --write`
2021-07-26T13:05:11.9793178Z npm ERR! Exit status 1
2021-07-26T13:05:11.9793922Z npm ERR! 
2021-07-26T13:05:11.9795038Z npm ERR! Failed at the electron-i18n@0.0.0-development test-only script.
2021-07-26T13:05:11.9796890Z npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
2021-07-26T13:05:11.9923427Z 
2021-07-26T13:05:11.9926436Z npm ERR! A complete log of this run can be found in:
2021-07-26T13:05:11.9942919Z npm ERR!     /home/runner/.npm/_logs/2021-07-26T13_05_11_983Z-debug.log
2021-07-26T13:05:12.0014788Z npm ERR! Test failed.  See above for more details.
2021-07-26T13:05:12.0047901Z ##[error]Process completed with exit code 1.
2021-07-26T13:05:12.0199755Z Post job cleanup.
2021-07-26T13:05:12.1276704Z [command]/usr/bin/git version
2021-07-26T13:05:12.1334872Z git version 2.32.0
2021-07-26T13:05:12.1374085Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2021-07-26T13:05:12.1406028Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2021-07-26T13:05:12.1617897Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2021-07-26T13:05:12.1635308Z http.https://github.com/.extraheader
2021-07-26T13:05:12.1641932Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2021-07-26T13:05:12.1673816Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2021-07-26T13:05:12.1925093Z Cleaning up orphan processes"
 content://media/external/file/59980#:~:text=2021-07-26T13,up%20orphan%20processes
