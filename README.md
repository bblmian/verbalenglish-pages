# verbalenglish-pages

「口语练习」（Verbal English Practice）iOS App 的公开页面。

| 页面 | 地址 | 用途 |
|---|---|---|
| `index.html` | <https://bblmian.github.io/verbalenglish-pages/> | **隐私政策**（中英双语）。App Store Connect 的 Privacy Policy URL 填这个 |
| `support.html` | <https://bblmian.github.io/verbalenglish-pages/support.html> | **支持页**（中英双语，30+ 条问答）。App Store Connect 的 **Support URL** 填这个；App 内「我的 → 联系与支持」也点开它 |

## 🔴 怎么改

**不要直接改这个仓库。** 正本在主仓库 `bblmian/VerbalEnglishPracticeApp` 的
`Product/privacy-policy/`（两个页面都在那里），改那边、再拷过来推，否则两份会分叉。
推之前在主仓库跑 `Scripts/page_check.sh`（真 WebKit 量几何 + 相对链接），
推之后 `curl` 两个地址到 **200** 才算上线 —— push 成功只说明 GitHub 收到了。

改动实质内容（新增接收数据的第三方、新增数据类型）时，记得同时更新页面顶部的「最后更新」日期，
并在 App 内再次征求同意 —— 政策第七节就是这么写的。

同一个开发者的另一个 App 的同类仓库：`bblmian/wisetodo-pages`。
