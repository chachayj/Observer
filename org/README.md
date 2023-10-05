# Observer, chacha's toy project

## Running tasks

npx nx build is-even (test)

npx nx build is-odd (test)

npx nx run-many -t build (test)

```
nx <target> <project> <...options>
```

You can also run multiple targets:

```
nx run-many -t <target1> <target2>
```

..or add `-p` to filter specific projects

```
nx run-many -t <target1> <target2> -p <proj1> <proj2>
```