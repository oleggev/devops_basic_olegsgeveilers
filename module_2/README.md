# Atbildes Modulis 2

**Nr. 13**
HASH neatšķirās.

**Nr. 16 (komentārs - atbildē noradīti tikai daži ieraksti jo reāli ir daudz Commit)**
```
git log --pretty="%h - %s" --since=1.week
```
```
2563bf3f9 - feat: support local preview, post split; add deploy preview (#30814)
7d51ba511 - Merge pull request #30862 from hashicorp/update-TF-WORKSPACE-variable
7b6dfabb7 - Merge pull request #30906 from hashicorp/jbardin/races
e68ad5ec4 - more edits
912e6ff6d - Apply suggestions from PR review
a0ebb94fb - Merge branch 'main' into update-TF-WORKSPACE-variable
2f7aa2fcb - Merge pull request #30905 from hashicorp/sebasslash/rename-env-vars
0693c8dfe - enable the race detector in tests
0731213ec - sync retry goroutine return
c52e3ed37 - test fixture race
0fe38fba6 - prevent unsynchronized output changes access
f63ef2b5e - Rename cloud env vars to use TF_CLOUD prefix
d3e660d91 - Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions
b1d933936 - Final formatting nits
eb2724d37 - Update CHANGELOG.md
d4776e8ef - lang/funcs: type conversion functions can convert null values
```
```
git log --pretty="%h - %s" --since=1.week --stat
```
```
2563bf3f9 - feat: support local preview, post split; add deploy preview (#30814)

 Makefile                                         |  42 +-
 website/img/docs/graph-example.png               | Bin 0 -> 27282 bytes
 website/img/docs/in-progress-apply.png           | Bin 0 -> 236223 bytes
 website/img/docs/intro-terraform-apis.png        | Bin 0 -> 115073 bytes
 website/img/docs/intro-terraform-workflow.png    | Bin 0 -> 370543 bytes
 website/img/docs/manually-pasted-plan-output.png | Bin 0 -> 73336 bytes
 website/img/docs/plan-comments.png               | Bin 0 -> 245820 bytes
 website/img/docs/pr-plan.png                     | Bin 0 -> 197934 bytes
 website/img/docs/program-steps.png               | Bin 0 -> 131234 bytes
 website/img/docs/pull-request.png                | Bin 0 -> 108925 bytes
 website/img/docs/verified-card.png               | Bin 0 -> 242416 bytes
 website/package-lock.json                        | 608 +++++++++++++++++++++++
 website/package.json                             |  13 +
 website/scripts/website-build.sh                 |  39 ++
 14 files changed, 690 insertions(+), 12 deletions(-)
7d51ba511 - Merge pull request #30862 from hashicorp/update-TF-WORKSPACE-variable
7b6dfabb7 - Merge pull request #30906 from hashicorp/jbardin/races
e68ad5ec4 - more edits

 website/docs/cli/cloud/settings.mdx | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
912e6ff6d - Apply suggestions from PR review
```
**Nr. 17 (komentārs - atbildē noradīti tikai daži ieraksti jo reāli ir daudz Commit ko uztaisīja autors)**
```
git log --pretty="%h - %s" --author='Laura Pacilio'
```
```
e68ad5ec4 - more edits
912e6ff6d - Apply suggestions from PR review
a0ebb94fb - Merge branch 'main' into update-TF-WORKSPACE-variable
d3e660d91 - Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions
b1d933936 - Final formatting nits
3c7c5bbd2 - add links to function and expressions; move result types back to conditionals page (oops)
2a206c798 - fix incorrect HCL syntax for example
7a43db405 - Add link to operators page and all out other types
ba3bb5ad5 - Apply suggestions from PR review
686dbcdb8 - fix confusing sentence on lifecycle page
```
**Nr. 18** 
```
git log --pretty="%h - %s" --author='Laura Pacilio' --since="2021-09-01" --before="2021-09-31"
```
```
8f09e2759 - Merge pull request #29567 from drasko95/patch-1
dfbef12a6 - Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar
a8e5b6a4a - Fix alphabetical order of sidebar
4d1baacea - Add Machine-Readable UI to sidebar and add hyphen :-)
dcf2d3c1e - Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key
43f960b19 - Merge pull request #28579 from ChadBailey/patch-2
48768a003 - Merge pull request #29451 from kmadof/patch-1
a819d7db3 - Merge pull request #29502 from hashicorp/alisdair/json-format-version
3c518880d - Merge pull request #29509 from drewmullen/d-module-source-revision-option
1e1d47d16 - Merge pull request #28345 from yvespp/destroy_provisioners_doc
73a3bb270 - Merge pull request #28334 from paultyng/patch-1
```
**Nr. 19**
```
git log --author='Laura Pacilio' --since="2022-04-21" 
```
Rezultāts tukšs.

## Autors

- Olegs G.  [oleggev/devops_basic_olegsgeveilers](https://github.com/oleggev/devops_basic_olegsgeveilers)