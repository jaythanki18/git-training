# Learn-Git_Branching

# Level 1: Introduction Sequence

## Task 1
* git commit

![alt text]({89952C7E-212D-46B4-835B-008BA3742CB4}.png)

## Task 2
* git checkout -b bugFix

![alt text]({18E780F8-2C83-4DCC-BD54-05CF37B1BB4F}.png)


## TASK 3
* git checkout -b bugFix
* git commit
* git checkout main
* git commit
* git merge bugfix

![alt text]({E3CA5379-281D-4CEB-A5E0-372983BC71B4}.png)

## Task 4
* git checkout -b bugfix
* git commit
* git checkout main
* git commit
* git chekout bugfix
* git rebase main

![alt text]({C1FCB315-B5D7-4FBF-AB2C-FB2CB092F5C3}.png)


# Level 2: Ramping up

## Task 1

* git checkout c4
![alt text]({653E8A3D-102D-450B-B51F-A3A67FEB24DB}.png)

## Task 2
* git checkout c4
* git checkout c4^

![alt text]({4233E050-48BC-4A24-9F20-8A680426A86D}.png)

## Task 3
* git checkout C2~1
* git branch -f main C6
* git branch -f bugFix C1~1

![alt text]({995F4DD2-7B38-4D32-89E5-EDC4C5E9521D}.png)

## Task 4
* git reset C3^
* git checkout pushed
* git revert C2

![alt text]({51E5D8E2-611D-42B9-BDC3-18D836D71560}.png)

# Level 3: Moving work around

## Task1
* git cherry-pick C3 C4 C7

![alt text]({518FCC72-F60A-48C8-919B-448D425A34B0}.png)

## Task 2
* git rebase -i C5~4

![alt text]({96FB24E7-68B8-435B-B975-70FE0D097DBA}.png)

# Level 4: A Mixed bag

## Task 1

* git checkout main
* git cherry-pick C4 

![alt text]({BDEEA128-C924-4B5E-8AFA-CCBB01E2791C}.png)

## Task 2
* git rebase -i HEAD~2
* git commit --amend
* git rebase -i HEAD~2
* git checkout main
* gt merge caption

![alt text]({60B5ADC9-4A90-4A80-96CF-F8EB602F3E06}.png)

## Task 3

* git checkout main
* git cherry-pick C2
* git commit --amend
* git cherry-pick C3

![alt text]({8F5AE43F-9514-4040-AEDE-74BF1C3A9CD3}.png)

## Task 4

* git tag v0 C1
* git tag v1 C2 
* git checkout C2 

![alt text]({3C7E90CC-CBBE-4DBC-A83E-BADDD0BEF2A1}.png)

## Task 5

* git describe C1
* git checkout C6
* git checkout bugFix
* git commit

![alt text]({6156CAB0-EFDF-46AE-AD7E-CD7E100F3556}.png)

# Level 5: Advanced topics

## Task 1

* git rebase bugFix
* git rebase main bugFix
* git rebase bugFix side
* git rebase side another
* git rebase another main

![alt text]({56A197FD-40CF-4D8D-A983-7E6477FA45B1}.png)

## Task 2

* git branch bugWork main~^2~

![alt text]({D06E3EE3-F4D6-469B-9EAD-D86762A93632}.png)

## Task 3
* git checkout one
* git cherry-pick C4 C3 C2
* git checkout two
* git cherry-pick C5 C4 C3 C2
* git branch -f three C2 

![alt text]({3FD61AC4-EF61-47EF-83AD-C52AF26D2606}.png)

# All git task completed
![alt text]({35DBA601-9D46-4F10-AC0E-E6F116AB118A}.png)