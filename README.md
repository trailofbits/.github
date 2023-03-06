.github
=======

Public shared workflow templates and reusable workflows for Trail of Bits.
You can find our public profile and repositories at https://github.com/trailofbits/.

## .github/workflows

Github Actions [reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows).

You can call these workflows from a workflow in your repo like:

```yaml
jobs:
  lint:
    uses: trailofbits/.github/.github/workflows/lint.yml@v0.1.0
```

## workflow-templates

Github Actions templates you can use from your repo -> Actions -> New workflow

Learn more about [creating starter workflows](https://docs.github.com/en/actions/using-workflows/creating-starter-workflows-for-your-organization) and [using starter workflows](https://docs.github.com/en/actions/using-workflows/using-starter-workflows)

This is an example of using our pip-audit starter workflow:
<img width="966" alt="image" src="https://user-images.githubusercontent.com/12104969/223135447-5128b4ed-c9d2-44cf-80c6-1395a555edde.png">

## profile

Our [Github organization's](https://github.com/trailofbits) public profile.
