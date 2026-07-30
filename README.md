Hugo PaperMod 模板
如何使用本模板
点击上方使用此模板（Use this template）按钮，基于模板新建代码仓库，将仓库命名为<你的仓库名称>。务必勾选「包含所有分支（Include all branches）」选项。
修改 config.yml 文件中的 baseURL，填写你的网站地址，示例：https://<你的GitHub用户名>.github.io/<你的仓库名称>
进入仓库设置开启 GitHub Pages：设置(Settings) → Pages → 来源(Source)：从分支部署(Deploy from a branch) → 分支(Branch)：gh_pages → 文件夹(Folder)：/root → 保存(Save)。
4.（可选）在 content 文件夹内新建 Markdown 文件，用来撰写文章内容。
5.（可选）提交修改并推送代码至远程仓库。
完成！你的站点将会上线，访问地址：https://<你的GitHub用户名>.github.io/<你的仓库名称>
注意事项
如果你推送代码时遇到报错：remote: Permission to xxx denied to github-actions[bot].
代表 GitHub Actions 机器人权限不足，请按以下步骤开启权限：
设置(Settings) → Actions → 通用(General) → 工作流权限(Workflow permissions) → 读写权限(Read and write permissions) → 保存(Save)
