# Module-of-gitterChat-ex2

notice:
- everytime: clear cookie

 v12-1-(way2) &  v12-1-(way3)   & v11-1-(way2)  ---github has bug(sometimes could run,sometimes not)

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
- Version v11-1-(way2)-----with 1 layer  of module (CPS)--checked-success  [output](https://i.imgur.com/ILMrzJT.png) 

#### (3) way3:  CPS + foreach 
- Version v11-0-(way3)---[output](https://i.imgur.com/RfqIDBk.png) & [finalCode in repo---de2](https://github.com/kiecoo/de2/tree/ce942f41b5b6e2fb94b9e1e970c4b66e772a6e17) `based on  v11-0-(way2)`
> [how to print people instead 1-person by foreach](https://github.com/kiecoo/de2/commit/b93fcaca3536f4d22eb90b168f80ba3f64a8df6c#diff-eacf331f0ffc35d4b482f1d15a887d3b)--(success in apple,fail in windows)

### 【v12】:`gitterChat` + `flipCard`(+module from get-github-activity-feed)
#### (1) way1:
- (failed) Version v12-1---with 1 layer  of module  (print 1 person)
>>>  (html:copy Version v11-1,    js: get-github-activity-feed)


#### (2) way2:  CPS        1 person
- Version v12-1-(way2)--1 person (checked-success)  [output](https://i.imgur.com/NqD3Rg4.png)
>>> - html: all =  `v11-1-(way2)` 
>>> - js : [js-----get-github-activity-feed](https://github.com/kiecoo/get-github-activity-feed/blob/master/index.js) (whole)+  `v11-1-(way2)` (some)  [how](https://github.com/kiecoo/module-gitterChat---ex2/commit/bbc28050ff5373616fc4838e62728296ac50f47a) : nomal(js)->CPS(js)
- Version v12-1-(way2)-----with 1 layer  of module (CPS)***(success but username couldn't be inputted (apple:success,windows:fail)-not pasted yet)***  [repo----de--v12-1-way3](https://github.com/kiecoo/de--v12-1-way3)   [output](https://i.imgur.com/GU03dnu.png)

#### (3) way3:  CPS + foreach 
- Version v12-1-(way3)--------------(x:checked-success wihtout clear cookie)   [output](https://i.imgur.com/yqy8eEq.png)
>>> - html: `v12-1-(way2)`(whole) +  editted as `how to print people instead 1-person by foreach` of `v11-0-(way3)`
>>> - js : all = `v12-1-(way2)`
- Version v12-1-way2- ----with 1 layer  of module  (checked-success) (sometimes show  2 person  [output1](https://i.imgur.com/94a3HIL.png) , next moment when refreshing shows 3 people [output2](https://i.imgur.com/wi83AvE.png) ) [repo-de1](https://github.com/kiecoo/de1) 
>>> -  difference from v12-1: (html:Version v11-1 + some of  get-github-activity-feed    js:same)
>>>  - [comparison-sheet](https://github.com/kiecoo/module-gitterChat---ex2/commit/28bbff649d69620a97be2f4c281addc5360ab503#diff-eacf331f0ffc35d4b482f1d15a887d3b)  between v12-1&2 in github

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




