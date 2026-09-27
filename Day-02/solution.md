# Day 02 Solutions

## Task 1: Check your present working directory

### Command

```bash
pwd
```

### Output

```text
/home/dinesh/Desktop/90-days-of-devops/Day-02
```

**Screenshot:**

![PWD](../assets/day02/pwd.png)

---

## Task 2: List all files/directories including hidden files

### Command

```bash
ls -a
```

### Output

```text
.  ..  README.md  solution.md
```

**Screenshot:**

![ls -a](../assets/day02/ls-a.png)

---

## Task 3: Create a nested directory A/B/C/D/E

### Commands

```bash
mkdir A
cd A
mkdir B
cd B
mkdir C
cd C
mkdir D
cd D
mkdir E
```

### Alternative (Recommended)

```bash
mkdir -p A/B/C/D/E
```
