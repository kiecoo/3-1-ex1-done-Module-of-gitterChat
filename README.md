# Module-of-gitterChat-ex2
>- ex2 : after being combined inside flip-card module
>- No. : 3-1-ex2:【success】

## rule of name
Version-`No. Of Topic`-`Module`-(`Style`)
>ex.  Version v11-1-(way2)
>* v11 = No. Of Topic
>* -1 =  with 1 layer  of module
>* way2 = CPS style-callback

##  contents
>in branches

### 【v0-v9】:`gitterChat` + `flipCard`
- Version v0---with 0 module
- Version v1---with 1 layer  of module
- Version v2---with 2 layers of module
- Version v3---with 3 layers of module

### 【v11】:`gitterChat` + `flipCard`(+json_usernames)
#### (1) way1:
- Version v11-0------------with 0 module
- Version v11-1------------with 1 layer  of module  ***failed, fail to debug ****
#### (2) way2:  CPS style:callback
- Version v11-0-(way2)-----with 0 layer  of module (CPS)-ok  [output](https://i.imgur.com/ILMrzJT.png)  [repo----userprofiles](https://github.com/kiecoo/userprofiles)
- Version v11-1-(way2)-----with 1 layer  of module (CPS)-ok  [output](https://i.imgur.com/ILMrzJT.png)  [repo---de-try](https://github.com/kiecoo/de-try)

### 【v12】:`gitterChat` + `flipCard`(+module from get-github-activity-feed)
#### (1) way1:
- (failed) Version v12-1---with 1 layer  of module  (print 1 person)
>>>  (html:copy Version v11-1,    js: get-github-activity-feed)
- Version v12-1-way2- ----with 1 layer  of module  (checked-success)  [output1](https://i.imgur.com/1XtzgDi.png)  [repo-de1](https://github.com/kiecoo/de1)   (print 3 people)
>>> -  difference from v12-1: (html:Version v11-1 + some of  get-github-activity-feed    js:same)
>>>  - [comparison-sheet](https://github.com/kiecoo/module-gitterChat---ex2/commit/28bbff649d69620a97be2f4c281addc5360ab503#diff-eacf331f0ffc35d4b482f1d15a887d3b)  between v12-1&2 in github
#### (2) way2:  CPS style:callback
- Version v12-1-(way2)-----with 1 layer  of module (CPS)***(success but username couldn't be inputted (apple:success,windows:fail)-not pasted yet)***  [repo----de--v12-1-way3](https://github.com/kiecoo/de--v12-1-way3)

### 【v13】:`gitterChat` + `flipCard`+`github-data`
- (failed) Version v13-1---with 1 layer  of module    [repo---de-for-testingOutput](https://github.com/kiecoo/de-for-testingOutput)
>>> html: 12-1-way2-success , js: `github-data`


- (not yet)Version v101---json of `github-data` inputted (`get-github-data.js` added)
- (not yet)Version v102---function of `github-data` inputted

-----
ps-- success-print-names
(already written again in github)

(failed)unknown why wrong-versionOld
(success) 12-1-test2-editted name-wrong  [versionNew](https://github.com/kiecoo/de-for-testingOutput)& [output](https://i.imgur.com/mqrEPg6.png)

