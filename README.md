# `gh team-add` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension for bulk register members to a github team

## Installation

```
gh extension install gh-cli-for-education/gh-team-add
```

## Usage

```
✗ gh team-add -h

1. Set the alias:

    cd:                            !gh config set current-org  2>/dev/null
    pwd:                           !gh config get current-org
   
   Example:
      ✗ gh pwd                   
      ULL-ESIT-DMSI-1920
2. Get the teams:

        ✗ gh org-teams | jq '.name'
        all
        antonella-garcia-alu0101227610
        casiano-rodriguez-leon-casiano
        Jaime-Simeón-Palomar-Blumenthal-alu0101228587
        jaime-simeon-palomar-blumenthal-alu0101228587
        JaimeSimeonPalomarBlumenthal
        laura-manzini-alu0101531700
        sergio-pitti-alu0101232812
        teresaBonet

3. List the names of the users you want to add to the target team

  gh team-add [-t team ] member1 member2 member3 ...
``` 

