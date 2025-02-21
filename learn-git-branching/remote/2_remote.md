# Learn Git Branching

# Level 1: Advanced Git Remotes!

## Task 1

```
1. git checkout main
2. git pull
3. git checkout side1
4. git rebase main
5. git checkout side2
6. git rebase side1
7. git checkout side3
8. git rebase side2
9. git checkout main
10. git rebase side3
11 git push
```

![alt text](9.png)


## Task 2
```
1. git checkout main
2. git pull
3. git merge side1
4. git merge side2
5. git merge side3
6. git push
```

![alt text](10.png)


## Task 3
```
1. git checkout -b side o/main
2. git commit
3. git pull --rebase
4. git push
```

![alt text](11.png)

## Task 4
```
1. git push origin main
2. git push origin foo
```

![alt text](12.png)

## Task 5
```
1. git push origin main~1:foo
2. git push origin foo:main
```

![alt text](13.png)

## Task 6
```
1. git fetch origin C3:foo
2. git fetch origin C6:main
3. git merge main
4. git checkout foo
5. git fmerge main
```

![alt text](14.png)

## Task 7
```
1. git push origin :foo
2. git push origin :bar
```
![alt text](15.png)

## Task 8
```
1. git pull origin C3:foo
2. git pusll origin C2:side
```

![alt text](16.png)

# Task Completion

![alt text]({11BBDB87-BEA4-4C24-BEB9-18162769E6D2}.png)