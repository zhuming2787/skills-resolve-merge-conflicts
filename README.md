<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

[English](https://github.com/skills/resolve-merge-conflicts) | 中文

> 本课程翻译自 Github Skills，全部课程请点击 [这里查看](https://www.github-zh.com/getting-started)

# 解决合并冲突

_了解为什么会产生冲突，以及如何正确地解决它们。_

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: 解决合并冲突

_现在我们来深入看看合并冲突是怎么回事吧! :mag:_

第一次看到合并冲突时可能会令人生畏，但不用担心，Git 在处理冲突时比你想象的聪明。它只是在某些情况下需要人工干预，告诉它该保留哪些内容、该舍弃哪些。
有时我们需要将两个分支的内容都合并在一起，有时候你可能需要完全重写一个版本。这就是为什么需要人来查看冲突内容，并做出正确修改。

### :keyboard: 实操环节: 解决合并冲突

1. 打开你刚刚创建的 Pull Request，我们已经为你准备好了一个冲突示例。别慌，这正是练习的重点！
2. 在页面底部的提示区域中，找到 “This branch has conflicts that must be resolved” 字样，然后点击 **Resolve conflicts** 按钮。
3. 你会看到一些高亮的标记区域，冲突部分会以 `<<<<<<< my-resume` 开头，以 `>>>>>>> main` 结尾。这些标记是 Git 自动加上的，用来告诉你两边的代码哪里有冲突。
4. 删除 main 分支中的修改内容，也就是删除 `=======` 下面、`>>>>>>> main` 上面的所有内容。
5. 接着，把下面几行合并标记也删掉：

   ```
   <<<<<<< my-resume
   =======
   >>>>>>> main
   ```
6. 删除完冲突标记后，点击 **Mark as resolved**。
7. 最后，点击 **Commit merge**。
8. 等待大约 20 秒后，刷新当前页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动识别进度并进入下一步。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/resolve-merge-conflicts) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
