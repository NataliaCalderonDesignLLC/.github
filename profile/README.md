# NataliaCalderonDesignLLC

![NC Design Logo](../attachments/nc-design-logo-full.png)

Private Github organization

## Workflow

> [!IMPORTANT]  
> Before starting any code changes ensure you're not on `main` branch.

Create a branch off of `main` by running the following command:

```bash
git checkout -b <my-branch>
```

> [!TIP]
> Once you have a branch you can push the branch, create a PR and keep making commits. The PR will keep track of all the commits and you can continously save your work without affecting `main`. Push your changes often so that you don't lose your work in the event of an accidental dataloss incident.

Once you're ready to merge your changes into `main` branch go ahead and merge the PR. Once the PR is merged you will need to run the following commands locally:

* **Switch back to main branch**

```bash
git switch main
```

* **Pull latest changes**

```bash
git pull
```

* **Tag your `main` branch with latest version**

```bash
git tag v0.X.X
```

* **Push tags**

```bash
git push --tags
```

> [!IMPORTANT]  
> Don't forget to cleanup leftover branches that have already been merged

## Cleanup

To cleanup and/or view any local branches run:

```bash
git branch
```

> [!CAUTION]
> Never delete `main` branch.

```bash
git branch -D <my-branch>
```

## Templates

Alerts are an extension of Markdown used to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the importance of the content.

> [!NOTE]  
> [Source](https://github.com/orgs/community/discussions/16925)

```text
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

Formated in markdown:

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

## Sources

* [Semantic Versioning](https://semver.org/)
